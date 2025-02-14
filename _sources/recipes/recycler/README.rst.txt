:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'recycler'
.. highlight: bash

recycler
========

.. conda:recipe:: recycler
   :replaces_section_title:

   Recycler is a tool designed for extracting circular sequences from de novo assembly graphs

   :homepage: https://github.com/Shamir-Lab/Recycler
   :license: BSD / BSD-3-Clause
   :recipe: /`recycler <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/recycler>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/recycler/meta.yaml>`_

   


.. conda:package:: recycler

   |downloads_recycler| |docker_recycler|

   :versions: 0.7-2, 0.7-0, 0.6.2-0, 0.6-0, 0.6p1-0
   
   :depends networkx: 
   :depends nose: 
   :depends numpy: 
   :depends pysam: 
   :depends python: >=2.7,<2.8.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install recycler

   and update with::

      conda update recycler

   or use the docker container::

      docker pull quay.io/biocontainers/recycler:<tag>

   (see `recycler/tags`_ for valid values for ``<tag>``)


.. |downloads_recycler| image:: https://img.shields.io/conda/dn/bioconda/recycler.svg?style=flat
   :target: https://anaconda.org/bioconda/recycler
   :alt:   (downloads)
.. |docker_recycler| image:: https://quay.io/repository/biocontainers/recycler/status
   :target: https://quay.io/repository/biocontainers/recycler
.. _`recycler/tags`: https://quay.io/repository/biocontainers/recycler?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/recycler/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/recycler/README.html