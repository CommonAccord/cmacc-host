# cmacc-host<br>
A bare folder and some stubs for the CommonAccord application.  <br>

# MAKE AN INSTANCE:

1.  On your computer you will need two standard software packages:  A) "LAMP" stack web server and B) git.  

  A.  For the "LAMP" stack, I use MAMP successfully on my Mac.  https://www.mamp.info/en/  download and install in /Applications/.  On the MAMP "Web Server" tab - select Apache web server and set to something like ~{user}/Sites.  Start the servers (you won't use MySQL, but it seems to start anyway).  Note what "port" you are using. It might be like :8888, or might be nothing (on PC?). You'll need to know the port number in step 4.  PCs don't have Perl installed by default, so you may have to install it. 
  
  B. For git: on Mac - https://desktop.github.com/ 
  
2. Start "cloning" the necessary files.  

  A. From https://github.com/CommonAccord/cmacc-host, Clone using the green "Clone or Download" button, then the "Open in Desktop".  Guide the clone to be in ~{user}/Sites/.  This includes the basic folder layout and i) the app (https://github.com/CommonAccord/cmacc-app) and the basic set of document widgets for making paragraphs, sections, some documents https://github.com/CommonAccord/Z-CmA, mounted as /G/Z/*)
  B. Test:  Open browser and navigate to http://localhost{:portnumber}/cmacc-host/index.php?action=list&file=G/Z/ol/3.  See if you get a page, and if so, click on "Document".  You should get a little, bare section list with {Ti} 1. {1.Sec} 2. {2.Sec} 3. {3.Sec}.  If so, success!  Continue by cloning materials you want to work on.  Keep an eye out for their listed "DEPENDENCIES".  You will need to clone those, too. If you are making contract agreements, you will very likely want https://github.com/CommonAccord/Agt-Form-CmA, which has frameworks for contract agreements in English and some French. 

You can add files using a text editor, move files using a file manager, edit files with an editor or the "Edit" view in the app.  If you use an IDE - for instance Visual Studio - you can make edits across groups of files and otherwise improve your productivity.

Feedback at CommonAccord.Slack.com or commonaccord@gmail.com, or ... make a pull request!


DEPENDENCIES:

A LAMP stack, for instance MAMP (mamp.info), perl, git.
