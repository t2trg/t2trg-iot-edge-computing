---
stand_alone: true
ipr: trust200902
docname: draft-hong-t2trg-iot-edge-computing-04
cat: info
pi:
  toc: 'yes'
  symrefs: 'yes'
  iprnotified: 'yes'
  strict: 'yes'
  compact: 'yes'
  sortrefs: 'yes'
  colonspace: 'yes'
  rfcedstyle: 'no'
  tocdepth: '4'
title: IoT Edge Challenges and Functions
abbrev: IoT Edge Computing
area: T2TRG
author:

- ins: J. Hong
  name: Jungha Hong
  org: ETRI
  street: '218 Gajeong-ro, Yuseung-Gu'
  city: Daejeon
  code: '34129'
  country: Korea
  email: jhong@etri.re.kr

- ins: Y-G. Hong
  name: Yong-Geun Hong
  org: ETRI
  street: '218 Gajeong-ro, Yuseung-Gu'
  city: Daejeon
  code: '34129'
  country: Korea
  email: yghong@etri.re.kr

- ins: X. de Foy
  name: Xavier de Foy
  org: InterDigital Communications, LLC
  street: '1000 Sherbrooke West'
  city: Montreal
  code: H3A 3G4
  country: Canada
  email: xavier.defoy@interdigital.com

- ins: M. Kovatsch
  name: Matthias Kovatsch
  org: Huawei Technologies Duesseldorf GmbH
  street: 'Riesstr. 25 C // 3.OG'
  city: Munich
  code: '80992'
  country: Germany
  email: ietf@kovatsch.net

- ins: E. Schooler
  name: Eve Schooler
  org: Intel
  street: '2200 Mission College Blvd.'
  city: Santa Clara, CA
  code: '95054-1537'
  country: USA
  email: eve.m.schooler@intel.com

- ins: D. Kutscher
  name: Dirk Kutscher
  org: University of Applied Sciences Emden/Leer
  street: 'Constantiaplatz 4'
  city: Emden
  code: '26723'
  country: Germany
  email: ietf@dkutscher.net

normative:

