# PCRasterQGIS
QGIS processing scripts to make PCRaster available in the Processing Toolbox.
Use QGIS in Anaconda and install PCRaster.

Save the scripts to your QGIS profile folder \processing\scripts

Install PCRaster and QGIS
1.	Use the Anaconda prompt
2.	Create the environment as explained here: 
    https://pcraster.geo.uu.nl/pcraster/4.3.0/documentation/pcraster_project/install.html
    Basically this command will do the job: 

    <code>conda create --name pcraster37 -c conda-forge python=3.7 pcraster spyder matplotlib</code>

    It also installs some other useful libraries.
3.	<code>conda activate pcraster37</code>
4.	Then install QGIS in this environment.

    <code>conda install qgis --channel conda-forge</code>

5.	Now you can use both PCRaster and QGIS. For example open the python prompt in QGIS and import pcraster there.

__[Video tutorial](https://youtu.be/IeqUhS_IwVY)__



After setting up the conda environment, you can use the QGIS Resource Sharing plugin to add PCRaster tools to the toolbox.
Install the plugin, go to Settings and add: https://github.com/jvdkwast/qgisrepository.git

![resourcesharingpcraster](https://user-images.githubusercontent.com/1172662/118008040-fee15a00-b34c-11eb-848b-4b2713db12cb.gif)

__[QGIS Open Day May 2021 presentation](https://youtu.be/jSwWvsT2JGM)__
