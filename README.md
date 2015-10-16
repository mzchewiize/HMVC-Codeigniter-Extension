# hmvcCodeigniterExtension
source for modulars extension for HMVC Codeigniter

<b>WHY WE design project for HMVC? </b>
<br/>
<p>
Key advantages to implementing the HMVC pattern in your development cycle:
Modularization: Reduction of dependencies between the disparate parts of the application.
Organization: Having a folder for each of the relevant triads makes for a lighter work load.
Reusability: By nature of the design it is easy to reuse nearly every piece of code.
Extendibility: Makes the application more extensible without sacrificing ease of maintenance.
These advantages will allow you to get M.O.R.E out of your application with less headaches.
</p>

Folder Structure for HMVC:
<code>
<p>Application</p>
<p>-core </p>
<p>-third_party</p>
<p>-controllers</p> 
<p>-views </p>
<p>-modules </p>
  <p>&nbsp;-FirstNewModules </p>
    <p>&nbsp;&nbsp;-controllers</p>
    <p>&nbsp;&nbsp;-views </p>
    <p>&nbsp;&nbsp;-models</p>
  <p>&nbsp;-SecondNewModules </p>
    <p>&nbsp;&nbsp;-controllers</p> 
    <p>&nbsp;&nbsp;-views </p>
    <p>&nbsp;&nbsp;-models</p>
</code>

<b>HOW IT WORKS?</b>
<p>
Download core and third_party , then paste folder into Application (root)
Create new folder follow by these below structure into Modules folder.
SecondNewModules
    -controllers
    -views
    -models
</p>

<b>How to calling ? </b>
<p>Examples : 
localpath /projectName/index.php/FirstNewModules 
</p>
