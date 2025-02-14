:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-nanotubes'
.. highlight: bash

bioconductor-nanotubes
======================

.. conda:recipe:: bioconductor-nanotubes
   :replaces_section_title:

   Cap Analysis of Gene Expression \(CAGE\) data from \"Identification of Gene Transcription Start Sites and Enhancers Responding to Pulmonary Carbon Nanotube Exposure in Vivo\" by Bornholdt et al. supplied as CAGE Transcription Start Sites \(CTSSs\).

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/nanotubes.html
   :license: GPL-3
   :recipe: /`bioconductor-nanotubes <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-nanotubes>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-nanotubes/meta.yaml>`_

   


.. conda:package:: bioconductor-nanotubes

   |downloads_bioconductor-nanotubes| |docker_bioconductor-nanotubes|

   :versions: 1.0.0-1
   
   :depends curl: >=7.64.1,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-nanotubes

   and update with::

      conda update bioconductor-nanotubes

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-nanotubes:<tag>

   (see `bioconductor-nanotubes/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-nanotubes| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-nanotubes.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-nanotubes
   :alt:   (downloads)
.. |docker_bioconductor-nanotubes| image:: https://quay.io/repository/biocontainers/bioconductor-nanotubes/status
   :target: https://quay.io/repository/biocontainers/bioconductor-nanotubes
.. _`bioconductor-nanotubes/tags`: https://quay.io/repository/biocontainers/bioconductor-nanotubes?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-nanotubes/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-nanotubes/README.html