:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'perl-params-util'
.. highlight: bash

perl-params-util
================

.. conda:recipe:: perl-params-util
   :replaces_section_title:

   Simple\, compact and correct param\-checking functions

   :homepage: http://metacpan.org/pod/Params::Util
   :license: perl_5
   :recipe: /`perl-params-util <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-params-util>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-params-util/meta.yaml>`_

   


.. conda:package:: perl-params-util

   |downloads_perl-params-util| |docker_perl-params-util|

   :versions: 1.07-4, 1.07-3, 1.07-2, 1.07-1, 1.07-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends perl: >=5.26.2,<5.26.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install perl-params-util

   and update with::

      conda update perl-params-util

   or use the docker container::

      docker pull quay.io/biocontainers/perl-params-util:<tag>

   (see `perl-params-util/tags`_ for valid values for ``<tag>``)


.. |downloads_perl-params-util| image:: https://img.shields.io/conda/dn/bioconda/perl-params-util.svg?style=flat
   :target: https://anaconda.org/bioconda/perl-params-util
   :alt:   (downloads)
.. |docker_perl-params-util| image:: https://quay.io/repository/biocontainers/perl-params-util/status
   :target: https://quay.io/repository/biocontainers/perl-params-util
.. _`perl-params-util/tags`: https://quay.io/repository/biocontainers/perl-params-util?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/perl-params-util/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/perl-params-util/README.html