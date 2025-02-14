:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'entrez-direct'
.. highlight: bash

entrez-direct
=============

.. conda:recipe:: entrez-direct
   :replaces_section_title:

   Entrez Direct \(EDirect\) is an advanced method for accessing the NCBI\'s set of interconnected databases \(publication\, sequence\, structure\, gene\, variation\, expression\, etc.\) from a UNIX terminal window. Functions take search terms from command\-line arguments. Individual operations are combined to build multi\-step queries. Record retrieval and formatting normally complete the process.

   :homepage: ftp://ftp.ncbi.nlm.nih.gov/entrez/entrezdirect/versions/11.0.20190322/README
   :license: PUBLIC DOMAIN
   :recipe: /`entrez-direct <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/entrez-direct>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/entrez-direct/meta.yaml>`_

   


.. conda:package:: entrez-direct

   |downloads_entrez-direct| |docker_entrez-direct|

   :versions: 11.0-0, 10.2-0, 10.0-0, 7.70-2, 7.70-1, 7.70-0, 7.00-1, 7.00-0, 5.80-0, 4.00-1, 4.00-0
   
   :depends perl: >=5.26.2,<5.26.3.0a0
   :depends perl-html-parser: 
   :depends perl-html-tagset: 
   :depends perl-html-tree: 
   :depends perl-http-cookies: 
   :depends perl-http-date: 
   :depends perl-http-message: 
   :depends perl-http-negotiate: 
   :depends perl-io-socket-ssl: 
   :depends perl-lwp-mediatypes: 
   :depends perl-lwp-protocol-https: 
   :depends perl-mozilla-ca: 
   :depends perl-net-http: 
   :depends perl-uri: 
   :depends perl-www-robotrules: 
   :depends perl-xml-simple: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install entrez-direct

   and update with::

      conda update entrez-direct

   or use the docker container::

      docker pull quay.io/biocontainers/entrez-direct:<tag>

   (see `entrez-direct/tags`_ for valid values for ``<tag>``)


.. |downloads_entrez-direct| image:: https://img.shields.io/conda/dn/bioconda/entrez-direct.svg?style=flat
   :target: https://anaconda.org/bioconda/entrez-direct
   :alt:   (downloads)
.. |docker_entrez-direct| image:: https://quay.io/repository/biocontainers/entrez-direct/status
   :target: https://quay.io/repository/biocontainers/entrez-direct
.. _`entrez-direct/tags`: https://quay.io/repository/biocontainers/entrez-direct?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/entrez-direct/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/entrez-direct/README.html