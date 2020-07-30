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
* [ ] Launch vehicles shall have sufficient velocity upon "departing the launch rail" to assure they will follow predictable flight paths. In lieu of detailed analysis, a rail departure velocity of at least 100 ft/s \(30.5 m/s\) is generally acceptable. Alternatively, the team may use detailed analysis to prove stability is achieved at a lower rail departure velocity \(greater than 50 ft/s \[15.24 m/s\]\) either theoretically \(eg computer simulation\) or empirically \(eg flight testing\).
* [ ] Launch vehicles shall remain "stable" for the entire ascent. Stable is defined as maintaining a static margin of at least 1.5 to 2 body calibers, regardless of CG movement due to depleting consumables and shifting center of pressure \(CP\) location due to wave drag effects \(which may become significant as low as 0.5 M\). Not falling below 2 body calibers will be considered nominal, while falling below 1.5 body calibers will be considered a loss of stability.

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

#### Control Systems

* [ ] Launch vehicle active flight control systems shall be optionally implemented strictly for pitch and/or roll stability augmentation, or for aerodynamic "braking". Under no circumstances will a launch vehicle entered in the IREC be actively guided towards a designated spatial target
* [ ] Launch vehicles implementing active flight controls shall be naturally stable without these controls being implemented \(eg the launch vehicle may be flown with the control actuator system \[CAS\] – including any control surfaces – either removed or rendered inert and mechanically locked, without becoming unstable during ascent\)
* [ ] Control actuator systems \(CAS\) shall mechanically lock in a neutral state whenever either an abort signal is received for any reason, primary system power is lost, or the launch vehicle's attitude exceeds 30° from its launch elevation. Any one of these conditions being met will trigger the fail safe, neutral system state.
* [ ] CAS shall mechanically lock in a neutral state until either the mission’s boost phase has ended \(ie all propulsive stages have ceased producing thrust\), the launch vehicle has crossed the point of maximum aerodynamic pressure \(aka max Q\) in its trajectory, or the launch vehicle has reached an altitude of 20,000 ft \(6,096 m\) AGL. Any one of these conditions being met will permit the active system state.

#### Airframe

* [ ] Launch vehicles shall be adequately vented to prevent unintended internal pressures developed during flight from causing either damage to the airframe or any other unplanned configuration changes. Typically, a 1/8 to 3/16 inch \(0.318 to 0.476 cm\) hole is drilled in the booster section just behind the nosecone or payload shoulder area, and through the hull or bulkhead of any similarly isolated compartment/bay.
* [ ] All load bearing eyebolts shall be of the closed-eye, forged type – NOT of the open eye, bent wire type. Furthermore, all load bearing eyebolts and U-Bolts shall be steel \(other than stainless\)
* [ ] Airframe joints which implement "coupling tubes" should be designed such that the coupling tube extends no less than one body caliber on either side of the joint – measured from the separation plane. Regardless of implementation \(eg RADAX or other join types\) airframe joints will be "stiff" \(ie prevent bending\).
* [ ] Launch lugs \(aka rail guides\) should implement "hard points" for mechanical attachment to the launch vehicle airframe. These hardened/reinforced areas on the vehicle airframe, such as a block of wood installed on the airframe interior surface where each launch lug attaches, will assist in mitigating lug "tear outs" during operations. At the IREC, competition officials will require teams to lift their launch vehicles by the rail guides and/or demonstrate that the bottom guide can hold the vehicle's weight when vertical before permitting them to proceed with launch preparations.
* [ ] The aft most launch lug shall support the launch vehicle's fully loaded launch weight while vertical.
* [ ] The team's Team ID \(a number assigned by ESRA prior to the IREC\), project name, and academic affiliation\(s\) shall be clearly identified on the launch vehicle airframe, nosecone and other locations where possible. The Team ID especially, will be prominently displayed \(preferably visible on all four quadrants of the vehicle, as well as fore and aft\), assisting competition officials to positively identify the project hardware with its respective team throughout the IREC.

#### GPS

* [ ] If your team has a GPS Tracker which utilizes HAM frequencies, the students configuring/using the tracking system ​MUST​ be licensed appropriately as a HAM operator \(Technician, General or Extra\).
* [ ] All teams will be assigned a frequency prior to arriving in Las Cruces. Failure to utilize thisassigned frequency will cause significant delays in approving your project for flight and maycause your rocket to be grounded.

### Recovery Considerations

* [ ] The recovery system shall implement adequate protection \(eg fire resistant material, pistons, baffles etc...\) to prevent hot ejection gases \(if implemented\) from causing burn damage
* [ ] The recovery system rigging \(eg parachute lines, risers, shock chords, etc...\) shall implement appropriately rated swivel links at connections to relieve twist/torsion as the specific design demands
* [ ] Parachutes should be highly dissimilar from one another visually \(primary colors differing\)

