:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'perl-params-validationcompiler'
.. highlight: bash

perl-params-validationcompiler
==============================

.. conda:recipe:: perl-params-validationcompiler/0.23
   :replaces_section_title:

   Build an optimized subroutine parameter validator once\, use it forever

   :homepage: http://metacpan.org/release/Params-ValidationCompiler
   :license: artistic_2
   :recipe: /`perl-params-validationcompiler <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-params-validationcompiler>`_/`0.23 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-params-validationcompiler/0.23>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-params-validationcompiler/0.23/meta.yaml>`_

   


.. conda:package:: perl-params-validationcompiler

   |downloads_perl-params-validationcompiler| |docker_perl-params-validationcompiler|

   :versions: 0.23-2, 0.23-1, 0.23-0
   
   :depends libstdcxx-ng: >=4.9
   :depends perl: >=5.26.2,<5.26.3.0a0
   :depends perl-app-cpanminus: 
   :depends perl-b: 
   :depends perl-devel-stacktrace: 
   :depends perl-eval-closure: 
   :depends perl-exception-class: 
   :depends perl-variable-magic: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install perl-params-validationcompiler

   and update with::

      conda update perl-params-validationcompiler

   or use the docker container::

      docker pull quay.io/biocontainers/perl-params-validationcompiler:<tag>

   (see `perl-params-validationcompiler/tags`_ for valid values for ``<tag>``)


.. |downloads_perl-params-validationcompiler| image:: https://img.shields.io/conda/dn/bioconda/perl-params-validationcompiler.svg?style=flat
   :target: https://anaconda.org/bioconda/perl-params-validationcompiler
   :alt:   (downloads)
.. |docker_perl-params-validationcompiler| image:: https://quay.io/repository/biocontainers/perl-params-validationcompiler/status
   :target: https://quay.io/repository/biocontainers/perl-params-validationcompiler
.. _`perl-params-validationcompiler/tags`: https://quay.io/repository/biocontainers/perl-params-validationcompiler?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/perl-params-validationcompiler/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/perl-params-validationcompiler/README.html