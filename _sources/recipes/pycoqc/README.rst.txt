:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'pycoqc'
.. highlight: bash

pycoqc
======

.. conda:recipe:: pycoqc
   :replaces_section_title:

   Python 3 package for Jupyter Notebook\, computing metrics and generating plots from Oxford Nanopore Albacore report

   :homepage: https://github.com/a-slide/pycoQC
   :license: GPL / GPL-3.0
   :recipe: /`pycoqc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pycoqc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pycoqc/meta.yaml>`_

   


.. conda:package:: pycoqc

   |downloads_pycoqc| |docker_pycoqc|

   :versions: 2.5.0.3-0, 2.2.4-0, 2.2.3-2, 2.2.3-1, 1.0.alpha1-0
   
   :depends h5py: >=2.8.0
   :depends jinja2: >=2.10
   :depends jupyter_contrib_nbextensions: 
   :depends jupyterthemes: 
   :depends notebook: >=4.0.0
   :depends numpy: >=1.13
   :depends pandas: >=0.23
   :depends plotly: >=3.4
   :depends python: >=3
   :depends scipy: >=1.1
   :depends tqdm: >=4.23
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install pycoqc

   and update with::

      conda update pycoqc

   or use the docker container::

      docker pull quay.io/biocontainers/pycoqc:<tag>

   (see `pycoqc/tags`_ for valid values for ``<tag>``)


.. |downloads_pycoqc| image:: https://img.shields.io/conda/dn/bioconda/pycoqc.svg?style=flat
   :target: https://anaconda.org/bioconda/pycoqc
   :alt:   (downloads)
.. |docker_pycoqc| image:: https://quay.io/repository/biocontainers/pycoqc/status
   :target: https://quay.io/repository/biocontainers/pycoqc
.. _`pycoqc/tags`: https://quay.io/repository/biocontainers/pycoqc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/pycoqc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/pycoqc/README.html