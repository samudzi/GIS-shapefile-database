303(d) Listed Impaired Waters with TMDLs
May 01, 2015 National Extract
US EPA Office of Water

This dataset provide geospatial and attribute data identifying the spatial 
extent of waters listed under TMDL having a status of "APPROVED/ESTABLISHED".  
The Total Maximum Daily Load (TMDL) Tracking System contains information 
on waters that are Not Supporting their designated uses. These waters are 
listed by the state as impaired under Section 303(d) of the Clean Water Act. 
The status of TMDLs are also tracked. TMDLs are pollution control measures 
that reduce the discharge of pollutants into impaired waters. A TMDL or 
Total Maximum Daily Load is a calculation of the maximum amount of a pollutant 
that a waterbody can receive and still meet water quality standards, and 
an allocation of that amount to the pollutant's sources. What is a total 
maximum daily load (TMDL)? Water quality standards are set by States, 
Territories, and Tribes. They identify the uses for each waterbody, for 
example, drinking water supply, contact recreation (swimming), and aquatic 
life support (fishing), and the scientific criteria to support that use. 
A TMDL is the sum of the allowable loads of a single pollutant from all 
contributing point and nonpoint sources. The calculation must include a margin of 
safety to ensure that the waterbody can be used for the purposes the state has 
designated. The calculation must also account for seasonal variation in water 
quality. The Clean Water Act, section 303, establishes the water quality 
standards and TMDL programs.

EPA does not collect geospatial information on actual TMDLs; this data layer uses 
the RAD 303(d) GIS layer to identify impaired waterbody segments for which now 
have a TMDL addressing one or more impairments.  Note: the Source Feature ID is 
the 303(d) List ID and not the TMDL ID.

Provided Components:

   1) ESRI Shapefiles
      a) Point Event Geometries
      b) Linear Event Geometries
      c) Area Event Geometries
      
   2) dBASE Tabular Datasets
      a) Record Level Metadata Linking Table
      b) Record Level Metadata
      c) Record Level Metadata Source Citations
      d) Program Attributes
      e) Source Feature ID Summary Table
      
   3) ESRI 10.x ArcMap MXD Project
   
All file geodatabase components have associated metadata which may be accessed 
using EPA's Environmental Dataset Gateway (EDG) located at
https://edg.epa.gov/metadata/catalog/main/home.page

The MXD example is provided to illustrate how to create a relationship between
the spatial geometry datasets and the program attributes datasets from 
ATTAINS/WATERS Expert Query Tool 
(http://ofmpub.epa.gov/pls/waters/f?p=ASKWATERS:EXPERT:0).  In the provided ArcMap 
project, select the IDENTIFY tool and click on any geometry event.  
Using the precreated relationship (utilizing the ESRI_KEY join field
located in both tables), a user may "drill down" through the related data
exploring the one or more impairments assigned to a geometry.

A secondary relationship allows the user to explore the record level metadata
associated with each event.


