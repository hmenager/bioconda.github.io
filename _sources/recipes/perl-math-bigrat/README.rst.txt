:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'perl-math-bigrat'
.. highlight: bash

perl-math-bigrat
================

.. conda:recipe:: perl-math-bigrat
   :replaces_section_title:

   Arbitrary big rational numbers

   :homepage: http://metacpan.org/pod/Math::BigRat
   :license: perl_5
   :recipe: /`perl-math-bigrat <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-math-bigrat>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-math-bigrat/meta.yaml>`_

   


.. conda:package:: perl-math-bigrat

   |downloads_perl-math-bigrat| |docker_perl-math-bigrat|

   :versions: 0.2614-0
   
   :depends perl: >=5.26.2,<5.26.3.0a0
   :depends perl-math-bigint: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install perl-math-bigrat

   and update with::

      conda update perl-math-bigrat

   or use the docker container::

      docker pull quay.io/biocontainers/perl-math-bigrat:<tag>

   (see `perl-math-bigrat/tags`_ for valid values for ``<tag>``)


.. |downloads_perl-math-bigrat| image:: https://img.shields.io/conda/dn/bioconda/perl-math-bigrat.svg?style=flat
   :target: https://anaconda.org/bioconda/perl-math-bigrat
   :alt:   (downloads)
.. |docker_perl-math-bigrat| image:: https://quay.io/repository/biocontainers/perl-math-bigrat/status
   :target: https://quay.io/repository/biocontainers/perl-math-bigrat
.. _`perl-math-bigrat/tags`: https://quay.io/repository/biocontainers/perl-math-bigrat?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/perl-math-bigrat/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/perl-math-bigrat/README.html