<!-- -->
- <span class="badge">MLsys 2026</span> **BOOST: BOttleneck-Optimized Scalable Training Framework for Low-Rank Large Language Models** <br>
   <span class="underline"> Zhengyang Wang<sup>*</sup>, Ziyue Liu<sup>*</sup>, <b>Ruijie Zhang</b>, Avinash Maurya, Paul Hovland, Bogdan Nicolae, Franck Cappello, Zheng Zhang(<sup>*</sup> Equal contributions)<br>
  Ninth Annual Conference on Machine Learning and Systems (MLSys 2026) <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/abs/2512.12131" target="_blank" rel="noopener">pdf</a>
  </div>
  <div id="bib" class="bibbox" markdown="1"><pre><code class="language-bibtex">@article{wang2025boost,
  title={BOOST: BOttleneck-Optimized Scalable Training Framework for Low-Rank Large Language Models},
  author={Wang, Zhengyang and Liu, Ziyue and Zhang, Ruijie and Maurya, Avinash and Hovland, Paul and Nicolae, Bogdan and Cappello, Franck and Zhang, Zheng},
  journal={arXiv preprint arXiv:2512.12131},
  year={2025}
}, 
}</code></pre></div>
  <div id="abstract" class="bibbox" markdown="1"><pre><code class="language-bibtex">The scale of transformer model pre-training is constrained by the increasing computation and communication cost. Low-rank bottleneck architectures offer a promising solution to significantly reduce the training time and memory footprint with minimum impact on accuracy. Despite algorithmic efficiency, bottleneck architectures scale poorly under standard tensor parallelism. Simply applying 3D parallelism designed for full-rank methods leads to excessive communication and poor GPU utilization. To address this limitation, we propose BOOST, an efficient training framework tailored for large-scale low-rank bottleneck architectures. BOOST introduces a novel Bottleneck-aware Tensor Parallelism, and combines optimizations such as online-RMSNorm, linear layer grouping, and low-rank activation checkpointing to achieve end-to-end training speedup. Evaluations on different low-rank bottleneck architectures demonstrate that BOOST achieves 1.46-1.91× speedup over full-rank model baselines and 1.87-2.27× speedup over low-rank model with naively integrated 3D parallelism, with improved GPU utilization and reduced communication overhead.</code></pre></div>
