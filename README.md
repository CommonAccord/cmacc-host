# cmacc-host<br>
A bare folder and some stubs for the CommonAccord application.  <br>

# MAKE AN INSTANCE:

1.  On your computer you will need two standard software packages:  A) "LAMP" stack web server and B) git.  

  A.  For the "LAMP" stack, I use MAMP successfully on my Mac.  https://www.mamp.info/en/  download and install in /Applications/.  On the MAMP "Web Server" tab - select Apache web server and set to something like ~{user}/Sites.  Start the servers (you won't use MySQL, but it seems to start anyway).  Note what "port" you are using. It might be like :8888, or might be nothing (on PC?). You'll need to know the port number in step 4.  PCs don't have Perl installed by default, so you may have to install it. 
  
  B. For git: on Mac - https://desktop.github.com/ 
  
2. Start "cloning" the necessary files.  

  A. From https://github.com/CommonAccord/cmacc-host, Clone using the green "Clone or Download" button, then the "Open in Desktop".  Guide the clone to be in ~{user}/Sites/.  
  B. From https://github.com/CommonAccord/cmacc-app, Clone using the green "Clone or Download" button then the "Open in Desktop".  Guide the clone to be in ~{user}/Sites/cmacc-host/vendor/.
  C. Start adding documents:  https://github.com/CommonAccord/Z-CmA, Clone using the green "Clone of Download" button.  Clone, using "Open in Desktop".  Guide the clone to be in ~{user}/Sites/cmacc-host/Doc/G/.  Rename so it becomes ~{user}/Sites/cmacc-host/Doc/G/Z/.  
  D. Test:  Open browser and navigate to http://localhost{:portnumber}/cmacc-host/index.php?action=list&file=G/Z/ol/3.  See if you get a page, and if so, click on "Document".  You should get a little, bare section list with {Ti} 1. {1.Sec} 2. {2.Sec} 3. {3.Sec}.  If so, success!  Continue by cloning materials you want to work on.  Keep an eye out for their listed "DEPENDENCIES".  You will need to clone those, too.

You can add files using a text editor, move files using a file manager, edit files with an editor or the "Edit" view in the app.  If you use an IDE - for instance Emacs - you can make edits across groups of files and otherwise improve your productivity.

Feedback at CommonAccord.Slack.com or commonaccord@gmail.com, or ... make a pull request!


DEPENDENCIES:

A LAMP stack, for instance MAMP (mamp.info), perl, git.
