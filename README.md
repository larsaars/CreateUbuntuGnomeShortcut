# CreateUbuntuShortcut
Create ubuntu shortcuts easily without much efford over terminal for gnome environment

This can be executed directly from the GNOME desktop directory or be inserted to bin directory.

To insert this bash script into the bin dir, follow these steps:
Since aptitude is needed, if you don't have it already installed, install it via
sudo apt-get install aptitude
Navigate to the Desktop via cd command in terminal
Create a new file:
touch createshortcut.run
Open the file and copy the file into there.
Then move file to /usr/bin with:
sudo mv createshortcut.run /usr/bin/createshortcut
Make the file executable:
sudo chmod +x /usr/bin/createshortcut

Everything is done so far!
To create shortcuts in .desktop format you just have to execute createshortcut when navigated in the desktop folder and follow the steps!
