:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'canu'
.. highlight: bash

canu
====

.. conda:recipe:: canu
   :replaces_section_title:

   Canu is a fork of the Celera Assembler designed for high\-noise single\-molecule sequencing.

   :homepage: http://canu.readthedocs.org/
   :developer docs: https://github.com/marbl/canu
   :license: GPL / GPLv2 and others
   :recipe: /`canu <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/canu>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/canu/meta.yaml>`_

   


.. conda:package:: canu

   |downloads_canu| |docker_canu|

   :versions: 1.8-2, 1.8-1, 1.8-0, 1.7.1-0, 1.7-0, 1.6-1, 1.5-1, 1.5-0, 1.4-2, 1.4-1, 1.4-0, 1.3-0, 1.1-0
   
   :depends gnuplot: >=5.0.5
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends openjdk: 
   :depends perl: 
   :depends perl-filesys-df: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install canu

   and update with::

      conda update canu

   or use the docker container::

      docker pull quay.io/biocontainers/canu:<tag>

   (see `canu/tags`_ for valid values for ``<tag>``)


.. |downloads_canu| image:: https://img.shields.io/conda/dn/bioconda/canu.svg?style=flat
   :target: https://anaconda.org/bioconda/canu
   :alt:   (downloads)
.. |docker_canu| image:: https://quay.io/repository/biocontainers/canu/status
   :target: https://quay.io/repository/biocontainers/canu
.. _`canu/tags`: https://quay.io/repository/biocontainers/canu?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/canu/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/canu/README.html