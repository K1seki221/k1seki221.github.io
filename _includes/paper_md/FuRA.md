<!-- -->
- <span class="badge">Preprint</span> **FuRA: Full-Rank Parameter-Efficient Fine-Tuning with Spectral Preconditioning** <br>
  Yequan Zhao, <span class="underline"><b>Ruijie Zhang</b></span>, Liyan Tan, Niall Moran, Tong Qin, Zheng Zhang <br>
  arXiv 2026 <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/abs/2605.22869" target="_blank" rel="noopener">pdf</a>
  <a class="newbadge red"  href="https://github.com/olokevin/FuRA-NIPS" target="_blank" rel="noopener">code</a>
  </div>
  <div id="bib" class="bibbox" markdown="1"><pre><code class="language-bibtex">@article{zhao2026fura,
  title={FuRA: Full-Rank Parameter-Efficient Fine-Tuning with Spectral Preconditioning},
  author={Zhao, Yequan and Zhang, Ruijie and Tan, Liyan and Moran, Niall and Qin, Tong and Zhang, Zheng},
  journal={arXiv preprint arXiv:2605.22869},
  year={2026}
}</code></pre></div>
  <div id="abstract" class="bibbox" markdown="1"><pre><code class="language-bibtex">Both full fine-tuning (Full FT) and parameter-efficient methods like LoRA add weight updates without regard to the spectral structure that pretraining has established. This allows noisy gradients from a small fine-tuning distribution to freely perturb the robust features learned through pretraining. We first identify spectral preconditioning as the key missing ingredient: reparameterizing each weight W through its full-rank SVD and freezing one singular basis confines every update to the pretrained column space, yielding a preconditioned optimizer that outperforms unconstrained Full FT at the same parameter count. To make this insight practical, we propose FuRA (Full-Rank Adaptation), which factorizes W via a block tensor-train decomposition W=LSR: the large core L is frozen at the pretrained block-wise SVD basis while only the small core R and per-block singular values S are trained. This single design choice simultaneously delivers full-rank spectral preconditioning, full-rank update capacity, and parameter, step time, memory efficiency on par with LoRA. FuRA outperforms Full FT on LLM fine-tuning (+1.37 on LLaMA-3-8B commonsense reasoning), LLM math reinforcement learning, and VLM visual instruction tuning. The 4-bit quantized version QFuRA also outperforms QLoRA.</code></pre></div>
