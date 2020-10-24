# PCRasterQGIS
QGIS processing scrips to make PCRaster available in the Processing Toolbox.
Use QGIS in Anaconda and install PCRaster.

Save the scipts to your QGIS profile folder \processing\scripts

Install PCRaster and QGIS
1.	Use the Anaconda prompt
2.	Create the environment as explained here: https://pcraster.geo.uu.nl/pcraster/4.3.0/documentation/pcraster_project/install.html
Basically this command will do the job: conda create --name pcraster37 -c conda-forge python=3.7 pcraster spyder matplotlib
It also installs some other useful libraries.
3.	conda activate pcraster37
4.	Then install QGIS in this environment. Best to use the laterst LTR version:
conda install qgis=3.10.10 --channel conda-forge
5.	Now you can use both PCRaster and QGIS. For example open the python prompt in QGIS and import pcraster there.

