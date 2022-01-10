---
title: "LipidTA"
excerpt: "Lipid Traffic Analysis - a python commandline interface for analysing lipidomics data"
collection: projects
---

The source code lives on [github][github].

The documentation lives at [ReadTheDocs][readthedocs].

The project can be installed from [PyPI][pypi].

## Abstract

Lipid Traffic Analysis (LTA) is a tool for using lipidomics data to test hypotheses about how metabolism is controlled.
Lipidomics data from several, metabolically connected tissues from control and experimental groups
can be used to plot the spatial or temporal distribution of lipids.
These distributions identify where changes in lipid metabolism occur and in which lipid pathways,
indicating the locus and biochemical alterations that occur in a given group.
LTA was conceived in two parts.
One is an Abundance Analysis,
in which the error-normalised fold change (ENFC) for the control and given group group is calculated.
Because the ratio of the control and experimental values is scaled by the error,
the ENFCs are easy to plot and compare between compartments.
The second part is a Switch Analysis.
This computes the presence of variables across the network.
Current development is focused on developing the technique for complex networks and on the rate of lipid transport.
