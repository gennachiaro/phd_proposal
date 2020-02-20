---
author-meta:
- Genna Chiaro
bibliography:
- content/manual-references.json
date-meta: '2020-02-20'
header-includes: '<!--

  Manubot generated metadata rendered from header-includes-template.html.

  Suggest improvements at https://github.com/manubot/manubot/blob/master/manubot/process/header-includes-template.html

  -->

  <meta name="dc.format" content="text/html" />

  <meta name="dc.title" content="Investigating the Crystal Cargo of Fiamme from the Ora Ignimbrite (Permian, Italy): Elucidating the Spatio-Temporal Evolution of a Crystal-Rich, Supereruption-Sized Magma System" />

  <meta name="citation_title" content="Investigating the Crystal Cargo of Fiamme from the Ora Ignimbrite (Permian, Italy): Elucidating the Spatio-Temporal Evolution of a Crystal-Rich, Supereruption-Sized Magma System" />

  <meta property="og:title" content="Investigating the Crystal Cargo of Fiamme from the Ora Ignimbrite (Permian, Italy): Elucidating the Spatio-Temporal Evolution of a Crystal-Rich, Supereruption-Sized Magma System" />

  <meta property="twitter:title" content="Investigating the Crystal Cargo of Fiamme from the Ora Ignimbrite (Permian, Italy): Elucidating the Spatio-Temporal Evolution of a Crystal-Rich, Supereruption-Sized Magma System" />

  <meta name="dc.date" content="2020-02-20" />

  <meta name="citation_publication_date" content="2020-02-20" />

  <meta name="dc.language" content="en-US" />

  <meta name="citation_language" content="en-US" />

  <meta name="dc.relation.ispartof" content="Manubot" />

  <meta name="dc.publisher" content="Manubot" />

  <meta name="citation_journal_title" content="Manubot" />

  <meta name="citation_technical_report_institution" content="Manubot" />

  <meta name="citation_author" content="Genna Chiaro" />

  <meta name="citation_author_institution" content="Department of Earth and Environmental Sciences, Vanderbilt University" />

  <meta name="citation_author_orcid" content="0000-0002-8981-7679" />

  <meta name="twitter:creator" content="@gennachiaro" />

  <link rel="canonical" href="https://gennachiaro.github.io/phd_proposal/" />

  <meta property="og:url" content="https://gennachiaro.github.io/phd_proposal/" />

  <meta property="twitter:url" content="https://gennachiaro.github.io/phd_proposal/" />

  <meta name="citation_fulltext_html_url" content="https://gennachiaro.github.io/phd_proposal/" />

  <meta name="citation_pdf_url" content="https://gennachiaro.github.io/phd_proposal/manuscript.pdf" />

  <link rel="alternate" type="application/pdf" href="https://gennachiaro.github.io/phd_proposal/manuscript.pdf" />

  <link rel="alternate" type="text/html" href="https://gennachiaro.github.io/phd_proposal/v/ac8596a98d114f31acadd27af5868814390b93f3/" />

  <meta name="manubot_html_url_versioned" content="https://gennachiaro.github.io/phd_proposal/v/ac8596a98d114f31acadd27af5868814390b93f3/" />

  <meta name="manubot_pdf_url_versioned" content="https://gennachiaro.github.io/phd_proposal/v/ac8596a98d114f31acadd27af5868814390b93f3/manuscript.pdf" />

  <meta property="og:type" content="article" />

  <meta property="twitter:card" content="summary_large_image" />

  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />

  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />

  <meta name="theme-color" content="#ad1457" />

  <!-- end Manubot generated metadata -->'
keywords:
- ora caldera
- minerals
- python
lang: en-US
manubot-clear-requests-cache: false
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
title: 'Investigating the Crystal Cargo of Fiamme from the Ora Ignimbrite (Permian, Italy): Elucidating the Spatio-Temporal Evolution of a Crystal-Rich, Supereruption-Sized Magma System'
...






