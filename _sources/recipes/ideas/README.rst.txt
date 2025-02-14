:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ideas'
.. highlight: bash

ideas
=====

.. conda:recipe:: ideas/1.20
   :replaces_section_title:

   A method for jointly and quantitatively characterizing multivariate epigenetic landscapes in many cell types\, tissues or conditions.

   :homepage: https://github.com/yuzhang123/IDEAS
   :license: MIT
   :recipe: /`ideas <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ideas>`_/`1.20 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ideas/1.20>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ideas/1.20/meta.yaml>`_

   


.. conda:package:: ideas

   |downloads_ideas| |docker_ideas|

   :versions: 1.20-1, 1.20-0
   
   :depends libstdcxx-ng: >=4.9
   :depends mkl: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ideas

   and update with::

      conda update ideas

   or use the docker container::

      docker pull quay.io/biocontainers/ideas:<tag>

   (see `ideas/tags`_ for valid values for ``<tag>``)


.. |downloads_ideas| image:: https://img.shields.io/conda/dn/bioconda/ideas.svg?style=flat
   :target: https://anaconda.org/bioconda/ideas
   :alt:   (downloads)
.. |docker_ideas| image:: https://quay.io/repository/biocontainers/ideas/status
   :target: https://quay.io/repository/biocontainers/ideas
.. _`ideas/tags`: https://quay.io/repository/biocontainers/ideas?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ideas/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ideas/README.html