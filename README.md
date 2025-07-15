# FRIDA 2025 Website

This repository contains the website for the 12th Workshop on Formal Reasoning in Distributed Algorithms (FRIDA 2025), colocated with DISC 2025 in Berlin, Germany.

## Quick Start

The website is built using Jekyll and GitHub Pages. Here's how to work with it:

### Prerequisites

- Ruby (version 2.7 or higher)
- Bundler gem
- Git

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/frida-2025/frida-2025.github.io.git
   cd frida-2025.github.io
   ```

2. **Install dependencies:**
   ```bash
   bundle install
   ```

3. **Run the development server:**
   ```bash
   bundle exec jekyll serve
   ```

4. **View the website:**
   Open your browser and go to `http://localhost:4000`

The development server will automatically rebuild the site when you make changes to files.

### Making Changes

#### Content Updates

- **Main content:** Edit `index.markdown`
- **Site configuration:** Edit `_config.yml`
- **Layout/theme:** Edit `_layouts/default.html`

#### Adding New Pages

1. Create a new `.markdown` or `.md` file in the root directory
2. Add front matter at the top:
   ```yaml
   ---
   layout: default
   title: Page Title
   ---
   ```
3. Add your content below the front matter

### Deployment

The website is automatically deployed to GitHub Pages when you push changes to the `main` branch.

1. **Add your changes:**
   ```bash
   git add .
   git commit -m "Description of changes"
   ```

2. **Push to GitHub:**
   ```bash
   git push origin main
   ```

3. **Wait for deployment:**
   GitHub Pages will automatically build and deploy the site. This usually takes 1-2 minutes.

4. **View the live site:**
   Visit `https://frida-2025.github.io`

### Important Notes

- **Don't commit:** `_site/`, `Gemfile.lock`, or `previous-edition/` - these are excluded in `.gitignore`
- **GitHub Pages builds automatically:** You don't need to run `jekyll build` manually
- **Theme:** The site uses the Minima theme with custom modifications
- **SEO:** The site includes proper SEO tags and meta information

### Previous Editions

Checkout out https://github.com/frida-2024/frida-2024.github.io for last year's website.
