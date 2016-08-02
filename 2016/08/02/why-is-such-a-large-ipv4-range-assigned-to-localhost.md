---

title: Why is such a large IPv4 range assigned to localhost?
link: http://networkengineering.stackexchange.com/questions/2840/why-is-such-a-large-ipv4-range-assigned-to-localhost
tags: IP, network, local

---

127/8 is the loopback function, every datagram will loop back inside the host, it should not appear anywhere else.
In 1986, the internet was completely classful and nobody gave thought about giving a class A network to the loopback address.
