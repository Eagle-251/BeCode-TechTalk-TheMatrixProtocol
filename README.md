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
- _Secure_
- _Persistent_
  - Participating Servers all replicate the history of a given Matrix Room, no one server "_owns_" the room.

---

<!-- _class: lead -->

# Matrix is... Decentralised

Users join a homeserver on a particular domain. All homeservers can federate with each other.

![bg right 60%](img/dencentalised.png)

---

![bg contain](img/Matrix-Diagram.png)

---

![bg contain](img/Matrix-Diagram2.png)

---

<!-- _class: lead -->

# Matrix is... Secure

Messages are by default encrypted using Olm, based on Signal's Double Ratchet Algorithm

---

![bg contain](img/double-ratchet.png)

---

<!-- backgroundColor: #2a3339 -->

![bg contain 70%](img/decrypted.png)

---

<!-- backgroundColor: #2a3339 -->

![bg contain 100%](img/encrypted.png)

---

<!-- backgroundColor: white -->
<!-- _class: lead -->

# Matrix is ... Persistent

Participating Servers all replicate the history of a given Matrix Room, no one server "_owns_" the room.

---

Room: `#example-room:example.com`

Client:

`POST /_matrix/client/v3/rooms/{roomId}/invite`

![bg left 90%](img/Pre-join.png)

---

Client:

`POST /_matrix/client/v3/rooms/{roomId}/invite`

Server:

`PUT /_matrix/federation/v1/send_join/{roomId}/{eventId}`

![bg left 90%](img/Matrix-Diagram2.png)

---

# Matrix is... Interoperable

The Appservice API allows dedicated applications to act as bridges to other platform. <br> For example:

- WhatsApp
- Signal
- Slack
- Discord

---

![bg contain](img/Matrix-Diagram3.png)

---

<!-- _class: lead -->

# Why Matrix?

---

<!-- _class: lead -->

# Time for A Demo!
