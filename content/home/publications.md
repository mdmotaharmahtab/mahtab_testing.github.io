---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

id: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Publications
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: BanLemma
    company: The 2023 Conference on Empirical Methods in Natural Language Processing (EMNLP); H-Index:176
    company_url: 'https://2023.emnlp.org/'
    company_logo: emnlp-2023-logo
    location: Singapore
    date_start: '2023-12-01'
    date_end: ''
    description: |2-
      * State-of-the-art Bangla Rule Based Lemmatizer which proposes a   novel iterative suffix stripping approach based on the part-of-speech tag of a word.Shows superior performance than all previously published Bangla lemmatization methods on existing datasets. 
      * Paper [BanLemma A Word Formation Dependent Rule Based
        Lemmatizer](https://aclanthology.org/2023.findings-emnlp.240)
      * Code [https://github.com/eblict-gigatech/BanLemma](https://github.com/eblict-gigatech/BanLemma)
      * Supervisor [Dr. Nabeel Mohammed](http://ece.northsouth.edu/people/dr-nabeel-mohammed/), [Dr. Ruhul Amin](https://www.fordham.edu/academics/research/faculty-research/research-consortium-on-disability/affiliates/ruhul-amin/)

  - title: BanglaBait
    company: RANLP
    company_url: 'https://ranlp.org/ranlp2023/'
    company_logo: ranlp_logo
    location: Bulgaria
    date_start: '2022-09-08'
    date_end: ''
    description: |2-
        *  First Bangla Clickbait News Article Dataset containing 15,056 data instances. Investigated various semi-supervised learning methods and compared them with supervised learning methods to prove the former's superiority.
        * Paper [BanglaBait: Semi-Supervised Adversarial Approach for Clickbait Detection on Bangla Clickbait Dataset](https://aclanthology.org/2023.ranlp-1.81/)
        * Code [https://github.com/mdmotaharmahtab/BanglaBait](https://github.com/mdmotaharmahtab/BanglaBait)
        * Supervisor [Dr. Farig Sadeque](https://www.bracu.ac.bd/about/people/farig-yousuf-sadeque)

  - title: GAN-BERT
    company: Springer
    company_url: 'https://link.springer.com/book/10.1007/978-3-031-20859-1#:~:text=DCAI%202022%20is%20a%20forum,artificial%20intelligence%20and%20computing%20areas'
    company_logo: dcai_logo
    location: Bulgaria
    date_start: '2022-09-08'
    date_end: ''
    description: |2-
        *  Trained state-of-the-art Transformer networks in adversarial fashion using Generative Adversarial Network (GAN) to achieve superior performance when labelled dataset size is too small.First Bangla Paper to investigate the application of GAN-BERT on Bangla text classification tasks.
        * Paper [A GAN-BERT Based Approach for Bengali Text Classification with a Few Labeled Examples](https://link.springer.com/chapter/10.1007/978-3-031-20859-1_3)
        * Supervisor [Mr. Annajiat Alim Rasel](https://www.bracu.ac.bd/about/people/mr-annajiat-alim-rasel)

design:
  columns: '1'

advanced:
  css_class: "publications-section"
---
