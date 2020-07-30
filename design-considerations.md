---
description: Design considerations and what to look out for given the IREC 2020 guidelines
---

# Design Constraints & Considerations

**Haloship Category**  
10,000 ft \(3048 m\) AGL apogee with commercial-off-the-shelf \(COTS\) solid or hybrid rocket propulsion system

### Motor Considerations

* [ ] Must not exceed total impulse of 9,208 pound-seconds \(40,960 Newton-seconds\)
* [ ] All ground-started propulsion system ignition circuits/sequences shall not be "armed" until all personnel are at least 50 ft \(15 m\) away from the launch vehicle
* [ ] A propulsion system is considered armed if only one action \(eg an ignition signal\) must occur for the propellant\(s\) to ignite. The "arming action" is usually something \(ie a switch in series\) that enables an ignition signal to ignite the propellant\(s\)

### Electronics Considerations

#### Safety

* [ ] All energetics shall be safed until the rocket is in the launch position, at which point they may be "armed". An energetic device is considered safed when two separate events are necessary to release the energy. An energetic device is considered armed when only one event is necessary to release the energy.
* [ ] All energetic device arming features shall be externally accessible/controllable. This does not preclude the limited use of access panels which may be secured for flight while the vehicle is in the launch position.
* [ ] All energetic device arming features shall be located on the airframe such that any inadvertent energy release by these devices will not impact personnel arming them. For example, the arming key switch for an energetic device used to deploy a hatch panel shall not be located at the same airframe clocking position as the hatch panel deployed by that charge. 

#### Altitude Logging

* [ ] Must carry a COTS barometric pressure altimeter, either standalone or part of COTS flight computer
* [ ] If using telemetry, it must report using the official altitude reporting 

#### Recovery

* [ ] The initial deployment event shall occur at or near apogee, stabilize the vehicle's attitude \(ie prevent or eliminate ballistic re-entry\), and reduce its descent rate to roughly between 75 and 150 ft/s \[23-46 m/s\]\)
* [ ] The main deployment event shall occur at an altitude no higher than 1,500 ft \(457 m\) AGL and reduce the vehicle's descent rate sufficiently to prevent excessive damage upon impact with ground \(ie less than 30 ft/s \[9 m/s\)\]\).

#### Redundancy

* [ ] Launch vehicles shall implement redundant recovery system electronics, including sensors/flight computers and "electric initiators"—assuring initiation by a backup system, with a separate power supply \(ie battery\), if the primary system fails.
* [ ] At least one redundant recovery system electronics subsystem shall implement a COTS flight computer \(eg StratoLogger, G-Wiz, Raven, Parrot, AIM, EasyMini, TeleMetrum, RRC3, etc...\). This flight computer may also serve as the official altitude logging system.
* [ ] All recovery system mechanisms shall be successfully \(without significant anomalies\) tested prior to the IREC, either by flight testing, or through one or more ground tests of key subsystems. In the case of such ground tests, sensor electronics will be functionally included in the demonstration by simulating the environmental conditions under which their deployment function is triggered. A link to all video of the testing cycle\(s\) should be included in the final report.

#### Cable Management

* [ ] All safety critical wiring shall implement a cable management solution \(e.g. wire ties, wiring, harnesses, cable raceways\). All safety critical wiring/cable connections shall be sufficiently secure as to prevent de-mating due to expected launch loads. This will be evaluated by a "tug test", in which the connection is gently but firmly "tugged" by hand to verify it is unlikely to break free in flight.

#### GPS

### Recovery Considerations

* [ ] The recovery system shall implement adequate protection \(eg fire resistant material, pistons, baffles etc...\) to prevent hot ejection gases \(if implemented\) from causing burn damage
* [ ] The recovery system rigging \(eg parachute lines, risers, shock chords, etc...\) shall implement appropriately rated swivel links at connections to relieve twist/torsion as the specific design demands
* [ ] Parachutes should be highly dissimilar from one another visually \(primary colors differing\)

