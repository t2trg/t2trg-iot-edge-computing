---
stand_alone: true
ipr: trust200902
docname: draft-irtf-t2trg-iot-edge-10
#docname: draft-irtf-t2trg-iot-edge-latest
cat: info
stream: IRTF
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
  country: Republic of Korea
  email: jhong@etri.re.kr

- ins: Y-G. Hong
  name: Yong-Geun Hong
  org: Daejeon University
  street: '62 Daehak-ro, Dong-gu'
  city: Daejeon
  code: '300716'
  country: Republic of Korea
  email: yonggeun.hong@gmail.com

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
  email: eve.schooler@gmail.com

- ins: D. Kutscher
  name: Dirk Kutscher
  org: Hong Kong University of Science and Technology (Guangzhou)
  street: 'No.1 Du Xue Rd'
  city: Guangzhou
  country: China
  email: ietf@dkutscher.net

normative:

informative:

  I-D.mcbride-edge-data-discovery-overview:
  RFC6291:
  RFC8578:
  I-D.irtf-t2trg-rest-iot:
  Ashton:
    title: That Internet of Things thing
    author:
    - ins: K. Ashton
    date: '2009'
    rc: RFID J. vol. 22, no. 7, pp. 97-114
    target: http://www.itrco.jp/libraries/RFIDjournal-That%20Internet%20of%20Things%20Thing.pdf
  Lin:
    seriesinfo:
      IEEE Internet of Things Journal: vol. 4, no. 5, pp. 1125-1142
      DOI: 10.1109/jiot.2017.2683200
    title: 'A Survey on Internet of Things: Architecture, Enabling Technologies, Security
      and Privacy, and Applications'
    author:
    - name: Jie Lin
      ins: J. Lin
    - name: Wei Yu
      ins: W. Yu
    - name: Nan Zhang
      ins: N. Zhang
    - name: Xinyu Yang
      ins: X. Yang
    - name: Hanlin Zhang
      ins: H. Zhang
    - name: Wei Zhao
      ins: W. Zhao
    date: 2017-10
  NIST:
    seriesinfo:
      National Institute of Standards and Technology: report
      DOI: 10.6028/nist.sp.800-145
    title: The NIST definition of cloud computing
    author:
    - name: P M Mell
      ins: P. Mell
    - name: T Grance
      ins: T. Grance
    date: '2011'
  Botta:
    seriesinfo:
      Future Generation Computer Systems: vol. 56, pp. 684-700
      DOI: 10.1016/j.future.2015.09.021
    title: 'Integration of Cloud computing and Internet of Things: A survey'
    author:
    - name: Alessio Botta
      ins: A. Botta
    - name: Walter de Donato
      ins: W. de Donato
    - name: Valerio Persico
      ins: V. Persico
    - name: Antonio Pescape
      ins: A. Pescape
    date: 2016-03
  Shi:
    seriesinfo:
      IEEE Internet of Things Journal: vol. 3, no. 5, pp. 637-646
      DOI: 10.1109/jiot.2016.2579198
    title: 'Edge Computing: Vision and Challenges'
    author:
    - name: Weisong Shi
      ins: W. Shi
    - name: Jie Cao
      ins: J. Cao
    - name: Quan Zhang
      ins: Q. Zhang
    - name: Youhuizi Li
      ins: Y. Li
    - name: Lanyu Xu
      ins: L. Xu
    date: 2016-10
  Mahadev:
    seriesinfo:
      Computer: vol. 50, no. 1, pp. 30-39
      DOI: 10.1109/mc.2017.9
    title: The Emergence of Edge Computing
    author:
    - name: Mahadev Satyanarayanan
      ins: M. Satyanarayanan
    date: 2017-01
  Chiang:
    seriesinfo:
      IEEE Internet of Things Journal: vol. 3, no. 6, pp. 854-864
      DOI: 10.1109/jiot.2016.2584538
    title: 'Fog and IoT: An Overview of Research Opportunities'
    author:
    - name: Mung Chiang
      ins: M. Chiang
    - name: Tao Zhang
      ins: T. Zhang
    date: 2016-12
  Weiner:
    seriesinfo:
      2014 IEEE International Conference on Communications: "(ICC)"
      DOI: 10.1109/icc.2014.6883918
    title: Design of a low-latency, high-reliability wireless communication system for
      control applications
    author:
    - name: Matthew Weiner
      ins: M. Weiner
    - name: Milos Jorgovanovic
      ins: M. Jorgovanovic
    - name: Anant Sahai
      ins: A. Sahai
    - name: Borivoje Nikolie
      ins: B. Nikolie
    date: 2014-06
  Kelly:
    title: 'Internet of Things Data to Top 1.6 Zettabytes by 2022'
    author:
    - ins: R. Kelly
    date: '2015'
    rc: Retrieved on 2022-05-24
    target: 'https://campustechnology.com/articles/2015/04/15/internet-of-things-data-to-top-1-6-zettabytes-by-2020.aspx'
  ISO_TR:
    title: 'Internet of things (IoT) - Edge computing'
    date: '2020'
    seriesinfo:
      ISO/IEC: TR 30164
    target: 'https://www.iso.org/standard/53284.html'
  OpenFog:
    title: 'OpenFog Reference Architecture for Fog Computing'
    date: '2017'
    rc: OpenFog Consortium
    target: https://iiconsortium.org/pdf/OpenFog_Reference_Architecture_2_09_17.pdf
  ETSI_MEC_03:
    title: 'Mobile Edge Computing (MEC); Framework and Reference Architecture'
    author:
    - org: ETSI
    date: '2019'
    rc: 'ETSI GS MEC 003'
    target: 'https://www.etsi.org/deliver/etsi_gs/MEC/001_099/003/02.01.01_60/gs_MEC003v020101p.pdf'
  ETSI_MEC_01:
    title: 'Multi-access Edge Computing (MEC); Terminology'
    author:
    - ins: ETSI
    date: '2019'
    rc: 'ETSI GS MEC 001'
    target: 'https://www.etsi.org/deliver/etsi_gs/MEC/001_099/001/02.01.01_60/gs_MEC001v020101p.pdf'
  NVIDIA:
    title: 'Training AI for Self-Driving Vehicles: the Challenge of Scale'
    author:
    - ins: A. Grzywaczewski
    date: '2017'
    rc: 'NVIDIA Developer Blog, retrieved on 2022-05-24'
    target: 'https://devblogs.nvidia.com/training-self-driving-vehicles-challenge-scale/'
  _60802:
    title: 'Use Cases IEC/IEEE 60802 V1.3'
    author:
    - org: IEC/IEEE
    date: '2018'
    seriesinfo:
      IEC/IEEE: 60802
    target: 'https://grouper.ieee.org/groups/802/1/files/public/docs2018/60802-industrial-use-cases-0918-v13.pdf'
  ENERGY:
    seriesinfo:
      Energy: vol. 78, pp. 397-410
      DOI: 10.1016/j.energy.2014.10.025
    title: Revealing household characteristics from smart meter data
    author:
    - name: Christian Beckel
      ins: C. Beckel
    - name: Leyna Sadamori
      ins: L. Sadamori
    - name: Thorsten Staake
      ins: T. Staake
    - name: Silvia Santini
      ins: S. Santini
    date: 2014-12
  ETSI_Sandbox:
    title: 'Multi-access Edge Computing (MEC) MEC Sandbox Work Item'
    date: '2020'
    rc: 'Portal'
    target: 'https://portal.etsi.org/webapp/WorkProgram/Report_WorkItem.asp?WKI_ID=57671'
  AdvantEDGE:
    title: 'Mobile Edge Emulation Platform'
    date: '2020'
    rc: 'Source Code Repository'
    target: 'https://github.com/InterDigitalInc/AdvantEDGE'
  SimulatingFog: # DOI.10.3390/fi11030055
    seriesinfo:
      Future Internet: vol. 11, no. 3, pp. 55
      DOI: 10.3390/fi11030055
    title: 'Simulating Fog and Edge Computing Scenarios: An Overview and Research Challenges'
    author:
    - name: Sergej Svorobej
      ins: S. Svorobej
    - name: Patricia Takako Endo
      ins: P. Takako Endo
    - name: Malika Bendechache
      ins: M. Bendechache
    - name: Christos Filelis-Papadopoulos
      ins: C. Filelis-Papadopoulos
    - name: Konstantinos Giannoutakis
      ins: K. Giannoutakis
    - name: George Gravvanis
      ins: G. Gravvanis
    - name: Dimitrios Tzovaras
      ins: D. Tzovaras
    - name: James Byrne
      ins: J. Byrne
    - name: Theo Lynn
      ins: T. Lynn
    date: '2019-02-26'
  PseudoDynamicTesting:
    seriesinfo:
      IEEE Communications Magazine: vol. 55, no. 11, pp. 98-104
      DOI: 10.1109/mcom.2017.1700328
    title: Pseudo-Dynamic Testing of Realistic Edge-Fog Cloud Ecosystems
    author:
    - name: Massimo Ficco
      ins: M. Ficco
    - name: Christian Esposito
      ins: C. Esposito
    - name: Yang Xiang
      ins: Y. Xiang
    - name: Francesco Palmieri
      ins: F. Palmieri
    date: 2017-11
  LFEDGE-EVE:
    title: 'Project Edge Virtualization Engine (EVE)'
    author:
    - ins: Linux Foundation
    date: '2020'
    rc: Portal, retrieved on 2022-05-24
    target: https://www.lfedge.org/projects/eve
  Yousefpour:
    seriesinfo:
      Journal of Systems Architecture: vol. 98, pp. 289-330
      DOI: 10.1016/j.sysarc.2019.02.009
    title: 'All one needs to know about fog computing and related edge computing paradigms:
      A complete survey'
    author:
    - name: Ashkan Yousefpour
      ins: A. Yousefpour
    - name: Caleb Fung
      ins: C. Fung
    - name: Tam Nguyen
      ins: T. Nguyen
    - name: Krishna Kadiyala
      ins: K. Kadiyala
    - name: Fatemeh Jalali
      ins: F. Jalali
    - name: Amirreza Niakanlahiji
      ins: A. Niakanlahiji
    - name: Jian Kong
      ins: J. Kong
    - name: Jason P. Jue
      ins: J. Jue
    date: 2019-09
  I-D.bernardos-sfc-fog-ran:
  Schafer:
    seriesinfo:
      2016 IEEE 36th International Conference on Distributed Computing Systems Workshops: "(ICDCSW)"
      DOI: 10.1109/icdcsw.2016.22
    title: 'Tasklets: Overcoming Heterogeneity in Distributed Computing Systems'
    author:
    - name: Dominik Schafer
      ins: D. Schafer
    - name: Janick Edinger
      ins: J. Edinger
    - name: Sebastian VanSyckel
      ins: S. VanSyckel
    - name: Justin Mazzola Paluska
      ins: J. Paluska
    - name: Christian Becker
      ins: C. Becker
    date: 2016-06
  Echeverria:
    seriesinfo:
      2016 IEEE/ACM Symposium on Edge Computing: "(SEC)"
      DOI: 10.1109/sec.2016.27
    title: Establishing Trusted Identities in Disconnected Edge Environments
    author:
    - name: Sebastian Echeverria
      ins: S. Echeverria
    - name: Dan Klinedinst
      ins: D. Klinedinst
    - name: Keegan Williams
      ins: K. Williams
    - name: Grace A. Lewis
      ins: G. Lewis
    date: 2016-10
  Harchol:
    seriesinfo:
      Proceedings of the 2018 Workshop on Mobile Edge: Communications
      DOI: 10.1145/3229556.3229558
    title: 'CESSNA: Resilient Edge-Computing'
    author:
    - name: Yotam Harchol
      ins: Y. Harchol
    - name: Aisha Mushtaq
      ins: A. Mushtaq
    - name: James McCauley
      ins: J. McCauley
    - name: Aurojit Panda
      ins: A. Panda
    - name: Scott Shenker
      ins: S. Shenker
    date: '2018-08-07'
  Anglano:
    seriesinfo:
      2018 Third International Conference on Fog and Mobile Edge Computing: "(FMEC)"
      DOI: 10.1109/fmec.2018.8364054
    title: A game-theoretic approach to coalition formation in fog provider federations
    author:
    - name: Cosimo Anglano
      ins: C. Anglano
    - name: Massimo Canonico
      ins: M. Canonico
    - name: Paolo Castagno
      ins: P. Castagno
    - name: Marco Guazzone
      ins: M. Guazzone
    - name: Matteo Sereno
      ins: M. Sereno
    date: 2018-04
  Jeong:
    seriesinfo:
      2017 IEEE Fog World Congress: "(FWC)"
      DOI: 10.1109/fwc.2017.8368528
    title: Towards a distributed computing framework for Fog
    author:
    - name: Taeyeol Jeong
      ins: T. Jeong
    - name: Jaeyoon Chung
      ins: J. Chung
    - name: James Won-Ki Hong
      ins: J. Hong
    - name: Sangtae Ha
      ins: S. Ha
    date: 2017-10
  Fan:
    seriesinfo:
      2017 IEEE International Conference on Communications: "(ICC)"
      DOI: 10.1109/icc.2017.7996722
    title: Cost Aware cloudlet Placement for big data processing at the edge
    author:
    - name: Qiang Fan
      ins: Q. Fan
    - name: Nirwan Ansari
      ins: N. Ansari
    date: 2017-05
  Yangui:
    seriesinfo:
      2016 IEEE International Symposium on Local and Metropolitan Area Networks: "(LANMAN)"
      DOI: 10.1109/lanman.2016.7548853
    title: A platform as-a-service for hybrid cloud/fog environments
    author:
    - name: Sami Yangui
      ins: S. Yangui
    - name: Pradeep Ravindran
      ins: P. Ravindran
    - name: Ons Bibani
      ins: O. Bibani
    - name: Roch H. Glitho
      ins: R. Glitho
    - name: Nejib Ben Hadj-Alouane
      ins: N. Ben Hadj-Alouane
    - name: Monique J. Morrow
      ins: M. Morrow
    - name: Paul A. Polakos
      ins: P. Polakos
    date: 2016-06
  Li:
    seriesinfo:
      2017 IEEE 37th International Conference on Distributed Computing Systems: "(ICDCS)"
      DOI: 10.1109/icdcs.2017.54
    title: 'MobiQoR: Pushing the Envelope of Mobile Edge Computing Via Quality-of-Result
      Optimization'
    author:
    - name: Yongbo Li
      ins: Y. Li
    - name: Yurong Chen
      ins: Y. Chen
    - name: Tian Lan
      ins: T. Lan
    - name: Guru Venkataramani
      ins: G. Venkataramani
    date: 2017-06
  Liu:
    seriesinfo:
      IEEE Transactions on Wireless Communications: vol. 16, no. 11, pp. 7039-7051
      DOI: 10.1109/twc.2017.2737015
    title: 'Cache Placement in Fog-RANs: From Centralized to Distributed Algorithms'
    author:
    - name: Juan Liu
      ins: J. Liu
    - name: Bo Bai
      ins: B. Bai
    - name: Jun Zhang
      ins: J. Zhang
    - name: Khaled B. Letaief
      ins: K. Letaief
    date: 2017-11
  Zhang:
    seriesinfo:
      2016 Fourth IEEE Workshop on Hot Topics in Web Systems and Technologies: "(HotWeb)"
      DOI: 10.1109/hotweb.2016.12
    title: 'Firework: Big Data Sharing and Processing in Collaborative Edge Environment'
    author:
    - name: Quan Zhang
      ins: Q. Zhang
    - name: Xiaohong Zhang
      ins: X. Zhang
    - name: Qingyang Zhang
      ins: Q. Zhang
    - name: Weisong Shi
      ins: W. Shi
    - name: Hong Zhong
      ins: H. Zhong
    date: 2016-10
  Basudan:
    seriesinfo:
      IEEE Internet of Things Journal: vol. 4, no. 3, pp. 772-782
      DOI: 10.1109/jiot.2017.2666783
    title: A Privacy-Preserving Vehicular Crowdsensing-Based Road Surface Condition
      Monitoring System Using Fog Computing
    author:
    - name: Sultan Basudan
      ins: S. Basudan
    - name: Xiaodong Lin
      ins: X. Lin
    - name: Karthik Sankaranarayanan
      ins: K. Sankaranarayanan
    date: 2017-06
  Renart:
    seriesinfo:
      2017 IEEE 1st International Conference on Fog and Edge Computing: "(ICFEC)"
      DOI: 10.1109/icfec.2017.18
    title: Data-Driven Stream Processing at the Edge
    author:
    - name: Eduard Gibert Renart
      ins: E. Renart
    - name: Javier Diaz-Montes
      ins: J. Diaz-Montes
    - name: Manish Parashar
      ins: M. Parashar
    date: 2017-05
  Zhang2:
    seriesinfo:
      IEEE Access: vol. 6, pp. 18209-18237
      DOI: 10.1109/access.2018.2820162
    title: 'Data Security and Privacy-Preserving in Edge Computing Paradigm: Survey
      and Open Issues'
    author:
    - name: Jiale Zhang
      ins: J. Zhang
    - name: Bing Chen
      ins: B. Chen
    - name: Yanchao Zhao
      ins: Y. Zhao
    - name: Xiang Cheng
      ins: X. Cheng
    - name: Feng Hu
      ins: F. Hu
    date: '2018'
  Yates:
    seriesinfo:
      IEEE Transactions on Information Theory: vol. 65, no. 3, pp. 1807-1827
      DOI: 10.1109/tit.2018.2871079
    title: 'The Age of Information: Real-Time Status Updating by Multiple Sources'
    author:
    - name: Roy D. Yates
      ins: R. Yates
    - name: Sanjit K. Kaul
      ins: S. Kaul
    date: 2019-03
  Khan:
    seriesinfo:
      IEEE Internet of Things Journal: vol. 7, no. 10, pp. 10200-10232
      DOI: 10.1109/jiot.2020.2987070
    title: 'Edge-Computing-Enabled Smart Cities: A Comprehensive Survey'
    author:
    - name: Latif U. Khan
      ins: L. Khan
    - name: Ibrar Yaqoob
      ins: I. Yaqoob
    - name: Nguyen H. Tran
      ins: N. Tran
    - name: S. M. Ahsan Kazmi
      ins: S. Kazmi
    - name: Tri Nguyen Dang
      ins: T. Dang
    - name: Choong Seon Hong
      ins: C. Hong
    date: 2020-10
  RFC7390:
  I-D.ietf-core-groupcomm-bis:
  Murshed:
    seriesinfo:
      ACM Computing Surveys: vol. 54, no. 8, pp. 1-37
      DOI: 10.1145/3469029
    title: 'Machine Learning at the Network Edge: A Survey'
    author:
    - name: M. G. Sarwar Murshed
      ins: M. Murshed
    - name: Christopher Murphy
      ins: C. Murphy
    - name: Daqing Hou
      ins: D. Hou
    - name: Nazar Khan
      ins: N. Khan
    - name: Ganesh Ananthanarayanan
      ins: G. Ananthanarayanan
    - name: Faraz Hussain
      ins: F. Hussain
    date: '2022-11-30'
  I-D.sarathchandra-coin-appcentres:
  I-D.defoy-t2trg-iot-edge-computing-background:
  Senel:
    seriesinfo:
      Proceedings of the 4th International Workshop on Edge Systems, Analytics and: Networking
      DOI: 10.1145/3434770.3459737
    title: 'EdgeNet: A Multi-Tenant and Multi-Provider Edge Cloud'
    author:
    - name: Berat Can Senel
      ins: B. Senel
    - name: Maxime Mouchet
      ins: M. Mouchet
    - name: Justin Cappos
      ins: J. Cappos
    - name: Olivier Fourmaux
      ins: O. Fourmaux
    - name: Timur Friedman
      ins: T. Friedman
    - name: Rick McGeer
      ins: R. McGeer
    date: '2021-04-26'
  Stanciu:
    seriesinfo:
      Proceedings of the 4th International Workshop on Edge Systems, Analytics and: Networking
      DOI: 10.1145/3434770.3459735
    title: Privacy-Preserving Crowd-Monitoring Using Bloom Filters and Homomorphic Encryption
    author:
    - name: Valeriu-Daniel Stanciu
      ins: V. Stanciu
    - name: Maarten van Steen
      ins: M. Steen
    - name: Ciprian Dobre
      ins: C. Dobre
    - name: Andreas Peter
      ins: A. Peter
    date: '2021-04-26'
  Jeffery:
    seriesinfo:
      Proceedings of the 4th International Workshop on Edge Systems, Analytics and: Networking
      DOI: 10.1145/3434770.3459730
    title: Rearchitecting Kubernetes for the Edge
    author:
    - name: Andrew Jeffery
      ins: A. Jeffery
    - name: Heidi Howard
      ins: H. Howard
    - name: Richard Mortier
      ins: R. Mortier
    date: '2021-04-26'
  Nieke:
    seriesinfo:
      Proceedings of the 4th International Workshop on Edge Systems, Analytics and: Networking
      DOI: 10.1145/3434770.3459731
    title: 'Edgedancer: Secure Mobile WebAssembly Services on the Edge'
    author:
    - name: Manuel Nieke
      ins: M. Nieke
    - name: Lennart Almstedt
      ins: L. Almstedt
    - name: Rudiger Kapitza
      ins: R. Kapitza
    date: '2021-04-26'
  Cao:
    seriesinfo:
      Proceedings of the 4th International Workshop on Edge Systems, Analytics and: Networking
      DOI: 10.1145/3434770.3459741
    title: 'eCaaS: A Management Framework of Edge Container as a Service for Business
      Workload'
    author:
    - name: Lianjie Cao
      ins: L. Cao
    - name: Anu Merican
      ins: A. Merican
    - name: Diman Zad Tootaghaj
      ins: D. Tootaghaj
    - name: Faraz Ahmed
      ins: F. Ahmed
    - name: Puneet Sharma
      ins: P. Sharma
    - name: Vinay Saxena
      ins: V. Saxena
    date: '2021-04-26'
  Larrea:
    seriesinfo:
      Proceedings of the Third ACM International Workshop on Edge Systems, Analytics and: Networking
      DOI: 10.1145/3378679.3394537
    title: The serverkernel operating system
    author:
    - name: Jon Larrea
      ins: J. Larrea
    - name: Antonio Barbalace
      ins: A. Barbalace
    date: '2020-04-27'
  Mortazavi:
    # DOI not found for this paper
    title: 'Toward Session Consistency for the Edge'
    author:
    - ins: S. Hossein Mortazavi
    - ins: B. Balasubramanian
    - ins: E. de Lara
    - ins: S. P. Narayanan
    date: '2018'
    rc: 'USENIX, Workshop on Hot Topics in Edge Computing (HotEdge 18)'
    target: 'https://www.usenix.org/conference/hotedge18/presentation/mortazavi'
  oneM2M-TR0001:
    title: 'TR 0001, Use Cases Collection'
    author:
    - ins: C. Mladin
    date: 'Oct. 2018'
    rc: 'oneM2M'
    target: 'https://member.onem2m.org/Application/documentapp/downloadLatestRevision/default.aspx?docID=28153'
  oneM2M-TR0018:
    title: 'TR 0018, Industrial Domain Enablement'
    author:
    - ins: C. Lu
    - ins: M. Jiang
    date: 'Feb. 2019'
    rc: 'oneM2M'
    target: 'https://member.onem2m.org/Application/documentapp/downloadLatestRevision/default.aspx?docID=29334'
  oneM2M-TR0026:
    title: 'TR 0026, Vehicular Domain Enablement'
    author:
    - ins: K. Yamamoto
    - ins: C. Mladin
    - ins: V. Kueh
    date: 'Jan. 2020'
    rc: 'oneM2M'
    target: 'https://member.onem2m.org/Application/documentapp/downloadLatestRevision/default.aspx?docID=31410'
  oneM2M-TR0052:
    title: 'TR 0052, Study on Edge and Fog Computing in oneM2M systems'
    author:
    - ins: K. Yamamoto
    - ins: C. Mladin
    date: 'Sep. 2020'
    rc: 'oneM2M'
    target: 'https://member.onem2m.org/Application/documentapp/downloadLatestRevision/default.aspx?docID=32633'
  oneM2M-TS0002:
    title: 'TS 0002, Requirements'
    author:
    - ins: S. He
    date: 'Feb. 2019'
    rc: 'oneM2M'
    target: 'https://member.onem2m.org/Application/documentapp/downloadLatestRevision/default.aspx?docID=29274'
  Chen:
    seriesinfo:
      IEEE Communications Magazine: vol. 56, no. 9, pp. 103-109
      DOI: 10.1109/mcom.2018.1701231
    title: Edge Computing in IoT-Based Manufacturing
    author:
    - name: Baotong Chen
      ins: B. Chen
    - name: Jiafu Wan
      ins: J. Wan
    - name: Antonio Celesti
      ins: A. Celesti
    - name: Di Li
      ins: D. Li
    - name: Haider Abbas
      ins: H. Abbas
    - name: Qin Zhang
      ins: Q. Zhang
    date: 2018-09
  Jones:
    seriesinfo:
      CIRP Journal of Manufacturing Science and Technology: vol. 29, pp. 36-52
      DOI: 10.1016/j.cirpj.2020.02.002
    title: 'Characterising the Digital Twin: A systematic literature review'
    author:
    - name: David Jones
      ins: D. Jones
    - name: Chris Snider
      ins: C. Snider
    - name: Aydin Nassehi
      ins: A. Nassehi
    - name: Jason Yon
      ins: J. Yon
    - name: Ben Hicks
      ins: B. Hicks
    date: 2020-05
  RFC7252:
  Cloudlets:
    seriesinfo:
      IEEE Pervasive Computing: vol. 8, no. 4, pp. 14-23
      DOI: 10.1109/mprv.2009.82
    title: The Case for VM-Based Cloudlets in Mobile Computing
    author:
    - name: M. Satyanarayanan
      ins: M. Satyanarayanan
    - name: P. Bahl
      ins: P. Bahl
    - name: R. Caceres
      ins: R. Caceres
    - name: N. Davies
      ins: N. Davies
    date: 2009-10
  ETSI_MEC_33:
    title: 'Multi-access Edge Computing (MEC); IoT API'
    author:
    - org: ETSI
    date: '2022'
    rc: 'ETSI GS MEC 033'
    target: 'https://www.etsi.org/deliver/etsi_gs/MEC/001_099/033/03.01.01_60/gs_MEC033v030101p.pdf'
  Madni:
    seriesinfo:
      Systems 7, no. 1: 7
      DOI: 10.3390/systems7010007
    title: Leveraging digital twin technology in model-based systems engineering
    author:
    - name: Azad M. Madni
      ins: A.M. Madni
    - name: Carla C. Madni
      ins: C. Madni
    - name: Scott D. Lucero
      ins: S.D. Lucero
    date: 2019
  I-D.irtf-nmrg-network-digital-twin-arch:
  I-D.hsingh-coinrg-reqs-p4comp:
  Farnbauer-Schmidt:
    seriesinfo:
      INFORMATIK 2019: 50 Jahre Gesellschaft fur Informatik - Informatik fur Gesellschaft, pp. 139-152
      DOI: 10.18420/inf2019_19
    title: 'Combining the Concepts of Semantic Data Integration and Edge Computing'
    author:
    - name: Matthias Farnbauer-Schmidt
      ins: M. Farnbauer-Schmidt
    - name: Julian Lindner
      ins: J. Lindner
    - name: Christopher Kaffenberger
      ins: C. Kaffenberger
    - name: Jens Albrecht
      ins: J. Albrecht
    date: 2019
  Brecko:
    seriesinfo:
      Applied Sciences 12, no. 18: 9124
      DOI: 10.3390/app12189124
    title: 'Federated Learning for Edge Computing: A Survey'
    author:
    - name: Alexander Brecko
      ins: A. Brecko
    - name: Erik Kajati
      ins: E. Kajati
    - name: Jiri Koziorek
      ins: J. Koziorek
    - name: Iveta Zolotova
      ins: I. Zolotova
    date: 2022
  Grewe:
    seriesinfo:
      Proceedings of the Workshop on Mobile Edge Communications: pp. 7-12
      DOI: 10.1145/3098208.3098210
    title: 'Information-Centric Mobile Edge Computing for Connected Vehicle Environments: Challenges and Research Directions'
    author:
    - name: Dennis Grewe
      ins: D. Grewe
    - name: Marco Wagner
      ins: M. Wagner
    - name: Mayutan Arumaithurai
      ins: M. Arumaithurai
    - name: Ioannis Psaras
      ins: I. Psaras
    - name: Dirk Kutscher
      ins: D. Kutscher
    date: 2017
  Ali:
    seriesinfo:
      IEEE Internet of Things Magazine: pp. 24-29
      DOI: 10.1109/IOTM.2019.1800024
    title: 'Enabling a Blockchain-Based IoT Edge'
    author:
    - name: Muhammad Salek Ali
      ins: M.S. Ali
    - name: Massimo Vecchio
      ins: M. Vecchio
    - name: Fabio Antonelli
      ins: F. Antonelli
    date: 2018
  chipmunk: DOI.10.1145/3405656.3420231
  kua: DOI.10.1145/3517212.3558083
  mqtt5:
    title: 'MQTT Version 5.0'
    author:
    - ins: OASIS Message Queuing Telemetry Transport (MQTT) TC
    date: 'March 2019'
    rc: 'OASIS'
    target: 'https://docs.oasis-open.org/mqtt/mqtt/v5.0/mqtt-v5.0.html'


