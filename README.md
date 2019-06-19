# oligo_melt_kinetics

I. Files 
ReadME.md
Nucleic_Acid_melt_kinetics.Rmd

II. Description
Calculation of rate constants and activation energies for folding and unfolding and Tm from kinetic data

III. Data inputs
A. Must have TWO columns only in csv file, labeled temp and abs (e.g., cool curve from Agilent spectrometer must be pasted onto the end of the heat curve.) Program automatically separates the heat and cool curves for kinetic analysis. 
B. Input sample name and filename in lines 21 and 22. 
C. Input temperature ramp rate in degrees C/min in line 25.
D. Input temperature range to be analyzed in Kelvin in lines 28 and 29. 

Press Knit

IV. Output
An HTML file, which can subsequently be converted into a pdf report if desired.
Report includes plot of absorbance vs. temperature, fits to kinetic curves, and Tm, rate constants, and activation energies obtained from fits. 