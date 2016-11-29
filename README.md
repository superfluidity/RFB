# RFB - Reusable Functional Blocks and RDCL - RFB Description and Composition Languages

Network Function Virtualization (NFV) is emerging as new architectural concept for the design and implementation of communication networks. In order to fully exploit the NFV potential, we need to re-think the way of designing and modelling the telecommunication services. We aim at supporting a granular and dynamic decomposition of services into Virtualized Network Functions (VNFs) and of Virtualized Network Functions into smaller components.

We start from the modelling of Virtualized Network Functions (VNFs) and of their composition, as defined by ETSI NFV working group [1]. We generalize the VNF concept into the concept of Reusable Functional Blocks (RFB).

We analyse and compare different description models for VNFs and their composition:
 - the first model proposed by ETSI in [4], see folder [ETSI14](https://github.com/superfluidity/RFB/tree/master/ETSI14) 
 - the model proposed by the OpenMano project [2] and included in the OSM [3] release 1, see folder [OSMr1](https://github.com/superfluidity/RFB/tree/master/OSMr1) 
 - the updated model proposed by ETSI in [5] [6], see folder [ETSI16](https://github.com/superfluidity/RFB/tree/master/ETSI16)

#### [ETSI14](https://github.com/superfluidity/RFB/tree/master/ETSI14)
- the set of descriptors related to a NS example
- a simplified class diagram for the overall model

#### [OSMr1 (OpenMano)](https://github.com/superfluidity/RFB/tree/master/OSMr1)
- the set of descriptors related to a NS example

#### [ETSI16](https://github.com/superfluidity/RFB/tree/master/ETSI16)
- the set of descriptors related to a NS example
- a simplified class diagram for the overall model
- a web GUI for editing and graphically displaying the descriptors ([see live demo](http://rdcl-demo.netgroup.uniroma2.it))
- UML models (and a tool to input UML models using a simplified notation)

## References
[1] ETSI NFV ISG, “Network Functions Virtualisation (NFV); Architectural Framework”, ETSI GS NFV 002 V1.2.1 (2014-12)  
[2] OpenMano project - https://github.com/nfvlabs/openmano  
[3] OSM - Open Source MANO https://osm.etsi.org/  
[4] ETSI NFV ISG, “Network Functions Virtualisation (NFV); Management and Orchestration”, ETSI GS NFV-MAN 001 V1.1.1 (2014-12)  
[5] ETSI NFV ISG, “Network Functions Virtualisation (NFV); VNF Packaging Specification”, ETSI GS NFV-IFA 011 V2.1.1 (2016-10)  
[6] ETSI NFV ISG, “Network Functions Virtualisation (NFV); Network Service Templates Specification”, ETSI GS NFV-IFA 014 V2.1.1 (2016-10)  

 

### Tools and hints

Sublime Syntax Highlighting for Yang : https://github.com/apackeer/sublime-yang-syntax

