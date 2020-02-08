# Capstone Project - The Battle of Neighborhoods
## Description of the problem and the background
As a person living in Ireland, I found out about the Irish Tradition before Christmas - 12 Pubs of Christmas Pub Crawl, where you and your friends visit 12 pubs in Christmas jumpers. I suggest that this can be an extremly unique opportunity in North America. After my primary research, I also noticed that there are little similar business projects and proposed that this topic can be chosen as Capstone project
In order to do so, it is important to find out 12 best pubs according to Foursquare and calculate average distance from the mean coordinates in order to understand the most suitable city to start a business
## A description of the data 
The Foursquare API will be used to extrapolate the coordinates to show it on the map. Based on the previous assignements, New York and Toronto were chosen to solve the problem. Furthermore, it became important to set limit to the needed number of pubs - 12 and to add pub category id to our query. Then, I normalised the results and got names, addresses, latitudes and longitudes of the pubs to show them on the map.
## Methodology
In order to solve the problem, it was needed, at first, to import all essential packages that were used in previous labs. Secondly, .json query was created to find out the credentials of the 12 pubs. Thirdly, folium.map was used to show the points on the maps for primary analysis (based on the algorithm of Toronto lab). Fourthly, I created the point, which contains the mean coordinates of the selected pubs, that is supposed to considered as a started point for crawl. After that, I calculated the mean distance between the starting point and the chosen pubs. Finally, this variable was the key in this "battle"


