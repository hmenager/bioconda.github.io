:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconda-utils'
.. highlight: bash

bioconda-utils
==============

.. conda:recipe:: bioconda-utils
   :replaces_section_title:

   Utilities for building and managing bioconda recipes.

   :homepage: http://bioconda.github.io/build-system.html
   :developer docs: https://github.com/bioconda/bioconda-utils
   :license: MIT / MIT
   :recipe: /`bioconda-utils <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconda-utils>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconda-utils/meta.yaml>`_

   


.. conda:package:: bioconda-utils

   |downloads_bioconda-utils| |docker_bioconda-utils|

   :versions: 0.16.7-1, 0.16.7-0, 0.16.6-0, 0.16.5-0, 0.16.3-0, 0.16.2-0, 0.15.13-0, 0.15.12-0, 0.15.11-0, 0.15.10-1, 0.15.10-0, 0.15.8-0, 0.15.7-0, 0.15.3-0, 0.15.2-0, 0.15.1-0, 0.14.9-0, 0.14.3-0, 0.14.2-0, 0.12.3-1, 0.12.3-0, 0.12.0-0, 0.11.4-1, 0.11.4-0, 0.11.3-0, 0.11.2-0, 0.11.1-0
   
   :depends aiofiles: 0.4.*
   :depends aioftp: 0.12.*
   :depends aiohttp: 3.4.*
   :depends aiohttp-jinja2: 1.1.*
   :depends aiohttp-security: 0.4.*
   :depends aiohttp-session: 2.7.*
   :depends aioredis: 1.2.*
   :depends alabaster: 0.7.*
   :depends anaconda-client: 1.6.*
   :depends argh: 0.26.*
   :depends backoff: 1.6.*
   :depends beautifulsoup4: 4.6.*
   :depends boltons: 18.*
   :depends cachetools: 3.0.*
   :depends celery: 4.2.*
   :depends colorlog: 3.1.*
   :depends conda: 4.6.14.*
   :depends conda-build: 3.18.9.*
   :depends conda-forge-pinning: 2019.07.11.*
   :depends conda-verify: 3.1.*
   :depends cryptography: 2.*
   :depends docutils: 
   :depends galaxy-lib: >=18.9.1
   :depends gidgethub: 3.0.*
   :depends git: 
   :depends gitpython: 2.1.*
   :depends gunicorn: 19.9.*
   :depends involucro: 1.1.*
   :depends jinja2: 2.10.*
   :depends jsonschema: 2.6.*
   :depends libblas: * *openblas
   :depends markdown: 3.1.*
   :depends networkx: 1.11.*
   :depends pandas: 0.23.*
   :depends pyaml: 17.12.*
   :depends pygithub: 1.34.*
   :depends pyjwt: 1.7.*
   :depends python: >=3.6
   :depends regex: 2018.08.29.*
   :depends requests: 2.20.*
   :depends ruamel_yaml: 0.15.*
   :depends six: 1.11.*
   :depends skopeo: 0.1.35.*
   :depends sphinx: 
   :depends sphinx-autodoc-typehints: 
   :depends tqdm: >=4.26
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconda-utils

   and update with::

      conda update bioconda-utils

   or use the docker container::

      docker pull quay.io/biocontainers/bioconda-utils:<tag>

   (see `bioconda-utils/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconda-utils| image:: https://img.shields.io/conda/dn/bioconda/bioconda-utils.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconda-utils
   :alt:   (downloads)
.. |docker_bioconda-utils| image:: https://quay.io/repository/biocontainers/bioconda-utils/status
   :target: https://quay.io/repository/biocontainers/bioconda-utils
.. _`bioconda-utils/tags`: https://quay.io/repository/biocontainers/bioconda-utils?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconda-utils/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconda-utils/README.html