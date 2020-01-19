# **_Atlas thing framework_**
This repository holds the latest development regarding Atlas thing framework. The framework is composed of the following components:
- [IoT Device Description Language](https://github.com/AEEldin/Atlas-thing-framework#1-iot-device-description-language-iot-ddl)
- [Atlas Thing Architecture](https://github.com/AEEldin/Atlas-thing-framework#2-atlas-thing-architecture)
- [Inter-Thing Relationship Framework](https://github.com/AEEldin/Atlas-thing-framework#3-inter-thing-relationship-framework)
- [Runtime Interactive Development Environment](https://github.com/AEEldin/Atlas-thing-framework#4-runtime-interactive-development-environment-ride)


## 1) IoT Device Description Language (IoT-DDL): 
XML-based human- and machine-readable configuration scheme to describe a thing in IoT in terms of inner components, identity, capabilities, resources, attachments and services. The IoT-DDL also describes the knowledge (social bonds and relationships) injected or acquired by the thing, as well as the different interactions that engage the thing with cloud platforms, edges, users (e.g., end-user, developer) and space-mates (nearby things or remote ones). Such configuration schemes are created by the thing vendor or owner and this then gets uploaded to the thing to enable the thing to self-discover its own power and engage with the surrounding IoT ecosystem. 

### Read more about it in the following paper:
> - Khaled, Ahmed E., Abdelsalam Helal, Wyatt Lindquist, and Choonhwa Lee. "IoT-DDL–device description language for the “T” in IoT." IEEE Access 6 (2018): 24048-24063. [Link: https://ieeexplore.ieee.org/abstract/document/8334820]
> - **_Also check the "IoT-DDL builder" to build an IoT-DDL file for Atlas thing._**


## 2) Atlas Thing Architecture: 
Based on the specifications of the IoT-DDL, Atlas thing architecture enables the automatic integration of the devices into the ecosystem and allows the programmer to discover and combine available services to create applications for the smart space. The Atlas thing architecture is a set of lightweight operating layers that initially aim at turning a thing into a smart stand-alone and self-dependable unit, getting smarter, more social, and more interactive with time. Atlas Thing Architecture extends the original Atlas architecture to enable the thing to self-discover itself and announce its presence, services and capabilities to other participants in the smart space. Besides capturing new engagement and programming opportunities, such knowledge exchange increases a thing’s awareness of the surrounding ecosystem and enables discovering and building new social relationships. Along with the provisioning and management capabilities offered by the Atlas Thing Architecture to the space users and developers, the Atlas Thing Architecture supports both thing-to-thing and thing-to-cloud communication paradigms through the support of a set of communication protocols and enabling communication interoperability through protocol translators. The Atlas Thing Architecture also enables, through the IoT-DDL, the thing to dynamically define and generate its own services and formulates appropriate programmable interfaces through which the thing mates can interact and trigger the offered services.

### Read more about it in the following papers:
> - Khaled, Ahmed E., Abdelsalam Helal, Wyatt Lindquist, and Choonhwa Lee. "IoT-DDL–device description language for the “T” in IoT." IEEE Access 6 (2018): 24048-24063. [Link: https://ieeexplore.ieee.org/abstract/document/8334820]
> - Khaled, Ahmed E., and Sumi Helal. "Interoperable communication framework for bridging RESTful and topic-based communication in IoT." Future Generation Computer Systems 92 (2019): 628-643. [Link: https://eprints.lancs.ac.uk/id/eprint/89459/1/1_s2.0_S0167739X17317387_main.pdf]
> - **_Also check the "Tweet-Specifications" to view the components of the different messages Atlas thing can communicate with._**


## 3) Inter-Thing Relationship Framework:
The inter-thing relationships programming framework utilizes  Atlas Thing Architecture as well as the thing IoT-DDL specifications to build a distributed programming ecosystem for the social IoT. The framework broadens the social IoT thing-level relationships (that link the things according to their identification attributes) and utilizes a set of concrete service-level relationships (that logically and functionally tie the offered services to build scenarios and applications). We believe this can empower developers to program a much wider class of meaningful IoT applications. The framework introduces service (abstraction of the function offered by a thing), relationship (abstraction of how different services are linked together) and recipe (abstraction of how different services and relationships build up a segment of an app) as the primitives for the Atlas IoT application. The framework also defines a set of operators that functionally define how the primitives are wired. 

### Read more about this framework in the following papers:
> - Khaled, Ahmed E., and Sumi Helal. "A framework for inter-thing relationships for programming the social IoT." In 2018 IEEE 4th World Forum on Internet of Things (WF-IoT), pp. 670-675. IEEE, 2018.
> - Khaled, Ahmed E., Wyatt Lindquist, and Abdelsalam Sumi Helal. "Service-relationship programming framework for the social iot." Open Journal of Internet Of Things (OJIOT) 4, no. 1 (2018): 35-53. [Link: https://www.ronpub.com/ojiot/OJIOT_2018v4i1n04_Khaled.html]


## 4) Runtime Interactive Development Environment (RIDE):
The Atlas RIDE, an interactive development environment for the mobile user to glimpse and program their smart spaces. The RIDE extends the inter-thing relationships programming framework and targets the smart-phone users with no programming experience to help them master their smart spaces and to build applications with a few clicks. The developer, through the RIDE, can listen to the smart space to capture the available services and relationships, establish applications, and set preferences for functionalities to guide the inference of new applications and engagement opportunities. The RIDE also accepts the description for application from the developers and generates mobile applications that run independently from the RIDE and communicate back with the things for the execution of the application. 

### Read more about this framework in the following papers:
> - Helal, Sumi, Ahmed E. Khaled, and Venkata Gutta. "Atlas Thing Architecture: Enabling Mobile Apps as Things in the IoT." In Proceedings of the 23rd Annual International Conference on Mobile Computing and Networking, pp. 480-482. 2017.
> - Khaled, Ahmed, Wyatt Lindquist, and Sumi Helal. "DIY Health IoT Apps." In Proceedings of the 16th ACM Conference on Embedded Networked Sensor Systems, pp. 406-407. ACM, 2018.