--- abstract

Many Internet of Things (IoT) applications have requirements that cannot be satisfied by traditional cloud-based systems (i.e., cloud computing). These include time sensitivity, data volume, connectivity cost, operation in the face of intermittent services, privacy, and security. As a result, IoT is driving the Internet toward edge computing. This document outlines the requirements of the emerging IoT Edge and its challenges. It presents a general model and major components of the IoT Edge to provide a common basis for future discussions in the T2TRG and other IRTF and IETF groups. This document is a product of the IRTF Thing-to-Thing Research Group (T2TRG).

--- middle

# Introduction

Currently, many IoT services leverage cloud computing platforms, because they provide virtually unlimited storage and processing power. The reliance of IoT on back-end cloud computing provides additional advantages such as scalability and efficiency.  Today's IoT systems are fairly static with respect to integrating and supporting computation.  It is not that there is no computation, but that systems are often limited to static configurations (edge gateways and cloud services).

However, IoT devices generate large amounts of data at the edges of the network. To meet IoT use case requirements, data is increasingly being stored, processed, analyzed, and acted upon close to the data sources. These requirements include time sensitivity, data volume, connectivity cost, and resiliency in the presence of intermittent connectivity, privacy, and security, which cannot be addressed by centralized cloud computing. A more flexible approach is necessary to address these needs effectively. This involves distributing computing (and storage) and seamlessly integrating it into the edge-cloud continuum. We refer to this integration of edge computing and IoT as "IoT edge computing". This draft describes the related background, use cases, challenges, system models, and functional components.

