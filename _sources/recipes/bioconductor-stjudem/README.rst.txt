:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-stjudem'
.. highlight: bash

bioconductor-stjudem
====================

.. conda:recipe:: bioconductor-stjudem
   :replaces_section_title:

   This is a microarray data set on acute lymphoblastic leukemia\, published in 2002 \(Yeoh et al.Cancer Cell 2002\). The experiments were conducted in the St.Jude Children\'s Research Hospital\, Memphis\, Tenessee\, USA. The raw data was preprocessed by variance stabilizing normalization \(Huber et al.\) on probe and subsequent summarization of probe expression values into probe set expression values using median polish.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/stjudem.html
   :license: LGPL (>= 2)
   :recipe: /`bioconductor-stjudem <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-stjudem>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-stjudem/meta.yaml>`_

   


.. conda:package:: bioconductor-stjudem

   |downloads_bioconductor-stjudem| |docker_bioconductor-stjudem|

   :versions: 1.24.0-1, 1.24.0-0, 1.22.0-0
   
   :depends curl: >=7.65.2,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-stjudem

   and update with::

      conda update bioconductor-stjudem

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-stjudem:<tag>

   (see `bioconductor-stjudem/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-stjudem| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-stjudem.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-stjudem
   :alt:   (downloads)
.. |docker_bioconductor-stjudem| image:: https://quay.io/repository/biocontainers/bioconductor-stjudem/status
   :target: https://quay.io/repository/biocontainers/bioconductor-stjudem
.. _`bioconductor-stjudem/tags`: https://quay.io/repository/biocontainers/bioconductor-stjudem?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-stjudem/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-stjudem/README.html