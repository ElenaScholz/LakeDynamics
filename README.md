# LakeDynamics

This Project is part of the course "Global Remote Sensing Applications"
of the EGALE Masters program of the university of Würzburg, supervised
by Dr. Maninder Singh Dhillon.

The aim of the project was the analysis of Lake Surface Area Variations
and the impact of climate variables of Lake Orog Nuur in Mongolia. The
Code for this project was written in Javascript within the Google Earth
Engine platform.

## Abstract: 
Lake surface areas fluctuate due to environmental changes, human activities, and meteorological variability. In this research, Sentinel-2 data was used for the detection of
shoreline and lake surface area variations and the correlation of climate variables of Lake Orog Nuur (Valley of Gobi Lakes, Mongolia). The processing was conducted in the
Google Earth Engine (GEE) at annual and monthly intervals using Sentinel-2 data from 2020 to 2023. To extract shoreline and lake surface area, the Automated Water Extraction
Index (AWEI) and Otsu Threshold were used. These metrics were correlated with climate variables aggregated on a monthly basis from ERA5 data, including precipitation,
temperature, evaporation, and available water. The results indicate high interannual and monthly variations in lake surface area, with the lake drying out twice within the
summer month and refilling within two months, which cannot be directly linked to precipitation or water availability. A high correlation was found between lake surface area and
precipitation/available water from October to March, and decorrelation during the summer months. The findings suggest that especially during summer, other factors such as
river runoff, permafrost and snowmelt from surrounding mountains play a crucial role in lake surface area extent. Therefore, these variables should be included in further analysis
in this region [R1, R2].

To read the poster [Click here](https://drive.google.com/file/d/1NvES7MFvwAqCMJEiPzoJxuzglWM1wJ_5/view?usp=sharing)

## Workflow:

## Access the code

There are two options to access the code:

1.  To get a quick overview over the code follow the link below. It will
    lead to my GEE-repository, where you can try it.\
    \
    [GEE:
    LakeDynamics](https://code.earthengine.google.com/?accept_repo=users/elenascholz/CC2_DrylandDynamics)

2.  If you like to use the code for your own analysis use the provided
    Scripts in the Scripts-folder. There you will find all three
    Scripts.\
    You can copy them into your own repository.\
    **Note**: Start with the file "Variable Definitions". There you can
    change all parameters for the analysis.

## Acknowledgements
[R1]: Klein, I., Dietz, A. J., Gessner, U., Galayeva, A., Myrzakhmetov, A., & Kuenzer, C. (2014). Evaluation of seasonal water body extents in Central Asia over the past 27 years derived from medium-resolution remote sensing data. International Journal of Applied Earth Observation and Geoinformation, 26, 335-349. https://doi.org/10.1016/j.jag.2013.08.004
[R2]: Szumińska, D. „Changes in surface area of the Böön Tsagaan and Orog lakes (Mongolia, Valley of the Lakes, 1974–2013) compared to climate and permafrost changes“, Sedimentary Geology, Volume 340, 2016, Pages 62-73,
ISSN 0037-0738, https://doi.org/10.1016/j.sedgeo.2016.03.002.

To implement the Scripts I used the Otsu Threshold. The function is
provided through Gennadii Donchyts’s package: [Gena
Package](https://code.earthengine.google.co.in/?scriptPath=users%2Fgena%2Fpackages%3Athresholding)\
