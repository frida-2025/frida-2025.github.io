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
  margin-top: -1rem;     /* Pull the details closer to the speaker name above */
}

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
</style>

# The 12th Workshop on Formal Reasoning in Distributed Algorithms


<div class="info-box">
  <strong>📅 Date:</strong> Monday, October 27, 2025 (whole-day workshop)<br>
  <strong>📍 Location:</strong> Berlin, Germany<br>
  <strong>🔗 Co-located with:</strong> <a href="https://www.disc-conference.org/wp/disc2025/">DISC 2025</a><br>
</div>

## About FRIDA

The FRIDA workshop aims to foster collaboration between the distributed algorithms and formal-methods communities. This workshop provides a forum for researchers to present recent advances in formal reasoning about distributed algorithms and systems, share experiences, and discuss future directions.

To attend, please register on the [DISC 2025](https://www.disc-conference.org/wp/disc2025/) website (registration will open soon).

FRIDA 2025 is organized by:
- [Giuliano Losa](https://www.losa.fr/) (giuliano@stellar.org), Stellar Development Foundation
- [Stephan Merz](https://members.loria.fr/Stephan.Merz/) (stephan.merz@loria.fr), INRIA Nancy & LORIA

## Call for Speakers

We are looking for speakers to present their work at FRIDA 2025. Please submit proposals for talks by email to the organizers by **September 15, 2025**. Submissions will be reviewed on an ongoing basis.

## Confirmed Speakers

**[Hagit Attiya, Technion](https://hagit.net.technion.ac.il/)** --- "Specifying binding and commitment with ghost outputs and strong refinement"
<details class="talk">
  <summary>
    <span class="summary-hint">Click to see abstract</span>
  </summary>
  <div markdown="1">

Binding requires a distributed protocol to limit the possible outputs of processes, in a manner that is unknown to the processes themselves. Commitment fixes the output to a value that remains hidden from almost all processes. Both are hyperproperties since they consider possible extensions of a trace. 

Specifying these properties is cumbersome, and arguing about them is even more so. 

This talk explores how these properties can be captured by enforcing strong refinement of abstract modules that produce *ghost outputs*, which are not observed by the processes invoking the protocol implementing the module. We will discuss how ghost outputs may facilitate the composition and verification of such modules. 

Examples will include binding crusader agreement and gather, random secret draw and verifiable secret sharing.

  </div>
</details>

**[Stefan Schmid, TU Berlin](https://schmiste.github.io/)** --- "Synthesis of dependable and self-driving communication networks"
<details class="talk">
  <summary>
    <span class="summary-hint">Click to see abstract</span>
  </summary>
  <div markdown="1">

Communication networks have become a critical infrastructure of our digital society. 
The resulting stringent reliability requirements however stand in stark contrast to today's manual and error-prone approach to operate networks.
In this talk, I will present opportunities for using formal methods to build highly dependable communication networks.
In particular, we show how the policy-compliance of important network protocols can be verified in polynomial time, and explore synthesis
approaches to efficiently generate and update network configurations. 
We will also discuss opportunities of AI/ML methodologies in this context.
  </div>
</details>

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
