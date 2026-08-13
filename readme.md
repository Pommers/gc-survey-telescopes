<p align="center">
  <img src="figures/logo.png" width="450">
</p>

# GC Surveys in Modern Observatories

## Observatory Analysis

This initial notebook sets up a dataframe (saved to a CSV) which contains all the required initial information for each of the observatories we are considering. From the selected facilities, it will ask, what are these facilities and what are the adopted parameters we will use downstream. For a first pass, published parameters are used; later we might refine the accuracy of these with filter modelling, etc.

## GCLF Reach

Using the facility parameters data, we now ask what GC populations can they actually reach, by modelling the GCLF.