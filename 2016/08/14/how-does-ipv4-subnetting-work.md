---

title: How does IPv4 Subnetting Work?
link: http://serverfault.com/questions/49765/how-does-ipv4-subnetting-work
tags: network, IPv4, subnet

---

Masks `/X` is the number of bits kept in the IP to determine the network ID.
Wildcard mask is the opposite.

Old classes (A,B, and C) defined Nx8 consecutive bits set to 1.

A router check the mask for each packet and match the packet to a subdomain.
Longest mask are checked firsts and the check stop as soon as a result is found.

Routing tables can "pass" the packet to a known router that can handle the subnetwork.
Default mask handle the "default" routing case.

Splitting a network can use additional bits in the mask to create subnetworks.
Using the next power of 2 (minus 2 - all 0's and all 1's - ) give the available space.
