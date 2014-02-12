Phonegap Android Production Ready Boilerplate
=============================================

This is a boilerplate for Creating Android Apps with Cordova 3.1.0.
<br>
Basically this was created for one of my personal project.
If you are a JavaScript/Web developer and kinda feel like you don't know the "J" of Java then you might just be able to generate an .apk file from the official docs of Phonegap. But if you want to submit it to Play Store then you need a Production Ready .apk file which I find pretty hard to generate by following the official Phonegap docs.

In this repo you will find a "almost" Production Ready Corodova Project for Eclipse.
<br>
Follow the steps below:
(I assume that your are on a Windows machine)
<br>
1 - You just need to add your "Web Dev" type files in the "assets/www" folder. (Don't delete anything and add "cordova.js"/ related js file in your "index.html")
<br>
2 - Setup ANT (You just need to download ANT and setup "ANT_HOME" & "ant/bin")
<br>
3 - Setup JDK (Download and setup "JAVA_HOME" & "jdk/bin")
<br>
4 - Setup ADT (Download and Setup the "tools" & "platform-tools" in your PATH environmental variable)
<br>
5 - Import the Project from Eclipse, Right Click on project -> Android Tools -> Fix Project Properties, then Clean.
<br>
With this you will be able to generate a .apk file which can be installed to your Device/Emulator.
<br>
6 - To sign your .apk  Right click on project -> Android Tools -> Export Signed Application Package.
<br>
7 - Just follow the onscreen instructions to generate "key" file (If you don't have one). This is dead easy, just put your details and some passwords.
<br>
Following all these steps, you should be end up with a Production Ready .apk file. If you are getting any error while trying to compile/run the App on AVD please try installing PhoneGap via NPM and then try again. 
<br>
*Pro Info: Step 7 will generate the compiled, signed, aligned, and ready for distribution .apk file. You can directly submit that to the Play Store. No need to zipalign bla bla it after exporting.
<br>
Enjoy!


License
=======
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details. To read more about the GNU Lesser General Public License that belongs to this program, see http://www.gnu.org/licenses/
