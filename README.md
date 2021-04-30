This repo constructs a functional connectome using nilearn and the sparse inverse covariance.
We use the **MSDL atlas** of functional regions in movie watching, and the **nilearn.input_data.NiftiMapsMasker** to extract time series.
Note that **MSDL atlas** comes with (x, y, z) MNI coordinates for the different regions.


# Nilearn
Nilearn enables approachable and versatile analyses of brain volumes. It provides statistical and machine-learning tools, with instructive documentation & open community.

pip install -U --user nilearn

Citing nilearn
https://nilearn.github.io/
http://journal.frontiersin.org/article/10.3389/fninf.2014.00014/abstract
