# RB-Modulation-Replication

This is a community effort to replicate the RB-Modulation project.
## Resources

- [Link to the RB-Modulation paper](https://arxiv.org/pdf/2405.17401)
- [Link to the original project description](https://github.com/LituRout/RB-Modulation)
- [Link to Würstchen repository](https://github.com/dome272/Wuerstchen)

## Project Description

RB-Modulation is a plug-and-play solution for (a) stylization with various prompts, and (b) composition with reference content images while maintaining sample diversity and prompt alignment by [Litu Rout](https://github.com/LituRout). The official code is not yet released, and this repository aims to collaboratively reproduce the project based on the available resources.

## Pre-trained Würstchen Models

RB-Modulation utilizes the pre-trained weights from the [Würstchen model](https://github.com/dome272/Wuerstchen). You can download the models from the following links:

### Würstchen v1
- **Download**: [Hugging Face](https://huggingface.co/dome272/wuerstchen)
- **Parameters**: 1B (Stage C) + 600M (Stage B) + 19M (Stage A)
- **Conditioning**: CLIP-H-Text
- **Training Steps**: 800,000
- **Resolution**: 512x512

### Würstchen v2
- **Download**: [Hugging Face](https://huggingface.co/dome272/wuerstchen)
- **Parameters**: 1B (Stage C) + 600M (Stage B) + 19M (Stage A)
- **Conditioning**: CLIP-bigG-Text
- **Training Steps**: 918,000
- **Resolution**: 1024x1024

## CSD: High-Performance Style Feature Extractor

RB-Modulation uses CSD (Contrastive Style Descriptor) as a style feature extractor. CSD creates a high-performance model for representing style and outperforms other large-scale pre-trained models and prior style retrieval methods on standard datasets. Using CSD, we examine the extent of style replication in the popular open-source text-to-image generative model Stable Diffusion, and consider different factors that impact the rate of style replication.

- **CSD Repository**: [GitHub](https://github.com/learn2phoenix/CSD)
- **CSD Paper**: [arXiv](https://arxiv.org/abs/2404.01292)

## How to Contribute

We welcome contributions in the following areas:
- Code implementation
- Testing
- Documentation
- Code reviews

## Getting Started

1. Fork the repository
2. Clone your forked repository
3. Create a new branch for your feature or bugfix
4. Commit your changes and push them to your fork
5. Create a pull request