Owing to the dynamic nature of the IoT edge computing landscape, this document does not list existing projects in this field. {{sec-overview}} presents a high-level overview of the field, based on a limited review of standards, research, open-source and proprietary products in {{I-D.defoy-t2trg-iot-edge-computing-background}}.

This document represents the consensus of the Thing-to-Thing Research Group (T2TRG). It has been reviewed extensively by the Research Group (RG) members who are actively involved in the research and development of the technology covered by this document. It is not an IETF product and is not a standard.

# Background

## Internet of Things (IoT)

Since the term "Internet of Things" (IoT) was coined by Kevin Ashton in 1999 working on Radio-Frequency Identification (RFID) technology {{Ashton}}, the concept of IoT has evolved. It now reflects a vision of connecting the physical world to the virtual world of computers using (often wireless) networks over which things can send and receive information without human intervention.  Recently, the term has become more literal by connecting things to the Internet and converging on Internet and Web technologies.

A Thing is a physical item made available in the IoT, thereby enabling digital interaction with the physical world for humans, services, and/or other Things ({{I-D.irtf-t2trg-rest-iot}}). In this document we will use the term "IoT device" to designate the embedded system attached to the Thing.

Resource-constrained Things such as sensors, home appliances and wearable devices often have limited storage and processing power, which can provide challenges with respect to reliability, performance, energy consumption, security, and privacy {{Lin}}. Some, less resource-constrained Things, can generate a voluminous amount of data. This range of factors led IoT designs that integrate Things into larger distributed systems, for example edge or cloud computing systems.

