---
layout: default
title:  The 12th Workshop on Formal Reasoning in Distributed Algorithms
---

<style>
.talk {
  margin-bottom: 1.5rem;  /* Add space after each talk block */
}

.talk > summary {
  cursor: pointer;
  list-style: none;
  display: block;
  margin-top: 0;
}

.slot + .talk > summary { margin-top: .25rem; }  /* small, safe tightening */

.talk > summary::-webkit-details-marker { 
  display: none; 
}


/* Hide the default "Click to see abstract" text */
.summary-hint {
  display: none;
}

/* Show "Reveal abstract" by default */
.talk > summary::after {
  content: "Reveal abstract";
  display: inline-block;
  color: #666;
  font-weight: normal;
  font-size: 0.85em;
  font-style: italic;
}
/* Show "Hide abstract" when expanded */
.talk[open] > summary::after {
  content: "Hide abstract";
}

/* Optional: Add some styling when the details are open */
.talk[open] > summary {
  margin-bottom: 0.5rem;
}

.talk[open] {
  margin-bottom: 2rem;  /* More space when abstract is shown */
}

h2 {
  border-bottom: 2px solid #e1e4e8;
  padding-bottom: 0.5rem;
  margin-top: 2.5rem;
  margin-bottom: 1.5rem;
}

/* Info boxes for important dates/details */
.info-box {
  background: #f6f8fa;
  border-left: 4px solid #667eea;
  padding: 1rem;
  margin: 1.5rem 0;
  border-radius: 4px;
}

.info-box strong {
  color: #667eea;
}

.session {
  background: #fafbfc;
  border: 1px solid #e1e4e8;
  border-left: 5px solid #667eea;
  border-radius: 6px;
  padding: 0.75rem 1rem;
  margin: 1.25rem 0;
}
.session-header {
  font-weight: 600;
  color: #2f3747;
  margin-bottom: 0.5rem;
  display: flex;
  flex-wrap: wrap;
  gap: .5rem;
  align-items: baseline;
}
.session-time {
  color: #6a737d;
  font-size: 0.9em;
}
.break {
  background: #fffdf2;
  border: 1px dashed #e3b341;
  color: #6b5800;
  padding: .5rem .75rem;
  border-radius: 6px;
  margin: 1rem 0;
}
.break.lunch {
  background: #fff6f6;
  border-color: #f0aaaa;
  color: #7a2d2d;
}
.slot {
  margin: .35rem 0 .75rem;
}
.slot + .talk { margin-top: -.25rem; } /* pulls abstract toggle closer */
</style>

# The 12th Workshop on Formal Reasoning in Distributed Algorithms


<div class="info-box">
  <strong>📅 Date:</strong> Monday, October 27, 2025 (whole-day workshop)<br>
  <strong>📍 Location:</strong> Berlin, Germany<br>
  <strong>🔗 Co-located with:</strong> <a href="https://www.disc-conference.org/wp/disc2025/">DISC 2025</a><br>
</div>

## About FRIDA

The FRIDA workshop aims to foster collaboration between the distributed algorithms and formal-methods communities. This workshop provides a forum for researchers to present recent advances in formal reasoning about distributed algorithms and systems, share experiences, and discuss future directions.

