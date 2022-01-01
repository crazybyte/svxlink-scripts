I would like to share some of my SvxLink scripts (I have plenty more :-) ).

svx-build 	Downloads all the dependencies plus the source and finally builds and installs SvxLink.

svx-update 	Roughly the same, but does a git pull and rebuilds SvxLink.

svx-start 	Starts the SvxLink service. Edit and un-comment the lines for svxreflector, if desired.

svx-stop 	Stops the service(s).

svx-restart 	Restarts the service(s).

svx-check 	Displays the running services.

svx 		Starts SvxLink on the console (stops the service before).

These scripts are verified on Raspberry OS Buster as well as on Debian 11 (bullseye).

Copy them to /usr/local/bin and make them executable.