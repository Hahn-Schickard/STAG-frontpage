---
layout: page
title: Features
permalink: /features/
---
  
## Application Features:
1. **Simple application**  
The most important goal of STAG is its ease of use. The sensor developer himself should have no or as little effort as possible to connect a sensor to STAG and thus also to the IT world. A sensor should register with STAG and then automatically become visible to the IT world via the interface and thus accessible to other systems.  
2. **Independent of specific sensor systems**  
In order to make the applicability as high as possible and to keep the configuration effort as low as possible, STAG is developed in such a way that it is independent of concrete sensor characteristics. STAG can support different sensor systems with different measurement values and properties "out-of-the-box". This is achieved through the use of a sensor description, such as is already provided for in the [Lightweight Machine to Machine Standard (LwM2M)](https://omaspecworks.org/what-is-oma-specworks/iot/lightweight-m2m-lwm2m/){:target="_blank"}  or in the [Bluetooth GATT profiles  (Generic Attribute Profile)](https://www.bluetooth.com/de/specifications/specs/){:target="_blank"}. 
3. **Modular and expandable design**  
The architecture of STAG has been defined in such a way that STAG itself can be extended by various technology or protocol adapters. This modular structure makes it possible to add further interfaces to STAG at a later date or to switch variably between different protocols.  
4. **Common understanding and data model of sensor systems and sensor information**  
In order to  translate and transforme between different protocols and standards, a uniform definition of sensor information is necessary. This central data model is used as a common core of the different technology and protocol adapters and significantly facilitates the translation between different technologies, as only one mapping into the central data model is required per technology or protocol and not n mappings into n supported technologies.   
5. **Central translation technology for mapping between different data models**  
The heart of STAG is the aforementioned common central data model. As with humans, the heart is of no use without the veins that ensure the flow of blood to and from the heart. In STAG, translation technology takes on the role of the veins. It makes it possible for the data coming from the sensors to be mapped into the common data model and then forwarded from there to the data adapters, which then make the data available to the higher systems in the IT world via specific interfaces.  

## Technical features:
1. **Completely written in C/C++**  
   STAG is completely written in C/C++ with cmake as build tool and conan for dependancy and library management.  
2. **Platform and compiler independent**  
   STAG can be compiled an run on Linux as well as Windows and Mac. Additional, it is compatible with X86 and ARM architecture and thus can be executed on small embedded Linux device like Raspberry as well as on virtualized backend servers.  
3. **Integrates the open62541 OPC UA server**  
   The implementation of the OPC UA adapter bases on the open source OPC UA SDK [open62541](https://open62541.org/){:target="_blank"}.  
4. **Includes an integrarted LwM2M server**  
   STAG includes a dedicated LwM2M server integrated in a technology adapter to handle LwM2M sensor requests.