informative:

  DATA-DISCOVERY:
    title: "Edge Data Discovery for COIN"
    date: {DATE}
    seriesinfo:
      Internet-Draft: draft-mcbride-edge-data-discovery-overview
    author:
      - ins: M. McBride
      - ins: D. Kutscher
      - ins: E. Schooler
      - ins: CJ. Bernardos
  RFC6291:
  Ashton:
    title: That Internet of Things thing
    author:
    - ins: K. Ashton
    date: '2009'
    seriesinfo: RFID J. vol. 22, no. 7, pp. 97-114
  Lin:
    title: 'A survey on Internet of Things: Architecture, enabling technologies, security and privacy, and applications'
    author:
    - ins: J. Lin
    - ins: W. Yu
    - ins: N. Zhang
    - ins: X. Yang
    - ins: H. Zhang
    - ins: W. Zhao
    date: '2017'
    seriesinfo: IEEE Internet of Things J., vol. 4, no. 5, pp. 1125-1142
  NIST:
    title: The NIST definition of Cloud Computing
    author:
    - ins: P. Mell
    - ins: T. Grance
    date: '2009'
    seriesinfo: Natl. Inst. Stand. Technol, vol. 53, no. 6, p. 50
  Botta:
    title: 'Integration of Cloud Computing and Internet of Things: A survey'
    author:
    - ins: A. Botta
    - ins: W. Donato
    - ins: V. Persico
    - ins: A. Pescape
    date: '2016'
    seriesinfo: Future Gener. Comput. Syst., vol. 56, pp. 684-700
  Evans:
    title: 'The Internet of Things: How the next evolution of the Internet is changing everything'
    author:
    - ins: D. Evans
    date: '2011'
    seriesinfo: CISCO White Paper
  Shi:
    title: 'Edge computing: vision and challenges'
    author:
    - ins: W. Shi
    - ins: J. Cao
    - ins: Q. Zhang
    - ins: Y. Li
    - ins: L. Xu
    date: '2016'
    seriesinfo: IEEE Internet of Things J., vol. 3, no. 5, pp. 637-646
  Mahadev:
    title: 'The Emergence of Edge Computing'
    author:
    - ins: M. Satyanarayanan
    date: '2017'
    seriesinfo: Computer, vol. 50, no. 1, pp. 30-39
  Chiang:
    title: 'Fog and IoT: An overview of research opportunities'
    author:
    - ins: M. Chiang
    - ins: T. Zhang
    date: '2016'
    seriesinfo: IEEE Internet Things J., vol. 3, no. 6, pp. 854-864
  Weiner:
    title: 'Design of a low-latency, high-reliability wireless communication system for control applications'
    author:
    - ins: M. Weiner
    - ins: M. Jorgovanovic
    - ins: A. Sahai
    - ins: B. Nikolie
    date: '2014'
    seriesinfo: IEEE Int. Conf. Commun. (ICC), Sydney, NSW, Australia, pp. 3829-3835
  Kelly:
    title: 'Internet of Things Data to Top 1.6 Zettabytes by 2022'
    author:
    - ins: R. Kelly
    date: '2016'
    target: 'https://campustechnology.com/articles/2015/04/15/internet-of-thingsdata-to-top-1-6-zettabytes-by-2020.aspx'
  ISO_TR:
    title: 'Information Technology - Cloud Computing - Edge Computing Landscape'
    date: '2018'
    seriesinfo: ISO/IEC TR 23188
  OpenFog:
    title: 'OpenFog Reference Architecture for Fog Computing'
    date: '2017'
    seriesinfo: OpenFog Consortium
  ETSI_MEC_03:
    title: 'Mobile Edge Computing (MEC); Framework and Reference Architecture'
    author:
    - ins: ETSI
    date: '2019'
    seriesinfo: 'ETSI GS 003'
    target: 'https://www.etsi.org/deliver/etsi_gs/MEC/001_099/003/02.01.01_60/gs_MEC003v020101p.pdf'
  ETSI_MEC_01:
    title: 'Multi-access Edge Computing (MEC); Terminology'
    author:
    - ins: ETSI
    date: '2019'
    seriesinfo: 'ETSI GS 001'
    target: 'https://www.etsi.org/deliver/etsi_gs/MEC/001_099/001/02.01.01_60/gs_MEC001v020101p.pdf'
  NVIDIA:
    title: 'Training AI for Self-Driving Vehicles: the Challenge of Scale'
    author:
    - ins: A. Grzywaczewski
    date: '2017'
    seriesinfo: 'NVIDIA Developer Blog'
    target: 'https://devblogs.nvidia.com/training-self-driving-vehicles-challenge-scale/'
  _60802:
    title: 'Use Cases IEC/IEEE 60802 V1.3'
    author:
    - ins: IEC/IEEE
    date: '2018'
    seriesinfo: 'IEC/IEEE 60802'
    target: 'http://www.ieee802.org/1/files/public/docs2018/60802-industrial-use-cases-0818-v13.pdf'
  ENERGY:
    title: 'Revealing Household Characteristics from Smart Meter Data'
    author:
    - ins: C. Beckel
    - ins: L. Sadamori
    - ins: T. Staake
    - ins: S. Santini
    date: '2014'
    seriesinfo: 'Energy, vol. 78, pp. 397-410'
  ETSI_Sandbox:
    title: 'Multi-access Edge Computing (MEC) MEC Sandbox Work Item'
    date: '2020'
    seriesinfo: 'Portal'
    target: 'https://portal.etsi.org/webapp/WorkProgram/Report_WorkItem.asp?WKI_ID=57671'
  AdvantEDGE:
    title: 'Mobile Edge Emulation Platform'
    date: '2020'
    seriesinfo: 'Source Code Repository'
    target: 'https://github.com/InterDigitalInc/AdvantEDGE'
  SimulatingFog:
    title: 'Simulating Fog and Edge Computing Scenarios: An Overview and Research Challenges'
    author:
    - ins: S. Svorobej
    - ins: al.
    date: '2019'
    seriesinfo: 'MPDI Future Internet 2019'
  PseudoDynamicTesting:
    title: 'Revealing Household Characteristics from Smart Meter Data'
    author:
    - ins: M. Ficco
    - ins: C. Esposito
    - ins: Y. Xiang
    - ins: F. Palmieri
    date: '2017'
    seriesinfo: 'IEEE Communications Magazine, Nov. 2017'

