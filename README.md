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

- **[Foundations](materials/foundations/README.md)** (1 h) - Ewa Szczurek 
- Break (15 min)
- **[PepCompass](materials/pepcompass/README.md)** (30 min) - Adam Bielecki
- **[OmegAMP](materials/omegamp/README.md)** (30 min) - Diogo Soares
- Break (15 min)
- **[Hyformer](materials/adam-izdebski/README.md)** (30 min) - Adam Izdebski
- **[Joint Self-Improvement](materials/serra-korkmaz/README.md)** (30 min) - Serra Korkmaz
- **[TBA](materials/pankhil-gawade/README.md)** (30 min) - Pankhil Gawade

## Guidelines for presenters

- Update the agenda with the title of your session.
- Add your subfolder in the `materials` directory to match your session title.
- Add a `README.md` to your subfolder with an appropriate description: setup instructions, citation, etc.
- Add a notebook to your subfolder containing "executable walkthrough". Ideally, participants should be able to run it in Google Colab or on their local machine. 
- If needed, add a PDF presentation with "a brief conceptual reminder".
- Build opportunities for participation into your session. E.g. prepare a few questions or short exercises that invite participants to predict an outcome, interpret a result, or explore how changing a parameter affects generation. Pause to discuss their answers and connect these observations to the concepts being taught.
- Deadline for prepering the materials: Friday, 9th of October, 1PM
