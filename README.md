# Everything is Spatial: Data and Digital Mapping

---

**Instructor**: Mimi Onuoha  
**Time**: Mondays 3:20 - 5:50
</br>**Contact**: <cgo221@nyu.edu>
</br>**Office Hours**: [Calendar](https://calendar.google.com/calendar/selfsched?sstoken=UUl0bkJBeEw5QmpTfGRlZmF1bHR8MTVmMGJiY2ZkYjkyNWQ0NGQ1Y2YzODliMDQ0MmRlODU) 


## Course Description


Digital technologies have created new opportunities and resources for mapping, cartography, and geolocation-based visual investigation. It has also brought the need to consider issues concerning power, representation, and space. In this seven-week course, students will be introduced to GIS (geographical information system) basics and learn the practical realities of working with spatial data using digital mapping tools and technologies like mapshaper, Leaflet.js, TileMill, MapBox, and d3.js. Special attention will be paid to working with different types of data (specifically geodata) formats. 

Time will also be devoted to investigating the conceptual questions that inform geographic data collection/representation and strategies for counter-mapping. Topics of discussion will include: what do maps represent as visual information artifacts? What happens when we consider claims to space as topics for art-based investigations? How is the expression of geodata a result of political processes? What does it mean for virtual creations to refer to physical realities, and in what ways do the two shape one another? 

Students will work individually on weekly assignments, but will have the opportunity to collaborate on a final project that addresses the techniques and topics studied in the course. To get the most out of this course, students should already have an understanding of HTML, CSS, and Javascript basics. 

This two-credit course will meet the first seven weeks of the semester. 


#### Format
Each week will begin with a selection of students presenting assignment from previous week. If there was a reading assigned, the class will start with a brief discussion of it (no laptops open during discussion).  The bulk of the class will be spent introducing and experimenting with more technical mapping methods and tools.

#### Learning Objectives 
- Exposure to broad range of techniques in digital mapping (students should eventually focus on one or two)
- Become conversational in the topics that surround the theory and understanding of cartography and mapping space
- Create maps (or map-based objects) that work as art objects and challenge common conventions or understandings of the capabilities of maps.

#### Grading
Course marks will be determined by evaluating class participation, weekly assignments, and the final project. 



---

## Syllabus 
NOTE: This syllabus is subject to change, and will be updated weekly. Star or bookmark and check often!


#### Week One - January 23
*About the course, logistics, and each other.* 

*What is a map? What's the history of mapping? How are maps used in ways that advance agendas? What are the tools involved in digital/web mapping, and what makes it different from its predecessors?* 

[Presentation](http://mimionuoha.github.io/spring2017-digitalmapping/weekone/): a quick history of mapping; analog vs digital vs web; how web mapping works; what maps do

- Introductions
- Discussion / Viewing: What can mapping do?
- Demonstration: A simple web map (Leaflet.js)

**ASSIGNMENTS**:

- Read the introduction to [this](https://www.justinobeirne.com/cartography-comparison) comparison of Google Maps and Apple Maps. 
- Create a map:
	- Change the [location](http://www.latlong.net/)
	- Use Leaflet.js, load tiles from [Stamen](http://maps.stamen.com/#toner-lite/12/37.7707/-122.3781), [CartoDB](https://cartodb.com/basemaps/) or any other basemap provider 
	- Push map online to your blog or github.io page and send me the link before Monday
- Go through [this](http://maptime.io/anatomy-of-a-web-map/#0) (but skim it! don't worry too much, we'll talk more in class)
- Download [Moves App](https://moves-app.com/) and record your activity this week. You don't have to sign in with Facebook, and you don't have to create an account.


#### Week Two - January 30

*Where does geographic data come from? What forms does it take, how has it been used in the past? How should we think about it now? Plus everything you need to know about tiles, and the basic anatomy of a web map.*

- Discussion of Reading + Assignments
- [Presentation](http://mimionuoha.github.io/spring2017-digitalmapping/weektwo/)
- Demonstration: Adding data to our maps (tools: geojsonlint, Mapshaper, geojson.io).
- [This is useful](https://github.com/tmcw/mapmakers-cheatsheet). 

**ASSIGNMENTS**: 

- Keep your Moves data running! 

	
#### Week Three - February 6
*Geodata + slippy maps*

- Overview of mapping tools, when to use what
- Leaflet/Mapbox, adding and manipulating data for slippy maps  

**ASSIGNMENTS**: 

- Reading: Borges and Baudrillard (in readings folder)
- Export your Moves data from the [website](https://accounts.moves-app.com/signin) 
	- Note: if you didn't create an account before, you will have to go to the app and create one now (click the small M in the lower right corner > settings > create account)
- Create a map using your Moves data. Just as we did in class, make the data more legible by accessing the underlying geojson. What is interesting? What is missing? Make the story clear from the map. 
	- If you want a more advanced challenge: display night vs daytime trips, add a legend for toggling the displays, or try animating paths. 
- Don't forget to push your map online! 


#### Week Four - February 13
*Visual Cues, Design Considerations. How can we use visual cues to tell stories, and layer data? Expanding our tool repertoire.* 

Download [QGIS](http://www.kyngchaos.com/software/qgis)   
Sign up for [Mapbox Studio](https://www.mapbox.com/studio/signup/)

- Discussion of reading + go over last week's assignment
- Mapbox for changing basemap styles 
- QGIS overview of creating maps and working with Natural Earth Data

Find Natural Earth Data [here](https://www.dropbox.com/sh/qtg8jwspuzo9m4a/AAAn943XXSOiIpn2QZ1Bt98Qa?dl=0).

Screen recording from class is [here](https://www.youtube.com/watch?v=pGdK4qLwOMI). 


**ASSIGNMENTS**: 

- Reading: *How to Lie With Maps*, chapter 7   (see readings folder)
- Use Mapbox Studio to create a new basemap style and map some data from NYC's [open data portal](https://nycopendata.socrata.com) (you can also use Mapzen's [Tangram](https://mapzen.com/products/tangram/) if you're so inclined.)
- Use QGIS to create a map of the physical features of all of some country in the world. Get Natural Earth Data from [here](http://www.naturalearthdata.com/downloads/), post an image of the map you create. 
- Upload your map and image online, email me the link before class.

#### Week Five - February 27
*Discussing final projects: expectations, presentation. Aerial and Satellite Imagery.*

- Discussion of reading + last week's assignment + what the rest of the course will be like
- Final project brief and requirements
- All about and working with satellite imagery


**ASSIGNMENTS**: [to come]

- Tell a story using satellite imagery. You should use whatever tool best gets the job done, depending on what you are highlighting. Some examples: you can reveal something using some of the other landsat bands, or highlight before and after imagery, or grab images from certain locations on Google Maps, etc. Feel free to be creative! 
- Note: this will be your last assignment before your final project. If you haven't turned in other assignments, please turn them in this week
- Send me your ideas for your final project. 



#### Week Six - March 6
*Experimental Geography in practice (guest presentation), more working with satellite and aerial imagery, intro to d3 for maps if time.* 

- Guest Speaker: [Ingrid Burrington](https://lifewinning.com/) 
- More on satellite imagery
- Quick D3 for maps overview!

**ASSIGNMENT**: Work on final projects


#### Week Seven - March 20
*Final Class* 

- Presenting Final Projects (featuring guest crtic [Dan Phiffer](https://phiffer.org/) (Mapzen, Small Data, Occupy.here) 

 