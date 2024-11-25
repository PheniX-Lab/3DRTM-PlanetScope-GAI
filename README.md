# 3DRTM-PlanetScope-GAI
Please cite this:
Dong, M., Liu, S., Jiang, R., Qi, J., de Solan, B., Comar, A., Li, L., Li, W., Ding, Y., & Baret, F. (2024). Comparing and combining data-driven and model-driven approaches to monitor wheat green area index with high spatio-temporal resolution satellites. Remote Sensing of Environment, 305
The GAI estimation model can be found in https://drive.google.com/file/d/1tQyfr16YaVcRHK1cTp4aDA08hkzCTN4m/view?usp=sharing
This is an improved 3D Radiative Transfer Model for GAI estimation based our previous study (Dong et al., 2024) . This approach integrates some prior information including canopy structure, leaf optical properties and soil background to improve the realism of the simulation. 

A suite of models (MARMIT-2 for soil reflectance, PROSPECT for leaf optical properties, ADEL-Wheat for canopy structure, and LESS for radiative transfer) was employed to generate five simulation datasets incorporating different combinations of prior information.

Table 1. The details of the simulated dataset used to train the retrieval method.
Training
Dataset	Prior knowledge
	Soil	Leaf biochemistry	Stages
D1	Empirical	uniform	whole
D2	MARMIT-2	uniform	whole
D3		co-distribution
	whole
D3Pre			pre-stem elongation
D3post			pre-stem elongation


 

Please cite like this:
Dong, M., Liu, S., Jiang, R., Qi, J., de Solan, B., Comar, A., Li, L., Li, W., Ding, Y., & Baret, F. (2024). Comparing and combining data-driven and model-driven approaches to monitor wheat green area index with high spatio-temporal resolution satellites. Remote Sensing of Environment, 305
