:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'biobb_pmx'
.. highlight: bash

biobb_pmx
=========

.. conda:recipe:: biobb_pmx
   :replaces_section_title:

   Biobb\_pmx is the Biobb module collection to perform PMX \(http\:\/\/pmx.mpibpc.mpg.de\) executions.

   :homepage: https://github.com/bioexcel/biobb_pmx
   :license: APACHE / Apache Software License
   :recipe: /`biobb_pmx <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/biobb_pmx>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/biobb_pmx/meta.yaml>`_

   \[\!\[\]\(https\:\/\/readthedocs.org\/projects\/biobb\-pmx\/badge\/\?version\=latest\)\]\(https\:\/\/biobb\-pmx.readthedocs.io\/en\/latest\/\?badge\=latest\)
   \[\!\[\]\(https\:\/\/img.shields.io\/badge\/install\%20with\-bioconda\-brightgreen.svg\?style\=flat\)\]\(https\:\/\/anaconda.org\/bioconda\/biobb\_pmx\)
   \[\!\[\]\(https\:\/\/quay.io\/repository\/biocontainers\/biobb\_pmx\/status\)\]\(https\:\/\/quay.io\/repository\/biocontainers\/biobb\_pmx\)
   \[\!\[\]\(https\:\/\/www.singularity\-hub.org\/static\/img\/hosted\-singularity\-\-hub\-\%23e32929.svg\)\]\(https\:\/\/www.singularity\-hub.org\/collections\/2735\/usage\)
   \[\!\[\]\(https\:\/\/img.shields.io\/badge\/License\-Apache\%202.0\-blue.svg\)\]\(https\:\/\/opensource.org\/licenses\/Apache\-2.0\)

   \# biobb\_pmx

   \#\#\# Introduction
   Biobb\_pmx is the Biobb module collection to perform PMX \(http\:\/\/pmx.mpibpc.mpg.de\) executions.
   Biobb \(BioExcel building blocks\) packages are Python building blocks that
   create new layer of compatibility and interoperability over popular
   bioinformatics tools.
   The latest documentation of this package can be found in our readthedocs site\:
   \[latest API documentation\]\(http\:\/\/biobb\_pmx.readthedocs.io\/en\/latest\/\).

   \#\#\# Version
   v1.0.0 April 2019 Release

   \#\#\# Copyright \& Licensing
   This software has been developed in the MMB group \(http\:\/\/mmb.irbbarcelona.org\) at the
   BSC \(http\:\/\/www.bsc.es\/\) \& IRB \(https\:\/\/www.irbbarcelona.org\/\) for the European BioExcel \(http\:\/\/bioexcel.eu\/\)\, funded by the European Commission
   \(EU H2020 \[675728\]\(http\:\/\/cordis.europa.eu\/projects\/675728\)\).

   \* \(c\) 2015\-2019 \[Barcelona Supercomputing Center\]\(https\:\/\/www.bsc.es\/\)
   \* \(c\) 2015\-2019 \[Institute for Research in Biomedicine\]\(https\:\/\/www.irbbarcelona.org\/\)

   Licensed under the
   \[Apache License 2.0\]\(https\:\/\/www.apache.org\/licenses\/LICENSE\-2.0\)\, see the file
   \[LICENSE\]\(LICENSE\) for details.

   \!\[\]\(https\:\/\/bioexcel.eu\/wp\-content\/uploads\/2015\/12\/Bioexcell\_logo\_1080px\_transp.png \"Bioexcel\"\)





.. conda:package:: biobb_pmx

   |downloads_biobb_pmx| |docker_biobb_pmx|

   :versions: 1.0.1-0, 1.0.0-0
   
   :depends biobb_common: 1.1.6
   :depends python: 3.6.*
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install biobb_pmx

   and update with::

      conda update biobb_pmx

   or use the docker container::

      docker pull quay.io/biocontainers/biobb_pmx:<tag>

   (see `biobb_pmx/tags`_ for valid values for ``<tag>``)


.. |downloads_biobb_pmx| image:: https://img.shields.io/conda/dn/bioconda/biobb_pmx.svg?style=flat
   :target: https://anaconda.org/bioconda/biobb_pmx
   :alt:   (downloads)
.. |docker_biobb_pmx| image:: https://quay.io/repository/biocontainers/biobb_pmx/status
   :target: https://quay.io/repository/biocontainers/biobb_pmx
.. _`biobb_pmx/tags`: https://quay.io/repository/biocontainers/biobb_pmx?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/biobb_pmx/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/biobb_pmx/README.html