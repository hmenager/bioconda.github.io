:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-yeastgsdata'
.. highlight: bash

bioconductor-yeastgsdata
========================

.. conda:recipe:: bioconductor-yeastgsdata
   :replaces_section_title:

   A collection of so\-called gold \(and other\) standard data sets

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/yeastGSData.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-yeastgsdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-yeastgsdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-yeastgsdata/meta.yaml>`_

   


.. conda:package:: bioconductor-yeastgsdata

   |downloads_bioconductor-yeastgsdata| |docker_bioconductor-yeastgsdata|

   :versions: 0.22.0-1, 0.22.0-0, 0.20.0-0
   
   :depends curl: >=7.64.1,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-yeastgsdata

   and update with::

      conda update bioconductor-yeastgsdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-yeastgsdata:<tag>

   (see `bioconductor-yeastgsdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-yeastgsdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-yeastgsdata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-yeastgsdata
   :alt:   (downloads)
.. |docker_bioconductor-yeastgsdata| image:: https://quay.io/repository/biocontainers/bioconductor-yeastgsdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-yeastgsdata
.. _`bioconductor-yeastgsdata/tags`: https://quay.io/repository/biocontainers/bioconductor-yeastgsdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-yeastgsdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-yeastgsdata/README.html