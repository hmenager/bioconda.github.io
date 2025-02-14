:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'nucleoatac'
.. highlight: bash

nucleoatac
==========

.. conda:recipe:: nucleoatac
   :replaces_section_title:

   Python package for calling nucleosomes using ATAC\-Seq data. Also includes general scripts for working with paired\-end ATAC\-Seq data \(or potentially other paired\-end data\).

   :homepage: https://github.com/GreenleafLab/NucleoATAC
   :documentation: http://nucleoatac.readthedocs.io/en/latest/
   
   :license: MIT / MIT
   :recipe: /`nucleoatac <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/nucleoatac>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/nucleoatac/meta.yaml>`_
   :links: doi: :doi:`10.1101/gr.192294.115`

   


.. conda:package:: nucleoatac

   |downloads_nucleoatac| |docker_nucleoatac|

   :versions: 0.3.4-2, 0.3.4-1, 0.3.4-0, 0.3.1-0
   
   :depends cython: >=0.22
   :depends matplotlib: 
   :depends numpy: >=1.9.1
   :depends pysam: >=0.8.1
   :depends python: <3
   :depends scipy: 
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install nucleoatac

   and update with::

      conda update nucleoatac

   or use the docker container::

      docker pull quay.io/biocontainers/nucleoatac:<tag>

   (see `nucleoatac/tags`_ for valid values for ``<tag>``)


.. |downloads_nucleoatac| image:: https://img.shields.io/conda/dn/bioconda/nucleoatac.svg?style=flat
   :target: https://anaconda.org/bioconda/nucleoatac
   :alt:   (downloads)
.. |docker_nucleoatac| image:: https://quay.io/repository/biocontainers/nucleoatac/status
   :target: https://quay.io/repository/biocontainers/nucleoatac
.. _`nucleoatac/tags`: https://quay.io/repository/biocontainers/nucleoatac?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/nucleoatac/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/nucleoatac/README.html