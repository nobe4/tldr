---

title: Knuth–Morris–Pratt algorithm
link: https://en.wikipedia.org/wiki/Knuth%E2%80%93Morris%E2%80%93Pratt_algorithm
tags: string, algorithm

---

Finding a string inside another can have poor performance for edge cases:
e.g. find AAB in AAAAAAAAB
KMP use previous match during a new run, jumping through matched string knowed to be unmatchable.
e.g. ABC in AAABC, on first fail will jump to the 3rd A.

