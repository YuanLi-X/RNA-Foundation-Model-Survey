# RNA-Foundation-Model-Survey


<!-- [![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url] -->
![](https://img.shields.io/badge/Status-building-brightgreen) 
![](https://img.shields.io/badge/PRs-Welcome-red) 

<h1 align="center">
  <br>
  <img src="png/logo.jpg" alt="Foundation Models in Transcriptomics" width="500">
</h1>

<p align="center">
  <strong><a href="#1papers-论文">Papers</a></strong> •
  <a href="#2.Survey (研究综述)">Research Survey</a> •
  <a href="#3.Datasets and Benchmarks (数据集与评测结果)">Dataset & benchmarks</a> •
  <a href="#4.Challenges (竞赛信息)">Challenges</a>
</p>


## 1.Papers (论文)

| Model | Release Time | Model_size | Architecture | Description | Paper Link | Model Link
| --- | --- | --- | --- | --- | --- | --- |
| RNABERT | 2022.02 | 515K | Transformer | | [[NAR Genomics Bioinformtics](https://academic.oup.com/nargab/article/4/1/lqac012/6534363)] | [[Code](https://huggingface.co/multimolecule/rnabert)]
| RNA-FM | 2022 | 23M | Transformer | | [[arxiv](https://arxiv.org/abs/2204.00300)] | [[Code](https://huggingface.co/multimolecule/rnafm?text=UAGC%3Cmask%3EUAUCAGACUGAUGUUG)]
| SpliceBERT | 2024 | 19.4M | Transformer | | [[Brief Bioinform](https://academic.oup.com/bib/article/25/3/bbae163/7644137?login=false)] | [[Code](https://huggingface.co/multimolecule/splicebert?text=UAGC%3Cmask%3EUAUCAGACUGAUGUUG)]
| RNA-MSM | 2024 | 95.9M | Transformer | | [[Nucleic Acids Research](https://academic.oup.com/nar/article/52/1/e3/7369930?login=false)] | [[Code](https://huggingface.co/multimolecule/rnamsm?text=GGUC%3Cmask%3ECUCUGGUUAGACCAGAUCUGAGCCU)]
| Omnigenome | 2024 | 186M | Transformer | | [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/35500)] | [[Code](https://huggingface.co/yangheng/OmniGenome-186M)]
| GenerRNA | 2024 |   | Transformer (decoder-only) | | [[PLOS](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0310814)] | [[Code](https://huggingface.co/pfnet/GenerRNA)]
| RfamGen | 2024 |   | VAE + covariance model | | [[Nature Methods](https://www.nature.com/articles/s41592-023-02148-8)]
| Bert2Ome | 2023 | 110M | CNN + Transformer | | [[IEEE/ACM Trans on Comput Biol Bioinform](https://ieeexplore.ieee.org/document/10018863)]


**Latest papers**: 

*Updated at 2025-11-18:*

- Language FMs
  - Simulations of Common Unsupervised Domain Adaptation Algorithms for Image Classification [[arxiv](https://arxiv.org/abs/2502.10694)]
  - RNABERT: Informative RNA base embedding for RNA structural alignment and clustering by deep representation learning. [[NAR Genomics Bioinformtics](https://academic.oup.com/nargab/article/4/1/lqac012/6534363)]
  - RNA-FM:  Interpretable RNA Foundation Model from Unannotated Data for Highly Accurate RNA Structure and Function Predictions [[arxiv](https://arxiv.org/abs/2204.00300)]
  - SpliceBERT: Self-supervised learning on millions of pre-mRNA sequences improves sequence-based RNA splicing prediction. [[Brief Bioinform](https://academic.oup.com/bib/article/25/3/bbae163/7644137?login=false)]
  - RNA-MSM: Multiple sequence alignment-based RNA language model and its application to structural inference. [[Nucleic Acids Research](https://academic.oup.com/nar/article/52/1/e3/7369930?login=false)]
  - Omnigenome: OmniGenome: Aligning RNA Sequences with Secondary Structures in Genomic Foundation Models. [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/35500)]
  - GenerRNA: GenerRNA: a generative pre-trained language model for de novo RNA design. [[PLOS](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0310814)]

- Vision FMs
  - RfamGen: Deep generative design of rna familysequences. [[Nature Methods](https://www.nature.com/articles/s41592-023-02148-8)]
- Multimodal FMs
  - Bert2Ome: BERT2OME: Prediction of 2′-O-Methylation Modifications From RNA Sequence by Transformer Architecture Based on BERT [[IEEE/ACM Trans on Comput Biol Bioinform](https://ieeexplore.ieee.org/document/10018863)]



## 2.Survey (研究综述)

- - -


## 3.Datasets and Benchmarks (数据集与评测结果)

- - -

## 4.Challenges (竞赛信息)


- - -


## Contributing (欢迎参与贡献)

If you are interested in contributing, please refer to [HERE](https://github.com/YuanLi-X/RNA-Foundation-Model-Survey/blob/main/CONTRIBUTING.md) for instructions in contribution.

- - -

### Copyright notice

> ***[Notes]This Github repo can be used by following the corresponding licenses. I want to emphasis that it may contain some PDFs or thesis, which were downloaded by me and can only be used for academic purposes. The copyrights of these materials are owned by corresponding publishers or organizations. All this are for better academic research. If any of the authors or publishers have concerns, please contact me to delete or replace them.***

[contributors-shield]: https://img.shields.io/github/contributors/jindongwang/transferlearning.svg?style=for-the-badge
[contributors-url]: https://github.com/jindongwang/transferlearning/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jindongwang/transferlearning.svg?style=for-the-badge
[forks-url]: https://github.com/jindongwang/transferlearning/network/members
[stars-shield]: https://img.shields.io/github/stars/jindongwang/transferlearning.svg?style=for-the-badge
[stars-url]: https://github.com/jindongwang/transferlearning/stargazers
[issues-shield]: https://img.shields.io/github/issues/jindongwang/transferlearning.svg?style=for-the-badge
[issues-url]: https://github.com/jindongwang/transferlearning/issues
[license-shield]: https://img.shields.io/github/license/jindongwang/transferlearning.svg?style=for-the-badge
[license-url]: https://github.com/jindongwang/transferlearning/blob/main/LICENSE.txt