## [CRiSIS2018](CRiSIS2018.md)
Link: [[Proceedings](https://link.springer.com/book/10.1007/978-3-030-12143-3)]
[[Conference](https://crisis2018.labri.fr/)]
Awardなし  
***
**_Trust Evaluation Model for Attack Detection in Social Internet of Things_**  
Abdelghani, Wafa; Zayani, Corinne Amel; Amous, Ikram; Sèdes, Florence  
https://link.springer.com/chapter/10.1007/978-3-030-12143-3_5  

##### Social Internet of Things (SIoT) is a paradigm in which the Internet of Things (IoT) concept is fused with Social Networks for allowing both people and objects to interact in order to offer a variety of attractive services and applications. However, with this emerging paradigm, people feel wary and cautious. They worry about revealing their data and violating their privacy. Without trustworthy mechanisms to guarantee the reliability of user’s communications and interactions, the SIoT will not reach enough popularity to be considered as a cutting-edge technology. Accordingly, trust management becomes a major challenge to provide qualified services and improved security.Several works in the literature have dealed with this problem and have proposed different trust-models. Nevertheless, proposed models aim to rank the best nodes in the SIoT network. This does not allow to detect different types of attack or malicious nodes.Hence, we overcome these issues through proposing a new trust-evaluation model, able to detect malicious nodes, block and isolate them, in order to obtain a reliable and resilient system. For this, we propose new features to describe and quantify the different behaviors that operate in such system. We formalized and implemented a new function learned and built based on supervised learning, to analyze different features and distinguish malicious behavior from benign ones. Experimentation made on a real data set prove the resilience and the performance of our trust model.

***

**_A Certificate-Less Key Exchange Protocol for IoT_**  
Kome, Ivan Marco Lobe; Cuppens-Boulahia, Nora; Cuppens, Frédéric; Frey, Vincent  
https://link.springer.com/chapter/10.1007/978-3-030-12143-3_6  

##### Diffie-Hellman key exchange is a popular cryptographic algorithm that allows Internet protocols to agree on a shared key and negotiate a secure connection. It is used in many protocols including SSH, IPsec, SMTPS, and protocols that rely on TLS. In the Internet of Things (IoT), we cannot rely on the PKI architecture to secure communications due to the growing number of connected things. We are proposing to decentralize the encryption keys management while maintaining the property of authentication and secrecy. We use the ability of each node to build a private channel to create a shared key, safe from the eye of an attacker. Our solution provides a solution to build a certificate-less trusted ecosystem for IoT.

***

## [HOST2019](HOST2019.md)
Link: [[Proceedings](https://ieeexplore.ieee.org/xpl/conhome/8736108/proceeding)]
[[Conference](http://www.hostsymposium.org/host2019/index2019.php)]
[[Awards](http://www.hostsymposium.org/host_2019awards.php)]  
***
**_QIF-Verilog: Quantitative Information-Flow based Hardware Description Languages for Pre-Silicon Security Assessment_**  
Guo, X.; Dutta, R. G.; He, J.; Tehranipoor, M. M.; Jin, Y.  
https://doi.org/10.1109/HST.2019.8740840  

##### Hardware vulnerabilities are often due to design mistakes because the designer does not sufficiently consider potential security vulnerabilities at the design stage. As a result, various security solutions have been developed to protect ICs, among which the language-based hardware security verification serves as a promising solution. The verification process will be performed while compiling the HDL of the design. However, similar to other formal verification methods, the language-based approach also suffers from scalability issue. Furthermore, existing solutions either lead to hardware overhead or are not designed for vulnerable or malicious logic detection. To alleviate these challenges, we propose a new language based framework, QIF-Verilog, to evaluate the trustworthiness of a hardware system at register transfer level (RTL). This framework introduces a quantified information flow (QIF) model and extends Verilog type systems to provide more expressiveness in presenting security rules; QIF is capable of checking the security rules given by the hardware designer. Secrets are labeled by the new type and then parsed to data flow, to which a QIF model will be applied. To demonstrate our approach, we design a compiler for QIF-Verilog and perform vulnerability analysis on benchmarks from Trust-Hub and OpenCore. We show that Trojans or design faults that leak information from circuit outputs can be detected automatically, and that our method evaluates the security of the design correctly.

***

## [POST2019](POST2019.md)
Link: [[Proceedings](https://link.springer.com/book/10.1007/978-3-030-17138-4)]
[[Conference](https://conf.researchr.org/track/etaps-2019/post-2019-papers)]
[[Awards](https://conf.researchr.org/attending/etaps-2019/etaps-test-of-time-award)]  
***
**_$$\textsc {Wys}^\star $$: A DSL for Verified Secure Multi-party Computations_**  
Rastogi, Aseem; Swamy, Nikhil; Hicks, Michael  
https://link.springer.com/chapter/10.1007/978-3-030-17138-4_5  

##### Secure multi-party computation (MPC) enables a set of mutually distrusting parties to cooperatively compute, using a cryptographic protocol, a function over their private data. This paper presents \(\textsc {Wys}^\star \), a new domain-specific language (DSL) for writing mixed-mode MPCs. \(\textsc {Wys}^\star \) is an embedded DSL hosted in F\(^\star \), a verification-oriented, effectful programming language. \(\textsc {Wys}^\star \) source programs are essentially F\(^\star \) programs written in a custom MPC effect, meaning that the programmers can use F\(^\star \)’s logic to verify the correctness and security properties of their programs. To reason about the distributed runtime semantics of these programs, we formalize a deep embedding of \(\textsc {Wys}^\star \), also in F\(^\star \). We mechanize the necessary metatheory to prove that the properties verified for the \(\textsc {Wys}^\star \) source programs carry over to the distributed, multi-party semantics. Finally, we use F\(^\star \)’s extraction to extract an interpreter that we have proved matches this semantics, yielding a partially verified implementation. \(\textsc {Wys}^\star \) is the first DSL to enable formal verification of MPC programs. We have implemented several MPC protocols in \(\textsc {Wys}^\star \), including private set intersection, joint median, and an MPC-based card dealing application, and have verified their correctness and security.

***

**_Orchestrating Layered Attestations_**  
Ramsdell, John D.; Rowe, Paul D.; Alexander, Perry; Helble, Sarah C.; Loscocco, Peter; Pendergrass, J. Aaron; Petz, Adam  
https://link.springer.com/chapter/10.1007/978-3-030-17138-4_9  

##### We present Copland, a language for specifying layered attestations. Layered attestations provide a remote appraiser with structured evidence of the integrity of a target system to support a trust decision. The language is designed to bridge the gap between formal analysis of attestation security guarantees and concrete implementations. We therefore provide two semantic interpretations of terms in our language. The first is a denotational semantics in terms of partially ordered sets of events. This directly connects Copland to prior work on layered attestation. The second is an operational semantics detailing how the data and control flow are executed. This gives explicit implementation guidance for attestation frameworks. We show a formal connection between the two semantics ensuring that any execution according to the operational semantics is consistent with the denotational event semantics. This ensures that formal guarantees resulting from analyzing the event semantics will hold for executions respecting the operational semantics. All results have been formally verified with the Coq proof assistant.

***

## [PST2018](PST2018.md)
Link: [[Proceedings](https://ieeexplore.ieee.org/xpl/conhome/8498146/proceeding)]
[[Conference](https://pstnet.ca/)]
Awardなし  
***
**_Mutual Authentication in Electronic Voting Schemes_**  
Augoye, V.; Tomlinson, A.  
https://doi.org/10.1109/PST.2018.8514212  

##### Voter eligibility is an important requirement of electronic voting which prevents double voting and voter impersonation. Many e-voting schemes assume a trustworthy environment for vote casting and tallying hence trust pollworkers to correctly authenticate voters. In this paper we propose a mutual entity authentication protocol using biometrics to ensure voter eligibility and digital signatures for ballot authentication in an untrustworthy environment.

***

**_Digitized Trust in Human-in-the-Loop Health Research_**  
Sutton, A.; Samavi, R.; Doyle, T. E.; Koff, D.  
https://doi.org/10.1109/PST.2018.8514168  

##### In this paper, we propose an architecture that utilizes blockchain technology for enabling verifiable trust in collaborative health research environments. The architecture supports the human-in-the-loop paradigm for health research by establishing trust between participants, including human researchers and AI systems, by making all data transformations transparent and verifiable by all participants. We define the trustworthiness of the system and provide an analysis of the architecture in terms of trust requirements. We then evaluate our architecture by analyzing its resiliency to common security threats and through an experimental realization.

***

**_Enforcing Privacy and Security in Public Cloud Storage_**  
Resende, J. S.; Martins, R.; Antunes, L.  
https://doi.org/10.1109/PST.2018.8514195  

##### Cloud storage allows users to remotely store their data, giving access anywhere and to anyone with an Internet connection. The accessibility, lack of local data maintenance and absence of local storage hardware are the main advantages of this type of storage. The adoption of this type of storage is being driven by its accessibility. However, one of the main barriers to its widespread adoption is the sovereignty issues originated by lack of trust in storing private and sensitive information in such a medium. Recent attacks to cloud-based storage show that current solutions do not provide adequate levels of security and subsequently fail to protect users' privacy. Usually, users rely solely on the security supplied by the storage providers, which in the presence of a security breach will ultimate lead to data leakage. In this paper, we propose and implement a broker (ARGUS) that acts as a proxy to the existing public cloud infrastructures by performing all the necessary authentication, cryptography and erasure coding. ARGUS uses erasure code as a way to provide efficient redundancy (opposite to standard replication) while adding an extra layer to data protection in which data is broken into fragments, expanded and encoded with redundant data pieces that are stored across a set of different storage providers (public or private). The key characteristics of ARGUS are confidentiality, integrity and availability of data stored in public cloud systems.

***

**_Crossing Cross-Domain Paths in the Current Web_**  
Ruohonen, J.; Salovaara, J.; Leppänen, V.  
https://doi.org/10.1109/PST.2018.8514163  

##### The loading of resources from third-parties has evoked new security and privacy concerns about the current world wide web. Building on the concepts of forced and implicit trust, this paper examines cross-domain transmission control protocol (TCP) connections that are initiated to domains other than the domain queried with a web browser. The dataset covers nearly ten thousand domains and over three hundred thousand TCP connections initiated by querying popular Finnish websites and globally popular sites. According to the results, (i) cross-domain connections are extremely common in the current Web. (ii) Most of these transmit encrypted content, although mixed content delivery is relatively common; many of the cross-domain connections deliver unencrypted content at the same time. (iii) Many of the cross-domain connections are initiated to known web advertisement domains, but a much larger share traces to social media platforms and cloud infrastructures. Finally, (iv) the results differ slightly between the Finnish web sites sampled and the globally popular sites. With these results, the paper contributes to the ongoing work for better understanding cross-domain connections and dependencies in the world wide web.

***

**_Trust-driven, Decentralized Data Access Control for Open Network of Autonomous Data Providers_**  
Opioła, Ł; Dutka, Ł; Słota, R. G.; Kitowski, J.  
https://doi.org/10.1109/PST.2018.8514209  

##### The observation of current trends in data access, especially in the field of scientific computations, shows that global data access that crosses federation boundaries is highly desirable. However, administrative constraints require that data centers remain autonomous, which effectively eliminates the possibility of cooperation. To overcome this, we plan to establish an open network of cooperating data providers. In this paper, we address the issue of data access control for such network. Our proposition is to use a synergy of hybrid peer-to-peer architecture, decentralized identity and access management, metadata synchronization protocol and trust driven authorization flow. The proposed solution is discussed using real-life use-cases concerning cross-federation data access.

***

**_Problem-based Derivation of Trustworthiness Requirements from Users’ Trust Concerns_**  
Mohammadi, N. G.; Ulfat-Bunyadi, N.; Heisel, M.  
https://doi.org/10.1109/PST.2018.8514183  

##### The trustworthiness of cyber-physical systems (CPS) that support complex collaborative business processes is an emergent property. New technologies like cloud computing bring new capabilities for hosting and offering complex collaborative business operations. However, these advances might introduce new vulnerabilities and threats caused by collaboration and data exchange over the Internet. Hence, users become more concerned about trust. In order to address users' trust concerns, trustworthiness requirements for the CPS must be elicited and satisfied. They describe the properties (qualities) the CPS must possess in order to be trustworthy. In this paper, we suggest a problem-based requirements engineering method that supports specifically the derivation of trustworthiness requirements. Based on identified trust concerns of users, trust assumptions are made explicit in problem diagrams. They express the conditions under which users are willing to trust. The problem diagrams and trust assumptions are then refined until they are concrete enough to derive trustworthiness requirements from them. During the refinement process, trust assumptions may influence and modify the system design (and vice versa, i.e., due to a certain system design, new trust concerns may arise that need to be addressed). In this way, users' trust concerns are considered right from the beginning and trustworthiness is designed into the CPS. An application example from the healthcare domain is used to demonstrate our approach.

***

**_Privacy Preserving Probabilistic Record Linkage Without Trusted Third Party_**  
Lazrig, I.; Ong, T. C.; Ray, I.; Ray, I.; Jiang, X.; Vaidya, J.  
https://doi.org/10.1109/PST.2018.8514192  

##### For the purpose of research, organizations often need to share and link data belonging to a single individual while protecting her privacy. This problem, referred to as privacy preserving record linkage (PPRL), has been investigated by researchers. Most PPRL works focus on deterministic linkages where the identifying attributes of two records must be equal in order to declare them to belong to the same individual. Moreover, most of these methods require the active participation of a trusted third party (TTP). If this TTP is compromised, it makes the data from all participating parties vulnerable to information leakage. The proposed work improves upon the existing methods in two ways. First, we propose a protocol which does not require two records to have an exact match on identifying attributes in order to be declared as belonging to the same individual. Second, we investigate probabilistic PPRL in the two-party setting without resorting to any TTP. We use Bloom filters for probabilistic matching and Yao's garbled circuit to perform the computation needed for the matching on encrypted data. To alleviate the computation and communication overhead of Yao's protocol, we leverage data blocking methods and optimize the computation. We provide a security proof of our method and experimentally evaluate the performance gained on large benchmark datasets.

***

**_On Sybil Classification in Online Social Networks Using Only Structural Features_**  
Mulamba, D.; Ray, I.; Ray, I.  
https://doi.org/10.1109/PST.2018.8514162  

##### Sybil attack is a problem that seriously affects Online Social Networks (OSNs). These attacks are made possible by the openness of OSN platforms that allows an attacker to create multiple fake accounts, called Sybils, which are then used to compromise the underlining trust pinnings of the OSN. Early Sybil account detection mechanisms involved classification of users into benign and malicious based on various attributes collected from the user profiles. One challenge affecting these classification methods is that user attributes can often be in-complete or inaccurate. In addition, these classification methods can be evaded by sophisticated attackers. More importantly, user profiles can often reveal sensitive user information that can potentially be misused causing privacy violation. In this work, we propose a Sybil detection method that is based on the classification of users into malicious and benign based on the inherent topology or structure of the underlining OSN graph. We propose a new set of structural features for a graph. Using this new feature set, we perform several experiments on both synthetic as well as real-world OSN data. Our results show that the proposed detection method is very effective in correctly classifying Sybil accounts without running the risk of being evaded by a sophisticated attacker and without compromising privacy of users.

***

## [STM2019](STM2019.md)
Link: [[Proceedings](https://link.springer.com/book/10.1007/978-3-030-31511-5)]
[[Conference](https://stm2019.uni.lu/)]
Awardなし  
***
**_Audit-Based Access Control with a Distributed Ledger: Applications to Healthcare Organizations_**  
Morelli, Umberto; Ranise, Silvio; Sartori, Damiano; Sciarretta, Giada; Tomasi, Alessandro  
https://link.springer.com/chapter/10.1007/978-3-030-31511-5_2  

##### We propose an audit-based architecture that leverages the Hyperledger Fabric distributed ledger as a means to increase accountability and decentralize the authorization decision process of Attribute-Based Access Control policies by using smart contracts. Our goal is to decrease the trust in administrators and users with privileged accounts, and make the a posteriori verification of access events more reliable. We implement our approach to the use case of Electronic Health Record access control. Preliminary experiments show the viability of the proposed approach.

***

**_Understanding Attestation: Analyzing Protocols that Use Quotes_**  
Guttman, Joshua D.; Ramsdell, John D.  
https://link.springer.com/chapter/10.1007/978-3-030-31511-5_6  

##### Attestation protocols use digital signatures and other cryptographic values to convey evidence of hardware state, program code, and associated keys. They require hardware support such as Trusted Execution Environments. Conclusions about attestations thus depend jointly on protocols, hardware services, and program behavior.We present a mechanized approach to modeling these properties, combining protocol analysis with axioms, that formalize hardware and software properties. Here, we model aspects of Intel’s SGX mechanism. Above the underlying manufacturer-provided protocols, we build a modular user-level that uses its attestations to make trust decisions.

***

**_Challenges of Using Trusted Computing for Collaborative Data Processing_**  
Wagner, Paul Georg; Birnstill, Pascal; Beyerer, Jürgen  
https://link.springer.com/chapter/10.1007/978-3-030-31511-5_7  

##### In recent years many business processes have become more interconnected than ever before. Driven by the advance of the Internet of Things, companies rely on complex data processing chains that span over many collaborating corporations and across different countries. As a result of this development, automated data acquisition and collaborative data usage is now a foundation of many innovative and successful business models. However, despite having a clear interest in sharing valuable data with other stakeholders, data owners simultaneously need to protect their assets against illegitimate use. In order to accommodate this requirement, existing data sharing solutions contain usage control systems capable of enforcing policies on data even after they have been shared. The integrity of these policy enforcement components is often monitored by a trusted platform module (TPM) on the data receiver’s side. In this work we evaluate the adequacy of TPM-based remote attestation for protecting shared data on foreign systems. In order to do so we develop an attacker model that includes privileged system users and expose attack vectors on TPM-protected data sharing applications. We show that TPMs do not provide sufficient protection against malicious administrators from competing stakeholders. Finally, we describe the advantages of using Intel’s Software Guard Extensions (SGX) to protect shared data in hostile environments and propose an enhanced system architecture that includes both SGX enclaves as well as a classical TPM.

***

**_Secure Trust Evaluation Using Multipath and Referral Chain Methods_**  
Raeini, Mohammad G.; Nojoumian, Mehrdad  
https://link.springer.com/chapter/10.1007/978-3-030-31511-5_8  

##### The notions of trust and reputation have been well studied and integrated into computer networks and internet-based services, e.g., Amazon and eBay websites. Using trust and reputation as social mechanisms can enhance the quality, reliability and trustworthiness of networks or services. These social mechanisms can also be used to provide better security measures. Indeed, trust and reputation can be considered as soft security methods that compliment hard security techniques. However, data security and privacy are among the primary challenges in trust and reputation systems. We therefore propose a secure trust evaluation (STE) method in which privacy of trust values and corresponding weights are preserved. Our proposed method is constructed based on an information theoretic framework for modeling trust and two approaches that propagate trust in a network, i.e., multipath and referral chain techniques. In other words, we utilize secure multiparty computation to provide protocols by which the nodes in a network will be able to evaluate their trust values in a secure fashion. We also provide a fascinating application of our STE method in the context of network routing protocols.

***

## [TrustBus2019](TrustBus2019.md)
Link: [[Proceedings](https://link.springer.com/book/10.1007/978-3-030-27813-7)]
[[Conference](http://www.dexa.org/trustbus2019)]
Awardなし  
***
**_I Did Not Accept That: Demonstrating Consent in Online Collection of Personal Data_**  
Jesus, Vitor; Mustare, Shweta  
https://link.springer.com/chapter/10.1007/978-3-030-27813-7_3  

##### Privacy in online collection of personal data is currently a much debated topic considering, amongst other reasons, the incidents with well known digital organisations, such as social networks and, in Europe, the recent EU/GDPR regulation. Among other required practices, explicit and simply worded consent from individuals must be obtained before collecting and using personal information. Further, individuals must also be given detailed information about what, how and what for data is collected. Consent is typically obtained at the collection point and, at a single point in time (ignoring updates), associated with Privacy Policies or End-User Agreements. At any moment, both the user and the organization should be able to produce evidence of this consent. This proof should not be disputable which leads us to strong cryptographic properties.The problem we discuss is how to robustly demonstrate such consent was given. We adapt fair-exchange protocols to this particular problem and, upon an exchange of personal data, we are able to produce a cryptographic receipt of acceptance that any party can use to prove consent and elicit non-repudiation. We discuss two broad strategies: a pure peer-to-peer scheme and the use of a Trusted Third Party.

***

**_The Interrelation of Game Elements and Privacy Requirements for the Design of a System: A Metamodel_**  
Mavroeidi, Aikaterini-Georgia; Kitsiou, Angeliki; Kalloniatis, Christos  
https://link.springer.com/chapter/10.1007/978-3-030-27813-7_8  

##### Due to the increased use of Information and Communication Technologies (ICTs), several methods have been developed in order to create more attractive interaction environments, so that users’ interest on using services to be maintained. Gamification consists a method, aiming to increase users’ engagement by implementing game design elements in services that are not games [1]. While using all these services, users’ information is recorded and monitored. Except the importance of increasing the use of ICTs, it is crucial to ensure that users’ personal information will be protected. To achieve it, privacy issues should be considered by software developers during the design phase of a service, in parallel with the game design elements. Based on our previous research [2], it was identified that the relation between gamification and privacy has not been examined sufficiently. As a result, a detailed analysis was conducted. In this work, in order to examine this relation in existent services, a detailed description of gamified services in several sectors has been conducted. Afterwards, based on the results of the conducted research and the examination of existent gamified services, a metamodel is presented, which describes how each game element conflicts with privacy requirements. By using this metamodel, software developers will be able to identify which mechanisms should be implemented in such services, so that users’ privacy to be protected in parallel. The development of such services ensures the trust between users and them and consequently, users’ engagements will be increased [3].

***

**_Decentralised and Collaborative Auditing of Workflows_**  
Nehme, Antonio; Jesus, Vitor; Mahbub, Khaled; Abdallah, Ali  
https://link.springer.com/chapter/10.1007/978-3-030-27813-7_9  

##### Workflows involve actions and decision making at the level of each participant. Trusted generation, collection and storage of evidence is fundamental for these systems to assert accountability in case of disputes. Ensuring the security of audit systems requires reliable protection of evidence in order to cope with its confidentiality, its integrity at generation and storage phases, as well as its availability. Collusion with an audit authority is a threat that can affect all these security aspects, and there is room for improvement in existent approaches that target this problem.This work presents an approach for workflow auditing which targets security challenges of collusion-related threats, covers different trust and confidentiality requirements, and offers flexible levels of scrutiny for reported events. It relies on participants verifying each other’s reported audit data, and introduces a secure mechanism to share encrypted audit trails with participants while protecting their confidentiality. We discuss the adequacy of our audit approach to produce reliable evidence despite possible collusion to destroy, tamper with, or hide evidence.

***

## [TrustCom2019](TrustCom2019.md)
Link: [[Proceedings](https://ieeexplore.ieee.org/xpl/conhome/8883860/proceeding)]
[[Conference](https://crow.org.nz/Trustcom2019)]
[[Awards](https://forumpoint2.eventsair.com/QuickEventWebsitePortal/trustcom19/tc19/ExtraContent/ContentPage?page=9)]  
***
**_Title_**  
Author  
https://doi.org/DOI  

##### Abstract Note

***

**_Building Trust in Container Environment_**  
Guo, Yunlong; Yu, Aimin; Gong, Xiaoli; Zhao, Lixin; Cai, Lijun; Meng, Dan  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00011  

##### Container technology is an emerging virtualization technology that is more efficient and lightweight than virtual machines. This technology is becoming increasingly popular. However, containers are vulnerable to attackers due to various security issues. It is necessary to build trust between users and their containers, as well as between a remote party and the container in the untrusted container environment. The existing trusted computing technologies build a trust chain from hardware to the running operating system. In this paper, we extend the trust chain to containers and build trust in the container environment. We first boot the computer to a trusted operating system. The trusted OS then verifies programs running on the OS to improve security. We design the well-formed signature list to help users to authorize container executables and modify the Linux kernel to verify executables running in containers. Therefore, the user is able to control what programs can run in his containers and trust the containers. Our approach generates a measurement list and creates a vTPM for each container. A remote party can request the measurement list based on our container state challenge protocol. As a result, a remote party is able to know the container state and decide whether to trust the container. We also implement the executables measurement and verification mechanism and evaluate the performance. The results show the container start delay is no more than 3% of the normal container start time and the overhead to measure and verify executables is no more than 1 us in most cases, which is reasonably efficient.

***

**_Trustworthy Privacy-Preserving Service Compositions_**  
Theuermann, Kevin  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00012  

##### E-Government applications are often composed of services provided by multiple service providers. Thus, public services must ensure accountability of performed actions to increase the trust in electronic services. Trust is crucial for user satisfaction and represents a key factor for the success of public services. Accountability is also necessary to determine an unintended behaviour of participants in service compositions. Transparent monitoring systems can facilitate the detection of failures or malicious behaviour of attackers. However, the demand for more accountability and transparency in public services arises challenges regarding the privacy of citizen's data. In this paper we propose a service composition concept providing accountability of service providers and considering privacy of sensitive data. This composition system uses proxy re-encryption in the communication protocol and cryptographically chains executed transactions. Retrospectively, citizens as well as participants of a processed service can validate the chained transactions. An implemented proof-of-concept demonstrates the feasibility of the proposed solution, which clearly supports accountability and thus increases trust in public services among citizens.

***

**_A Unified Measurable Software Trustworthy Model Based on Vulnerability Loss Speed Index_**  
Jabeen, Gul; Ping, Luo  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00013  

##### As trust becomes increasingly important in the software domain. Due to its complex composite concept, people face great challenges, especially in today's dynamic and constantly changing internet technology. In addition, measuring the software trustworthiness correctly and effectively plays a significant role in gaining users trust in choosing different software. In the context of security, trust is previously measured based on the vulnerability time occurrence to predict the total number of vulnerabilities or their future occurrence time. In this study, we proposed a new unified index called ""loss speed index"" that integrates the most important variables of software security such as vulnerability occurrence time, number and severity loss, which are used to evaluate the overall software trust measurement. Based on this new definition, a new model called software trustworthy security growth model (STSGM) has been proposed. This paper also aims at filling the gap by addressing the severity of vulnerabilities and proposed a vulnerability severity prediction model, the results are further evaluated by STSGM to estimate the future loss speed index. Our work has several features such as: (1) It is used to predict the vulnerability severity/type in future, (2) Unlike traditional evaluation methods like expert scoring, our model uses historical data to predict the future loss speed of software, (3) The loss metric value is used to evaluate the risk associated with different software, which has a direct impact on software trustworthiness. Experiments performed on real software vulnerability datasets and its results are analyzed to check the correctness and effectiveness of the proposed model.

***

**_MicroTEE: Designing TEE OS Based on the Microkernel Architecture_**  
Ji, Dongxu; Zhang, Qianying; Zhao, Shijun; Shi, Zhiping; Guan, Yong  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00014  
**[Best Trust Track Paper Award]**

##### ARM TrustZone technology is widely used to provide Trusted Execution Environments (TEE) for mobile devices. However, most TEE OSes are implemented as monolithic kernels. In such designs, device drivers, kernel services and kernel modules all run in the kernel, which results in large size of the kernel. It is difficult to guarantee that all components of the kernel have no security vulnerabilities in the monolithic kernel architecture, such as the integer overflow vulnerability in Qualcomm QSEE TrustZone and the TZDriver vulnerability in HUAWEI Hisilicon TEE architecture. This paper presents MicroTEE, a TEE OS based on the microkernel architecture. In MicroTEE, the microkernel provides strong isolation for TEE OS's basic services, such as crypto service and platform key management service. The kernel is only responsible for providing core services such as address space management, thread management, and inter-process communication. Other fundamental services, such as crypto service and platform key management service are implemented as applications at the user layer. Crypto Services and Key Management are used to provide Trusted Applications (TAs) with sensitive information encryption, data signing, and platform attestation functions. Our design avoids the compromise of the whole TEE OS if only one kernel service is vulnerable. A monitor has also been added to perform the switch between the secure world and the normal world. Finally, we implemented a MicroTEE prototype on the Freescale i.MX6Q Sabre Lite development board and tested its performance. Evaluation results show that the performance of cryptographic operations in MicroTEE is better than it in Linux when the size of data is small.

***

**_Trust and Reputation in Vehicular Networks: A Smart Contract-Based Approach_**  
Malik, Nisha; Nanda, Priyadarsi; He, Xiangjian; Liu, RenPing  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00015  

##### Appending digital signatures and certificates to messages guarantee data integrity and ensure non-repudiation, but do not identify greedy authenticated nodes. Trust evolves if some reputable and trusted node verifies the node, data and evaluates the trustworthiness of the node using an accurate metric. But, even if the verifying party is a trusted centralized party, there is opacity and obscurity in computed reputation rating. The trusted party maps it with the node's identity, but how is it evaluated and what inputs derive the reputation rating remains hidden, thus concealment of transparency leads to privacy. Besides, the malevolent nodes might collude together for defamatory actions against reliable nodes, and eventually bad mouth these nodes or praise malicious nodes collaboratively. Thus, we cannot always assume the fairness of the nodes as the rating they give to any node might not be a fair one. In this paper, we propose a smart contract-based approach to update and query the reputation of nodes, stored and maintained by IPFS distributed storage. The use case particularly deals with an emergency scenario, dealing against colluding attacks. Our scheme is implemented using MATLAB simulation. The results show how smart contracts are capable of accurately identifying trustworthy nodes and record the reputation of a node transparently and immutably.

***

**_Optimal File Dissemination Scheduling Under a General Binary Tree of Trust Relationship_**  
Tien, Yun-Ping; Lin, Wei-Chen; Ho, Jan-Ming; Hon, Wing-Kai  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00016  

##### Ku et al. (GLOBECOM 2012) first studied the file dissemination problem under hierarchical trust relationship. They showed that when the trust relationship is defined as a rooted full binary tree, then there exists an optimal schedule for file dissemination taking ⌈log2 n⌉ rounds, where n is the total number of nodes including the source and destinations of broadcasting. Furthermore, they devised a linear-time algorithm to compute such a schedule. In this paper, we extend the file dissemination problem with the trust relationship in the form of general binary tree, i.e., each internal node is not restricted to have exactly two children. We show that an optimal schedule for file dissemination remains ⌈log2 n⌉ rounds, irrespective of the tree topology, and such a schedule can be computed in linear time. While we are extending Ku et al.'s results, our algorithm is based on a completely different approach. We have also considered the case of finding such an optimal schedule in the parallel setting, and propose an algorithm with parallel time complexity O(h log2 n), where h denotes height of the tree. Furthermore, we show that the sequential algorithm and the parallel algorithm work for the case when the trust relationship is a rooted DAG such that the out-degree of each node is bounded by two. Finally, we remark that our algorithms also produce asymptotically optimal schedules for general degree-d DAGs when d is a constant, while the problem becomes NP-hard even when the out-degree of each node in the DAG is limited to 6.

***

**_Horcruxes for Everyone - A Framework for Key-Loss Recovery by Splitting Trust_**  
Hörandner, Felix; Rabensteiner, Christof  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00017  

##### Many modern applications require users to manage keys on their own devices, which, in case of device loss or failure, may lead to serious consequences, e.g., losing access to their Bitcoin wallet. These applications need a secure and user-friendly strategy that protects users from losing keys while preserving the keys' confidentiality. Fortunately, password-protected secret sharing (PPSS) can be used to design such a key-loss recovery strategy: It enables users to split their keys into shares, to distribute these shares across third parties and, if necessary, to recover keys via password authentication. However, deploying PPSS in a key-loss recovery strategy leaves the following practical questions unanswered: Which third parties should a user pick to diversify the trust? How can these third parties be recruited? And: How can other applications benefit from such a strategy? In this paper, we develop a framework for key-loss recovery, which allows users to distribute shares in a hierarchy that is aligned with relevant trust factors. As part of the framework, we propose a management app that supports users in building and managing hierarchical trust policies, and that offers its service to other applications. To convince organizations to operate servers, we implement our framework with a focus on server-side cost-efficiency. We extend a PPSS scheme with hierarchical trust policies, add efficient prevention of online guessing, and measure the performance of the overall system at-scale on AWS. The cost projection shows that deploying our framework is inexpensive: 40 organizations, each operating server resources for less than $20, support 50 million users when splitting and recovering their keys.

***

**_HyperMI: A Privilege-level VM Protection Approach against Compromised Hypervisor_**  
Lin, Kunli; Liu, Wenqing; Zhang, Kun; Tu, Bibo  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00018  

##### Sensitive data in guest virtual machine is easy to be leaked once hypervisor is compromised. Therefore, VM protection is important to protect the memory of VM from compromised hypervisor's malicious access causally. Previous efforts employ extra customized hardware or employ new software relying on a higher privilege level than hypervisor. This paper proposes HyperMI, a novel approach that provides a privilege-level secure execution environment for VM protection in cloud computing against compromised hypervisor. It provides HyperMI world, effective VM isolation and event-driven VM monitoring in order to prevent customers' sensitive data in VM from being leaked. HyperMI world, placed at the same privilege level with hypervisor, is a privilege-level secure isolated execution environment. As TCB, it is used for VM isolation and VM monitoring. What's the most important, HyperMI focuses on decoupling the function of interaction between hypervisor and VM and decoupling the function of address mapping of VM from hypervisor. As a result, HyperMI can only controls page mapping of VM and EPT updating when a page is allocated to a VM. We have implemented a prototype for KVM hypervisor with multiple Linux as guest OSes, which can be used in commercial cloud computing industry with portability and compatibility for all kinds of CPU platforms. The security analysis shows that this approach can provide protection for VM with effective isolation and event-driven monitoring, and the performance evaluation confirms the efficiency of HyperMI.

***

**_The Deviation Attack: A Novel Denial-of-Service Attack Against IKEv2_**  
Ninet, Tristan; Legay, Axel; Maillard, Romaric; Traonouez, Louis-Marie; Zendra, Olivier  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00019  

##### In previous analyses IKEv2 has been shown to suffer from an authentication vulnerability that was considered not exploitable. By designing and implementing a novel slow Denial-of-Service attack, which we name the Deviation Attack, we show that the vulnerability is actually exploitable. We explain the attack's requirements, propose possible counter-measures and propose two possible modifications of the protocol, which both overcome the vulnerability.

***

**_A Survey of Research on CAPTCHA Designing and Breaking Techniques_**  
Zhang, Yang; Gao, Haichang; Pei, Ge; Luo, Sainan; Chang, Guoqin; Cheng, Nuo  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00020  

##### The Internet plays an increasingly important role in people's lives, but it also brings security problems. CAPTCHA, which stands for Completely Automated Public Turing Test to Tell Computers and Humans Apart, has been widely used as a security mechanism. This paper outlines the scientific and technological progress in both the design and attack of CAPTCHAs related to these three CAPTCHA categories. It first presents a comprehensive survey of recent developments for each CAPTCHA type in terms of usability, robustness and their weaknesses and strengths. Second, it summarizes the attack methods for each category. In addition, the differences between the three CAPTCHA categories and the attack methods will also be discussed. Lastly, this paper provides suggestions for future research and proposes some problems worthy of further study.

***

**_AVOCAD: Adaptive Terrorist Comms Surveillance and Interception using Machine Learning_**  
Azab, Ahmad; Maruatona, Omaru; Watters, Paul  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00021  

##### VoIP traffic classification is becoming increasingly important in the real-time detection and disruption of drug distribution and terrorism communications. To reduce waste and inefficiency, it is important that a VoIP call detection system is highly accurate and adaptive in order to distinctly differentiate VoIP and non-VoIP calls accurately and to detect newer versions of VoIP calls if a user uses a different VoIP application to avoid detection. However, a consistent disadvantage of VoIP classifiers is that they are only useful on the VoIP version or product that they were trained on. These systems are therefore unable to accurately classify previously unseen versions of the different VoIP products. In this paper we introduce Avocad, a novel methodology for detecting different VoIP traffic products such as Skype with high accuracy. Our approach uses machine learning classifiers and network statistical features and has comparable detection accuracy and speed to existing VoIP detection applications. The uniqueness of our method is that it detects untrained versions of a VoIP application, thus helping to optimise real-time detection of VoIP traffic. Results show that our method can record an F-Measure score of up to 0.996.

***

**_Malware Detection with Malware Images using Deep Learning Techniques_**  
He, Ke; Kim, Dong-Seong  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00022  

##### Driven by economic benefits, the number of malware attacks is increasing significantly on a daily basis. Malware Detection Systems (MDS) is the first line of defense against malicious attacks, thus it is important for malware detection systems to accurately and efficiently detect malware. Traditional MDS typically utilizes traditional machine learning algorithms that require feature selection and extraction, which are time-consuming and error-prone. Conventional deep learning based approaches typically use Recurrent Neural Network (RNN) which can be vulnerable to redundant API injection. Thus, we investigate the effectiveness of Convolutional Neural Networks (CNN) against redundant API injection. We designed a malware detection system that transforms malware files into image representations and classifies the image representation with CNN. The CNN is implemented with spatial pyramid pooling layers (SPP) to deal with varying size input. We evaluate the effectiveness of SPP and image color space (greyscale/RGB) by measuring the performance of our system on both unaltered data and adversarial data with redundant API injected. Results show that naive SPP implementation is impractical due to memory constraints and greyscale imaging is effective against redundant API injection.

***

**_IoT Device Identification via Network-Flow Based Fingerprinting and Learning_**  
Hamad, Salma Abdalla; Zhang, Wei Emma; Sheng, Quan Z.; Nepal, Surya  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00023  

##### Nowadays, increasing number of intelligent devices and smart sensors are connected by Internet of Things (IoT) techniques, and have helped people to manage and improve their lives. However, security issues are emerging in IoT, among which things identification is one of the challenges in that various solutions of different vendors, standards, protocols and communities groups coexist. In this paper, we address the challenge of IoT device identification by analyzing a sequence of packets from its high-level network traffic, i.e., network-flow data and extract unique flow-based features to create a fingerprint for each device. We adopt supervised machine learning techniques for the identification task. The proposed approach can automatically identify white-listed device types and individual device instances connected to a network. Moreover, we propose a security system model design that enables enforcement of rules for constraining the IoT device communications as per their given privileges. Unknown or suspicious devices with abnormal behaviour can be identified, and their communication is restricted for further monitoring. We show that the presented approach is effective in identifying white-listed device types with average accuracy up to 90.3% which is a 9.3% increase compared with the state-of-the-art technique. Individual device instances having the same model and vendor as well as unknown devices are correctly identified with minimal performance overhead.

***

**_Phishing URL Detection via CNN and Attention-Based Hierarchical RNN_**  
Huang, Yongjie; Yang, Qiping; Qin, Jinghui; Wen, Wushao  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00024  

##### Phishing websites have long been a serious threat to cyber security. For decades, many researchers have been devoted to developing novel techniques to detect phishing websites automatically. While state-of-the-art solutions can achieve superior performances, they require substantial manual feature engineering and are not adept at detecting newly emerging phishing attacks. Therefore, developing techniques that can detect phishing websites automatically and handle zero-day phishing attacks swiftly is still an open challenge in this area. In this work, we propose PhishingNet, a deep learning-based approach for timely detection of phishing Uniform Resource Locators (URLs). Specifically, we use a Convolutional Neural Network (CNN) module to extract character-level spatial feature representations of URLs; meanwhile, we employ an attention-based hierarchical Recurrent Neural Network(RNN) module to extract word-level temporal feature representations of URLs. We then fuse these feature representations via a three-layer CNN to build accurate feature representations of URLs, on which we train a phishing URL classifier. Extensive experiments on a verified dataset collected from the Internet demonstrate that the feature representations extracted automatically are conducive to the improvement of the generalization ability of our approach on newly emerging URLs, which makes our approach achieve competitive performance against other state-of-the-art approaches.

***

**_STDeepGraph: Spatial-Temporal Deep Learning on Communication Graphs for Long-Term Network Attack Detection_**  
Yao, Yepeng; Su, Liya; Lu, Zhigang; Liu, Baoxu  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00025  

##### Network communication data are high-dimensional and spatiotemporal, and their information content is often degraded by common traffic analysis methods. For long-term network attack detection based on network flows, it is important to extract a discriminative, high-dimensional intrinsic representation of such flows. This work focuses on a hybrid deep neural network design using a combination of a convolutional neural network (CNN) and long short-term memory (LSTM) with graph similarity measures to learn high-dimensional representations from the network traffic. In particular, examining a set of network flows, we commence by constructing a temporal communication graph and then computing graph kernel matrices. Having obtained the kernel matrices, for each graph, we use the kernel value between graphs and calculate graph characterization vectors by graph signal processing. This vector can be regarded as a kernel-based similarity embedding vector of the graph that integrates structural similarity information and leverages efficient graph kernel using the graph Laplacian matrix. Our approach exploits graph structures as the additional prior information, the graph Laplacian matrix for feature extraction and hybrid deep learning models for long-term information learning on communication graphs. Experiments on two real-world network attack datasets show that our approach can extract more discriminative representations, leading to an improved accuracy in a supervised classification task. The experimental results show that our method increases the overall accuracy by approximately 10%-15%.

***

**_Continuous Authentication of Embedded Software_**  
Ott, Karl; Mahapatra, Rabi  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00026  

##### This paper explores the use of frequency information of hardware performance counter data to enable continuous authentication (CA) in embedded software. Current approaches for CA are not targeted for use with embedded software. In order to be more suitable for embedded scenarios the proposed method uses short time Fourier transforms on streams of hardware performance counters. The frequency information is used to build an encoding to a state transition. These transitions are used to build a corresponding state machine which recognizes and authenticates the protected program continuously at run time. The method achieves an average successful authentication true positive rate of 97% with a 1.5% false positive rate.

***

**_CCGA: Clustering and Capturing Group Activities for DGA-Based Botnets Detection_**  
Liu, Zhicheng; Yun, Xiaochun; Zhang, Yongzheng; Wang, Yipeng  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00027  

##### Botnet is a part of the most destructive threats to network security and is often used in malicious activities. DGA-based botnet, which uses Domain Generation Algorithm (DGA) to evade detection, has become the main channel to carry out online crimes. In the past, many detection mechanisms focusing on domain features are proposed, but the potential problem is that the features extracting only from the domain names are insufficient and the enemies could easily forge them to disturb detection. In this paper, we propose a novel approach named CCGA to detect DGA-based botnet by leveraging the concerted group behaviors of infected hosts on DNS traffic. The analysis of group behaviors enhances the robustness of our system irrespective of various evasion techniques, such as fake-querying, packet encryption and noise generated by normal users. The proposed scheme associates hosts together in an unsupervised way and then uses supervised learning to distinguish whether it's a botnet. Our system is evaluated in a large ISP over two days and compared with the state of art FANCI. Experimental results show that CCGA can accurately and effectively detect DGA-based botnet in a real-world network. Our system also catches 5 unknown botnet groups and provides a novel method to verify them. Therefore, the system will provide an unique perspective on the current state of globally distributed malware, particularly the ones that use DNS.

***

**_Real-Time Detection of Malware Activities by Analyzing Darknet Traffic Using Graphical Lasso_**  
Han, Chansu; Shimamura, Jumpei; Takahashi, Takeshi; Inoue, Daisuke; Kawakita, Masanori; Takeuchi, Jun'ichi; Nakao, Koji  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00028  

##### Recent malware evolutions have rendered cyberspace less secure, and we are currently witnessing an increasing number of severe security incidents. To minimize the impact of malware activities, it is important to detect them promptly and precisely. We have been working on this issue by monitoring traffic coming into unused IP address spaces, i.e., the darknet. On our darknet, Internet-wide scans from malware are observed as if they are coordinated or working cooperatively. Based on this observation, our earlier method monitored network traffic arriving at our darknet, estimated the degree of cooperation between each pair of the source hosts, and detected significant changes in cooperation among source hosts as a sign of newly activated malware activities. However, this method does not work in real time, and thus, it is impractical. In this study, we extend our earlier work and propose an online processing algorithm, making it possible to detect malware activities in real time. In our evaluation, we measure the detection performance of the proposed method with our proof-of-concept implementation to demonstrate its feasibility and effectiveness in terms of detecting the rise of new malware activities in real time.

***

**_A Worst-Case Entropy Estimation of Oscillator-Based Entropy Sources: When the Adversaries Have Access to the History Outputs_**  
Zhu, Shaofeng; Chen, Hua; Xi, Wei; Chen, Meihui; Fan, Limin; Feng, Dengguo  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00029  

##### Entropy sources are designed to provide unpredictable random numbers for cryptographic systems. As an assessment of the sources, Shannon entropy is usually adopted to quantitatively measure the unpredictability of the outputs. In several related works about the entropy evaluation of ring oscillator-based (RO-based) entropy sources, authors evaluated the unpredictability with the average conditional Shannon entropy (ACE) of the source, moreover provided a lower bound of the ACE (LBoACE). However, in this paper, we have demonstrated that when the adversaries have access to the history outputs of the entropy source, for example, by some intrusive attacks, the LBoACE may overestimate the actual unpredictability of the next output for the adversaries. In this situation, we suggest to adopt the specific conditional Shannon entropy (SCE) which exactly measures the unpredictability of the future output with the knowledge of previous output sequences and so is more consistent with the reality than the ACE. In particular, to be conservative, we propose to take the lower bound of the SCE (LBoSCE) as an estimation of the worst-case entropy of the sources. We put forward a detailed method to estimate this worst-case entropy of RO-based entropy sources, which we have also verified by experiment on an FPGA device. We recommend to adopt this method to provide a conservative assessment of the unpredictability when the entropy source works in a vulnerable environment and the adversaries might obtain the previous outputs.

***

**_Power-Grid Controller Anomaly Detection with Enhanced Temporal Deep Learning_**  
He, Zecheng; Raghavan, Aswin; Hu, Guangyuan; Chai, Sek; Lee, Ruby  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00030  

##### Controllers of security-critical cyber-physical systems, like the power grid, are a very important class of computer systems. Attacks against the control code of a power-grid system, especially zero-day attacks, can be catastrophic. Earlier detection of the anomalies can prevent further damage. However, detecting zero-day attacks is extremely challenging because they have no known code and have unknown behavior. Furthermore, if data collected from the controller is transferred to a server through networks for analysis and detection of anomalous behavior, this creates a very large attack surface and also delays detection. In order to address this problem, we propose Reconstruction Error Distribution (RED) of Hardware Performance Counters (HPCs), and a data-driven defense system based on it. Specifically, we first train a temporal deep learning model, using only normal HPC readings from legitimate processes that run daily in these power-grid systems, to model the normal behavior of the power-grid controller. Then, we run this model using real-time data from commonly available HPCs. We use the proposed RED to enhance the temporal deep learning detection of anomalous behavior, by estimating distribution deviations from the normal behavior with an effective statistical test. Experimental results on a real power-grid controller show that we can detect anomalous behavior with high accuracy (>99.9%), nearly zero false positives and short (<; 360ms) latency.

***

**_When are Opaque Predicates Useful?_**  
Zobernig, Lukas; Galbraith, Steven D.; Russello, Giovanni  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00031  

##### Opaque predicates are a commonly used technique in program obfuscation, intended to add complexity to control flow and to insert dummy code or watermarks. However, there are many attacks known to detect opaque predicates and remove dummy code. We survey these attacks and argue that many types of programs cannot be securely obfuscated using opaque predicates. In particular we explain that most previous works on control flow obfuscation have introduced predicates that are easily distinguished from naturally occurring predicates in code, and hence easily removed by an attacker. We state two conditions that are necessary for a program to be suitable for control flow obfuscation. We give an integrated approach to control flow obfuscation that simultaneously obfuscates real predicates and introduces opaque predicates. The opaque predicates are indistinguishable from the obfuscated real predicates in the program. If an attacker applies the usual approaches (both static and dynamic) to identify and remove opaque predicates then they are likely to remove critical functionality and introduce errors. We have implemented our obfuscator in LLVM. We provide an analysis of the performance of the resulting obfuscated code.

***

**_An Ant Colony Algorithm Based Content Poisoning Mitigation in Named Data Networking_**  
Cui, Wenjing; Li, Yang; Zhang, Yan; Liu, Chang; Zhan, Mengqi  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00032  

##### Content Poisoning in Named Data Networking (NDN) can greatly reduce the effect of ubiquitous data caching, which is a prominent feature in NDN. Especially, when the NDN routers are compromised by attackers, finding a suitable scheme to mitigate such content poisoning in NDN routers is a challenge. In this paper, we proposed a scheme named Ant Colony Algorithm Based Content Poisoning Mitigation (ACO-CPM) in NDN. This scheme introduces the ACO to probe the safety transmission path and adjust the content retrieval process, by collecting the security information of all routers on the whole path. Meanwhile, the ACO-CPM can bypass the evil routers and therefore prevent the evil routers distributing illegal content any more. Plus, the proposed scheme can mitigate content poisoning by clearing bogus Data packets in the cache store during the path finding process. We implement our scheme by comparing it with ROM scheme in ndnSIM simulator. Simulation results show that our scheme can alleviate the content poisoning attacks caused by evil routers quickly and effectively.

***

**_A Heuristic Method for Network Modification Against Cyber Epidemic Attacks_**  
Yan, Dingyu; Liu, Feng  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00033  

##### Moving target defense (MTD) is considered as a disruptive defense technology to address the issue of an asymmetric situation between attacker and defender in cyberspace. However, most existing studies on the network-level MTD lack the theoretical modeling and analysis in a dynamical perspective. This study sets out to establish a dynamical model for the interaction between the network-level MTD and cyber epidemic attacks. In this paper, we provide a heuristic method for network modification against the cyber epidemic attack based on theoretical security conditions of the cyber dynamical system. The simulation results demonstrate that our network modification model can effectively resist multiple cyber epidemic attacks, which confirms the theoretical analysis.

***

**_Tracking Sensitive Information and Operations in Integrated Clinical Environment_**  
Li, Zhangtan; Cheng, Liang; Zhang, Yang  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00034  

##### Integrated Clinical Environment (ICE) is a standardized framework for achieving device interoperability in medical cyber-physical systems. The ICE utilizes high-level supervisory apps and a low-level communication middleware to coordinate medical devices. The need to design complex ICE systems that are both safe and effective has presented numerous challenges, including interoperability, context-aware intelligence, security and privacy. In this paper, we present a data flow analysis framework for the ICE systems. The framework performs the combination of static and dynamic analysis for the sensitive data and operations in the ICE systems. Our experiments demonstrate that the data flow analysis framework can record how the medical devices transmit sensitive data and perform misuse detection by tracing the runtime context of the sensitive operations.

***

**_Distributed Quantitative Information Flow Evaluation for Service Composition in Clouds_**  
Xi, Ning; Sun, Cong; Ma, Jianfeng; Lv, Jing  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00035  

##### Service composition provides a promising way for the delivery of IT applications to satisfy complex consumers' demands. The qualitative information flow control mechanism based on non-interference provides a solid security assurance on the propagation of customer's private data across multiple service providers. However, strict discipline limits the service availability and may cause a high failure rate on service composition. Therefore, we propose a distributed quantitative information flow evaluation approach for service composition across multiple clouds. The quantitative approach provides us a more precise way to evaluate the leakage and supports the customized disciplines on information flow security for the diverse requirements of different customers. Through the experiments and the proof, the results indicate that our approach can improve the availability of composite service effectively with affordable costs while satisfying the customer's security requirements.

***

**_A Topic-Based Unsupervised Learning Approach for Online Underground Market Exploration_**  
Huang, Shin-Ying; Ban, Tao  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00036  

##### Cyber fraud has become a lucrative form of illicit business by leveraging the Internet as a communication channel and as a result, causes significant losses to the economy. Criminals in the cyber fraud underground economy use online underground markets and other forms of social media to exchange and trade illegitimate information. Due to the high variability in the marketplaces and actors therein, analyzing these underground markets is challenging. To understand more about the underground economy of cyber fraud and its actors, we propose a topic-based hierarchical self-organizing map, which can well represent and visualize actors' similarity and thus, uncover their roles in the underground markets. We compare the proposed method with a topic-based social network analysis method for identifying the key users and their roles in the cyber fraud value chain. Experiments conducted on data from several online underground markets suggest that the proposed method can aid in identifying key actors in terms of roles, influence levels, and their social relationships.

***

**_Hybrid Logical Clocks for Database Forensics: Filling the Gap between Chain of Custody and Database Auditing_**  
Flores, Denys A.; Jhumka, Arshad  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00038  

##### Database audit records are important for investigating suspicious actions against transactional databases. Their admissibility as digital evidence depends on satisfying Chain of Custody (CoC) properties during their generation, collection and preservation in order to prevent their modification, guarantee action accountability, and allow third-party verification. However, their production has relied on auditing capabilities provided by commercial database systems which may not be effective if malicious users (or insiders) misuse their privileges to disable audit controls, and compromise their admissibility. Hence, in this paper, we propose a forensically-aware distributed database architecture that implements CoC properties as functional requirements to produce admissible audit records. The novelty of our proposal is the use of hybrid logical clocks, which compared with a previous centralised vector-clock architecture, has evident advantages as it (i) allows for more accurate provenance and causality tracking of insider actions, (ii) is more scalable in terms of system size, and (iii) although latency is higher (as expected in distributed environments), 70 per cent of user transactions are executed within acceptable latency intervals.

***

**_MURITE-Detector: Identifying User-Role in Information Theft Events of Mobile Network_**  
Cheng, Zhenyu; Chen, Xunxun; Zhang, Yongzheng; Li, Shuhao; Xu, Jian  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00039  

##### The emergence of information theft apps poses a serious threat to smartphone users. Most of information theft apps rely on network interfaces to steal users' privacy and use short message service (SMS) to implement command and control. In this paper, we propose an available and effective user-role identification model, MURITE-detector (Mobile User-Role in Information Theft Events detector), by using network flows and call detail records (CDRs) with convolutional neural network (CNN) algorithm. Firstly, we generate network flow vectors and CDR vectors from raw data sets, and then match them into node vectors. Subsequently, we use CNN to classify user-roles into: Sourcer, Transferer, Victim and Other. Because of command-and-control server invalidation and system version incompatibility, etc., most of the collected information theft apps can't run properly in reality. So we extract code modules from some of these apps, and then recode and compile them into ITM-capsule (Information Theft Modules capsule) to generate information theft network traffic. Finally, we obtain 37,384 information theft network flows, 61,635 benign network flows and 200,522 short message CDRs. We match these data through labels and construct two node vector sets A and B randomly. In addition, we also compare CNN with other machine learning algorithms, and the result shows that CNN performs better. In an evaluation of MURITE-detector, it gets an accuracy of 92.17%, a precision of 93.18% and a recall of 94.68%. Therefore, our model is suitable for identifying user-role in mobile network information theft events.

***

**_AIMED: Evolving Malware with Genetic Programming to Evade Detection_**  
Castro, Raphael Labaca; Schmitt, Corinna; Dreo, Gabi  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00040  

##### Genetic Programming (GP) has previously proved to achieve valuable results on the fields of image processing and arcade learning. Similarly, it can be used as an adversarial learning approach to evolve malware samples until static learning classifiers are no longer able to detect it. While the implementation is relatively simple compared with other Machine Learning approaches, results proved that GP can be a competitive solution to find adversarial malware examples comparing with similar methods. Thus, AIMED - Automatic Intelligent Malware Modifications to Evade Detection - was designed and imple-mented using genetic algorithms to evade malware classifiers. Our experiments suggest that the time to achieve adversarial malware samples can be reduced up to 50% compared to classic random approaches. Moreover, we implemented AIMED to generate adversarial examples using individual malware scanners as target and tested the evasive files against further classifiers from both research and industry. The generated examples achieved up to 82% of cross-evasion rates among the classifiers.

***

**_FIoT: Detecting the Memory Corruption in Lightweight IoT Device Firmware_**  
Zhu, Lipeng; Fu, Xiaotong; Yao, Yao; Zhang, Yuqing; Wang, He  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00041  
**[Best Security Track Paper Award]**

##### The IoT industry has developed rapidly in recent years, which has attracted the attention of security researchers. However, the researchers are hampered by the wide variety of IoT device operating systems and their hardware architectures. Especially for the lightweight IoT devices, many manufacturers do not provide the device firmware images, embedded firmware source code or even the develop documents. As a result, it hinders traditional static analysis and dynamic analysis techniques. In this paper, we propose a novel dynamic analysis framework, called FIoT, which aims at finding memory corruption vulnerabilities in lightweight IoT device firmware images. The key idea is dynamically run the binary code snippets through symbolic execution with carrying out a fuzzing test. Specifically, we generate code snippets through traversing the control-flow graph (CFG) in a backward manner. We improved the CFG recovery approach and backward slice approach for better performance. To reduce the influence of the binary firmware, FIoT leverages loading address determination analysis and library function identification approach. We have implemented a prototype of FIoT and conducted experiments. Our results show that FIoT can complete the Fuzzing test within 40 seconds in average. Considering 170 seconds for static analysis, FIoT can load and analyze a lightweight IoT firmware within 210 seconds in total. Furthermore, we illustrate the effectiveness of FIoT by applying it over 115 firmware images from 17 manufacturers. We have found 35 images exist memory corruptions, which are all zero-day vulnerabilities.

***

**_A Signature-Based Assistant Random Oversampling Method for Malware Detection_**  
Pang, Ying; Chen, Zhenxiang; Peng, Lizhi; Ma, Kun; Zhao, Chuan; Ji, Ke  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00042  

##### Mobile malware detection has attracted considerable attention because people are becoming increasingly inseparable from their mobile devices. Some researchers have endeavored to discover traces of malicious apps by harnessing the semantics of network traffic. However, network traffic data naturally exhibit imbalanced distributions. To date, studies that consider such imbalanced problem have been limited. Thus, we propose an oversampling method that can synthesize malicious instances based on a signature from the perspective of nominal features for mobile malware detection problem. First, we cluster the malicious network traffic datasets and generate signatures from each cluster. Second, the signatures are used to synthesize new malicious instances. The synthetic instances combined with instances obtained through the random oversampling method are used to enrich the minority class dataset. Finally, a semantic-based mobile malware detection model is built by using the rebalanced datasets. Our approach is compared with 10 other resampling algorithms on two network traffic datasets with different imbalanced ratios. Results show that the combination of the proposed method and the random oversampling algorithm has superior performance to the 10 other resampling algorithms for imbalanced malware detection.

***

**_A Security Framework for IoT Authentication and Authorization Based on Blockchain Technology_**  
Rashid, M. A.; Pajooh, Houshyar Honar  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00043  

##### The decentralized and distributed nature of the Blockchain technology makes it a suitable solution to improve the device-to-device communication security challenges. This work explores the possible application of blockchain technology to address the IoT security problems under the 5G cellular system. We propose a multi-layer security network model for IoT network based on blockchain technology. The proposed model addresses the problems associated with the actual deployment of the blockchain technology by dividing the IoT network into a multi-layer decentralized system. In the proposed model, we divide the network into K-unknown clusters using Evolutionary Computation algorithms which are Genetic Algorithms (GAs) and Particle Swarm Optimization (PSO). A local authentication mechanism is chosen for authentication and authorization purpose within each cluster handed by each Cluster Head (CH). The high security and credibility assurance of the blockchain technology provides an authentication mechanism for CHs communication with each other and Base Stations (BS) through a local blockchain implementation without a central authority. We also propose a global blockchain implementation for BSs communications. Finally, our proposal implements an open source blockchain platform Hyperledger Fabric to verify the proposed system.

***

**_Selective Adversarial Learning for Mobile Malware_**  
Khoda, Mahbub; Imam, Tasadduq; Kamruzzaman, Joarder; Gondal, Iqbal; Rahman, Ashfaqur  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00044  

##### Machine learning models, including deep neural networks, have been shown to be vulnerable to adversarial attacks. Adversarial samples are crafted from legitimate inputs by carefully introducing small perturbation to the input so that the classifier is fooled. Adversarial retraining, which involves retraining the classifier using adversarial samples, has been shown to improve the robustness of the classifier against adversarial attacks. However, it has been also shown that retraining with too many samples can lead to performance degradation. Hence, a careful selection of the adversarial samples that are used to retrain the classifier is necessary, yet existing works select these samples in a randomized fashion. In our work, we propose two novel approaches for selecting adversarial samples: based on the distance from cluster center of malware and based on the probability derived from a kernel based learning (KBL). Our experiment results show that both of our selective mechanisms for adversarial retraining outperform the random selection technique and significantly improve the classifier performance against adversarial attacks. In particular, selection with KBL delivers above 6% improvement in detection accuracy compared to random selection. The method proposed here has greater impact in designing robust machine learning system for security applications.

***

**_Credit Card Fraud Detection in E-Commerce_**  
Porwal, Utkarsh; Mukund, Smruthi  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00045  

##### Often the challenge associated with tasks like fraud detection is the lack of all likely patterns needed to train suitable supervised learning models. This problem accentuates when the fraudulent patterns are not only scarce, they also change over time. Change in fraudulent patterns is because fraudsters continue to innovate novel ways to circumvent measures put in place to prevent fraud. Limited data and continuously changing patterns makes learning significantly difficult. We hypothesize that good behavior does not change with time and data points representing good behavior have consistent spatial signature under different groupings. Based on this hypothesis we are proposing an approach that detects fraudulent patterns in large data sets by assigning a consistency score to each data point using an ensemble of clustering methods. Our main contribution is proposing a novel method that can detect outliers in large datasets and is robust to changing patterns. We also argue that area under the ROC curve, although a commonly used metric to evaluate outlier detection methods is not the right metric. Since outlier detection problems have a skewed distribution of classes, precision-recall curves are better suited because precision compares false positives to true positives (outliers) rather than true negatives (inliers) and therefore is not affected by the problem of class imbalance. The proposed approach is tested on a large real world credit card fraud detection dataset available through Kaggle. We report our performance on both AUPRC and AUROC and show meaningful improvements over the baseline methods.

***

**_Security and Performance Assessment of IP Multiplexing Moving Target Defence in Software Defined Networks_**  
Dishington, Cole; Sharma, Dilli P.; Kim, Dong Seong; Cho, Jin-Hee; Moore, Terrence J.; Nelson, Frederica F.  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00046  

##### With the interconnection of services and customers, network attacks are capable of large amounts of damage. Flexible Random Virtual IP Multiplexing (FRVM) is a Moving Target Defence (MTD) technique that protects against reconnaissance and access with address mutation and multiplexing. Security techniques must be trusted, however, FRVM, along with past MTD techniques, have gaps in realistic evaluation and thorough analysis of security and performance. FRVM, and two comparison techniques, were deployed on a virtualised network to demonstrate FRVM's security and performance trade-offs. The key results include the security and performance trade-offs of address multiplexing and address mutation. The security benefit of IP address multiplexing is much greater than its performance overhead, deployed on top of address mutation. Frequent address mutation significantly increases an attackers' network scan durations as well as effectively obfuscating and hiding network configurations.

***

**_Deep Android Malware Classification with API-Based Feature Graph_**  
Huang, Na; Xu, Ming; Zheng, Ning; Qiao, Tong; Choo, Kim-Kwang Raymond  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00047  

##### The rapid growth of Android malware apps poses a great security threat to users thus it is very important and urgent to detect Android malware effectively. What's more, the increasing unknown malware and evasion technique also call for novel detection method. In this paper, we focus on API feature and develop a novel method to detect Android malware. First, we propose a novel selection method for API feature related with the malware class. However, such API also has a legitimate use in benign app thus causing FP problem (misclassify benign as malware). Second, we further explore structure relationships between these APIs and map to a matrix interpreted as the hand-refined API-based feature graph. Third, a CNN-based classifier is developed for the API-based feature graph classification. Evaluations of a real-world dataset containing 3,697 malware apps and 3,312 benign apps demonstrate that selected API feature is effective for Android malware classification, just top 20 APIs can achieve high F1 of 94.3% under Random Forest classifier. When the available API features are few, classification performance including FPR indicator can achieve effective improvement effectively by complementing our further work.

***

**_Context-Aware Authentication Using Co-Located Devices_**  
Gomi, Hidehito; Yamaguchi, Shuji; Ogami, Wataru; Teraoka, Teruhiko; Higurashi, Tatsuru  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00048  

##### This paper proposes a context-aware authentication mechanism that verifies the identity of a user via the data generated by detecting short-range radio signals from nearby devices. Many projects on user authentication have aimed to improve security and usability. Although these projects have been successful in solving individual problems, authentication using passwords remains the most dominant authentication mechanism. So far, however, only a few attempts have been made at pursuing authentication using information about co-located devices, even though an increasingly large number of wearable and Internet-of-Things (IoT) devices is appearing in our computing environments. We explore the feasibility of the proposed mechanism by conducting in-house experiments. Our experimental results suggest that the information on co-location with nearby devices has good potential for implicitly and continuously authenticating a user while modulating the authentication accuracy.

***

**_Understanding the Influence of Graph Kernels on Deep Learning Architecture: A Case Study of Flow-Based Network Attack Detection_**  
Su, Liya; Yao, Yepeng; Lu, Zhigang; Liu, Baoxu  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00049  

##### Flow-based network attack detection technology is able to identify many threats in network traffic. Existing techniques have several drawbacks: i) rule-based approaches are vulnerable because it needs all the signatures defined for the possible attacks, ii) anomaly-based approaches are not efficient because it is easy to find ways to launch attacks that bypass detection, and iii) both rule-based and anomaly-based approaches heavily rely on domain knowledge of networked system and cyber security. The major challenge to existing methods is to understand novel attack scenarios and design a model to detect novel and more serious attacks. In this paper, we investigate network attacks and unveil the key activities and the relationships between these activities. For that reason, we propose methods to understand the network security practices using theoretic concepts such as graph kernels. In addition, we integrate graph kernels over deep learning architecture to exploit the relationship expressiveness among network flows and combine ability of deep neural networks (DNNs) with deep architectures to learn hidden representations, based on the communication representation graph of each network flow in a specific time interval, then the flow-based network attack detection can be done effectively by measuring the similarity between the graphs to two flows. The proposed study provides the effectiveness to obtain insights about network attacks and detect network attacks. Using two real-world datasets which contain several new types of network attacks, we achieve significant improvements in accuracies over existing network attack detection tasks.

***

**_Thermal Covert Channels Leveraging Package-on-Package DRAM_**  
Chen, Shuai; Xiong, Wenjie; Xu, Yehan; Li, Bing; Szefer, Jakub  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00050  

##### Package-on-Package (PoP) is an intergraded circuit packaging technique where multiple separate packages are mounted vertically one on top of the other, allowing for more compact system design and reduction in the distance between modules. However, this can introduce security vulnerabilities. In particular, this work shows that due to the close physical proximity of a System-on-a-Chip (SoC) package and a PoP DRAM that is on top of it, a thermal covert channel exists between the SoC and the PoP DRAM. The thermal covert channel can allow multiple cores in the SoC to communicate by modulating the temperature of the PoP DRAM. Especially, it is possible for one core in the SoC to generate heat patterns, which encode data that is to be transmitted, and another core to observe the transmitted pattern by measuring the decay rate of DRAM cells. Further, a covert channel can be established between a remote user and an SoC core by modulating the PoP DRAM temperature that then affects errors in PoP DRAM PUF fingerprints that are sent to the remote user for device authentication. Following these ideas, this paper introduces two new covert channels: first leveraging the observation of the number of bit flips in the PoP DRAM directly, and second through observation of bit flips induced in PoP DRAM PUF fingerprints. This paper also evaluates the DRAM cell decay rates in PoP DRAM, when heated by execution of different instructions on the processor cores in the SoC underneath the DRAM module. The evaluation was performed on three Raspberry Pi B+ boards, which have PoP DRAM. The evaluation was done both in office environment and in a thermal chamber. To mitigate the new channels, a set of defenses is discussed.

***

**_Continuous Authorization in Subject-Driven Data Sharing Using Wearable Devices_**  
Chowdhury, Mohammad Jabed Morshed; Colman, Alan; Kabir, Muhammad Ashad; Han, Jun; Sarda, Paul  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00051  

##### Sharing personal data with other people or organizations over the web has become a common phenomena of our modern life. This type of sharing is usually managed by access control mechanisms that include access control model and policies. However, these models are designed from the organizational perspective and do not provide sufficient flexibility and control to the individuals. Therefore, individuals often cannot control sharing of their personal data based on their personal context. In addition, the existing context-aware access control models usually check contextual condition once at the beginning of the access and do not evaluate the context during an on-going access. Moreover, individuals do not have control to define how often they want to evaluate the context condition for an ongoing access. Wearable devices such as Fitbit and Apple Smart Watch have recently become increasingly popular. This has made it possible to gather an individual's real-time contextual information (e.g., location, blood-pressure etc.) which can be used to enforce continuous authorization to the individual's data resources. In this paper, we introduce a novel data sharing policy model for continuous authorization in subject-driven data sharing. A software prototype has been implemented employing a wearable device to demonstrate continuous authorization. Our continuous authorization framework provides more control to the individuals by enabling revocation of on-going access to shared data if the specified context condition becomes invalid.

***

**_A Secure User-Centric Framework for Dynamic Service Provisioning in IoT Environments_**  
Sen, Amartya; Fletcher, Kenneth; Madria, Sanjay  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00052  

##### Internet of things (IoT) services are currently provisioned to users by having them specify their functional requirements like region of interest (ROI), and non-functional requirements such as quality of service (QoS). Selecting IoT services based on functionality is relatively mature. However, due to the abundance of functionally similar IoT services, it is challenging to select IoT services using QoS. Further, users' non-functional requirements maybe dynamic and vary over time. Although there are several QoS-driven web services selection methods, adopting such methods for IoT environments is not sufficient. This is because they are not designed to capture users' varying security preferences and are typically unable to explicitly tradeoff users' security and QoS preferences. This paper presents a comprehensive user-centric framework for secure and dynamic service provisioning in IoT environments, by allowing users to explicitly express their varying QoS and security preferences when selecting IoT services to support their applications. The novelty of the proposed user-centric framework lies in its ability to enable users personalize their security requirements for IoT services. To evaluate the feasibility of the proposed framework, an IoT case scenario is simulated.

***

**_Laughter in the Wild: A Study Into DoS Vulnerabilities in YAML Libraries_**  
Rasheed, Shawn; Dietrich, Jens; Tahir, Amjed  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00053  

##### YAML is a widely used serialisation language for data interchange and application configuration. Since its introduction, remote code execution vulnerabilities have been reported for YAML parsers, and countermeasures have been proposed. Even though denial-of-service (DoS) vulnerabilities affecting parsers for formats such as XML have been extensively studied, a similar investigation for YAML libraries is lacking. In this paper, we systematically study DoS vulnerabilities for 14 libraries for ten popular programming languages and as a result, we have discovered seven previously unknown vulnerabilities, which have been reported and are pending CVE identifiers.

***

**_HSDC–Net: Secure Anonymous Messaging in Online Social Networks_**  
Nosouhi, Mohammad Reza; Yu, Shui; Sood, Keshav; Grobler, Marthie  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00054  

##### Hiding contents of users' messages has been successfully addressed before, while anonymization of message senders remains a challenge since users do not usually trust ISPs and messaging application providers. To resolve this challenge, several solutions have been proposed so far. Among them, the Dining Cryptographers network protocol (DC-net) provides the strongest anonymity guarantees. However, DC-net suffers from two critical issues that makes it impractical, i.e., (1) collision possibility and (2) vulnerability against disruptions. Apart from that, we noticed a third critical issue during our investigation. (3) DC-net users can be deanonymized after they publish at least three messages. We name this problem the short stability issue and prove that anonymity is provided only for a few cycles of message publishing. As far as we know, this problem has not been identified in the previous research works. In this paper, we propose Harmonized and Stable DC-net (HSDC-net), a self-organizing protocol for anonymous communications. In our protocol design, we first resolve the short stability issue and obtain SDC-net, a stable extension of DC-net. Then, we integrate the Slot Reservation and Disruption Management sub-protocols into SDC-net to overcome the collision and security issues, respectively. The obtained HSDC-net protocol can also be integrated into blockchain-based cryptocurrencies (e.g. Bitcoin) to mix multiple transactions (belonging to different users) into a single transaction in such a way that the source of each payment is unknown. This preserves privacy of blockchain users. Our prototype implementation shows that HSDC-net achieves low latencies that makes it a practical protocol.

***

**_Automatic Anonymization of Textual Documents: Detecting Sensitive Information via Word Embeddings_**  
Hassan, Fadi; Sánchez, David; Soria-Comas, Jordi; Domingo-Ferrer, Josep  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00055  
**[Best Privacy Track Paper Award]**

##### Data sharing is key in a wide range of activities but raises serious privacy concerns when the data contain personal information. Anonymization mechanisms provide ways to transform the data so that identities and/or sensitive data are not disclosed (i.e., data are no longer personal). Even though a variety of methods have been proposed for structured data, automatic anonymization of unstructured text it still far from being solved. Textual data anonymization consists of detecting sensitive pieces of text, which are later removed and/or generalized. The detection process is especially challenging and it is usually based on classifiers pre-trained on large quantities of manually tagged data, which are able to detect a fixed set of (sensitive) entities such as names or locations. However, this approach is severely limited because sensitive information may appear in text in many forms and not all the appearances of a certain entity type may disclose information on the individual to be protected. In this work we propose a more general solution to text anonymization based on the notion of word embedding. The idea is to represent all the entities appearing in the document as word vectors that capture their semantic relationships. Then a particular entity (e.g. an individual or an organization) can automatically be protected by removing the other entities co-occurring in the document whose vectors are similar to the particular entity's vector. Furthermore, our method does not require manually tagged training data and is language-agnostic. We empirically evaluated our proposal on a collection of biographies. Our results show a significant improvement of the detection recall in comparison with classical approaches to text anonymization based on named entity recognition.

***

**_A Generic Information and Consent Framework for the IoT_**  
Morel, Victor; Cunche, Mathieu; Le Métayer, Daniel  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00056  

##### The Internet of Things (IoT) raises specific issues in terms of privacy, in particular with respect to information and consent. In this paper, we propose a generic framework for information and consent in the IoT which is protective both for data subjects and for data controllers. We present high level requirements for information and consent and several technical solutions to implement them. We also outline the design space and sketch a prototype implementation.

***

**_Poisoning Attack in Federated Learning using Generative Adversarial Nets_**  
Zhang, Jiale; Chen, Junjun; Wu, Di; Chen, Bing; Yu, Shui  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00057  

##### Federated learning is a novel distributed learning framework, where the deep learning model is trained in a collaborative manner among thousands of participants. The shares between server and participants are only model parameters, which prevent the server from direct access to the private training data. However, we notice that the federated learning architecture is vulnerable to an active attack from insider participants, called poisoning attack, where the attacker can act as a benign participant in federated learning to upload the poisoned update to the server so that he can easily affect the performance of the global model. In this work, we study and evaluate a poisoning attack in federated learning system based on generative adversarial nets (GAN). That is, an attacker first acts as a benign participant and stealthily trains a GAN to mimic prototypical samples of the other participants' training set which does not belong to the attacker. Then these generated samples will be fully controlled by the attacker to generate the poisoning updates, and the global model will be compromised by the attacker with uploading the scaled poisoning updates to the server. In our evaluation, we show that the attacker in our construction can successfully generate samples of other benign participants using GAN and the global model performs more than 80% accuracy on both poisoning tasks and main tasks.

***

**_Trustworthy Distributed Computations on Personal Data Using Trusted Execution Environments_**  
Ladjel, Riad; Anciaux, Nicolas; Pucheral, Philippe; Scerri, Guillaume  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00058  

##### Thanks to new regulations like GDPR, Personal Data Management Systems (PDMS) have become a reality. This decentralized way of managing personal data provides a de facto protection against massive attacks on central servers. But, when performing distributed computations, this raises the question of how to preserve individuals' trust on their PDMS? And how to guarantee the integrity of the final result? This paper proposes a secure computing framework capitalizing on the use of Trusted Execution Environments at the edge of the network to tackle these questions.

***

**_Privacy-Preserving Outsourcing Computation of QR Decomposition in the Encrypted Domain_**  
Zhang, Yonghong; Zheng, Peijia; Luo, Weiqi  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00059  

##### Signal processing in encrypted domain has become an important mean to protect privacy in an untrusted network environment. Due to the limitations of the underlying encryption methods, many useful algorithms that are sophisticated are not well implemented. Considering that QR decomposition is widely used in many fields, in this paper, we propose to implement QR decomposition in homomorphic encrypted domain. We firstly realize some necessary primitive operations in homomorphic encrypted domain, including division and open square operation. Gram-Schmidt process is then studied in the encrypted domain. We propose the implementation of QR decomposition in the encrypted domain by using the secure implementation of Gram-Schmidt process. We conduct experiments to demonstrate the effectiveness and analyze the performance of the proposed outsourced QR decomposition.

***

**_A Robust Watermarking Scheme for Encrypted JPEG Bitstreams with Format-Compliant Encryption_**  
Chen, Wenhao; Zeng, Bohang; Zheng, Peijia  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00060  

##### JPEG is a very popular image compression standard in Internet. To simultaneously provide image content protection and copyright protection, in this paper, we provide a robust watermarking scheme for encrypted JPEG bitstreams. The JPEG bitstream is enciphered with a format-compliant encryption to produce another JPEG bitstream with meaningless image content. The watermark embedder can directly embed the message into the encrypted JPEG stream by modifying the quantized DC coefficients without performing decryption or decompression in advanced. As for the watermark extraction, anyone who has the embedding key can extract the watermark from the encrypted watermarked JPEG bitstream and the decrypted watermarked JPEG bitstream. All the watermark embedding and extraction procedures are performed in the compressed domain. We conduct the experiments to verify the effectiveness of the proposed JPEG encryption and watermarking algorithms. Our experimental results also show that the decrypted watermarked images have high visual fidelity, and the watermarking scheme is robust against some common watermarking attacks.

***

**_Evolved Similarity Techniques in Malware Analysis_**  
Black, Paul; Gondal, Iqbal; Vamplew, Peter; Lakhotia, Arun  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00061  

##### Malware authors are known to reuse existing code, this development process results in software evolution and a sequence of versions of a malware family containing functions that show a divergence from the initial version. This paper proposes the term evolved similarity to account for this gradual divergence of similarity across the version history of a malware family. While existing techniques are able to match functions in different versions of malware, these techniques work best when the version changes are relatively small. This paper introduces the concept of evolved similarity and presents automated Evolved Similarity Techniques (EST). EST differs from existing malware function similarity techniques by focusing on the identification of significantly modified functions in adjacent malware versions and may also be used to identify function similarity in malware samples that differ by several versions. The challenge in identifying evolved malware function pairs lies in identifying features that are relatively invariant across evolved code. The research in this paper makes use of the function call graph to establish these features and then demonstrates the use of these techniques using Zeus malware.

***

**_A Robust and Reversible Watermarking Technique for Relational Dataset Based on Clustering_**  
Chai, Heyan; Yang, Shuqiang; Jiang, Zoe L.; Wang, Xuan  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00062  

##### With rapid information development, data sharing becomes a crucial part in the Internet. In the process of sharing, data ownership protection and data traceability are two key issues that need to be solved urgently. To address these problem, digital watermarking technology can be a solution. Digital watermarking is used to guard the rights of owners of digital products. Many robust and reversible watermarking techniques are proposed recently to ensure the rights and recover original data set. But most methods require primary keys of the data as a required parameter, resulting in original data not recovered and partial data not traceable against data structure attack. In this paper, a cluster-based robust and reversible watermarking (RRWC) technique for relational data has been proposed that provides a solution to two major function: ownership rights protection and partial data traceability. The unsupervised classification algorithm is used to group dataset, where the primary key of the data will not be used and the watermarks can be embedded with low distortion and high capacity. RRWC addresses malicious attacks, such as subset insertion attack, deletion attack, alteration attack and data structure attack. Experimental results demonstrate the effectiveness and robustness of RRWC against attacks.

***

**_TRIM, Wear Levelling and Garbage Collection on Solid State Drives: A Prediction Model for Forensic Investigators_**  
Nisbet, Alastair; Jacob, Rijo  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00063  

##### A fundamental requirement for evidence in any civil or criminal case is that nothing should be done to the evidence that changes it in any way. This may not always be possible and can be acceptable provided the changes can be justified. A forensic investigator who seizes digital evidence can normally secure that evidence and show that what is presented during a trial is identical to what was seized. In the case of solid state hard drives, there are 3 technologies that may alter the evidence: TRIM, Wear Levelling and Garbage Collection. All three of these moves or deletes data from the drive leading to evidence that is in a different state from when it was seized. This research examines these 3 processes and offers a guideline for predicting when they may be implemented, the effect of these processes and how to explain to a court what has occurred.

***

**_TwinPorter - An Architecture For Enabling the Live Migration of VMI-Based Monitored Virtual Machines_**  
Taubmann, Benjamin; Böhm, Alexander; Reiser, Hans P.  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00064  

##### Virtual machine introspection has evolved into a valuable tool for several purposes such as incident analysis and intrusion detection. In addition to that, there has been a lot of work that aims at enabling cloud tenants to do VMI on their virtual machines in IaaS-based clouds. Migration can be a required operation in cloud environments, for example, to keep service level agreements or to minimize power consumption. Common tools for migration of virtual machines do not provide support for coordinating VMI-based monitoring with migration. TwinPorter introduces a mechanism that migrates in parallel both the analyzing system and the analyzed system to the same target host. It ensures that the analyzed virtual machine never runs without being actively monitored and keeps the downtime of the analyzed system minimal by extending the live pre-copy based migration protocol of Xen. In our TwinPorter prototype, we measured an additional downtime of about 2 s of the monitored system during migration.

***

**_Defeating Fake Food Labels Using Watermarking and Biosequence Analysis_**  
Naidu, Vijay; Mohanty, Manoranjan  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00065  

##### Fake food label is one of the leading ways to distribute a low quality food item as a high quality branded product. For example, under fake labels, significantly higher amount of fake Manuka honey is sold than what is actually being produced. In this paper, we propose a scheme to combat the spread of such low quality food items by identifying fake food labels. In our scheme, a watermarking is inserted to a genuine food label and biosequence analysis is used to detect this watermark. The proposed biosequence analysis is such that it can detect duplicate labels, for example a photocopy of the genuine label. The proposed method works by converting a label image into biological amino acid form (e.g., to A, C, D, G, H, etc. form) and then extracting a signature from the label (which is represented in amino acid form) using biological tools. These signatures are then matched against a query label image to find out its originality. Experiment with honey food labels (honey watermarked dataset created by us) shows that the proposed method has true positive rate of 91:67%.

***

**_Finding Rats in Cats: Detecting Stealthy Attacks using Group Anomaly Detection_**  
Kuppa, Aditya; Grzonkowski, Slawomir; Asghar, Muhammad Rizwan; Le-Khac, Nhien-An  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00066  

##### Advanced attack campaigns span across multiple stages and stay stealthy for long time periods. There is a growing trend of attackers using off-the-shelf tools and pre-installed system applications (such as powershell and wmic) to evade the detection because the same tools are also used by system administrators and security analysts for legitimate purposes for their routine tasks. Such a dual nature of using these tools makes the analyst's task harder when it comes to spotting the difference between attack and benign activities. To start investigations, event logs can be collected from operational systems; however, these logs are generic enough and it often becomes impossible to attribute a potential attack to a specific attack group. Recent approaches in the literature have used anomaly detection techniques, which aim at distinguishing between malicious and normal behavior of computers or network systems. Unfortunately, anomaly detection systems based on point anomalies are too rigid in a sense that they could miss the malicious activity and classify the attack, not an outlier. Therefore, there is a research challenge to make better detection of malicious activities. To address this challenge, in this paper, we leverage Group Anomaly Detection (GAD), which detects anomalous collections of individual data points. Our approach is to build a neural network model utilizing Adversarial Autoencoder (AAE-alpha) in order to detect the activity of an attacker who leverages off-the-shelf tools and system applications. In addition, we also build Behavior2Vec and Command2Vec sentence embedding deep learning models specific for feature extraction tasks. We conduct extensive experiments to evaluate our models on real-world datasets collected for a period of two months. Our method discovered 2 new attack tools used by targeted attack groups and multiple instances of malicious activity. The empirical results demonstrate that our approach is effective and robust in discovering targeted attacks, pen-tests, and attack campaigns leveraging custom tools.

***

**_Learning Wear Patterns on Footwear Outsoles Using Convolutional Neural Networks_**  
Francis, Xavier; Sharifzadeh, Hamid; Newton, Angus; Baghaei, Nilufar; Varastehpour, Soheil  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00067  

##### Footwear outsoles acquire characteristics unique to the individual wearing them over time. Forensic scientists largely rely on their skills and knowledge-gained through years of experience-to analyse such characteristics on a shoeprint. In this work, we present a deep learning model that, for the first time, can predict the wear pattern on a unique dataset of shoeprints that captures the life and wear of a pair of shoes. We also present an additional architecture able to reconstruct the outsole back to its original state on a given week, and provide empirical evaluations of the performance of both models.

***

**_Anomaly Detection in Network Traffic Using Dynamic Graph Mining with a Sparse Autoencoder_**  
Jia, Guanbo; Miller, Paul; Hong, Xin; Kalutarage, Harsha; Ban, Tao  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00068  

##### Network based attacks on ecommerce websites can have serious economic consequences. Hence, anomaly detection in dynamic network traffic has become an increasingly important research topic in recent years. This paper proposes a novel dynamic Graph and sparse Autoencoder based Anomaly Detection algorithm named GAAD. In GAAD, the network traffic over contiguous time intervals is first modelled as a series of dynamic bipartite graph increments. One mode projection is performed on each bipartite graph increment and the adjacency matrix derived. Columns of the resultant adjacency matrix are then used to train a sparse autoencoder to reconstruct it. The sum of squared errors between the reconstructed approximation and original adjacency matrix is then calculated. An online learning algorithm is then used to estimate a Gaussian distribution that models the error distribution. Outlier error values are deemed to represent anomalous traffic flows corresponding to possible attacks. In the experiment, a network emulator was used to generate representative ecommerce traffic flows over a time period of 225 minutes with five attacks injected, including SYN scans, host emulation and DDoS attacks. ROC curves were generated to investigate the influence of the autoencoder hyper-parameters. It was found that increasing the number of hidden nodes and their activation level, and increasing sparseness resulted in improved performance. Analysis showed that the sparse autoencoder was unable to encode the highly structured adjacency matrix structures associated with attacks, hence they were detected as anomalies. In contrast, SVD and variants, such as the compact matrix decomposition, were found to accurately encode the attack matrices, hence they went undetected.

***

**_Characterizing the Limitations of Forensic Event Reconstruction Based on Log Files_**  
Latzo, Tobias; Freiling, Felix  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00069  
**[Best Forensics and Analytics Track Paper Award]**

##### Many forensic investigations include the analysis of log files. In a scenario of a single GNU/Linux server running Apache and Wordpress, we study which types of events can be inferred from log files and which ones not. Based on a formal definition of event reconstruction, we systematically compare which sources of logging information have which effect on the possibility to reconstruct events. Thereby, we attempt to characterize the limitations of forensic event reconstruction based on log files. The evaluation revealed that especially typical insider attacks leave few traces in common log files. Using traces from selected system calls considerably increases the possibility of incident detection.

***

**_Framework for the Retrieval of Social Media and Instant Messaging Evidence from Volatile Memory_**  
Thantilage, Ranul Deelaka; Le Khac, Nhien An  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00070  

##### The human society today has had to be confronted by the threat posed by criminals who are taking the advantages of social media and instant-messaging apps to conduct their criminal activities. In literature, there are many approaches for forensic acquisition and analysis of these apps. However, most of the approaches mainly focus on non-volatile storage media. Meanwhile, social media and instant-messaging platforms do not usually store information relating to social transactions in non-volatile bases. Hence, in this paper, we propose a framework for volatile memory forensics that is essential for the ready retrieval of evidence. Our approach is based on the retrieval of social media and instant-messaging evidence through the use of string search mechanism extended by the usage of regular expressions and the functionality of match groups. Our approach has been tested and proved to be effective with different social media apps on two popular operating systems: Windows and Mac.

***

**_PURE: Generating Quality Threat Intelligence by Clustering and Correlating OSINT_**  
Azevedo, Rui; Medeiros, Ibéria; Bessani, Alysson  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00071  

##### Cybersecurity has become a top priority for most organizations. To more aptly protect themselves, organizations are moving from reactive to proactive defensive measures. They are investing in cyber threat intelligence (CTI) to provide them forewarning about the risks they face, as well as to accelerate their response times in the detection of attacks. A mean to obtain CTI is the collection of open source intelligence (OSINT) information via threat intelligence platforms and their representation as indicators of compromise (IoC). However, most of these platforms are providing threat information with little to no processing, presenting thus limitations on generating useful quality data. This work presents an approach for improving OSINT processing to generate threat intelligence of quality in the form of enriched IoCs. This improved intelligence is obtained by correlating and combining IoCs coming from different OSINT feeds that contain information about the same threat, aggregating them into clusters, and then representing the threat information contained within those clusters in a single enriched IoC. The approach was implemented in the PURE platform and evaluated with 34 OSINT feeds, which allowed the creation of enriched IoCs that permitted the identification of attacks not previously possible by analyzing the IoCs individually.

***

**_An Adaptive Physical Layer Key Extraction Scheme for Smart Homes_**  
Zhao, Hong; Zhang, Yuexin; Huang, Xinyi; Xiang, Yang  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00073  
**[Best Emerging Technologies Track Paper Award] [Conference Best Overall Paper Award]**

##### The wireless transmission of home area networks contributes to the vulnerabilities of smart homes. As a result, smart homes are vulnerable to malicious attacks like eavesdropping. To secure the transmissions, secret keys should be established for smart home devices. In practical smart home applications, smart home devices might be resource-constrained devices. Thus, the lightweight key establishment schemes are preferred. Typically, lightweight physical layer key extraction schemes can be employed by the smart home devices. However, the key generation rate of the schemes is low. To improve the key generation rate, in this paper we propose an adaptive physical layer key extraction scheme for smart homes by making use of the Received Signal Strength (RSS). Specifically, in our scheme, two smart home devices collect the RSS measurements by probing with each other. Then, the collected measurements are quantized by running the proposed Self-adaptive Lossless Quantization algorithm. Completing these operations, the two smart home devices can obtain the secret key. In our scheme, we design the self-adaptive lossless quantization algorithm to improve the key generation rate. To show the practicality of the new scheme, we implement it using the Ralink WiFi cards. Additionally, we analyse the performance of our scheme and compare it with that of other related works.

***

**_Making Monero Hard-to-Trace and More Efficient_**  
Liu, Qingyi; Liu, Zhen; Long, Yu; Liu, Zhiqiang; Sui, Zhimei; Sun, Shifeng; Tang, Shuyang; Gu, Dawu  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00075  

##### Most cryptocurrencies have successfully provided anonymity in a permissionless environment. However, the pattern of transfers is open to publicity. To face this issue, Monero was proposed to provide untraceability from ring signatures by introducing mixins to obfuscate addresses. By temporal analysis, however, the transfer pattern can still be partially revealed in a stochastic approach due to inappropriate selections of mixins. Thereby, each flow of coins can be traced with high probability which disobeys the untraceability principle of Monero. In this work, we propose a hard-to-trace protocol based on Monero where each transaction output is assembled into a fixed ring set. In this way, inappropriate mixins are forbidden, and thereby the temporal analysis is resisted. Apart from the traceability issue, Monero is also challenged due to its growing difficulty of block assembly. To guarantee the privacy, ""key images"" with a considerable size have to be stored by each miner to verify transactions and assemble blocks. As blockchain grows, the number of key images increases and a significant burden has already been caused, making the block assembly of Monero inefficient to most miners. Aimed at a more practical block assembly, our protocol allows key image truncations to facilitate transaction verifications.

***

**_PIT: A Probe Into Internet of Things by Comprehensive Security Analysis_**  
Sachidananda, Vinay; Bhairav, Suhas; Ghosh, Nirnay; Elovici, Yuval  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00076  

##### One of the major issues which are hindering widespread and seamless adoption of Internet of Thing (IoT) is security. The IoT devices are vulnerable and susceptible to attacks which became evident from a series of recent large-scale distributed denial-of-service (DDoS) attacks, leading to substantial business and financial losses. Furthermore, in order to find vulnerabilities in IoT, there is a lack of comprehensive security analysis framework. In this paper, we present a modular, adaptable and tunable framework, called PIT, to probe IoT systems at different layers of design and implementation. PIT consists of several security analysis engines, viz., penetration testing, fuzzing, static analysis, and dynamic analysis and an exploitation engine to discover multiple IoT vulnerabilities, respectively. We also develop a novel grey-box fuzzer, called Applica, as a part of the fuzzing engine to overcome the limitations of the present day fuzzers. The proposed framework has been evaluated on a real-world IoT testbed comprising of the state-of-the-art devices. We discovered several network and system-level vulnerabilities such as Buffer Overflow, Denial-of-Service, SQL Injection, etc., and successfully exploited them to demonstrate the presence of security loopholes in the IoT devices.

***

**_A Probability Prediction Based Mutable Control-Flow Attestation Scheme on Embedded Platforms_**  
Hu, Jianxing; Huo, Dongdong; Wang, Meilin; Wang, Yazhe; Zhang, Yan; Li, Yu  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00077  

##### Control-flow attacks cause powerful threats to the software integrity. Remote attestation for control flow is a crucial security service for ensuring the software integrity on embedded platforms. The fine-grained remote control-flow attestation with execution-profiling Control-Flow Graph (CFG) is applied to defend against control-flow attacks. It is a safe scheme but it may influence the runtime efficiency. In fact, we find out only the vulnerable parts of a program need being attested at costly fine-grained level to ensure the security, and the remaining normal parts just need a lightweight coarse-grained check to reduce the overhead. We propose Mutable Granularity Control-Flow Attestation (MGC-FA) scheme, which bases on a probabilistic model, to distinguish between the vulnerable and normal parts in the program and combine fine-grained and coarse-grained control-flow attestation schemes. MGC-FA employs the execution-profiling CFG to apply the remote control-flow attestation scheme on embedded devices. MGC-FA is implemented on Raspberry Pi with ARM TrustZone and the experimental results show its effect on balancing the relationship between runtime efficiency and control-flow security.

***

**_A Secure and Practical Blockchain Scheme for IoT_**  
Liu, Hongyang; Shen, Feng; Liu, Zhiqiang; Long, Yu; Liu, Zhen; Sun, Shifeng; Tang, Shuyang; Gu, Dawu  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00078  

##### With features such as decentralization, consistency, tamper resistance, non-repudiation, and pseudonym, blockchain technology has the potential to strengthen the Internet of Things (IoT) significantly, thus opening an intriguing research area in the integration of blockchain and IoT. However, most existing blockchain schemes were not dedicated to the IoT ecosystem and hence could not meet the specific requirements of IoT. This paper aims to fix the gap. Inspired by Chainspace, a blockchain platform which could be applicable in IoT, VChain is proposed, a novel blockchain scheme suitable for IoT which is more secure, concrete, and practical compared with Chainspace. Specifically, in VChain, a two-layer BFT-based consensus protocol with HoneyBadger BFT protocol is proposed and a collective signature scheme as building blocks. The designs above allow for supporting faulty-shards-tolerance and asynchronous network model, which could not be sustained in Chainspace, and keeping high efficiency as well. Moreover, the sharding strategy presented in VChain, different from that in RapidChain, which adopts the energy-consuming PoW mechanism for sharding, is environmentfriendly and thus makes VChain fit for IoT well. Last but not least, VChain also inherits the merits of Chainspace to separate the execution and verification of smart contracts for privacy.

***

**_A Typo-Tolerant Password Authentication Scheme with Targeted Error Correction_**  
Chen, Xin; Huang, Xinyi; Mu, Yi; Wang, Ding  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00079  

##### Password-based authentication is used in almost every computer system. However, users might not always type their passwords correctly. In order to improve the accuracy of password authentication without reducing security, Chatterjee et al. (IEEE S&P'16); Guan et al. (SecureComm'17) proposed typo-tolerant schemes, respectively. However, these schemes do not consider the impact of personal information on password usages when generating candidate sets, while Wang et al. (NDSS'18) show that 36.95% 51.43% of users employ their personal information to generate passwords. In this paper, we propose a typo-tolerant password authentication scheme with targeted error correction. Our scheme focuses on two aspects: fuzzy judgment and error correction. During the process of password authentication, we first use fuzzy judgment to determine whether the input password contains personal information, and then correct the password according to the result of the fuzzy judgment. The error correction is divided into two types: with personal information and without personal information. Our experimental results show that our solution, when correcting the password entered by the user, is generally able to achieve higher accuracy. When considering the four main errors occurring in the mobile dataset and the general dataset, the average correct rate is 96.29%. The analysis illustrates that the average success proportion of targeted error correction (68.56%) is two times higher than the average success proportion of non-targeted error correction (31.44%), indicating the feasibility of our scheme.

***

**_A Correctable Public Blockchain_**  
Marsalek, Alexander; Zefferer, Thomas  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00080  

##### A key property of current blockchain solutions is the immutability of data stored in the blockchain. While this is a desired feature e.g. for crypto currencies, it can be a show stopper for other use cases that still require ex-post correction or removal of stored data. Existing proposals for redactable blockchains address this issue, but support the correction of specific types of stored data only. To overcome these limitations, we propose and introduce a correctable blockchain architecture that supports correction of arbitrary data. The proposed solution uses a consensus-enforced voting mechanism for decentralized decision making on requested data corrections. Information on applied corrections is stored in a second chain, which ensures that the corrected chain can still be validated successfully. We have verified the security of the proposed correctable blockchain architecture by means of a detailed security analysis. Furthermore, we have evaluated the proposed solution by means of a first reference implementation, which demonstrates the solution's feasibility. First experiments conducted with this reference implementation indicate that the added data-correction functionality has only negligible impacts on the overall performance.

***

**_A Logic for Secure Stratified Systems and its Application to Containerized Systems_**  
Lauer, Hagen; Sakzad, Amin; Rudolph, Carsten; Nepal, Surya  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00081  

##### We present the design and verification of a secure integrity measurement system for containerized systems. Containerization of applications allows fine-graded deployment and management of services and dependencies but also needs fine-graded security mechanisms. In this paper we provide formal abstractions for containerized systems by introducing LS3, a formal model and logic with sub-domain constructs to represent stratified systems and their interactions. Using our formal model, we prove that the widely used Trusted Computing Group (TCG) based Integrity Measurement Architecture (IMA) securely extends trust measurements from boot to applications. However, IMA is not designed to make domain specific trust measurements and is consequently incapable of creating domain specific integrity reports. Current research aims to improve either trust measurement performance or comprehensiveness but does not improve the measurement function and its semantics to allow remote verification of measurements per domain. We present an enhanced trust measurement architecture design, which produces domain specific integrity measurements suitable for fine-graded remote attestation. Providing domain specific integrity reports eases system and sub-system verification and yields desirable properties such as measurement log stability and constrained disclosure for multi-domain systems. We verify and prove the correctness of our trust measurement architecture using our formal model.

***

**_A Secure Decentralized Trustless E-Voting System Based on Smart Contract_**  
Lyu, Jiazhuo; Jiang, Zoe L.; Wang, Xuan; Nong, Zhenhao; Au, Man Ho; Fang, Junbin  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00082  

##### E-voting plays a significant role in social activities. The trust of the voting results and the privacy of each voter are always the most important concerns in designing secure e-voting system. In this paper, we design a decentralized trustless e-voting system based on the smart contract. To guarantee the correctness of the voting result, the smart contract on Blockchain is used to provide a trusted public bulletin board and trusted computing environment. To hide the identity of each voter as well as avoid multiple voting, linkable ring signature is used for each voter to group a signing ring. In addition, to make sure that all voters will see the voting result at the same time, or nobody can get it, threshold encryption without trusted third party is used to make secret-key secretly before tally stage. Moreover, the trust (power) of the voting system is separated to all voters. Even though some of them are malicious, the final result will not be influenced. The contract is deployed on the Ethereum private network. Some feasibility and cost analysis on money and time are also provided.

***

**_(Linkable) Ring Signature from Hash-Then-One-Way Signature_**  
Lu, Xingye; Au, Man Ho; Zhang, Zhenfei  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00083  

##### In this paper, we revisit the generic construction of ring signatures from hash-then-one-way type (Type-H) signatures proposed by Abe et al. (AOS) in 2004 and made the following contributions. First, we give a proof for the generic construction, in a strengthened security model. Previously, this was only done for concrete instantiations, in a weaker model. Second, we extend AOS's framework to generically construct one-time linkable ring signatures from Type-H signatures and one-time signatures. Lastly, we instantiate the generic construction with an NTRU-based Type-H signature: Falcon and obtain a post-quantum linkable ring signature scheme. Our analysis shows that the resulting linkable signature is more efficient than any existing lattice based solutions for small to moderate number of users.

***

**_Constructing Strong Designated Verifier Signatures from Key Encapsulation Mechanisms_**  
Gong, Borui; Au, Man Ho; Xue, Haiyang  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00084  

##### A designated verifier signature (DVS) allows a signer to convince a verifier that a message has been endorsed in a way that the conviction cannot be transferred to any third party. This is achieved by the property that the signature can be generated by one of them. Since DVS is publicly verifiable, a valid DVS implies that the signature must be created by either the signer or the verifier. To enhance privacy of signers' identity, a strong DVS (SDVS) disallows public verification. In this paper, we investigate various aspects of SDVS with making two contributions. Firstly, we consider SDVS in the multi-user setting and propose two strengthened models, namely, multi-user and multi-user+. To illustrate the significance of our models, we show that it is possible to forge an SDVS when the attacker is given signatures from an honest signer to multiple dishonest verifiers. Secondly, we give a generic construction of SDVS from Key Encapsulation Mechanism (KEM) and Pseudorandom Function (PRF) in the standard model. Our generic construction is secure in the multi-user setting if the underlying KEM and PRF are secure. We also give instantiations based on DDH and LWE assumptions respectively.

***

**_MedBloc: A Blockchain-Based Secure EHR System for Sharing and Accessing Medical Data_**  
Huang, Jack; Qi, Yuan Wei; Asghar, Muhammad Rizwan; Meads, Andrew; Tu, Yu-Cheng  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00085  

##### In New Zealand, there is currently no shared Electronic Health Record (EHR) system integrated between major healthcare organisations, such as hospitals, medical centres, and specialists. Thanks to its characteristics, blockchain technology can be a suitable platform for building a large-scale EHR system for New Zealand. In this paper, we present MedBloc, a blockchain-based secure EHR system that enables patients and healthcare providers to access and share health records in a usable yet privacy-preserving manner. MedBloc captures a longitudinal view of the patient's health story and enables patients to give or withdraw consent for regulating access to their records. To protect medical data, MedBloc uses an encryption mechanism and enforces a smart contract based access control mechanism for regulating access. MedBloc not only demonstrates how the blockchain can establish New Zealand's first shared EHR system but it shows how blockchain can potentially disrupt the entire medical technology domain.

***

**_CloudSafe: A Tool for an Automated Security Analysis for Cloud Computing_**  
An, Seongmo; Eom, Taehoon; Park, Jong Sou; Hong, Jin Bum; Nhlabatsi, Armstrong; Fetais, Noora; Khan, Khaled M.; Kim, Dong Seong  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00086  

##### Cloud computing has been adopted widely, providing on-demand computing resources to improve performance and reduce operational costs. However, these new functionalities also bring new ways to exploit the cloud computing environment. To assess the security of the cloud, graphical security models can be used, such as Attack Graphs and Attack Trees. However, existing models do not consider all types of threats, and also automating the security assessment functions are difficult. In this paper, we propose a new security assessment tool for the cloud named CloudSafe, an automated security assessment for the cloud. The CloudSafe tool collates various tools and frameworks to automate the security assessment process. To demonstrate the applicability of the CloudSafe, we conducted security assessment in Amazon AWS, where our experimental results showed that we can effectively gather security information of the cloud and carry out security assessment to produce security reports. Users and cloud service providers can use the security report generated by the CloudSafe to understand the security posture of the cloud being used/provided.

***

**_Security and Performance Modeling and Optimization for Software Defined Networking_**  
Eom, Taehoon; Hong, Jin Bum; An, SeongMo; Park, Jong Sou; Kim, Dong Seong  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00087  

##### Software Defined Networking (SDN) provides new functionalities to efficiently manage the network traffic, which can be used to enhance the networking capabilities to support the growing communication demands today. But at the same time, it introduces new attack vectors that can be exploited by attackers. Hence, evaluating and selecting countermeasures to optimize the security of the SDN is of paramount importance. However, one should also take into account the trade-off between security and performance of the SDN. In this paper, we present a security optimization approach for the SDN taking into account the trade-off between security and performance. We evaluate the security of the SDN using graphical security models and metrics, and use queuing models to measure the performance of the SDN. Further, we use Genetic Algorithms, namely NSGA-II, to optimally select the countermeasure with performance and security constraints. Our experimental analysis results show that the proposed approach can efficiently compute the countermeasures that will optimize the security of the SDN while satisfying the performance constraints.

***

**_A Dynamic Access Control Policy Model for Sharing of Healthcare Data in Multiple Domains_**  
Salehi Shahraki, Ahmad; Rudolph, Carsten; Grobler, Marthie  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00088  

##### Authorization models have been developed to prevent unauthorized access to valuable resources such as electronic healthcare records (EHRs). In an applied environment, such as the healthcare domain, there are several types of authorities that generate EHRs and other security parameters via central authority for their users and the attribute authorities. The use of a central authority introduces several challenges in terms of security and privacy due to the increased risk if the central authority is compromised or corrupted. Observing that this research area has not been well addressed to date, we propose and present the first decentralized multi-authority attribute-based access control (DMA-ABAC) model based on the policy model, which enables authorities to independently control their security settings. We present an access control framework for a dynamic cross-domain authorization model that combines Attribute-Based Access Control (ABAC) and Attribute-Based Group Signature (ABGS). This combination aims at providing flexible access control with resistance against reply and third party storage attacks and attribute collusion, and enhanced access control, privacy and selective attributes.

***

**_Tackling Data Inefficiency: Compressing the Bitcoin Blockchain_**  
Marsalek, Alexander; Zefferer, Thomas; Fasllija, Edona; Ziegler, Dominik  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00089  

##### In blockchain-based solutions, the amount of data stored in the blockchain increases steadily. Considerable amounts of data accordingly need to be download and stored at decentralized nodes to carry out meaningful validations. For the Bitcoin blockchain, approximately 197 GB must currently be downloaded and processed by any node aiming to fully verify the correctness of stored transactions. This represents an emerging problem with respect to resource-constrained thin clients that lack the required download or storage capacities, but with which meaningful validations still need to be carried out. This problem will gain even more relevance in the future, as blockchain technology is applied to new domains such as the Internet of Things (IoT) that necessitate the use of thin clients. We address this emerging problem by proposing a novel compressible blockchain architecture. In our proposal, we use a snapshot-based approach, to create snapshots of the blockchain at regular intervals and store them in blocks. These blocks are chained, forming a second blockchain that is linked to the primary chain. In this way, the amount of data that needs to be downloaded and stored by decentralized nodes is reduced considerably, while the full validation of the entire blockchain still remains feasible. In this paper, we describe the proposed compressible blockchain architecture in detail. We conducted evaluations that demonstrate the feasibility of the proposed solution and show its advantages over related approaches introduced in the literature. Overall, our design can be used to reduce the size of the blockchain by up to 93%, facilitating secure blockchain-based applications even on resource-constrained thin clients such as IoT devices.

***