## Cloud Computing

Cloud computing has been defined in {{NIST}}: "cloud computing is a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort or service provider interaction".  The low cost and massive availability of storage and processing power enabled the realization of another computing model, in which virtualized resources can be leased in an on-demand fashion and be provided as general utilities. Platform-as-a-Service and cloud computing platforms widely adopted this paradigm for delivering services over the Internet, gaining both economical and technical benefits {{Botta}}.

Today, an unprecedented volume and variety of data is generated by Things, and applications deployed at the network edge consume this data.  In this context, cloud-based service models are not suitable for some classes of applications which require very short response times, access to local personal data, or generate vast amounts of data.  These applications may instead leverage edge computing.

## Edge Computing

Edge computing, also referred to as fog computing in some settings, is a new paradigm in which substantial computing and storage resources are placed at the edge of the Internet, close to mobile devices, sensors, actuators, or machines.  Edge computing happens near data sources {{Mahadev}}, as well as close to where decisions are made or where interactions with the physical world take place ("close" here can refer to a distance which is topological, physical, latency-based, etc.).  It processes both downstream data (originating from cloud services) and upstream data (originating from end devices or network elements).  The term "fog computing" usually represents the notion of multi-tiered edge computing, that is, several layers of compute infrastructure between end devices and cloud services.

An edge device is any computing or networking resource residing between end-device data sources and cloud-based data centers.  In edge computing, end devices consume and produce data. At the network edge, devices not only request services and information from the Cloud but also handle computing tasks including processing, storage, caching, and load balancing on data sent to and from the Cloud {{Shi}}.  This does not preclude end devices from hosting computation themselves, when possible, independently or as part of a distributed edge computing platform.

Several standards developing organization (SDO) and industry forums have provided definitions of edge and fog computing:

* ISO defines edge computing as a "form of distributed computing in which significant processing and data storage takes place on nodes which are at the edge of the network" {{ISO_TR}}.
* ETSI defines multi-access edge computing as a "system which provides an IT service environment and cloud-computing capabilities at the edge of an access network which contains one or more type of access technology, and in close proximity to its users" {{ETSI_MEC_01}}.
* The Industry IoT Consortium (IIC, now incorporating what was formerly OpenFog) defines fog computing as "a horizontal, system-level architecture that distributes computing, storage, control and networking functions closer to the users along a cloud-to-thing continuum" {{OpenFog}}.

Based on these definitions, we can summarize a general philosophy of edge computing as distributing the required functions close to users and data, while the difference to classic local systems is the usage of management and orchestration features adopted from cloud computing.

Actors from various industries approach edge computing using different terms and reference models although, in practice, these approaches are not incompatible and may integrate with each other:

