This repository contains the code for the `SC-MAMBA2` package for modeling single-cell transcriptome data.

In `our study <https://www.biorxiv.org/content/10.1101/2024.09.30.615775v1>`_, we applied the state-space model `MAMBA2 <https://arxiv.org/pdf/2405.21060>`_ to single-cell transcriptomics, developing the SC-MAMBA2 model. SC-MAMBA2 leverages the efficiency and scalability of state-space models (SSM), enabling it to handle ultra-long transcriptome sequences with lower computational cost.

The model was trained on a dataset of 57 million cells, making it the most comprehensive solution to date for processing ultra-long sequences. Extensive benchmarking across various downstream tasks consistently demonstrated SC-MAMBA2's superior performance compared to state-of-the-art models, showcasing exceptional accuracy and computational efficiency.

.. image:: https://raw.githubusercontent.com/GlancerZ/scMamba2/main/docs/model_arch.png
   :alt: Workflow
