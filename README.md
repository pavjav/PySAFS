# PySAFS
Python Interface for SAFS RAID Array Architecture

Preparing repo for PySAFS

PySAFS is a python interface for the SAFS Architecture.
Using: libboost-python 1.55.0 (Trusty-Tahr)

The goal of the project is to create a simple python shell api for heap data analysis

Future Goals:
Benchmarking operations by way of an SSD RAID 0 setup (preferably with a ThunderBolt 3 RAID box)

SAFS/FlashX: https://github.com/zheng-da/FlashX

Side Note: Ultimately, a RAID 5 set up using TB3 r/w speeds would degrade the hardware in a short amount of time. Meanwhile, we should opt for TB2 RAID boxes, as it is cheaper than outfitting machines with pricey TB3 add-in cards or new mobos, and pySAFS should (hopefully) translate into that.


