:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'perl-io-prompt'
.. highlight: bash

perl-io-prompt
==============

.. conda:recipe:: perl-io-prompt
   :replaces_section_title:

   Interactively prompt for user input

   :homepage: http://search.cpan.org/dist/IO-Prompt/lib/IO/Prompt.pm
   :license: perl_5
   :recipe: /`perl-io-prompt <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-io-prompt>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-io-prompt/meta.yaml>`_

   


.. conda:package:: perl-io-prompt

   |downloads_perl-io-prompt| |docker_perl-io-prompt|

   :versions: 0.997004-2, 0.997004-1, 0.997004-0
   
   :depends perl: >=5.26.2,<5.26.3.0a0
   :depends perl-termreadkey: 
   :depends perl-want: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install perl-io-prompt

   and update with::

      conda update perl-io-prompt

   or use the docker container::

      docker pull quay.io/biocontainers/perl-io-prompt:<tag>

   (see `perl-io-prompt/tags`_ for valid values for ``<tag>``)


.. |downloads_perl-io-prompt| image:: https://img.shields.io/conda/dn/bioconda/perl-io-prompt.svg?style=flat
   :target: https://anaconda.org/bioconda/perl-io-prompt
   :alt:   (downloads)
.. |docker_perl-io-prompt| image:: https://quay.io/repository/biocontainers/perl-io-prompt/status
   :target: https://quay.io/repository/biocontainers/perl-io-prompt
.. _`perl-io-prompt/tags`: https://quay.io/repository/biocontainers/perl-io-prompt?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/perl-io-prompt/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/perl-io-prompt/README.html