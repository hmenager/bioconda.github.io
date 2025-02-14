:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-flowsorted.cordbloodcombined.450k'
.. highlight: bash

bioconductor-flowsorted.cordbloodcombined.450k
==============================================

.. conda:recipe:: bioconductor-flowsorted.cordbloodcombined.450k
   :replaces_section_title:

   Raw data objects to be used for umbilical cord blood cell proportion estimation in minfi and similar packages. The FlowSorted.CordBloodCombined.450k object is based in samples assayed by Bakulski et al\, Gervin et al.\, de Goede et al.\, and Lin et al.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/FlowSorted.CordBloodCombined.450k.html
   :license: GPL-3
   :recipe: /`bioconductor-flowsorted.cordbloodcombined.450k <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-flowsorted.cordbloodcombined.450k>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-flowsorted.cordbloodcombined.450k/meta.yaml>`_

   


.. conda:package:: bioconductor-flowsorted.cordbloodcombined.450k

   |downloads_bioconductor-flowsorted.cordbloodcombined.450k| |docker_bioconductor-flowsorted.cordbloodcombined.450k|

   :versions: 1.0.0-1
   
   :depends bioconductor-experimenthub: >=1.10.0,<1.11.0
   :depends bioconductor-flowsorted.blood.epic: >=1.2.0,<1.3.0
   :depends bioconductor-illuminahumanmethylation450kanno.ilmn12.hg19: >=0.6.0,<0.7.0
   :depends bioconductor-illuminahumanmethylationepicanno.ilm10b4.hg19: >=0.6.0,<0.7.0
   :depends bioconductor-minfi: >=1.30.0,<1.31.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-flowsorted.cordbloodcombined.450k

   and update with::

      conda update bioconductor-flowsorted.cordbloodcombined.450k

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-flowsorted.cordbloodcombined.450k:<tag>

   (see `bioconductor-flowsorted.cordbloodcombined.450k/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-flowsorted.cordbloodcombined.450k| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-flowsorted.cordbloodcombined.450k.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-flowsorted.cordbloodcombined.450k
   :alt:   (downloads)
.. |docker_bioconductor-flowsorted.cordbloodcombined.450k| image:: https://quay.io/repository/biocontainers/bioconductor-flowsorted.cordbloodcombined.450k/status
   :target: https://quay.io/repository/biocontainers/bioconductor-flowsorted.cordbloodcombined.450k
.. _`bioconductor-flowsorted.cordbloodcombined.450k/tags`: https://quay.io/repository/biocontainers/bioconductor-flowsorted.cordbloodcombined.450k?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-flowsorted.cordbloodcombined.450k/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-flowsorted.cordbloodcombined.450k/README.html