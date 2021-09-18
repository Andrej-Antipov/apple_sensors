
Only test with my Macbook air with M1. Please check your mac's `ioreg -lfx` output to make changes in `temp_sensor.m` if needed.


Usage

Download applet. Execute terminal command xattr -rc /applet path/ (drag'n'drop the applet on terminal window after that command) and lounch the applet. First start may get ask you to install additional support tool from apple for pyton 3 support. After its download and install M1 sensors will work as expected. Tested up to Big Sur 11.6
To exit press ctrl+c in the prog terminal window. The window will closed after cancel execution automatically. 

## References

For **better names** (e.g. what is `PMU TP3w` ?) for the sensors, please refer to

https://github.com/exelban/stats/blob/master/Modules/Sensors/values.swift

https://github.com/acidanthera/VirtualSMC/blob/master/Docs/SMCSensorKeys.txt

Here is a similar code in swift for getting sensor values using IOKit (for intel Mac)

https://github.com/exelban/stats/blob/master/Modules/Sensors/values.swift

For intel Mac, an easier way to get sensor infomation:

`sudo powermetrics`


## Demo: screen shot 
- screen shot
![screen shot](https://github.com/Andrej-Antipov/apple_sensors/blob/master/demo/33.png)
<!---

![screen shot](screen_shot.png)
--->



