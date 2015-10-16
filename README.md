# hmvcCodeigniterExtension
source for modulars extension for HMVC Codeigniter

WHY WE design project for HMVC?

Key advantages to implementing the HMVC pattern in your development cycle:
Modularization: Reduction of dependencies between the disparate parts of the application.
Organization: Having a folder for each of the relevant triads makes for a lighter work load.
Reusability: By nature of the design it is easy to reuse nearly every piece of code.
Extendibility: Makes the application more extensible without sacrificing ease of maintenance.
These advantages will allow you to get M.O.R.E out of your application with less headaches.

Folder Structure for HMVC:
Application 
-core
-third_party
-controllers
-views
-modules
  -FirstNewModules
    -controllers
    -views
    -models
  -SecondNewModules
    -controllers
    -views
    -models

HOW IT WORKS?
Download core and third_party , then paste folder into Application (root)
Create new folder follow by these below structure into Modules folder.
SecondNewModules
    -controllers
    -views
    -models

How to calling ?
Examples : 
localpath /projectName/index.php/FirstNewModules
