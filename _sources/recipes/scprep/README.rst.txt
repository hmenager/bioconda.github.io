:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'scprep'
.. highlight: bash

scprep
======

.. conda:recipe:: scprep
   :replaces_section_title:

   Tools for loading and preprocessing biological matrices in Python.

   :homepage: https://github.com/KrishnaswamyLab/scprep
   :license: GPL2 / GNU General Public Version 2
   :recipe: /`scprep <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/scprep>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/scprep/meta.yaml>`_

   


.. conda:package:: scprep

   |downloads_scprep| |docker_scprep|

   :versions: 0.12.2-0, 0.12.1-0, 0.12.0-0, 0.8.1-0, 0.7.1-0
   
   :depends decorator: >=4.3.0
   :depends numpy: >=1.10.0
   :depends pandas: >=0.19.0,<0.24
   :depends python: >=3.5
   :depends scikit-learn: >=0.19.1
   :depends scipy: >=0.18.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install scprep

   and update with::

      conda update scprep

   or use the docker container::

      docker pull quay.io/biocontainers/scprep:<tag>

   (see `scprep/tags`_ for valid values for ``<tag>``)


.. |downloads_scprep| image:: https://img.shields.io/conda/dn/bioconda/scprep.svg?style=flat
   :target: https://anaconda.org/bioconda/scprep
   :alt:   (downloads)
.. |docker_scprep| image:: https://quay.io/repository/biocontainers/scprep/status
   :target: https://quay.io/repository/biocontainers/scprep
.. _`scprep/tags`: https://quay.io/repository/biocontainers/scprep?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/scprep/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/scprep/README.html