:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'perl-xml-dom-xpath'
.. highlight: bash

perl-xml-dom-xpath
==================

.. conda:recipe:: perl-xml-dom-xpath
   :replaces_section_title:

   Perl extension to add XPath support to XML\:\:DOM\, using XML\:\:XPath engine

   :homepage: http://metacpan.org/pod/XML-DOM-XPath
   :license: unknown
   :recipe: /`perl-xml-dom-xpath <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-xml-dom-xpath>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-xml-dom-xpath/meta.yaml>`_

   


.. conda:package:: perl-xml-dom-xpath

   |downloads_perl-xml-dom-xpath| |docker_perl-xml-dom-xpath|

   :versions: 0.14-1, 0.14-0
   
   :depends perl: >=5.26.2,<5.26.3.0a0
   :depends perl-xml-dom: 
   :depends perl-xml-xpathengine: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install perl-xml-dom-xpath

   and update with::

      conda update perl-xml-dom-xpath

   or use the docker container::

      docker pull quay.io/biocontainers/perl-xml-dom-xpath:<tag>

   (see `perl-xml-dom-xpath/tags`_ for valid values for ``<tag>``)


.. |downloads_perl-xml-dom-xpath| image:: https://img.shields.io/conda/dn/bioconda/perl-xml-dom-xpath.svg?style=flat
   :target: https://anaconda.org/bioconda/perl-xml-dom-xpath
   :alt:   (downloads)
.. |docker_perl-xml-dom-xpath| image:: https://quay.io/repository/biocontainers/perl-xml-dom-xpath/status
   :target: https://quay.io/repository/biocontainers/perl-xml-dom-xpath
.. _`perl-xml-dom-xpath/tags`: https://quay.io/repository/biocontainers/perl-xml-dom-xpath?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/perl-xml-dom-xpath/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/perl-xml-dom-xpath/README.html