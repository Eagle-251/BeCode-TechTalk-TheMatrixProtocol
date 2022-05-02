---
theme: gaia
backgroundColor: white
marp: true
---

<!-- _class: lead -->

# The Matrix Protocol

An open network for secure, decentralized communication

![bg right 75%](https://raw.githubusercontent.com/matrix-org/matrix.org/master/content/matrix%20logo.svg)

---

# What is it?

- An open source project that governs the publication of an open specification of the Matrix communication standard.

- This consists of:
  - Client - Server API
  - Server - Server API
  - Application Service API
  - Reference Implementation of Servers and Clients

---

### Matrix is..

- _Decentralised_
  - Users have a homeserver on a particular domain, and all homeservers can federate with each other
- _Secure_
  - Messages are by default encrypted using Olm, based on Signal's Double Ratchet Algorithm
- _Persistent_
  - Participating Servers all replicate the history of a given Matrix Room, no one server "_owns_" the room.

---

<!-- _class: lead -->

# Matrix Network Topology

---

![bg contain](images/Matrix-Diagram.png)

---

![bg contain](images/Matrix-Diagram2.png)

---

![bg contain](images/Matrix-Diagram3.png)
