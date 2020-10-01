---
title: "A hierarchically pipelined data acquisition system for single-photon avalanche diode array"
authors:
- Rahmadi Trimananda
date: "2009-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2009-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: In *Master’s Thesis, Delft University of Technology*
publication_short: In *Master’s Thesis, Delft University of Technology*

abstract: Single Photon Avalanche Diode (SPAD) is a type of highly sensitive diode that can detect single photons. It is, therefore, useful for certain applications that need photon sensing capability. A system, consisting of 32 x 32 SPAD array, with its controller alongside on Virtex-II Pro FPGA on board, has been being developed and tested to evince its reliability and robustness. It utilizes the SPAD array for photon counting (time-uncorrelated) and measuring the arrival times of single photons (time-correlated), which implies fast data rate, and, thus, fast data acquisition. Alas, as it was first developed without any adequate data acquisition capability to cope with the potential of the SPAD, it is then considered important to create one.

This thesis report presents a design of a system that is able to perform a robust data acquisition as it works together with the SPAD array and its controller. It has been implemented in Verilog HDL, simulated, synthesized, and tested on the FPGA. Apart from this firmware itself, a set of simple DLL functions has been written to control it. Additionally, a particular software is also created based on the DLL functions to provide a standard interface for the users, while the functions also work with many applications, eg MATLAB. The entire system has been tested, profiled, characterized, and even used in some real experiments. In terms of speed and robustness, it shows a great advancement for the SPAD array data acquisition.

links:
url_pdf: https://repository.tudelft.nl/islandora/object/uuid%3Afac9915f-2aab-4200-94b2-46669371b88d
---
