#  Delta Drive Classic Control System

##  Overview

This project demonstrates controlling a motor using a Delta VFD with Forward, Reverse, and Stop operations via a selector switch, along with safety integration using an external fault sensor.

---

##  Control Logic

### Selector Switch (3 Positions)

* Left Position → Forward
* Middle Position → Stop
* Right Position → Reverse

---

##  Timing Configuration

* Acceleration Time: 3 seconds
* Deceleration Time: 3 seconds

---

##  Safety Feature

A Normally Closed (NC) sensor is used as an External Fault:

* Normal Condition → System runs normally
* Sensor Triggered → Drive enters fault (EF) and motor stops immediately

---

##  Drive Configuration

* Run Command Source: External Terminals
* Frequency Source: Configurable
* External Fault: Enabled
* Acc/Dec Time: 3 seconds

---

##  Demo

A video demonstration is included showing:

* Forward/Reverse operation
* Stop behavior
* External fault triggering
[Watch The Video](video.mp4)
---


## 📚 References

* Delta VFD Manual (Official Documentation)

---

## 🛠️ Tools Used

* Delta VFD
* Selector Switch
* NC Push Button (Sensor)
* Industrial Control Wiring
