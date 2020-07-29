---
description: Documentation for the OpenRocket Software-in-the-loop extension
---

# Software-in-the-loop

Directory

1. [Overview]()
2. [Working with socat]()
3. [Compiling/Usage]()

### Overview

The OpenRocket extension is meant to provide the simulation environment for your flight software. While OpenRocket provides several useful events and values, this extension makes use of the following simple outputs:

* acceleration

\(near-future\)

* velocity
* world coordinates
* rotational coordinates

These values are provided over a serial port \(virtual ports included\). Commands can be sent back to the simulation to carry out events \(chute deployment, airbrake deployment, fin movement\). As a result, your flight software controls the actuation of the rocket in the OpenRocket simulation, leading to software-in-the-loop testing.

## Usage

Coming soon!

## Development

### Working with `socat`

1. Install

```text
sudo apt install socat
```

1. Start virtual ports

```text
sudo socat PTY,link=/dev/ttyUSB98 PTY,link=/dev/ttyUSB99

```

1. Elevate user privilege to operate ports

```text
sudo chmod a+rw /dev/ttyUSB98 && sudo chmod a+rw /dev/ttyUSB99
```

### Compilation and Usage

1. Change directory to `orksim`

```text
cd ork-extension
```

1. Compile program

```text
ant
```

1. Copy the `.jar` file to OpenRocket plug-in

```text
cp ./haloship.jar ~/.openrocket/Plugins/haloship.jar
```

