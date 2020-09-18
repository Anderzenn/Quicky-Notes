# Quicky Notes
Quicky Notes is a simple, quick and easy to use program for writing down notes.
The project was started back in mid 2018 by me (Mads Rosengren Andersen), and was made using Electron, but actually started out in Visual Studio as a WPF app.
Quicky Notes was started because I felt like the regular text editor was just not pleasing to look at and I wanted something that was still simple, yet useful. 
So I came up with the idea of creating a notes program that you could open up, write something in, and then just close down and when opened again everything would be right where you left it. During the early days of Quicky Notes, it was known as "qNotes" and it worked. You could open and save text files, and it was simple and clean. However, I felt limited by WPF, and wanted the program to be available on both Mac and Windows. So I decided to switch to Electron after a lot of thinking. Electron was both new and familiar. So mid 2019, Quicky Notes was born and in 2020 the first version to the public was released, version 0.2.1.


# Quicky Notes Changelog (v.0.2.1)
 - Changed name from qNotes to Quicky Notes
 - Completely rewrote program in Electron
 - Added Autosave (Localstorage)
 - Added Local Saving (Localstorage)
 - Added Cross-platform support. (Currently Mac OSX & Windows)
 - Added splash screen
 - Added character count
 - Added word count
 - Added line count
 - Added current line count
 - Added tooltip for text stat counters
 - Added Header and Sub-Header overview
 - Added clickable headers and sub-headers (can be made with # and ##)
 - Added resize ability to overview
 - Added visibility toggle for overview
 - Added Discord rich presence
 
 ## Known Issues
  - Tooltip sometimes flashes when hovering over counters
  - Closing the application to the dock on Mac and opening it again causes it to completely relaunch
  - If two headers or subheaders exist with the exact same name, the text will go to the first result
  
  ## TODO
   - Fix known issues
   - Make Discord Rich Presence togglable
   - Settings
   - Light mode
   - Custom Saving & Loading
   - Drag n Drop loading
