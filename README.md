IRTF SGD Test Datasets
==========================

This repository contains test datasets for use with the the Tessellis software.

Please see the 
[Tessellis Documentation](https://github.com/AJThorpe/tessellis/blob/main/README.md)
for more information on the Tessellis architecture and base infrastructure.

Sample Dataset Sources
-----------------------

- Dataset was aquired through Dr. Casey Honniball's GO program for IRTF Lunar observations
- Contains .fits files aquired from the SpeX GuiderDog Data (SGD)
- Dataset should be considered L1A (uncalibrated, unclean raw detector counts) processing level


System Requirements
---------------------

* tessellis 


IF REQUIRED: Install base tessellis package
------------------------------------------------------------
SKIP IF YOU HAVE ALREADY INSTALLED BASE TESSELLIS ENVIRONMENT 

If Tessellis Base is not yet installed, follow the
[installation instructions](https://github.com/AJThorpe/tessellis/blob/main/docs/installation.rst)
within the tessellis source repo documentation.

Obtain test repo
----------------
```bash
    # Enable tessellis environment appropriately
    git clone https://github.com/AJThorpe/test_data_sgd test_data_sgd
```

Run sample test scripts
-----------------------
```bash

    # Enable Tessellis Environment appropriately

    # Tessellis-based test scripts should successfully return 0 if everything is set up properly.
    tessellis/tests/scripts/test_sgd.sh
```
