# Overview
This is a very simple project showing how BentoML can be used

## Environment
Refer to the requirements.txt file for the needed python packages.  It is recommended to use python 3.9.

## train.py
After activating the python environment run train.py.  This will create a bentoml model.
To view the bentoml models in the current environment: bentoml models list

## test.py
This shows a simple inference.

## service.py
This file shows how to run bentoml as an api service.

## bentofile.yaml
This is a packaged bento manifest.
To actually build the bento: bentoml build

