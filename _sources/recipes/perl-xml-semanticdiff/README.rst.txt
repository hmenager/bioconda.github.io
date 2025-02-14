:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'perl-xml-semanticdiff'
.. highlight: bash

perl-xml-semanticdiff
=====================

.. conda:recipe:: perl-xml-semanticdiff
   :replaces_section_title:

   Perl extension for comparing XML documents.

   :homepage: http://metacpan.org/pod/XML-SemanticDiff
   :license: perl_5
   :recipe: /`perl-xml-semanticdiff <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-xml-semanticdiff>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-xml-semanticdiff/meta.yaml>`_

   


.. conda:package:: perl-xml-semanticdiff

   |downloads_perl-xml-semanticdiff| |docker_perl-xml-semanticdiff|

   :versions: 1.0007-0, 1.0004-2, 1.0004-1, 1.0004-0
   
   :depends perl: >=5.26.2,<5.26.3.0a0
   :depends perl-digest-md5: 
   :depends perl-encode: 
   :depends perl-xml-parser: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install perl-xml-semanticdiff

   and update with::

      conda update perl-xml-semanticdiff

   or use the docker container::

      docker pull quay.io/biocontainers/perl-xml-semanticdiff:<tag>

   (see `perl-xml-semanticdiff/tags`_ for valid values for ``<tag>``)


.. |downloads_perl-xml-semanticdiff| image:: https://img.shields.io/conda/dn/bioconda/perl-xml-semanticdiff.svg?style=flat
   :target: https://anaconda.org/bioconda/perl-xml-semanticdiff
   :alt:   (downloads)
.. |docker_perl-xml-semanticdiff| image:: https://quay.io/repository/biocontainers/perl-xml-semanticdiff/status
   :target: https://quay.io/repository/biocontainers/perl-xml-semanticdiff
.. _`perl-xml-semanticdiff/tags`: https://quay.io/repository/biocontainers/perl-xml-semanticdiff?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/perl-xml-semanticdiff/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/perl-xml-semanticdiff/README.html