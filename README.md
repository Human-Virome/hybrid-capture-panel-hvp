# Human Virome Hybrid Capture Panel

A comprehensive resource for designing hybrid capture panels targeting human-infecting viruses.

🌐 **[View the Website](https://human-virome.github.io/hybrid-capture-panel-hvp/)**

## Overview

This repository serves as a lightweight "platoform" for HVP scientists to provide feedback on reference genome choice for designing a **hybrid capture sequencing panel**.

## Contents

- **`output/human_virus_metadata.v0.2.0.tsv`** - Curated metadata for human-infecting viruses
- **`output/metadata_cards.v0.2.0.html`** - Interactive card viewer for browsing virus metadata
- **`docs/`** - GitHub Pages website source

## Website

The website is automatically deployed via GitHub Pages. Visit:
**https://human-virome.github.io/hybrid-capture-panel-hvp/**


### Local Development

```bash
# Setup (first time only)
conda env create -f environment.yml
conda activate hvp-site
conda install -c conda-forge cxx-compiler make
ln -s ~/.conda/envs/hvp-site/bin/ruby ~/.conda/envs/hvp-site/share/rubygems/bin/ruby
gem install bundler jekyll
cd docs
ruby -S bundle install

# Run local server
ruby -S bundle exec jekyll serve --baseurl "" --port 4001
# Visit http://localhost:4001/
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
