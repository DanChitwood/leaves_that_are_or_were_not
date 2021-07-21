# Leaves that are or were not

Data and code for a manuscript tentatively titled ***The grapevine leaves that are (or were) not: constraints on leaf development and choosing to see what seemingly is not.***

The data and code in this repository are for learning and reproducibile science purposes for a manuscript that is being written. With revisions, the exact wording and analyses may change or not precisely match the corresponding publication (if and when that occurs).

**Procrustes_all.csv:** Dataset from which all analyses are derived.  
**Figures.ipynb:** Jupyter iPython notebook with documented code.  
**Figures 1-6:** Tentative figures using output analyses from the code.  
**Figure_images:** A zip file containing a folder with visual outputs from notebook analyses.  

To help in interpreting the analyses and code contained in this respository, figure legends are provided below:  

**Figure 1: Modeling vein-to-blade ratio as a function of normalized shoot position.** The natural log of the ratio of vein-to-blade area (vein-to-blade ratio) is modeled as a 2nd degree polynomial of normalized shoot position (where 0 is the shoot tip and 1 is the shoot base). The normalized shoot position value corresponding to the minimum vein-to-blade ratio is 0.6379505834434538 (magenta vertical line). This value has a 3.22% difference from the value of the inverse of the golden ratio, 0.61803398875 (gold vertical line).

**Figure 2: Developmental trajectories of leaf development through Principal Component Analysis (PCA) space by species. A-B)** 2nd degree polynomials modeling PC1 (A) and PC2 (B) values by vein-to-blade ratio for three species (*Vitis riparia*, gold; *V. amurensis*, lavender; *Ampelopsis glandulosa* var. *brevipedunculata*, green). **C)** Data points and models plotted as PC2 vs. PC1. Regions corresponding to mature, old leaves and young, small leaves are indicated. **D)** Models for 11 species (indicated by color) and data points colored by vein-to-blade ratio (a white to black gradient, scale provided). Percent variance explained by each PC are indicated in axis labels.

**Figure 3: Allometric changes in leaf shape during development.** Changes in the proportional area different regions of the leaf occupy (middle lobe, lavender blue; vasculature, yellow; distal lobe, light green; distal sinus, dark green; proximal lobe, orange; proximal sinus, magenta) are modeled as developmental trajectories across 100 theoretical time points for three different species: *V. riparia*, *V. amurensis*, and *A. glandulosa* var. *brevipedunculata*. Theoretical grapevine leaves are reconstructed for timepoints 0, 12, 24, 36, 48, 60, 72, 84, and 96 for each species. Note that the trajectories run from mature, large leaves on the left to young, small leaves on the right.

**Figure 4: Theoretical grapevine leaves at the limits of what is empirically observed.** Principal Component Analysis (PCA) space plotting individual leaves colored by vein-to-blade ratio (a white to black gradient, scale provided) and modeled developmental trajectories of different species (indicated by color). Three lines are drawn that encompass the shape of all empirically measured leaves. Theoretical grapevine leaves are reconstructed for five equidistant points along each line (large gray dots), pointed to by lines outside of the plot. Different regions of the leaf are indicated by color: middle lobe, lavender blue; vasculature, yellow; distal lobe, light green; distal sinus, dark green; proximal lobe, orange; proximal sinus, magenta.

**Figure 5: Self-intersecting leaves.** 100 theoretical leaves, equidistantly spaced along PC1 and PC2, were reconstructed. The range was selected to find the limits of theoretical leaves with any self-intersection in any sub-region of the leaf. For each reconstructed leaf, vein-to-blade ratio was calculated (a white to black gradient, scale provided). The boundary that encompasses theoretical leaves with no self-intersection of any region is indicated by a solid, black line. Empirically measured leaves are indicated by points (dodger blue).

**Figure 6: Morphospace.** 100 reconstructed grapevine leaves across PC1 and PC2. Rounded coordinates for each theoretical leaf are indicated along the axes. The boundary that encompasses theoretical leaves with no self-intersection of any region is indicated by a solid black line. The boundary that encompasses nearly all empirically measured leaves is indicated by a dashed black line. Different regions of the leaf are indicated by color: middle lobe, lavender blue; vasculature, yellow; distal lobe, light green; distal sinus, dark green; proximal lobe, orange; proximal sinus, magenta. Alpha transparency is used so that overlapping regions in leaves can be seen.
