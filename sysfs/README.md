# Experiments with Low Voltage Labs Traffic Lights on Raspberry Pi in C

## sysfs Method

Example showing how to use the Low Voltage Labs Traffic Lights with the sysfs method of accessing the GPIO pins.

### Attach Traffic Lights

Attach the traffic lights so that they are connected to GPIO 9, 10, 11.

### Compile and Run Code

```
$ git clone https://github.com/simonprickett/cpitrafficlights.git
$ cd cpitrafficlights/sysfs
$ make
$ ./trafficlights
```
