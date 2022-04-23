
<!-- Add banner here -->

# Finding Public Recycle Bins in New York City
## Motivation:
While recycling at home, school and work is relatively straightforward, recycling in public spaces comes with many hurdles. Public recycling bins are placed sporadicly and sometimes, it takes effort to find one. Frequenctly, I have to carry recycling trash with me home to recycle after a day out for the lack of my knowledge of locations of recycling bins in public. In this project, I created this jupyter notebook that will show you 10 nearest public recycling bin near you in NYC and also, show u an interactive map with all the recycling bins information. 


## Dataset:
https://data.cityofnewyork.us/Environment/Public-Recycling-Bins/sxx4-xhzg
<img width="480" alt="image" src="https://user-images.githubusercontent.com/89811897/164916961-7b1efa8d-094d-4071-a2e5-843c5c9b3d63.png">


## Liberies Used:
Pandas, Numpy, Geopy, Folium

## Method: 
This jupyter notebook takes your current geospatial location. Then from the dataset, it calculates the length of the shortest path between two points your location and the recycling bins locations in the dataset, and returns a dataframe output with 10 nearest recycling bins locations near you. At the end, I also created an interactive map with all recycling bins in NYC and your location. 

## Demo/Result:


<img width="309" alt="image" src="https://user-images.githubusercontent.com/89811897/164916608-409af644-475d-4d0f-bbcb-6f1cc54575dd.png">



Click on icons for more information about the recycling bin
<img width="990" alt="image" src="https://user-images.githubusercontent.com/89811897/164916473-e8920e03-a05d-4353-8070-c643ccbc2729.png">


