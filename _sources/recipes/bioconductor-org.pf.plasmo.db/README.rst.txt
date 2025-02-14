:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-org.pf.plasmo.db'
.. highlight: bash

bioconductor-org.pf.plasmo.db
=============================

.. conda:recipe:: bioconductor-org.pf.plasmo.db
   :replaces_section_title:

   Genome wide annotation for Malaria\, primarily based on mapping using Entrez Gene identifiers.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/org.Pf.plasmo.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-org.pf.plasmo.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-org.pf.plasmo.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-org.pf.plasmo.db/meta.yaml>`_

   


.. conda:package:: bioconductor-org.pf.plasmo.db

   |downloads_bioconductor-org.pf.plasmo.db| |docker_bioconductor-org.pf.plasmo.db|

   :versions: 3.8.2-1, 3.7.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-org.pf.plasmo.db

   and update with::

      conda update bioconductor-org.pf.plasmo.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-org.pf.plasmo.db:<tag>

   (see `bioconductor-org.pf.plasmo.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-org.pf.plasmo.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-org.pf.plasmo.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-org.pf.plasmo.db
   :alt:   (downloads)
.. |docker_bioconductor-org.pf.plasmo.db| image:: https://quay.io/repository/biocontainers/bioconductor-org.pf.plasmo.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-org.pf.plasmo.db
.. _`bioconductor-org.pf.plasmo.db/tags`: https://quay.io/repository/biocontainers/bioconductor-org.pf.plasmo.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-org.pf.plasmo.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-org.pf.plasmo.db/README.html