:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-clariomsmousehttranscriptcluster.db'
.. highlight: bash

bioconductor-clariomsmousehttranscriptcluster.db
================================================

.. conda:recipe:: bioconductor-clariomsmousehttranscriptcluster.db
   :replaces_section_title:

   Affymetrix clariomsmouseht annotation data \(chip clariomsmousehttranscriptcluster\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/clariomsmousehttranscriptcluster.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-clariomsmousehttranscriptcluster.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clariomsmousehttranscriptcluster.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clariomsmousehttranscriptcluster.db/meta.yaml>`_

   


.. conda:package:: bioconductor-clariomsmousehttranscriptcluster.db

   |downloads_bioconductor-clariomsmousehttranscriptcluster.db| |docker_bioconductor-clariomsmousehttranscriptcluster.db|

   :versions: 8.7.0-2, 8.7.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-org.mm.eg.db: >=3.8.0,<3.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-clariomsmousehttranscriptcluster.db

   and update with::

      conda update bioconductor-clariomsmousehttranscriptcluster.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-clariomsmousehttranscriptcluster.db:<tag>

   (see `bioconductor-clariomsmousehttranscriptcluster.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-clariomsmousehttranscriptcluster.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-clariomsmousehttranscriptcluster.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-clariomsmousehttranscriptcluster.db
   :alt:   (downloads)
.. |docker_bioconductor-clariomsmousehttranscriptcluster.db| image:: https://quay.io/repository/biocontainers/bioconductor-clariomsmousehttranscriptcluster.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-clariomsmousehttranscriptcluster.db
.. _`bioconductor-clariomsmousehttranscriptcluster.db/tags`: https://quay.io/repository/biocontainers/bioconductor-clariomsmousehttranscriptcluster.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-clariomsmousehttranscriptcluster.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-clariomsmousehttranscriptcluster.db/README.html