# ChorDNS: DNS Resolution Analysis with a Distributed Hashtable Approach

## Team

* Benjamin Michalowicz
* Dheeraj Ramchandani
* Ghanendra Piplani
* Tarush Abhaya Jain 

## About

DNS Chord implementation for CSE 534 Final Project.

## Installation

1. Install anaconda
2. `conda create -n py36 python=3.6`
3. `conda activate py36`
4. `cat requirements.txt | while read line; do pip install $line; done`
5. Extract `pyDistAlgo-1.0.12.gz`
5. `python ‪CSE534-ChorDNS/pyDistAlgo-1.0.12/setup.py install`


## How to Run

1. `conda activate py36`
2. `python -m da --message-buffer-size 1000000 -F output --logfile --logfilename test.log src/dns_resolver/main.da`

## References

## TODO

1. ~~Installation~~
2. ~~How to run?~~
3. Getting data files to work
4. Plotting tests results
