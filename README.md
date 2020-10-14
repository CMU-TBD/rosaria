
For information on how to use RosAria, see <http://wiki.ros.org/ROSARIA>,
especially <http://wiki.ros.org/ROSARIA/Tutorials/How to use ROSARIA>.

## TBD Lab Edits
The following are changes we made to the base ROSARIA package.
- Added `laser_frame` ROS parameter for the `rosaria` node to specify the TF_frame in which the laser is pubished under. 
- Fixed problem where the frame was always called `laser_frame` regardless of name passed into the laser publishing class.