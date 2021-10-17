# ParkCompass :compass:

## Description *(v1.0)*
This interactive Grasshopper tool helps **YOU** to identify different routes and ways to navigate through a city to its public parks & gardens.      
Instead of being directed via a mapping application this tool helps you to explore numerous scenic routes through a city!

## Examples

video:   *Exploring Parks/greenspace to a distance of 500m along Budapest City river area*

https://user-images.githubusercontent.com/88935906/137607646-c3c516bc-ec51-4029-ab38-09a12e8e6442.mp4



<br>
<br>

Image below:  *Accompanying graphs help inform decisons regarding transport mode, journey length and start point*
<img src="https://user-images.githubusercontent.com/88935906/137608792-328991f7-8da5-4436-bcd7-6fc5e8612213.jpg" alt="alt text" width="900">


Image below: *The output of these graphs also change as the user adjusts various location/distance parameters*

<img src="https://user-images.githubusercontent.com/88935906/137608921-1715ce74-b5f7-434d-b783-a920bb2a31e5.jpg" alt="alt text" width="900">



## Use

- **Step 1:** Upload OSM file 

...*(recommended study area 3km or file size up to 60mb)*
<br>
  
- **Step 2:** Chose your mode of transport either bike / car / foot / public transport or combination car + foot

...*(use the graphs to help determine amount of available OSM data for each mode)*
<br>
 
- **Step 3:** Draw curve over Base Map to set study area
  <br>  
  
- **Step 4:** Adjust start point along drawn curve and adjust the distance you wish to travel from this point.
  <br>
  
- **Step 5:** Enjoy scenic travels through your city as you explore the city's beautiful parks & gardens!

(*note: Pink panels inside definition specify main user control points*)


## Interpreting Graphs 


![3-02](https://user-images.githubusercontent.com/88935906/137609667-cb3014a0-56e0-427c-88bd-bea58ffcc26f.jpg)

1. Upon selecting your city's OSM file this horizontal bar chart will display insights to the total lengths of ways for each of the transport options in that city. This information will help to inform the user when selecting their desired transport mode. 

2. The information displayed on this gauge chart shifts with the various adjustments made in step 4 above. It reveals the % of park/green space surface area that is within the specified distance as compared to the toal amount of green space area in the city.

3. This vertical bar chart reveals insights such as shortest,longest and average lengths of paths that are being displayed according to the adjustments made in step 4 above. These metrics help inform the user of variations in the displayed routes.

4. This bar chart is similar to char 2 but instead of surface area it reveals insights into the number of parks within the set radius as compared to the total number of parks in the city. Knowing the numbers of parks in these proximities reveals locations that have more choice of parks & greenspace. 

## Other Techniques used

**Vector Field**: *If not on specific paths the vectors help to direct users to the nearest park. The base grid for this component should be adjusted for different size maps.*

<img src="https://user-images.githubusercontent.com/88935906/137610720-7a4b1940-5cad-4036-bbc3-b63736d0f35e.jpg" width="100">


**Metaball**: *The metaball component groups together clusters of park. This enables easy visualisation of parks as well as grouping together parks in close proximity so that multiple paths are not drawn/overlapped to the same vicinity*

<img src="https://user-images.githubusercontent.com/88935906/137610523-e7810089-2578-4b67-8d57-fea7fe04e187.jpg" width="100">


**Annotations**: *The small numbers that notate the end points also order the paths from shortest to longest 1 being the shortest displayed path.*

<img src="https://user-images.githubusercontent.com/88935906/137610799-6c1f5493-b234-4864-9572-356facdc01b7.jpg" width="87">


## Compatibility

- Grasshopper file is optimised for use with Rhino7
  
- Chart Components require the installation of HUMAN UI plugin

## Status

This tool has been developed to a release stage.
