:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'r-syntactic'
.. highlight: bash

r-syntactic
===========

.. conda:recipe:: r-syntactic
   :replaces_section_title:

   Make syntactically valid names out of character vectors.

   :homepage: https://syntactic.acidgenomics.com/
   :developer docs: https://github.com/acidgenomics/syntactic
   :license: MIT
   :recipe: /`r-syntactic <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-syntactic>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-syntactic/meta.yaml>`_

   


.. conda:package:: r-syntactic

   |downloads_r-syntactic| |docker_r-syntactic|

   :versions: 0.3.0-0, 0.2.6-0, 0.2.5-0, 0.2.4-1, 0.2.4-0, 0.2.3-0, 0.2.1-0, 0.2.0-0, 0.1.10-0, 0.1.9-0, 0.1.5-0, 0.1.4-0
   
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-goalie: >=0.3.7
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install r-syntactic

   and update with::

      conda update r-syntactic

   or use the docker container::

      docker pull quay.io/biocontainers/r-syntactic:<tag>

   (see `r-syntactic/tags`_ for valid values for ``<tag>``)


.. |downloads_r-syntactic| image:: https://img.shields.io/conda/dn/bioconda/r-syntactic.svg?style=flat
   :target: https://anaconda.org/bioconda/r-syntactic
   :alt:   (downloads)
.. |docker_r-syntactic| image:: https://quay.io/repository/biocontainers/r-syntactic/status
   :target: https://quay.io/repository/biocontainers/r-syntactic
.. _`r-syntactic/tags`: https://quay.io/repository/biocontainers/r-syntactic?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/r-syntactic/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/r-syntactic/README.html