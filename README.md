# Controllable Generative Design of Biological Sequences

This repository contains teaching materials for **Controllable Generative Design of Biological Sequences**, a tutorial at the [ML in PL 2026 Conference](https://conference.mlinpl.org/2026/program#tutorial-1), led by members of the [Ewa Szczurek Lab](https://ewaszczureklab.mimuw.edu.pl/).

## Description
Generative machine learning is transforming how we design peptides, proteins and small molecules. Yet for AI-oriented researchers, understanding how these methods connect to real biological design problems, and how to apply them in practice, can be hard to approach. This tutorial closes that gap, teaching both the theory behind controllable generative design and the practical skills needed to apply our lab’s models to concrete sequence design tasks.

The first part (about 1.5 hours) will cover the conceptual foundations. We will introduce conditional and guided generation for biological sequences, spanning diffusion based methods, latent space approaches, and property guided sampling, motivating each through concrete design goals such as antimicrobial activity or target binding.

The hands-on part (about 2 to 2.5 hours) will turn theory into practice. Participants will run our models directly, in several operating modes. OmegAMP handles conditional antimicrobial peptide generation, while JSI and PepCompass support latent space exploration and property guided design. Each segment will pair a brief conceptual reminder with a guided, executable walkthrough, so attendees will be able to reproduce results and adapt the workflows to their own questions.

While the tutorial focuses on biological sequences, the underlying principles of conditioning, guidance, and controlled sampling transfer directly to other controllable generative AI problems, so the material will serve anyone working on steering generative models toward desired outcomes.

**Goals of the tutorial:** By the end, participants will understand when and why to reach for each method and will have working familiarity running them on realistic tasks. Our goal is that they walk away ready to apply these tools to their own research questions, whether in peptides, proteins, or broader sequence design.

**Prerequisites:** Basic Python is needed. Some familiarity with generative AI and biological sequences will help, but is not strictly required.

## Agenda

- **[Foundations (slides)](materials/foundations/Readme.md)** (1 h) - Ewa Szczurek 
- Break (15 min)
- **[PepCompass](materials/pepcompass/README.md)** (30 min) - Adam Bielecki
    - [Google Colab](https://colab.research.google.com/drive/1wrVuW79WUhAzymUFtwBvdy4Z1NvFUxb7#scrollTo=3HD8lxkx3CGm)
- **[OmegAMP](materials/omegamp/README.md)** (30 min) - Diogo Soares
    - [Slides](materials/omegamp/omegamp-ml-in-pl.pdf)
    - [Google Colab](https://colab.research.google.com/drive/1hrk-3Pc0zZUkpCVKMY6vns9G6BcWWXyM?usp=sharing)
- Break (15 min)
- **[Sampling with Joint Generative-Predictive Chemical Language Models (slides)](materials/Sampling-with-Joint-Generative-Predictive-Chemical-Language-Models/Sampling-with-Joint-Generative-Predictive-Chemical-Language-Models.pdf)**
    - **[Hyformer](materials/Sampling-with-Joint-Generative-Predictive-Chemical-Language-Models/hyformer/README.md)** (30 min) - Adam Izdebski
        - [Google Colab](https://colab.research.google.com/drive/1dyt9vm33mdxRChD0lrfXK6UEgbmlAWpK?usp=sharing)
    - **[Joint-self-improvement](materials/Sampling-with-Joint-Generative-Predictive-Chemical-Language-Models/joint-self-improvement/README.md)** (30 min) - Serra Korkmaz
        - [Google Colab](https://colab.research.google.com/drive/1dZail-j4WVSEuziQlAXPV8cKmbkIpV97?usp=sharing)
    - **[AMPFormer](materials/Sampling-with-Joint-Generative-Predictive-Chemical-Language-Models/ampformer/README.md)** (30 min) - Pankhil Gawade
        - [Google Colab](https://colab.research.google.com/github/Pankhil07/mlinpl-peptide-tutorial/blob/main/mlinpl-controllable-peptide-design.ipynb)
