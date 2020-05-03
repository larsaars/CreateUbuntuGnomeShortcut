# CreateUbuntuShortcut
#Create ubuntu shortcuts easily without much efford over terminal for gnome environment

This can be executed directly from the GNOME desktop directory or be inserted to bin directory.<br><br>

#To insert this bash script into the bin dir, follow these steps:<br>
Since aptitude is needed, if you don't have it already installed, install it via<br>
`sudo apt-get install aptitude`<br>
Navigate to the Desktop via cd command in terminal<br>
Create a new file:<br>
`touch createshortcut.run`<br>
Open the file and copy the file into there.<br>
Then move file to /usr/bin with:<br>
`sudo mv createshortcut.run /usr/bin/createshortcut`<br>
Make the file executable:<br>
`sudo chmod +x /usr/bin/createshortcut`<br><br>

Everything is done so far!<br>
To create shortcuts in .desktop format you just have to execute `createshortcut` when navigated in the desktop folder and follow the steps!
