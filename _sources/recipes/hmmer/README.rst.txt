:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'hmmer'
.. highlight: bash

hmmer
=====

.. conda:recipe:: hmmer
   :replaces_section_title:

   Biosequence analysis using profile hidden Markov models

   :homepage: http://hmmer.org/
   :license: BSD
   :recipe: /`hmmer <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/hmmer>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/hmmer/meta.yaml>`_

   


.. conda:package:: hmmer

   |downloads_hmmer| |docker_hmmer|

   :versions: 3.2.1-1, 3.2.1-0, 3.2-3, 3.2-2, 3.2-0, 3.1b2-3, 3.1b2-2, 3.1b2-1, 3.1b2-0, 2.3.2-3, 2.3.2-2, 2.3.2-1, 2.3.2-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install hmmer

   and update with::

      conda update hmmer

   or use the docker container::

      docker pull quay.io/biocontainers/hmmer:<tag>

   (see `hmmer/tags`_ for valid values for ``<tag>``)


.. |downloads_hmmer| image:: https://img.shields.io/conda/dn/bioconda/hmmer.svg?style=flat
   :target: https://anaconda.org/bioconda/hmmer
   :alt:   (downloads)
.. |docker_hmmer| image:: https://quay.io/repository/biocontainers/hmmer/status
   :target: https://quay.io/repository/biocontainers/hmmer
.. _`hmmer/tags`: https://quay.io/repository/biocontainers/hmmer?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/hmmer/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/hmmer/README.html