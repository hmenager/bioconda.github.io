:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bsgenome.ggallus.ucsc.galgal5'
.. highlight: bash

bioconductor-bsgenome.ggallus.ucsc.galgal5
==========================================

.. conda:recipe:: bioconductor-bsgenome.ggallus.ucsc.galgal5
   :replaces_section_title:

   Full genome sequences for Gallus gallus \(Chicken\) as provided by UCSC \(galGal5\, Dec. 2015\) and stored in Biostrings objects.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/BSgenome.Ggallus.UCSC.galGal5.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-bsgenome.ggallus.ucsc.galgal5 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bsgenome.ggallus.ucsc.galgal5>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bsgenome.ggallus.ucsc.galgal5/meta.yaml>`_

   


.. conda:package:: bioconductor-bsgenome.ggallus.ucsc.galgal5

   |downloads_bioconductor-bsgenome.ggallus.ucsc.galgal5| |docker_bioconductor-bsgenome.ggallus.ucsc.galgal5|

   :versions: 1.4.2-3, 1.4.2-0
   
   :depends bioconductor-bsgenome: >=1.52.0,<1.53.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bsgenome.ggallus.ucsc.galgal5

   and update with::

      conda update bioconductor-bsgenome.ggallus.ucsc.galgal5

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bsgenome.ggallus.ucsc.galgal5:<tag>

   (see `bioconductor-bsgenome.ggallus.ucsc.galgal5/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bsgenome.ggallus.ucsc.galgal5| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bsgenome.ggallus.ucsc.galgal5.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bsgenome.ggallus.ucsc.galgal5
   :alt:   (downloads)
.. |docker_bioconductor-bsgenome.ggallus.ucsc.galgal5| image:: https://quay.io/repository/biocontainers/bioconductor-bsgenome.ggallus.ucsc.galgal5/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bsgenome.ggallus.ucsc.galgal5
.. _`bioconductor-bsgenome.ggallus.ucsc.galgal5/tags`: https://quay.io/repository/biocontainers/bioconductor-bsgenome.ggallus.ucsc.galgal5?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bsgenome.ggallus.ucsc.galgal5/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bsgenome.ggallus.ucsc.galgal5/README.html