## CoTrack
#### A tool to capture collaboration across physical and digital spaces in collocated blended settings
CoTrack is a tool developed for tracking students' activities in physical and digital spaces during collaboration activities in collocated settings. CoTrack uses **Raspberry Pi based prototype** with a Microphone array with 4 mics. This prototype uses Voice activity detection for identifying the presence of voice and direction of arrival algorithm for detecting the direction from which sound is coming.

To synchronize time in the prototypes, NTP (Network Time Protocol) is used and MQTT protocol is used to transmitting data to the server.

CoTrack uses Etherpad which is an open-source real-time collaborative editor to allows students to interact in digital space. It provides an shared writing space for students. An Ehterpad plugin ([ep_update_track](https://github.com/pankajchejara23/ep_update_track)) is developed to capture students' activities in Etherpad.

#### Dashboard
To visualize the students' activities data from physical and digital spaces, an interactive web-based dashboard has been developed for teachers. It allows the teacher to see the speaking time, group-dynamics, writing activities for each group. The teacher can also visualize the same data for the entire duration of activity using different time-window.  
![dash.png]
