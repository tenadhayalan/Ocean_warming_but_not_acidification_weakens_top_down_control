# Ocean warming but not acidification weakens top-down control of an intertidal foundation species 

Journal: <i> tbd </i>

Tena S. Dhayalan 1, Nyssa J. Silbiger 2 

1 Department of Biology, California State University Northridge, Northridge, California, USA

2 Uehiro Center for the Advancement of Oceanography, Department of Oceanography, University of Hawaiʻi at Mānoa, Honolulu, Hawaiʻi, USA
Corresponding author: Tena S. Dhayalan1 tenadhayalan@gmail.com

## Abstract

As ocean warming and acidification intensify, changes in organismal physiology will drive shifts in community structure. In the California rocky intertidal, organisms regularly experience extreme changes in abiotic conditions during tidal transitions (e.g., enduring daily fluctuations of up to 0.8 pH units and 10–20°C shifts in temperature) which push their physiological limits and increase their susceptibility to the effects of climate change. Here, we aimed to understand the physiological responses of the California mussel (Mytilus californianus) and the predatory emarginate dogwinkle (Nucella emarginata) to predicted future abiotic conditions. We assessed individual metabolic rates of biomass growth, shell growth, respiration, and calcification after four weeks of exposure to a range of nine pHs (7.2-8.0) at two temperature levels (18, 22°C). Whelks and mussels were both unaffected by acidification, but responded differently to the effects of warming. The predatory whelk displayed signs of thermal stress with an average decrease of 50% in respiration rate, 375% in calcification rate, and 33% in shell growth under elevated temperatures. Warming also halved the probability of whelks actively drilling mussels for consumption, which could indicate weaker top-down effects under warm conditions. The mussels were more resistant to warming, showing no changes in any of the physiological measurements between treatments. These results indicate that there are differential responses to ocean warming across trophic levels, reducing predation pressure on a competitively dominant, habitat-forming bivalve, which may alter intertidal biodiversity and shift ecosystem functioning. 

## [Data](/Data)
 * [field](/Data/field)
   * quadrat.csv (mussel and whelk field measurements and densiites)
   * san_pedro_temp_buoy.csv (data from https://data.caloos.org/#metadata/103471/station/data)
 * [growth](/Data/growth)
   * mytilus_initial.csv (initial mussel shell measurements and weights)
   * nucella_initial.csv (initial snail shell measurements and weights)
 * [pH_temp](/Data/pH_temp)
    * 
 * [PR](/Data/PR)
    * RawO2 (contains raw O2 files for all respiration runs)
 * [TA](/Data/TA)
    *
## [Scripts](/Scripts)
 * pCO2_calc.R (calculates carbonate chemistry parameters using carb package)
 * pHcode.R (uses TRIS calibrations and mV readings to calculate pH on the total scale)
 * PR.R (calculates standardized photosynthesis and respiration rates using oxygen measurements and weights)
 * statistical_analysis.Rmd (all statistical analysis and figure output)
 * TA_calc.Rmd (calculates standardized calcification rates using total alkalinity and weights)
 * TotalAlkCalc_wParsing.R (calculates total alkalinity from potentiometric titrations)
## [Output](/Output)
All figures for publication.

