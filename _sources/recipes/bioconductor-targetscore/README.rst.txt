:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-targetscore'
.. highlight: bash

bioconductor-targetscore
========================

.. conda:recipe:: bioconductor-targetscore
   :replaces_section_title:

   Infer the posterior distributions of microRNA targets by probabilistically modelling the likelihood microRNA\-overexpression fold\-changes and sequence\-based scores. Variaitonal Bayesian Gaussian mixture model \(VB\-GMM\) is applied to log fold\-changes and sequence scores to obtain the posteriors of latent variable being the miRNA targets. The final targetScore is computed as the sigmoid\-transformed fold\-change weighted by the averaged posteriors of target components over all of the features.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/TargetScore.html
   :license: GPL-2
   :recipe: /`bioconductor-targetscore <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-targetscore>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-targetscore/meta.yaml>`_
   :links: biotools: :biotools:`targetscore`, doi: :doi:`10.1093/bioinformatics/btt599`

   


.. conda:package:: bioconductor-targetscore

   |downloads_bioconductor-targetscore| |docker_bioconductor-targetscore|

   :versions: 1.22.0-1, 1.22.0-0, 1.20.0-0, 1.18.0-0, 1.16.0-0, 1.14.0-0
   
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-matrix: 
   :depends r-pracma: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-targetscore

   and update with::

      conda update bioconductor-targetscore

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-targetscore:<tag>

   (see `bioconductor-targetscore/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-targetscore| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-targetscore.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-targetscore
   :alt:   (downloads)
.. |docker_bioconductor-targetscore| image:: https://quay.io/repository/biocontainers/bioconductor-targetscore/status
   :target: https://quay.io/repository/biocontainers/bioconductor-targetscore
.. _`bioconductor-targetscore/tags`: https://quay.io/repository/biocontainers/bioconductor-targetscore?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-targetscore/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-targetscore/README.html