--- abstract

Many IoT applications have requirements that cannot be met by the traditional Cloud (aka Cloud computing). These include time sensitivity, data volume, uplink cost, operation in the face of intermittent services, privacy and security. As a result, the IoT is driving the Internet toward Edge computing. This document outlines the requirements of the emerging IoT Edge and its challenges. It presents a snapshot of the state-of-the-art, a general model, and major components of the IoT Edge, with the goal to provide a common base for future discussions in T2TRG and other IETF WGs and RGs.

--- middle

# Introduction

Currently, many IoT services leverage the Cloud, since it can provide virtually unlimited storage and processing power.
The reliance of IoT on  back-end cloud computing brings additional advantages such as flexibility and efficiency.
Today’s IoT systems are fairly static with respect to integrating and supporting computation. It’s not that there is no computation, but systems are often limited to static configurations (edge gateways, the Cloud).

However, IoT devices are creating vast amounts of data at the network edge. To meet IoT use case requirements, that data increasingly is being stored, processed, analyzed, and acted upon close to the data producers.
These requirements include time sensitivity, data volume, uplink cost, resiliency in the face of intermittent connectivity, privacy, and security, which cannot be addressed by today's centralized cloud computing.
These requirements suggest a more flexible way to distribute computing (and storage) and to integrate it in the edge-cloud continuum.
We will refer to this integration of edge computing and IoT as "IoT edge computing".
Our draft describes uses cases, challenges, a proposed system model and derived functional components.

# Background

## Internet of Things (IoT)

Since the term "Internet of Things" (IoT) was coined by Kevin Ashton in 1999 working on Radio-Frequency Identification (RFID) technology at the Auto-ID Center of the Massachusetts Institute of Technology (MIT) {{Ashton}},
the concept of IoT had been broadened to reflect the vision of connecting the physical world to the virtual world of computers using (wireless) sensor networks with any kind of technology with which the Things can send and receive information without human intervention.
Recently, the term has become more literal by actually connecting Things to the Internet and converging on Internet and also Web technology.
Things are usually embedded systems of various kinds, such as home appliances, mobile equipment, wearable devices, etc. 
Things are widely distributed, but typically have limited storage and processing power, which raise concerns regarding reliability, performance, energy consumption, security, and privacy  {{Lin}}.

## Cloud Computing

