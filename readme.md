                                          Description
Which Cell Towers would be feasible to have a Wi-Fi Hotspot implement on them such that they service the students in the nearby high schools and also people (which will also include the students from the nearby high schools) who frequent the nearby parks? 
This question can be addressed by joining datasets on Cell Towers, High Schools and Parks of Howard County
Taking the constraints of the data into consideration, I think the best way to represent the analysis is by using a map where the location of the cell tower can be shown by a pin and the area of coverage could be shown by transparent blue circular layer. The high schools and parks and playgrounds can be shown by small polygons depicting their area in the map. This will provide us with a clear picture as to how many nearby high schools and parks and playgrounds will be serviced within the range of the tower and  help decide which towers can be used to implement the free Wi-Fi technology. 
This dataset has been generated according to the specifications for class INFM600, Fall 2015 at the University of Maryland, College Park.

                                           FILES 
Cell_Towers.csv                                                                                
This is the focal dataset. It contains data on the various locations where a cell tower is present and owned by Howard County, Maryland. It contains specifics on the name, street address, city and geometric point of location.

Schools_High.csv      
This dataset contains information about the public high schools in the Howard County. It includes information such as name, address, city, zip code and geolocation of the public high schools.   

Parks.csv
The dataset includes information about various parks located in Howard county.It contains particulars on the name, address, type of park, area coverage, zip code, geolocation etc. of the parks in Howard County.
    

Wifi_School.csv
This dataset was created by performing an outer join of Cell Towers and High School datasets on the “geom” column which represents the geolocations.

Process Documentation

License
The dataset created for INFM600 class is distributed under a Creative Commons Attribution 4.0 International Public License (see http://creativecommons.org/licenses/by/4.0/ for details)

References
Sanganal, Akshay. (2015). Wifi_School [Data Set].
Available at https://github.com/akshaysanganal/INFM600

Howard County, Maryland. (2014). Schools - High – high school locations [Data set]. 
Retrieved 21st October 2015 from https://data.howardcountymd.gov/

Howard County, Maryland. (2014). Cell Towers – cell tower locations [Data set]. 
Retrieved 21st October 2015 from https://data.howardcountymd.gov/

Howard County, Maryland. (2015). Parks – park locations [Data set]. 
Retrieved 21st October 2015 from https://data.howardcountymd.gov/
