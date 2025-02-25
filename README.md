# Open Hardware in the Loop Community

![Discord](https://img.shields.io/discord/1232626958932643841?style=plastic&logo=discord&label=Join%20our%20Discord)


Welcome to the Open Hardware in the loop (HiL) community 👋

We are a forum for software engineers, hardware hackers, QA teams, and embedded board manufacturers to come together and have conversations about Hardware in the Loop (HiL or HitL) systems. We welcome folks to present their systems in the forum, ask questions about HiL CI/CD pipelines, and document our knowledge to help everyone along the path to building an effective system.

## What is Hardware in the Loop?

Hardware in the Loop is a system that enables the testing of software applications on real hardware. 

- It's a feedback loop for teams to test software changes in a controlled environment before deploying applications to production (embedded IoT, fleet management use-cases)
- It's a QA pipeline to test if your software works well with new hardware under synthetic, stress testing, or real-life workloads (Factory floor, compliance testing use-cases)
- It's a way to test systems end-to-end by controlling external factors (power, network, environment) and creating diverse test scenarios to catch mission-critical failures. 

Hardware in the loop helps ensure everything is functioning as intended in an environment that makes your teams deploy as fast as possible and as confidently as possible. 

## Who are we?

The community was started in 2024 by fellow HiL system builders who have been: 

- tired of rebuilding the wheel constantly.
- Tired of having no standardized documentation on how to start thinking about Hardware in the Loop. 
- Tired of proprietary, expensive hardware automation jigs built for limited use cases. 

The community is meant to be a way to pool our collective expertise, document our past learnings, and present them as a guide for anyone looking to build their own HiL system.

## Where can you find us?

You are welcome to join our community chat on [Discord](https://discord.gg/vt6GYwesb3) even if you want to learn about Hardware in the Loop. Please introduce yourself and tell us about your work and interests.

We are looking to spread awareness about the community, talk to more people, and discuss HiL at conferences and meetups. Please share the website as much as you can!

### Community meetings

Hardware in the Loop community
Tuesday, February 25 · 2:00 – 3:00pm  and every two weeks.
Time zone: Europe/Paris
Google Meet joining info
Video call link: https://meet.google.com/bkm-sams-qpd
Or dial: ‪(FR) +33 1 73 08 31 91‬ PIN: ‪141 268 879 5765‬#
More phone numbers: https://tel.meet/bkm-sams-qpd?pin=1412688795765
Or join via SIP: sip:1412688795765@gmeet.redhat.com 

Please feel free to ping Miguel Angel Ajo on discord, or majopela@redhat.com to get a calendar invite.

## Presentations and Talks

This section provides a list of presentations and talks related to hardware in the loop.

### 2025

* **[A Cloud Native Workflow for Hardware-in-the-Loop Software Development](https://kccnceu2025.sched.com/event/1txFD?iframe=no)** April 3rd - KubeCon, London - Miguel Angel Ajo, Red Hat

### 2024

* **[Jumpstarter: Enabling Open hardware in the loop](https://pretalx.com/devconf-cz-2024/talk/7W9CSQ/)** Jun 13th Devconf.cz - Miguel Ángel Ajo Pelayo, Red Hat

* **[Unveiling the Test Champions: Comparing Testing Automation Systems for Embedded Environments](https://www.youtube.com/watch?v=IVgzn5wVgL0)** Apr EOSS24 - Paweł Wieczorek, Collabora

* **[Quickly Test Your Kernel with GitLab CI](https://www.youtube.com/watch?v=AUHUONWYTPw)** Apr OSSNA2024 - Helen Koike, Collabora

* **[Testing rotation sensor drivers with LEGO robots and other adventures in the Linux IIO subsystem](https://www.youtube.com/watch?v=5gja2Fd6iy4)** Apr OSSNA2024 - David Lechner, BayLibre

* **[Quality Beyond Kernelci.Org in Upstream Linux for TI SoCs](https://www.youtube.com/watch?v=XqXW-rZHdA0)** Apr OSSNA2024 - Barry Sheraw & Nishanth Menon - Texas Instruments


* **[Jumpstarter: Open Hardware In The Loop for everybody](https://fosdem.org/2024/schedule/event/fosdem-2024-3070-jumpstarter-open-hardware-in-the-loop-for-everybody/)** Feb FOSDEM - Miguel Ángel Ajo & Ricardo Noriega,  Red Hat

* **[Testing in a Box: Streamlining Embedded Systems Testing](https://fosdem.org/2024/schedule/event/fosdem-2024-3196-testing-in-a-box-streamlining-embedded-systems-testing/)** Feb FOSDEM -  Mudit Sharma, Will Salmon, CodeThink


## Software

* **[Jumpstarter](https://jumpstarter.dev) is a hardware-in-the-loop (HIL) software designed to facilitate
  automated testing, CI workflows, and firmware development for hardware labs. It provides a scalable and
  secure environment for managing test hardware, integrating with enterprise authentication and
  Kubernetes-based infrastructure. Jumpstarter enables remote control, power management, and
  automated interaction with test devices, making it a powerful tool for embedded development
  and hardware validation. Inspired by Labgrid, with a Cloud Native design, and Apache 2 Licensing.
  
* **[Labgrid](https://labgrid.readthedocs.io)  is an embedded hardware testing and automation framework
  designed for remote control and interaction with test hardware. It provides a unified API to manage
  various test lab setups, enabling reproducible and scalable testing workflows. Labgrid is particularly
  useful for embedded development, offering features like power cycling, serial access, and
  network-controlled interactions. GPL Licensed.


## Hardware

This section provides a list of hardware components, systems, and shops, that can help
you build hardware in the loop testing rigs

### Testing rigs
* **[Autokit](https://github.com/balena-io-hardware/autokit-info-doc)**: Balena Autokit is the
    documentation for a testing rig that can be used to test embedded devices: enables power
    switching, wifi testing, HDMI capture and storage switching via SD-MUX.

* **[DUTLink](https://github.com/jumpstarter-dev/dutlink-board)**: DUTLink is part of the
    Jumpstarter project it's a board to connect your SOM to a testing server, enables:
    power switching, power metering, USB3 SuperSpeed storage switching, UART, and basic
    GPIOs.

* **[Linux Test automation controller](https://www.linux-automation.com/en/products/lxa-tac.html)**:
    A great labgrid exporter. Enables: Power control and metering, GPIOs, UART, CAN,
    IOBUS, USB, and Ethernet access. It does not provide storage switching directly
    but can be used in combination with SD-MUX. Supports POE.

### Shops
* **[Numato Labs](https://numato.com/shop/)** Provides a comprehensive range of USB/Network
    controlled modules and accessories with CE certification.

