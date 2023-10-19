# 1.3 - Understand Security Concepts Relevant to Cloud Computing

## Cryptography and Key Management

Some considerations.
- Where are the keys stored?
- Who generates and manages the keys?
- Should a key management service be used?

## Identity and Access Control

There are multiple types of access control.
- Physical access
- User access
- Privilege access
- Service access

## Data and Media Sanitization

Types of sanitization techniques include the following.
- Overwriting
- Cryptographic erasure

## Netowrk Security

- Network security groups
- Zero trust network (formal definition can be found in NIST SP 800-207)
- Ingress and egress monitoring

## Virtualization Security

Hypervisor type 1 is generally faster and more secure but requires special skills to set up and maintain.
Hypervisor type 2 run on top of a host operating system like Windows or macOS. These are easier to set up, typically requiring only the skills needed to install the virtualization application.

Virtual machine escape

[https://en.wikipedia.org/wiki/Virtual_machine_escape](https://en.wikipedia.org/wiki/Virtual_machine_escape)

> In computer security, virtual machine escape is the process of a program breaking out of the virtual machine on which it is running and interacting with the host operating system.

Other considerations
- Container security
- Ephemeral computing
- Serverless technology

## Common Threats

The Cloud Security Alliance (CSA) publishes a list of common cloud threats known as the Egregious Eleven.

## Security Hygiene

- Patching
- Baseline
