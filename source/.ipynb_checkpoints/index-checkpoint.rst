:github_url: https://causalai.github.io/pytorch_geometric/

Causal AI Report
===============================


本 `项目 <https://heyanggong.github.io/tangjieReport/>`_ 是关于 Report invited by Tang Jie 的准备文档。 我们期望在这个项目中，

1. 把信息因果模型的理论构架阐述清楚，
2. 并且指出 VAE， Bayesian network, RNN 等都是 ICM 的特例。

我们把旨在通过 Judea Pearl 提出的小图灵测试的AI系统及其研究称为 Causal AI。 更多信息参见 `About Causal AI <https://github.com/CausalAI/AboutCausalAI>`_。


.. toctree:: 
   :glob:
   :maxdepth: 1
   :caption: 预备知识:

   notes/README
   notes/02-AI_overview
   notes/01-stat_compute
   notes/03-tools
   notes/04-Important_papers
   
.. toctree:: 
   :glob:
   :maxdepth: 1
   :caption: Info Causal Models:   

   InfoCausalModels
   
.. toctree::
   :glob:
   :maxdepth: 1
   :caption: 信息因果模型示例:
    
   models/01-ICM_using_Pyro 
   models/02-one_node
   
   

Indices and Tables
==================

* :ref:`genindex`
* :ref:`modindex`
