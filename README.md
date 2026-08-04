# Aryan Sharan Reddy Guda

I'm a Master's student in Quantitative Biology and Bioinformatics at Carnegie Mellon,
working on generative models for proteins.

Right now I'm a graduate researcher in the Chiu Lab at
[UPMC Hillman Cancer Center](https://hillman.upmc.com/), on multimodal
representation learning that ties together
Cell Painting morphology, drug structure, and protein sequence. Before CMU I did a double
major in Biotechnology & Bioinformatics and Electrical Engineering at IIT Hyderabad.

**[gasredx09.github.io](https://gasredx09.github.io/)** &nbsp;·&nbsp;
[LinkedIn](https://www.linkedin.com/in/gasredx09/) &nbsp;·&nbsp;
[X](https://x.com/gasredX_09) &nbsp;·&nbsp;
aryanshg@andrew.cmu.edu

### A few things I've built

- **[TuneDiMA](https://github.com/gasredX09/TuneDiMA)**: parameter-efficient fine-tuning of
  DiMA, a latent diffusion model for protein sequences, so generation can be conditioned on
  protein family and function instead of being unguided.

- **[cafa6-protein-function-prediction](https://github.com/gasredX09/cafa6-protein-function-prediction)**:
  predicting GO terms straight from amino-acid sequence. ESM-2 embeddings and a DIAMOND
  k-NN baseline, ensembled and max-propagated over the GO DAG.

- **[protein-backbone-structural-validation](https://github.com/gasredX09/protein-backbone-structural-validation)**:
  do generated backbones actually hold up? CCTBX Ramachandran and MolProbity clashscore
  analysis across 100 structures from La-Proteina and ReQFlow.

- **[pLaTeX](https://github.com/gasredX09/pLaTeX)**: a LaTeX speed-typesetting game. It runs a
  real TeX Live 2025 engine in WebAssembly and grades you by compiling both your source and
  the target, then comparing the two pages pixel for pixel. Anything that typesets
  identically is accepted.

- **[Genome2Clusters](https://github.com/gasredX09/Genome2Clusters)**: clustering 6,129
  predicted proteins from the *Mycoplasma genitalium* genome on physicochemical properties
  alone, then checking against BLAST to see whether composition carries functional signal.

Mostly Python and PyTorch, on PSC Bridges-2 when things need GPUs.
