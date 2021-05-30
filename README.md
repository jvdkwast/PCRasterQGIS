# PCRasterQGIS
QGIS processing scripts to make PCRaster available in the Processing Toolbox.
Use QGIS in Anaconda and install PCRaster.

Save the scripts to your QGIS profile folder \processing\scripts

Install PCRaster and QGIS
1.	Use the Anaconda prompt
2.	Create the environment with PCRaster and QGIS:

    <code>conda create --name pcrasterqgis-c conda-forge pcraster qgis</code>

    It also installs some other useful libraries.
3.	Activate the environment <code>conda activate pcrasterqgis</code>
4.	Now you can use both PCRaster and QGIS. For example open the python prompt in QGIS and import pcraster there.

More info about installing PCRaster with conda: https://pcraster.geo.uu.nl/pcraster/4.3.1/documentation/pcraster_project/install.html
More info about installing QGIS with conda: https://gisunchained.wordpress.com/2019/05/29/using-qgis-from-conda/

__[Video tutorial](https://youtu.be/IeqUhS_IwVY)__

After setting up the conda environment, you can use the QGIS Resource Sharing plugin to add PCRaster tools to the toolbox.
Install the plugin, go to Settings and add: https://github.com/jvdkwast/qgisrepository.git

![resourcesharingpcraster](https://user-images.githubusercontent.com/1172662/118008040-fee15a00-b34c-11eb-848b-4b2713db12cb.gif)

__[QGIS Open Day May 2021 presentation](https://youtu.be/jSwWvsT2JGM)__
