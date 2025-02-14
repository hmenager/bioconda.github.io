:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'perl-tie-refhash'
.. highlight: bash

perl-tie-refhash
================

.. conda:recipe:: perl-tie-refhash/1.39
   :replaces_section_title:

   use references as hash keys

   :homepage: http://metacpan.org/pod/Tie::RefHash
   :license: perl_5
   :recipe: /`perl-tie-refhash <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-tie-refhash>`_/`1.39 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-tie-refhash/1.39>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-tie-refhash/1.39/meta.yaml>`_

   


.. conda:package:: perl-tie-refhash

   |downloads_perl-tie-refhash| |docker_perl-tie-refhash|

   :versions: 1.39-2, 1.39-1, 1.39-0
   
   :depends perl: >=5.26.2,<5.26.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install perl-tie-refhash

   and update with::

      conda update perl-tie-refhash

   or use the docker container::

      docker pull quay.io/biocontainers/perl-tie-refhash:<tag>

   (see `perl-tie-refhash/tags`_ for valid values for ``<tag>``)


.. |downloads_perl-tie-refhash| image:: https://img.shields.io/conda/dn/bioconda/perl-tie-refhash.svg?style=flat
   :target: https://anaconda.org/bioconda/perl-tie-refhash
   :alt:   (downloads)
.. |docker_perl-tie-refhash| image:: https://quay.io/repository/biocontainers/perl-tie-refhash/status
   :target: https://quay.io/repository/biocontainers/perl-tie-refhash
.. _`perl-tie-refhash/tags`: https://quay.io/repository/biocontainers/perl-tie-refhash?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/perl-tie-refhash/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/perl-tie-refhash/README.html