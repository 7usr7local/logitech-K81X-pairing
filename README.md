Logitech K81X keyboard Linux Bluetooth pairing
==============================================

This is 7usr7local's version of "Logitech K810 keyboard Linux Bluetooth pairing" by pedrogaudencio,
recognizing the K811 as well.

Solution for a persistent connection
------------------------------------

(Deleted pedrogaudencio's instructions as it pairs out of the box nowadays)

Key configuration
-----------------

`sudo apt-get install build-essential`

`./build.sh`

`sudo ./k81X_conf -d /dev/hidraw<X> -f on`

You will have to replace <X> by the hid number that was assigned to your keyboard. Of course there are more clever ways, but just work through the numbers brute force starting with hidraw0. The script is clever enough to detect if it’s not the K810/K811.
