# 🖧 Day 2 | Ethernet Cables, Communication Flow, and Auto MDI-X

## 🎯 Objective
Understand why network connections work by exploring the difference between straight-through and crossover cables, and how devices handle transmit and receive signaling.

---

## 🧱 Lab Focus
This lab focused on the physical side of communication and how proper cable selection affects connectivity between devices.

Key areas explored:
- Straight-through cables
- Crossover cables
- Transmit and receive behavior
- Auto MDI-X functionality

---

## 🔌 Cable Behavior

### Straight-Through Cable
Straight-through cables keep the wiring the same from one end to the other.

Used for connections between different device types such as:
- PC → Switch
- Switch → Router

These connections work because the internal wiring of the devices is already complementary.

### 📸 Straight-Through Connection Example
![Straight Through Cable](https://github.com/Pelumi-Johnson/Ethernet-Cables-Communication-Flow-and-Auto-MDI-X/blob/main/Screenshot%202026-03-26%20013623.png)

---

### Crossover Cable
Crossover cables swap the transmit and receive wires.

Used for connections between similar device types such as:
- PC → PC
- Switch → Switch
- Router → Router

This allows one device’s transmit pins to align with the other device’s receive pins.

### 📸 Crossover Connection Example
![Crossover Cable](crossover.png)

---

## 🧠 Core Concept
Each network device uses pins to send and receive data.

For communication to succeed:
- one side must transmit
- the other side must receive

If transmit and receive are not aligned properly, communication will fail unless the device can adjust internally.

---

## 🔄 Auto MDI-X
A key part of this lab was learning about Auto MDI-X.

Auto MDI-X allows a device to:
- detect the cable type being used
- automatically adjust transmit and receive signaling
- compensate for mismatched cable connections

### 📸 Auto MDI-X Behavior / Working Connection
![Auto MDIX](auto-mdix.png)

---

## 📡 Key Takeaway
This lab shifted the focus from simply asking whether the connection works to understanding why it works.

Correct cable design matters because:
- physical connections are the foundation of network communication
- transmit and receive alignment determines whether devices can exchange data
- Auto MDI-X adds flexibility, but does not replace understanding

---

## 📝 What I Learned
- Straight-through cables are typically used between different device types
- Crossover cables are typically used between similar device types
- Communication depends on matching transmit and receive paths
- Auto MDI-X can automatically correct mismatched cable usage
- Understanding the design behind communication is more important than memorizing outcomes

---

## ✅ Outcome
Developed a stronger understanding of physical layer communication and how cable design supports successful data exchange between devices.

This lab reinforced the importance of understanding not just whether a network works, but why it works.