Cloud computing has been defined in {{NIST}}: "cloud computing is a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources
(e.g., networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort or service provider interaction".
Cloud computing has been a predominant technology which has virtually unlimited capacity in terms of storage and processing power.
The availability of virtually unlimited storage and processing capabilities at low cost enabled the realization of a new computing model, in which virtualized resources can be leased in an on-demand fashion, being provided as general utilities.
Companies like Amazon, Google, Facebook, etc. widely adopted this paradigm for delivering services over the Internet, gaining both economical and technical benefits {{Botta}}.

Now with IoT, we will reach the era of post-clouds where unprecedented volume and variety of data will be generated by things at edge/local networks and many applications will be deployed on the edge networks to consume these IoT data. Some of the applications may need very short response times, some may contain personal data, and others may generate vast amounts of data. Today's cloud-based service models are not suitable for these applications.

It is predicted that by 2019, 45% of the data created in IoT will be stored, processed, analyzed and acted close to, or at the edge of the network and about 50 billion devices will connect to the Internet by 2020 {{Evans}}. So, moving all data from edge/local networks to the cloud data center may not be an efficient way anymore to process vast amounts of data.

In cloud computing, users traditionally only consumed IoT data through cloud services. Now, however, users are also producing IoT data with their mobile devices. This change requires even more functionality at edge/local networks {{Shi}}, to support mobile edge computing considerations.

## Edge Computing

Edge computing, under certain aspects also referred to as fog computing, is a new paradigm in which substantial computing and storage resources are placed at the edge of the Internet, that is, in close proximity to mobile devices, sensors, actuators, or machines, so that computing happens near data sources {{Mahadev}}, or closer (topologically, physically, in term of latency, etc.) to where decisions or interactions with the physical world are happening.
It works on both downstream data on behalf of cloud services and upstream data on behalf of IoT services.

An edge device is any computing or networking resource residing between data sources and cloud-based datacenters.
In edge computing, end devices not only consume data, but also produce data. 
And at the network edge, devices not only request services and information from the cloud, but also handle computing tasks including processing, storage, caching, and load balancing on data sent to and from the cloud {{Shi}}.
This does not preclude end devices from hosting computation themselves when possible, independently or as part of a distributed edge computing platform.

The definition of edge computing from ISO is a "form of distributed computing in which significant processing and data storage takes place on nodes which are at the edge of the network" {{ISO_TR}}. ETSI's definition of multi-access edge computing is a "system which provides an IT service environment and cloud-computing capabilities at the edge of an access network which contains one or more type of access technology, and in close proximity to its users" {{ETSI_MEC_01}}.

The similar concept of fog computing from the Industrial Internet Consortium (formerly OpenFog) is "a horizontal, system-level architecture that distributes computing, storage, control and networking functions closer to the users along a cloud-to-thing continuum" {{OpenFog}}.
The term fog computing usually represents the notion of a multi-tiered edge computing, that is, several layers of compute infrastructure between the end devices and the cloud.

Based on these definitions, we can summarize a general philosophy of edge computing as to distribute the required functions close to users and data, while the difference to classic local systems is the usage of management and orchestration features adopted from cloud computing.

Actors from various industries approach edge computing using different terms and reference models, although in practice these approaches are not incompatible and may integrate with each other:

* The telecommunication industry tends to use a model where edge computing services are deployed over NFV infrastructure at aggregation points, or in proximity to the user equipment (e.g., gNodeBs) {{ETSI_MEC_03}}.
* Enterprise and campus solutions often interpret edge computing as an "edge cloud", that is, a smaller data center directly connected to the local network (often referred to as "on-premise").
* The automation industry defines the edge as the connection point between IT from OT (Operational Technology). Hence, here edge computing sometimes referres to applying IT solutions to OT problems such as analytics, more flexible user interfaces, or simply having more compute power than an automation controller.

It is clear that the combination of these models leads to a multi-tier edge computing solution as mentioned above.

## Example of IoT Edge Computing Use Cases

IoT edge computing can be used in home, industry, grid, healthcare, city, transportation, agriculture, and/or education scenarios.
We discuss here only a few examples of such use cases, to point out differentiating requirements.

### Smart Construction

In traditional construction domain, heavy equipment and machinery pose risks to humans and property. Thus, there have been many attempts to deploy technology to protect lives and property in construction sites. For example, measurements of noise, vibration, and gas can be recorded on a remote server and reported to an inspector. Today, data produced by such measurements is collected by a local gateway and transferred to a remote server. This incurs transmission costs, e.g., over a LTE connection, and storage costs, e.g., when using Amazon Web Services. When an inspector needs to investigate an incident, he checks the information stored on a server.

If we leverage IoT edge computing, sensor data can be processed and analyzed on a gateway located within or near a construction site. And with the help of statistical analysis or machine learning technologies, we can predict future incidents in advance and this prediction can trigger an on-site alarm and a notification to an inspector.

To determine the exact cause of an incident, sensor data including audio and video are transferred to a remote server. In this case, audio and video data volume is typically very large and the cost of transmission can be an issue.
Edge computing can be leveraged to predict the time of an incident, which can reduce the volume of transmitted data; while during a normal time period audio and video data may be transmitted with a low resolution, during an emergency, this transmission may use a high resolution. This adjustment can reduce transmission cost significantly.

### Smart Grid

In future smart city scenarios, the Smart Grid will be critical in ensuring highly available/efficient energy control in city-wide electricity management.
Edge computing is expected to play a significant role in those systems to improve transmission efficiency of electricity; to react and restore power after a disturbance; to reduce operation costs and reuse renewable energy effectively, since these operations involve local decision making. In addition, edge computing can help monitoring power generation and power demand, and making electrical energy storage decisions in the smart grid system.

### Smart Water System

The water system is one of the most important aspects of a city. Effective use of water, and cost-effective and environment-friendly water treatment  are critical aspects of this system. They can be facilitated by edge computing in smart water systems, to help monitor water consumption, transportation and prediction of future water use. For example, water harvesting and ground water monitoring will be supported through edge computing.
Edge computing will also enable locally analyzing collected information related to water control and management, and limit water losses.

# Challenges for IoT and Impacts of Edge Computing {#sec-challenges}

As the IoT is maturing, systems are converging, deployments are growing, and IoT technology is used with more and more demanding applications such as industrial, automotive, or healthcare.
This leads to new challenges for the network infrastructure.
In particular, the amount of data created at the edge is expected to be vast.
Industrial machines such as laser cutters already produce over 1 terabyte per hour, the same applies for autonomous cars {{NVIDIA}}.
90% of IoT data is expected to be stored, processed, analyzed, and acted upon close to the source {{Kelly}},
as cloud computing models alone cannot address the new challenges {{Chiang}}.
Below we discuss IoT use case requirements that are moving cloud capabilities to be more proximate and more distributed and disaggregated. Beyond addressing those requirements, however, edge computing can also bring flexibility to classic networking functions such as protocol translation in gateways.

## Time Sensitivity

Many industrial control systems, such as manufacturing systems, smart grids, oil and gas systems, etc., often require stringent end-to-end latency between the sensor and control node.
While some IoT applications may require latency below a few tens of milliseconds {{Weiner}},
industrial robots and motion control systems have use cases for cycle times in the order of microseconds {{_60802}}.
An important aspect for real-time communications is not only the latency, but also guarantees for jitter.
This means control packets need to arrive with as little variation as possible with a strict deadline.
Given the best-effort characteristics of the Internet, this challenge is virtually impossible to address, without comprehending end-to-end guarantees for individual message delivery and continuous data flows.

## Uplink Cost

Many IoT deployments are not challenged by a constrained network bandwidth to the cloud.
The fifth generation mobile networks (5G) and Wi-Fi 6 both theoretically top out at 10 gigabits per second (i.e., 4.5 terabyte per hour), which enables high-bandwidth uplinks.
However, the resulting cost for high-bandwidth connectivity to upload all data to the cloud is unjustifiable and impractical for most IoT applications.
In some settings, e.g. in aeronautical communication, higher communication costs reduce the amount of data that can be practically uploaded even further. 

## Resilience to Intermittent Services

Many IoT devices such as sensors, data collectors, actuators, controllers, etc. have very limited hardware resources
and cannot rely solely on their limited resources to meet all their computing and/or storage needs.
They require reliable, uninterrupted or resilient services to augment their capabilities in order to fulfill their application tasks.
This is hard and partly impossible to achieve with cloud services for systems such as vehicles, drones, or oil rigs that have intermittent network connectivity.

## Privacy and Security

When IoT services are deployed at home, personal information can be learned from detected usage data.
For example, one can extract information about employment, family status, age, and income by analyzing smart meter data {{ENERGY}}.
Policy makers started to provide frameworks that limit the usage of personal data and put strict requirements on data controllers and processors.
However, data stored indefinitely in the cloud also increases the risk of data leakage, for instance, through attacks on rich targets.

Industrial systems are often argued to not have privacy implications, as no personal data is gathered.
Yet data from such systems is often highly sensitive, as one might be able to infer trade secrets such as the setup of production lines.
Hence, the owner of these systems are generally reluctant to upload IoT data to the cloud.

# IoT Edge Computing Functions

## Overview of IoT Edge Computing Today

This section provides an overview of today's IoT edge computing field, based on a limited review of standards, research, open-source and proprietary products in draft-defoy-t2trg-iot-edge-computing-background.

IoT gateways, both open-source (such as EdgeX Foundry or Home Edge) and proprietary (such as Amazon Greengrass, Microsoft Azure IoT Edge, Google Cloud Iot Core, and gateways from Bosh, Siemens), represent a common class of IoT edge computing products, where the gateway is providing a local service on customer premises, and is remotely managed through a cloud service. IoT communication protocols are typically used between IoT devices and the gateway, including CoAP, MQTT and many specialized IoT protocols (such as OPC UA and DDS in the Industrial IoT space), while the gateway communicates with the distant cloud typically using HTTPS. Virtualization platforms enable the deployment of virtual edge computing functions (as VMs, application containers, etc.), including IoT gateway software, on servers in the mobile network infrastructure (at base station and concentration points), in edge datacenters (in central offices) or regional datacenters located near central offices. End devices are envisioned to become computing devices in forward looking projects, but are not commonly used as such today.

Physical or virtual IoT gateways can host application programs, which are typically built using an SDK to access local services through a programmatic API.
Edge cloud system operators host their customers' applications VMs or containers on servers located in or near access networks, which can implement local edge services. For example, mobile networks can provide edge services for radio network information, location and bandwidth management.

Life cycle management of services and applications on physical IoT gateways is often cloud-based.
Edge cloud management platforms and products (such as StarlingX, Akraino Edge Stack, Mobile EdgeX) adapt cloud management technologies (e.g., Kubernetes) to the edge cloud, i.e., to smaller, distributed computing devices running outside a controlled data center. Services and application life-cycle is typically using a NFV-like management and orchestration model.

The platform typically includes services to advertise or consume APIs (e.g., Mp1 interface in ETSI MEC supports service discovery and communication), and enables communicating with local and remote endpoints (e.g., message routing function in IoT gateways). The service platform is typically extensible by edge applications, since they can advertise an API that other edge applications can consume. IoT communication services include protocols translation, analytics and transcoding. Communication between edge computing devices is enabled in tiered deployments or distributed deployments.

An edge cloud platform may enable pass-through without storage or local storage (e.g., on IoT gateways). Some edge cloud platforms use a distributed form of storage such as an ICN network (e.g., NFN nodes can store data in NDN) or a distributed storage platform (e.g., Ceph). External storage, e.g., on databases in distant or local IT cloud, is typically used for filtered data deemed worthy of long term storage, although in some case it may be for all data, for example when required for regulatory reasons.

Stateful computing is supported on platforms hosting native programs, VMs or containers. Stateless computing is supported on platforms providing a "serverless computing" service (a.k.a. function-as-a-service), or on systems based on named function networking.

In many IoT use cases, a typical network usage pattern is high volume uplink with some form of traffic reduction enabled by processing over edge computing devices. Alternatives to traffic reduction include deferred transmission (to off-peak hours or using physical shipping). Downlink traffic includes application control and software updates. Other, downlink-heavy traffic patterns are not excluded but are more often associated with non-IoT usage (e.g., video CDNs).

## Models

Edge computing is expected to play an important role in deploying new IoT services integrated with Big Data and AI, enabled by flexible in-network computing platforms. Although there are lots of approaches to edge computing, we attempt to lay out a general model and list associated logical functions in this section. In practice, this model can map to different architectures, such as: 

- A single IoT gateway, or a hierarchy of IoT gateways, typically connected to the cloud (e.g., to extend the traditionally cloud-based management of IoT devices and data to the edge). A common role of an IoT Gateway is to provide access to an heterogeneous set of IoT devices/sensors; handle IoT data; and deliver IoT data to its final destination in a cloud network. Whereas an IoT gateway needs  interactions with cloud like as conventional cloud computing, it can also operate independently.
- A set of distributed computing nodes, e.g., embedded in switches, routers, edge cloud servers or mobile devices. In the future, some IoT end devices may have enough computing capabilities to participate in such distributed systems. In this model, edge computing nodes can collaborate with each other to share their resources.

~~~~~~~~~~~~~~~~~~~
   +---------------------+
   |   Remote network    |  +---------------+
   |(e.g., cloud network)|  |   Service     |
   +-----------+---------+  |   Operator    |
               |            +------+--------+
               |                   |
+--------------+-------------------+-----------+
|            Edge Computing Domain             |
|                                              |
|   Computing Nodes (edge or end devices)      |
|                                              |
|   OAM Components                             |
|   - Resources Discovery                      |
|   - Virtualization Management                |
|   - Authentication                           |
|   - Edge Organization and Federation         |
|   - ...                                      |
|                                              |
|   Functional Components                      |
|   - External APIs                            |
|   - Communication Brokering                  |
|   - In-Network Computation                   |
|   - Edge Caching                             |
|   - Other Services                           |
|   - ...                                      |
|                                              |
|   Application Components                     |
|   - IoT End Devices Management               |
|   - Data Management                          |
|   - ...                                      |
|                                              |
+------+--------------+-------- - - - -+- - - -+
       |              |       |        |       |
       |              |          +-----+--+     
  +----+---+    +-----+--+    |  |compute |    |
  |  End   |    |  End   | ...   |node/end|     
  |Device 1|    |Device 2| ...|  |device n|    |
  +--------+    +--------+       +--------+     
                              + - - - - - - - -+
~~~~~~~~~~~~~~~~~~~
{: artwork-align="center" #rl-fig1 title="Model of IoT Edge Computing"}

In this general model, the edge computing domain is interconnected with IoT end devices (southbound connectivity) and possibly with a remote/cloud network (northbound connectivity), and with a service operator's system.
Edge computing nodes provide multiple logical functions, or components, which may not all be present in a given system. They may be implemented in a centralized or distributed fashion, in the edge network, or through some interworking between the edge network and a remote cloud network.

We now attempt to enumerate major edge computing domain components. They are here loosely organized into OAM, functional and application components, with the understanding that the distinction between these classes may not always be clear, depending on actual system architectures.

## OAM Components

Edge computing OAM goes beyond the network-related OAM functions listed in {{RFC6291}}. Besides infrastructure (network, storage and computing resources), edge computing systems can also include computing environments (for VMs, software containers, functions), IoT end devices, data and code.

Operation related functions include performance monitoring for service level agreement measurement; fault management and provisioning for links, nodes, compute and storage resources, platforms and services. Administration covers network/compute/storage resources, platforms and services discovery, configuration and planning. Management covers monitoring and diagnostics of failures, as well as means to minimize their occurrence and take corrective actions. This may include software updates management, high service availability through redundancy and multipath communication.

We further detail a few OAM components.

### Resources Discovery

This component is about finding infrastructure resources, such as compute, network and storage, but also other resources such as IoT end devices, sensors, data, code, or services.

### Virtualization Management

Some IoT edge computing systems make use of virtualized (compute, storage and networking) resources, which need to be allocated and configured.

### Authentication and Authorization

This can cover authenticating platforms, end devices, data, code units and applications or users interacting with the system. Today, centralized gateway-based systems rely for device authentication on the installation of a secret on IoT end devices and on computing devices (e.g., a device certificate stored in a hardware security module).

### Edge Organization and Federation

In a distributed system context, once edge devices have discovered and authenticated each other, they can be organized, or self-organize, into hierarchies or clusters. Such groups can also form federations with other edge or remote clouds.

## Functional Components

### External APIs

An IoT edge cloud may provide a northbound data plane or management plane interface to a remote network, e.g., a cloud, home or enterprise network. This interface does not exist in standalone (local-only) scenarios. To support such an interface when it exists, an edge computing component needs to expose an API, deal with authentication and authorization, support secure communication.

An IoT edge cloud may provide an API or interface to local users (e.g., to facilitate local management), or to mobile users (e.g., to provide access to services and applications, or to manage data published by the mobile device).

### Communication Brokering

A typical function of IoT edge computing is to facilitate communication with IoT end devices: for example, enable clients to register as recipients for data from devices, as well as forwarding/routing of traffic to or from IoT end devices, enabling various data discovery and redistribution patterns, e.g., north-south with clouds, east-west with other edge devices {{DATA-DISCOVERY}}. Another aspect of a communication component is dispatching of alerts and notifications to interested consumers both inside and outside of the edge computing domain. Protocol translation, analytics and transcoding may also be performed when necessary.

Communication brokering may be centralized in some systems, e.g., using a hub-and-spoke message broker, or distributed like with message buses, possibly in a layered bus approach. Distributed systems may leverage direct communication between end devices and communication devices, such as device-to-device links. Brokers functions can include ensuring communication reliability, traceability, and in some cases transaction management.

QoS can be provided in some systems through the combination of network QoS (e.g., traffic engineering or wireless resource scheduling) and compute/storage resource allocations. In some systems a bandwidth manager service can be exposed to enable allocation of bandwidth to/from an edge computing application instance.

### In-Network Computation

A core function of IoT edge computing is to enable computation offloading, i.e., to perform computation on an edge node on behalf of a device or user. The support for in-network computation may vary in term of capability, e.g., computing nodes can host a virtual machine able run stateful or stateless code, or a rule engine providing an API to register actions in response to conditions such as IoT device ID, sensor values to check, thresholds, etc. Computation offloading includes orchestration or application lifecycle related aspects, such as: selecting an appropriate compute device based on available resources, compute node properties, etc., and with varying goals including for example load balancing and energy conservation; onboarding code on a platform or compute device; assisted or automatic partitioning of code; invoking remote code execution; relocating an instance from one compute node to another; session continuity when communicating with mobile end devices.

### Edge Caching

A purpose of local caching may be to enable local data processing (e.g., pre-processing or analysis), or to enable delayed virtual or physical shipping. A responsibility of the edge caching component is to manage data persistence, e.g., to schedule removal of data when it is no longer needed. Another aspect of this component may be to authenticate and encrypt data. It can for example take the form of a distributed storage system, and deal with related issues, e.g., reaching and maintaining data consistency; enabling efficient access to data, for example using some form of sharding.

### Other Services

Data generated by IoT devices and associated information obtained from the access network may be used to provide high level services such as end device location, radio network information and bandwidth management. 

## Application Components

### IoT End Devices Management

IoT end device management includes managing information about the IoT devices, including their sensors, how to communicate with them, etc.
Edge computing addresses the scalability challenges from the massive number of IoT end devices and IoT data value by separating the scalability domain into edge/local networks and remote network.

### Data Management

With regard to the high level challenges listed in {{sec-challenges}}, data storage and processing at the edge is a major aspect of IoT edge computing. Data may therefore need to be classified (e.g., in terms of privacy, importance, validity, etc.). Data analysis such as performed in AI/ML tasks performed at the edge may benefit from specialized hardware support on computing nodes. IoT edge computing will face challenges in term of, for example, programmability, naming, data abstraction, data service management and data discovery (discussed in communication brokering). Furthermore, while edge computing can support IoT services independently of cloud computing, it can also be connected to cloud computing. Thus, the relationship of IoT edge computing to cloud computing, with regard to data management, is another potential challenge {{ISO_TR}}.

## Simulation and Emulation Environments

IoT Edge Computing brings new challenges to simulation and emulation tools used by researchers and developers. A varied set of applications, network and computing technologies can coexist in a distributed system, which make modelling difficult. Scale, mobility and resource management are additional challenges [SimulatingFog].

Tools include simulators, where simplified application logic runs on top of a fog network model, and emulators, where actual applications can be deployed, typically in software containers, over a cloud infrastructure (e.g. Docker, Kubernetes) itself running over a network emulating edge network conditions such as variable delays, throughput and mobility events. To gain in scale, emulated and simulated systems can be used together in hybrid federation-based approaches [PseudoDynamicTesting], while to gain in realism physical devices can be interconnected with emulated systems. Examples of related work and platforms include the publicly accessible MEC sandbox work recently initiated in ETSI [ETSI_Sandbox], and open source simulators and emulators ([AdvantEDGE] emulator and tools cited in [SimulatingFog]).

# Security Considerations

T.B.D.

# Acknowledgement

The authors would like to thank Joo-Sang Youn, Akbar Rahman, Michel Roy, Robert Gazda and Rute Sofia for their valuable comments and suggestions on this document.

