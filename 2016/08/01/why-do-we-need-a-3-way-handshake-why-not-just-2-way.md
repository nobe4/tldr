---

title: Why do we need a 3-way handshake? Why not just 2-way?
link: http://networkengineering.stackexchange.com/questions/24068/why-do-we-need-a-3-way-handshake-why-not-just-2-way
tags: network, security, synchronisation

---

The SYN numbers needs to be ACKnowledged by both sides to enable effective "secure" communication.
Bob ---SYN---> Alice
    <-ACK-SYN-
    ---ACK--->
