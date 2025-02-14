:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'perl-xml-namespacesupport'
.. highlight: bash

perl-xml-namespacesupport
=========================

.. conda:recipe:: perl-xml-namespacesupport
   :replaces_section_title:

   a simple generic namespace support class

   :homepage: https://github.com/perigrin/xml-namespacesupport
   :license: perl_5
   :recipe: /`perl-xml-namespacesupport <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-xml-namespacesupport>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-xml-namespacesupport/meta.yaml>`_

   


.. conda:package:: perl-xml-namespacesupport

   |downloads_perl-xml-namespacesupport| |docker_perl-xml-namespacesupport|

   :versions: 1.12-0, 1.11-1, 1.11-0
   
   :depends perl: >=5.26.2,<5.27.0a0
   :depends perl-constant: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install perl-xml-namespacesupport

   and update with::

      conda update perl-xml-namespacesupport

   or use the docker container::

      docker pull quay.io/biocontainers/perl-xml-namespacesupport:<tag>

   (see `perl-xml-namespacesupport/tags`_ for valid values for ``<tag>``)


.. |downloads_perl-xml-namespacesupport| image:: https://img.shields.io/conda/dn/bioconda/perl-xml-namespacesupport.svg?style=flat
   :target: https://anaconda.org/bioconda/perl-xml-namespacesupport
   :alt:   (downloads)
.. |docker_perl-xml-namespacesupport| image:: https://quay.io/repository/biocontainers/perl-xml-namespacesupport/status
   :target: https://quay.io/repository/biocontainers/perl-xml-namespacesupport
.. _`perl-xml-namespacesupport/tags`: https://quay.io/repository/biocontainers/perl-xml-namespacesupport?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/perl-xml-namespacesupport/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/perl-xml-namespacesupport/README.html