To attend, please [register on the DISC 2025 website](https://www.disc-conference.org/wp/disc2025/registration/).

FRIDA 2025 is organized by:
- [Giuliano Losa](https://www.losa.fr/) (giuliano@stellar.org), Stellar Development Foundation
- [Stephan Merz](https://members.loria.fr/Stephan.Merz/) (stephan.merz@loria.fr), INRIA Nancy & LORIA

## Tentative Schedule

<!-- NOTE indenting HTML breaks everything; don't do it -->

<div class="session">
<div class="session-header">
Session 1 — Morning I
<span class="session-time">09:30–10:30</span>
</div>

<div class="slot">09:30–10:10 — <strong><a href="https://www.cs.ox.ac.uk/people/bill.roscoe/">Bill Roscoe</a></strong>, Oxford University and University College Oxford Blockchain Research Centre, “Stochastic reasoning in decentralised systems”</div>
<details class="talk">
<summary><span class="summary-hint">Click to see abstract</span></summary>
<div markdown="1">
Where the number of trials of a mechanism is bounded, it is sensible to engineer that mechanism to have such a small probability ϵ of failure that over all time we can discount the probability δ of it ever going wrong. So if there are at most 10⁹ trials and we are prepared to accept a δ=10⁻⁹ probability of failure over all time, this would suggest ϵ=10⁻¹⁸. If a blockchain has a good source of random numbers, this allows us to create many efficient mechanisms, including consensus, that are stochastically certain to work. A number of interesting challenges in formal reasoning arise.
</div>
</details>

<div class="slot">10:10–10:30 — <strong><a href="https://informatics.tuwien.ac.at/">Ivana Bocevska</a></strong>, TU Wien, “Automated Game-Theoretic Security Analysis of Blockchain Protocols”
</div>
<details class="talk">
<summary><span class="summary-hint">Click to see abstract</span></summary>
<div markdown="1">
Game-theoretic security analysis of blockchain technologies has proven highly valuable. Such analysis examines protocols from an economic perspective, specifically by exploring the economic incentives that drive user behavior. Thus, it ensures that deviating from the intended, honest behavior of a protocol is not financially beneficial: as long as users follow the protocol, they cannot be financially harmed, regardless of how others behave. Such an economic analysis of blockchain protocols can be encoded as an automated reasoning problem in the first-order theory of real arithmetic, thereby reducing game-theoretic reasoning to satisfiability modulo theories (SMT) solving.
We conduct a divide-and-conquer security analysis based on compositional reasoning over games. Our compositional analysis is incremental: we divide games into subgames such that changes to one subgame do not necessitate re-analyzing the entire game, but only the ancestor nodes. Our approach is sound, complete, and effective: combining the security properties of subgames yields security of the entire game. Experimental results show that compositional reasoning scales well to games with millions of nodes, enabling security analysis of large real-life protocols.
</div>
</details>
</div>

<div class="break">10:30–11:00 — Coffee Break</div>

<div class="session">
<div class="session-header">
Session 2 — Morning II
<span class="session-time">11:00–12:20</span>
</div>

<div class="slot">11:00–11:40 — <strong><a href="https://crypto.unibe.ch/jv/">Juan Villacis</a></strong>, University of Bern, “What properties should asymmetric quorum systems satisfy?”</div>
<details class="talk">
<summary><span class="summary-hint">Click to see abstract</span></summary>
<div markdown="1">
In distributed systems with asymmetric trust, each participant is free to make its own trust assumptions about others, captured by an asymmetric quorum system. This contrasts with ordinary, symmetric quorum systems and threshold models, where trust assumptions are uniformly shared among participants. In the symmetric setting, quorum systems must satisfy the consistency and availability properties to solve key problems like reliable broadcast and consensus. But what properties are needed in the asymmetric setting to solve these problems? We examine this question in both the crash-fault and Byzantine models. In the crash-fault setting, any quorum system satisfying consistency and availability can be transformed into a symmetric one, removing any benefit from asymmetric trust. In the Byzantine model, consistency and availability are not enough to solve reliable broadcast and consensus. Existing approaches overcome this by introducing stronger assumptions. We show that some of these assumptions are overly restrictive, so much so that they effectively eliminate the benefits of asymmetric trust. We introduce a new way to characterize asymmetric problems and, based on this, present protocols for reliable broadcast and consensus that work under weaker assumptions than existing solutions.
</div>
</details>

<div class="slot">11:40–12:20 — <strong><a href="https://www.technion.ac.il/en/">Raïssa Nataf</a></strong>, Technion</div>

<div class="slot">12:20–13:00 — <strong><a href="https://academia.yannicmaus.de/">Yannic Maus</a></strong>, TU Graz</div>
</div>

<div class="break lunch">13:00–14:30 — Lunch Break</div>

<div class="session">
<div class="session-header">
Session 3 — Afternoon I
<span class="session-time">14:30–16:30</span>
</div>

<div class="slot">14:30–15:10 — <strong><a href="https://schmiste.github.io/">Stefan Schmid</a></strong>, TU Berlin, “Synthesis of dependable and self-driving communication networks”</div>
<details class="talk">
<summary><span class="summary-hint">Click to see abstract</span></summary>
<div markdown="1">
Communication networks have become a critical infrastructure of our digital society. 
The resulting stringent reliability requirements however stand in stark contrast to today's manual and error-prone approach to operate networks.
In this talk, I will present opportunities for using formal methods to build highly dependable communication networks.
In particular, we show how the policy-compliance of important network protocols can be verified in polynomial time, and explore synthesis
approaches to efficiently generate and update network configurations. 
We will also discuss opportunities of AI/ML methodologies in this context.
</div>
</details>

<div class="slot">15:10–15:50 — <strong><a href="https://people.rennes.inria.fr/Nathalie.Bertrand/index.html">Nathalie Bertrand</a></strong>, University of Rennes, Inria, CNRS, IRISA</div>

<div class="slot">15:50–16:30 — <strong><a href="https://gchockler.com/">Gregory Chockler</a></strong>, University of Surrey, “Proving Linearizability of Fault-Tolerant Register Protocols: Dependency Graph Approach”</div>
</div>

<div class="break">16:30—17:00 — Break</div>

<div class="session">
<div class="session-header">
Session 4 — Afternoon II
<span class="session-time">17:00–18:00</span>
</div>

<div class="slot">17:00–17:20 — <strong><a href="https://www.linkedin.com/in/isabelle-coget-b63b5b197/">Isabelle Coget</a></strong>, Polytechnic Institute of Paris, “Automated Reasoning on Consistency Models with MONA”</div>
<details class="talk">
<summary><span class="summary-hint">Click to see abstract</span></summary>
<div markdown="1">
Reasoning about consistency models for replicated objects is a challenging task that requires a deep understanding of both the consistency models themselves and a large part of human inputs in mechanized verification approaches.

In this work, we introduce a fully automated approach to reasoning about consistency models for replicated objects. We explore the monadic second-order logic (MSO) representation of consistency properties, with the aim of extending the well-known MSO-to-automata translation to traces of executions.

Thus, this talk focuses on reducing MSO over execution traces to MSO over finite words, so as to match the input requirements of the MONA tool, which performs satisfiability in this setting by translating such formulas into automata.
</div>
</details>

<div class="slot">17:20–18:00 — <strong><a href="https://hagit.net.technion.ac.il/">Hagit Attiya</a></strong>, Technion, “Specifying binding and commitment with ghost outputs and strong refinement”</div>
<details class="talk">
<summary><span class="summary-hint">Click to see abstract</span></summary>
<div markdown="1">
Binding requires a distributed protocol to limit the possible outputs of processes, in a manner that is unknown to the processes themselves. Commitment fixes the output to a value that remains hidden from almost all processes. Both are hyperproperties since they consider possible extensions of a trace. 

Specifying these properties is cumbersome, and arguing about them is even more so. 

This talk explores how these properties can be captured by enforcing strong refinement of abstract modules that produce *ghost outputs*, which are not observed by the processes invoking the protocol implementing the module. We will discuss how ghost outputs may facilitate the composition and verification of such modules. 

Examples will include binding crusader agreement and gather, random secret draw and verifiable secret sharing.
</div>
</details>
</div>


## Topics of Interest

The topics of interest for the FRIDA workshop include the following, as they apply to distributed algorithms and systems:

* formal modeling
* model checking
* interactive theorem proving
* parameterized model checking
* integration of different verification techniques
* benchmarking
* synthesis
* run-time verification
* testing
* invariant inference

## Previous Editions

Starting a productive dialogue between distributed algorithms and verification communities was the goal of a successful [Dagstuhl Seminar "Formal Verification of Distributed Algorithms"](https://www.dagstuhl.de/en/program/calendar/semhp/?semnr=13141) which was held in April 2013. During this seminar, the participants agreed that a series of workshops should be held in order to strengthen the community that does research on these issues.

The FRIDA workshop has taken place every year since 2014:

* [FRIDA 2024](https://frida-2024.github.io) - Montreal, Canada (CAV 2024)
* [FRIDA 2023](https://frida-2023.github.io) - L'Aquila, Italy (DISC 2023)
* [FRIDA 2022](https://frida-2022.github.io) - Haifa, Israel (FLoC 2022)
* [FRIDA 2021](https://frida-2021.github.io) - Online (DISC 2021)
* [FRIDA 2020](https://frida2020.galois.com/) - Online (QONFEST 2020)
* [FRIDA 2019](https://team.inria.fr/veridis/events/frida2019/) - Budapest, Hungary (DISC 2019)
* [FRIDA 2018](https://forsyte.at/events/frida2018/) - Oxford, UK (FLoC 2018)
* [FRIDA 2017](https://forsyte.at/events/frida2017/) - Vienna, Austria (DISC 2017)
* [FRIDA 2016](https://forsyte.at/events/frida2016/) - Marrakech, Morocco (NETYS 2016)
* [FRIDA 2015](http://discotec2015.inria.fr/workshops/frida-2015/) - Grenoble, France (FORTE 2015)
* [FRIDA 2014](https://easychair.org/smart-program/VSL2014/FRIDA-index.html) - Vienna, Austria (Vienna Summer of Logic 2014)

## Contact

For questions about FRIDA 2025, please contact the organizers:

- [Giuliano Losa](mailto:giuliano@stellar.org) (giuliano@stellar.org)
- [Stephan Merz](mailto:stephan.merz@loria.fr) (stephan.merz@loria.fr)
