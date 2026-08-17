<!-- -->
- <span class="badge">COLM 2026</span> **MuonQ: Enhancing Low-Bit Muon Quantization via Directional Fidelity Optimization** <br>
  Yupeng Su, <span class="underline"><b>Ruijie Zhang</b></span>, Ziyue Liu, Yequan Zhao, Zheng Zhang <br>
  Conference on Language Modeling (COLM 2026) <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/abs/2605.11396" target="_blank" rel="noopener">pdf</a>
  <a class="newbadge red"  href="https://github.com/YupengSu/MuonQ" target="_blank" rel="noopener">code</a>
  </div>
  <div id="bib" class="bibbox" markdown="1"><pre><code class="language-bibtex">@article{su2026muonq,
  title={MuonQ: Enhancing Low-Bit Muon Quantization via Directional Fidelity Optimization},
  author={Su, Yupeng and Zhang, Ruijie and Liu, Ziyue and Zhao, Yequan and Zhang, Zheng},
  journal={arXiv preprint arXiv:2605.11396},
  year={2026}
}</code></pre></div>
  <div id="abstract" class="bibbox" markdown="1"><pre><code class="language-bibtex">The Muon optimizer has emerged as a compelling alternative to Adam for training large language models, achieving remarkable computational savings through gradient orthogonalization. However, Muon's optimizer state is more sensitive to quantization errors: because the orthogonalization discards the magnitudes of singular values and retains only directional information, even small quantization errors in singular vector directions are amplified in the update. In this work, we propose MuonQ, a low-bit Muon training framework built on the principle of directional fidelity optimization. First, we apply a pre-quantization normalization so that each step introduces quantization errors of the same magnitude, preventing the accumulated error from developing a preferred direction. Second, we introduce a structural decomposition that separately quantizes the dominant singular components via power iteration, ensuring that quantization errors perturb only singular value magnitudes rather than rotating singular vector directions. Third, we adopt the mu-law companding quantization to allocate higher resolution to densely packed momentum values, shifting the quantization objective from outlier preservation to dense-region distinguishability. Together, these techniques enable stable 4-bit quantization of Muon's optimizer states. Pre-training experiments on GPT-style and LLaMA-style models demonstrate that MuonQ at 4-bit precision recovers most of full-precision Muon's training loss and downstream accuracy while reducing optimizer-state memory by up to 7.3x, offering a favorable point on the accuracy-memory trade-off.</code></pre></div>
