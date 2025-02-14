:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'pyega3'
.. highlight: bash

pyega3
======

.. conda:recipe:: pyega3
   :replaces_section_title:

   EGA python client

   :homepage: https://github.com/EGA-archive/ega-download-client
   :license: APACHE / Apache Software
   :recipe: /`pyega3 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pyega3>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pyega3/meta.yaml>`_

   


.. conda:package:: pyega3

   |downloads_pyega3| |docker_pyega3|

   :versions: 3.0.39-0, 3.0.38-0, 3.0.21-1, 3.0.21-0
   
   :depends python: >3
   :depends python-htsget: 
   :depends requests: 
   :depends tqdm: >=4.26.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install pyega3

   and update with::

      conda update pyega3

   or use the docker container::

      docker pull quay.io/biocontainers/pyega3:<tag>

   (see `pyega3/tags`_ for valid values for ``<tag>``)


.. |downloads_pyega3| image:: https://img.shields.io/conda/dn/bioconda/pyega3.svg?style=flat
   :target: https://anaconda.org/bioconda/pyega3
   :alt:   (downloads)
.. |docker_pyega3| image:: https://quay.io/repository/biocontainers/pyega3/status
   :target: https://quay.io/repository/biocontainers/pyega3
.. _`pyega3/tags`: https://quay.io/repository/biocontainers/pyega3?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/pyega3/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/pyega3/README.html