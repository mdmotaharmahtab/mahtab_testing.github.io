---
# An instance of the Accomplishments widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: accomplishments

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 100

# Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
# title: 'Accomplish&shy;ments'
# title: "Accomplish<br>ments"
title: "Blogs"

subtitle:

# Date format
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Accomplishments.
#   Add/remove as many `item` blocks below as you like.
#   `title`, `organization`, and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
item:
  - date_end: ''
    date_start: '2024-04-29'
    description: 'Capturing long-range dependencies in texts/audio/images requires a larger context length. Sparse Transformers¹ reduces the computation complexity of the Transformer networks. GPT-3 uses the Sparse Transformers architecture in their Transformers.'
    organization: Medium
    organization_url: https://medium.com/
    title: Sparse Transformers Explained | Part 1
    url: 'https://medium.com/@mahtab27672767/sparse-transformers-explained-part-1-aacbe10dca4a'

design:
  columns: '1'
advanced:
  css_class: "blog-section"
---
