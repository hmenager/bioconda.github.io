:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chemmineob'
.. highlight: bash

bioconductor-chemmineob
=======================

.. conda:recipe:: bioconductor-chemmineob
   :replaces_section_title:

   ChemmineOB provides an R interface to a subset of cheminformatics functionalities implemented by the OpelBabel C\+\+ project. OpenBabel is an open source cheminformatics toolbox that includes utilities for structure format interconversions\, descriptor calculations\, compound similarity searching and more. ChemineOB aims to make a subset of these utilities available from within R. For non\-developers\, ChemineOB is primarily intended to be used from ChemmineR as an add\-on package rather than used directly.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/ChemmineOB.html
   :license: file LICENSE
   :recipe: /`bioconductor-chemmineob <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chemmineob>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chemmineob/meta.yaml>`_

   


.. conda:package:: bioconductor-chemmineob

   |downloads_bioconductor-chemmineob| |docker_bioconductor-chemmineob|

   :versions: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chemmineob

   and update with::

      conda update bioconductor-chemmineob

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chemmineob:<tag>

   (see `bioconductor-chemmineob/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chemmineob| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chemmineob.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-chemmineob
   :alt:   (downloads)
.. |docker_bioconductor-chemmineob| image:: https://quay.io/repository/biocontainers/bioconductor-chemmineob/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chemmineob
.. _`bioconductor-chemmineob/tags`: https://quay.io/repository/biocontainers/bioconductor-chemmineob?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chemmineob/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chemmineob/README.html