---
title: ''
summary: ''
date: 2026-06-07
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Email Me
        url: mailto:cfy25@mails.tsinghua.edu.cn
      headings:
        about: About
        education: Education
        interests: Research Interests
    design:
      background:
        color: white
      name:
        size: md
      avatar:
        size: medium
        shape: rounded

  - block: markdown
    id: research
    content:
      title: Research Focus
      subtitle: ''
      text: |-
        I am interested in building computational models that connect molecular perturbations to cellular phenotypes and therapeutic design. My current focus spans perturbation biology, AI virtual cell modeling, single-cell transcriptomics, AI-driven drug discovery, and protein/perturbation-based drug discovery.

        <div class="grid gap-4 md:grid-cols-3 not-prose mt-8">
          <img class="rounded-md border border-gray-200 bg-white p-4 object-contain h-28 w-full" src="media/labs/mdl.png" alt="Molecular Design Laboratory logo">
          <img class="rounded-md border border-gray-200 bg-white p-4 object-contain h-28 w-full" src="media/labs/bii.png" alt="A*STAR Bioinformatics Institute logo">
          <img class="rounded-md border border-gray-200 bg-white p-4 object-contain h-28 w-full" src="media/labs/cancer-pku.png" alt="Cancer PKU logo">
        </div>
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications & Manuscripts
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
      sort_by: date
      sort_ascending: false
    design:
      view: citation

  - block: markdown
    id: experience
    content:
      title: Research Experience
      text: |-
        **Tsinghua BIOPIC / Cancer PKU**  
        PhD student working on tumor microenvironment, perturbation biology, and single-cell modeling.

        **A*STAR Bioinformatics Institute / NUS**  
        Developed TCM-Navigator, an AI-assisted workflow for TCM-like molecular generation and evaluation.

        **Molecular Design Laboratory, SJTU School of Medicine**  
        Studied CRISPR-Cas9 allostery, conformational dynamics, and database resources for allosteric drug discovery.
    design:
      columns: '1'
---
