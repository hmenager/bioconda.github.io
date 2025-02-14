:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'snap-aligner'
.. highlight: bash

snap-aligner
============

.. conda:recipe:: snap-aligner
   :replaces_section_title:

   Scalable Nucleotide Alignment Program \-\- a fast and accurate read aligner for high\-throughput sequencing data

   :homepage: http://snap.cs.berkeley.edu/
   :license: Apache v2
   :recipe: /`snap-aligner <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/snap-aligner>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/snap-aligner/meta.yaml>`_

   


.. conda:package:: snap-aligner

   |downloads_snap-aligner| |docker_snap-aligner|

   :versions: 1.0beta.23-0, 1.0beta.18-0, 1.0dev.97-1, 1.0dev.97-0
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install snap-aligner

   and update with::

      conda update snap-aligner

   or use the docker container::

      docker pull quay.io/biocontainers/snap-aligner:<tag>

   (see `snap-aligner/tags`_ for valid values for ``<tag>``)


.. |downloads_snap-aligner| image:: https://img.shields.io/conda/dn/bioconda/snap-aligner.svg?style=flat
   :target: https://anaconda.org/bioconda/snap-aligner
   :alt:   (downloads)
.. |docker_snap-aligner| image:: https://quay.io/repository/biocontainers/snap-aligner/status
   :target: https://quay.io/repository/biocontainers/snap-aligner
.. _`snap-aligner/tags`: https://quay.io/repository/biocontainers/snap-aligner?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/snap-aligner/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/snap-aligner/README.html