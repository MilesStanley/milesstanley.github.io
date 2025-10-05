---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Bachelor of Science in Computer Science (GPA: 3.96), University of Washington, Expected Graduation: June 2026

Research Interests
======
* Robust and Fair AI
* Explainable AI
* Interdisciplinary AI
* Computational Social Science
* Natural Language Processing

Publications & Presentations
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Research Experience
======
* REU Researcher, May 2025 – August 2025
  * Rochester Institute of Technology, Rochester, NY
  * Advisor: Prof. Ashiqur KhudaBukhsh
  * First author on a project investigating “vaccine buyer’s remorse” in a large corpus of YouTube comments.
  * Implemented a multi-stage hybrid pipeline to quantify nuanced, politically charged sentiment at scale.
  * Created a novel benchmark dataset of 2,000 comments, annotated by a politically diverse panel to mitigate subjectivity and rater bias.
  * Fine-tuned and evaluated multiple LLMs (e.g., Llama 3, Mixtral) to classify comments based on narrative perspective (first-person vs. vicarious) and the presence of regret.

* Undergraduate Research Assistant, Oct. 2024 – Present
  * University of Washington, Make4All Group, Seattle, WA
  * Advisors: Prof. Jennifer Mankoff, Brianna Wimer (Ph.D. Student)
  * Collaborating on the development of generative AI tools to create accessible flowcharts.
  * Leading design of Generative Rationale-Guided Training (GRGT), a framework for improving LLM robustness by supervising internal reasoning.
  * Implementing a teacher-student model with a dual-objective loss function to align a student model’s reasoning.

* Laboratory Research Assistant, Nov. 2024 – Present
  * University of Washington School of Medicine, NEST Program, Seattle, WA
  * Advisor: Prof. Rachel Umoren
  * Evaluated signal denoising techniques to improve neonatal heart rate measurement during ambulance transport.
  * Developed multithreaded Python scripts using Tesseract OCR to automate data extraction from medical reports, achieving a 75% reduction in execution time.
  * Developing an NLP system using LLMs (Llama 3.1) to evaluate medical simulation transcripts for automated scoring and feedback.

Teaching & Mentorship Experience
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Technical Skills
======
* Languages: Python, Java, JavaScript, TypeScript, C, Bash
* Developer Tools: Git, GitHub, Docker, VS Code
* AI/ML Libraries: PyTorch, Hugging Face (Transformers, Datasets), Scikit-learn, Pandas, NumPy, Matplotlib
* Human Languages: English (Native), French (Fluent)
