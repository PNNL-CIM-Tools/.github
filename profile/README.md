# PNNL Common Information Library Toolbox

This organization contains tools and resources for working with the Common Information Model (CIM) as well as links to other available tools

## PNNL Developed Tools

### CIMantic Graphs

Python library for generating in-memory labeled property graphs of CIM objects for creating, editing, and parsing node-breaker / bus-branch transmission and distribution models.

https://github.com/PNNL-CIM-Tools/CIM-Graph

CIM Profiles: CIM 15-18, custom profiles can be added easily
Language: Python
OS: Windows, Linux, MacOS


### CIMHub

A tool set for translating electric power distribution system models between various formats, using the IEC Standard 61970/61968 CIM as the "Hub". Support is currently being added for bus-branch transmission models and electro-magnetic transient solvers.

https://github.com/GRIDAPPSD/CIMHub

CIM Profiles: CIM 100: CIMHub profile and GMDM profile
Language: Java, Python
OS: Windows, Linux, MacOS

### UUDEX

A proposed replacement for Inter-Control Center Communications Protocol (ICCP) using CIM classes and attributes

https://github.com/pnnl/UUDEX

Language: Python


### CIM Training & Tutorials:

Enabling Data Exchange using CIM: https://www.pnnl.gov/main/publications/external/technical_reports/PNNL-32679.pdf

Demystifying CIM Part 1 Slide Deck 

Demystifying CIM Part 2 Slide Deck


## Other Free / Open-Source Tools

This list is not meant to be comprehensive or be interpreted as a recommendation or endorsement of any other tools. It is merely provided as a useful list of possibly complementary tools that may be used as part of a larger tool chain.

### CIM-Tool

GUI tool can be used to create a new CIM profile from a CIM .eap information model file and then export that CIM profile to a data profile.

https://github.com/CIMug-org/CIMTool

CIM Profiles: Any
Language:Java
OS: Windows

### CIM-Compare

Command-line tool can be used to compare different CIM profiles and discover changes to classes and attributes in the information model

https://github.com/CIMug-org/cim-compare

CIM Profiles: Any two (for comparison)
Language: Java
OS: Windows

### CIMpy

Python library for import and export of CGMES / CIM IEC-61970 files in the XML/RDF format

https://github.com/sogno-platform/cimpy

CIM Profiles: ENTSO-E / CGMES (IEC-61970 only, -61968 and -62325 classes not supported)
Language: Python
OS: Any

### PyCIM

(Deprecated) Python library for reading / writing CIM XML files

https://github.com/rwl/PyCIM

CIM Profiles: CIM14-15
Language: Python
OS: Any

### CIM++

C++ library for reading/deserializing CIM XML files

https://github.com/sogno-platform/libcimpp

CIM Profiles: CIM16-17
Language: C++
OS: Any

### CIMGen

Data profile creation tool that creates data classes from a CIM profile

https://github.com/sogno-platform/cimgen

CIM Profiles: Any
Language: Python, Java, C++
OS: Any

### Pintura

Basic web plotter for drawing CIM models, limited to classes `ACLineSegment`, `EnergyConsumer`, `PowerTransformer`, `SynchronousMachine`, `TopologicalNode`, and `Terminal`

https://github.com/sogno-platform/pintura
https://sogno.energy/pintura/

CIM Profiles: CIM16
Language: JavaScript
OS: Web-based

### InterPSS OpenCIM

GUI for opening and parsing CIM models. Free community version available with 10,000 object limit.

https://sites.google.com/a/interpss.com/interpss/opencim

CIM Profiles: CIM10, CIM14
Language: Java
OS: Windows

### CIM-2-Modelica

Conversion tool to convert CIM models for use in the Modelica modeling language

https://github.com/ALSETLab/cim2modelica

CIM Profiles: CGMES
Language: Java

### CIMverter

Another conversion tool to the Modelica modeling language

https://github.com/cim-iec/cimverter

CIM Profiles: CGMES
Language: C++


## Commercial CIM Tools

This list is not meant to be comprehensive or be interpreted as a recommendation or endorsement of any other tools or vendor solution. It is merely provided as a useful list of possibly complementary tools that may be used as part of a larger tool chain.

### CIMSpy (Power Info LLC)

GUI-based tool for geospatial rendering and editing of CIM models

https://powerinfo.us/CIMSpy.html


### CIM Adapter (SISCO)

Adapter for loading CIM power system models into an AVEVA/OSIsoft PI Historian

https://sisconet.com/our-products/cim-adapter/


### CIMphony (Open Grid Systems)

GUI-based tool for geospatial rendering and editing of CIM models


### ArcGIS CIM Adapter (Similix)

Converter from ESRI ArcGIS format to CIM XML.

https://www.esri.com/partners/similix-aps-a2T390000003EEREA2/similix-cim-adaptor--a2df2000003eouAAAQ


### PSS-ODMS (Siemens)

CIM-based transmission planning and analysis suite with similar capabilities and GUI as PSSE. Model exchange supported between PSSE and ENTSO-E CGMES profile.

https://www.siemens.com/global/en/products/energy/grid-software/planning/pss-software/pss-odms.html






