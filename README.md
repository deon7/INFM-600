# INFM-600
Includes files and documents relating to Information Organization assignment for INFM 600

-------
Version
-------

Version 1.0 (October 2015)

-------------
Focal Dataset
-------------
My Focal dataset contains all public schools (elementary, middle and high) in the Howard County area. This dataset was obtained by combining three different files, ie: the schools were categorized into 3 different sets based on school level (elementary, middle, high). Each School is identified by an FID and a School name in the file. Additional details like the area and the zipcode are also included in the file. The 'geom' column in the file gives us information about the geo-location of a particular school. This is important because we will combine our other two datasets based on geo-location to find proximity of crosswalks and flashing signs around different types of schools. 

Secondary Datasets:

------------------------------
Paint School Crosswalk dataset
------------------------------
This file includes information regarding painted crosswalks related to schools in the Howard County area and was collected using a GPS. All this information is maintained by Public Works.

-----------------------------
School Flashing Signs dataset 
-----------------------------
This file includes geo location about different flashing signs near schools in the Howard County area. These signs are used to reduce the speed limit near schools. 

----------------------------------------------------------------
Important Questions that can be answered using this new dataset: 
----------------------------------------------------------------
Q. Is there an inherent higher priority around safety near elementary schools (via modes of proximity of painted crosswalks and flashing signs) as compared to middle and high schools? Owing to the age groups that are enrolled in elementary schools, do the public works set a higher emphasis on having these facilities installed around them as compared to having these equally distributed around all schools in the Howard County area?
 
---------
Analysis: 
---------
We can look at the proximity of paint school crosswalks and flashing signs to nearby schools and then classify them as elementary, middle or high schools. The geo location would help us in determining proximity and would give us a count of the number of crosswalks and flashing signs near a particular school level. 
This can then be tallied up to find out if there is a significant difference in the number of amenities near a specific school type.
The data would be best represented via a map of the schools in the county area and then the distribution of crosswalks and flashing signs around these schools. Labelling the schools as elementary, middle or high school would be our next logical step. This would give us a good visual representation of all the data for our analysis. 

Document for combining datasets can be found under the title of 'Processing Document' under the same file location repository (INFM 600)

------- 
License
-------

The dataset created for INFM600 class is distributed under a Creative Commons Attribution 4.0 International Public License(see http://creativecommons.org/licenses/by/4.0/ for details)


-----------
References: 
-----------

Crasto, Deon. (2015) Tagging crosswalks and flashing signs near public schools in Howard County, MD [Dataset]
Available at https://github.com/deon7/INFM-600/

Howard County, Maryland. (November 2014). Schools - Elementary [Data set]. Retrieved October 25th 2015 from https://data.howardcountymd.gov/


Howard County, Maryland. (November 2014). Schools - Middle [Data set]. Retrieved October 25th 2015 from https://data.howardcountymd.gov/


Howard County, Maryland. (Novemeber 2014). Schools - High [Data set]. Retrieved October 25th 2015 from https://data.howardcountymd.gov/

Howard County, Maryland. Paint School Crosswalks[Data set]. Retrieved October 25th 2015 from https://data.howardcountymd.gov/

Howard County, Maryland. School Flashing Signs[Data set]. Retrieved October 25th 2015 from https://data.howardcountymd.gov/

