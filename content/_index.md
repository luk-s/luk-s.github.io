---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-06-08
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: large-triangles.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: news
    content:
      title: News
      subtitle:
      text: |
        <style>
          table {
            border-collapse: collapse;
          }
          th, td {
            border: none;
            padding: 0.5em 1em;
          }
        </style>
        | | |
        | ------- | ----------- |
        | **May 2, 2025**    | 🎓 I just started a PhD at ETH Zurich, supervised by [Florian Tramèr](https://floriantramer.com) |
        | **May 1, 2025**    | 📘 Our paper [The Perils of Optimizing Learned Reward Functions: Low Training Error Does Not Guarantee Low Regret](papers/safe-reward-model-optimization/) has been accepted as a conference paper to ICML 2025! |
        | **Feb 12, 2024**   | 🏅 I was awarded an [ETH medal](https://inf.ethz.ch/news-and-events/spotlights/infk-news-channel/2024/02/eth-medals-for-masters-graduates.html) for my outstanding Master's thesis. |
        | **Dec 20, 2023**   | 📘 Our paper [Evaluating superhuman models with consistency checks](papers/evaluating-superhuman-models/) has been accepted as a conference paper to SaTML 2024! |
      design:
        - columns: '1'
---