---
title: 'CryptanalysisBench: Can LLMs do Cryptanalysis?'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Avital Shafran
  - Nicholas Carlini
  - Matthew Jagielski
  - Milad Nasr
  - Orr Dunkelman
  - Eyal Ronen
  - Florian Tramèr

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2026-07-29T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-07-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: arXiv preprint
publication_short: '*arXiv preprint*'

abstract: "Cryptanalysis - the task of finding attacks against cryptographic schemes - sits at the intersection of mathematical reasoning and cybersecurity, two areas where LLMs have advanced fastest. Cryptanalysis represents both a clean testbed for frontier reasoning (as practical attacks can be automatically verified) and a domain with unusually high stakes, since the primitives under study underpin our digital security. In this paper we ask whether LLMs can do cryptanalysis, and find that the answer is increasingly yes. We introduce CryptanalysisBench, 191 tasks across six families of cryptographic primitives (block ciphers, hash functions, etc.) drawn primarily from four NIST standardization competitions. Our benchmark consists of three tiers: (i) primitives with known practical breaks; (ii) primitives with no known practical break, evaluated both at full strength and as scaled-down variants; and (iii) a challenge set of production primitives at the frontier of cryptanalysis. Five frontier models break 65%-86% of Tier 1 schemes, 6-12 Tier-2 schemes at full strength, and 24-61 across all scaled-down variants. Beyond deriving known results, models produce novel cryptanalysis, such as a key-recovery attack that exploits a design flaw in the SpoC AEAD and an error in KINDI's published CCA-security proof, both to the best of our knowledge not previously known. We release CryptanalysisBench as a tool to help track if (or when) AI cryptanalysis becomes a serious factor and as a scaffold for stress-testing candidate schemes before deployment. The attacks that the benchmark already surfaces are an early snapshot of a fast-moving frontier that may soon match, and in places exceed, the published state of the art."

# Summary. An optional shortened abstract.
summary: ''

tags:
  - Cryptanalysis
  - LLMs
  - AI Safety

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
  - name: Website
    url: 'https://cryptanalysis-bench.com/'

# Make the publication title link straight to the external site.
external_link: 'https://cryptanalysis-bench.com/'

url_pdf: 'https://arxiv.org/abs/2607.18538'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
