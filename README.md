# BTDA Project - BYOB
The centralized storage and management of grades and other assessments of an academic nature increases the risk of data loss due to natural disasters (fires, water damage) and targeted hacking attacks. Furthermore it can lack transparency of why certain grades were given and from whom. In addition to these fundamental issues, the centralized approach unnecessarily complicates the process of applying for a university since one always needs to first gather all his/her assessments in order to prove them to the other university or e.g. scholarship foundations.
By using a decentralized approach like blockchains we can leverage the properties of these in order to achieve a much more secure, reliable and joint solution.

This project aims to build a simple blockchain using [Substrate](https://substrate.io/). The blockchain will be used to store and manage the data of a simple decentralized application (dApp) that allows users (academic institutions) to store and verify the data of their students (e.g. certificates, diplomas, etc.).

# Core-functionalities

- Grades and in general all assessments will be stored and managed decentralized in a zero trust environment.
- Every student and other academic subjects are able to view their assessments or those which they gave to others.
- It will be very reliable since no single central server manages the data but a federated system of participating nodes.
- Transparency will be increased since no centralized process obfuscates how and from whom an assessment was given

# Main Goals

- The security property of blockchains will ensure that no hacking attacks endanger the sensible and valuable data for the individuals.
- Availability will also be increased and not restricted by e.g. maintaining activities (e.g. Qispos down 22-06)

## Substrate Node Compilation

Some known issues with the compilation of the Substrate node are:

- missing protocol buffers compiler: `sudo apt install  protobuf-compiler`
- missing clang: `sudo apt install clang`
