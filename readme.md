
# Hybrid Random Features

This repo contains coding implementation of section 4.2 Language Modeling in the experimental section of our paper [Hybrid Random Features](https://arxiv.org/abs/2110.04367)


<img src="https://github.com/HL-hanlin/HRF_ICLR2022/blob/main/img/hrf.jpg" width="800px"></img>


## Abstract

We propose a new class of random feature methods for linearizing softmax and Gaussian kernels called hybrid random features (HRFs) that automatically adapt the quality of kernel estimation to provide most accurate approximation in the defined regions of interest. Special instantiations of HRFs lead to well-known methods such as trigonometric (Rahimi and Recht, 2007) or (recently introduced in the context of linear-attention Transformers) positive random features (Choromanski et al., 2021). By generalizing Bochner's Theorem for softmax/Gaussian kernels and leveraging random features for compositional kernels, the HRF-mechanism provides strong theoretical guarantees - unbiased approximation and strictly smaller worst-case relative errors than its counterparts. We conduct exhaustive empirical evaluation of HRF ranging from pointwise kernel estimation experiments, through tests on data admitting clustering structure to benchmarking implicit-attention Transformers (also for downstream Robotics applications), demonstrating its quality in a wide spectrum of machine learning problems.


## Citations

```bibtex
@article{DBLP:journals/corr/abs-2110-04367,
  author    = {Krzysztof Choromanski and Haoxian Chen and Han Lin and Yuanzhe Ma and Arijit Sehanobish and Deepali Jain and Michael S. Ryoo and Jake Varley and  Andy Zeng and Valerii Likhosherstov and Dmitry Kalashnikov and Vikas Sindhwani and Adrian Weller},
  title     = {Hybrid Random Features},
  journal   = {CoRR},
  volume    = {abs/2110.04367},
  year      = {2021},
  url       = {https://arxiv.org/abs/2110.04367},
  eprinttype = {arXiv},
  eprint    = {2110.04367},
  timestamp = {Thu, 21 Oct 2021 16:20:08 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-2110-04367.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```
