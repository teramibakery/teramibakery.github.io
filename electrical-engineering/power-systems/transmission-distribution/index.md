---
layout: default
title: Transmission & Distribution
---

# Transmission & Distribution (T&D)

## General idea
At a high level:
- **Transmission:** bulk power transfer over long distances at **high voltage**. For a given real power transfer, increasing voltage allows current to be lower (since, in simple form, \(P \approx VI\), and for three-phase systems \(P = \sqrt{3}\,V_{LL} I \cos\phi\)). Lower current reduces resistive losses and allows smaller conductor sizes. Typical transmission voltage levels include **132 kV, 230 kV, 345 kV, 500 kV**, and **765 kV**.
- **Distribution:** local delivery of electrical power from substations to **homes and businesses** at **medium and low voltages**, over shorter distances. Distribution systems operate at voltages **below transmission levels**, commonly **11 kV, 22 kV, 33 kV, and 66 kV**, and carry lower power compared to the transmission network.

## Why high voltage is used
For a given power transfer, increasing voltage reduces current. Lower current reduces:
- **I²R losses** in lines and cables  
- required conductor size (and associated capital cost)  
- voltage drop over distance  

## Key components
Common T&D elements include:
- **Generators** and step-up transformers (to transmission voltage)
- **Transmission lines** (overhead or underground)
- **Substations** (switching, protection, voltage transformation)
- **Step-down transformers** (to distribution voltage)
- **Distribution feeders**, **laterals**, and **service transformers**
- **Switchgear**, **breakers**, **reclosers**, and **relays**
- **Capacitor banks** and **reactors** (voltage and reactive-power control)

## Transmission vs distribution modeling (practical differences)
- **Transmission analysis** typically focuses on power flow, system stability, contingency analysis (N-1), and reactive-power / voltage control.
- **Distribution analysis** typically focuses on voltage drop, feeder loading, protection coordination, reliability, and high penetration of DER (solar PV, EV charging, energy storage).

## System control and reliability
- **Frequency control:** System frequency remains constant (typically **60 Hz** in North America) when **generation and load are balanced**. Imbalances result in frequency deviations, which are corrected through primary, secondary, and tertiary control actions.
- **Voltage control:** Maintained locally using reactive-power resources such as generators, capacitor banks, reactors, and transformer tap changers.
- **Reliability standards:** In North America, system planning and operation are governed by **:contentReference[oaicite:0]{index=0} (NERC)**, which defines mandatory reliability standards for frequency, voltage, and system operating limits.
- **N-1 criterion:** The power system must be able to withstand the loss of **any single system element** (e.g., a line, transformer, or generator) **without loss of system integrity or widespread service interruption**.

## Reference
- https://en.wikipedia.org/wiki/Electric_power_transmission  
- https://en.wikipedia.org/wiki/Electric_power_distribution  
- https://www.nerc.com/AboutNERC/Pages/default.aspx
