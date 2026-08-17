<!-- -->
- <span class="badge">Preprint</span> **Muon<sup>2</sup>: Boosting Muon via Adaptive Second-Moment Preconditioning** <br>
  Ziyue Liu, <span class="underline"><b>Ruijie Zhang</b></span>, Zhengyang Wang, Yequan Zhao, Yupeng Su, Zi Yang, Zheng Zhang <br>
  arXiv 2026 <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/abs/2604.09967" target="_blank" rel="noopener">pdf</a>
  </div>
  <div id="bib" class="bibbox" markdown="1"><pre><code class="language-bibtex">@article{liu2026muon2,
  title={Muon$^2$: Boosting Muon via Adaptive Second-Moment Preconditioning},
  author={Liu, Ziyue and Zhang, Ruijie and Wang, Zhengyang and Zhao, Yequan and Su, Yupeng and Yang, Zi and Zhang, Zheng},
  journal={arXiv preprint arXiv:2604.09967},
  year={2026}
}</code></pre></div>
  <div id="abstract" class="bibbox" markdown="1"><pre><code class="language-bibtex">Muon has emerged as a promising optimizer for large-scale foundation model pre-training by exploiting the matrix structure of neural network updates through iterative orthogonalization. However, its practical efficiency is limited by the need for multiple Newton-Schulz (NS) iterations per optimization step, which introduces non-trivial computation and communication overhead. We propose Muon^2, an extension of Muon that applies Adam-style adaptive second-moment preconditioning before orthogonalization. Our key insight is that the core challenge of polar approximation in Muon lies in the ill-conditioned momentum matrix, of which the spectrum is substantially improved by Muon^2, leading to faster convergence toward a practically sufficient orthogonalization. We further characterize the practical orthogonalization quality via directional alignment, under which Muon^2 demonstrates dramatic improvement over Muon at each polar step. Across GPT and LLaMA pre-training experiments from 60M to 1.3B parameters, Muon^2 consistently outperforms Muon and recent Muon variants while reducing NS iterations by 40%. We further introduce Muon^2-F, a memory-efficient factorized variant that preserves most of the gains of Muon^2 with negligible memory overhead.</code></pre></div>
