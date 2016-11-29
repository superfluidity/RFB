# VNF and NS descriptors proposed by ETSI NFV ISG in 2016-10

### Content
- [Example Network Service and corresponding descriptors](#example-network-service-and-corresponding-descriptors)
- [Web GUI for editing VNFDs and NSDs](#web-gui-for-editing-vnfds-and-nsds)
- [Simplified diagram of the Information Model](#simplified-diagram-of-the-information-model)
- [UML modeling](#uml-modeling)
- [References](#references)

### Example Network Service and corresponding descriptors
We have identified an example Network Services, composed by 3 VNFs. The NS is represented in the following figure.

![NS example 01](https://github.com/superfluidity/RFB/blob/master/ETSI16/images/NS-example-01-ETSI16.png)

We have provided example descriptors for the NS and VNFs represented in the figure above, compliant with the specifications in [1] and [2].

### Web GUI for editing VNFDs and NSDs
<br /> 
<br /> 
See live demo [here](http://rdcl-demo.netgroup.uniroma2.it/)

<br /> 
<br /> 
<br /> 

### Simplified diagram of the Information Model
We have analysed the relationships among the model components and produced the following diagram.

![ETSI16-model-simplified-diagram](https://github.com/superfluidity/RFB/blob/master/ETSI16/images/ETSI16-overall-simplified-diagram.png)

### UML modeling

To better understand and analyze the model defined by [1] and [2], we have started representing its components with UML class diagrams, see [here](https://github.com/superfluidity/RFB/tree/master/ETSI16/UML).

To this aim, our starting point are UML class diagrams described in [PlantUML](http://plantuml.com/class-diagram), a language to describe (and generate) UML diagrams. The advantage of a description in the PlantUML language is that it is compact and human readable and thus easy to compare with the reference documents. The [ETSI16-plantuml.uml](https://github.com/superfluidity/RFB/tree/master/ETSI16/UML/ETSI16-plantuml.uml) file contains the UML class diagram in PlantUML format of the elements described in [1] and [2]. The image below has been generated from this file using the PlantUML executable.

![ETSI16-plantuml.png](https://github.com/superfluidity/RFB/blob/master/ETSI16/UML/ETSI16-plantuml.png)

On the other side, using [Papyrus](https://eclipse.org/papyrus/), a modeling environment hosted by the Eclipse foundation, has several other advantages, as it is based on standards and allows better control over the graphical layout of the diagrams.

Thus, to combine the readability of the PlantUML class diagrams and at the same time be able to use the features provided by Papyrus, we have developed a converter from the PlantUML class diagram textual format to the Papyrus class diagram standard XMI format. This tool is provided in the [plantuml2papyrus](https://github.com/superfluidity/RFB/tree/master/ETSI16/UML/plantuml2papyrus/) directory.  The [ETSI16-papyrus.uml](https://github.com/superfluidity/RFB/tree/master/ETSI16/UML/ETSI16-papyrus.uml) and [ETSI16-papyrus.notation](https://github.com/superfluidity/RFB/tree/master/ETSI16/UML/ETSI16-papyrus.notation) files contain the UML class diagram in Papyrus XMI format obtained through conversion of the [ETSI16-plantuml.uml](https://github.com/superfluidity/RFB/tree/master/ETSI16/UML/ETSI16-plantuml.uml) file. 

### References
[1] ETSI NFV ISG, “Network Functions Virtualisation (NFV); VNF Packaging Specification”, ETSI GS NFV-IFA 011 V2.1.1 (2016-10) [pdf link](http://www.etsi.org/deliver/etsi_gs/NFV-IFA/001_099/011/02.01.01_60/gs_NFV-IFA011v020101p.pdf)  
[2] ETSI NFV ISG, “Network Functions Virtualisation (NFV); Network Service Templates Specification”, ETSI GS NFV-IFA 014 V2.1.1 (2016-10) [pdf link](http://www.etsi.org/deliver/etsi_gs/NFV-IFA/001_099/014/02.01.01_60/gs_NFV-IFA014v020101p.pdf)
