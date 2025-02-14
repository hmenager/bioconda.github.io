:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-xenopuslaeviscdf'
.. highlight: bash

bioconductor-xenopuslaeviscdf
=============================

.. conda:recipe:: bioconductor-xenopuslaeviscdf
   :replaces_section_title:

   A package containing an environment representing the Xenopus\_laevis.cdf file.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/xenopuslaeviscdf.html
   :license: LGPL
   :recipe: /`bioconductor-xenopuslaeviscdf <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-xenopuslaeviscdf>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-xenopuslaeviscdf/meta.yaml>`_

   


.. conda:package:: bioconductor-xenopuslaeviscdf

   |downloads_bioconductor-xenopuslaeviscdf| |docker_bioconductor-xenopuslaeviscdf|

   :versions: 2.18.0-2, 2.18.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-xenopuslaeviscdf

   and update with::

      conda update bioconductor-xenopuslaeviscdf

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-xenopuslaeviscdf:<tag>

   (see `bioconductor-xenopuslaeviscdf/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-xenopuslaeviscdf| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-xenopuslaeviscdf.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-xenopuslaeviscdf
   :alt:   (downloads)
.. |docker_bioconductor-xenopuslaeviscdf| image:: https://quay.io/repository/biocontainers/bioconductor-xenopuslaeviscdf/status
   :target: https://quay.io/repository/biocontainers/bioconductor-xenopuslaeviscdf
.. _`bioconductor-xenopuslaeviscdf/tags`: https://quay.io/repository/biocontainers/bioconductor-xenopuslaeviscdf?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-xenopuslaeviscdf/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-xenopuslaeviscdf/README.html