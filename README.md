  Flightgear Ryan-Navion model from http://helijah.free.fr/flightgear/hangar.htm with updated
KNS80 Nav Radio and KAP140 Autopilot instruments from https://github.com/reiszner?tab=repositories.

  Navigation Instrument Displays: 
    At panel lower-centre the KCS200-'KI252' ( a mistype for KI525 Indicator Sysytem ) 
is replaced with KCS55-KI525 Indicator common to the lancair-235, updated from KI252 by Torsten Dryer. 
The KI525a Course Devitation Indicator is switched between NAV1 radio, KNS80 RNAV and 'GPS' by setting
the property: /instrumentation/nav-source/selector to 0, 1, 2.
With nav-source/selector set to 1 the CDI will respond to either KNS80 VOR or RNAV waypoint according
to KNS80 Nav Mode setting.  There are push-buttons added on the panel for KI525 nav source selection. 
GPS mode for the KCS55 has not been tested.

nav-source-panel
  This instrument is a three-way radio push-button to set nav-source index for HSI and autopilot.
It's based on the RMI instrument from Helijah's Lancair-235 with the'TAC' label replaced with 'GPS'
for nav-source index value 2; this is the only change to the png image so the image file shows the 
full RMI face and pointers.  The .xml and .ac file are chopped so that only the pushbutton switches
are displayed. 

panel 

  Various panel.xml files are reatained: 
panel-orig.xml     is the original layout with KNS80 situated on the right beyond the radio stack.
panel-orig-525.xml is the original layout, as above with KFC55-KI525, nav=selecot-pbs in place of HSI252
panel-pack.xml     re-arranges the radio stack to include KNS80 for up-close readability
panel-pack-525.xml id the re-arranged the radio stack together with KI525 and nav selector pushbuttons

The last described is copied into panel.xml as the default panel. 


Trim Wheel 
  seems to be mislabelled: rolling the trimwheel from bottom to top adjusts nose-down, 
to descend,  the label suggests 'UP', wrongly. 
 
  
  


