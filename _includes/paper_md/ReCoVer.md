<!-- -->
- <span class="badge">Preprint</span> **ReCoVer: Resilient LLM Pre-Training System via Fault-Tolerant Collective and Versatile Workload** <br>
  Ziyue Liu, Zhengyang Wang, <span class="underline"><b>Ruijie Zhang</b></span>, Avinash Maurya, Hui Zhou, Paul Hovland, Sheng Di, Franck Cappello, Bogdan Nicolae, Zheng Zhang <br>
  arXiv 2026 <br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/abs/2605.11215" target="_blank" rel="noopener">pdf</a>
  </div>
  <div id="bib" class="bibbox" markdown="1"><pre><code class="language-bibtex">@article{liu2026recover,
  title={ReCoVer: Resilient LLM Pre-Training System via Fault-Tolerant Collective and Versatile Workload},
  author={Liu, Ziyue and Wang, Zhengyang and Zhang, Ruijie and Maurya, Avinash and Zhou, Hui and Hovland, Paul and Di, Sheng and Cappello, Franck and Nicolae, Bogdan and Zhang, Zheng},
  journal={arXiv preprint arXiv:2605.11215},
  year={2026}
}</code></pre></div>
  <div id="abstract" class="bibbox" markdown="1"><pre><code class="language-bibtex">Pre-training large language models on massive GPU clusters has made hardware faults routine rather than rare, driving the need for resilient training systems. Yet existing frameworks either focus on specific parallelism schemes or risk drifting away from a failure-free training trajectory. We propose ReCoVer, a resilient LLM pre-training system that upholds a single invariant: each iteration keeps the number of microbatches constant, ensuring per-iteration gradients remain stochastically equivalent to a failure-free run. The framework is organized as three decoupled protocol layers: (1) Fault-tolerant collectives that isolate faults from propagating across replicas; (2) in-step fine-grained recovery that preserves intra-iteration progress and prevents gradient corruption; (3) versatile-workload policy that dynamically redistributes microbatch quotas across the survivors. The design is parallelism-agnostic, integrating directly with both 3D parallelism and Hybrid Sharded Data Parallel (HSDP) as a drop-in substrate. We evaluate our implementation on end-to-end pre-training tasks for up to 512 GPUs, ReCoVer successfully preserves the training trajectory from a failure-free reference despite of 256 GPUs lost spread across the run. For comparison with checkpoint-and-restart baselines, ReCoVer demonstrates 2.23x higher effective throughput after successive failures. This advantage results in ReCoVer processing 74.9% more tokens at 234 GPU-hours, with the gap widening as the training prolongs.</code></pre></div>
