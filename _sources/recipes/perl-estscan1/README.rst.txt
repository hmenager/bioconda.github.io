:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'perl-estscan1'
.. highlight: bash

perl-estscan1
=============

.. conda:recipe:: perl-estscan1/1.3
   :replaces_section_title:

   Detects coding regions in DNA sequences even if they are of low quality. ESTScan.pm contains the Perl part of the code that reads in the matrices file. The C code that does the actual computation is located in estscan.c.

   :homepage: http://estscan.sourceforge.net
   :license: open source
   :recipe: /`perl-estscan1 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-estscan1>`_/`1.3 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-estscan1/1.3>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-estscan1/1.3/meta.yaml>`_

   


.. conda:package:: perl-estscan1

   |downloads_perl-estscan1| |docker_perl-estscan1|

   :versions: 1.3-1, 1.3-0
   
   :depends perl: >=5.26.2,<5.27.0a0
   :depends perl-btlib: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install perl-estscan1

   and update with::

      conda update perl-estscan1

   or use the docker container::

      docker pull quay.io/biocontainers/perl-estscan1:<tag>

   (see `perl-estscan1/tags`_ for valid values for ``<tag>``)


.. |downloads_perl-estscan1| image:: https://img.shields.io/conda/dn/bioconda/perl-estscan1.svg?style=flat
   :target: https://anaconda.org/bioconda/perl-estscan1
   :alt:   (downloads)
.. |docker_perl-estscan1| image:: https://quay.io/repository/biocontainers/perl-estscan1/status
   :target: https://quay.io/repository/biocontainers/perl-estscan1
.. _`perl-estscan1/tags`: https://quay.io/repository/biocontainers/perl-estscan1?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/perl-estscan1/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/perl-estscan1/README.html