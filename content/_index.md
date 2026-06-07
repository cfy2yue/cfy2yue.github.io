---
title: ''
summary: ''
date: 2026-06-07
type: landing

sections:
  - block: markdown
    id: bio
    content:
      title: ''
      text: |-
        <div class="mx-auto max-w-6xl px-4 py-10 sm:py-14 lg:py-16">
        <div class="grid gap-10 lg:grid-cols-[300px_1fr] lg:items-start">
        <aside class="flex flex-col items-center text-center lg:sticky lg:top-24">
        <img class="h-64 w-52 rounded-md border border-gray-200 object-cover object-top shadow-sm" src="/media/authors/me.jpg" alt="Feiying Chen portrait">
        <h1 class="mt-6 text-4xl font-semibold tracking-normal text-gray-950">Feiying Chen</h1>
        <p class="mt-2 text-lg font-medium text-primary-700">PhD Student in Biology</p>
        <p class="mt-1 text-base text-gray-700">Tsinghua University</p>
        <div class="mt-5 flex flex-wrap justify-center gap-3 text-sm">
        <a class="rounded-md border border-gray-300 px-3 py-2 font-medium text-gray-800 hover:border-primary-500 hover:text-primary-700" href="mailto:cfy25@mails.tsinghua.edu.cn">Email</a>
        <a class="rounded-md border border-gray-300 px-3 py-2 font-medium text-gray-800 hover:border-primary-500 hover:text-primary-700" href="https://github.com/cfy2yue">GitHub</a>
        </div>
        </aside>
        <div class="min-w-0">
        <p class="text-xl leading-8 text-gray-800">I study computational models that connect molecular and cellular perturbations with phenotypic outcomes. My current interests include perturbation biology, AI virtual cells, single-cell transcriptomics, AI-driven drug discovery, and phenotype-based drug design.</p>
        <div class="mt-8 flex flex-wrap gap-2 text-sm">
        <span class="rounded-md bg-gray-100 px-3 py-2 text-gray-800">Perturbation Biology</span>
        <span class="rounded-md bg-gray-100 px-3 py-2 text-gray-800">AI Virtual Cell</span>
        <span class="rounded-md bg-gray-100 px-3 py-2 text-gray-800">Single-cell Transcriptomics</span>
        <span class="rounded-md bg-gray-100 px-3 py-2 text-gray-800">AI-driven Drug Discovery</span>
        <span class="rounded-md bg-gray-100 px-3 py-2 text-gray-800">Phenotype-based Drug Design</span>
        </div>
        <div class="mt-10 grid gap-6 md:grid-cols-2">
        <section>
        <h2 class="text-xl font-semibold text-gray-950">Education</h2>
        <div class="mt-4 space-y-4 text-gray-800">
        <div>
        <p class="font-semibold">PhD in Biology</p>
        <p>Tsinghua University, 2025-present</p>
        <p class="text-sm text-gray-600">Advisor: Prof. Zemin Zhang</p>
        </div>
        <div>
        <p class="font-semibold">B.S. in Biomedical Science</p>
        <p>Shanghai Jiao Tong University, Zhiyuan Honors Program, 2021-2025</p>
        </div>
        </div>
        </section>
        <section>
        <h2 class="text-xl font-semibold text-gray-950">Research Directions</h2>
        <ul class="mt-4 space-y-2 text-gray-800">
        <li>Perturbation-response modeling from single-cell data</li>
        <li>AI virtual cell pretraining, deployment, and post-training</li>
        <li>Phenotype-guided molecular and therapeutic design</li>
        <li>Computational chemistry for mechanism-aware drug discovery</li>
        </ul>
        </section>
        </div>
        </div>
        </div>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: skills
    content:
      title: Skills
      text: |-
        <div class="grid gap-5 md:grid-cols-3">
        <section class="rounded-md border border-gray-200 bg-white p-5">
        <h3 class="text-lg font-semibold text-gray-950">Computational Chemistry</h3>
        <p class="mt-3 text-gray-700">Molecular dynamics, docking, homology modeling, pathway analysis, Markov state modeling, and allosteric mechanism analysis.</p>
        </section>
        <section class="rounded-md border border-gray-200 bg-white p-5">
        <h3 class="text-lg font-semibold text-gray-950">AI Virtual Cell</h3>
        <p class="mt-3 text-gray-700">Single-cell foundation model pretraining, deployment, post-training, perturbation response modeling, and phenotype prediction.</p>
        </section>
        <section class="rounded-md border border-gray-200 bg-white p-5">
        <h3 class="text-lg font-semibold text-gray-950">Deep Learning</h3>
        <p class="mt-3 text-gray-700">Transformer-based, flow matching-based, diffusion-based, and agent-based models, with biology-prior embeddings for biomedical representation learning.</p>
        </section>
        </div>
    design:
      columns: '1'

  - block: markdown
    id: research
    content:
      title: Research Focus
      subtitle: ''
      text: |-
        <div class="grid gap-4 md:grid-cols-3 not-prose">
        <img class="rounded-md border border-gray-200 bg-white p-4 object-contain h-28 w-full" src="/media/labs/cancer-pku.png" alt="Cancer PKU logo">
        <img class="rounded-md border border-gray-200 bg-white p-4 object-contain h-28 w-full" src="/media/labs/bii.png" alt="A*STAR Bioinformatics Institute logo">
        <img class="rounded-md border border-gray-200 bg-white p-4 object-contain h-28 w-full" src="/media/labs/mdl.png" alt="Molecular Design Laboratory logo">
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
        <div class="space-y-6">
        <section>
        <h3 class="text-xl font-semibold text-gray-950">CancerPKU</h3>
        <p class="mt-1 text-gray-700">PhD-stage research on tumor microenvironment, perturbation biology, and single-cell modeling.</p>
        </section>
        <section>
        <h3 class="text-xl font-semibold text-gray-950">A*STAR Bioinformatics Institute / NUS</h3>
        <p class="mt-1 text-gray-700">Developed TCM-Navigator, an AI-assisted workflow for TCM-like molecular generation, quality control, and target-aware evaluation.</p>
        </section>
        <section>
        <h3 class="text-xl font-semibold text-gray-950">Molecular Design Laboratory, SJTU School of Medicine</h3>
        <p class="mt-1 text-gray-700">Studied CRISPR-Cas9 allostery, conformational dynamics, and allosteric database resources for mechanism-aware drug discovery.</p>
        </section>
        </div>
    design:
      columns: '1'
---
