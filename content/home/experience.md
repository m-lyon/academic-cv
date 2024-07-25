---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

active: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant
    company: University of Manchester
    company_url: 'https://www.manchester.ac.uk/'
    company_logo: uom
    location: Manchester
    date_start: '2022-06-01'
    date_end:
    description: |2-
        * Designed and implemented data cleaning and preprocessing pipelines.
        * Performed exploratory analysis on large time-series datasets.
        * Lead tutorials on several machine learning courses.
        * Developed DL architectures for high dimensional genomic time-series data.

  - title: Research Software Engineer
    company: Save Sight Institute
    company_url: 'https://www.sydney.edu.au/save-sight-institute/'
    company_logo: uos
    location: Sydney
    date_start: '2019-08-01'
    date_end: '2020-08-01'
    description: |2-
        * Developed, tested, and documented neuroimaging processing pipelines.
        * Deployed deep learning models into production.
        * Lead algorithm design and optimization workflows.
        * Consulted on neuroimaging analysis techniques and signal processing.
        
  - title: Neuroimaging Analyst
    company: Sydney Neuroimaging Analysis Centre
    company_url: 'https://www.snac.com.au/'
    company_logo: snac
    location: Sydney
    date_start: '2019-08-01'
    date_end: '2020-01-01'
    description: |2-
        * Developed, implemented, and led QC on neuroimaging analysis pipelines.
        * Conducted exploratory data analyses.

  - title: Research Software Engineer
    company: Heart Research Institute
    company_url: 'https://www.hri.org.au/'
    company_logo: hri
    location: Sydney
    date_start: '2017-07-01'
    date_end: '2019-07-01'
    description: |2-
        * Built and managed a distributed computing cluster.
        * Developed, tested, and documented neuroimaging processing pipelines.
        * Oversaw data ingestion and QC/QA, created dashboard visualisations.
        * Conducted clinical research using MRI data.

design:
  columns: '2'
---
