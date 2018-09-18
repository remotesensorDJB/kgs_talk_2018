@title[unmanned aerial systems research]
### unmanned aerial systems (uas)
### research
#### @ UofL
###### D.J. Biddle, GISP
---
@title[the plan]
### the plan
- Quick introduction
- Brief Overview of the UofL Center for GIS
- Overview of the small UAS Landscape
- Regulatory Landscape
- UAS Mapping Operations
- Structure from Motion Image Processing
- UAS Research at UofL 
---
@title[introduction]
### About me 
- GIS Technology Consultant @ UofL 
- B.S./M.S. in Applied Geography from UofL
- GISP Certification
- Active in KAMP as board member and committee member
---
@title[ULCGIS Overview]
### ULCGIS Mission
> @size[.6em](Established in 1996, the mission of the University of Louisville Center for Geographic Information Sciences is to provide instruction, applications, and research in geographic information systems technology.  The resources of the Center for GIS are available to professional staff, students, and faculty to provide service and products to individuals and agencies of the University, and the local and state community.)
+++
### Program Overview
![ULCGIS Overview](images/ULCGIS-Org-Chart.png)
+++
### Instruction in Geospatial Technologies
- Broad curriculum of courses in fundamentals and applications of geospatial technology
- Students from all disciplines, both undergraduate and graduate level 
- Technical skills training and emphasis on critical thinking position students for job market or advanced degrees
- Curriculum highlights
  - Intro to Programming for GIS
  - Web Mapping (new for Fall 2018)
  - Survey of UAS Technologies (new for Spring 2019)
  - Undergraduate certificate program: online for Fall 2018
- ESRI-based practical experience
+++
- Administration: GIS Consulting for internal clients
![Fire Map](images/firemap.png)
+++
- Administration: GIS Consulting for internal clients
![Enrollment Map](images/enrollment.png)
+++
- Administration: GIS Consulting for internal clients
![Commuter Map](images/commute.jpg)
+++
- Administration: GIS Consulting for internal clients
![Flood Map](images/floodmap.jpg)
+++
@title[Overview of the UAS Landscape]
### A definition
> Unmanned Aerial Systems (UAS) consist of...
> - an unmanned aerial vehicle (UAV/RPV/drone)
> - a ground-based controller/operator
> - communications between the two
---
@title[Modern small UAS]
### Modern small UAS/imaging drones
- Standard Elements
 - UAV/drone 
 - Mission planning element
 - Command and control element
+++
### Modern small UAS/imaging drones
- Standard Elements
 - Communication link
 - Payload (cameras/sensors/etc)
 - Launch and recovery element (if required)
---
### Modern small UAS/imaging drones
#### Fixed wing vs multirotor
- Fixed wing
 - Simpler structure
 - Greater endurance/flight time
 - Bigger payloads (larger sensors)
 - No stationary flight
+++
### Modern small UAS/imaging drones
#### Fixed wing vs multirotor
- Multirotor
 - vertical takeoff and landing
 - hovering/precise maneuvering
 - more complex (mechanically and electronically)
 - shorter flight times/smaller payloads
