<!-- -->
- <span class="badge">Preprint</span> **GRZO: Group-Relative Zeroth-Order Optimization for Large Language Model Fine-Tuning** <br>
  Liyan Tan, Yequan Zhao, Yifan Yang, <span class="underline"><b>Ruijie Zhang</b></span>, Xinling Yu, Zheng Zhang <br>
  arXiv 2026 <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/abs/2606.02857" target="_blank" rel="noopener">pdf</a>
  </div>
  <div id="bib" class="bibbox" markdown="1"><pre><code class="language-bibtex">@article{tan2026grzo,
  title={GRZO: Group-Relative Zeroth-Order Optimization for Large Language Model Fine-Tuning},
  author={Tan, Liyan and Zhao, Yequan and Yang, Yifan and Zhang, Ruijie and Yu, Xinling and Zhang, Zheng},
  journal={arXiv preprint arXiv:2606.02857},
  year={2026}
}</code></pre></div>
  <div id="abstract" class="bibbox" markdown="1"><pre><code class="language-bibtex">Zeroth-order (ZO) optimization is a memory-efficient alternative to backpropagation for fine-tuning large language models, but its deployment is limited by the high variance of gradient estimation. We propose GRZO, a Group-Relative Zeroth-Order optimizer that draws one pseudo-independent perturbation per minibatch example and aggregates the per-example losses through group-relative normalization, raising the effective gradient-direction count from one to the batch size at no additional forward cost while preserving inference-level memory. We prove that GRZO is directionally unbiased with variance shrinking proportionally to the batch size, yielding a tighter nonconvex convergence bound than MeZO. Across RoBERTa-large, Llama3-8B, and OPT-13B over multiple tasks, GRZO improves average accuracy on Llama 3-8B by +3.0 over MeZO at 23% lower peak GPU memory; as a drop-in replacement for the MeZO core, it lifts sparse, low-rank, and quantized ZO variants by +6.0 on average.</code></pre></div>
