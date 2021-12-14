Usage
=======

Prerequisites
______________________________________

The read-in tool supports xlsx, xls and docx formats. All doc should be converted to docx before reformatting. 
This tool assumes country-specific structures remain consistent.

.. note:: a slight change in the structure of the raw station file may lead to unsuccessful reformatting.

Logging in
____________

The first port of call for an editor is the login page for the administrator interface. Access this by adding /cms onto the end of your root URL (e.g. https://droughtwatch.icpac.net/cms). Enter your username and password and click Sign in.

.. image:: ../_static/maintenance_guide/login.png
   :align: center

Creating/Updating Stations
______________________________________

As a data manager on the CMS, you are capable of creating new stations which will be referenced during reformating. To create a station, follow the steps below:

First, select '**snippets**' on the left sidebar then select Stations. 

.. image:: ../_static/data_manager_guide/add_station.png
   :align: center

.. image:: ../_static/data_manager_guide/create_station.png
   :align: center


Fill the fields appropriately and save.

.. image:: ../_static/data_manager_guide/add_station_info.png
   :align: center

----------

Reformat Station Data
______________________________________

Daily data
-------------

For daily station data:

1. Select country from list

2. Load station-specific data file

3. Select year and month. (days will be automatically picked from the station file)


.. image:: ../_static/data_manager_guide/daily_data_reformat.png
   :align: center


A preview of the reformatted station data will be shown.

.. image:: ../_static/data_manager_guide/daily_data_preview.png
   :align: center

The tool allows download of reformatted data in csv, shapefile or geojson format.


Dekadal data
--------------

For dekadal station data:

1. Select country from list

2. Load station-specific data file

3. Select date


.. image:: ../_static/data_manager_guide/dekadal_data_reformat.png
   :align: center

A preview of the reformatted station data will be shown. 

.. image:: ../_static/data_manager_guide/dekadal_data_preview.png
   :align: center