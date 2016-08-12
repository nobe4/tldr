---

title: How can I analyze a potentially harmful binary safely?
link: http://reverseengineering.stackexchange.com/questions/23/how-can-i-analyze-a-potentially-harmful-binary-safely
tags: security, VM, malware

---

User-mode sandbox: emulate a black box.
Virtualisation: emulate memory and hardware but run on host's processor.
Dynamic translation: Translate each instruction to host's instruction and execute it.
Full emulation: emulate the processor and the instructions.
Static analysis: Do not execute the code, or use an emulated debugger.
