> [!CAUTION]
> **This repository is an archive for the live project see** https://github.com/gem-pasteur/macsyfinder


MacSyFinder
===========

MacSyFinder - Detection of macromolecular systems in protein datasets using systems modelling and similarity search.


Citation
-------- 
Abby SS, Néron B, Ménager H, Touchon M, Rocha EPC (2014). MacSyFinder: A Program to Mine Genomes for Molecular Systems with an Application to CRISPR-Cas Systems. PLoS ONE 9(10): e110726. doi:10.1371/journal.pone.0110726
http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0110726


Download distribution
---------------------
 
[ ![Download](https://api.bintray.com/packages/gem-pasteur/MacSyFinder/macsyfinder/images/download.svg) ](https://bintray.com/gem-pasteur/MacSyFinder/macsyfinder/_latestVersion)


Installation from distribution
------------------------------

1. Uncompress and untar the package:

   tar -xzf macsyfinder-x.x.tar.gz

2. Go to the macsyfinder directory
 
    cd macsyfinder-1.0

3. Build and install

    python setup.py build
    
    python setup.py test -vv
    
    python setup.py install

    to see all installation options "python setup.py --help"

See the INSTALL file for more details.


Installation from repository
----------------------------

 Please be careful, MacSyView has its own repository: https://github.com/gem-pasteur/macsyview
 
 
Unit tests with Travis-CI
-------------------------
 [![Build Status](https://travis-ci.org/gem-pasteur/macsyfinder.svg?branch=master)](https://travis-ci.org/gem-pasteur/macsyfinder)


Documentation
-------------

You will find complete documentation for setting up your project at the Read the Docs site.

[![Doc] (https://readthedocs.org/projects/macsyfinder/badge/?version=latest)](http://macsyfinder.readthedocs.org/en/latest/#)
