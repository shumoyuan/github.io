---
layout:     post
title:      Implementation of Rainbow Table
subtitle:   A quick method to crack encrypted password
date:       2018-10-27
author:     Jue Yuan
header-img: "img/post-bg-2018.jpg"
tags:
    - Rainbow Table
    - Cryptography
    - Security
---
[ProjectPage](https://github.com/shumoyuan/RainbowTable)

Description:(From wikipedia)
A rainbow table is a precomputed table for caching the output of cryptographic hash functions, usually for cracking password hashes. Tables are usually used in recovering a key derivation function (or credit card numbers, etc.) up to a certain length consisting of a limited set of characters. It is a practical example of a space–time tradeoff, using less computer processing time and more storage than a brute-force attack which calculates a hash on every attempt, but more processing time and less storage than a simple key derivation function with one entry per hash. Use of a key derivation that employs a salt makes this attack infeasible.
Rainbow tables were invented by Philippe Oechslin as an application of an earlier, simpler algorithm by Martin Hellman.

Instruction:

source files:

• utils.py. This file contains utility functions.

• crypto.py. This file defines cryptographic functions.

• rainbow.py. This file contains a partial implementation of rainbow tables.

• attack.py. This file contains attack code.

Requirement:

install PyCrypto with Python3 under Linux
pip3 install pycrypto

usage；
python attack.py problemX
