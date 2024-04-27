# Tunneling
## Introduction
In real world, it's a way to cross those paths which couldn't be normally crossed. Similarly, in networking, tunnels are a method for transporting data across a network using protocols that are not supported by that network. Tunneling works by `encapsulating` packets: wrapping packets inside of other packets. (Packets are small pieces of data that can be re-assembled at their destination into a larger file.). It can also set up efficient and secure connections between networks, enable the usage of unsupported network protocols, and in some cases allow users to bypass `firewalls`.
## How Does Packet Encapsulation Works?
An encapsulated packet is essentially a packet inside another packet. In an encapsulated packet, the header and payload of the first packet goes inside the payload section of the surrounding packet. The original packet itself becomes the payload.
Headers contains the information about the protocols and the source and destination addresses.
Original Packet contains the protocols of a network, Where the wrapper packet contains the protocols of the another network by which the original packet should be transferred. 
![Packet Encapsulation](https://github.com/REZ-OAN/tunneling-poc/blob/main/images/packet_encapsulaton.png)
