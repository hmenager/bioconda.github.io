:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'dnp-diprofile'
.. highlight: bash

dnp-diprofile
=============

.. conda:recipe:: dnp-diprofile
   :replaces_section_title:

   Dinucleotide frequency of occurrence in a batch of fasta sequences

   :homepage: https://github.com/erinijapranckeviciene/dnpatterntools
   :license: MIT
   :recipe: /`dnp-diprofile <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/dnp-diprofile>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/dnp-diprofile/meta.yaml>`_

   


.. conda:package:: dnp-diprofile

   |downloads_dnp-diprofile| |docker_dnp-diprofile|

   :versions: 1.0-1, 1.0-0
   
   :depends bzip2: >=1.0.6,<2.0a0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install dnp-diprofile

   and update with::

      conda update dnp-diprofile

   or use the docker container::

      docker pull quay.io/biocontainers/dnp-diprofile:<tag>

   (see `dnp-diprofile/tags`_ for valid values for ``<tag>``)


.. |downloads_dnp-diprofile| image:: https://img.shields.io/conda/dn/bioconda/dnp-diprofile.svg?style=flat
   :target: https://anaconda.org/bioconda/dnp-diprofile
   :alt:   (downloads)
.. |docker_dnp-diprofile| image:: https://quay.io/repository/biocontainers/dnp-diprofile/status
   :target: https://quay.io/repository/biocontainers/dnp-diprofile
.. _`dnp-diprofile/tags`: https://quay.io/repository/biocontainers/dnp-diprofile?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/dnp-diprofile/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/dnp-diprofile/README.html