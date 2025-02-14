:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bcbio-variation'
.. highlight: bash

bcbio-variation
===============

.. conda:recipe:: bcbio-variation
   :replaces_section_title:

   Toolkit to analyze genomic variation data\, built on the GATK with Clojure

   :homepage: https://github.com/chapmanb/bcbio.variation
   :license: MIT
   :recipe: /`bcbio-variation <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bcbio-variation>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bcbio-variation/meta.yaml>`_

   


.. conda:package:: bcbio-variation

   |downloads_bcbio-variation| |docker_bcbio-variation|

   :versions: 0.2.6-3, 0.2.6-2, 0.2.6-1, 0.2.6-0
   
   :depends openjdk: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bcbio-variation

   and update with::

      conda update bcbio-variation

   or use the docker container::

      docker pull quay.io/biocontainers/bcbio-variation:<tag>

   (see `bcbio-variation/tags`_ for valid values for ``<tag>``)


.. |downloads_bcbio-variation| image:: https://img.shields.io/conda/dn/bioconda/bcbio-variation.svg?style=flat
   :target: https://anaconda.org/bioconda/bcbio-variation
   :alt:   (downloads)
.. |docker_bcbio-variation| image:: https://quay.io/repository/biocontainers/bcbio-variation/status
   :target: https://quay.io/repository/biocontainers/bcbio-variation
.. _`bcbio-variation/tags`: https://quay.io/repository/biocontainers/bcbio-variation?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bcbio-variation/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bcbio-variation/README.html