:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'perl-test-simple'
.. highlight: bash

perl-test-simple
================

.. conda:recipe:: perl-test-simple
   :replaces_section_title:

   Basic utilities for writing tests.

   :homepage: http://metacpan.org/pod/Test-Simple
   :license: perl_5
   :recipe: /`perl-test-simple <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-test-simple>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-test-simple/meta.yaml>`_

   


.. conda:package:: perl-test-simple

   |downloads_perl-test-simple| |docker_perl-test-simple|

   :versions: 1.302164-0, 1.302156-0, 1.302141-0, 1.302140-0, 1.302075-1, 1.302075-0, 1.302052-1, 1.302052-0
   
   :depends perl: >=5.26.2,<5.26.3.0a0
   :depends perl-file-temp: 
   :depends perl-storable: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install perl-test-simple

   and update with::

      conda update perl-test-simple

   or use the docker container::

      docker pull quay.io/biocontainers/perl-test-simple:<tag>

   (see `perl-test-simple/tags`_ for valid values for ``<tag>``)


.. |downloads_perl-test-simple| image:: https://img.shields.io/conda/dn/bioconda/perl-test-simple.svg?style=flat
   :target: https://anaconda.org/bioconda/perl-test-simple
   :alt:   (downloads)
.. |docker_perl-test-simple| image:: https://quay.io/repository/biocontainers/perl-test-simple/status
   :target: https://quay.io/repository/biocontainers/perl-test-simple
.. _`perl-test-simple/tags`: https://quay.io/repository/biocontainers/perl-test-simple?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/perl-test-simple/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/perl-test-simple/README.html