* The telecommunication industry tends to use a model where edge computing services are deployed over Network Function Virtualization (NFV) infrastructure, at aggregation points or in proximity to the user equipment (e.g., gNodeBs) {{ETSI_MEC_03}}.
* Enterprise and campus solutions often interpret edge computing as an "edge cloud", that is, a smaller data center directly connected to the local network (often referred to as "on-premise").
* The automation industry defines the edge as the connection point between IT and OT (Operational Technology). Hence, edge computing sometimes refers to applying IT solutions to OT problems, such as analytics, more flexible user interfaces, or simply having more computing power than an automation controller.

## Examples of IoT Edge Computing Use Cases {#sec-uc}

IoT edge computing can be used in home, industry, grid, healthcare, city, transportation, agriculture, and/or educational scenarios. Here, we discuss only a few examples of such use cases, to identify differentiating requirements, providing references to other use cases.

**Smart Factory**

As part of the 4th industrial revolution, smart factories run real-time processes based on IT technologies, such as artificial intelligence and big data. Even a very small environmental change in a smart factory can lead to a situation in which production efficiency decreases or product quality problems occur. Therefore, simple but time-sensitive processing can be performed at the edge, for example, controlling the temperature and humidity in the factory, or operating machines based on the real-time collection of the operational status of each machine. However, data requiring highly precise analysis, such as machine lifecycle management or accident risk prediction, can be transferred to a central data center for processing.

The use of edge computing in a smart factory can reduce the cost of network and storage resources by reducing the communication load to the central data center or server. It is also possible to improve process efficiency and facility asset productivity through real-time prediction of failures and to reduce the cost of failure through preliminary measures. In the existing manufacturing field, production facilities are manually run according to a program entered in advance; however, edge computing in a smart factory enables tailoring solutions by analyzing data at each production facility and machine level. Digital twins {{Jones}} of IoT devices have been jointly used with edge computing in industrial IoT scenarios {{Chen}}.

**Smart Grid**

In future smart city scenarios, the Smart Grid will be critical in ensuring highly available/efficient energy control in city-wide electricity management.  Edge computing is expected to play a significant role in these systems to improve the transmission efficiency of electricity, to react to, and restore power after a disturbance, to reduce operation costs, and to reuse energy effectively, since these operations involve local decision-making. In addition, edge computing can help monitor power generation and power demand, and make local electrical energy storage decisions in smart grid systems.

**Smart Agriculture**

Smart agriculture integrates information and communication technologies with farming technology. Intelligent farms use IoT technology to measure and analyze parameters, such as the temperature, humidity, sunlight, carbon dioxide, and soil quality, in crop cultivation facilities. Depending on the analysis results, control devices are used to set the environmental parameters to an appropriate state. Remote management is also possible through mobile devices such as smartphones.

In existing farms, simple systems such as management according to temperature and humidity can be easily and inexpensively implemented using IoT technology. Field sensors gather data on field and crop condition. This data is then transmitted to cloud servers that process data and recommend actions. The use of edge computing can reduce the volume of back-and-forth data transmissions significantly, resulting in cost and bandwidth savings. Locally generated data can be processed at the edge, and local computing and analytics can drive local actions. With edge computing, it is easy for farmers to select large amounts of data for processing, and data can be analyzed even in remote areas with poor access conditions. Other applications include enabling dashboarding, for example, to visualize the farm status, as well as enhancing Extended Reality (XR) applications that require edge audio/video processing. As the number of people working on farming has been decreasing over time, increasing automation enabled by edge computing can be a driving force for future smart agriculture.

**Smart Construction**

Safety is critical at construction sites. Every year, many construction workers lose their lives because of falls, collisions, electric shocks, and other accidents.  Therefore, solutions have been developed to improve construction site safety, including the real-time identification of workers, monitoring of equipment location, and predictive accident prevention. To deploy these solutions, many cameras and IoT sensors have been installed on construction sites, to measure noise, vibration, gas concentration, etc. Typically, the data generated from these measurements is collected in on-site gateways and sent to remote cloud servers for storage and analysis. Thus, an inspector can check the information stored on the cloud server to investigate an incident. However, this approach can be expensive because of transmission costs, for example, of video streams over a mobile network connection, and because usage fees of private cloud services.

Using edge computing, data generated at the construction site can be processed and analyzed on an edge server located within or near the site. Only the result of this processing needs to be transferred to a cloud server, thus reducing transmission costs. It is also possible to locally generate warnings to prevent accidents in real-time.

**Self-Driving Car**

Edge computing plays a crucial role in safety-focused self-driving car systems. With a multitude of sensors, such as high-resolution cameras, radar, LIDAR, sonar sensors, and GPS systems, autonomous vehicles generate vast amounts of real-time data. Local processing utilizing edge computing nodes allows for efficient collection and analysis of this data to monitor vehicle distances and road conditions and respond promptly to unexpected situations. Roadside computing nodes can also be leveraged to offload tasks when necessary, for example, when the local processing capacity of the car is insufficient because of hardware constraints or a large data volume.

For instance, when the car ahead slows, a self-driving car adjusts its speed to maintain a safe distance, or when a roadside signal changes, it adapts its behavior accordingly. In another example, cars equipped with self-parking features utilize local processing to analyze sensor data, determine suitable parking spots, and execute precise parking maneuvers without relying on external processing or connectivity. It is also possible to use in-cabin cameras coupled with local processing to monitor the driver's attention level and detect signs of drowsiness or distraction. The system can issue warnings or implement preventive measures to ensure driver safety.

Edge computing empowers self-driving cars by enabling real-time processing, reducing latency, enhancing data privacy, and optimizing bandwidth usage. By leveraging local processing capabilities, self-driving cars can make rapid decisions, adapt to changing environments, and ensure safer and more efficient autonomous driving experiences.

**Digital Twin**

A digital twin can simulate different scenarios and predict outcomes based on real-time data collected from the physical environment. This simulation capability empowers proactive maintenance, optimization of operations, and the prediction of potential issues or failures. Decision makers can use digital twins to test and validate different strategies, identify inefficiencies, and optimize performance.

With edge computing, real-time data is collected, processed, and analyzed directly at the edge, allowing for the accurate monitoring and simulation of physical assets. Moreover, edge computing effectively minimizes latency, enabling rapid responses to dynamic conditions as computational resources are brought closer to the physical object. Running digital twin processing at the edge enables organizations to obtain timely insights and make informed decisions that maximize efficiency and performance.

**Other Use Cases**

AI/ML systems at the edge empower real-time analysis, faster decision-making, reduced latency, improved operational efficiency, and personalized experiences across various industries, by bringing artificial intelligence and machine learning capabilities closer to edge devices.

In addition, oneM2M has studied several IoT edge computing use cases, which are documented in {{oneM2M-TR0001}}, {{oneM2M-TR0018}} and {{oneM2M-TR0026}}. The edge computing related requirements raised through the analysis of these use cases are captured in {{oneM2M-TS0002}}.

# IoT Challenges Leading Towards Edge Computing {#sec-challenges}

This section describes the challenges faced by IoT that are motivating the adoption of edge computing. These are distinct from the research challenges applicable to IoT edge computing, some of which are mentioned in {{sec-functions}}.

IoT technology is used with increasingly demanding applications, for example, in industrial, automotive and healthcare domains, leading to new challenges.  For example, industrial machines such as laser cutters produce over 1 terabyte of data per hour, and similar amounts can be generated in autonomous cars {{NVIDIA}}.  90% of IoT data is expected to be stored, processed, analyzed, and acted upon close to the source {{Kelly}}, as cloud computing models alone cannot address these new challenges {{Chiang}}.

Below, we discuss IoT use case requirements that are moving cloud capabilities to be more proximate, distributed, and disaggregated.

## Time Sensitivity

Many industrial control systems, such as manufacturing systems, smart grids, and oil and gas systems often require stringent end-to-end latency between the sensor and control nodes.  While some IoT applications may require latency below a few tens of milliseconds {{Weiner}}, industrial robots and motion control systems have use cases for cycle times in the order of microseconds {{_60802}}.  In some cases, speed-of-light limitations may simply prevent a cloud-based solutions; however, this is not the only challenge relative to time sensitivity.  Guarantees for bounded latency and jitter ({{RFC8578}} section 7) are also important for industrial IoT applications.  This means that control packets must arrive with as little variation as possible and within a strict deadline.  Given the best-effort characteristics of the Internet, this challenge is virtually impossible to address, without using end-to-end guarantees for individual message delivery and continuous data flows.

## Connectivity Cost

Some IoT deployments may not face bandwidth constraints when uploading data to the Cloud.  5G and Wi-Fi 6 networks both theoretically top out at 10 gigabits per second (i.e., 4.5 terabytes per hour), allowing to transfer large amounts of uplink data.  However, the cost of maintaining continuous high-bandwidth connectivity for such usage is unjustifiable and impractical for most IoT applications.  In some settings, for example, in aeronautical communication, higher communication costs reduce the amount of data that can be practically uploaded even further.  Minimizing reliance on high-bandwidth connectivity is therefore a requirement, for example, by processing data at the edge and deriving summarized or actionable insights that can be transmitted to the Cloud.

