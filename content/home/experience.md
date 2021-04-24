---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

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
  - title: Senior Data Scientist
    company: Banque Nationale de Données Maladies Rares
    company_url: ''
    company_logo: org-gc
    location: Paris, France
    date_start: '2020-06-01'
    date_end: ''
    description: |2-
        Responsibilities include:

        * Built a machine learning algorithm for automatic extraction of clinical information from rare diseases patients’ electronic health records.

        * Conducted epidemiological studies on rare disease patients including the impact of coronavirus and surmortality.

        * Helped building an automated COVID dashboard for AP-HP.

        * Developed tools to anonymize nominative patient data and contributed to build the desindentified research rare disease registry.

        * Implemented a deduplication algorithm using record linkage.


  - title: Affiliated Staff
    company: Boston Children Hospital
    company_url: ''
    company_logo: org-x
    location: Boston, MA
    date_start: '2017-09-01'
    date_end: '2019-09-01'
    description: |2-
        Responsibilities include:
          * Assisted research work on identifying the neurological basis of autism using MRIs data using statistics and machine learning.

          * Created data preprocessing pipelines to build normative datasets from publicly available data using the computational radiology lab infrastructures.

          * Built Dockers and singularity containers to deploy lab software solutions on BCH, Harvard Medical School, and Harvard Faculty of Art and Science high-performance clusters.



design:
  columns: '2'
---
