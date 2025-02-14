:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-meshsim'
.. highlight: bash

bioconductor-meshsim
====================

.. conda:recipe:: bioconductor-meshsim
   :replaces_section_title:

   Provide for measuring semantic similarity over MeSH headings and MEDLINE documents

   :homepage: http://bioconductor.org/packages/3.5/bioc/html/MeSHSim.html
   :license: GPL-2
   :recipe: /`bioconductor-meshsim <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-meshsim>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-meshsim/meta.yaml>`_
   :links: biotools: :biotools:`meshsim`, doi: :doi:`10.1142/S0219720015420020`

   


.. conda:package:: bioconductor-meshsim

   |downloads_bioconductor-meshsim| |docker_bioconductor-meshsim|

   :versions: 1.7.0-0
   
   :depends r-base: 3.3.2*
   :depends r-rcurl: 
   :depends r-xml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-meshsim

   and update with::

      conda update bioconductor-meshsim

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-meshsim:<tag>

   (see `bioconductor-meshsim/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-meshsim| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-meshsim.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-meshsim
   :alt:   (downloads)
.. |docker_bioconductor-meshsim| image:: https://quay.io/repository/biocontainers/bioconductor-meshsim/status
   :target: https://quay.io/repository/biocontainers/bioconductor-meshsim
.. _`bioconductor-meshsim/tags`: https://quay.io/repository/biocontainers/bioconductor-meshsim?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-meshsim/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-meshsim/README.html