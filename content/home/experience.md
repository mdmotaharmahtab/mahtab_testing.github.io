---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

id: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
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
  - title: AI Engineer
    company: Delineate Inc.
    company_url: 'https://gigatechltd.com/'
    company_logo: delineate_logo
    location: Remote
    date_start: '2024-10-01'
    date_end: ''
    description: |2-
      * Parallel background processing using Celery and Webhooks for
      faster Table Extraction using GPT4o. 
      * Pipeline enabling extraction of QSP clinical trial data from 
      clnical papers and tables.
  - title: Jr. AI Engineer
    company: Giga Tech Ltd.
    company_url: 'https://gigatechltd.com/'
    company_logo: gigatech-logo
    location: Dhaka, Bangladesh
    date_start: '2022-09-01'
    date_end: '2024-10-01'
    description: |2-
        *  Created new state-of-the-art systems for a plethora of Bangla NLP tasks e.g. Named Entity Recognition (NER), Parts of Speech (POS), Lemmatization, and Emotion recognition. Bangla Lemmatization and Emotion recognition systems are publicly available at [https://github.com/eblict-gigatech/BanLemma](https://github.com/eblict-gigatech/BanLemma) and [https://sentiment.bangla.gov.bd](https://sentiment.bangla.gov.bd) respectively.
        * Optimized deployment of LLMs using Optimum (for ONNX conversion) and Nvidia TensorRT(TRT) format for further optimization. Used PyTorch Profiler to identify inference bottlenecks. Used Nvidia Triton Inference Server (TIS) as the default ML inference server for concurrent request serving and scheduling, batch inference and response caching.
        * Created REST APIs using FastAPI for hosting ML inference endpoints. Used MongoDB for response caching in NVIDIA Triton.
        * Used Qdrant vector DB for fast semantic searching, Dask to analyze and query big dataframes, DVC for dataset versioning and MLflow for model, artifact and experiment versioning.
        * Created pipeline for Natural Language generation (NLG) in Bangla for both encoder models like BERT and auto-regressive models like GPT2. Analyzed and overcame common issues like repetitive text generation, and unmeaningful word generation in NLG for Bangla.

  - title: Professor of Semiconductor Physics
    company: University X
    company_url: ''
    company_logo: qcri_logo
    location: Remote
    date_start: '2021-09-01'
    date_end: '2021-12-31'
    description: |2-
      * Pretrained a HuBERT model on Bangla ASR dataset for joint task of speech and speaker recognition pipeline using SpeechBrain.
      * Assisted in enriching existing open source Bangla ASR datasets by adding more scripted audio and correcting existing annotation


design:
  columns: '1'

advanced:
  css_class: "education-section"
---