## Resilience to Intermittent Services

Many IoT devices, such as sensors, actuators, and controllers, have very limited hardware resources and cannot rely solely on their own resources to meet their computing and/or storage needs.  They require reliable, uninterrupted, or resilient services to augment their capabilities to fulfill their application tasks.  This is difficult and partly impossible to achieve using cloud services for systems such as vehicles, drones, or oil rigs that have intermittent network connectivity.  Conversely, a cloud back-end might want to device data even if it is currently asleep.

## Privacy and Security {#sec-priv}

When IoT services are deployed at home, personal information can be learned from detected usage data.  For example, one can extract information about employment, family status, age, and income by analyzing smart-meter data {{ENERGY}}.  Policy makers have begun to provide frameworks that limit the usage of personal data and impose strict requirements on data controllers and processors.  Data stored indefinitely in the Cloud also increases the risk of data leakage, for instance, through attacks on rich targets.

It is often argues that industrial systems do not provide privacy implications, as no personal data is gathered.  However, data from such systems is often highly sensitive, as one might be able to infer trade secrets such as the setup of production lines.  Hence, owners of these systems are generally reluctant to upload IoT data to the Cloud.

Furthermore, passive observers can perform traffic analysis on device-to-cloud paths.  Therefore, hiding traffic patterns associated with sensor networks can be another requirement for edge computing.

# IoT Edge Computing Functions {#sec-functions}

We first look at the current state of IoT edge computing ({{sec-overview}}), and then define a general system model ({{sec-model}}). This provides a context for IoT edge-computing functions, which are listed in {{sec-components-oam}}, {{sec-components-functional}} and {{sec-components-app}}.

## Overview of IoT Edge Computing Today {#sec-overview}

This section provides an overview of today's IoT edge computing field based on a limited review of standards, research, open-source and proprietary products in {{I-D.defoy-t2trg-iot-edge-computing-background}}.

IoT gateways, both open-source (such as EdgeX Foundry or Home Edge) and proprietary products, represent a common class of IoT edge-computing products, where the gateway provides a local service on customer premises and is remotely managed through a cloud service. IoT communication protocols are typically used between IoT devices and the gateway, including CoAP {{RFC7252}}, MQTT {{mqtt5}}, and many specialized IoT protocols (such as OPC UA and DDS in the Industrial IoT space), while the gateway communicates with the distant cloud typically using HTTPS. Virtualization platforms enable the deployment of virtual edge computing functions (using VMs and application containers), including IoT gateway software, on servers in the mobile network infrastructure (at base stations and concentration points), edge data centers (in central offices), and regional data centers located near central offices. End devices are envisioned to become computing devices in forward-looking projects, but are not commonly used today.

In addition to open-source and proprietary solutions, a horizontal IoT service layer is standardized by the oneM2M standards body to reduce fragmentation, increase interoperability and promote reuse in the IoT ecosystem. Furthermore, ETSI MEC developed an IoT API {{ETSI_MEC_33}} that enables the deployment of heterogeneous IoT platforms and provides a means to configure the various components of an IoT system.

Physical or virtual IoT gateways can host application programs that are typically built using an SDK to access local services through a programmatic API.  Edge cloud system operators host their customers' application VMs or containers on servers located in or near access networks that can implement local edge services. For example, mobile networks can provide edge services for radio-network information, location, and bandwidth management.

Resilience in the IoT can entail the ability to operate autonomously in periods of disconnectedness to preserve the integrity and safety of the controlled system, possibly in a degraded mode. IoT devices and gateways are often expected to operate in always-on and unattended modes, using fault detection and unassisted recovery functions.

The life cycle management of services and applications on physical IoT gateways is generally cloud-based.  Edge cloud management platforms and products (such as StarlingX, Akraino Edge Stack, or proprietary products from major Cloud providers) adapt cloud management technologies (e.g., Kubernetes) to the edge cloud, that is, to smaller, distributed computing devices running outside a controlled data center. The service and application life-cycle is typically using an NFV-like management and orchestration model.

The platform typically enables advertising or consuming services hosted on the platform (e.g., the Mp1 interface in ETSI MEC supports service discovery and communication), and enables communication with local and remote endpoints (e.g., message routing function in IoT gateways).  The platform is typically extensible to edge applications because it can advertise a service that other edge applications can consume. The IoT communication services include protocol translation, analytics, and transcoding.  Communication between edge-computing devices is enabled in tiered or distributed deployments.

An edge cloud platform may enable pass-through without storage or local storage (e.g., on IoT gateways). Some edge cloud platforms use distributed storage such as that provided by a distributed storage platform (e.g., EdgeFS, Ceph), or, in more experimental settings, by an ICN network, for example, systems such as Chipmunk {{chipmunk}} and Kua {{kua}} have been proposed as distributed information-centric objects stores.  External storage, for example, on databases in distant or local IT cloud, is typically used for filtered data deemed worthy of long-term storage, although in some cases it may be for all data, for example when required for regulatory reasons.

Stateful computing is supported on platforms that host native programs, VMs, or containers. Stateless computing is supported on platforms providing a "serverless computing" service (also known as function-as-a-service, e.g., using stateless containers), or on systems based on named function networking.

In many IoT use cases, a typical network usage pattern is a high volume uplink with some form of traffic reduction enabled by processing over edge-computing devices. Alternatives to traffic reduction include deferred transmission (to off-peak hours or using physical shipping). Downlink traffic includes application control and software updates. Downlink-heavy traffic patterns are not excluded but are more often associated with non-IoT usage (e.g., video CDNs).

## General Model {#sec-model}

Edge computing is expected to play an important role in deploying new IoT services integrated with Big Data and AI enabled by flexible in-network computing platforms. Although there are many approaches to edge computing, in this section, we attempt to lay out a general model and the list associated logical functions. In practice, this model can be mapped to different architectures, such as:

- A single IoT gateway, or a hierarchy of IoT gateways, typically connected to the cloud (e.g., to extend the traditional cloud-based management of IoT devices and data to the edge). The IoT gateway plays a common role in providing access to a heterogeneous set of IoT devices/sensors, handling IoT data, and delivering IoT data to its final destination in a cloud network. Whereas an IoT gateway requires interactions with the cloud, it can also operate independently in a disconnected mode.
- A set of distributed computing nodes, for example, embedded in switches, routers, edge cloud servers, or mobile devices. Some IoT devices have sufficient computing capabilities to participate in such distributed systems owing to advances in hardware technology. In this model, edge-computing nodes can collaborate to share resources.
- A hybrid system involving both IoT gateways and supporting functions in distributed computing nodes.

In the general model described in {{rl-fig1}}, the edge computing domain is interconnected with IoT devices (southbound connectivity), possibly with a remote/cloud network (northbound connectivity), and with a service operator's system.  Edge-computing nodes provide multiple logical functions or components that may not be present in a given system. They may be implemented in a centralized or distributed fashion, at the network edge, or through interworking between the edge network and remote cloud networks.

~~~~~~~~~~~~~~~~~~~ aasvg
   +---------------------+
   |   Remote network    |  +---------------+
   |(e.g., cloud network)|  |   Service     |
   +-----------+---------+  |   Operator    |
               |            +------+--------+
               |                   |
+--------------+-------------------+-----------+
|            Edge Computing Domain             |
|                                              |
|   One or more Computing Nodes                |
|   (IoT gateway, end devices, switches,       |
|   routers, mini/micro-data centers, etc.)    |
|                                              |
|   OAM Components                             |
|   - Resource Discovery and Authentication    |
|   - Edge Organization and Federation         |
|   - Multi-Tenancy and Isolation              |
|   - ...                                      |
|                                              |
|   Functional Components                      |
|   - In-Network Computation                   |
|   - Edge Caching                             |
|   - Communication                            |
|   - Other Services                           |
|   - ...                                      |
|                                              |
|   Application Components                     |
|   - IoT Devices Management                   |
|   - Data Management and Analytics            |
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

In the distributed model described in {{rl-fig2}}, the edge-computing domain is composed of IoT edge gateways and IoT devices which are also used as computing nodes.  Edge computing domains are connected to a remote/cloud network and their respective service operator's system. IoT devices/computing nodes provide logical functions, for example as part of distributed machine learning or distributed image processing applications. The processing capabilities in IoT devices are limited; they require the support of other nodes, and in a distributed machine learning application, the training process for AI services can be executed at IoT edge gateways or cloud networks and the prediction (inference) service is executed in the IoT devices. In a distributed image processing application, some image processing functions can be similarly executed at the edge or in the cloud, while preprocessing, which helps limiting the amount of uploaded data, is performed by the IoT device.

