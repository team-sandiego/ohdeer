# ohDeer

readme file for ohDeer - a survey and web application to report and analyze animal road impacts

## Mission Statement

Road impacts of animals have had a clear increase in Nova Scotia and right now there is very little infrastructure to ease the transportation of animals through the Nova Scotia road network. Impacts with animals could not only lead to the death of an animal, but could cause major property damage, or in some cases, cause an accident that leads to more serious injuries of passengers in the vehicle. 

The current method of reporting roadkill is a 1-(800) number that connects the reporter with the Department of Natural Resources, the Department of Transportation, the RCMP, or limited voluntary wildlife rescue organizations (there are currently only two notable in Nova Scotia). This method may be considered more tedious than a user-friendly survey application to facilitate the simplicity of reporting with an easy-to-use interface. With this strategic method, it will be easier to keep track of the observation data by importing it directly into a geodatabase that gives a tangible and accurate georeference and other pertinent information that is associated with the event. 

By engaging the public in reporting roadkill, live data and valuable spatial information can be provided to conservation authorities, government agencies, and municipalities to evaluate areas that are more susceptible to road impacts with animals. Observations being directly available in a geodatabase allow these organizations to query the data in order to gain more spatial information on a specific species. 

## App Characteristics

The goal is for this information to be used to promote road safety by providing live data to those responsible for road maintenance and, in the longer term, to encourage intervention methods (i.e. wildlife passageways, fencing, clearing forest near roads, adding signage, road maintenance). 

Our app has two components: 

1. a user-friendly survey component that gathers crowd-sourced observation data input by the public and 
2. the visualization of the road impact observation data via the web application component

## App Usage

### Survey:

The survey component of the application allows the user to input their observation data using the Survey 123 Connect interface. The survey can be accessed by searching ohDeer on the Downloadable Surveys list in the Survey123 application (accessible on Android, IOS and online). 

User options include:

  Animal Type
    -Choose an animal from the drop down list or select other and the user may input the animal type 
  Condition of Animal
    -Deceased
    -Wounded
    -Unsure
  Image 
  Date & Time
  Location
    -A map opens to allow user to geographically pin where the observation was made
  Notes on Location
    -Gives the user the option to expand on the georeference, or, if user has location services turned off, to input directions via text
  Contact Info
    -Full name 
    -Phone number
    -Email

After the observation is submitted, the data is inputted into a geodatabase as a layer file and visualized as a point in the web application.

### Web Application


## Limitations

Possible limitations of this app include:

  -Limited reports coming from rural areas where the population is scarce
  
  -Users having little interest on taking time to fill out a report 
  
  -Users not being able to recognize certain species they see in order to describe them
  
  -In the future, including traffic volume data and numbers of species data should be included as a temporal study to see the difference the app is making in regards to animal conservation 


## Data Sources 

Significant Species and Habitat Database, provided by the Department of Natural Resources included shapefile with data for the entire province

Municipalities/Provincial borders and Nova Scotia Road Network provided by NS Open Data Catalogue 

Nova Scotia Earth at Night provided by NASA Worldview Snapshot


## License

GNU General Public License v3.0

