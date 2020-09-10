# Mesh Networking with LoRa

## Project Intro

https://github.com/AllenGlan/new-england-route-zero

This time around, we'll be building a LoRa mesh network that provides coverage to the greater New Haven area. This task is essentially akin to designing and deploying our own cellular service that one can connect to anywhere in New Haven. If time permits, we can also develop applications for the network, including live audio/video transmission (making voice/video calls), secure messaging, geolocation (making a local positioning system) and much more! Here's a brief intro to LoRa:

### What is LoRa?

- LoRa (Long Range) is a communication & networking protocol
- Developed by LoRa Alliance, popularized in 2018
- Operates at FCC unlicensed 915 MHz in the US

### Core Features and Applications

LoRa has a couple of awesome features that we'll take advantage of this semester:

- Long range, low power consumption, low bandwidth
- Low cost and highly resilient
- Widely applicable in Internet-of-Things (IoT) devices
- Used for infrastructure-less networking (e.g., tracking wildlife)
- Enables infrastructure-level security and control
- Possible to establish low cost, high coverage mesh networks
- Ranging and geolocation potentials

## Objectives

The objectives are intentionally a bit vague and without timestamps. We'll figure out a more concrete version once we get a team together. The project will operate under a **hybrid model** that's suitable for both on-campus and remote members.

Please note that this project will be **relatively difficult and intensive** -- it is not for the faint of heart. But it will also be extremely rewarding and has the potential to fulfill a great cause. If you are passionate about distributed systems engineering and committed to learning, this will be the project for you!

**Prior experience with programming, hardware, networking, information theory, etc. will be of great help, but they are by no means prerequisites.** This is an opportunity for us to learn together!

Overall, there are two big parts of the project, and we will decide which to concentrate on based on the background of our team.

### Objective: Physical Layer

1. Design and construct LoRa terminals
	1. Leverage existing platforms such as Raspberry Pi and other SBCs
	2. Iterate on form factor and energy consumption
	3. Design portable solutions with battery and solar panels
	4. Design and fabricate water- and dust- resistant enclosures

2. Deploy self-sufficient terminals in New Haven
	1. Continuous monitor liveness and performance of nodes
	2. Validate self sufficiency and availability

3. Establish preliminary mesh network
	1. Develop protocols for integration of new nodes

### Objective: Network Layer and Beyond

1. Construct a fault-tolerant, robust network
2. Design routing nodes towards other WANs (e.g., Starlink)
3. Implement secure messaging protocols (e.g., Signal protocol)
4. Experiment on ranging and geolocation methods
5. Develop low-latency, high-fidelity audio/video codecs
6. Curate a platform for real-world testing of distributed algorithms
7. Formulate production-environment solutions for general applications
