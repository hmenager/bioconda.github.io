:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-xlaevis.db'
.. highlight: bash

bioconductor-xlaevis.db
=======================

.. conda:recipe:: bioconductor-xlaevis.db
   :replaces_section_title:

   Affymetrix Xenopus laevis annotation data \(chip xlaevis\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/xlaevis.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-xlaevis.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-xlaevis.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-xlaevis.db/meta.yaml>`_

   


.. conda:package:: bioconductor-xlaevis.db

   |downloads_bioconductor-xlaevis.db| |docker_bioconductor-xlaevis.db|

   :versions: 3.2.3-2, 3.2.3-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-org.xl.eg.db: >=3.8.0,<3.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-xlaevis.db

   and update with::

      conda update bioconductor-xlaevis.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-xlaevis.db:<tag>

   (see `bioconductor-xlaevis.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-xlaevis.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-xlaevis.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-xlaevis.db
   :alt:   (downloads)
.. |docker_bioconductor-xlaevis.db| image:: https://quay.io/repository/biocontainers/bioconductor-xlaevis.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-xlaevis.db
.. _`bioconductor-xlaevis.db/tags`: https://quay.io/repository/biocontainers/bioconductor-xlaevis.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-xlaevis.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-xlaevis.db/README.html