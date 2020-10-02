---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* Tseran, Hanna, et al. "Natural Variational Continual Learning." NeurIPS Workshop on Continual Learning, 2018.
* Tseran, Hanna, and Tatsuya Harada. "Variational Inference for Continual Learning by using Weight-Perturbation in Adam." Master's Thesis, 2018.
* Tseran, Hanna, and Tatsuya Harada. "Memory augmented neural network with Gaussian embeddings for one-shot learning." NIPS Workshop on Bayesian Deep Learning, 2017.
* Tseran, Hanna, and Yuri Svirid. "Algorithms for recognition of circular objects and elements on them (in case of coins)." Specialist Thesis, 2015. (In Russian)

You can also find some of my publications on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% if author.googlescholar %}
  You can also find some of my publications on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<div>
  <i>test</i>
  <div class="author__urls-wrapper">
    <button class="btn btn--inverse">Follow</button>
    <ul class="author__urls social-icons">
      {% if author.googlescholar %}
        <li><a href="{{ author.googlescholar }}"><i class="fas fa-fw fa-graduation-cap"></i> Google Scholar</a></li>
      {% endif %}
    </ul>
  </div>
</div>
