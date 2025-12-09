# Human Virome Hybrid Capture Panel

A comprehensive resource for designing hybrid capture panels targeting human-infecting viruses.

🌐 **[View the Website](https://human-virome.github.io/hybrid-capture-panel-hvp/)**

## Overview

This repository provides curated metadata and resources for designing **hybrid capture sequencing panels** that target viruses known to infect humans. Hybrid capture enrichment is a powerful technique for detecting and characterizing viral sequences in complex clinical and environmental samples.

## Contents

- **`output/human_virus_metadata.v0.2.0.tsv`** - Curated metadata for human-infecting viruses
- **`output/metadata_cards.v0.2.0.html`** - Interactive card viewer for browsing virus metadata
- **`docs/`** - GitHub Pages website source

## Website

The website is automatically deployed via GitHub Pages. Visit:
**https://human-virome.github.io/hybrid-capture-panel-hvp/**

### Local Development

To test the website locally, you have two options:

#### Option 1: Simple Python server (no build required)
```bash
cd docs
python -m http.server 8000
# Visit http://localhost:8000
```

#### Option 2: Jekyll (full build with theme support)
```bash
cd docs
bundle install
bundle exec jekyll serve
# Visit http://localhost:4000/hybrid-capture-panel-hvp/
```

**Requirements for Jekyll:**
- Ruby 2.7+ with Bundler (`gem install bundler`)
- Or use the provided conda environment (see below)

### Conda Environment for Local Testing

If you prefer conda, create an environment with Ruby:
```bash
conda create -n hvp-site ruby=3.2 -c conda-forge
conda activate hvp-site
gem install bundler jekyll
cd docs
bundle install
bundle exec jekyll serve
```

## GitHub Pages Setup

To enable GitHub Pages for this repository:

1. Go to **Settings → Pages**
2. Under "Build and deployment", select **GitHub Actions**
3. The site will deploy automatically on push to `main`

## Contributing

We welcome contributions! Please submit issues and pull requests on GitHub.

## License

See [LICENSE](LICENSE) for details
