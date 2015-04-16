# spatial-data-integration
Materials for working group on integrating heterogeneous data across scales

## Thu Morning Discussion - General Problem Outline:

 - have data + meta-data about some quantity
   * sometimes direct measurement
   * sometimes indirect measurement + transformation / interpretation process
 - generally has mixed regions of overlap
 - data have different "resolution" + "uncertainty"
   * conventional spatial / temporal issues
   * also precision generally: variation, bias, complex distribution of results relative "finer" scale measurement
   * sometimes well characterized in meta data, sometimes no provenance
 - want to create reference mesh from this data
   * automatable process
   * propagated uncertainty
   * synthesized finer scale where none available
 - using mesh:
   * forecasting
   * back-propagation of subsequent modeling reults to re-evaluate data
   * identify experiments / observations with maximal returns
