---

title: What are the differences between a digital signature, a MAC and a hash?
link: http://crypto.stackexchange.com/questions/5646/what-are-the-differences-between-a-digital-signature-a-mac-and-a-hash
tags: security, message, exchange, key

---

Hash: Protect integrity, allowing the message to be sent insecurely, e.g. for big files.
Message Authentication Code: Are keyed hashes, preserving also the identity (with a secret key).
Digital signature: Can only be [en/de]crypted with the proper key, verifying the non-repudiation principle.
