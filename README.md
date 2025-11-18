# cloudBIM Working Group  
*A cloud-native, operational layer for connected, interoperable buildings.*

## Overview
cloudBIM defines the cloud-first, API-driven BIM layer that enables buildings to operate as **living systems**, not static files.  
It extends OpenBIM into the **IBB Data Stack**, providing the persistent spatial and asset context required for:

- live device connections  
- semantic models (RDF, 223P, Brick, REC, Haystack)  
- Digital Building Profiles  
- interoperable system-of-systems workflows  
- automated work orders and operational intelligence  
- lifecycle and TXO/TCO analytics  

Traditional BIM is file-based, design-centric, and human-operated.  
**cloudBIM is operational, connected, and machine-readable.**

It is the digital backbone that allows owners, engineers, integrators, and systems to share a common, continuously updated context.

---

## Why cloudBIM?

### **1. File-Based BIM ≠ Operational Reality**
Revit/IFC files are essential design artifacts, but they:
- lack persistent IDs  
- rarely contain semantic relationships  
- cannot keep pace with live sensors, APIs, or building automation  

File-based BIM is static.  
Buildings are not.

### **2. Buildings Need a Cloud-Native Context Layer**
cloudBIM provides:
- spatial hierarchy (rooms → zones → domains)  
- asset-level identities (ICIDs / IFC GeoIDs)  
- semantic relationships (equipment ↔ systems ↔ controls)  
- live data bindings  
- cross-system logic  

This is the “operational BIM” layer required to build a real digital twin.

---

## Relationship to OpenBIM, IFC, and COBie
cloudBIM builds on top of existing OpenBIM foundations and is designed to **complement—not replace—** established industry standards such as:

- **IFC** (Industry Foundation Classes)  
- **COBie** (Construction-Operations Building Information Exchange)

These standards remain essential for structured design documentation and asset data delivery.

cloudBIM focuses on the **cloud-native, operational layer** needed for:
- live, streaming data  
- persistent identity  
- API-driven integration  
- semantic models  
- building automation context  
- everyday operational workflows  

The goal is full compatibility with current and future buildingSMART developments, ensuring that cloudBIM remains **neutral, interoperable, and respectful of existing standards bodies.**

---

## Scope of this Repository
This repository will publish:

### **Digital Building Profiles**  
Portable descriptions of how a building’s spaces, assets, systems, semantics, and live data connect.

### **Process Documentation**  
Step-by-step workflows for transforming a building from:  
**Static BIM → cloudBIM → Living Digital Twin.**

### **Integration Patterns**  
Reusable, neutral templates describing how sensors, systems, assets, and semantics connect within cloudBIM.  
These patterns provide clarity while leaving space for alignment with C4SBF, IBB, and other emerging standards.

### **Semantic + Data Artifacts**
- RDF/TTL models  
- Graph models  
- JSON examples  
- API mappings  
- Naming and identity conventions  

### **Operational BIM Patterns**
- cloudBIM schema  
- zone/domain hierarchy (223P)  
- persistent identities (ICIDs, IFC GeoIDs)  
- asset → endpoint mapping  

---

## Background Reading
For a deeper explanation of the motivation behind cloudBIM, see:  

**From Static BIM to Living Systems**  
AutomatedBuildings (November 2025)  
https://www.automatedbuildings.com/2025/11/from-static-bim-to-living-systems/

This article introduces the concepts behind cloudBIM and explains why a cloud-native operational BIM layer is essential for building intelligence.

---

## Current Status
This repo is in the **initial structuring phase** as the working group defines the foundational documentation and patterns.  
Content from reference projects (including the PAE Living Building) will be added as Digital Building Profiles and sample artifacts.

---

## Governance  
Chairperson: **Kimon Onuma**  
Governing Board/Committee:  
Kimon Onuma, Rick Justis, Tristan de Frondeville, Kennady Gales, Tracy Markie, Anto Budiardjo

---

## Contributing  
Please refer to **Contributing.md** and **Code_of_Conduct.md** for full guidelines.

The working group welcomes input from owners, integrators, engineers, and the broader C4SBF community.
