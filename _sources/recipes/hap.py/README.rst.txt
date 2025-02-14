:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'hap.py'
.. highlight: bash

hap.py
======

.. conda:recipe:: hap.py
   :replaces_section_title:

   Haplotype VCF comparison tools

   :homepage: https://github.com/Illumina/hap.py
   :license: BSD / BSD-2-Clause
   :recipe: /`hap.py <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/hap.py>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/hap.py/meta.yaml>`_

   


.. conda:package:: hap.py

   |downloads_hap.py| |docker_hap.py|

   :versions: 0.3.10-0, 0.3.7-1, 0.3.7-0, 0.2.9-1, 0.2.9-0
   
   :depends bcftools: 
   :depends bx-python: 
   :depends cython: 
   :depends libgcc: 
   :depends nose: 
   :depends numpy: 
   :depends pandas: 
   :depends pybedtools: 
   :depends pysam: 
   :depends python: 2.7*
   :depends samtools: 
   :depends scipy: 
   :depends zlib: 1.2.11*
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install hap.py

   and update with::

      conda update hap.py

   or use the docker container::

      docker pull quay.io/biocontainers/hap.py:<tag>

   (see `hap.py/tags`_ for valid values for ``<tag>``)


.. |downloads_hap.py| image:: https://img.shields.io/conda/dn/bioconda/hap.py.svg?style=flat
   :target: https://anaconda.org/bioconda/hap.py
   :alt:   (downloads)
.. |docker_hap.py| image:: https://quay.io/repository/biocontainers/hap.py/status
   :target: https://quay.io/repository/biocontainers/hap.py
.. _`hap.py/tags`: https://quay.io/repository/biocontainers/hap.py?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/hap.py/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/hap.py/README.html