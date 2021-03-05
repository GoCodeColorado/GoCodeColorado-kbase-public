![gcc_logo_2021](../../Images/GCC_Logo_2021.png)

![ogr_1](./images/ogr_1.PNG)


# Ogr2Ogr Cheatsheet for GoCode Colorado

Ogr2ogr is command line GIS based on the Geospatial Data Abstraction Library, [GDAL](https://gdal.org/), free and open source. It is the backbone of QGIS, and it is super simple to use. The ArcPy of open, for those like me who speak ESRI.

It would seem that Ogr is almost exclusively limited by one’s capacity to research the command or operand for the tool you know in the GUI, here are links to cheat sheets that cover lots of the basics:

- [Boston GIS Ogr2ogr cheatsheet](http://www.bostongis.com/PrinterFriendly.aspx?content_name=ogr_cheatsheet)
- [dwatkns gdal cheat sheet on GitHub](https://github.com/dwtkns/gdal-cheat-sheet)

Below are a few examples to get you started.

1. list all fields in a source file - link to GDAL page on [ogrinfo](https://gdal.org/programs/ogrinfo.html)
  - ogrinfo {input}

2. create csv files
- Input: `ogr2ogr -sql "SELECT 'Arapahoe' AS countyName, 005 AS countyFips, PARCEL_ID AS parcel_id, Situs_Address AS sitAddNum, Owner AS owner FROM arapahoe_parcels" -f`
- Output: `CSV C:\MainDirectory\Parcels\csv\arapahoe.csv D:\Parcels\Parcels_Staging.gdb arapahoe_parcels`

3. add table from gdb into new (source) destination gdb
ogr2ogr -overwrite -t_srs EPSG:26913 -f FileGDB
- Input: `D:\Parcels\Adams\adams_parcel_linework.shp -lco FEATURE_DATASET=adams`
- Ouput: `C:\MainDirectory\Parcels.gdb`

4. create new gdb from copying existing gdb
ogr2ogr -f FileGDB
- Input: `D:\Parcels\Adams\adams_parcel_linework.shp -nln adams`
- Output: `C:\MainDirectory\Parcels.gdb`

5. append - add layers into gdb’s feature classes
ogr2ogr -f FileGDB -append -nln adams_sales C:\MainDirectory\Parcels.gdb D:\Parcels_001\Adams\AssessorsData2014.gdb "sales"

6. list tables for GDB
- ogrinfo D:\Parcels_001\Adams\AssessorsData2014.gdb

7. view records
- ogrinfo D:\Parcels_001\Adams\AssessorsData2014.gdb "sales"

8. join
C:\MainDirectory>ogrinfo -sql "SELECT s.accountno FROM sales s JOIN improvements i on s.ac
countno=i.accountno" D:\Parcels\Adams\AssessorsData2014.gdb

INFO: Open of `D:\Parcels_001\Adams\AssessorsData2014.gdb'
