# RFB - Reusable Functional Blocks
Reusable Functional Blocks for Network Function Virtualization

Network Function Virtualization (NFV) is emerging a new architectural concept for the design and implementation of communication networks. In order to fully exploit the NFV potential, we need to re-think the way of designing and modelling the telecommunication services.

We aim at supporting a granular and dynamic decomposition of services into Virtualized Network Functions and of Virtualized Network Functions into smaller components.

We start from the modelling of Virtualized Network Functions (VNFs) and of their composition, as provided by ETSI NFV working group and by the OpenMano project. In particular the OpenMano project has provided a template for describing Virtualized Network Functions (VNFD - VNF Descriptor) and a template to describe Network Services (NSD - Network Service Descriptor). A Virtualized Network Function can be split in VNF Components (VNFCs), which can be described in the VNFD files.

We generalize the VNF and VNFC concepts into the concept of Resusable Functional Blocks and we provide a template to describe RFBs (RFBD - RFB Descriptor). RFBDs are described using YAML, exactly as OpenMano's VNFDs. 

