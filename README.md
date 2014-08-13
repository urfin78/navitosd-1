navitosd-1
==========


My Layout is based on one 800x480 layout, which was posted on wiki.navit-project.org OSD_Layouts page some years ago. I changed it to fit for my FWVGA (854x480px) Android device (Motorola Milestone 2 (Droid 2)). It should work both horizontally and vertically and differs if a route is set or not.

Download the graphic files here and put it in an subfolder osd_graphics of your navit dir. (Or just change the osd_graphics/ location in the XML to your needs)

Most of the elements should be self explaining, but for the sake of completeness:

##### With route:
###### Top
* left: Streetname of the street driving
* beneath: GPS Status (actually it is "vehicle.position_radius", because the "real" gps status wasn't working on my Android device) and Route_Status
* right: remaining length of route (km or meter)
* beneath: time of arrival / remaining time

###### Middle
* left: zoom in and back to position (if you dragged the map somewhere else)
* right: zoom out and abort routing

###### Bottom
* left: next turn with remaining lenght to it
* middle: on which street to turn
* right: driving speed and speed restriction of street with speed warner (turns red if driving to fast)

##### Without route
###### Top
* left: Streetname of the street driving
* beneath: GPS Status (actually it is "vehicle.position_radius", because the "real" gps status wasn't working on my Android device)
* right: Height (meter)

###### Middle
* left: zoom in and back to position (if you dragged the map somewhere else)
* right: zoom out

###### Bottom
* right: driving speed and speed restriction of street with speed warner (turns red if driving to fast)

If you find any error or have a question regarding this layout, feel free to contact me here.
