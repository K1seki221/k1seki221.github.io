<!-- -->
- <span class="badge">Preprint</span> **Rényi Entropy: A New Token Pruning Metric for Vision Transformers** <br>
  Wei-Yuan Su, <span class="underline"><b>Ruijie Zhang</b></span><sup>&dagger;</sup>, Zheng Zhang (<sup>&dagger;</sup> Project supervision) <br>
  arXiv 2026 <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/abs/2603.27900" target="_blank" rel="noopener">pdf</a>
  </div>
  <div id="bib" class="bibbox" markdown="1"><pre><code class="language-bibtex">@article{su2026renyientropy,
  title={R\'enyi Entropy: A New Token Pruning Metric for Vision Transformers},
  author={Su, Wei-Yuan and Zhang, Ruijie and Zhang, Zheng},
  journal={arXiv preprint arXiv:2603.27900},
  year={2026}
}</code></pre></div>
  <div id="abstract" class="bibbox" markdown="1"><pre><code class="language-bibtex">Vision Transformers (ViTs) achieve state-of-the-art performance but suffer from the O(N^2) complexity of self-attention, making inference costly for high-resolution inputs. To address this bottleneck, token pruning has emerged as a critical technique to accelerate inference. Most existing methods rely on the [CLS] token to estimate patch importance. However, we argue that [CLS] token can be unreliable in early layers where semantic representations are still immature. As a result, pruning in the early layer often leads to inaccurate importance estimation and unnecessary information loss. In this work, we propose a training-free token importance metric, namely Col-Ln, which is derived from Renyi entropy that enables the identification of informative tokens from the first layer of the network, thereby enabling more reliable pruning in token reduction. Extensive experiments on ViTs and Large Vision-Language Models (LVLMs) demonstrate that our approach consistently outperforms state-of-the-art pruning methods across diverse benchmarks.</code></pre></div>
