:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-breastcancerupp'
.. highlight: bash

bioconductor-breastcancerupp
============================

.. conda:recipe:: bioconductor-breastcancerupp
   :replaces_section_title:

   Gene expression data from a breast cancer study published by Miller et al. in 2005\, provided as an eSet.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/breastCancerUPP.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-breastcancerupp <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-breastcancerupp>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-breastcancerupp/meta.yaml>`_

   


.. conda:package:: bioconductor-breastcancerupp

   |downloads_bioconductor-breastcancerupp| |docker_bioconductor-breastcancerupp|

   :versions: 1.22.0-1, 1.22.0-0, 1.20.0-0
   
   :depends curl: >=7.65.2,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-breastcancerupp

   and update with::

      conda update bioconductor-breastcancerupp

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-breastcancerupp:<tag>

   (see `bioconductor-breastcancerupp/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-breastcancerupp| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-breastcancerupp.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-breastcancerupp
   :alt:   (downloads)
.. |docker_bioconductor-breastcancerupp| image:: https://quay.io/repository/biocontainers/bioconductor-breastcancerupp/status
   :target: https://quay.io/repository/biocontainers/bioconductor-breastcancerupp
.. _`bioconductor-breastcancerupp/tags`: https://quay.io/repository/biocontainers/bioconductor-breastcancerupp?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-breastcancerupp/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-breastcancerupp/README.html