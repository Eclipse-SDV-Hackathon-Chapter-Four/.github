# Eclipse SDV Hackathon Chapter Four

06 October 2026 – 8 October 2026

BUILD openly. CONNECT communities. DELIVER together

You don't have to be a rocket scientist to help build the next Rocketmobile! We start with code first! Join the Eclipse SDV Hackathon Challenge to hack the software defined car of the future!

## Register here:
[Event Page](https://www.eclipse-foundation.events/event/sdv-hackathon-chapter-four/summary)

## Pitching Instructions
tbd

## Hackathon Guide Book
[Hackathon Guide Book](./Eclipse_Hackathon_Guide_Book.pdf)

## Hackathon Evaluation Forms (aka Scorecards)
[Hackathon Evaluation Forms](./Eclipse_SDV_Hackathon_2026_EvaluationForms.pdf)

## Hackathon Pitching Session
[SDV Hackathon 2026_Pitching Session](./SDV%20Hackathon%202026_Pitching%20Session.pdf)

## Blogposts and News
[Announcing the Eclipse SDV Hackathon Chapter 4: May the fourth be with you!](https://eclipsesdv.org/blogs/announcing-the-eclipse-sdv-hackathon-chapter-4-may-the-fourth-be-with-you/)
More to come...

## About the challenges

The Eclipse Software Defined Vehicle Hackathon is back - this year in one location: Friedrichshafen, Germany.

Participants, coaches, and partners will come together at See Campus Friedrichshafen for an intensive hands-on hackathon focused on open collaboration, real-world SDV use cases, and practical prototyping.

The main purpose of the SDV Hackathon is to bring together automotive software enthusiasts to experiment with Eclipse SDV projects, build exciting new features, explore emerging technologies, and - most importantly - have fun while coding.

This year’s hackathon will follow a partly new concept, which will be announced soon. Interested participants and partners should stay tuned for more details on the updated format, challenge topics, and how to get involved.

Over the course of two and a half days, participants will be supported by experienced Hack Coaches from the automotive and technology ecosystem. The coaches will help teams turn ideas into working prototypes based on open source automotive software projects, with a strong focus on collaboration across the Eclipse SDV community.

## Track 1 Innovation Track Challenges:

### Challenge "Doctor Whodunit!!"  

Something in the vehicle just failed — whodunit? Travel your system's timeline: inject faults you've seen before or expect in the future, and let the evidence tell the story. 

Build a safety evidence factory around the Battery Thermal Guardian — an EV thermal-runaway early-warning service. Regulations require occupants be warned minutes before a battery thermal event turns dangerous, so a stale or stuck cell-temperature signal silently disarms the entire warning chain. Run the Guardian on an AutoSD-based runtime, supervised by Ankaios, exchanging heartbeat, fault, and mitigation events over uProtocol, with diagnostic truth exposed through OpenSOVD. openDuT replays repeatable fault campaigns at three levels — delayed or duplicated messages, stuck or implausible VSS signals, even device-level sensor dropout — while your evidence collector links hazard → safety goal → injected fault → detection → mitigation → verdict for every test, packaged as a reusable SDV Blueprint.

_Every fault leaves evidence. Solve the case._

**Prerequisites:** Basic Rust or Python, Linux/containers, pub/sub messaging

**Projects:** openDuT, uProtocol, Ankaios, OpenSOVD, KUKSA, AutoSD, S-CORE, SDV Blueprints

**HackCoaches:** Naci Dai, Leonardo Rossetti, Frank Märkle, Ramachandran Chakravadhanula, Svante Karlsson, Shriram Gobichettipalayam Ramalingam

### Challenge "Hack to the Future"

Your DeLorean is waiting. Build an SDV feature that jumps between hardware and virtual setups: develop it against simulated endpoints, then move it onto embedded controllers and real cars without changing your service code. uProtocol keeps services portable across platforms and transports, and openDuT rewires the testbench on the fly, so switching setups means no replugging of cables.

The reference scenario is the Guardian Loop, a child presence detection feature of the kind Euro NCAP now rewards in its safety ratings: a child left in a parked car is at risk as the cabin heats up, so a sensor detects occupancy and rising temperature, a decision service on an AutoSD-built HPC image evaluates the risk, and an OpenBSW-based zonal controller responds by opening a window, running the fan, or sounding the alarm. As a stretch goal, drive the on-site Flux Capacitor and Time Circuits displays from your services.

_Where we're going, we don't need cables!_

**Prerequisites:** Basic knowledge of Rust and C++, Linux/containers, pub/sub messaging

**Projects:** uProtocol, openDuT, OpenBSW, AutoSD

**HackCoaches:** Frank Märkle, Christian Schilling, Leonardo Rossetti, Akshai Murukakumar, Svante Karlsson, Shriram Gobichettipalayam Ramalingam 

## Who can join

This hackathon is open to all. Whether you are a student just starting with coding or you are an experienced software developer and interested in hacking the challenges of automotive software, you are welcome to join the quest!

Make sure to attend and get hands-on experience on our open source tools and projects.

If you are still not acquainted with open source and SDV, it will be useful to check out our current [SDV Projects](https://sdv.eclipse.org/projects/) and get to know what you can expect.
