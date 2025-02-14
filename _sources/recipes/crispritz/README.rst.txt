:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'crispritz'
.. highlight: bash

crispritz
=========

.. conda:recipe:: crispritz
   :replaces_section_title:

   CRISPRitz\, tool package for CRISPR experiments assessment and analysis.

   :homepage: https://github.com/pinellolab/CRISPRitz
   :license: GPL3
   :recipe: /`crispritz <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/crispritz>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/crispritz/meta.yaml>`_

   


.. conda:package:: crispritz

   |downloads_crispritz| |docker_crispritz|

   :versions: 2.1.1-0, 2.1.0-0, 1.2.1-0, 1.2.0-0, 1.1.1-1, 1.1.1-0, 1.1.0-1, 1.1.0-0, 1.0.5-0, 1.0.3-0
   
   :depends bcftools: 
   :depends bedtools: 
   :depends biopython: 
   :depends boost: >=1.70.0,<1.70.1.0a0
   :depends intervaltree: 
   :depends libcxx: 
   :depends libdeflate: >=1.0,<1.1.0a0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends matplotlib: 
   :depends more-itertools: 
   :depends numpy: 
   :depends openmp: 
   :depends pandas: 
   :depends python: >=3.6,<3.7.0a0
   :depends scikit-learn: 0.21.2.*
   :depends scipy: 
   :depends statsmodels: 
   :depends tk: >=8.6.9,<8.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install crispritz

   and update with::

      conda update crispritz

   or use the docker container::

      docker pull quay.io/biocontainers/crispritz:<tag>

   (see `crispritz/tags`_ for valid values for ``<tag>``)


.. |downloads_crispritz| image:: https://img.shields.io/conda/dn/bioconda/crispritz.svg?style=flat
   :target: https://anaconda.org/bioconda/crispritz
   :alt:   (downloads)
.. |docker_crispritz| image:: https://quay.io/repository/biocontainers/crispritz/status
   :target: https://quay.io/repository/biocontainers/crispritz
.. _`crispritz/tags`: https://quay.io/repository/biocontainers/crispritz?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/crispritz/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/crispritz/README.html