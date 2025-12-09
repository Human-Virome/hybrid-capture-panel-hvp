---
layout: default
title: Home
---

<div class="hero">
  <h1>🧬 Human Virome Hybrid Capture Panel</h1>
  <p class="tagline">A comprehensive resource for designing hybrid capture panels targeting human-infecting viruses</p>
</div>

## About This Project

This repository serves as a lightweight "platoform" for HVP scientists to provide feedback on reference genome choice for designing a **hybrid capture sequencing panel**. The goal of the hybrid capture panel is to target viruses likely to infect humans. Hybrid capture enrichment is a powerful technique for detecting and characterizing viral sequences in complex clinical and environmental samples, but existing panels are missing some human-tropic viruses.

**NOTE:** This is not a completed or official database, nor does its contents reflect the opinions of the Human Virome Program or its funding bodies. Consider this an ad hoc platform for soliciting discussion and feedback.

### What's Included

- **Curated Virus Metadata**: Comprehensive information on human-infecting viruses including taxonomy, genome lengths, and reference sequences
- **Interactive Metadata Cards**: Browse and filter virus information with our [interactive card viewer](metadata_cards.html)
- **Link to Genome Sequences**: A bulk .fasta file of all genomes in current version !link

## Quick Links

<div class="button-row">
  <a href="metadata_cards.html" class="btn">📋 Browse Virus Metadata Cards</a>
  <a href="https://github.com/Human-Virome/hybrid-capture-panel-hvp" class="btn btn-secondary">💻 View on GitHub</a>
</div>

## Getting Started

1. **Explore the metadata**: Start by browsing the [Virus Metadata Cards](metadata_cards.html) to see the curated list of human viruses
2. **Provide Feedback**: If you see a species or genome that looks wrong, please use the buttons and comment box in the species cards. Then, download your feedback and post it in the HVP Slack Channel.
3. **Download the data**: Raw metadata is available in TSV format in the `output/` directory in the GitHub page. `.tsv` files can be opened in Microsoft Excel for easy perusal.


---

<p class="footer-note">
  Maintained by researchers in the <a href="https://github.com/Human-Virome">Human Virome</a> Program
</p>

<style>
.hero {
  text-align: center;
  padding: 2rem 1rem;
  margin-bottom: 2rem;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  border-radius: 12px;
  color: white;
}
.hero h1 {
  margin: 0 0 0.5rem;
  font-size: 2rem;
}
.tagline {
  font-size: 1.1rem;
  opacity: 0.95;
  margin: 0;
}
.button-row {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
  margin: 1.5rem 0;
}
.btn {
  display: inline-block;
  padding: 0.75rem 1.5rem;
  background: #667eea;
  color: white !important;
  text-decoration: none;
  border-radius: 8px;
  font-weight: 600;
  transition: transform 0.2s, box-shadow 0.2s;
}
.btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(102, 126, 234, 0.4);
}
.btn-secondary {
  background: #374151;
}
.btn-secondary:hover {
  box-shadow: 0 4px 12px rgba(55, 65, 81, 0.4);
}
.footer-note {
  text-align: center;
  color: #6b7280;
  font-size: 0.9rem;
  margin-top: 3rem;
}
</style>
