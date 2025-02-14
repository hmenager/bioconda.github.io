:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'viennarna'
.. highlight: bash

viennarna
=========

.. conda:recipe:: viennarna
   :replaces_section_title:

   Vienna RNA package \-\- RNA secondary structure prediction and comparison

   :homepage: http://www.tbi.univie.ac.at/RNA/
   :license: custom
   :recipe: /`viennarna <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/viennarna>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/viennarna/meta.yaml>`_

   


.. conda:package:: viennarna

   |downloads_viennarna| |docker_viennarna|

   :versions: 2.4.14-0, 2.4.13-2, 2.4.11-2, 2.4.11-1, 2.4.11-0, 2.4.9-0, 2.4.8-2, 2.4.8-1, 2.4.8-0, 2.4.7-5, 2.4.7-4, 2.4.7-3, 2.4.7-2, 2.4.6-1, 2.4.6-0, 2.4.5-3, 2.4.5-2, 2.4.5-1, 2.4.5-0, 2.4.4-3, 2.4.4-1, 2.4.4-0, 2.4.3-2, 2.4.3-0, 2.4.2-3, 2.4.2-1, 2.4.1-3, 2.4.1-1, 2.4.1-0, 2.3.5-2, 2.3.5-0, 2.3.3-2, 2.3.3-0, 2.3.2-2, 2.3.2-0, 2.3.1-3, 2.3.1-1, 2.3.1-0, 2.3.0-3, 2.3.0-1, 2.2.10-3, 2.2.10-1, 2.2.10-0, 2.2.9-0, 2.2.8-0, 2.2.7-0, 2.2.5-3, 2.2.5-2, 2.2.5-0, 2.1.9-1, 2.1.9-0, 2.1.8-0, 2.1.5-0, 1.8.5-1, 1.8.5-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends python: >=2.7,<2.8.0a0
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install viennarna

   and update with::

      conda update viennarna

   or use the docker container::

      docker pull quay.io/biocontainers/viennarna:<tag>

   (see `viennarna/tags`_ for valid values for ``<tag>``)


.. |downloads_viennarna| image:: https://img.shields.io/conda/dn/bioconda/viennarna.svg?style=flat
   :target: https://anaconda.org/bioconda/viennarna
   :alt:   (downloads)
.. |docker_viennarna| image:: https://quay.io/repository/biocontainers/viennarna/status
   :target: https://quay.io/repository/biocontainers/viennarna
.. _`viennarna/tags`: https://quay.io/repository/biocontainers/viennarna?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/viennarna/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/viennarna/README.html