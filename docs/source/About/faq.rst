Frequently Asked Questions
============================

Datasets
____________

How is the Combined Drought Indicator computed?
---------------------------------------------------

Combined Drought Indicator based on SPI (from CHIRPS), soil moisture and fAPAR, to
identify areas with potential to suffer agricultural drought, areas where the
vegetation is already affected by drought conditions, and areas in recovery process
to normal conditions after a drought episode. The method is based in 5 impact levels.

These levels are:

- **'Watch'** when a relevant precipitation shortage is observed,

- **'Warning'** when this precipitation shortage comes with a soil moisture anomaly,

- **'Alert'** when these two conditions are accompanied with an anomaly in the vegetation condition,

- **'Partial recovery'** when after a drought episode, the meteorological conditions are recovered to normal but not the vegetation conditions,

- **'Full recovery'** when meteorological and vegetation normal conditions are recovered.

.. seealso:: For more information refer to :ref:`Combined Drought indicator (CDI)` section

Also :download:`Download CDI Factsheet<https://droughtwatch.icpac.net/documents/2/EADW-CDI-Factsheet.pdf>`

------

When will the next CDI be generated?
---------------------------------------------------

CDI is computed based on availability of SPI, fAPAR Anomaly and Soil Moisture Anomaly data as shown in the table below.

+-----------------+---------------------------+----------------------+-----------------+
| **CDI (dekad)** | **fAPAR Anomaly (dekad)** | **SMA (dekad)**      | **SPI (month)** |
+-----------------+---------------------------+----------------------+-----------------+
| 1st             | 1st (same month           | 3rd (previous month  | previous month  |
|                 |                           |                      |                 |
|                 | as CDI)                   | from CDI)            | from CDI        |
+-----------------+---------------------------+----------------------+-----------------+
| 2nd             | 2nd (same month           | 1st (same month      | previous month  |
|                 |                           |                      |                 |
|                 | as CDI)                   | as CDI)              | from CDI        |
+-----------------+---------------------------+----------------------+-----------------+
| 3rd             | 3rd (same month           | 2nd (same month      | same month      |
|                 |                           |                      |                 |
|                 | as CDI)                   | as CDI)              | as CDI          |
+-----------------+---------------------------+----------------------+-----------------+

To elaborate the above table better, below is an example of computation of dekadal CDI for the month of November.

+-----------------+----------------------------+-----------------+-----------------+
| **CDI (dekad)** | **fAPAR Anomaly (dekad)**  | **SMA (dekad)** | **SPI (month)** |
+-----------------+----------------------------+-----------------+-----------------+
| 1st Dekad       | 1st Dekad                  | 3rd Dekad       | October         |
|                 |                            |                 |                 |
| November        | November                   | October         |                 |
+-----------------+----------------------------+-----------------+-----------------+
| 2nd Dekad       | 2nd Dekad                  | 1st Dekad       | October         |
|                 |                            |                 |                 |
| November        | November                   | November        |                 |
+-----------------+----------------------------+-----------------+-----------------+
| 3rd Dekad       | 3rd Dekad                  | 2nd Dekad       | November        |
|                 |                            | November        |                 |
| November        | November                   |                 |                 |
+-----------------+----------------------------+-----------------+-----------------+

Availability of fAPAR Anomaly and Soil Moisture Anomaly datasets is approximately during the dates shown below.

