# HMVC-Codeigniter-Extension
source for modulars extension for HMVC Codeigniter

<b>WHY WE design project for HMVC? </b>
<br/>
<p>
Key advantages to implementing the HMVC pattern in your development cycle:
<code>
    <b>Modularization </b>: Reduction of dependencies between the disparate parts of the application.
    <b>Organization </b>: Having a folder for each of the relevant triads makes for a lighter work load.
    <b>Reusability </b>: By nature of the design it is easy to reuse nearly every piece of code.
    <b>Extendibility</b>: Makes the application more extensible without sacrificing ease of maintenance.
</code>
These advantages will allow you to get M.O.R.E out of your application with less headaches.

</p>
Folder Structure for HMVC:
<pre><code>
Application
/core
/third_party
/controllers
/views
/modules
    /SecondNewModule
       /controllers
       /models
       /views
   /FirstNewModule
     /controllers
     /models
     /views   
</code></pre>

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