<small><em>
This manuscript
([permalink](https://gennachiaro.github.io/phd_proposal/v/ac8596a98d114f31acadd27af5868814390b93f3/))
was automatically generated
from [gennachiaro/phd_proposal@ac8596a](https://github.com/gennachiaro/phd_proposal/tree/ac8596a98d114f31acadd27af5868814390b93f3)
on February 20, 2020.
</em></small>

## Authors



+ **Genna Chiaro**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-8981-7679](https://orcid.org/0000-0002-8981-7679)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [gennachiaro](https://github.com/gennachiaro)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [gennachiaro](https://twitter.com/gennachiaro)<br>
  <small>
     Department of Earth and Environmental Sciences, Vanderbilt University
  </small>



## Motivation

Supereruptions, events that expel >450 km3 of magma from the subsurface, are the most extreme expressions of eruptive volcanism on Earth (Sparks et al., 2005).  These catastrophic events tend to occur every ~100,000 years (Mason et al., 2004).  Due to their scarcity, we are limited to studying the resulting deposits of these colossal eruptions.  By investigating the evolutionary history preserved in mineral rims, unaltered volcanic glass compositions, spatial distribution of deposits, and timescales of magmatic processes, we can inform our current hypotheses regarding the formation of large silicic magma systems that are capable of supereruption.    
	
Our inability to obtain high-resolution subsurface images has spurred innovative methods for resolving the organization of magma in the crust.  If we know major element concentrations of the original melt and the minerals present, we can obtain temperature and pressure estimates using the thermodynamics software, Rhyolite-MELTS (Gualda and Ghiorso, 2014).  Importantly, this can help determine where the magma bodies were situated in the crust prior to eruption.  Major and trace element compositions of volcanic glasses can provide information on the number of magma bodies in the system (Begué et al., 2014).  Furthermore, both the lateral distribution of volcanic glasses and 40Ar/39Ar sanidine geochronology can provide insight on the evolution of the eruption and whether the deposit was emplaced instantaneously or had distinct volcanic pulses (Begué et al., 2014; Kay et al., 2011).  

I plan to investigate the pre-eruptive conditions of a crystal-rich supereruption, the Ora Ignimbrite, in order to fill current gaps in knowledge regarding the structure and evolution of highly-evolved, crystal-rich, trans-crustal magma systems.

The following research questions are the main focus of my dissertation: 

  **1.	Can we use mineral major and trace element compositions to identify fiamme type and population?**

  **2.	Do the mineral populations record similar histories?  What can this tell us about magmatic processes during the assembly and eruption of large silicic systems?**

  **3.	Can we observe clustering of fiamme populations in space and time? What does this suggest about the subsurface architecture of the Ora magmatic system?  Are we able to identify different phases of the eruption and the tapping of separate vents?**

  **4.	Can high-precision 40Ar/39Ar sanidine ages subdivide the Ora eruption into distinguishable volcanic pulses, thereby illuminating the episodic tempo and dynamic behavior of this very large magmatic system?**

The Permian Ora Ignimbrites (>1,200 km3) are advantageous deposits for this study because glacial incision has revealed exceptional intracaldera exposures with >1,000 m of vertical relief.  I plan to expand upon my M.S. work on the Ora vitrophyre horizons and develop major and trace element-based hierarchical clustering algorithms in python to identify minerals that correspond to the pre-defined fiamme types and populations identified in Chiaro (2019).  I will also develop a python script that creates phase composition maps from BSE thin section scans by calibrating the greyscale values to EDS mineral analyses (Willis et al., 2017).  An image recognition machine-learning algorithm will also be created in python that classifies minerals from phase compositions maps into their respective populations.  A hot-spot clustering analysis (Ripley’s k-function) in ArcGIS will be used to determine the distribution of fiamme types and populations throughout the entire deposit and high-precision 40Ar/39Ar sanidine ages will provide eruption ages.  By integrating this project with the Rhyolite-MELTS pressures calculated in Chiaro et al., (in prep), we hope to elucidate the spatio-temporal evolution of a supereruption-sized, crystal-rich magma system. 


## Background

The supereruption-scale Ora Ignimbrites are products of an ignimbrite flareup resulting from subduction of the Paleotethys Ocean and the consequent formation of Pangaea (Cassinis et al., 2012).  Glacial incision of the Permian Ora Ignimbrites (>1,200 km3) reveals heterogeneous intracaldera deposits with >1,000 m of relief.  Less voluminous outflow was emplaced to the north and south of the caldera and is stratigraphically similar to late-erupted intracaldera units (Marocchi et al., 2008).  The Ora deposits are interpreted to be low-intensity eruptions that tapped multiple magma bodies and were sourced from discrete vents (Willcock et al., 2015).  Bulk rock chemistry and mineralogy suggest that caldera collapse and eruption initiated in the south and migrated northward through time (Willcock et al., 2013).  

<p align="center">
<img src="https://user-images.githubusercontent.com/56849646/72564434-5238ba80-3875-11ea-92ce-a7e11f834ea9.png" width="90%"></p> 

<p align="center">Figure 1: A map of the field location.  The four fiamme types identified in Chiaro et al. (in prep) are listed with their corresponding vitrophyre locations.</p>

<p align="center">Table 1: Samples collected in Fall 2017 and Spring 2019.  Sample locations are shown in Fig. 1.  The number of bulk tuff samples and fiamme are listed.</p>

**Samples:**|**Location:**|**Type:**|**Bulk Tuff:**|**Fiamme:**
:-----:|:-----:|:-----:|:-----:|:-----:
**ORA 2**|Outflow Vitrophyre|Vitrophyre|9|31
**ORA 3**|Northern Intracaldera|Bulk Tuff|1|1
**ORA 4**|Odorizzi Quarry|Bulk Tuff|2|50
**ORA 5**|Intracaldera Vitrophyre|Vitrophyre|1|30
**ORA 6**|Northern Intracaldera|Rhyolite Dike|4| 
**ORA 7**|Base of Northern Intracaldera|Bulk Tuff|1| 
**ORA 8**|Northern Intracaldera|Bulk Tuff|1| 
**ORA 9**|NW Outflow 1|Biotite-Rich Fiamme| |1
**ORA 10**|NW Outflow 2|Medium-Grained Fiamme| |1
**ORA 11**|Castel Firmiano|Ash/Ignimbrite Contact|3| 
**ORA 12**|Rhyolite Dike|Granite Dike|4| 
**ORA 13**|Rhyolite Dike|Potential Fiamma| |1
**ORA 14**|Caldera Rim Cutting Dike|Porphyritic Coarse-Grained Dike|1| 
**ORA 15**|Caldera Rim Cutting Dike|Medium-Grained Dike |1| 
**ORA 16**|Cava Flor Quarry|Fine and Coarse-Grained Fiamme| |4
**ORA 17**|NW Outflow 3|Fine to Medium-Grained Fiamme| |3
**ORA 18**|Magdalena Hike|Pseudotachylite|1| 
**ORA 19**|Magdalena Hike @ Sculpture|Fine and Coarse-Grained Dikes|4|

Recent work investigated the pre-eruptive architecture of the Ora magmatic system by studying the textural, mineralogical, and geochemical features of fiamme (Chiaro, 2019).  Fiamme were collected from two vitrophyre horizons, an early-erupted intracaldera deposit and a late-erupted outflow deposit, in order to find well-preserved glass.  These fiamme were initially grouped into four types based on crystal content and biotite content (Table 2).  Glass major elements further verified the categorization scheme (Fig. 2).  The tight clustering of MG and VCCR glass major element compositions suggests that the glasses are unaltered and thus represent pristine melt compositions (Fig. 2).

<p align="center">Table 2: The four fiamme types and their location, crystal content, maximum phenocryst size, and mafic content (Chiaro et al., in prep).</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/56849646/72564985-895b9b80-3876-11ea-9ddb-7eeb32da66e5.png" width="100%"></p> 

<p align="center">
<img src="https://user-images.githubusercontent.com/56849646/74773086-d3111a80-5256-11ea-8420-d8298448067b.png" width="90%"></p> 

<p align="center">Figure 2: All fiamme major element glass compositions.  The colors correspond to the fiamme types shown above in Table 2. (a) The tight clustering of VCCR and MG fiamme suggest that these glasses did not undergo alteration.  (b) Clustering in the Na2O vs. K2O plot provides further evidence that the VCCR and MG glasses represent pristine melt compositions.</p>

Glass trace element compositions reveal at least three discrete populations for both the VCCR and MG fiamme, suggesting the presence of multiple magma batches within the Ora system (Fig. 3).  Furthermore, the magma batches that erupted to form the intracaldera deposits were distinct from the magma batches that contributed to the outflow.  

Pre-eruptive storage pressures from the Rhyolite-MELTS (Q2F) geobarometer suggest that there were two potential scenarios for the subsurface organization of magma bodies in the Ora system (Fig. 4).  Either there were two distinct crystal mush zones located at slightly different depths within the crust, or there was a continuous crystal mush present with multiple heterogeneous zones located throughout (Chiaro, 2019).  

<p align="center">
<img src="https://user-images.githubusercontent.com/56849646/72565422-6b426b00-3877-11ea-9d2e-68c5bbb85cd9.png" width="90%"></p> 

<p align="center">Figure 3: (a) A rare earth element diagram showing differences between the early-erupted intracaldera (VCCR) and late-erupted outflow (MG) fiamme. (b) A plot of strontium vs. barium illustrates six discrete glass populations from the VCCR and MG fiamme.  Each population is inferred to represent a separate magma batch.</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/56849646/72565474-8e6d1a80-3877-11ea-8b54-da854fa797b2.png" width="90%"></p> 
 
<p align="center">Figure 4: (a) Different fiamme types were stored at different pressures in the crust, with a progression of erupting shallower to deeper magmas through time.  (b) Silica content vs. pressure shows variable storage depths for the FGCP melt, suggesting that there were multiple, small melt bodies located at different depths throughout the magma chamber (from Chiaro, 2019).</p>


## Approach

Sampling horizons for this project were chosen to (1) span the full duration of ignimbrite emplacement, (2) represent key lithologies based on observed textural variations and bulk rock geochemistry, and (3) reflect features within the section that might relate to possible time gaps (Fig. 5).  These locations were identified from stratigraphic logs in Willcock et al. (2013) which characterize observed changes in volcanic lithofacies.  I also utilized work detailing the stratigraphic variation of bulk rock compositions and crystal contents from Willcock et al. (2015) to inform my sampling strategy.  

<p align="center">
<img src="https://user-images.githubusercontent.com/56849646/74671934-cebf0180-5171-11ea-9d75-437d162ebe0b.png" width="90%"></p>

<p align="center">
<img src="https://user-images.githubusercontent.com/56849646/74672141-455bff00-5172-11ea-9f08-6f02e414ecdf.png" width="90%"></p> 

<p align="center">Figure 5: (a) A map of the Ora Ignimbrite deposits with acquired samples and future sampling sites.  Modified from Willcock et al., 2013.  (b) A cross section of the Athesian Volcanic Group from NNW to SSE.  Future sampling sites are shown with their approximate stratigraphic horizons in the intracaldera and outflows.  Modified from Bradner et al., 2016.</p>

*Mineral-Based Fiamme Classification:*

I plan to build on the work completed for my M.S. (Chiaro, 2019) and determine a mineral-based characterization scheme in order to categorize fiamme throughout the entire Ora deposit.  Fiamme with well-preserved glass are only present in the vitrophyre horizons; this necessitates an alternative approach to fingerprinting fiamme.  We will use mineral major and trace element compositions from plagioclase, alkali feldspar, and biotite to determine each fiamme type and population.  Preliminary work shows that biotite and plagioclase major elements can be used to differentiate intracaldera vs. outflow fiamme (Fig. 6).  Furthermore, biotite major element compositions can be used to infer both fiamme type and population (Fig. 6).  

Sliwinski et al. (2017) has shown that biotite trace element compositions can be used to fingerprint magma batches at Las Cañadas volcano in Tenerife.  Similarly, biotite major elements have been used to differentiate tephra deposits of the Toba Tuff (Smith et al., 2011).  Our glass trace element compositions differentiate fiamme populations in Ora; each fiamme population is interpreted to represent an individual magma batch (Fig. 3, 6).  Biotite rims grown from these discrete magma batches will likely retain different trace element compositions, allowing for a mineral-based classification to fingerprint different magma batches.    

<p align="center">
<img src="https://user-images.githubusercontent.com/56849646/72555930-3c21fe80-3863-11ea-96e3-2f958b3af366.png" width="45%"></img> <img src="https://user-images.githubusercontent.com/56849646/72555952-4512d000-3863-11ea-9ebc-e9299a09a0b9.png" width="45%"></p> 
  
<p align="center">Figure 6: Biotite and plagioclase major element compositions from fiamme.  Fiamme are divided into population based on hue.  Both plagioclase and biotite can be used to determine fiamme type, and biotite can also determine fiamme population.  Figure from Chiaro et al., 2020 (in prep).</p>

*Hierarchical Clustering and Machine Learning in Python:*

The foundation of this project requires major and trace element compositions for entire minerals.  I plan to develop a hierarchical agglomerative clustering algorithm in python for major elements in order to statistically determine how many clusters of minerals are present in the sampled fiamme.  Another clustering algorithm will be completed using trace elements and we will compare the results.  Once the clusters are identified, we can observe whether they correlate with fiamme type and population (Chiaro, 2019).  If we see a correlation, we can confidently use mineral compositions to classify fiamme throughout the Ora Ignimbrite.  

I will also create individual mineral maps in order to visualize core to rim cluster evolution (Fig. 7).  These maps will be created in two ways: (1) from EDS scans and (2) by correlating BSE greyscale values with EDS analyses.  We will determine which method is best by comparing efficiency and accuracy.  By noting where the clusters occur in each mineral and by looking at a large enough population of core to rim clusters, we can infer whether crystals experienced similar histories.  This approach may reveal information regarding the magmatic processes that occurred prior to the Ora eruption (injection, decompression-driven growth, etc.).                 

<p align="center">
<img src="https://user-images.githubusercontent.com/56849646/72556172-af2b7500-3863-11ea-9745-323250943155.jpg" width="50%"></p>
 
<p align="center">Figure 7: (A-C) BSE and EDS scans of a clinopyroxene phenocryst from the Holuhraun-Bardarbunga eruption in 2014-2015.  The circles show the location of the electron microprobe analysis and the color indicates the corresponding cluster from major element analysis.  (D) Trace element profiles from A-B.  The colors and numbers at the bottom indicate the corresponding cluster identified with major elements.  (E) The same as D, but for another crystal that is not shown (from Luca Caricchi).</p>

We are also interested in identifying the mineral populations present in the ignimbrite matrix and observing whether this varies throughout the deposit.  Machine learning algorithms are becoming widely incorporated in scientific studies and they provide an opportunity to make tedious point-counting obsolete.  I plan to develop a machine learning algorithm in python that can classify each mineral in a phase composition map into its associated population.
  
This involves creating phase composition maps (PCMs) from full thin section BSE images.  Utilizing BSE scans instead of EDS scans is much faster and we can show mineral phases and compositions rather than elemental concentrations (Willis et al., 2017).  This process involves calibrating BSE greyscale values with EDS mineral analyses.  
  
We then have to train the code to classify each mineral with its correct population (based on major element clustering).  The image recognition will be completed with the scikitlearn package in python.  Initial formulation will involve training a supervised machine learning algorithm to identify feldspars.  If successful, we will work to develop an unsupervised neural network algorithm.  The unsupervised neural network algorithm will effectively create clusters automatically via self-organizing maps and then it will tag each mineral with its identified population. 

*Hot Spot Cluster Analysis in ArcGIS:*

We plan to utilize a hot-spot clustering analysis (Ripley’s k-function) in ArcGIS in order to see whether fiamme populations are constrained to specific regions.  This multi-distance spatial cluster analyses investigates the clustering of features over a defined study area.  We believe that this may provide insight on the pre-eruptive magmatic architecture. For example, if the Ora system had two laterally juxtaposed magma chambers that were tapped by different eruptive conduits, we would expect to find two separate clusters with discrete fiamme populations.  Integrating spatial statistics and petrology can help us determine how magma was stored in the crust prior to eruption (single chamber, multiple chambers?) and the approximate locations of storage in the x-y plane.  If we combine our previously obtained Rhyolite-MELTS data to this model, we can elucidate pre-eruptive storage conditions in three-dimensions.

*Sequence Stratigraphy and Ar-Ar Age Dating:*

This aspect of my project will provide a critical temporal framework for the Ora deposits and a context for understanding the spatio-temporal evolution of a giant magmatic system.  Single crystal 40Ar/39Ar sanidine geochronology has the potential to distinguish episodes within supereruption-scale sequences; e.g. Kay et al. (2011) identified three volcanic pulses within the 2 Ma Cerro Galan Ignimbrite.  Ages of the Permian Ora deposits cannot achieve the same absolute precision, but if they span >~50 kyr we should be able to evaluate the eruptive tempo. 

The eruption duration will be determined by obtaining 40Ar/39Ar sanidine ages for early, middle, and late deposits in both the southern and northern calderas (Fig. 5).  Comparison of early-erupted sanidine ages from both calderas can reveal whether there was a break in time for the two-stage caldera collapse model suggested by Willcock et al. (2015). To determine whether the Ora supereruption can be subdivided into distinct volcanic pulses, we will sample from strata with observable changes in lithofacies and bulk rock geochemistry (Willcock et al., 2013). These variations may represent the tapping of distinct magma bodies.

We are also interested in seeing whether we can identify different phases of the eruption and the activation of new volcanic vents.  Can we observe the transition from the early-erupted material (VCCR + FG) to the late-erupted material (MG + FGCP) in the stratigraphic record?  Is it an instantaneous switch?  Or do we find a horizon which includes all four fiamme types?  The possibility that some supereruptions occurred episodically, rather than ~instantaneously, is significant for understanding the storage and mobilization of eruptible magma in the shallow crust (e.g. Cashman et al., 2017).  Evidence for multiple distinct eruptions can alter how we view the evolution and behavior of supereruption-sized magma systems through time.

A creative approach to these questions may provide insight on the eruption dynamics of the Ora Ignimbrite.  Similar to extinction horizons in biostratigraphy, we may be able to observe the extinction of fiamme populations in the volcanic strata.  Coupling 40Ar/39Ar ages with observed fiamme extinction trends may demonstrate whether the eruption migrated northward through time as suggested by Willcock et al (2013). If we observe a northward trend, this may suggest the sequential tapping of laterally juxtaposed magma bodies (Begué et al., 2014). If not, this may represent the eruption of multiple magma bodies emplaced at different depths within a transcrustal magmatic system (Cashman et al., 2017).

<p align="center">
<img src="https://user-images.githubusercontent.com/56849646/72556237-d2562480-3863-11ea-86bc-0a83ca508c78.png" width="70%"></p> 

<p align="center">Figure 6: Bulk rock compositions, biotite crystal content (Bt), and total crystal content (CF) variation through time.  The yellow stars indicate horizons of interest that could show potential changes in eruptive material.  Locations 3 and 8 are intracaldera deposits and correlate with Ora 3 and Ora 8.  We have yet to sample from location 20, which is just south of the Ora 2 vitrophyre unit.  Figure is modified from Willcock et al., 2015.</p>


## Methods

*Sample Collection:*

The samples collected during the 2017 and 2019 field seasons are shown in figure 1 and their descriptions are listed in table 1.  Currently, we have a disproportionate amount of samples from the northern intracaldera.  In order to reduce the sampling bias for our spatial statistics, we will obtain more samples from the southern intracaldera and southern outflow.  Clustering analyses in ArcGIS requires at least 30 features to be reliable.  In order to sample a significant number of fiamme, we will make fiamme mounts to maximize sampling potential and analysis speed.  The ignimbrite matrix samples will be made into 75 x 50 mm billets.

*Analytical Work:*

We plan to obtain BSE full thin section scans and EDS major element compositions with the Tescan VEGA3 SEM at Vanderbilt University.  We will also collect trace element profiles using line scans with consistently spaced laser pits from the ThermoFisher iCAP Qc quadrupole ICPMS at Vanderbilt University.     

*Hierarchical Clustering and Machine Learning in Python:*

The skills to develop code for this project will be gained from taking Data Camp online courses and by utilizing the abundant wealth of information on the internet.  The hierarchical clustering algorithm will effectively calculate the Euclidean distance between all the points and store them in a proximity matrix.  Points with the smallest distances separating them will be merged into clusters until only one single cluster is left.  A dendrogram is then created and the optimum number of clusters is determined visually by intersecting the tallest vertical line in the dendrogram.

We will create phase composition maps (PCMs) for the machine learning algorithms by using the methods described in Willis et al. (2017).  This involves correlating BSE greyscale values with EDS mineral analyses.  The machine learning algorithm will be trained to classify minerals into pre-defined clusters based on pattern recognition.  

*Spatial Statistics in ArcGIS:*

Proficiency in ArcGIS was gained from an Advanced Spatial Analysis course taken in 2018 at Vanderbilt University.  ArcGIS skills will be refined by participating in an ESRI MOOC titled Spatial Data Science: The New Frontier in Analytics which runs from February 12-April 9, 2020.  The Spatial Analysis Research Laboratory (SARL) at Vanderbilt University will also provide expertise in GIS if any roadblocks may arise.   

*Ar-Ar Dating:*

Geochronological analyses will be completed at the New Mexico Geochronology Research Laboratory (NMGRL).  Sanidines will be separated, irradiated, and prepared for analysis using a Thermo Scientific Helix Multicollector.  The analytical capabilities at NMGRL predict that individual analyses will have an age precision of ~20 ka for crystal fragments weighing 0.2 mg. With the large, unaltered sanidines present at Ora, this precision can readily test my research questions.


## Timeline

**Year 1 (2019-2020):**

- April 2020: Qualifying Exam

- May 2020: Submit paper based on MSc work

**Year 2 (2020-2021):**

- September 2020: Fieldwork in Bolzano, Italy to collect samples from the future sampling sites for *Sequence Stratigraphy and 40Ar-39Ar Dating* (Fig. 5)

- Oct 2020: Travel to NM Tech. Learn sample prep, pick sanidines, assemble unknowns and standards into irradiation trays, send out for irradiation*

~4 months of post-irradiation cooldown:

- Feb 2021: Travel to NM Tech. Learn sample analysis and conduct data reduction for age determination

- Mar 2021: Begin work on argon geochronology manuscript

*Processed (irradiated) samples are available for isotope measurements within a 2-6 month window.* 

**Year 3 (2021-2022):**

- Fall 2022: Final trip to Ora to obtain stratigraphic samples we may need to fill gaps in our argument

- Spring 2022: Finalize dissertation and defend!!

- Spring/Summer 2022: Caldera workshop at Ora?


## Broader Impacts

*Open Source:*

Our community has developed novel methods to assess the records preserved within individual crystals to understand the evolution of magmatic systems.  With the expansion of open source science, we have capitalized on collaboration and creating workflows that are accessible to all.  This proposed project will develop python scripts that will automate statistical analyses and tedious point counting to further the open science revolution. 

*Timescales:*

By investigating the eruption ages of the Ora Ignimbrites, we gain insight into the duration and eruptive tempo of supereruption-sized magma volumes which can be used to constrain rates of melt flux during the accretion and evolution of magma bodies in a trans-crustal system (Karakas et al 2019).

*EarthRates:*

Large, unaltered Ora phenocrysts could be an excellent candidate for use as a late Paleozoic sanidine 40Ar/39Ar standard, which is sought by the EarthRates project.  

*Mentoring Undergraduates:*

Possible student working on zircon in Ora??


## References

<!-- Explicitly insert bibliography here -->

<div id="refs"></div>

Bégué, F., Deering, C.D., Gravley, D.M., Kennedy, B.M., Chambefort, I., Gualda, G.A.R., and Bachmann, O., 2014, Extraction, storage and eruption of multiple isolated magma batches in the paired Mamaku and Ohakuri eruption,Taupo volcanic zone, New Zealand: Journal of Petrology, v. 55, p. 1653–1684, doi:10.1093/petrology/egu038.

Brandner, R., Gruber, A., Morelli, C., and Mair, V., 2016, Field trip 1 - Pulses of Neotethys-Rifting in the Permomesozoic of the Dolomites: Geo. Alp, v. 13, p. 7–70.

Cashman, K. V., Sparks, R.S.J., and Blundy, J.D., 2017, Vertically extensive and unstable magmatic systems: A unified view of igneous processes: Science, v. 355, doi:10.1126/science.aag3055.

Cassinis, G., Perotti, C.R., and Ronchi, A., 2012, Permian continental basins in the Southern Alps (Italy) and peri-mediterranean correlations: International Journal of Earth Sciences, v. 101, p. 129–157, doi:10.1007/s00531-011-0642-6.

Chiaro, G.R., 2019, Multiple Magma Bodies: Understanding the Pre-Eruptive Architecture and Magmatic     
Processes of Supereruptions Based on Textural, Mineralogical, and Geochemical Features of Fiamme from the Ora Ignimbrite (Permian) [M.S. thesis]: Vanderbilt University, 157 p.

Kay, S.M., Coira, B., Wörner, G., Kay, R.W., and Singer, B.S., 2011, Geochemical, isotopic and single crystal 40 Ar/ 39 Ar age constraints on the evolution of the Cerro Galán ignimbrites: Bulletin of Volcanology, v. 73, p. 1487–1511, doi:10.1007/s00445-010-0410-7.

Marocchi, M., Morelli, C., Mair, V., Klötzli, U., and Bargossi, G.M., 2008, Evolution of Large Silicic Magma Systems: New U-Pb Zircon Data on the NW Permian Athesian Volcanic Group (Southern Alps, Italy): The Journal of Geology, v. 116, p. 480–498, doi:10.1086/590135.

Mason, B.G., Pyle, D.M., and Oppenheimer, C., 2004, The size and frequency of the largest explosive eruptions on Earth: Bulletin of Volcanology, v. 66, p. 735–748, doi:10.1007/s00445-004-0355-9.
Sliwinski, J.T., Ellis, B.S., Dávila-Harris, P., Wolff, J.A., Olin, P.H., and Bachmann, O., 2017, The use of biotite trace element compositions for fingerprinting magma batches at Las Cañadas volcano, Tenerife: Bulletin of Volcanology, v. 79, doi:10.1007/s00445-016-1088-2.

Smith, V.C., Pearce, N.J.G., Matthews, N.E., Westgate, J.A., Petraglia, M.D., Haslam, M., Lane, C.S., Korisettar, R., and Pal, J.N., 2011, Geochemical fingerprinting of the widespread Toba tephra using biotite compositions: Quaternary International, v. 246, p. 97–104, doi:10.1016/j.quaint.2011.05.012.

Sparks RSJ, Self S, Grattan JP, O., and C, Pyle DM, R.H., 2005, Supereruptions: global effects and future threats.:
Willcock, M.A.W., Bargossi, G.M., Weinberg, R.F., Gasparotto, G., Cas, R.A.F., Giordano, G., and Marocchi, M., 2015, A complex magma reservoir system for a large volume intra- to extra-caldera ignimbrite: Mineralogical and chemical architecture of the VEI8, Permian Ora ignimbrite (Italy): Journal of Volcanology and Geothermal Research, v. 306, p. 17–40, doi:10.1016/j.jvolgeores.2015.09.015.

Willcock, M.A.W., Cas, R.A.F., Giordano, G., and Morelli, C., 2013, The eruption, pyroclastic flow behaviour, and caldera in-filling processes of the extremely large volume (>1290km3), intra- to extra-caldera, Permian Ora (Ignimbrite) Formation, Southern Alps, Italy: Journal of Volcanology and Geothermal Research, v. 265, p. 102–126, doi:10.1016/j.jvolgeores.2013.08.012.

Willis, K. V., Srogi, L.A., Lutz, T., Monson, F.C., and Pollock, M., 2017, Phase Composition Maps integrate mineral compositions with rock textures from the micro-meter to the thin section scale: Computers and Geosciences, v. 109, p. 162–177, doi:10.1016/j.cageo.2017.08.009.





<div id="refs"></div>


