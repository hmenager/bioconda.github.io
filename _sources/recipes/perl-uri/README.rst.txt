:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'perl-uri'
.. highlight: bash

perl-uri
========

.. conda:recipe:: perl-uri
   :replaces_section_title:

   Uniform Resource Identifiers \(absolute and relative\)

   :homepage: https://github.com/libwww-perl/URI
   :license: perl_5
   :recipe: /`perl-uri <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-uri>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-uri/meta.yaml>`_

   


.. conda:package:: perl-uri

   |downloads_perl-uri| |docker_perl-uri|

   :versions: 1.76-0, 1.74-0, 1.71-3, 1.71-2, 1.71-1, 1.71-0, 1.69-7, 1.69-6, 1.69-5, 1.69-4, 1.69-3, 1.69-2, 1.69-1, 1.69-0
   
   :depends perl: >=5.26.2,<5.26.3.0a0
   :depends perl-business-isbn: 
   :depends perl-carp: 
   :depends perl-constant: 
   :depends perl-data-dumper: 
   :depends perl-encode: 
   :depends perl-exporter: 
   :depends perl-mime-base64: 
   :depends perl-parent: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install perl-uri

   and update with::

      conda update perl-uri

   or use the docker container::

      docker pull quay.io/biocontainers/perl-uri:<tag>

   (see `perl-uri/tags`_ for valid values for ``<tag>``)


.. |downloads_perl-uri| image:: https://img.shields.io/conda/dn/bioconda/perl-uri.svg?style=flat
   :target: https://anaconda.org/bioconda/perl-uri
   :alt:   (downloads)
.. |docker_perl-uri| image:: https://quay.io/repository/biocontainers/perl-uri/status
   :target: https://quay.io/repository/biocontainers/perl-uri
.. _`perl-uri/tags`: https://quay.io/repository/biocontainers/perl-uri?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/perl-uri/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/perl-uri/README.html