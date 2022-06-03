# Spatial_analytics_final_project

## This is the repository for my final project in spatial analytics 

### Project Description
This project will investigate visualizing the spatial dimension of moving out university places, in order to illustrate how the patterns for the motivations can be traced using data from Danmarks Statistik and methods and tools learned throughout this course. Further I will discuss the different aspects of this plan. 

### Repository Structure

The repository includes three folders:

    in: this folder should contain the data that the code is run on
    out: this folder will contain the results after the code has been run
    src: this folder contains the script of code that must be run to achieve the results

### Method

This project consists of one script in R, which wrangles data collected from Danmarks statistik and then uses leaflet/mapbox in order to visualize the location of respectively the current and future universities (points) in comparison to the cycling range (polygons). This visualization will then show the overlaps (and lack of the same), which will make me able to analyze the motivation (parts of) the government's plan for moving out university places. 

### Usage
The project encourages to investigate whether there will be a visual (spatial) effect of the governments' plan of moving out university places. This script then can be reused for future data, as long as its of the same format and has the same column names as I have used. 

In order to run this script using my code you'll have to run the script in R, using the same repository structure as I have for this project. I have placed the data used for the project in the "in" folder, so it can easily be reused, but it can also be found on the following page by using the parameters I have: https://www.dst.dk/da/Statistik/emner/borgere/befolkning/befolkningstal 


### Results
As expected the five cities with most young residents, are the places where the current university places are located, as shown on figure 1 (Copenhagen, Odense, Aarhus, Aalborg and Esbjerg). On figure 2 it is illustrated where the future university places are to be located, using the cycling range as polygons – as of now, it is only Esbjerg that has a cycling range that overlaps with one of the top five cities. It should be marked though, that Esbjerg is already on the map of current universities, and this might be reason it already has a higher number of young residents. My results can be found for further inspection in the "out" folder. 
