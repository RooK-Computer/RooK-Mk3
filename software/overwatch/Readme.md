# Overwatch setup

You find here the needed configuration files for overwatch and the overwatch binary for RetroPie (armv7l).
To build the dep file you have to extract the .tar.gz file as root and run (under retropie is best)

`dpkg-deb --build overwatch`

in this directory.
The files are put in a .tar.gz file as the permissions are important and working on those files as non-root always messes up permissions.
Maybe we will build a dev environment where the user is root, then we might add those files directly.

## installing

Somehow get overwatch.deb onto your retropie setup (cartridge, onboard storage,... you will find a way).
Gain terminal access. That is possible by simply using the "quit emulationstation" option. You will be dumped into a logged in terminal session.
When you exit that, emulationstation will be restarted.
Connect a Keyboard, and navigate to where you put the .deb file.

Then run

`sudo dpkg -i overwatch.deb`

That should be it. All three keys should work now.

