# eFRADIR

This is a repository containing tha data used in the eFRADIR journal paper.
The **networks** folder contains the used networks in *.gml* format.
The **eartquake_probabilities** folder contains the earthquake probability maps in *.csv* format.

## Networks
For each node the position is gived with the Latitude, Longitude coordinates.
For each edge the length, the initial unavailability (unav1), the unavailability after the spine upgrade (unav_final) and if the link is part of the spine (onspine) is given.

## Eathquake probabilities
Each row in the *.csv* files is corresponding to a physical position given by the first 2 columns. After that, the probability of an earthquake with a certain moment magnitude is given for that position. The moment magnitudes are listed in the first row.