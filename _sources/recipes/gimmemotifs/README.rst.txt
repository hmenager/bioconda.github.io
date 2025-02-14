:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'gimmemotifs'
.. highlight: bash

gimmemotifs
===========

.. conda:recipe:: gimmemotifs
   :replaces_section_title:

   Motif prediction pipeline and various motif\-related tools

   :homepage: https://github.com/vanheeringen-lab/gimmemotifs
   :license: MIT
   :recipe: /`gimmemotifs <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/gimmemotifs>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/gimmemotifs/meta.yaml>`_
   :links: biotools: :biotools:`gimmemotifs`

   


.. conda:package:: gimmemotifs

   |downloads_gimmemotifs| |docker_gimmemotifs|

   :versions: 0.13.1-3, 0.13.1-2, 0.13.1-1, 0.13.1-0, 0.13.0-1, 0.13.0-0, 0.12.0-1, 0.12.0-0, 0.11.1-1, 0.11.1-0, 0.10.0-0, 0.10.0b6-1, 0.10.0b5-1, 0.10.0b4-1, 0.10.0b4-0, 0.10.0b1-0, 0.9.0.6-0, 0.9.0.5-0, 0.9.0.4-0, 0.9.0.3-2, 0.8.9.1-1
   
   :depends bedtools: 
   :depends diskcache: 
   :depends feather-format: 
   :depends future: 
   :depends gadem: 
   :depends genomepy: 
   :depends ghostscript: 
   :depends homer: 
   :depends jinja2: 
   :depends libgcc-ng: >=7.3.0
   :depends matplotlib: >=2.0
   :depends meme: 
   :depends ncurses: >=6.1,<6.2.0a0
   :depends numpy: 
   :depends pillow: 
   :depends pybedtools: 
   :depends pysam: 
   :depends python: >=3.6,<3.7.0a0
   :depends python-xxhash: 
   :depends pyyaml: >=3.10
   :depends scikit-learn: >=0.18
   :depends scipy: <1.3.0
   :depends seaborn: 
   :depends six: 
   :depends sklearn-contrib-lightning: 
   :depends statsmodels: 
   :depends tqdm: 
   :depends trawler: 
   :depends ucsc-bigbedtobed: 
   :depends ucsc-genepredtobed: 
   :depends weeder: 
   :depends xdg: 
   :depends xgboost: >=0.71
   :depends xxmotif: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install gimmemotifs

   and update with::

      conda update gimmemotifs

   or use the docker container::

      docker pull quay.io/biocontainers/gimmemotifs:<tag>

   (see `gimmemotifs/tags`_ for valid values for ``<tag>``)


.. |downloads_gimmemotifs| image:: https://img.shields.io/conda/dn/bioconda/gimmemotifs.svg?style=flat
   :target: https://anaconda.org/bioconda/gimmemotifs
   :alt:   (downloads)
.. |docker_gimmemotifs| image:: https://quay.io/repository/biocontainers/gimmemotifs/status
   :target: https://quay.io/repository/biocontainers/gimmemotifs
.. _`gimmemotifs/tags`: https://quay.io/repository/biocontainers/gimmemotifs?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/gimmemotifs/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/gimmemotifs/README.html