In promotion of manned spaceflight returning to US soil on 27 May 2020, SpaceX and NASA released a docking simulator of the SpaceX's Dragon 2 capsule docking with the ISS. 

This process will be automated in the actual launch but the astronauts can always take manual control in case of emergencies.

[Dragon-ISS docking sim](https://iss-sim.spacex.com/)

I wrote a JavaScript to dock automatically. 

The script works by first zeroing out the angles with a basic PID controller (technically PD since the I term wasn't needed). When the angular errors are sufficiently small, the script starts to correct the position using the same method.

In order to run the script yourself, just paste it in the development console of your browser (press Ctrl+Shift+J for Chrome).

Have fun! :P