~~~~~~~~~~~~~~~~~~~ aasvg
+----------------------------------------------+
|            Edge Computing Domain             |
|                                              |
| +--------+    +--------+        +--------+   |
| |Compute |    |Compute |        |Compute |   |
| |node/End|    |node/End|  ....  |node/End|   |
| |device 1|    |device 2|  ....  |device m|   |
| +----+---+    +----+---+        +----+---+   |
|      |             |                 |       |
|  +---+-------------+-----------------+--+    |
|  |           IoT Edge Gateway           |    |
|  +-----------+-------------------+------+    |
|              |                   |           |
+--------------+-------------------+-----------+
               |                   |
   +-----------+---------+  +------+-------+
   |   Remote network    |  |   Service    |
   |(e.g., cloud network)|  |  Operator(s) |
   +-----------+---------+  +------+-------+
               |                   |
+--------------+-------------------+-----------+
|              |                   |           |
|  +-----------+-------------------+------+    |
|  |           IoT Edge Gateway           |    |
|  +---+-------------+-----------------+--+    |
|      |             |                 |       |
| +----+---+    +----+---+        +----+---+   |
| |Compute |    |Compute |        |Compute |   |
| |node/End|    |node/End|  ....  |node/End|   |
| |device 1|    |device 2|  ....  |device n|   |
| +--------+    +--------+        +--------+   |
|                                              |
|            Edge Computing Domain             |
+----------------------------------------------+
~~~~~~~~~~~~~~~~~~~
{: artwork-align="center" #rl-fig2 title="Example: Machine Learning over a Distributed IoT Edge Computing System"}

In the following, we enumerate major edge computing domain components. They are here loosely organized into OAM (Operations, Administration, and Maintenance), functional, and application components, with the understanding that the distinction between these classes may not always be clear, depending on actual system architectures. Some representative research challenges are associated with those functions. We used input from co-authors, IRTF attendees, and some comprehensive reviews of the field ({{Yousefpour}}, {{Zhang2}}, {{Khan}}).

## OAM Components {#sec-components-oam}

Edge computing OAM extends beyond the network-related OAM functions listed in {{RFC6291}}. In addition to infrastructure (network, storage, and computing resources), edge computing systems can also include computing environments (for VMs, software containers, functions), IoT devices, data, and code.

Operation-related functions include performance monitoring for service-level agreement measurements, fault management and provisioning for links, nodes, compute and storage resources, platforms, and services. Administration covers network/compute/storage resources, platforms and services discovery, configuration, and planning. Discovery during normal operation (e.g., discovery of compute or storage nodes by endpoints) is typically not included in OAM; however, in this document, we do not address it separately. Management covers the monitoring and diagnostics of failures, as well as means to minimize their occurrence and take corrective actions. This may include software update management and high service availability through redundancy and multipath communication. Centralized (e.g., SDN) and decentralized management systems can be used. Finally, we arbitrarily chose to address data management as an application component, however, in some systems, data management may be considered similar to a network management function.

We further detail a few relevant OAM components.

### Resource Discovery and Authentication {#sec-dis-auth}

Discovery and authentication may target platforms and , infrastructure resources, such as computing, networking, and storage, as well as other resources such as IoT devices, sensors, data, code units, services, applications, and users interacting with the system. Broker-based solutions can be used, for example, using an IoT gateway as a broker to discover IoT resources. More decentralized solutions can also be used in replacement or complement, for example, CoAP enables multicast discovery of an IoT device, and CoAP service discovery enables obtaining a list of resources made available by this device {{RFC7252}}. For device authentication, current centralized gateway-based systems rely on the installation of a secret on IoT devices and computing devices (e.g., a device certificate stored in a hardware security module, or a combination of code and data stored in a trusted execution environment).

Related challenges include:

* Discovery, authentication, and trust establishment between IoT devices, compute nodes, and platforms, with regard to concerns such as mobility, heterogeneous devices and networks, scale, multiple trust domains, constrained devices, anonymity, and traceability.
* Intermittent connectivity to the Internet, removing the need to rely on a third-party authority {{Echeverria}}.
* Resiliency to failure {{Harchol}}, denial of service attacks, easier physical access for attackers.

### Edge Organization and Federation

In a distributed system context, once edge devices have discovered and authenticated each other, they can be organized, or self-organized, into hierarchies or clusters. The organizational structure may range from centralized to peer-to-peer, or it may be closely tied to other systems. Such groups can also form federations with other edges or with remote clouds.

Related challenges include:

* Support for scaling, and enabling fault-tolerance or self-healing {{Jeong}}. In addition to using a hierarchical organization to cope with scaling, another available and possibly complementary mechanism is multicast ({{RFC7390}} {{I-D.ietf-core-groupcomm-bis}}). Other approaches include relying on blockchains {{Ali}}.
* Integration of edge computing with virtualized Radio Access Networks (Fog RAN) {{I-D.bernardos-sfc-fog-ran}} and 5G access networks.
* Sharing resources in multi-vendor/operator scenarios, to optimize criteria such as profit {{Anglano}}, resource usage, latency, and energy consumption.
* Capacity planning, placement of infrastructure nodes to minimize delay {{Fan}}, cost, energy, etc.
* Incentives for participation, for example, in peer-to-peer federation schemes.
* Design of federated AI over IoT edge computing systems {{Brecko}}, for example, for anomaly detection.

### Multi-Tenancy and Isolation

Some IoT edge computing systems make use of virtualized (compute, storage and networking) resources to address the need for secure multi-tenancy at the edge. This leads to "edge clouds" that share properties with remotes clouds and can reuse some of their ecosystems. Virtualization function management is largely covered by ETSI NFV and MEC standards and recommendations. Projects such as {{LFEDGE-EVE}} further cover virtualization and its management in distributed edge-computing settings.

Related challenges include:

* Adapting cloud management platforms to the edge, to account for its distributed nature, e.g., using Conflict-free Replicated Data Types (CRDT) {{Jeffery}}, heterogeneity and customization, e.g., using intent-based management mechanisms {{Cao}}, and limited resources.
* Minimizing virtual function instantiation time and resource usage.

## Functional Components {#sec-components-functional}

### In-Network Computation

A core function of IoT edge computing is to enable local computation on a node at the network edge, typically for application-layer processing, such as processing input data from sensors, making local decisions, preprocessing data, offloading computation on behalf of a device, service, or user. Related functions include orchestrating computation (in a centralized or distributed manner) and managing application lifecycles. Support for in-network computation may vary in terms of capability, for example, computing nodes can host virtual machines, software containers, software actors, uni-kernels running stateful or stateless code, or a rule engine providing an API to register actions in response to conditions such as IoT device ID, sensor values to check, thresholds, etc.

Edge offloading includes offloading to and from an IoT device, and to and from a network node. {{Cloudlets}} offer an example of offloading computation from an end device to a network node. In contrast, oneM2M is an example of a system that allows a cloud-based IoT platform to transfer resources and tasks to a target edge node {{oneM2M-TR0052}}. Once transferred, the edge node can directly support IoT devices that it serves with the service offloaded by the cloud (e.g., group management, location management, etc.).

QoS can be provided in some systems through the combination of network QoS (e.g., traffic engineering or wireless resource scheduling) and compute/storage resource allocations. For example, in some systems, a bandwidth manager service can be exposed to enable allocation of the bandwidth to/from an edge-computing application instance.

In-network computation can leverage the underlying services, provided using data generated by IoT devices and access networks. Such services include IoT device location, radio network information, bandwidth management and congestion management (e.g., the congestion management feature of oneM2M {{oneM2M-TR0052}}).

Related challenges include:

* (Computation placement) Selecting, in a centralized or distributed/peer-to-peer manner, an appropriate compute device based on available resources, location of data input and data sinks, compute node properties, etc., and with varying goals including end-to-end latency, privacy, high availability, energy conservation, or network efficiency, for example, using load-balancing techniques to avoid congestion.
* Onboarding code on a platform or computing device, and invoking remote code execution, possibly as part of a distributed programming model and with respect to similar concerns of latency, privacy, etc.: For example, offloading can be included in a vehicular scenario {{Grewe}}. These operations should deal with heterogeneous compute nodes {{Schafer}}, and may also support end devices, including IoT devices, as compute nodes {{Larrea}}.
* Adapting Quality of Results (QoR) for applications where a perfect result is not necessary {{Li}}.
* Assisted or automatic partitioning of code: for example, for application programs {{I-D.sarathchandra-coin-appcentres}} or network programs {{I-D.hsingh-coinrg-reqs-p4comp}}.
* Supporting computation across trust domains: for example, verifying computation results.
* Support for computation mobility: relocating an instance from one compute node to another, while maintaining a given service level; session continuity when communicating with end devices that are mobile, possibly at high speed (e.g., in vehicular scenarios); defining lightweight execution environments for secure code mobility, for example, using WebAssembly {{Nieke}}.
* Defining, managing, and verifying Service Level Agreements (SLA) for edge-computing systems: pricing is a challenging task.

### Edge Storage and Caching

Local storage or caching enables local data processing (e.g., preprocessing or analysis) as well as delayed data transfer to the cloud or delayed physical shipping.  An edge node may offer local data storage (in which persistence is subject to retention policies), caching, or both.  Caching generally refers to temporary storage to improve performance without persistence guarantees.  An edge-caching component manages data persistence, for example, it schedules the removal of data when it is no longer needed.  Other related aspects include the authentication and encryption of data.  Edge storage and caching can take the form of a distributed storage systems.

Related challenges include:

* (Cache and data placement) Using cache positioning and data placement strategies to minimize data retrieval delay {{Liu}} and energy consumption. Caches may be positioned in the access network infrastructure or on end devices.
* Maintaining consistency, freshness, reliability, and privacy of stored/cached data in systems that are distributed, constrained, and dynamic (e.g., owing to end devices and computing nodes churn or mobility), and which can have additional data governance constraints on data storage location. For example, {{Mortazavi}} leverages a hierarchical storage organization. Freshness-related metrics include the age of information {{Yates}} that captures the timeliness of information received from a sender (e.g., an IoT device).

### Communication

An edge cloud may provide a northbound data plane or management plane interface to a remote network, such as a cloud, home or enterprise network. This interface does not exist in stand-alone (local-only) scenarios. To support such an interface when it exists, an edge computing component needs to expose an API, deal with authentication and authorization, and support secure communication.

An edge cloud may provide an API or interface to local or mobile users, for example, to provide access to services and applications, or to manage data published by local/mobile devices.

Edge-computing nodes communicate with IoT devices over a southbound interface, typically for data acquisition and IoT device management.

Communication brokering is a typical function of IoT edge computing that facilitates communication with IoT devices, enabling clients to register as recipients for data from devices, as well as forwarding/routing of traffic to or from IoT devices, enabling various data discovery and redistribution patterns, for example, north-south with clouds, east-west with other edge devices {{I-D.mcbride-edge-data-discovery-overview}}.  Another related aspect is dispatching alerts and notifications to interested consumers both inside and outside the edge-computing domain.  Protocol translation, analytics, and video transcoding can also be performed when necessary. Communication brokering may be centralized in some systems, for example, using a hub-and-spoke message broker, or distributed with message buses, possibly in a layered bus approach.  Distributed systems can leverage direct communication between end devices over device-to-device links.  A broker can ensure communication reliability and traceability and, in some cases, transaction management.

Related challenges include:

* Defining edge computing abstractions, such as PaaS {{Yangui}}, suitable for users and cloud systems to interact with edge computing systems and dealing with interoperability issues such as data model heterogeneity.
* Enabling secure and resilient communication between IoT devices and remote cloud, for example, through multipath support.

## Application Components {#sec-components-app}

IoT edge computing can host applications, such as those mentioned in {{sec-uc}}. While describing the components of individual applications is out of our scope, some of those applications share similar functions, such as IoT device management and data management, as described below.

### IoT Device Management

IoT device management includes managing information regarding IoT devices, including their sensors, and how to communicate with them. Edge computing addresses the scalability challenges of a large number of IoT devices by separating the scalability domain into edge/local networks and remote networks. For example, in the context of the oneM2M standard, a device management functionality (called "software campaign" in oneM2M) enables the installation, deletion, activation, and deactivation of software functions/services on a potentially large number of edge nodes {{oneM2M-TR0052}}. Using a dashboard or management software, a service provider issues these requests through an IoT cloud platform supporting the software campaign functionality.

Challenges listed in {{sec-dis-auth}} may be applicable to IoT devices management as well.

### Data Management and Analytics {#sec-data}

Data storage and processing at the edge are major aspects of IoT edge computing, directly addressing the high-level IoT challenges listed in {{sec-challenges}}. Data analysis, for example, through AI/ML tasks performed at the edge, may benefit from specialized hardware support on the computing nodes.

Related challenges include:

* Addressing concerns regarding resource usage, security, and privacy when sharing, processing, discovering, or managing data: for example presenting data in views composed of an aggregation of related data {{Zhang}}; protecting data communication between authenticated peers {{Basudan}}, classifying data (e.g., in terms of privacy, importance, validity), and compressing and encrypting data, for example, using homomorphic encryption to directly process encrypted data {{Stanciu}}.
* Other concerns regarding edge data discovery (e.g., streaming data, metadata, and events) include siloization and lack of standards in edge environments that can be dynamic (e.g., vehicular networks) and heterogeneous {{I-D.mcbride-edge-data-discovery-overview}}.
* Data-driven programming models {{Renart}}, for example, event-based, including handling naming and data abstractions.
* Data integration in an environment that without data standardization, or where different sources use different ontologies {{Farnbauer-Schmidt}}.
* Addressing concerns such as limited resources, privacy, dynamic, and heterogeneous environments to deploy machine learning at the edge: for example, making machine learning more lightweight and distributed (e.g., enabling distributed inference at the edge), supporting shorter training times and simplified models, and supporting models that can be compressed for efficient communication {{Murshed}}.
* Although edge computing can support IoT services independently of cloud computing, it can also be connected to cloud computing. Thus, the relationship between IoT edge computing and cloud computing, with regard to data management, is another potential challenge {{ISO_TR}}.

## Simulation and Emulation Environments

IoT Edge Computing introduces new challenges to the simulation and emulation tools used by researchers and developers. A varied set of applications, networks, and computing technologies can coexist in a distributed system, making modeling difficult. Scale, mobility, and resource management are additional challenges [SimulatingFog].

Tools include simulators, where simplified application logic runs on top of a fog network model, and emulators, where actual applications can be deployed, typically in software containers, over a cloud infrastructure (e.g., Docker and Kubernetes) running over a network emulating network edge conditions such as variable delays, throughput and mobility events. To gain in scale, emulated and simulated systems can be used together in hybrid federation-based approaches [PseudoDynamicTesting], whereas to gain in realism, physical devices can be interconnected with emulated systems. Examples of related work and platforms include the publicly accessible MEC sandbox work recently initiated in ETSI [ETSI_Sandbox], and open source simulators and emulators ([AdvantEDGE] emulator and tools cited in [SimulatingFog]). EdgeNet {{Senel}} is a globally distributed edge cloud for Internet researchers, using nodes contributed by institutions, and based on Docker for containerization and Kubernetes for deployment and node management.

Digital twins are virtual instances of a physical system (twin) that are continually updated with the latter's performance, maintenance, and health status data throughout the life cycle of the physical system.  {{Madni}}. In contrast to a traditional emulation or simulated environment, digital twins, once generated, are maintained in sync by their physical twin, which can be, among many other instances, an IoT device, edge device, an edge network. The benefits of digital twins go beyond those of emulation and include accelerated business processes, enhanced productivity, and faster innovation with reduced costs {{I-D.irtf-nmrg-network-digital-twin-arch}}.

# Security Considerations

Privacy and security are drivers of the adoption of edge computing for the IoT ({{sec-priv}}). As discussed in {{sec-dis-auth}}, authentication and trust (among computing nodes, management nodes, and end devices) can be challenging as scale, mobility, and heterogeneity increase. The sometimes disconnected nature of edge resources can avoid reliance on third-party authorities. Distributed edge computing is exposed reliability and denial of service attacks. Personal or proprietary IoT data leakage is also a major threat, particularly because of the distributed nature of the systems ({{sec-data}}). Furthermore, blockchain-based distributed IoT edge computing must be designed for privacy, since public blockchain addressing does not guarantee absolute anonymity {{Ali}}.

However, edge computing also offers solutions in the security space: maintaining privacy by computing sensitive data closer to data generators is a major use case for IoT edge computing.  An edge cloud can be used to perform actions based on sensitive data or to anonymize or aggregate data prior to transmission to a remote cloud server. Edge computing communication brokering functions can also be used to secure communication between edge and cloud networks.

# Conclusion

IoT edge computing plays an essential role, complementary to the cloud, in enabling IoT systems in certain situations. In this document, we presented use cases and listing the core challenges faced by IoT that drive the need for IoT edge computing. The first part of this document may therefore help focus future research efforts on the aspects of IoT edge computing where it is most useful. The second part of this document presents a general system model and structured overview of the associated research challenges and related work. The structure, based on the system model, is not meant to be restrictive and exists for the purpose of having a link between individual research areas and where they are applicable in an IoT edge computing system.

# IANA Considerations

This document has no IANA actions.

# Acknowledgements

The authors would like to thank Joo-Sang Youn, Akbar Rahman, Michel Roy, Robert Gazda, Rute Sofia, Thomas Fossati, Chonggang Wang, {{{Marie-José Montpetit}}}, Carlos J. Bernardos, Milan Milenkovic, Dale Seed, JaeSeung Song, Roberto Morabito, Carsten Bormann and {{{Ari Keränen}}} for their valuable comments and suggestions on this document.