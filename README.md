Launch-Terminal-Here
====================

A small Script/App that allows Terminal to open at the current folder location and run a command.

To Run the App, copy it onto your Desktop and double click. It will open Terminal at the current folder location in your Finder. (note that Finder MUST be open for this to work).

Alternativly, copy the App into the desired folder(s) that you wish to use the Launch Terminal here App in, and double click when you are in that folder.

Another alternative is to copy the app into your aplications folder and then drag up to your finder toolbar (alt + cmd + drag for Mavericks and Yosemite). You then have quick access to the App what ever Finder folder you are in.

I have created an icon (OSX Yosemite Design ONLY) that will match the Finder Toolbar icons. If the icon does not load with the App when downloaded, right click on the app, click "show package contents" open the "contents" folder, locate the "icon" and follow thsese instructions:

Step 1: Copy the icon to the clipboard

a) Right click on the file.
b) Choose 'Get Info' from the 'File' menu.
c) In the info window that pops up, click on the icon.
d) Choose 'Copy' from the 'Edit' menu.
e) Close the info window.

Step 2: Paste the icon to the desired item

a) Navagate back to the App (in your appliocation folder or Desktop etc.).
b) Right click on the App
b) Choose 'Get Info' from the 'File' menu.
c) In the info window that pops up, click on the icon
d) Choose 'Paste' from the 'Edit' menu.
e) Close the info window

To Run a command(s) of your choice, open the app in Apples Script Editor:

a) Remove the "--" to un-comment.
b) Copy in your Terminal command where it says "Your Command" and/or "your Next Command".
c) Adjust your delay between commands (a bit of trial and error will be needed here).
	
	-- do script "Your Command" in front window
	
	-- delay 2
	
	-- do script "Your Next Command" in front window

Now run the App and away you go!

This is my first Git Project so all comments and feedback would be much appriciated.
