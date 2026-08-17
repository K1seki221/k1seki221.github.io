<!-- -->
- <span class="badge">Preprint</span> **TEON: Tensorized Orthonormalization Beyond Layer-Wise Muon for Large Language Model Pre-Training** <br>
  <span class="underline"><b>Ruijie Zhang</b></span>, Yequan Zhao, Ziyue Liu, Zhengyang Wang, Dongyang Li, Yupeng Su, Sijia Liu, Zheng Zhang <br>
  arXiv 2026 <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/abs/2601.23261" target="_blank" rel="noopener">pdf</a>
  </div>
  <div id="bib" class="bibbox" markdown="1"><pre><code class="language-bibtex">@article{zhang2026teon,
  title={TEON: Tensorized Orthonormalization Beyond Layer-Wise Muon for Large Language Model Pre-Training},
  author={Zhang, Ruijie and Zhao, Yequan and Liu, Ziyue and Wang, Zhengyang and Li, Dongyang and Su, Yupeng and Liu, Sijia and Zhang, Zheng},
  journal={arXiv preprint arXiv:2601.23261},
  year={2026}
}</code></pre></div>
  <div id="abstract" class="bibbox" markdown="1"><pre><code class="language-bibtex">The Muon optimizer has demonstrated strong empirical performance in pre-training large language models by performing matrix-level gradient (or momentum) orthogonalization in each layer independently. In this work, we propose TEON, a principled generalization of Muon that extends orthogonalization beyond individual layers by modeling the gradients of a neural network as a structured higher-order tensor. We present TEON's improved convergence guarantee over layer-wise Muon, and further develop a practical instantiation of TEON based on the theoretical analysis with corresponding ablation. We evaluate our approach on two widely adopted architectures: GPT-style models, ranging from 130M to 774M parameters, and LLaMA-style models, ranging from 60M to 1B parameters. Experimental results show that TEON consistently improves training and validation perplexity across model scales and exhibits strong robustness under various approximate SVD schemes.</code></pre></div>
