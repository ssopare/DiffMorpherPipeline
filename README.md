# DiffMorpherPipeline

**LaTeX source for the research paper**:  
**"DiffMorpher-GELU: Enhancing Diffusion Models with GELU for Seamless and High-Fidelity Image Morphing"**  
**Author:** Simon Opare  
**Institution:** Kwame Nkrumah University of Science and Technology (KNUST)

---

## Overview

This repository contains the LaTeX source code for the paper that introduces **DiffMorpher-GELU**, a novel pipeline that enhances image morphing with diffusion models. By integrating the Gaussian Error Linear Unit (GELU) activation into Stable Diffusion’s UNet architecture, the proposed framework achieves smoother semantic interpolation and higher-fidelity image transitions compared to existing GAN and diffusion-based methods.

**Key contributions include:**
- Incorporation of GELU activation into the diffusion model UNet.
- LoRA parameter interpolation between two input images.
- Latent noise spherical interpolation for natural transitions.
- Self-attention key-value interpolation and AdaIN normalization.
- Adaptive sampling rescheduling to ensure uniform transition speed.
- Creation and evaluation on a benchmark dataset, **MorphBench**.

---

## File Structure

- `DiffMorpher_GELU_Complete_SimonOpare.tex` – Main LaTeX document for the full paper.
- `figures/` – (Optional) Folder for any figures used in the paper.
- `README.md` – This documentation file.

---

## How to Compile

To generate the PDF from the LaTeX file:

```bash
pdflatex DiffMorpher_GELU_Complete_SimonOpare.tex
