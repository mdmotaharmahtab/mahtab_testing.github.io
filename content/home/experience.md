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
        *  Created new state-of-the-art systems for a plethora of Bangla NLP tasks e.g. Named Entity Recognition (NER), Parts of Speech (POS), Lemmatization, Question Answering, Coreference Resolution and Emotion recognition. Performed R&D on increasing performance beyond the current state-of-the-art to achieve 90% KPI on ML modules. Two such systems Bangla Lemmatization and Emotion recognition are publicly available at [https://github.com/eblict-gigatech/BanLemma](https://github.com/eblict-gigatech/BanLemma) and [https://sentiment.bangla.gov.bd](https://sentiment.bangla.gov.bd) respectively.
        * Created GPT4o inference pipeline for Bangla NER and Coreference
        Resolution systems using [ReAct](https://arxiv.org/abs/2210.03629) prompting method achieving comparable performance against finetuned systems.
        * Created pipeline for Natural Language generation (NLG) in Bangla for both encoder models like BERT and auto-regressive models like GPT2. Analyzed and overcame common issues like repetitive text generation, and unmeaningful word generation in NLG for Bangla.
        * The Question Answering (QA) module establishes new state-of-the-art results on Bangla datasets including  SQuAD-bn (translated from the SQuAD-2.0 and TyDI-QA English QA datasets) by a modified loss function to balance performance among null and non-null questions.
        * The NER classification module establishes new state-of-the-art results on Bangla NER datasets by a hierarchical majority voting mechanism among external contexts retrieved from a Knowledge Base.
        * Created data augmentation pipeline to handle the class imbalance problem in sequence tagging tasks. Formulated a general test set creation guidelines for unbiased classification performance calculation.
        * Optimized deployment of LLMs using Optimum (for ONNX conversion) and Nvidia TensorRT(TRT) format for further optimization. Used PyTorch Profiler to identify inference bottlenecks. Used Nvidia Triton Inference Server (TIS) as the default ML inference server for concurrent request serving and scheduling, batch inference and response caching in MongoDB. Used Locust for load testing and pytorch profiler to reduce bottlenecks.
        * Created REST APIs using FastAPI for hosting ML inference endpoints. Used MongoDB for response caching in NVIDIA Triton.
        * Used Qdrant vector DB for fast semantic searching, Dask to analyze and query big dataframes, DVC for dataset versioning and MLflow for model, artifact and experiment versioning.
        * Used Qdrant vector DB for fast semantic searching, Dask to analyze and query big dataframes, DVC for dataset versioning and MLflow for model, artifact and experiment versioning.

  - title: Research Assistant
    company: Qatar Computing Research Institute
    company_url: 'https://www.hbku.edu.qa/en/qcri'
    company_logo: qcri_logo
    location: Remote
    date_start: '2021-09-01'
    date_end: '2021-12-31'
    description: |2-
      * Pretrained a HuBERT model on Bangla ASR dataset for joint task of speech and speaker recognition pipeline using SpeechBrain.
      * Assisted in enriching existing open source Bangla ASR datasets by adding more scripted audio and correcting existing annotation
  
  - title: Undergraduate Teacher Assistant
    company: BRAC University
    company_url: 'https://www.bracu.ac.bd/'
    company_logo: brac_uni
    location: Dhaka, Bangladesh
    date_start: '2020-04-01'
    date_end: '2022-04-30'
    description: |2-
      * Helped students with different coding assignments and helped teachers in checking scripts.
      * Assisted students in conducting research in various fields and submitting papers to conferences.
      * Assisted Teachers in lab classes and helped students with different course materials during consultation hour.

design:
  columns: '1'

advanced:
  css_class: "experience-section"
---
