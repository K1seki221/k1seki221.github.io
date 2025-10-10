<!-- -->
- <span class="badge">Preprint</span> **Rényi Sharpness: A Novel Sharpness that Strongly Correlates with Generalization** <br>
  Qiaozhe Zhang, Jun Sun, <span class="underline"><b>Ruijie Zhang</b></span>, Yingzhuang Liu <br>
  arXiv 2025 (Submitted to ICLR 2025)<br>
  <div class="newbadges" id="tabs" data-open="">
  <button class="newbadge green"  type="button" data-tab="bib">bib</button>
  <button class="newbadge orange" type="button" data-tab="abstract">abstract</button>
  <a class="newbadge blue" href="https://arxiv.org/pdf/2510.07758" target="_blank" rel="noopener">pdf</a>
  <a class="newbadge red"  href="https://github.com/QiaozheZhang/RSAM" target="_blank" rel="noopener">code</a>
  </div>
  <div id="bib" class="bibbox" markdown="1"><pre><code class="language-bibtex">@misc{zhang2025renyisharpnessnovelsharpness,
      title={R\'enyi Sharpness: A Novel Sharpness that Strongly Correlates with Generalization}, 
      author={Qiaozhe Zhang and Jun Sun and Ruijie Zhang and Yingzhuang Liu},
      year={2025},
      eprint={2510.07758},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2510.07758}, 
}</code></pre></div>
  <div id="abstract" class="bibbox" markdown="1"><pre><code class="language-bibtex">Sharpness (of the loss minima) is a common measure to investigate the generalization of neural networks. Intuitively speaking, the flatter the landscape near the minima is, the better generalization might be. Unfortunately, the correlation between many existing sharpness measures and the generalization is usually not strong, sometimes even weak. To close the gap between the intuition and the reality, we propose a novel sharpness measure, i.e., \textit{Rényi sharpness}, which is defined as the negative Rényi entropy (a generalization of the classical Shannon entropy) of the loss Hessian. The main ideas are as follows: 1) we realize that \textit{uniform} (identical) eigenvalues of the loss Hessian is most desirable (while keeping the sum constant) to achieve good generalization; 2) we employ the \textit{Rényi entropy} to concisely characterize the extent of the spread of the eigenvalues of loss Hessian. Normally, the larger the spread, the smaller the (Rényi) entropy. To rigorously establish the relationship between generalization and (Rényi) sharpness, we provide several generalization bounds in terms of Rényi sharpness, by taking advantage of the reparametrization invariance property of Rényi sharpness, as well as the trick of translating the data discrepancy to the weight perturbation. Furthermore, extensive experiments are conducted to verify the strong correlation (in specific, Kendall rank correlation) between the Rényi sharpness and generalization. Moreover, we propose to use a variant of Rényi Sharpness as regularizer during training, i.e., Rényi Sharpness Aware Minimization (RSAM), which turns out to outperform all existing sharpness-aware minimization methods. It is worthy noting that the test accuracy gain of our proposed RSAM method could be as high as nearly 2.5%, compared against the classical SAM method.</code></pre></div>