+++
### Fixed wing: eBee
![eBee](http://images.gizmag.com/inline/ebee-1.jpg)
+++
### Fixed wing: Trimble UX5
![UX5](http://www.geo-matching.com/upload/2192-general.jpg)
+++
### Fixed Wing: 3DR Aero-M
![Aero Drone](http://www.droidika.com/wp-content/uploads/2015/04/001_aerom.jpg)
+++
### Multirotor: DJI Phantom
![Phantom](https://www.drone-world.com/media/catalog/product/cache/1/image/730x487/9df78eab33525d08d6e5fb8d27136e95/p/4/p4_pro_plus-v2.jpg)
+++
### Multirotor: DJI Mavic Pro
![Mavic](https://www.drone-world.com/media/catalog/product/cache/1/image/730x487/9df78eab33525d08d6e5fb8d27136e95/m/a/mavicpro_remote.jpg)
+++
### Multirotor: 3DR X8
![X8](https://3dr.com/wp-content/uploads/2017/03/x8-m1.jpg)
+++
### Multirotor: DJI Matrice
![Matrice](http://aerialmediapros.com/store/images/product/d/dji-matrice-600-build-your-own-custom-package.png)
+++
### Meow-lti-rotor: Orville the Drone Cat
![Orville the drone cat](https://www.youtube.com/embed/fsdLU6D5PMo?start=27)
---
### small UAS Regulatory Landscape 
- Hobbyist/Recreational Use: No license required! BUT!
 - < 55lbs
 - flown within visual line-of-sight of operator
 - Notify ALL airports/helipads within 5 mi.
+++
### small UAS Regulatory Landscape
- Commercial Operations
 - Fly under FAA Part 107 Rules
 - Register UAS with FAA
 - Obtain Part 107 Remote PIC license
+++
### FAA Part 107 Rules
- <=400ft AGL 
- Daytime only
- Never over people
- [Permission required in special airspace (< 5mi from controlled airports)](https://app.airmap.io/)
- [FAA Part 107 Summary](https://www.faa.gov/uas/media/Part_107_Summary.pdf)
---
### Mapping applications of small UAS
- Aerial Photography/Orthomosaics
- Topographic Mapping/Digital Terrain Modelling
- Photogrammetry/Volumetric Survey
- IR/Thermal analysis
- Vegetation mapping
+++
### Mapping applications of small UAS
- Structure from Motion (SfM) image processing
 - 3D reconstruction based on point matching between overlapping images
 - Same principle as stereoscopic imagery
  - **parallax**: displacement of an object caused by a change in the point of observation
+++
![parallax](images/parallax.jpg)
+++
### Mapping applications of small UAS
- Generalized processing steps:
  1. Feature detection/image matching
  2. Point cloud generation
  3. Ground Control Point (GCP) specification (optional)
  4. Point cloud densification
  5. Mesh generation
  6. Orthomosaic/Digital Surface Model Generation
+++
### Image Processing in Pix4DMapper Pro
![Ray Cloud](https://4.bp.blogspot.com/-l4DIvz6Q8YQ/WMWS7lKOCMI/AAAAAAAABFI/-K1SItx8s0Y4XbRQlLXPsGlOOSJormMigCLcB/s1600/TyingDownGCPRAYCLOUDSgsadgsdgasdgdsg.png)
+++
### Image Processing in AgiSoft Photoscan
![Agisoft](images/agisoft.mp4)
---
### UAS Research Group at UofL
- Small cohort of faculty, staff, and students
- Fleet of drones:
 - 2 x DJ Mavic Pro, 1 x DJI Phantom 4 Pro, 2 x 3DR X8, 2 x 3DR Aero
- Parrot Sequoia NIR sensor for vegetation applications
- GNSS equiment for ground control survey
- 2 FAA licensed Part 107 Remote Pilots
- Workstations and SfM software for processing imagery
+++
### UAS Research Group at UofL 
- Recent/Ongoing Projects
 - Perryville Battlefield site mapping and modelling
 - UofL Stream Institute stream restoration site mapping
 - Kavango Zambezi Vulnerability and Adaptation (KAZAVA) Project 
---
@title[Perryville Battlefield Mapping Project]
### Perryville Battlefield Mapping
###### Interdisciplinary Research Project
- Collaboration with Dr. Daniel Krebs (History Dept)
- Broad Objective: Using geospatial technology to map, model, analyze, and interpret the Civil War battle of Perryville
- Funding through the Commonwealth Center for Humanities and Society
+++
### Perryville Battlefield Mapping
- Multiple components: 
 - Georeferencing historic maps |
 - Interpreting and capturing spatial data from historic texts |
 - Time series analysis to model and interpret progression of troops during battle |
 - Terrain analysis to understand impact of topography on tactical advantages for Confederate Army |
+++
### Perryville Battlefield Mapping
###### Background Information
- October 8th, 1862
- Confederate General Braxton Bragg makes camp with his army on Doctor's Creek near Perryville
- Union Army, led by Gen. Don Carlos Buell, pursues Bragg from the west
+++
### Perryville Battlefield Mapping
###### Background Information
- Knobs to the west of town provide high ground for defensive positions for Bragg's soldiers
- Bragg orders attack on Union positions, but Union army uses cloak of hilly terrain to surprise advancing Confederates. 
- Repeatedly, Union forces retreated before General Bragg's men and established new defensive lines on another ridge.
+++
### Perryville Battlefield Mapping
###### Background Information
- Depressions and hills were not obvious to soldiers during the battle and led to a series of tragic mistakes by commanders on both sides.
- Units found themselves in the midst of withering crossfire because the terrain had forced them into an unfavorable position.
- At the same time, this terrain led to a phenomenon called acoustic shadow. Union General Don Carlos Buell, hence, could not hear the battle from his headquarters and did not send vital reinforcements on time
+++
### Perryville Battlefield Terrain Analysis
- Using digital terrain data from LiDAR and UAS, recreate the setting of the battle:
 - How tall was the corn in early October? What was its impact on sightlines?
 - How tall and dense was the forest separating the battlefield from Buell's position to the West?
 - How many decibels are created by a 10 lb cannon? Under atmospheric conditions in early October?
 - Can we model the acoustic shadow? 
+++ 
### Perryville UAS Field Operations
- First large-scale mapping effort by UofL 
- 2 flights conducted on March 3rd, 2017.
- 60 acres mapped at a resolution of 2 cm
- High winds, cold temperatures, and equipment failures presented difficult conditions
- No ground control used, image EXIF data only 
+++ 
![Perryville Survey](images/perryville1.jpg)
+++ 
![Perryville Survey](images/perryville2.jpg)
+++ 
![Perryville Survey](images/perryville3.jpg)
+++ 
![Perryville Survey](images/perryville4.jpg)
+++
![Perryville Orthophoto](images/perryville_full.jpg)
##### Orthophoto
+++ 
![Perryville Cannon Detail](images/perryville_cannon.jpg)
##### Cannon Detail
+++ 
![Perryville Vegetation Detail](images/perryville_veg.jpg)
##### Vegetation Detail
+++ 
![Perryville Drone Angel](images/perryville_angel.jpg)
##### Drone Angel!
+++
### Next Steps
- Refly area using ground control points for increased accuracy
- Process imagery in Pix4D Mapper Pro
- Derive historic vegetation characteristics from maps and texts
- Generate 3D model for terrain analysis
- Create series of 3D and timeenabled story maps for reinterpretation of battle
---
### UofL Stream Institute 
###### Stream Restoration Mapping
- Collaboration with Speed School Stream Institute
- Stream restoration projects design and build stream and wetland ecosystems
- Strip existing vegetation from site, dig/reinforce new stream channel, grade floodplain
- Miitigate erosion, promote healthy vegetation communities, aquatic life
+++
![Before restoration](images/stream_rest_b4_sm.jpg)

Mill Branch, Knox County, KY before stream restoration
+++
![After restoration](images/stream_rest_aft_sm.jpg)

Mill Branch, Knox County, KY after stream restoration
+++
### UofL Stream Institute
###### Stream Restoration Mapping
- Improve process and add value for existing stream restoration project workflow
- UAS-derived "As Built" survey as substitute for time consuming and expensive ground survey
- Can low-cost UAS data provide accuracy necessary for precise engineering applications?
 - Horizontal and vertical accuracy of digital elevation product paramount
+++
### Early Efforts
- Moody Lane site in Oldham County
- Mission flown using a Blade QX4 UAV with a GoPro camera
- This combo does not encode coordinate information to image EXIF data
- Even with ground control, resulting image quality was lacking
- GPS navigation system also of poor reliability
+++
![Moody Lane site](images/moody1.JPG)
+++
![Moody Lane site](images/moody2.JPG)
+++
![Moody Lane site](images/moody3.JPG)
+++
![Moody Lane site](images/crash.JPG)
+++
![Moody Lane site](images/stream_moody.jpg)
+++
![Moody Lane site](images/Animation.gif)
+++
### Stream Mapping 2.0
##### Stonecoal Branch, Morehead, KY (9 acres)
![Stonecoal](images/stonecoal_loc.jpg)
+++
![Stonecoal #1](images/DSC_0754.jpg)
+++
![Stonecoal #1](images/DSC_0766.jpg)
+++
### Site Characteristics
- 9 acres of narrow upland valley
- Sparse vegetation around channel/floodplain
- Mature trees lining restoration site
- Steep gradient from upvalley end to downvalley end (200ft elevation change)
+++
### Challenges to UAS Operations
- Narrow site necessitates flight high above tallest trees
 - limits potential resolution
- Steep gradient changes ground sampling distance/resolution
 - SfM software expects consistent GSD throughout image
- Wooded surrounding area presents risk of equipment loss
+++
### Field operations
- Sept 9th, 2017
- Variable lighting conditions 
 - strong, shifting shadows throughout the day
- Stream Institute conducted ground control survey using robotic total station
- 2 flights at 100m elevation with DJI Phantom 4 Pro
- Resulting data at 2cm resolution, Horiz/Vert error < 6"
+++
![Stonecoal Flight Plan](images/stonecoal_flight.JPG)
+++
![Stonecoal Video](https://www.youtube.com/embed/oggkjrZpJgk)
+++
![Stonecoal Preview](images/stonecoal_preview.jpg)
+++
![Stonecoal Ortho](images/morehead_ortho.jpg)

Orthophoto
+++
![Stonecoal Ortho Zoom](images/morehead_ortho_zoom.JPG)

Orthophoto Detail
+++
![Stonecoal DSM](images/morehead_dsm.jpg)

DSM
+++
![Stonecoal DSM Zoom](images/morehead_dsm_zoom.jpg)

DSM Detail
+++
![Stonecoal Contours](images/morehead_contours_zoom.jpg)

1 foot contour lines
+++
###### 3D Site Model
https://www.dronedeploy.com/app2/data/59c9bd7d52db903288ddf60d 
+++
### Next steps
- Explore RTK GNSS for improved ground control efficiency
- Explore stairstepped flights to normalize GSD across terrain
- Explore derivative spatial products and their value to stream restoration research
- Obtain funding to build capacity for more stream restoration mapping efforts
---
### Thanks!
##### Any Questions? 




 






