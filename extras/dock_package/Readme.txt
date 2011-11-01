dock_package readme
-------------------

dock_pacakge is a experimental system which allows you to control the dock on a system.

The system is open and as such you may edit to meet your requirements. Contributions back are welcome.
At this stage users who do not have a local system account will have the dock modified based upon settings which you will want to edit. The easiest place to start editing the dock settings regarding which files are placed into the dock is by editing the file : 

<additemtodock/extras/dock_package/root/Library/Additional Files/SystemMaintenance/dock/add_to_dock_list.txt>

This is a list of items to be placed into the dock.

If you have problems, suggestions then please let me know.

There are also a number of tools which have been released since the additemtodock initiated which offer a very fine grain of control with regards dock management on Mac OS X.

The easiest way to get started is to follow these instructions : 
 (1) Setup an your client computer (on which we will manage the dock) so that remote home directory logins are working.
 (2) Edit the add_to_dock_list.txt file mentioned above.
 (3) Ensue you have Xcode installed on the system you are using to build the packages
 (3) Build 

There are various modifications which could be a couple of possibilities are listed below : 
 - The add_to_dock_list.txt could be downloaded from an http / rsync server for easy distributed management of dock files.
 - The example com.apple.dock.plist (base dock) could be hosted on an http / rsync server for easy distributed managment.
 - LaunchD could be used to alter the dock rather than using login hooks. That would be a good idea :)
 - We could be using luggage for building the packages. That would also be a good idea :)





