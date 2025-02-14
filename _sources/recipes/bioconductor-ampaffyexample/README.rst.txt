:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ampaffyexample'
.. highlight: bash

bioconductor-ampaffyexample
===========================

.. conda:recipe:: bioconductor-ampaffyexample
   :replaces_section_title:

   Six arrays. Three from amplified RNA\, three from the typical procedure.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/AmpAffyExample.html
   :license: LGPL (>= 2)
   :recipe: /`bioconductor-ampaffyexample <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ampaffyexample>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ampaffyexample/meta.yaml>`_

   


.. conda:package:: bioconductor-ampaffyexample

   |downloads_bioconductor-ampaffyexample| |docker_bioconductor-ampaffyexample|

   :versions: 1.24.0-1, 1.22.0-0
   
   :depends bioconductor-affy: >=1.62.0,<1.63.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ampaffyexample

   and update with::

      conda update bioconductor-ampaffyexample

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ampaffyexample:<tag>

   (see `bioconductor-ampaffyexample/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ampaffyexample| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ampaffyexample.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ampaffyexample
   :alt:   (downloads)
.. |docker_bioconductor-ampaffyexample| image:: https://quay.io/repository/biocontainers/bioconductor-ampaffyexample/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ampaffyexample
.. _`bioconductor-ampaffyexample/tags`: https://quay.io/repository/biocontainers/bioconductor-ampaffyexample?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ampaffyexample/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ampaffyexample/README.html