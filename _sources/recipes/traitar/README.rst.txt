:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'traitar'
.. highlight: bash

traitar
=======

.. conda:recipe:: traitar
   :replaces_section_title:

   traitar \- The microbial trait analyzer

   :homepage: http://github.com/aweimann/traitar
   :license: GPL3 / GNU General Public, version 3 (GPL-3.0)
   :recipe: /`traitar <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/traitar>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/traitar/meta.yaml>`_

   Traitar is a software for characterizing microbial samples from nucleotide or protein sequences


.. conda:package:: traitar

   |downloads_traitar| |docker_traitar|

   :versions: 1.1.2-0
   
   :depends matplotlib: >=1.3.1
   :depends numpy: >=1.6
   :depends pandas: >=0.13.1
   :depends python: 2.7.*
   :depends scipy: >=0.13.3
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install traitar

   and update with::

      conda update traitar

   or use the docker container::

      docker pull quay.io/biocontainers/traitar:<tag>

   (see `traitar/tags`_ for valid values for ``<tag>``)


.. |downloads_traitar| image:: https://img.shields.io/conda/dn/bioconda/traitar.svg?style=flat
   :target: https://anaconda.org/bioconda/traitar
   :alt:   (downloads)
.. |docker_traitar| image:: https://quay.io/repository/biocontainers/traitar/status
   :target: https://quay.io/repository/biocontainers/traitar
.. _`traitar/tags`: https://quay.io/repository/biocontainers/traitar?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/traitar/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/traitar/README.html