:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hybridmtest'
.. highlight: bash

bioconductor-hybridmtest
========================

.. conda:recipe:: bioconductor-hybridmtest
   :replaces_section_title:

   Performs hybrid multiple testing that incorporates method selection and assumption evaluations into the analysis using empirical Bayes probability \(EBP\) estimates obtained by Grenander density estimation. For instance\, for 3\-group comparison analysis\, Hybrid Multiple testing considers EBPs as weighted EBPs between F\-test and H\-test with EBPs from Shapiro Wilk test of normality as weigth. Instead of just using EBPs from F\-test only or using H\-test only\, this methodology combines both types of EBPs through EBPs from Shapiro Wilk test of normality. This methodology uses then the law of total EBPs.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/HybridMTest.html
   :license: GPL Version 2 or later
   :recipe: /`bioconductor-hybridmtest <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hybridmtest>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hybridmtest/meta.yaml>`_
   :links: biotools: :biotools:`hybridmtest`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-hybridmtest

   |downloads_bioconductor-hybridmtest| |docker_bioconductor-hybridmtest|

   :versions: 1.28.0-1, 1.26.0-0, 1.24.0-0, 1.22.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-fdrtool: 
   :depends r-mass: 
   :depends r-survival: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hybridmtest

   and update with::

      conda update bioconductor-hybridmtest

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hybridmtest:<tag>

   (see `bioconductor-hybridmtest/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hybridmtest| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hybridmtest.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hybridmtest
   :alt:   (downloads)
.. |docker_bioconductor-hybridmtest| image:: https://quay.io/repository/biocontainers/bioconductor-hybridmtest/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hybridmtest
.. _`bioconductor-hybridmtest/tags`: https://quay.io/repository/biocontainers/bioconductor-hybridmtest?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hybridmtest/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hybridmtest/README.html