+-----------+-----------+-----------------------------------------------+
| **Month** | **Dekad** | **Data availability dates (these**            |
|           |           |                                               |
|           |           | **are the dates when fAPAR Anomaly**          |
|           |           |                                               |
|           |           | **and Soil Moisture will be made**            |
|           |           |                                               |
|           |           | **available on JRC Jeodpp)**                  |
|           |           +-------------------+---------------------------+
|           |           | **FAPAR Anomaly** | **Soil Moisture Anomaly** |
+-----------+-----------+-------------------+---------------------------+
| January   | 1st       | 18th January      | 21st January              |
|           +-----------+-------------------+---------------------------+
|           | 2nd       | 26th January      | 1st February              |
|           +-----------+-------------------+---------------------------+
|           | 3rd       | 3rd February      | 11th February             |
+-----------+-----------+-------------------+---------------------------+
| February  | 1st       | 19th February     | 21st February             |
|           +-----------+-------------------+---------------------------+
|           | 2nd       | 27th February     | 1st March                 |
|           +-----------+-------------------+---------------------------+
|           | 3rd       | 7th March         | 11th March                |
+-----------+-----------+-------------------+---------------------------+
| March     | 1st       | 15th March        | 21st March                |
|           +-----------+-------------------+---------------------------+
|           | 2nd       | 23rd March        | 1st April                 |
|           +-----------+-------------------+---------------------------+
|           | 3rd       | 8th April         | 11th April                |
+-----------+-----------+-------------------+---------------------------+
| April     | 1st       | 16th April        | 21st April                |
|           +-----------+-------------------+---------------------------+
|           | 2nd       | 24th April        | 1st May                   |
|           +-----------+-------------------+---------------------------+
|           | 3rd       | 2nd May           | 11th May                  |
+-----------+-----------+-------------------+---------------------------+
| May       | 1st       | 18th May          | 21st May                  |
|           +-----------+-------------------+---------------------------+
|           | 2nd       | 26th May          | 1st June                  |
|           +-----------+-------------------+---------------------------+
|           | 3rd       | 3rd June          | 11th June                 |
+-----------+-----------+-------------------+---------------------------+
| June      | 1st       | 19th June         | 21st June                 |
|           +-----------+-------------------+---------------------------+
|           | 2nd       | 27th June         | 1st July                  |
|           +-----------+-------------------+---------------------------+
|           | 3rd       | 5th July          | 11th July                 |
+-----------+-----------+-------------------+---------------------------+
| July      | 1st       | 13th July         | 21st July                 |
|           +-----------+-------------------+---------------------------+
|           | 2nd       | 29th July         | 1st August                |
|           +-----------+-------------------+---------------------------+
|           | 3rd       | 6th August        | 11th August               |
+-----------+-----------+-------------------+---------------------------+
| August    | 1st       | 14th August       | 21st August               |
|           +-----------+-------------------+---------------------------+
|           | 2nd       | 22nd August       | 1st September             |
|           +-----------+-------------------+---------------------------+
|           | 3rd       | 7th September     | 11th September            |
+-----------+-----------+-------------------+---------------------------+
| September | 1st       | 15th September    | 21st September            |
|           +-----------+-------------------+---------------------------+
|           | 2nd       | 23rd September    | 1st October               |
|           +-----------+-------------------+---------------------------+
|           | 3rd       | 9th October       | 11th October              |
+-----------+-----------+-------------------+---------------------------+
| October   | 1st       | 17th October      | 21st October              |
|           +-----------+-------------------+---------------------------+
|           | 2nd       | 25th October      | 1st November              |
|           +-----------+-------------------+---------------------------+
|           | 3rd       | 2nd November      | 11th November             |
+-----------+-----------+-------------------+---------------------------+
| November  | 1st       | 18th November     | 21st November             |
|           +-----------+-------------------+---------------------------+
|           | 2nd       | 26th November     | 1st December              |
|           +-----------+-------------------+---------------------------+
|           | 3rd       | 4th December      | 11th December             |
+-----------+-----------+-------------------+---------------------------+
| December  | 1st       | 12th December     | 21st December             |
|           +-----------+-------------------+---------------------------+
|           | 2nd       | 28th December     | 1st January               |
|           +-----------+-------------------+---------------------------+
|           | 3rd       | 5th January       | 11th January              |
+-----------+-----------+-------------------+---------------------------+

------


Is there an option to download raster data on the drought watch?
------------------------------------------------------------------

Both Geotiff and NetCDF Raster files for datasets on the mapviewer are available on drought watch's https file server at 
https://droughtwatch.icpac.net:5000/ . All files are grouped yearly and bands/time dimansions split based on the temporal resolution.

------


What is the rationale for having recovery levels on the CDI?
-------------------------------------------------------------

Recovery levels on the CDI highlight areas that have returned to their normal conditions after experiencing drought. **Partial Recovery** areas
capture areas that have recovered to their normal meteorological conditions but not vegetation growth while **Full Recovery** areas have recovered to their normal meteorological and 
agricultural conditions.

------


Why is the Combined Drought Indicator saying an area is experiencing drought when I know it is not?
----------------------------------------------------------------------------------------------------------

Generally the assessment of drought is done using individual indicators that are based on meteorological or hydrological data, or remote sensing imagery. 
The development of a combined indicator that integrates meteorological, hydrological and remote sensing data, can help to reduce false alarms, which may arise for example in the case of 
vegetation-based indicators (e.g. FAPAR Anomaly) where a biomass reduction can be caused by factors other than a drought-induced water stress.

The final output should be interpreted as showing areas potentially experiencing drought. Several factors could lead to the identification of patterns 
of drought occurence which do not seem to correlate to what is happening on the ground, the date of analysis being a very important one. While the Combined Drought Indicator integrates
Soil Moisture Anomaly, SPI and fAPAR Anomaly data to yield its results, it is yet to integrate exposure/vulnerability information to furthur customize it for the region. It is also worth 
noting the accuracy of the CDI is constrained by the accuracy of the datasets it is derived from.

Plans are underway to develop a form to crowdsource ground truth information relating to the occurence of drought. In the meantime, feel free to drop your feedback
at https://droughtwatch.icpac.net/contact/

------


Future Plans
_____________________

Any plans on predicting drought?
------------------------------------------------------------------

Plans are underway to incorporate forecasted datasets relevant to drought e.g Forecasted SPI.


Do you plan to support raster data download for custom areas of interest?
-------------------------------------------------------------------------

In addition to supplying raster data for the entire region, development plans are underway to allow users to dynamically download raster files on the system for a subset of their area 
of interest.

Plans for analysis at lower admin levels?
------------------------------------------------------------------

Currently, the system allows for analysis at Administrative Level 1. Development is well underway to extend this analysis for lower administrative levels.


Any other future plans?
--------------------------

The development of the system is currently ongoing with plans to integrate periodic products disseminated as comprehensive reports to subscribed users, provide additional 
thematic datasets, perform drought forecasting, translate system warnings into impact-based information/warnings among other plans.