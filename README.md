# Elastic Optical Network Simulator

This simulator run arrival requests on an Elastic Optical Network Simulator.

## Getting Started

These instructions will guide you to run this simulator.

### Files

'config.py': It defines the parameters of the simulator

'eon_simulator.py': It contains EON simulator

'run.py': It starts simulation of EON

### Installing

It requires: python 2.7, networkx 1.10, numpy,
 decorator-3.4.0

######

python 2.7
networkx==1.10
numpy
simpy==2.2
decorator-3.4.0

#######

PIP install d'ont run in python 2.7, deprecated in jan/21

download exactaly versions and install manually

install via PIP offline install, or easyinstall 

pip 20.3.4 from python 2.7

in requires.zip They are packages requires

## Commands Verify requires

import sys

sys.version

import networkx

print networkx.__version__

import SimPy

print SimPy.__version__



### Run the simulator

python run.py

### Results

Results of the simulations are put in the folder out according to the choose topology
