# VNF and NS descriptors proposed by ETSI NFV ISG in 2016-10

### Content
- [Example Network Service and corresponding descriptors](#example-network-service-and-corresponding-descriptors)
- [Simplified diagram](#simplified-diagram)
- [UML modeling](#uml-modeling)
- [References](#references)

### Example Network Service and corresponding descriptors
We have identified an example Network Services, composed by 3 VNFs. The NS is represented in the following figure.

![NS example 01](https://github.com/superfluidity/RFB/blob/master/ETSI16/images/NS-example-01-ETSI16.png)

We have provided example descriptors for the NS and VNFs, compliant with the specifications in [1] and [2].

### Simplified diagram
We have analysed the relationships among the model components and produced the following diagram.

![ETSI16-model-simplified-diagram](https://github.com/superfluidity/RFB/blob/master/ETSI16/images/ETSI16-overall-simplified-diagram.png)

### UML modeling

We have started representing the model components with UML class diagrams, see [here](https://github.com/superfluidity/RFB/tree/master/ETSI16/UML). We have produced standard UML files that can be visualized using the [Papyrus UML tool](https://eclipse.org/papyrus/). Actually, we have used [Plantuml](http://plantuml.com/) syntax to input the UML diagram and then a converter written in python to generate files in standard UML notation.

### References
[1] ETSI NFV ISG, “Network Functions Virtualisation (NFV); VNF Packaging Specification”, ETSI GS NFV-IFA 011 V2.1.1 (2016-10) [pdf link](http://www.etsi.org/deliver/etsi_gs/NFV-IFA/001_099/011/02.01.01_60/gs_NFV-IFA011v020101p.pdf)  
[2] ETSI NFV ISG, “Network Functions Virtualisation (NFV); Network Service Templates Specification”, ETSI GS NFV-IFA 014 V2.1.1 (2016-10) [pdf link](http://www.etsi.org/deliver/etsi_gs/NFV-IFA/001_099/014/02.01.01_60/gs_NFV-IFA014v020101p.pdf)
