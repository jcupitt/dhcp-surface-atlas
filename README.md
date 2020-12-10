# dHCP surface atlas, 10/12/2020

This surface atlas was prepared by this software:

https://github.com/jcupitt/SurfaceAtlasConstruction/tree/revise-scripts

Which in turn was derived from this software:

https://github.com/jelenabozek/SurfaceAtlasConstruction

Which is described in this paper:

*Construction of a neonatal cortical surface atlas using Multimodal
Surface Matching in the Developing Human Connectome Project*, Bozek et al.,
Neuroimage, 179, p. 11-29, 2018

All 980 neonatal dHCP scans that passed structural pipeline QC were used,
with no attempt to remove duplicate subjects:

https://biomedia.github.io/dHCP-release-notes/

The construction was run for eight iterations. Sigma was set to 1.0, but
allowed to rise up to 2.5 at the age extremes.


