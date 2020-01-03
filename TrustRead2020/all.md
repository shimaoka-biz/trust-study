## [CRiSIS2018](CRiSIS2018.md) The 13th International Conference on Risks and Security of Internet and Systems
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

## [POST2019](POST2019.md) 8th International Conference on Principles of Security and Trust
Link: [[Proceedings](https://link.springer.com/book/10.1007/978-3-030-17138-4)]
[[Conference](https://www.etaps.org/2019/post)]
[[Awards](https://www.etaps.org/2019/test-of-time-award)]  
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

## [POST2018](POST2018.md) 7th International Conference on Principles of Security and Trust
Link: [[Proceedings](https://link.springer.com/book/10.1007/978-3-319-89722-6)]
[[Conference](https://www.etaps.org/2018/post)]
[[Awards](https://www.etaps.org/2018/test-of-time-award)]  
***
**_Formal Verification of Integrity-Preserving Countermeasures Against Cache Storage Side-Channels_**  
Nemati, Hamed; Baumann, Christoph; Guanciale, Roberto; Dam, Mads  
https://link.springer.com/chapter/10.1007/978-3-319-89722-6_5  

##### Formal verification of systems-level software such as hypervisors and operating systems can enhance system trustworthiness. However, without taking low level features like caches into account the verification may become unsound. While this is a well-known fact w.r.t. timing leaks, few works have addressed latent cache storage side-channels, whose effects are not limited to information leakage. We present a verification methodology to analyse soundness of countermeasures used to neutralise these channels. We apply the proposed methodology to existing countermeasures, showing that they allow to restore integrity of the system. We decompose the proof effort into verification conditions that allow for an easy adaption of our strategy to various software and hardware platforms. As case study, we extend the verification of an existing hypervisor whose integrity can be tampered using cache storage channels. We used the HOL4 theorem prover to validate our security analysis, applying the verification methodology to a generic hardware model.

***

**_SoK: Unraveling Bitcoin Smart Contracts_**  
Atzei, Nicola; Bartoletti, Massimo; Cimoli, Tiziana; Lande, Stefano; Zunino, Roberto  
https://link.springer.com/chapter/10.1007/978-3-319-89722-6_9  

##### Albeit the primary usage of Bitcoin is to exchange currency, its blockchain and consensus mechanism can also be exploited to securely execute some forms of smart contracts. These are agreements among mutually distrusting parties, which can be automatically enforced without resorting to a trusted intermediary. Over the last few years a variety of smart contracts for Bitcoin have been proposed, both by the academic community and by that of developers. However, the heterogeneity in their treatment, the informal (often incomplete or imprecise) descriptions, and the use of poorly documented Bitcoin features, pose obstacles to the research. In this paper we present a comprehensive survey of smart contracts on Bitcoin, in a uniform framework. Our treatment is based on a new formal specification language for smart contracts, which also helps us to highlight some subtleties in existing informal descriptions, making a step towards automatic verification. We discuss some obstacles to the diffusion of smart contracts on Bitcoin, and we identify the most promising open research challenges.

***

**_A Semantic Framework for the Security Analysis of Ethereum Smart Contracts_**  
Grishchenko, Ilya; Maffei, Matteo; Schneidewind, Clara  
https://link.springer.com/chapter/10.1007/978-3-319-89722-6_10  

##### Smart contracts are programs running on cryptocurrency (e.g., Ethereum) blockchains, whose popularity stem from the possibility to perform financial transactions, such as payments and auctions, in a distributed environment without need for any trusted third party. Given their financial nature, bugs or vulnerabilities in these programs may lead to catastrophic consequences, as witnessed by recent attacks. Unfortunately, programming smart contracts is a delicate task that requires strong expertise: Ethereum smart contracts are written in Solidity, a dedicated language resembling JavaScript, and shipped over the blockchain in the EVM bytecode format. In order to rigorously verify the security of smart contracts, it is of paramount importance to formalize their semantics as well as the security properties of interest, in particular at the level of the bytecode being executed.In this paper, we present the first complete small-step semantics of EVM bytecode, which we formalize in the F* proof assistant, obtaining executable code that we successfully validate against the official Ethereum test suite. Furthermore, we formally define for the first time a number of central security properties for smart contracts, such as call integrity, atomicity, and independence from miner controlled parameters. This formalization relies on a combination of hyper- and safety properties. Along this work, we identified various mistakes and imprecisions in existing semantics and verification tools for Ethereum smart contracts, thereby demonstrating once more the importance of rigorous semantic foundations for the design of security verification techniques.

***

**_Tool Demonstration: FSolidM for Designing Secure Ethereum Smart Contracts_**  
Mavridou, Anastasia; Laszka, Aron  
https://link.springer.com/chapter/10.1007/978-3-319-89722-6_11  

##### Blockchain-based distributed computing platforms enable the trusted execution of computation—defined in the form of smart contracts—without trusted agents. Smart contracts are envisioned to have a variety of applications, ranging from financial to IoT asset tracking. Unfortunately, the development of smart contracts has proven to be extremely error prone. In practice, contracts are riddled with security vulnerabilities comprising a critical issue since bugs are by design non-fixable and contracts may handle financial assets of significant value. To facilitate the development of secure smart contracts, we have created the FSolidM framework, which allows developers to define contracts as finite state machines (FSMs) with rigorous and clear semantics. FSolidM provides an easy-to-use graphical editor for specifying FSMs, a code generator for creating Ethereum smart contracts, and a set of plugins that developers may add to their FSMs to enhance security and functionality.

***

## [STM2019](STM2019.md) 15th International Workshop on Security and Trust Management
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

## [STM2018](STM2018.md) 14th International Workshop on Security and Trust Management
Link: [[Proceedings](https://link.springer.com/book/10.1007/978-3-030-01141-3)]
[[Conference](https://www.nics.uma.es/pub/stm18/index.html)]
Awardなし  
***
**_Tux: Trust Update on Linux Booting_**  
Lee, Suhho; Yoo, Seehwan  
https://link.springer.com/chapter/10.1007/978-3-030-01141-3_7  

##### Preserving integrity is one of the essential requirements in trusted computing. However, When it comes to system update, even with the state-of-the-art integrity management system such as OpenCIT cannot properly manage integrity. This is because the updates are not transparent to the remote attestation server and the integrity value is not updated according to the updates.This paper presents Trust Update on Linux booting, TUX. TUX collaboratively manages the integrity along with the kernel update, so that the update is transparent to the attestation server. With TUX, we can successfully maintain trust for the managed machines, even with frequent OS kernel updates. Also, TUX guarantees robust verified and measured boot to safeguard the integrity of a system’s booting process.

***

## [TrustBus2019](TrustBus2019.md) 16th International Conference on Trust and Privacy in Digital Business
Link: [[Proceedings](https://link.springer.com/book/10.1007/978-3-030-27813-7)]
[[Conference](http://www.dexa.org/trustbus2019)]
Awardなし  
***
**_I Did Not Accept That: Demonstrating Consent in Online Collection of Personal Data_**  
Jesus, Vitor; Mustare, Shweta  
https://link.springer.com/chapter/10.1007/978-3-030-27813-7_4  

##### Privacy in online collection of personal data is currently a much debated topic considering, amongst other reasons, the incidents with well known digital organisations, such as social networks and, in Europe, the recent EU/GDPR regulation. Among other required practices, explicit and simply worded consent from individuals must be obtained before collecting and using personal information. Further, individuals must also be given detailed information about what, how and what for data is collected. Consent is typically obtained at the collection point and, at a single point in time (ignoring updates), associated with Privacy Policies or End-User Agreements. At any moment, both the user and the organization should be able to produce evidence of this consent. This proof should not be disputable which leads us to strong cryptographic properties.The problem we discuss is how to robustly demonstrate such consent was given. We adapt fair-exchange protocols to this particular problem and, upon an exchange of personal data, we are able to produce a cryptographic receipt of acceptance that any party can use to prove consent and elicit non-repudiation. We discuss two broad strategies: a pure peer-to-peer scheme and the use of a Trusted Third Party.

***

**_I Did Not Accept That: Demonstrating Consent in Online Collection of Personal Data_**  
Jesus, Vitor; Mustare, Shweta  
https://link.springer.com/chapter/10.1007/978-3-030-27813-7_5  

##### Privacy in online collection of personal data is currently a much debated topic considering, amongst other reasons, the incidents with well known digital organisations, such as social networks and, in Europe, the recent EU/GDPR regulation. Among other required practices, explicit and simply worded consent from individuals must be obtained before collecting and using personal information. Further, individuals must also be given detailed information about what, how and what for data is collected. Consent is typically obtained at the collection point and, at a single point in time (ignoring updates), associated with Privacy Policies or End-User Agreements. At any moment, both the user and the organization should be able to produce evidence of this consent. This proof should not be disputable which leads us to strong cryptographic properties.The problem we discuss is how to robustly demonstrate such consent was given. We adapt fair-exchange protocols to this particular problem and, upon an exchange of personal data, we are able to produce a cryptographic receipt of acceptance that any party can use to prove consent and elicit non-repudiation. We discuss two broad strategies: a pure peer-to-peer scheme and the use of a Trusted Third Party.

***

**_The Interrelation of Game Elements and Privacy Requirements for the Design of a System: A Metamodel_**  
Mavroeidi, Aikaterini-Georgia; Kitsiou, Angeliki; Kalloniatis, Christos  
https://link.springer.com/chapter/10.1007/978-3-030-27813-7_13  

##### Due to the increased use of Information and Communication Technologies (ICTs), several methods have been developed in order to create more attractive interaction environments, so that users’ interest on using services to be maintained. Gamification consists a method, aiming to increase users’ engagement by implementing game design elements in services that are not games [1]. While using all these services, users’ information is recorded and monitored. Except the importance of increasing the use of ICTs, it is crucial to ensure that users’ personal information will be protected. To achieve it, privacy issues should be considered by software developers during the design phase of a service, in parallel with the game design elements. Based on our previous research [2], it was identified that the relation between gamification and privacy has not been examined sufficiently. As a result, a detailed analysis was conducted. In this work, in order to examine this relation in existent services, a detailed description of gamified services in several sectors has been conducted. Afterwards, based on the results of the conducted research and the examination of existent gamified services, a metamodel is presented, which describes how each game element conflicts with privacy requirements. By using this metamodel, software developers will be able to identify which mechanisms should be implemented in such services, so that users’ privacy to be protected in parallel. The development of such services ensures the trust between users and them and consequently, users’ engagements will be increased [3].

***

**_The Interrelation of Game Elements and Privacy Requirements for the Design of a System: A Metamodel_**  
Mavroeidi, Aikaterini-Georgia; Kitsiou, Angeliki; Kalloniatis, Christos  
https://link.springer.com/chapter/10.1007/978-3-030-27813-7_14  

##### Due to the increased use of Information and Communication Technologies (ICTs), several methods have been developed in order to create more attractive interaction environments, so that users’ interest on using services to be maintained. Gamification consists a method, aiming to increase users’ engagement by implementing game design elements in services that are not games [1]. While using all these services, users’ information is recorded and monitored. Except the importance of increasing the use of ICTs, it is crucial to ensure that users’ personal information will be protected. To achieve it, privacy issues should be considered by software developers during the design phase of a service, in parallel with the game design elements. Based on our previous research [2], it was identified that the relation between gamification and privacy has not been examined sufficiently. As a result, a detailed analysis was conducted. In this work, in order to examine this relation in existent services, a detailed description of gamified services in several sectors has been conducted. Afterwards, based on the results of the conducted research and the examination of existent gamified services, a metamodel is presented, which describes how each game element conflicts with privacy requirements. By using this metamodel, software developers will be able to identify which mechanisms should be implemented in such services, so that users’ privacy to be protected in parallel. The development of such services ensures the trust between users and them and consequently, users’ engagements will be increased [3].

***

**_Decentralised and Collaborative Auditing of Workflows_**  
Nehme, Antonio; Jesus, Vitor; Mahbub, Khaled; Abdallah, Ali  
https://link.springer.com/chapter/10.1007/978-3-030-27813-7_15  

##### Workflows involve actions and decision making at the level of each participant. Trusted generation, collection and storage of evidence is fundamental for these systems to assert accountability in case of disputes. Ensuring the security of audit systems requires reliable protection of evidence in order to cope with its confidentiality, its integrity at generation and storage phases, as well as its availability. Collusion with an audit authority is a threat that can affect all these security aspects, and there is room for improvement in existent approaches that target this problem.This work presents an approach for workflow auditing which targets security challenges of collusion-related threats, covers different trust and confidentiality requirements, and offers flexible levels of scrutiny for reported events. It relies on participants verifying each other’s reported audit data, and introduces a secure mechanism to share encrypted audit trails with participants while protecting their confidentiality. We discuss the adequacy of our audit approach to produce reliable evidence despite possible collusion to destroy, tamper with, or hide evidence.

***

**_Decentralised and Collaborative Auditing of Workflows_**  
Nehme, Antonio; Jesus, Vitor; Mahbub, Khaled; Abdallah, Ali  
https://link.springer.com/chapter/10.1007/978-3-030-27813-7_16  

##### Workflows involve actions and decision making at the level of each participant. Trusted generation, collection and storage of evidence is fundamental for these systems to assert accountability in case of disputes. Ensuring the security of audit systems requires reliable protection of evidence in order to cope with its confidentiality, its integrity at generation and storage phases, as well as its availability. Collusion with an audit authority is a threat that can affect all these security aspects, and there is room for improvement in existent approaches that target this problem.This work presents an approach for workflow auditing which targets security challenges of collusion-related threats, covers different trust and confidentiality requirements, and offers flexible levels of scrutiny for reported events. It relies on participants verifying each other’s reported audit data, and introduces a secure mechanism to share encrypted audit trails with participants while protecting their confidentiality. We discuss the adequacy of our audit approach to produce reliable evidence despite possible collusion to destroy, tamper with, or hide evidence.

***

## [TrustBus2018](TrustBus2018.md) 15th International Conference on Trust and Privacy in Digital Business
Link: [[Proceedings](https://link.springer.com/book/10.1007/978-3-319-98385-1)]
[[Conference](http://www.dexa.org/previous/dexa2018/trustbus2018.html)]
Awardなし  
***
**_Can Spatial Transformation-Based Privacy Preservation Compromise Location Privacy?_**  
Paturi, Anand; Mazumdar, Subhasish  
https://link.springer.com/chapter/10.1007/978-3-319-98385-1_6  

##### While mobile users would like to pose location-based queries such as “find me the nearest service of type S” or “find me k nearest services of type S,” they are increasingly aware of the underlying privacy concerns and threats. One of the two main approaches suggested by researchers for countering this threat involves spatial transformation via Hilbert curves. This scheme transforms a two-dimensional coordinate space into a one-dimensional space such that adjacency in the latter space implies contiguity in the former. A Trusted Server (TS) provides a Location-Based Server (LBS) with Points of Interest (POIs) indexed by the one-dimension Hilbert indices obtained by transforming their two-dimensional coordinates; mobile users query the LBS using the Hilbert index corresponding to their two-dimensional coordinates; the LBS finds the nearest Hilbert indices with appropriate POIs and returns them to the users. Owing to the large number of possible Hilbert transformations using different parameters, the attempt by an LBS to invert the transformation, i.e., compute a two-dimensional coordinate of the target user (or the POIs) is generally considered infeasible. In this paper, we ask to what extent and by which methods can a rogue LBS squeeze a privacy compromise from this scheme? We model the adversary and examine the possibilities of an attack based on semantic factors such as the distribution of POI categories and variations in POI density as well as collusion and exploitation of weaknesses in the mobile system software architecture. Finally, we point out limitations of such attacks and suggest strategies to strengthen defences against them.

***

**_Trustworthiness Cases – Toward Preparation for the Trustworthiness Certification_**  
Gol Mohammadi, Nazila; Ulfat-Bunyadi, Nelufar; Heisel, Maritta  
https://link.springer.com/chapter/10.1007/978-3-319-98385-1_17  

##### The trustworthiness of cyber-physical systems that support complex collaborative business processes is an emergent property. In order to address users’ trust concerns, trustworthiness requirements of systems must be assured. In this paper, we discuss the challenges of evidence-based trustworthiness assurance in order to tackle the problem of neglecting trustworthiness requirements while developing systems. To achieve this, we propose an approach that considers trustworthiness requirements using so-called trustworthiness cases. Our trustworthiness cases will guide the system development process toward evidence-based assurance of trustworthiness. Trustworthiness cases are based on assurance cases that have been successfully applied in safety- and security-related systems. We use an application example from the health care domain to demonstrate our approach.

***

## [HOST2019](HOST2019.md) 2019 IEEE International Symposium on Hardware Oriented Security and Trust
Link: [[Proceedings](https://ieeexplore.ieee.org/xpl/conhome/8736108/proceeding)]
[[Conference](http://www.hostsymposium.org/host2019/index2019.php)]
[[Awards](http://www.hostsymposium.org/host_2019awards.php)]  
***
**_QIF-Verilog: Quantitative Information-Flow based Hardware Description Languages for Pre-Silicon Security Assessment_**  
Guo, Xiaolong; Dutta, Raj Gautam; He, Jiaji; Tehranipoor, Mark M.; Jin, Yier  
https://doi.org/10.1109/HST.2019.8740840  

##### Hardware vulnerabilities are often due to design mistakes because the designer does not sufficiently consider potential security vulnerabilities at the design stage. As a result, various security solutions have been developed to protect ICs, among which the language-based hardware security verification serves as a promising solution. The verification process will be performed while compiling the HDL of the design. However, similar to other formal verification methods, the language-based approach also suffers from scalability issue. Furthermore, existing solutions either lead to hardware overhead or are not designed for vulnerable or malicious logic detection. To alleviate these challenges, we propose a new language based framework, QIF-Verilog, to evaluate the trustworthiness of a hardware system at register transfer level (RTL). This framework introduces a quantified information flow (QIF) model and extends Verilog type systems to provide more expressiveness in presenting security rules; QIF is capable of checking the security rules given by the hardware designer. Secrets are labeled by the new type and then parsed to data flow, to which a QIF model will be applied. To demonstrate our approach, we design a compiler for QIF-Verilog and perform vulnerability analysis on benchmarks from Trust-Hub and OpenCore. We show that Trojans or design faults that leak information from circuit outputs can be detected automatically, and that our method evaluates the security of the design correctly.

***

## [HOST2018](HOST2018.md) 2018 IEEE International Symposium on Hardware Oriented Security and Trust
Link: [[Proceedings](https://ieeexplore.ieee.org/xpl/conhome/8369415/proceeding)]
[[Conference](http://www.hostsymposium.org/host2018/index2018.php)]
[[Awards](http://www.hostsymposium.org/host_2018awards.php)]  
***
**_B-TREPID: Batteryless tamper-resistant envelope with a PUF and integrity detection_**  
Immler, Vincent; Obermaier, Johannes; König, Martin; Hiller, Matthias; Sig, Georg  
https://doi.org/10.1109/HST.2018.8383890  

##### Protecting embedded devices against physical attacks is a challenging task since the attacker has control of the device in a hostile environment. To address this issue, current countermeasures typically use a battery-backed tamper-respondent envelope that encloses the entire device to create a trusted compartment. However, the battery affects the system's robustness and weight, and also leads to difficulties with the security mechanism while shipping the device. In contrast, we present a batteryless tamper-resistant envelope, which contains a fine mesh of electrodes, and its complementary security concept. An evaluation unit checks the integrity of the sensor mesh by detecting short and open circuits. Additionally, it measures the capacitances of the mesh. Once its preliminary integrity is confirmed, a cryptographic key is derived from the capacitive measurements that represent a PUF, to decrypt and authenticate the firmware of the enclosed host system. We demonstrate the feasibility of our concept, provide details on the layout and electrical properties of the batteryless envelope, and explain the underlying security architecture. Practical results from a set of manufactured envelopes facilitate future research.

***

## [PST2018](PST2018.md) 16th Annual Conference on Privacy, Security and Trust
Link: [[Proceedings](https://ieeexplore.ieee.org/xpl/conhome/8498146/proceeding)]
[[Conference](https://pstnet.ca/)]
Awardなし  
***
**_Crossing Cross-Domain Paths in the Current Web_**  
Ruohonen, Jukka; Salovaara, Joonas; Leppänen, Ville  
https://doi.org/10.1109/PST.2018.8514163  

##### The loading of resources from third-parties has evoked new security and privacy concerns about the current world wide web. Building on the concepts of forced and implicit trust, this paper examines cross-domain transmission control protocol (TCP) connections that are initiated to domains other than the domain queried with a web browser. The dataset covers nearly ten thousand domains and over three hundred thousand TCP connections initiated by querying popular Finnish websites and globally popular sites. According to the results, (i) cross-domain connections are extremely common in the current Web. (ii) Most of these transmit encrypted content, although mixed content delivery is relatively common; many of the cross-domain connections deliver unencrypted content at the same time. (iii) Many of the cross-domain connections are initiated to known web advertisement domains, but a much larger share traces to social media platforms and cloud infrastructures. Finally, (iv) the results differ slightly between the Finnish web sites sampled and the globally popular sites. With these results, the paper contributes to the ongoing work for better understanding cross-domain connections and dependencies in the world wide web.

***

**_Mutual Authentication in Electronic Voting Schemes_**  
Augoye, Voke; Tomlinson, Allan  
https://doi.org/10.1109/PST.2018.8514212  

##### Voter eligibility is an important requirement of electronic voting which prevents double voting and voter impersonation. Many e-voting schemes assume a trustworthy environment for vote casting and tallying hence trust pollworkers to correctly authenticate voters. In this paper we propose a mutual entity authentication protocol using biometrics to ensure voter eligibility and digital signatures for ballot authentication in an untrustworthy environment.

***

**_Problem-based Derivation of Trustworthiness Requirements from Users’ Trust Concerns_**  
Mohammadi, Nazila Gol; Ulfat-Bunyadi, Nelufar; Heisel, Maritta  
https://doi.org/10.1109/PST.2018.8514183  

##### The trustworthiness of cyber-physical systems (CPS) that support complex collaborative business processes is an emergent property. New technologies like cloud computing bring new capabilities for hosting and offering complex collaborative business operations. However, these advances might introduce new vulnerabilities and threats caused by collaboration and data exchange over the Internet. Hence, users become more concerned about trust. In order to address users' trust concerns, trustworthiness requirements for the CPS must be elicited and satisfied. They describe the properties (qualities) the CPS must possess in order to be trustworthy. In this paper, we suggest a problem-based requirements engineering method that supports specifically the derivation of trustworthiness requirements. Based on identified trust concerns of users, trust assumptions are made explicit in problem diagrams. They express the conditions under which users are willing to trust. The problem diagrams and trust assumptions are then refined until they are concrete enough to derive trustworthiness requirements from them. During the refinement process, trust assumptions may influence and modify the system design (and vice versa, i.e., due to a certain system design, new trust concerns may arise that need to be addressed). In this way, users' trust concerns are considered right from the beginning and trustworthiness is designed into the CPS. An application example from the healthcare domain is used to demonstrate our approach.

***

**_Digitized Trust in Human-in-the-Loop Health Research_**  
Sutton, Andrew; Samavi, Reza; Doyle, Thomas E.; Koff, David  
https://doi.org/10.1109/PST.2018.8514168  

##### In this paper, we propose an architecture that utilizes blockchain technology for enabling verifiable trust in collaborative health research environments. The architecture supports the human-in-the-loop paradigm for health research by establishing trust between participants, including human researchers and AI systems, by making all data transformations transparent and verifiable by all participants. We define the trustworthiness of the system and provide an analysis of the architecture in terms of trust requirements. We then evaluate our architecture by analyzing its resiliency to common security threats and through an experimental realization.

***

**_Trust-driven, Decentralized Data Access Control for Open Network of Autonomous Data Providers_**  
Opioła, Łukasz; Dutka, Łukasz; Słota, Renata G.; Kitowski, Jacek  
https://doi.org/10.1109/PST.2018.8514209  

##### The observation of current trends in data access, especially in the field of scientific computations, shows that global data access that crosses federation boundaries is highly desirable. However, administrative constraints require that data centers remain autonomous, which effectively eliminates the possibility of cooperation. To overcome this, we plan to establish an open network of cooperating data providers. In this paper, we address the issue of data access control for such network. Our proposition is to use a synergy of hybrid peer-to-peer architecture, decentralized identity and access management, metadata synchronization protocol and trust driven authorization flow. The proposed solution is discussed using real-life use-cases concerning cross-federation data access.

***

**_On Sybil Classification in Online Social Networks Using Only Structural Features_**  
Mulamba, Dieudonne; Ray, Indrajit; Ray, Indrakshi  
https://doi.org/10.1109/PST.2018.8514162  

##### Sybil attack is a problem that seriously affects Online Social Networks (OSNs). These attacks are made possible by the openness of OSN platforms that allows an attacker to create multiple fake accounts, called Sybils, which are then used to compromise the underlining trust pinnings of the OSN. Early Sybil account detection mechanisms involved classification of users into benign and malicious based on various attributes collected from the user profiles. One challenge affecting these classification methods is that user attributes can often be in-complete or inaccurate. In addition, these classification methods can be evaded by sophisticated attackers. More importantly, user profiles can often reveal sensitive user information that can potentially be misused causing privacy violation. In this work, we propose a Sybil detection method that is based on the classification of users into malicious and benign based on the inherent topology or structure of the underlining OSN graph. We propose a new set of structural features for a graph. Using this new feature set, we perform several experiments on both synthetic as well as real-world OSN data. Our results show that the proposed detection method is very effective in correctly classifying Sybil accounts without running the risk of being evaded by a sophisticated attacker and without compromising privacy of users.

***

**_Enforcing Privacy and Security in Public Cloud Storage_**  
Resende, João S.; Martins, Rolando; Antunes, Luís  
https://doi.org/10.1109/PST.2018.8514195  

##### Cloud storage allows users to remotely store their data, giving access anywhere and to anyone with an Internet connection. The accessibility, lack of local data maintenance and absence of local storage hardware are the main advantages of this type of storage. The adoption of this type of storage is being driven by its accessibility. However, one of the main barriers to its widespread adoption is the sovereignty issues originated by lack of trust in storing private and sensitive information in such a medium. Recent attacks to cloud-based storage show that current solutions do not provide adequate levels of security and subsequently fail to protect users' privacy. Usually, users rely solely on the security supplied by the storage providers, which in the presence of a security breach will ultimate lead to data leakage. In this paper, we propose and implement a broker (ARGUS) that acts as a proxy to the existing public cloud infrastructures by performing all the necessary authentication, cryptography and erasure coding. ARGUS uses erasure code as a way to provide efficient redundancy (opposite to standard replication) while adding an extra layer to data protection in which data is broken into fragments, expanded and encoded with redundant data pieces that are stored across a set of different storage providers (public or private). The key characteristics of ARGUS are confidentiality, integrity and availability of data stored in public cloud systems.

***

**_Privacy Preserving Probabilistic Record Linkage Without Trusted Third Party_**  
Lazrig, Ibrahim; Ong, Toan C.; Ray, Indrajit; Ray, Indrakshi; Jiang, Xiaoqian; Vaidya, Jaideep  
https://doi.org/10.1109/PST.2018.8514192  

##### For the purpose of research, organizations often need to share and link data belonging to a single individual while protecting her privacy. This problem, referred to as privacy preserving record linkage (PPRL), has been investigated by researchers. Most PPRL works focus on deterministic linkages where the identifying attributes of two records must be equal in order to declare them to belong to the same individual. Moreover, most of these methods require the active participation of a trusted third party (TTP). If this TTP is compromised, it makes the data from all participating parties vulnerable to information leakage. The proposed work improves upon the existing methods in two ways. First, we propose a protocol which does not require two records to have an exact match on identifying attributes in order to be declared as belonging to the same individual. Second, we investigate probabilistic PPRL in the two-party setting without resorting to any TTP. We use Bloom filters for probabilistic matching and Yao's garbled circuit to perform the computation needed for the matching on encrypted data. To alleviate the computation and communication overhead of Yao's protocol, we leverage data blocking methods and optimize the computation. We provide a security proof of our method and experimentally evaluate the performance gained on large benchmark datasets.

***

## [TrustCom2019](TrustCom2019.md) 18th IEEE International Conference On Trust, Security And Privacy In Computing And Communications
Link: [[Proceedings](https://ieeexplore.ieee.org/xpl/conhome/8883860/proceeding)]
[[Conference](https://crow.org.nz/Trustcom2019)]
[[Awards](https://forumpoint2.eventsair.com/QuickEventWebsitePortal/trustcom19/tc19/ExtraContent/ContentPage?page=9)]  
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

**_Security and Performance Assessment of IP Multiplexing Moving Target Defence in Software Defined Networks_**  
Dishington, Cole; Sharma, Dilli P.; Kim, Dong Seong; Cho, Jin-Hee; Moore, Terrence J.; Nelson, Frederica F.  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00046  

##### With the interconnection of services and customers, network attacks are capable of large amounts of damage. Flexible Random Virtual IP Multiplexing (FRVM) is a Moving Target Defence (MTD) technique that protects against reconnaissance and access with address mutation and multiplexing. Security techniques must be trusted, however, FRVM, along with past MTD techniques, have gaps in realistic evaluation and thorough analysis of security and performance. FRVM, and two comparison techniques, were deployed on a virtualised network to demonstrate FRVM's security and performance trade-offs. The key results include the security and performance trade-offs of address multiplexing and address mutation. The security benefit of IP address multiplexing is much greater than its performance overhead, deployed on top of address mutation. Frequent address mutation significantly increases an attackers' network scan durations as well as effectively obfuscating and hiding network configurations.

***

**_HSDC–Net: Secure Anonymous Messaging in Online Social Networks_**  
Nosouhi, Mohammad Reza; Yu, Shui; Sood, Keshav; Grobler, Marthie  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00054  

##### Hiding contents of users' messages has been successfully addressed before, while anonymization of message senders remains a challenge since users do not usually trust ISPs and messaging application providers. To resolve this challenge, several solutions have been proposed so far. Among them, the Dining Cryptographers network protocol (DC-net) provides the strongest anonymity guarantees. However, DC-net suffers from two critical issues that makes it impractical, i.e., (1) collision possibility and (2) vulnerability against disruptions. Apart from that, we noticed a third critical issue during our investigation. (3) DC-net users can be deanonymized after they publish at least three messages. We name this problem the short stability issue and prove that anonymity is provided only for a few cycles of message publishing. As far as we know, this problem has not been identified in the previous research works. In this paper, we propose Harmonized and Stable DC-net (HSDC-net), a self-organizing protocol for anonymous communications. In our protocol design, we first resolve the short stability issue and obtain SDC-net, a stable extension of DC-net. Then, we integrate the Slot Reservation and Disruption Management sub-protocols into SDC-net to overcome the collision and security issues, respectively. The obtained HSDC-net protocol can also be integrated into blockchain-based cryptocurrencies (e.g. Bitcoin) to mix multiple transactions (belonging to different users) into a single transaction in such a way that the source of each payment is unknown. This preserves privacy of blockchain users. Our prototype implementation shows that HSDC-net achieves low latencies that makes it a practical protocol.

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

**_A Probability Prediction Based Mutable Control-Flow Attestation Scheme on Embedded Platforms_**  
Hu, Jianxing; Huo, Dongdong; Wang, Meilin; Wang, Yazhe; Zhang, Yan; Li, Yu  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00077  

##### Control-flow attacks cause powerful threats to the software integrity. Remote attestation for control flow is a crucial security service for ensuring the software integrity on embedded platforms. The fine-grained remote control-flow attestation with execution-profiling Control-Flow Graph (CFG) is applied to defend against control-flow attacks. It is a safe scheme but it may influence the runtime efficiency. In fact, we find out only the vulnerable parts of a program need being attested at costly fine-grained level to ensure the security, and the remaining normal parts just need a lightweight coarse-grained check to reduce the overhead. We propose Mutable Granularity Control-Flow Attestation (MGC-FA) scheme, which bases on a probabilistic model, to distinguish between the vulnerable and normal parts in the program and combine fine-grained and coarse-grained control-flow attestation schemes. MGC-FA employs the execution-profiling CFG to apply the remote control-flow attestation scheme on embedded devices. MGC-FA is implemented on Raspberry Pi with ARM TrustZone and the experimental results show its effect on balancing the relationship between runtime efficiency and control-flow security.

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

**_A Secure Private Charging Pile Sharing Scheme with Electric Vehicles in Energy Blockchain_**  
Wang, Yuntao; Su, Zhou; Zhang, Kuan  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00092  

##### With the rapid advance of electric vehicles (EVs) and the sparse public charging infrastructure, the private charging pile sharing networks (PCPSNs) hold the potential to improve the quality of experience (QoE) of using EVs by leveraging private charging piles (PCPs) as shared charging points to charge a group of distributed EVs. However, due to the potential security and privacy issues for EVs and PCPs caused by untrusted participants in decentralized energy market, it becomes a crucial challenge to optimally schedule the charging and sharing strategies of EVs and PCPs in PCPSNs. In this paper, we propose a secure and permissioned blockchain-based PCP sharing scheme for EVs in PCPSNs. Firstly, we present an energy blockchain-based PCPSN framework to enhance the security of distributed energy trading. Secondly, we develop a reputation-based secure PCP sharing protocol to efficiently reach consensus in the blockchain with the implement of BLS multi-signature. Thirdly, we investigate a distributed reputation model to evaluate the trustworthiness of participants and identify malicious users. In addition, based on the many-to-one matching game, the optimal strategies of EVs and PCPs are analyzed by searching the stable matching pairs. Finally, simulation results show that the proposed scheme can not only improve the QoE of users, but also protect the network from adversaries.

***

**_Measuring Trustworthiness of IoT Image Sensor Data Using Other Sensors’ Complementary Multimodal Data_**  
Islam, Mohammad Manzurul; Karmakar, Gour; Kamruzzaman, Joarder; Murshed, Manzur  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00112  

##### Trust of image sensor data is becoming increasingly important as the Internet of Things (IoT) applications grow from home appliances to surveillance. Up to our knowledge, there exists only one work in literature that estimates trustworthiness of digital images applied to forensic applications, based on a machine learning technique. The efficacy of this technique is heavily dependent on availability of an appropriate training set and adequate variation of IoT sensor data with noise, interference and environmental condition, but availability of such data cannot be assured always. Therefore, to overcome this limitation, a robust method capable of estimating trustworthy measure with high accuracy is needed. Lowering cost of sensors allow many IoT applications to use multiple types of sensors to observe the same event. In such cases, complementary multimodal data of one sensor can be exploited to measure trust level of another sensor data. In this paper, for the first time, we introduce a completely new approach to estimate the trustworthiness of an image sensor data using another sensor's numerical data. We develop a theoretical model using the Dempster-Shafer theory (DST) framework. The efficacy of the proposed model in estimating trust level of an image sensor data is analyzed by observing a fire event using IoT image and temperature sensor data in a residential setup under different scenarios. The proposed model produces highly accurate trust level in all scenarios with authentic and forged image data.

***

**_Differentially Private Streaming to Untrusted Edge Servers in Intelligent Transportation System_**  
Ghane Ezabadi, Soheila; Jolfaei, Alireza; Kulik, Lars; Kotagiri, Ramamohanarao  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00113  

##### This paper considers the privacy issues in the intelligent transportation system, in which the data is largely communicated based upon vehicle-to-infrastructure and vehicle-to-vehicle protocols. The sensory data communicated by the vehicles contain sensitive information, such as location and speed, which could violate the driver's privacy if they are leaked with no perturbation. Recent studies suggested mechanisms for randomizing the stream of vehicular data to ensure individuals' privacy. Although the past works on differential privacy provide a strong privacy guarantee, they are limited to applications where communication parties are trusted and/or data is limited to a few types. In this paper, we address this gap by proposing a differentially private mechanism that adds noise in the user side rather than the server. Also, our mechanism is able to perturb various types of data as pointed out by the dedicated short-range communication protocols in the automotive industry. The proposed mechanism is data adaptive and scales the noise with respect to the data type and distribution. Our extensive experiments show the accuracy of our mechanism compared to the recent approaches.

***

**_Trusted Autonomous Vehicle: Measuring Trust using On-Board Unit Data_**  
Chowdhury, Abdullahi; Karmakar, Gour; Kamruzzaman, Joarder  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00114  

##### Vehicular Ad-hoc Networks (VANETs) play an essential role in ensuring safe, reliable and faster transportation with the help of an Intelligent Transportation system. The trustworthiness of vehicles in VANETs is extremely important to ensure the authenticity of messages and traffic information transmitted in extremely dynamic topographical conditions where vehicles move at high speed. False or misleading information may cause substantial traffic congestions, road accidents and may even cost lives. Many approaches exist in literature to measure the trustworthiness of GPS data and messages of an Autonomous Vehicle (AV). To the best of our knowledge, they have not considered the trustworthiness of other On-Board Unit (OBU) components of an AV, along with GPS data and transmitted messages, though they have a substantial relevance in overall vehicle trust measurement. In this paper, we introduce a novel model to measure the overall trustworthiness of an AV considering four different OBU components additionally. The performance of the proposed method is evaluated with a traffic simulation model developed by Simulation of Urban Mobility (SUMO) using realistic traffic data and considering different levels of uncertainty.

***

**_Secure Data Streaming to Untrusted Road Side Units in Intelligent Transportation System_**  
Jolfaei, Alireza; Kant, Krishna; Shafei, Hassan  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00115  

##### The paper considers data security issues in vehicle-to-infrastructure communications, where vehicles stream data to a road side unit. We assume aggregated data in road side units can be stored or used for data analytics. In this environment, there are issues in regards to the scalability of key management and computation limitations at the edge of the network. To address these issues, we suggest the formation of groups in the vehicle layer, where a group leader is assigned to communicate with group devices and the road side unit. We propose a lightweight permutation mechanism for preserving the confidentiality of sensory data.

***

**_Big Data Security Frameworks Meet the Intelligent Transportation Systems Trust Challenges_**  
Awaysheh, Feras; Cabaleiro, José Carlos; Pena, Tomás Fernández; Alazab, Mamoun  
https://doi.org/10.1109/TrustCom/BigDataSE.2019.00117  

##### Many technological cases exploiting data science have been realized in recent years; machine learning, Internet of Things, and stream data processing are examples of this trend. Other advanced applications have focused on capturing the value from streaming data of different objects of transport and traffic management in an Intelligent Transportation System (ITS). In this context, security control and trust level play a decisive role in the sustainable adoption of this trend. However, conceptual work integrating the security approaches of different disciplines into one coherent reference architecture is limited. The contribution of this paper is a reference architecture for ITS security (called SITS). In addition, a classification of Big Data technologies, products, and services to address the ITS trust challenges is presented. We also proposed a novel multi-tier ITS security framework for validating the usability of SITS with business intelligence development in the enterprise domain.

***

## [TrustCom2018](TrustCom2018.md) 17th IEEE International Conference On Trust, Security And Privacy In Computing And Communications
Link: [[Proceedings](https://ieeexplore.ieee.org/xpl/conhome/8454845/proceeding)]
[[Conference](http://www.cloud-conf.net/trustcom18/)]
Awardなし  
***
**_Engineering Trust: A Graph-Based Algorithm for Modeling, Validating, and Evaluating Trust_**  
Tucker, S.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00011  

##### Trust is an important topic in today's interconnected world. Breaches of trust in today's systems has had profound effects upon us all, and they are very difficult and costly to fix especially when caused by flaws in the system's architecture. Trust modeling can expose these types of issues, but modeling trust in complex multi-tiered system architectures can be very difficult. Often experts have differing views of trust and how it applies to systems within their domain. This work presents a graph-based modeling methodology that normalizes the application of trust across disparate system domains allowing the modeling of complex intersystem trust relationships. An algorithm is proposed that applies graph theory to model, validate and evaluate trust in system architectures. Also, it provides the means to apply metrics to compare and prioritize the effectiveness of trust management in system and component architectures. The results produced by the algorithm can be used in conjunction with systems engineering processes to ensure both trust and the efficient use of resources.

***

**_A Novel Dynamic Cloud Service Trust Evaluation Model in Cloud Computing_**  
Wang, Y.; Wen, J.; Zhou, W.; Luo, F.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00012  

##### There are many different types of cloud services. How to choose the best cloud service for a specific application is a challenging issue. Using cloud services, users' private data could be exposed to a third party, which might not be trusted. In this paper, a dynamic cloud service trust evaluation model is proposed based on service-level agreement (SLA) and privacy-awareness. First, to make the final trust evaluation value more practical, the proposed model performs a comprehensive trust evaluation, which consists of direct, indirect, and reputation trust. Second, cloud services are divided into five levels based on their service capabilities. By analyzing SLA to determine the quality of service, the user can choose a suitable SLA. In order to protect data security of the cloud service user, we propose a data protection method based on a normal cloud model. Finally, we propose a dynamic trust update mechanism to update the direct trust. Experimental results based on a public dataset show that the proposed model effectively identifies the user community based on service preferences, improves the service requester's satisfaction, avoids malicious interference, and is accurate and feasible.

***

**_One Secure Access Scheme Based on Trusted Execution Environment_**  
Fan, Y.; Liu, S.; Tan, G.; Lin, X.; Zhao, G.; Bai, J.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00013  

##### The wide adoption of mobile devices poses an imminent threat to preserving privacy. In order to prevent the leakage of sensitive information (such as the contact list, or private pictures) raised by inappropriate access, we propose a secure access scheme based on Trusted Execution Environment (TEE) specifically designed for mobile devices. The proposed scheme has two purposes: secure access and minimizing losses. For secure access, we use TEE to run access authorization and verification; for minimizing losses, we use the strategy of file slice to divide the sensitive file into multiple parts and then encrypt the file parts respectively in case of large-scale leakage. Practically, our scheme's ""minimizing losses"" can be easily expanded to cloud computing by mapping one file part in our scheme to a whole file in cloud computing scenario. The theoretical analysis and experimental evaluation indicate that our scheme meets the requirement in respects of efficiency and security.

***

**_Understanding Trust, Privacy and Financial Fears in Online Payment_**  
Haddad, G. El; Aïmeur, E.; Hage, H.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00015  

##### In online payment, customers must transmit their personal and financial information through the website to conclude their purchase and pay the services or items selected. They may face possible fears from online transactions raised by their risk perception about financial or privacy loss. They may have concerns over the payment decision with the possible negative behaviors such as shopping cart abandonment. Therefore, customers have three major players that need to be addressed in online payment: the online seller, the payment page, and their own perception. However, few studies have explored these three players in an online purchasing environment. In this paper, we focus on the customer concerns and examine the antecedents of trust, payment security perception as well as their joint effect on two fundamentally important customers' aspects privacy concerns and financial fear perception. A total of 392 individuals participated in an online survey. The results highlight the importance, of the seller website's components (such as ease of use, security signs, and quality information) and their impact on the perceived payment security as well as their impact on customer's trust and financial fear perception. The objective of our study is to design a research model that explains the factors contributing to an online payment decision.

***

**_DecentID: Decentralized and Privacy-Preserving Identity Storage System Using Smart Contracts_**  
Friebe, S.; Sobik, I.; Zitterbart, M.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00016  

##### Many Internet services require the registration of an account before permitting use of their services. Over time, many Internet users end up with a multitude of accounts with separated identities. A solution to this problem is offered by single-sign-on (SSO) providers, where a user can create a single identity and use this identity for multiple services. However it requires the user to trust the SSO provider. When the provider blocks access to the identities the users lose access to their subscribed services. To avoid this problem, we propose DecentID, a completely decentralized identity storage system that does not require a centralized trusted third party. Instead, a public blockchain is used as trust anchor. Identities can be created and used for different services. Each service can only read the identity attributes disclosed for it without being able to read attributes the user wants to keep secret.

***

**_Reputation Prediction Using Influence Conversion_**  
Rakoczy, M. E.; Bouzeghoub, A.; Gancarski, A. Lopes; Wegrzyn-Wolska, K.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00017  

##### Currently, due to constantly increasing popularity of social media sites and thus increasing amounts of data available to study, the field of social computing has gained momentum. The research about human interactions in social networks have proven to have multiple usages in e-commerce, recommendation and others. Amongst studied topics, notions of trustworthiness and influence drawn much attention in recent years. However, these notions were studied separately and independently, with little focus on the fact that, in real life, they tend to exist simultaneously. In this paper, we focus on this novel problem and present an investigation of both influence and reputation. In particular, we propose a transition method, that uses existing influence information from social network in order to predict the collective trustworthiness of the node, or reputation. Through preliminary experiments on a real-world dataset, we demonstrate the suitability of our method.

***

**_Secure, Resilient, and Self-Configuring Fog Architecture for Untrustworthy IoT Environments_**  
Kahla, M.; Azab, M.; Mansour, A.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00018  

##### The extensive increase in the number of IoT devices and the massive data generated and sent to the cloud hinder the cloud abilities to handle it. Further, some IoT devices are latency-sensitive. Such sensitivity makes it harder for far clouds to handle the IoT needs in a timely manner. A new technology named ""Fog computing"" has emerged as a solution to such problems. Fog computing relies on close by computational devices to handle the conventional cloud load. However, Fog computing introduced additional problems related to the trustworthiness and safety of such devices. Unfortunately, the suggested architectures did not consider such problem. In this paper we present a novel self-configuring fog architecture to support IoT networks with security and trust in mind. We realize the concept of Moving-target defense by mobilizing the applications inside the fog using live migrations. Performance evaluations using a benchmark for mobilized applications showed that the added overhead of live migrations is very small making it deployable in real scenarios. Finally, we presented a mathematical model to estimate the survival probabilities of both static and mobile applications within the fog. Moreover, this work can be extended to other systems such as mobile ad-hoc networks (MANETS) or in vehicular cloud computing (VCC).

***

**_Repoxy: Replication Proxy for Trustworthy SDN Controller Operation_**  
Azab, M.; Hamdy, A.; Mansour, A.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00019  

##### Software Defined Networks (SDN) is envisaged as a future model for large-scale, elastic, and adaptive networks. However, such flexibility comes with a major cost. Relying heavily on software across the entire architecture and the centralized nature of the most important component, the controller, gave the attackers asymmetric advantage. for decades, we used to build security tools to secure the network traffic, but network components security was always protected by physical perimeters behind doors. In this paper, we present REPlication prOXY(Repoxy), a smart gateway isolating the north and southbound to enhance controller resilience, availability, and reliability in presence of attacks and also discuss our first version of the implementation. Repoxy presents a novel SDN-controller intrusion detection system to detect any malicious manipulations to the controller software. Further, Repoxy enables elasticity and high-availability for SDN controllers by facilitating southbound-oblivious seamless multi-controller replication, and handover for same network traffic. Additionally, Repoxy helps forensic analysts to easily find attack traces by exploiting Repoxy's information-rich database logging all the switch controller interactions. Results and evaluations showed the enhanced trustworthiness in the SDN network with a reasonable overhead when Repoxy is used.

***

**_A Dynamic Trust Weight Allocation Technique for Data Reconstruction in Mobile Wireless Sensor Networks_**  
Aleman, C. Sanchez; Pissinou, N.; Alemany, S.; Kamhoua, G.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00020  

##### Data accuracy and low energy consumption in mobile wireless sensor networks (MWSN) are crucial attributes for real-time applications. Although there are many existing methods to reconstruct data for wireless sensor networks, there are few developed for highly mobile environments. We propose Dynamic Trust Weight Allocation Technique (DTWA), a novel in-network data reconstruction method that determines the trust level in the data accuracy of each candidate node by evaluating spatio-temporal correlations, trajectory behavior, quantity and quality of data, and the number of hops traveled by the received data from the source. DTWA is capable of evaluating second-hand data when there is no first-hand data available and selecting second-hand data when this last is more accurate than the first-hand data. Our results demonstrate that data reconstructed using DTWA depicts significantly lower Root Mean Square Error (RMSE) compared to the IMC method when tested for both low and high incomplete dataset scenarios.

***

**_TARAS: Trust-Aware Role-Based Access Control System in Public Internet-of-Things_**  
Gwak, B.; Cho, J.; Lee, D.; Son, H.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00022  

##### Due to the proliferation of Internet-of-Things (IoT) environments, humans working with heterogeneous, smart objects in public IoT environments become more popular than ever before. This situation often requires to establish trust relationships between a user and a smart object for their secure interactions, but without the presence of prior interactions. In this work, we are interested in how a smart object can grant an access right to a human user in the absence of any prior knowledge in which some users may be malicious aiming to breach security goals of the IoT system. To solve this problem, we propose a trust-aware, role-based access control system, namely TARAS, which provides adaptive authorization to users based on dynamic trust estimation. In TARAS, for the initial trust establishment, we take a multidisciplinary approach by adopting the concept of I-sharing from psychology. The I-sharing follows the rationale that people with similar roles and traits are more likely to respond in a similar way. This theory provides a powerful tool to quickly establish trust between a smart object and a new user with no prior interactions. In addition, TARAS can adaptively filter malicious users out by revoking their access rights based on adaptive, dynamic trust estimation. Our experimental results show that the proposed TARAS mechanism can maximize system integrity in terms of correctly detecting malicious or benign users while maximizing service availability to users particularly when the system is fine-tuned based on the identified optimal setting in terms of an optimal trust threshold.

***

**_BARS: A Blockchain-Based Anonymous Reputation System for Trust Management in VANETs_**  
Lu, Z.; Wang, Q.; Qu, G.; Liu, Z.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00025  

##### The public key infrastructure (PKI) based authentication protocol provides the basic security services for vehicular ad-hoc networks (VANETs). However, trust and privacy are still open issues due to the unique characteristics of vehicles. It is crucial for VANETs to prevent internal vehicles from broadcasting forged messages while simultaneously protecting the privacy of each vehicle against tracking attacks. In this paper, we propose a blockchain-based anonymous reputation system (BARS) to break the linkability between real identities and public keys to preserve privacy. The certificate and revocation transparency is implemented efficiently using two blockchains. We design a trust model to improve the trustworthiness of messages relying on the reputation of the sender based on both direct historical interactions and indirect opinions about the sender. Experiments are conducted to evaluate BARS in terms of security and performance and the results show that BARS is able to establish distributed trust management, while protecting the privacy of vehicles.

***

**_Turning Trust Around: Smart Contract-Assisted Public Key Infrastructure_**  
Ahmed, A. S.; Aura, T.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00026  

##### In past, several Certificate Authority (CA) compromise and subsequent mis-issue of certificate raise the importance of certificate transparency and dynamic trust management for certificates. Certificate Transparency (CT) provides transparency for issued certificates, thus enabling corrective measure for a mis-issued certificate by a CA. However, CT and existing mechanisms cannot convey the dynamic trust state for a certificate. To address this weakness, we propose Smart Contract-assisted PKI (SCP) - a smart contract based PKI extension - to manage dynamic trust network for PKI. SCP enables distributed trust in PKI, provides a protocol for managing dynamic trust, assures trust state of a certificate, and provides a better trust experience for end-users.

***

**_A Comprehensive Analysis of Packet Loss in MANETs_**  
Khan, M. S.; Waris, S.; Ahmed, I.; Khan, M. I.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00028  

##### Security schemes proposed for for Mobile Ad hoc Networks (MANETs) based on node's trust computation consider packet drop as a sign of misbehaving from malicious nodes. However, this may not be always true because of node mobility and limited processing capability feature of nodes in MANETs. As nodes are free to move in MANETs, packet loss may occur due to node mobility, non-availability of next hop nodes, and so on. Moreover, due to frequent data from multiple sources, a forwarding node queue may overflow that causes packet loss. Furthermore, packet loss may also occur due to congestion in the network. To better overcome the packet loss problem discussed previously, the packet loss possible reasons should be analyzed comprehensively in all aspect and then propose a counter strategy against each packet loss reason. In this paper, we analyze the reasons behind packet loss in MANETs comprehensively under different network scenarios. Moreover, we investigate the effect of different network parameters, such as mobility, data rate, and congestion on packet loss. One of the main contributions of this paper is to analyze the causes of packet drop comprehensively in MANETs. This work provides detailed insights in selecting the proper parameters to analyze the behavior of nodes in the network in different context. Moreover, this work also provides help in the design of trust-based security schemes to detect and isolate true malicious nodes in the network.

***

**_Trust4App: Automating Trustworthiness Assessment of Mobile Applications_**  
Habib, S. M.; Alexopoulos, N.; Islam, M. M.; Heider, J.; Marsh, S.; Müehlhäeuser, M.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00029  

##### Smartphones have become ubiquitous in our everyday lives, providing diverse functionalities via millions of applications (apps) that are readily available. To achieve these functionalities, apps need to access and utilize potentially sensitive data, stored in the user's device. This can pose a serious threat to users' security and privacy, when considering malicious or underskilled developers. While application marketplaces, like Google Play store and Apple App store, provide factors like ratings, user reviews, and number of downloads to distinguish benign from risky apps, studies have shown that these metrics are not adequately effective. The security and privacy health of an application should also be considered to generate a more reliable and transparent trustworthiness score. In order to automate the trustworthiness assessment of mobile applications, we introduce the Trust4App framework, which not only considers the publicly available factors mentioned above, but also takes into account the Security and Privacy (S&P) health of an application. Additionally, it considers the S&P posture of a user, and provides an holistic personalized trustworthiness score. While existing automatic trustworthiness frameworks only consider trustworthiness indicators (e.g. permission usage, privacy leaks) individually, Trust4App is, to the best of our knowledge, the first framework to combine these indicators. We also implement a proof-of-concept realization of our framework and demonstrate that Trust4App provides a more comprehensive, intuitive and actionable trustworthiness assessment compared to existing approaches.

***

**_Bionic Mechanism Based Dynamic Trust Evaluation Method in Cloud Environment_**  
Ma, S.; Shuai, X.; Zhou, Z.; Qiao, K.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00030  

##### In cloud environments, trust is one of the most important tools to enhance security. Trust can improve the reliability of cloud computing resources and has an important role in the business environments. In this paper, trust in cloud environment is regarded as a self-organizing system, using bionic mechanism, a dynamic trust evaluation method with family attribute is proposed. In this method, factors of trust evaluation include time, IP and behavior feedback. Data structure of access record table and trust record table are designed to store the relationship between ancestor nodes and descendant nodes. Based on trust information of the current node's ancestors, the biological evolution process is simulated. In order to minimize the influence of joint fraud on trust evaluation, the connected graph of ancestor nodes is constructed to evaluate the comprehensive trust of the node? which is converted to TSP problem and the optimal sequence of ancestor nodes is got by ant colony algorithm. The influence weight of ancestor node's trust on the current node's trust evaluation is denoted by the geometric sequence, and each factor's trust evaluation value of the current node is calculated. According to each factor's average weight of ancestor nodes, the comprehensive trust value of the current node is calculated. The simulation result shows that the trust evaluation method based on bionic mechanism is effective, and trust evaluation process of the current node can be regarded as comprehensive application of the ancestors' trust information, and the optimal trust sequence is searched. With increasing of ancestor nodes' trust information, the trust evaluation result is more accurate, which can effectively solve the joint fraud problem.

***

**_ESRQ: An Efficient Secure Routing Method in Wireless Sensor Networks Based on Q-Learning_**  
Liu, G.; Wang, X.; Li, X.; Hao, J.; Feng, Z.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00032  

##### Some trust-based methods have been proposed for consideration by guaranteeing the security routing of wireless sensor networks (WSN) recently. However, Most of the current research work usually consumes a lot of energy resources and computing resources or only performs well for specific types of attacks. In this paper, we propose a lightweight and efficient security routing method by combining the trust mechanism with q-learning algorithm. The sensor node determines the credibility of the specific node autonomously and efficiently according to the performance of the behavior of the node. The results show that 1) this method provides a more secure routing mechanism and it can effectively deal with many kinds of attacks; and 2) the method is lightweight and reliable, it provides better energy/packet delivery tradeoff performance compared with other existing trust-based methods and can cope with different conditions.

***

**_Trust-Based Dynamic Linear Threshold Models for Non-competitive and Competitive Influence Propagation_**  
Caliò, A.; Tagarelli, A.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00033  

##### What are the key-features that enable an information diffusion model to explain the inherent dynamic, and often competitive, nature of real-world propagation phenomena? In this paper we aim to answer this question by proposing a novel class of diffusion models, inspired by the classic Linear Threshold model, and built around the following aspects: trust/distrust in the user relationships, which is leveraged to model different effects of social influence on the decisions taken by an individual; changes in adopting one or alternative information items; hesitation towards adopting an information item over time; latency in the propagation; time horizon for the unfolding of the diffusion process; and multiple cascades of information that might occur competitively. To the best of our knowledge, the above aspects have never been unified into the same LT-based diffusion model. We also define different strategies for the selection of the initial influencers to simulate non-competitive and competitive diffusion scenarios, particularly related to the problem of limitation of misinformation spread. Results on publicly available networks have shown the meaningfulness and uniqueness of our models.

***

**_A Trust Energy-Efficient QoS Routing Scheme for Mobile Peer-to-Peer Networks_**  
Qu, D.; Liang, D.; Wu, S.; Li, J.; Xuan, W.; Wang, X.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00035  

##### Due to the ubiquitous use of wireless communication and enormous success of peer-to-peer (P2P) mode in wired networks, mobile P2P network (MP2P) attracts increasing attentions. However, the selfishness of nodes caused by the P2P mode, the scarcity of resources, and the Quality of Service (QoS) requirements of various network applications make it difficult to design an appropriate routing scheme. Thus, in this paper, we propose a trust energy-efficient QoS routing scheme in MP2P. We evaluate a routing path from three different aspects, namely, trust, energy consumption and QoS respectively. We apply interval forms to denote the network states and application requirements respectively for their difficulty to obtain and describe accurately, and calculate their matching by probability model and satisfaction degree as the evaluation value of a link. Then a heuristic routing protocol is proposed to find satisfied routing paths. Results from simulation experiments demonstrate that our proposed scheme has a better performance.

***

**_An Elite Clone Parallel Genetic Algorithm for Trust Monitoring Assignment Problem in Adaptive Wireless Sensor Networks_**  
Zhou, J.; Tian, M.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00039  

##### Adaptive wireless sensor networks (AWSNs) consist of sensors that have sensing, computation, wireless communication, and free-infrastructure abilities. AWSNs have applications in the fields of transportation, environmental monitoring, homelands security, automated assistance for the elderly monitors, industrial process control, military purposes and many other areas. The trust monitoring assignment scheme is usually designed for AWSNs to enhance the monitored rate. However, the trust monitoring assignment problem can be formulated as a nonlinear mixed integer optimization problem. In this paper, we propose an elite clone parallel genetic algorithm (ECPGA) based trust monitoring assignment approach for maximizing the monitored rate. We formulate our objective function to optimize the monitored rate under multiple constraints. The proposed algorithm combines the advantages of high efficiency of elite selection and the global search ability of the clone mutation. An analysis is given to show the correctness of ECPGA, and simulations are conducted to demonstrate the performance improvement of ECPGA against simulated annealing (SA) and ant colony optimization (ACO). Although sub-optimal for AWSNs systems, simulation results demonstrate that the proposed ECPGA algorithm can reach higher monitoring rate compared to the SA and ACO approach.

***

**_Quality of Information as an indicator of Trust in the Internet of Things_**  
Baqa, H.; Truong, N. B.; Crespi, N.; Lee, G. M.; Gall, F. Le  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00040  

##### The past decade has seen a rise in complexity and scale of software systems, particularly with the emerging of the Internet of Thing consisting of large scale and heterogeneous entities which results in difficulties in providing trustworthy services. To overcome such challenges, providing high quality information for IoT service provider as well as monitoring trust relationship of end-users toward the services are paramount. Such trust relationships are user-oriented and subjective phenomenon that hook on specific quality of data. Following this catalyst, we propose a mechanism to evaluate quality of information (QoI) for streaming data from sensor device; then use the QoI evaluation score as an indicator of trust. Concepts and assessment methodology for QoI along with a trust monitoring system are described. We also develop a framework that classifies streaming of data based on semantic context and generate QoI score as a relevant input for a trust monitoring component. This framework enables a dynamic trust management in the context of IoT for both end-users and services that empowers service providers to deliver trustworthy and high quality IoT services. Challenges encountered during implementation and contribution in standardization are discussed. We believe this paper offers better understanding on QoI and its importance in trust evaluation in IoT applications; also provides detailed implementation of the QoI and Trust components for real-world applications and services.

***

**_Practical Decentralized Attribute-Based Delegation Using Secure Name Systems_**  
Schanzenbach, M.; Banse, C.; Schütte, J.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00046  

##### Identity and trust in the modern Internet are centralized around an oligopoly of identity service providers consisting solely of major tech companies. The problem with centralizing trust has become evident in recent discoveries of mass surveillance and censorship programs as well as information leakage through hacking incidents. One approach to decentralizing trust is distributed, attribute-based access control via attribute-based delegation (ABD). Attribute-based delegation allows a large number of cross-domain attribute issuers to be used in making authorization decisions. Attributes are not only issued to identities, but can also be delegated to other attributes issued by different entities in the system. The resulting trust chains can then be resolved by any entity given an appropriate attribute storage and resolution system. While current proposals often fail at the practicability, we show how attribute-based delegation can be realized on top of the secure GNU Name System (GNS) to solve an authorization problem in a real-world scenario.

***

**_Online Allocation of Cloud Resources Based on Security Satisfaction_**  
Halabi, T.; Bellaiche, M.; Abusitta, A.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00063  

##### Businesses are becoming increasingly interested in exploiting the Cloud Computing technology. However, Cloud insecurity is still among the main factors that are blocking the full migration towards this paradigm. Increasing security investments will speed up the Cloud adoption process and improve the trustworthiness of the Cloud Service Providers (CSP). Moreover, the integration of the security element into the process of resource allocation will help increase the protection of the deployed services. However, this integration requires suitable modeling of customers' security requirements and CSPs' security offerings. To this end, we propose in this paper a broker-based model for the allocation of resources in the Cloud based on service security satisfaction. The resource allocation problem is modeled as a linear optimization problem and solved using an Evolutionary Computation approach, namely, the Genetic Algorithm (GA). The objective is to maximize the global security satisfaction of users' services by placing them on the data centers that adhere the most to their security requirements. Results show that the GA achieves an acceptable approximation of the optimal solution and is computationally efficient, which makes it suitable to function in online mode and cope with the scalability of the Cloud environment.

***

**_Inscription: Thwarting ActionScript Web Attacks From Within_**  
Sridhar, M.; Mohanty, A.; Yilmaz, F.; Tendulkar, V.; Hamlen, K. W.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00078  

##### The design and implementation of Inscription, the first fully automated Adobe Flash binary code transformation system that can guard major Flash vulnerability categories without modifying vulnerable Flash VMs, is presented and evaluated. Inscription affords a means of mitigating the significant class of web attacks that target unpatched, legacy Flash VMs and their apps. Such legacy VMs, and the new and legacy Flash apps that they run, continue to abound in a staggering number of web clients and hosts today; their security issues routinely star in major annual threat reports and exploit kits worldwide. Through two complementary binary transformation approaches based on in-lined reference monitoring, it is shown that many of these exploits can be thwarted by a third-party principal (e.g., web page publisher, ad network, network firewall, or web browser) lacking the ability to universally patch all end-user VMs-write-access to the untrusted Flash apps (prior to execution) suffices. Detailed case-studies describing proof-of-concept exploits and mitigations for five major vulnerability categories are reported.

***

**_A Temporal and Spatial Constrained Attribute-Based Access Control Scheme for Cloud Storage_**  
Liu, Z.; Jiang, Z. L.; Wang, X.; Yiu, S. M.; Zhang, R.; Wu, Y.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00092  

##### Cloud storage service allows data owners to store their (encrypted) data in a remote and may be untrusted cloud server. Attribute-Based Encryption (ABE) provides an excellent and flexible solution for data access control. As more and more applications evolved, ABE schemes may not handle all scenarios, in particular, if the access control has a time and location constraint. Time and location attributes are not as static as other general attributes. Existing ABE schemes cannot efficiently handle the continuous range of an attribute making it impractical for temporal and spatial constraints that are changing dynamically. In this paper, we propose a novel temporal and spatial constrained attribute-based access control (TSC-ABAC) scheme to solve this problem. Our system adopts a redesigned access structure and makes use of multi-dimensional range derivation function to match the time domain. This is the first ABE scheme that can efficiently handle time and location elements simultaneously. We further propose an extended TSC-ABAC scheme, which aims at reducing the decryption cost imposed on user. A thorough security and performance analysis shows that our design is secure and efficient. The result of our work could provide a feasible and practical data access control scheme for cloud storage services.

***

**_Blockchain Based Secured Identity Authentication and Expeditious Revocation Framework for Vehicular Networks_**  
Malik, N.; Nanda, P.; Arora, A.; He, X.; Puthal, D.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00099  

##### Authentication and revocation of users in Vehicular Adhoc Networks (VANETS) are two vital security aspects. It is extremely important to perform these actions promptly and efficiently. The past works addressing these issues lack in mitigating the reliance on the centralized trusted authority and therefore do not provide distributed and decentralized security. This paper proposes a blockchain based authentication and revocation framework for vehicular networks, which not only reduces the computation and communication overhead by mitigating dependency on a trusted authority for identity verification, but also speedily updates the status of revocated vehicles in the shared blockchain ledger. In the proposed framework, vehicles obtain their Pseudo IDs from the Certificate Authority (CA), which are stored along with their certificate in the immutable authentication blockchain and the pointer corresponding to the entry in blockchain, enables the Road Side Units (RSUs) to verify the identity of a vehicle on road. The efficiency and performance of the framework has been validated using the Omnet++ simulation environment.

***

**_Fully Decentralized Authentication and Revocation Scheme in Data Sharing Systems_**  
Li, X.; Jiang, J.; Chen, Y.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00100  

##### In this paper, we propose a fully decentralized authentication and revocation scheme(f-DMA) based on multi-authority attribute-based encryption that can be used in data sharing systems with multiple distrusted authorizes. This scheme establishes a fully decentralized secret key generation and key distribution systems, which eliminates the security risk on central authority(CA) compromise and is resilient to authority and user collusion attacks. Our system also provides computation efficient revocation that can achieve both specific user revocation and attribute revocation. We prove our scheme correct under the Decisional Bilinear Diffie-Hellman (DBDH) assumption; we also include a complete end-to-end implementation that demonstrates the practical efficacy of our technique.

***

**_An Experimental Flow Secure File System_**  
Rudrapatna, S.; Kumar, N. Narendra; Taware, A.; Vyas, P.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00113  

##### Information-flow control (IFC) encompasses several practical end-to-end security requirements including confidentiality and integrity, and is widely regarded as a uniform approach to building secure systems. File system is an important component of any secure system as it is the most widely used channel for information sharing among applications. In this paper, we present a design and implementation of a secure file system, based on the Readers-Writers Flow Model (RWFM), for a Linux OS. The secure file system imposes requisite access controls at the granularity of operating system processes, and controls information-flow via the file-system objects. That the system indeed prevents misuse of indirect information flow is demonstrated by encoding practical security policies like the standard Linux access controls, RBAC, Chinese-wall etc. One of the distinct characteristics of the approach is that it satisfies the property of labeled security protection as envisaged in the Trusted Computer System Evaluation Criteria; perhaps the first on a full file system of a widely used OS. Another distinct advantage of our system is that it requires (i) minimal effort from the end-user for specifying the initial policy, and (ii) no additional effort from the programmers perspective. The current implementation is illustrated through examples, compared with implementations of other similar efforts related to file-systems and other relevant facets from the literature.

***

**_Reinforcing IoT-Enforced Security Policies_**  
Oualha, N.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00119  

##### To provide confidentiality protection and access control to large amount of data generated by the Internet of Things (IoT), one promising approach lies on the use of Attribute-Based Encryption (ABE). However, the ABE-based approach needs to cope with the resource constraints of IoT devices, by providing data encryption and access control only under small access policies. With the goal to mitigate this limitation inherent to the IoT, this paper introduces a new technique that relies on semi-trusted intermediate entities to reinforce large access policies derived from small policies enforced by IoT devices without revealing the encrypted data.

***

**_Lightweight Verification for Searchable Encryption_**  
Wang, B.; Fan, X.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00132  

##### Symmetric Searchable Encryption (SSE) is a promising primitive to securely perform keyword queries and to efficiently retrieve associated files from a curious server without sacrificing data privacy. Unfortunately, besides being curious, an untrusted server could also be malicious, which would return incorrect or incomplete results to a client. Since a client does not maintain its entire dataset locally after outsourcing, preventing malicious servers is necessary and challenging. In this paper, we propose a lightweight Verifiable SSE scheme, which can verify the correctness and completeness of keyword search results obtained from SSE against a malicious server. Our scheme not only achieves an asymptotically efficient verification time and communication overhead, but also outperforms previous solutions in practice. Moreover, our scheme can efficiently support updates on verification metadata. We formally define and analyze the security of our scheme, and conduct extensive experiments on massive datasets to demonstrate the efficiency of our scheme.

***

**_Capstone: Mobility Modeling on Smartphones to Achieve Privacy by Design_**  
Kulkarni, V.; Moro, A.; Chapuis, B.; Garbinato, B.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00136  

##### Sharing location traces with context-aware service providers has privacy implications. Location-privacy preserving mechanisms, such as obfuscation, anonymization and cryptographic primitives, have been shown to have impractical utility/privacy tradeoff. Another solution for enhancing user privacy is to minimize data sharing by executing the tasks conventionally carried out at the service providers' end on the users' smartphones. Although the data volume shared with the untrusted entities is significantly reduced, executing computationally demanding server-side tasks on resource-constrained smartphones is often impracticable. To this end, we propose a novel perspective on lowering the computational complexity by treating spatiotemporal trajectories as space-time signals. Lowering the data dimensionality facilitates offloading the computational tasks onto the digital-signal processors and the usage of the non-blocking signal-processing pipelines. While focusing on the task of user mobility modeling, we achieve the following results in comparison to the state of the art techniques: (i) mobility models with precision and recall greater than 80%, (ii) reduction in computational complexity by a factor of 2.5, and (iii) reduction in power consumption by a factor of 0.5. Using real-world mobility datasets, we demonstrate the suitability of our technique to function on smartphones.

***

**_AuthStore: Password-Based Authentication and Encrypted Data Storage in Untrusted Environments_**  
Zeidler, C.; Asghar, M. R.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00140  

##### Passwords are widely used for client to server authentication as well as for encrypting data stored in untrusted environments, such as cloud storage. Both, authentication and encrypted cloud storage, are usually discussed in isolation. In this work, we propose AuthStore, a flexible authentication framework that allows users to securely reuse passwords for authentication as well as for encrypted cloud storage at a single or multiple service providers. Users can configure how secure passwords are protected using password stretching techniques. We present a compact password-authenticated key exchange protocol (CompactPAKE) that integrates the retrieval of password stretching parameters. A parameter attack is described and we show how existing solutions suffer from this attack. Furthermore, we introduce a password manager that supports CompactPAKE.

***

**_Track me if you can? Query Based Dual Location Privacy in VANETs for V2V and V2I_**  
Arif, M.; Wang, G.; Peng, T.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00152  

##### In the Vehicular Ad-hoc Networks (VANETs), a vehicle or the vehicle driver could be recognized and tracked by eavesdropping its queries (e.g., beacons) by an adversary, since these quires contain personal information and data such as the queries and location of the vehicle. This attack leads to threats on the vehicles location privacy. The current solutions, exercises Anonymizer, a third trusted party (TTP) in between the LBS and the vehicles. The insertion of the TTP shifts the endangered entity from the LBS to the Anonymizer, regarding security risk, and with the jeopardized anonymizer, the vehicles or vehicles drivers related data will also be at risk. In this paper, we come up with efficient query based dual location privacy in VANETs for V2V and V2I communication. In which we use the circle based dummy generation (CBDG) algorithm along with TTP. Before sending the query to the TTP first we create some dummy location by using CBDG, because we cannot trust completely on TTP architecture. And then we use CASPER as TTP to process the desired query from vehicles to LBS. after receiving the processed query from the LBS, the TTP sends the results back to the drives, where the vehicle drivers finds their desired results. Our results shows that the proposed scheme preserve the location privacy based on the queries at low communication and computational cost.

***

**_QueryGuard: Privacy-Preserving Latency-Aware Query Optimization for Edge Computing_**  
Xu, R.; Palanisamy, B.; Joshi, J.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00153  

##### The emerging edge computing paradigm has enabled applications having low response time requirements to meet the quality of service needs of applications by moving the computations to the edge of the network that is geographically closer to the end-users and end-devices. Despite the low latency advantages provided by the edge computing model, there are significant privacy risks associated with the adoption of edge computing services for applications dealing with sensitive data. In contrast to cloud data centers where system infrastructures are managed through strict and regularized policies, edge computing nodes are scattered geographically and may not have the same degree of regulatory and monitoring oversight. This can lead to higher privacy risks for the data processed and stored at the edge nodes, thus making them less trusted. In this paper, we show that a direct application of traditional performance-based query optimization techniques in edge computing can lead to unexpected data disclosure risks at the edge nodes. We propose a new privacy-preserving latency-aware query optimization framework, QueryGuard, that simultaneously tackles the privacy-aware distributed query processing problem while optimizing the queries for latency. Our experimental evaluation demonstrates that QueryGuard achieves better performance in terms of execution time and memory usage than conventional distributed query optimization techniques while also enforcing the required constraints related to data privacy.

***

**_PMDA: Privacy-Preserving Multi-functional Data Aggregation Without TTP in Smart Grid_**  
He, Z.; Pan, S.; Lin, D.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00154  

##### In the smart grid, residents' electricity usage needs to be periodically measured and reported for the purpose of better energy management. At the same time, real-time collection of residents' electricity consumption may unfavorably incur privacy leakage, which has motivated the research on privacy-preserving aggregation of electricity readings. Most previous studies either rely on a trusted third party (TTP) or suffer from expensive computation. In this paper, we first reveal the privacy flaws of a very recent scheme pursing privacy preservation without relying on the TTP. By presenting concrete attacks, we show that this scheme has failed to meet the design goals. Then, for better privacy protection, we construct a new scheme called PMDA, which utilizes Shamir's secret sharing to allow smart meters to negotiate aggregation parameters in the absence of a TTP. Using only lightweight cryptography, PMDA efficiently supports multi-functional aggregation of the electricity readings, and simultaneously preserves residents' privacy. Theoretical analysis is provided with regard to PMDA's security and efficiency. Moreover, experimental data obtained from a prototype indicates that our proposal is efficient and feasible for practical deployment.

***

**_An Efficient Blacklistable Anonymous Credential System with Reputation Using Pairing-Based Accumulator_**  
Nakanishi, T.; Kanatani, T.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00158  

##### To achieve the privacy-enhancing authentications without any TTP (Trusted Third Party), blacklistable anonymous credential systems have been proposed. In conventional blacklistable anonymous credential systems, a user is blacklisted after the user misbehaves once. Since it is too harsh to be of practical use, extended blacklistable anonymous credential systems based on reputation have been proposed. In the reputation-based system, each behavior of a user is given a score. The service provider publishes a reputation list of correspondences between session ID and the score. In the authentication, a user can anonymously prove the total of his own scores. However, the previously proposed systems have the efficiency problem: The authentication data size is O(|L|) or O(K), where |L| is the size of the reputation list L, and K is the size of the following window. In the window type of systems, the authentication is based on a window with most recent K authentications of the user. When a past authentication becomes outside the window, the misbehaving of the authentication is forgiven. Thus, K should be as large as possible. Therefore, the previous systems suffer from O(|L|) or O(K)-size data in each authentication. In addition, in the previous systems, the authentication needs the computation of O(|L|) or O(K) exponentiations, which is heavy. In this paper, an efficient blacklistable anonymous credential system with reputation is proposed. In our system, the data size of the authentication does not depend on parameters such as |L| and K, and is O(1). Furthermore, although the computational costs in the authentication depend on some parameters, the parameter-related costs are only multiplications instead of exponentiations. For constructing our system, we newly introduce the concept of an accumulator for reputation, and show an efficient pairing-based construction. Using the accumulator, we construct the efficient blacklistable anonymous credential system with reputation.

***

**_Towards Domain-Specific and Privacy-Preserving Qualified eID in a User-Centric Identity Model_**  
Lenz, T.; Krnjic, V.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00160  

##### Unique and qualified identification is essential in numerous security-critical areas, like eGovernment, or eBusiness. Therefore, many countries have already deployed eID solutions to confirm identity information of entities and to increase trust into the identity information. Many of these confirmation solutions only support an all-or-nothing disclosure, which means that selective disclosure of single attributes is not possible. Some other work has dealt with this privacy issue by using anonymous credentials or malleable signatures. However, all of these solutions lacks in flexible generation of qualified and provable pseudonyms that based on confirmed eID information. In this paper, we propose an advanced and lightweight model for user-centric and qualified identity information that facilitates selective disclosure and domain-specific altering of single identity attributes in order to protect the citizen's privacy. We illustrate the practical applicability of our model by implementing all components as prototype applications. Finally, we evaluate our model and compare it with other approaches for selective disclosure.

***

**_RZKPB: A Privacy-Preserving Blockchain-Based Fair Transaction Method for Sharing Economy_**  
Li, B.; Wang, Y.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00161  

##### Emerging blockchain systems have been widely adopted in sharing economy, such as e-commerce, to allow mutually distrustful parties to transact fairly without trusted parties. Most blockchain systems, however, lack transactional privacy protection. All transactions, including trading relationship between pseudonyms and content transacted, are exposed on the blockchain. Although many existing privacy protection methods on the blockchain have been proposed, it is difficult to find a trade-off between keeping speed and protecting privacy of transactions. To address this limitation, we propose a novel privacy-preserving method RZKPB that does not store financial transactions in clear on the blockchain, thus retaining transactional privacy from the public's view. Meanwhile, these transactions are as proofs to solve disputes between trading partners. RZKPB ensures fairness and privacy of transactions between participants without adding a new trusted party and breaking the verifying protocol on the blockchain. We take the e-commerce as an example in sharing economy to introduce RZKPB in our paper. Our experimental results show that compared with existing privacy-preserving methods based on the blockchain, RZKPB is more efficient under different settings.

***

**_PHeDHA: Protecting Healthcare Data in Health Information Exchanges with Active Data Bundles_**  
Fadheel, W.; Salih, R.; Lilien, L.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00164  

##### Health Information Exchanges (HIEs) collect and disseminate electronic patient healthcare data (EHRs/EMRs) among different healthcare providers to improve the quality and reduce the cost of healthcare services. However, the dissemination of patient data raises privacy and security concerns due to ease of copying and unauthorized dissemination of electronic data. This paper proposes a HIE system called PHeDHA (Protecting Healthcare Data in HIEs with Active Data Bundles), which provides privacy and security protection for patient data during their transmission via an HIE among different healthcare providers. PHeDHA uses as its basis the scheme named Active Data Bundles with Trusted Third Party (ADB-TTP). As the name suggests, ADB-TTP is based on an integration of a trusted third party (TTP) with Active Data Bundles (ADBs). An ADB is a software object that keeps patient healthcare data as sensitive data; includes metadata describing these sensitive data and prescribing their use (via data access and privacy policies specified within metadata); and encompasses a policy enforcement engine (called a virtual machine or VM), which controls and manages how the ADB behaves. In particular, the VM assures ADB's data integrity and enforces its policies specified as a part of metadata. We describe and discuss the conceptual model for PHeDHA, based on ADB-TTP. We are currently evaluating PHeDHA via simulation experiments.

***

**_Monero Ring Attack: Recreating Zero Mixin Transaction Effect_**  
Wijaya, D. A.; Liu, J.; Steinfeld, R.; Liu, D.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00165  

##### Monero is one of the privacy-preserving cryptocurrencies employing CryptoNote protocol. The privacy features in Monero are provided by cryptographic techniques such as linkable ring signature and one-time public key. Recent studies show that the majority of Monero inputs are traceable prior to mandatory RingCT transaction. After the RingCT was implemented, the problems were mitigated. We propose a novel attack to reduce the anonymity of Monero transactions or even to fully deanonymise the inputs. The proposed protocol can be launched in RingCT protocol and enables multiple attackers to collaborate without trusting each other. The attack scheme can be planted in the existing Monero services without extra fees and without putting the users' money at risk.

***

**_PANDORA: Preserving Privacy in PRNU-Based Source Camera Attribution_**  
Mohanty, M.; Zhang, M.; Asghar, M. R.; Russello, G.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00166  

##### Photo Response Non-Uniformity (PRNU) noise-based source camera attribution is a popular digital forensic method. In this method, a camera fingerprint computed from a set of known images of the camera is matched against the extracted noise of an anonymous questionable image to find if the camera had taken the anonymous image. The possibility of privacy leak, however, is one of the main concerns of the PRNU-based method. Using the camera fingerprint (or the extracted noise), an adversary can identify the owner of the camera by matching the fingerprint with the noise of an image (or with the fingerprint computed from a set of images) crawled from a social media account. In this paper, we address this privacy concern by encrypting both the fingerprint and the noise using the Boneh-Goh-Nissim (BGN) encryption scheme, and performing the matching in encrypted domain. To overcome leakage of privacy from the content of an image that is used in the fingerprint calculation, we compute the fingerprint within a trusted environment, such as ARM TrustZone. We present PANDORA that aims at minimizing privacy loss and allows authorized forensic experts to perform camera attribution.

***

**_Identifying Passive Message Fingerprint Attacks via Honey Challenge in Collaborative Intrusion Detection Networks_**  
Li, W.; Meng, W.; Wang, Y.; Kwok, L. F.; Lu, R.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00167  

##### To enhance the detection capability of a single intrusion detection system (IDS), collaborative intrusion detection networks (CIDNs) have been exploited and developed via enabling a set of IDS nodes to exchange information with each other. In CIDNs, challenge-based trust mechanism has been considered as one promising solution to identify malicious nodes by evaluating the satisfaction levels between challenges and responses. However, such mechanism is still vulnerable to some advanced insider attacks like passive message fingerprint attack (PMFA), which is deemed as an advanced attack on challenge-based CIDNs by collecting messages and identifying normal requests in a passive way. In this work, we focus on PMFA and design Honey Challenge, an improved challenge mechanism for challenge-based CIDNs characterized by sending challenges in a similar way of sending normal requests, in such a way malicious nodes cannot accurately identify the normal requests. In the evaluation, we investigate the attack performance under both simulated and real network environments. Experimental results demonstrate that our proposed mechanism can identify malicious nodes under PMFA and decrease their trust values in a quick manner.

***

**_Enabling Trust in Deep Learning Models: A Digital Forensics Case Study_**  
K, A.; Grzonkowski, S.; Lekhac, N.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00172  

##### Today, the volume of evidence collected per case is growing exponentially, to address this problem forensics investigators are looking for investigation process with tools built on new technologies like big data, cloud services, and Deep Learning (DL) techniques. Consequently, the accuracy of artifacts found also relies on the performance of techniques used, especially DL models. Recently, Deep Neural Nets (DNN) have achieved state of the art performance in the tasks of classification and recognition. In the context of digital forensics, DNN has been applied in the domains of cybercrime investigation such as child abuse investigations, malware classification, steganalysis and image forensics. However, the robustness of DNN models in the context of digital forensics is never studied before. Hence, in this research, we design and implement a domain-independent Adversary Testing Framework (ATF) to test security robustness of black-box DNN's. By using ATF, we also methodically test a commercially available DNN service used in forensic investigations and bypass the detection, where published methods fail in control settings.

***

**_Managed Blockchain Based Cryptocurrencies with Consensus Enforced Rules and Transparency_**  
Mell, P.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00177  

##### Blockchain based cryptocurrencies are usually unmanaged, distributed, consensus-based systems in which no single entity has control. Managed cryptocurrencies can be implemented using private blockchains but are fundamentally different as the owners have complete control to do arbitrary activity without transparency (since they control the mining). In this work we explore a hybrid approach where a managed cryptocurrency is maintained through distributed consensus based methods. The currency administrator can perform ongoing management functions while the consensus methods enforce the rules of the cryptocurrency and provide transparency for all management actions. This enables the introduction of money management features common in fiat currencies but where the managing entity cannot perform arbitrary actions and transparency is enforced. We thus eliminate the need for users to trust the currency administrator but also to enable the administrator to manage the cryptocurrency. We demonstrate how to implement our approach through modest modifications to the implicit Bitcoin specification, however, our approach can be applied to most any blockchain based cryptocurrency using a variety of consensus methods.

***

**_Blockchain as a Notarization Service for Data Sharing with Personal Data Store_**  
Chowdhury, M. J. M.; Colman, A.; Kabir, M. A.; Han, J.; Sarda, P.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00183  

##### Personal data such as electronic medical records and academic records are critical and sensitive private information. These personal information is usually hosted across many data-custodian systems. Personal Data Store (PDS) is a service that lets an individual store, manage and deploy their key personal data in a highly secure and structured way. It also gives the user a central point of control for their personal information. One of the inherent problems of digital records is that it can be easily forged. Therefore, the data-consumer(with whom the data is shared) often needs to verify the authenticity of the shared document/record by communicating with the document/certificate issuing authority (e.g., data custodian). However, this process is time consuming and inefficient. In recent time, blockchain has gained tremendous attention from both industry and academia for distributed recording and immutable transactions. Blockchain provides a shared, immutable and transparent history of transactions enabling the building of applications that incorporate trust, accountability and transparency. This provides a unique opportunity to develop a secure and trustable data sharing system using blockchain. However, blockchain is primarily proposed for publicly verifiable transactions and does not provide privacy to the individuals. In this paper, we propose a data sharing framework that will guarantee the authenticity of the shared data in real-time and provide transactional privacy in a blockchain network. We have implemented our framework in a prototype that ensures privacy, integrity, and fine-grained access control over the shared data. The proposed work can significantly reduce the turnaround time for data sharing, improve the decision making process and reduce the overall cost.

***

**_Qualified eID Derivation Into a Distributed Ledger Based IdM System_**  
Abraham, A.; Theuermann, K.; Kirchengast, E.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00195  

##### Traditional identity management systems (IdMS) suffer from significant weaknesses, such as the reliance on a single central entity that provides the identity data or the users lack control over their identity data. The introduction of qualified self-sovereign identities (SSIs) for eGovernment systems can strengthen the privacy of citizens. Furthermore, it is possible to solve fundamental trust issues of traditional IdMS by utilizing distributed ledger technology (DLT) together with performing a consensus algorithm. The contribution of this paper is twofold. First, this paper proposes a solution for the derivation of qualified electronic identities (eIDs), issued by a traditional IdMS, into a distributed ledger (DL) based IdMS that enables SSIs. Second, we have implemented a proof-of-concept (PoC) realizing qualified eID derivation into an SSI system based on the DLT. This PoC was realized, among others, by introducing an agent that represents the interface between the traditional IdM and the SSI system as well as by extending the consensus algorithm. The proposed approach used for eID derivation ensures the maintenance of the trust as well as the quality of the identity data.

***

**_A Hybrid Recommendation Algorithm Based on Heuristic Similarity and Trust Measure_**  
Yang, C.; Chen, X.; Song, T.; Jiang, B.; Liu, Q.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00196  

##### In this paper, we propose a hybrid collaborative filtering recommendation algorithm based on heuristic similarity and trust measure, in order to alleviate the problem of data sparsity, cold start and trust measure. Firstly, a new similarity measure is implemented by weighted fusion of multiple similarity influence factors obtained from the rating matrix, so that the similarity measure becomes more accurate. Then, a user trust relationship computing model is implemented by constructing the user's trust network based on the trust propagation theory. On this basis, a SIMT collaborative filtering algorithm is designed which integrates trust and similarity instead of the similarity in traditional collaborative filtering algorithm. Further, an improved K nearest neighbor recommendation based on clustering algorithm is implemented for generation of a better recommendation list. Finally, a comparative experiment on FilmTrust dataset shows that the proposed algorithm has improved the quality and accuracy of recommendation, thus overcome the problem of data sparsity, cold start and trust measure to a certain extent.

***

**_Building Trusted Golden Models-Free Hardware Trojan Detection Framework Against Untrustworthy Testing Parties Using a Novel Clustering Ensemble Technique_**  
Bian, R.; Xue, M.; Wang, J.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00203  

##### As a result of the globalization of integrated circuits (ICs) design and fabrication process, ICs are becoming vulnerable to hardware Trojans. Most of the existing hardware Trojan detection works suppose that the testing stage is trustworthy. However, testing parties may conspire with malicious attackers to modify the results of hardware Trojan detection. In this paper, we propose a trusted and robust hardware Trojan detection framework against untrustworthy testing parties exploiting a novel clustering ensemble method. The proposed technique can expose the malicious modifications on Trojan detection results introduced by untrustworthy testing parties. Compared with the state-of-the-art detection methods, the proposed technique does not require fabricated golden chips or simulated golden models. The experiment results on ISCAS89 benchmark circuits show that the proposed technique can resist modifications robustly and detect hardware Trojans with decent accuracy (up to 91%).

***

**_Behavioral Based Trust Metrics and the Smart Grid_**  
Obert, J.; Chavez, A.; Johnson, J.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00209  

##### To ensure reliable and predictable service in the electrical grid it is important to gauge the level of trust present within critical components and substations. Although trust throughout a smart grid is temporal and dynamically varies according to measured states, it is possible to accurately formulate communications and service level strategies based on such trust measurements. Utilizing an effective set of machine learning and statistical methods, it is shown that establishment of trust levels between substations using behavioral pattern analysis is possible. It is also shown that the establishment of such trust can facilitate simple secure communications routing between substations.

***

**_Concepts for Trust Propagation in Knowledge Processing Systems - A Brief Introduction and Overview_**  
Jäger, M.; Nadschläger, S.; Küng, J.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00212  

##### What is ""Trust""? Everybody has a sense of trusting people or institutions, but how is trust defined? The definition of trust always depends on the specific field of research and application, which makes it hard to answer this question in general at a computational level. Thinking of knowledge processing systems we face this question twice. How can we define and calculate trust values for the input data and, more challenging, what is the trust value of the output? Within this paper we consider a binary, a probabilistic, an opinion-space and - our recently developed approach - a weighted arithmetic mean trust model. Then we show ways, how knowledge processing systems can handle these trust values and propagate them through a network of processing steps in a way that the final results are representative. With these presented and developed models, we can give insights to the topic of defining and propagating trust in knowledge processing systems.

***

**_Towards Trustworthy Information Sharing by Creating Cyber Security Alliances_**  
Deljoo, A.; Engers, T. van; Koning, R.; Gommans, L.; Laat, C. de  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00213  

##### As attacks are becoming more and more organized, collaboration amongst network domain owners is required next to arranging technical counter measures. Sharing cyber intelligence amongst network domain owners is, therefore, becoming increasingly important. Additionally, networks have grown scale, complexity, and degree of inter-connectedness, such that their protection can often only be guaranteed and financed as a shared effort. In this paper, we introduce the concept of cyber security alliance shaped by different organizations that facilitate the sharing of incident information across them. Creating a cyber security alliance highlights requirements such as: 1) creates and manages trust among the members, 2) introduces a federated governance model, creating common policies, standards for alliance's members, and 3) provides a strong incentive to partners to join an alliance by introducing a common benefit. This paper discusses ongoing research on a social trust model, which helps the members to select the right partner to perform joint tasks, and encourages sharing of incident information. Furthermore, we use the service provider group framework as a way to arrange the establishment of our proposed cyber security alliance that coordinates activities across the alliance to establish trust. We present our social computational trust model and its antecedents.

***

**_Detection and Prevention of Routing Attacks in Internet of Things_**  
Choudhary, S.; Kesswani, N.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00219  

##### Internet of things (IoT) is the smart network which connects smart objects over the Internet. The Internet is untrusted and unreliable network and thus IoT network is vulnerable to different kind of attacks. Conventional encryption and authentication techniques sometimes fail on IoT based network and intrusion may succeed to destroy the network. So, it is necessary to design intrusion detection system for such network. In our paper, we detect routing attacks such as sinkhole and selective forwarding. We have also tried to prevent our network from these attacks. We designed detection and prevention algorithm, i.e., KMA (Key Match Algorithm) and CBA (Cluster- Based Algorithm) in MatLab simulation environment. We gave two intrusion detection mechanisms and compared their results as well. True positive intrusion detection rate for our work is between 50% to 80% with KMA and 76% to 96% with CBA algorithm.

***

**_UCAM: Usage, Communication and Access Monitoring Based Detection System for IoT Botnets_**  
Sajjad, S. M.; Yousaf, M.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00221  

##### Botnets are being used for launching Distributed Denial of Service (DDoS) attacks causing massive financial loses to the enterprises. With the rise of low-cost, less protected Internet of Things (IoT) devices the likelihood of harm from botnets have also increased. Open sourcing the source code of Mirai IoT malware has provided the foundation step for the development and subsequent launch of variants of Mirai IoT botnets. Detecting such kind of threats is essential for the smooth operation of the Internet. Such security measures are basic requirements for the establishment of user trust on the Internet of Things devices. This paper presents UCAM: Usage, Communication and Access Monitoring Based Botnets Detection System for IoT. The proposed solution has three main components i.e. descriptor, monitor and comparator. Descriptor defines Device Usage, Communication and Access policies. Monitor observes the current state of device Usage, Communication and Access. Anomalies are Detected by the Comparator. Results show that the proposed detection system successfully detects Mirai IoT malware.

***

**_Who Would you Like to be Today?: Impersonation by Fake Azure Active Directory Identity Federation_**  
Syynimaa, N.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00232  

##### Azure Active Directory (AAD) is Microsoft's cloud-based directory and identity management service used by various service providers (SPs). For instance, Microsoft's own Office 365 is utilizing identity management services of AAD. Hundreds of external SPs are also providing services which are supporting AAD identities. Besides cloud-based managed identities, AAD also supports federated identities where authentication is performed by the external identity provider (IdP). Identity federation is based on a trust between SP and IdP. In this paper, we will report a vulnerability in AAD identity federation which enables undetectable identity impersonation. The vulnerability is caused by a design flaw in the trust to IdPs. We will also introduce some methods to detect the exploitation of the vulnerability and provide advice how to limit the risk of exploitation.

***

**_Double-Blind Reputation vs. Intelligent Fake VIP Attacks in Cloud-Assisted Interactions_**  
Konorski, J.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00241  

##### We consider a generic model of Client-Server interactions in the presence of Sender and Relay, conceptual agents acting on behalf of Client and Server, respectively, and modeling cloud service providers in the envisaged ""QoS as a Service paradigm"". Client generates objects which Sender tags with demanded QoS level, whereas Relay assigns the QoS level to be provided at Server. To verify an object's right to a QoS level, Relay detects its signature that neither Client nor Sender can modify. Since signature detection is costly, Relay tends to occasionally skip it and trust an object; this prompts Sender to occasionally launch a Fake VIP attack, i.e., demand undue QoS level. In a Stackelberg game setting, Relay employs a trust strategy in the form of a double-blind reputation scheme so as to minimize the signature detection cost and undue QoS provision, anticipating a best-response Fake VIP attack strategy on the part of Sender. We ask whether the double-blind reputation scheme, previously proved resilient to a probabilistic Fake VIP attack strategy, is equally resilient to more intelligent Sender behavior. Two intelligent attack strategies are proposed and analyzed using two-dimensional Markov chains.

***

**_The Blockchain for Domain Based Static Sharding_**  
Yoo, H.; Yim, J.; Kim, S.  
https://doi.org/10.1109/TrustCom/BigDataSE.2018.00252  

##### Blockchain is the shared distributed ledger to record the history of transactions. In blockchain network, nodes validate the transactions and reach the consensus on the ordered transactions. The more transactions are happened, the more processing powers of nodes are needed. Shard is introduced to blockchain for processing the multiple transactions in parallel. In this paper, we propose the blockchain for a domain based static sharding. We split a blockchain into multiple shards based on the domain. In each shard, nodes validate the multiple transactions concurrently and keep the shard's ledger separately. With this, it can be processing of low-latency transaction. Also, by changing the composition of committee members that validate blocks dynamically, we can enable the blockchain to be more trust.

***

## [HFES2019](HFES2019.md) 63rd International Annual Meeting of the Human Factors and Ergonomics Society
Link: [[Proceedings](https://journals.sagepub.com/toc/proe/63/1)]
[[Conference](http://www.hfes2019.org/)]
Awardなし  
***
**_Trust in Automation as a Function of Transparency and Teaming_**  
  
https://doi.org/10.1177/1071181319631212  

##### Information analysis is a critical piece of successful operations. As automation becomes a more common element in this analysis, it is important to understand what information should be communicated to users to promote proper use of automation. Both transparency, information regarding how and why automation functions proceed, and uncertainty may be two vital pieces of communication. Method: Twenty-six participants completed a simulated tank identification task with an automated or human teammate across 3 levels of teammate transparency. Trials varied in presence or absence of uncertainty information. Trust and performance effects were evaluated. Users were shown a terrain image and had to determine if a military tank was present in the terrain. The teammate provided a Tank Present or Absent recommendation along with transparent reasoning for the recommendation. Participants then made a tank presence judgement. Results: Transparency increased user trust as well as reaction times. Having uncertainty information increased user trust, but decreased performance accuracy. Teammate type had no significant effect on trust, accuracy, or reaction time. Discussion: The data indicate that transparency and uncertainty information can help users form an accurate mental model of teammate capabilities.

***

**_Neural Correlates of Trust During an Automated System Monitoring Task: Preliminary Results of an Effective Connectivity Study_**  
Sanders, Nathan; Choo, Sanghyun; Kim, Nayoung; Nam, Chang S.; Fitts, Edward P.  
https://doi.org/10.1177/1071181319631409  

##### As autonomous systems become more prevalent and their inner workings become more opaque, we increasingly rely on trust to guide our interactions with them especially in complex or rapidly evolving situations. When our expectations of what automation is capable of do not match reality, the consequences can be sub-optimal to say the least. The degree to which our trust reflects actual capability is known as trust calibration. One of the approaches to studying this is neuroergonomics. By understanding the neural mechanisms involved in human-machine trust, we can design systems which promote trust calibration and possibly measure trust in real time. Our study used the Multi Attribute Task Battery to investigate neural correlates of trust in automation. We used EEG to record brain activity of participants as they watched four algorithms of varying reliability perform the SYSMON subtask on the MATB. Subjects reported their subjective trust level after each round. We subsequently conducted an effective connectivity analysis and identified the cingulate cortex as a node, and its asymmetry ratio and incoming information flow as possible indices of trust calibration. We hope our study will inform future work involving decision-making and real-time cognitive state detection.

***

**_Detecting Human Trust Calibration in Automation: A Deep Learning Approach_**  
Choo, Sanghyun; Sanders, Nathan; Kim, Nayoung; Kim, Wonjoon; Nam, Chang S.; Fitts, Edward P.  
https://doi.org/10.1177/1071181319631298  

##### 

***

**_An Empirical Exploration of Resilience in Human-Autonomy Teams Operating Remotely Piloted Aircraft Systems_**  
Demir, Mustafa; McNeese, Nathan J.; Cooke, Nancy J.; Grimm, David A.; Gorman, Jamie C.  
https://doi.org/10.1177/1071181319631020  

##### Project overviewTeam resilience is an interactive and dynamic process that develops over time while a team maintains performance. This study aims to empirically investigate systems-level resilience in a Remotely Piloted Aircraft (RPA) System simulated task environment by examining team interaction during novel events. The approach used in the current study to measure systems-level resilience was developed by Hoffman & Hancock (2017). In their conceptual study, resilience was considered a key feature of success in emerging complex sociotechnical systems; in our case, that is applied to Human-Autonomy Teams (HATs). Hoffman and Hancock conceptualized a resilience measure dynamically by means of several components, such as the time it took the system to recognize and characterize anomalies, and the time taken to specify and achieve new goals. In their framework, there were two main sub-events which expressed resilience via time-based measures, and upon which we designed ours in this study: (1) time taken to design a new process and (2) time required to implement it (Hoffman & Hancock, 2017).DesignIn this current research, there were three heterogeneous team members who used a text-based system to communicate and successfully photograph target waypoints: (1) navigator – provided information regarding a flight plan with speed and altitude restrictions of each waypoint; (2) pilot – controlled the RPA by adjusting its altitude and airspeed through negotiating with the photographer in order to take a good photo of the target waypoints; and (3) photographer – screened camera settings and sent feedback to the other team members regarding the status of target’s photograph. This study followed the Wizard of Oz paradigm wherein the navigator and photographer were seated together in one room and were told that the pilot was a synthetic agent. In actuality, the pilot was a well-trained experimenter who was working from a separate room. This ‘synthetic’ pilot used restricted vocabulary to simulate that of a computer. The main manipulations in this study consisted of three degraded conditions: (1) automation failure - role-level display failures while processing specific targets, (2) autonomy failure - autonomous agent behaved abnormally while processing specific targets (i.e., it provided misinformation to other team members or demonstrated incorrect actions), and (3) malicious cyber-attacks - the hijacking of the synthetic agent, which led to the synthetic agent providing false, detrimental information to the team about the RPA destination. Because the malicious cyber-attack only occurred once (during the final mission), we will focus on the automation and autonomy failures for this study. Each failure was imposed at a selected target waypoint and the teams had to find a solution in a limited amount of time. The time limit for each failure was related to the difficulty of the failure. Each failure was introduced at a pre-selected target waypoint for each team.MethodIn this experiment, there were 22 teams, with only two participants randomly assigned to the navigator and photographer roles for each team, because the pilot was a highly-trained experimenter. The current task was comprised of ten 40-minute missions in which teams needed to take as many “good” photos as possible of ground targets while avoiding alarms and rule violations. For this study, using the RPAS paradigm, we calculated two team resilience scores (1) time taken to design a new process and (2) time required to implement it (Hoffman & Hancock, 2017). For the calculations, we used the message sent time (in seconds) for each role to express resilience in terms of the proportion of total task time (2400 seconds). As an outcome measure, we used target processing efficiency as a coordination and time-based performance score, which was based on how quickly teams were able to take a good photo of each target.Results and discussionWe found that teams were more resilient during automation failures and progressed toward targets more successfully than during autonomy failures. We see three possible explanations for this: (1) automation failures were more explicit than autonomy failures, since at least one team member interacted with other teammates; (2) autonomy failures took more time for human teammates to identify the failure, because the autonomous agent’s abnormal behavior was not as straight forward; and 3) human teammates overtrusted to the autonomous agent and lack confidence in themselves and let the failure go on.AcknowledgementsThis research is supported by ONR Award N000141712382 (Program Managers: Marc Steinberg, Micah Clark). We also acknowledge the assistance of Steven M. Shope of Sandia Research Corporation, who integrated the synthetic agent and the testbed.

***

**_Enhancing Transparency in Human-autonomy Teaming via the Option-centric Rationale Display_**  
Luo, Ruikun; Du, Na; Huang, Kevin Y.; Yang, X. Jessie  
https://doi.org/10.1177/1071181319631366  

##### Human-autonomy teaming is a major emphasis in the ongoing transformation of future work space wherein human agents and autonomous agents are expected to work as a team. While the increasing complexity in algorithms empowers autonomous systems, one major concern arises from the human factors perspective: Human agents have difficulty deciphering autonomy-generated solutions and increasingly perceive autonomy as a mysterious black box. The lack of transparency could lead to the lack of trust in autonomy and sub-optimal team performance (Chen and Barnes, 2014; Endsley, 2017; Lyons and Havig, 2014; de Visser et al., 2018; Yang et al., 2017).In response to this concern, researchers have investigated ways to enhance autonomy transparency. Existing human factors research on autonomy transparency has largely concentrated on conveying automation reliability or likelihood/(un)certainty information (Beller et al., 2013; McGuirl and Sarter, 2006; Wang et al., 2009; Neyedli et al., 2011). Providing explanations of automation’s behaviors is another way to increase transparency, which leads to higher performance and trust (Dzindolet et al., 2003; Mercado et al., 2016). Specifically, in the context of automated vehicles, studies have showed that informing the drivers of the reasons for the action of automated vehicles decreased drivers’ anxiety, increased their sense of control, preference and acceptance (Koo et al., 2014, 2016; Forster et al., 2017).However, the studies mentioned above largely focused on conveying simple likelihood information or used hand-drafted explanations, with only few exceptions (e.g.(Mercado et al., 2016)). Further research is needed to examine potential design structures of transparency autonomy.In the present study, we wish to propose an option-centric explanation approach, inspired by the research on design rationale. Design rationale is an area of design science focusing on the “representation for explicitly documenting the reasoning and argumentation that make sense of a specific artifact (MacLean et al., 1991)”. The theoretical underpinning for design rationale is that for designers what is important is not just the specific artifact itself but its other possibilities – why an artifact is designed in a particular way compared to how it might otherwise be. We aim to evaluate the effectiveness of the option-centric explanation approach on trust, dependence and team performance.We conducted a human-in-the-loop experiment with 34 participants (Age: Mean = 23.7 years, SD = 2.88 years). We developed a simulated game Treasure Hunter, where participants and an intelligent assistant worked together to uncover a map for treasures. The intelligent assistant’s ability, intent and decision-making rationale was conveyed in the option-centric rationale display. The experiment used a between-subject design with an independent variable – whether the option-centric rationale explanation was provided. The participants were randomly assigned to either of the two explanation conditions. Participants’ trust to the intelligent assistant, confidence of accomplishing the experiment without the intelligent assistant, and workload for the whole session were collected, as well as their scores for each map.The results showed that by conveying the intelligent assistant’s ability, intent and decision-making rationale in the option-centric rationale display, participants had higher task performance. With the display of all the options, participants had a better understanding and overview of the system. Therefore, they could utilize the intelligent assistant more appropriately and earned a higher score. It is notable that every participant only played 10 maps during the whole session. The advantages of option-centric rationale display might be more apparent if more rounds are played in the experiment session. Although not significant at the .05 level, there seems to be a trend suggesting lower levels of workload when the rationale explanation displayed.Our study contributes to the study of human-autonomy teaming by considering the important role of explanation display. It can help human operators build appropriate trust and improve the human-autonomy team performance.

***

**_Effects of Anthropomorphic Phishing Detection Aids, Transparency Information, and Feedback on User Trust, Performance, and Aid Retention_**  
Mishler, Scott; Jeffcoat, Cody; Chen, Jing  
https://doi.org/10.1177/1071181319631351  

##### Phishing email attacks are a prevalent threat to internet users. Users often ignore or otherwise disregard automated aids, even when the aids’ reliability is high. The current study sought to fill a gap in the literature by examining the effects of anthropomorphism, feedback, and transparency information on user trust and performance within the domain of phishing email detection. Based upon previous studies in anthropomorphic automated systems, this study incorporated three levels of anthropomorphism (AI, human, text), two levels of aid gender (male, female), transparency information (present, absent), and feedback (present, absent). The 465 participants were recruited online through Amazon Mechanical Turk (MTurk) and performed the study on Qualtrics. Phishing was explained and instructions told the participants to judge whether the following emails are legitimate or phishing in three separate blocks of five emails. The first block was without any automated aid as a baseline of participants’ performance. The second block showed participants their respective aid and had them complete five more emails with the aid. The final block allowed participants to choose if they wanted to keep the aid or classify the emails alone. Afterwards, participants were asked how much they trusted the aid to help detect phishing threats using a trust in automation scale based on Jian, Bisantz, and Drury's (2000) study. Our results revealed improved performance on the phishing detection task for participants with an aid over participants without an aid. In addition, feedback was shown to be helpful for improving judgement accuracy as well as increase trust. Transparency also improved judgement accuracy for the human aid but was less helpful for the AI aid. This study compliments past research indicating improvements in performance with automated aids (Chen et al., 2018; Röttger, Bali, & Manzey, 2009; Wiegmann, Rich, & Zhang, 2001). Performance in blocks 2 and 3 was better than block 1. A significant positive correlation between trust and performance reinforces that high trust in a highly reliable aid begets good performance. Subsequently, if participants did not retain the aid for block 3, their performance was worse than those who retained the aid. Designers of automated aid systems should prioritize users interacting with and using the aid so that performance stays high. Feedback also helped improve judgement accuracy. By allowing participants to understand the reliability of the aid, they could learn to trust it more and rely on the suggestions of the aid. Feedback information should be offered to users if possible because it helps improve trust and performance, which is the goal of any automated aid system. Human aids with transparency information helped improve performance compared to human aids without transparency information. But this effect was not found for AI aids and nearly reversed. Transparency was expected to improve trust and performance (Hoff & Bashir, 2015), but it showed no differences in trust and only improved performance for human aids. This new finding demonstrates that there could be differences in the perception of human and AI aids, although further experiments would need to be conducted to further examine these findings.

***

**_Generational differences in trust in digital assistants_**  
Noah, Benjamin; Sethumadhavan, Arathi  
https://doi.org/10.1177/1071181319631029  

##### Human trust in automation has been studied extensively within safety critical domains (military, aviation, process control, etc.) because harmful consequences are associated with the improper calibration of trust in automated systems in these domains (Parasuraman & Riley, 1997). As such, researchers have worked to identify important factors which help humans build trust in such systems (Hoff & Bashir, 2015). With the explosion of AI in consumer technologies, it is becoming equally critical to understand how humans interact with everyday devices. This study investigated how factors that have been identified to impact trust in automation in safety critical domains influence the trust and use of popular digital assistants (Siri, Cortana, Bixby or Google Now). We conducted an online survey with 278 regular users of digital assistants across three generations (GenX, GenY, and GenZ). The results demonstrate that, even after controlling for dispositional factors (i.e., individual characteristics such as age, culture, gender), GenZ exhibited higher trust in digital assistants than GenX. More interestingly, linear regression analyses revealed a different set of predictors of trust for each generation. Results from this survey have implications for the design of digital assistants.

***

**_Attribution Biases and Trust Development in Physical Human-Machine Coordination: Blaming Yourself, Your Partner or an Unexpected Event_**  
Hsiung, Chi-Ping; Chiou, Erin  
https://doi.org/10.1177/1071181319631039  

##### Reading partners’ actions correctly is essential for successful coordination, but interpretation does not always reflect reality. Attribution biases, such as self-serving and correspondence biases, lead people to misinterpret their partners’ actions and falsely assign blame after a surprise, or unexpected event. These biases further influence people’s trust in their partners, including machine partners (Muir, 1987; Madhavan & Wiegmann, 2004). Advances in robotics have allowed for robots to partner with people at work and be treated socially (Young, Hawkins, Sharlin & Igarashi, 2009). However, these advances may interfere with a person’s appropriate calibration of trust in robots (Parasuraman & Miller, 2004). A better understanding of attribution biases in the wake of an unexpected event may shed light on how trust develops in a robot partner. This study was built on a human coordination example to serve as a reference for future human-robot interactions. We posit that attribution biases lead people to blame their partner after experiencing a negative performance outcome, thus lowering their trust in the partner.Sixty participants (30 pairs) were tasked to coordinate with an unfamiliar human partner, to lift a 17.5 lb. box containing a 200ml cup of water filled to the brim, from the floor to a table, as quickly as possible without spilling water. Before the task, participants were told that the pair with the best performance would be rewarded; however, all pairs were told they did not achieve this. Participant pairs were randomly assigned to a surprise condition during which they heard a 250 Hz warning tone, or a baseline condition with no warning tone. Participants in both conditions were told to pause the task as quickly as possible if the warning tone was present. It was unknown to participants when or if a warning tone would occur. To assess participants’ trust in their partner, Muir’s (1987) trust questionnaire was administered twice, once after introducing the task to participants, and again after the coordination task was completed. To capture blame assignment, a scale based on Kim and Hinds (2006) was administered after participants were told they did not achieve the best performance.Results indicate participants were less likely to blame their partners for the negative outcome, compared to blaming themselves or the warning tone itself (in the surprise condition). Next, surprisingly, in the surprise condition, instead of experiencing a decrease of trust in a partner after the negative outcome, there was a significant increase in trust in their partners. No significant difference in trust was found in the baseline condition. Finally, results also indicate that initial trust in a partner is a significant predictor for how people assign blame. In general, the effects of attribution biases were not observed in the present study. Friendliness may be a factor in people’s assignment of blame; although participants were unfamiliar with one another, all participants were students at the same university. Second, shared experience during the surprise condition, including the chance to assess their partner’s behaviors in response to the warning tone, may have been a catalyst for increased trust in a partner. It is important to note that although physical differences between participants were not evaluated in this study, height may be a potential confounding factor in this task. These findings enlighten our understanding of physical human-robot coordination scenarios and trust in a partner.

***

**_Subjective Measurement of Trust: Is It on the Level?_**  
Wei, Jiajun; Bolton, Matthew L.; Humphrey, Laura  
https://doi.org/10.1177/1071181319631062  

##### Psychometrics are increasingly being used to evaluate trust in the automation of safety-critical systems. There is no consensus on what the highest level of measurement is for psychometric trust. This is important as the level of measurement determines what mathematics and statistics can be meaningfully applied to ratings. In this work, we introduce a new method for determining what the maximum level of measurement is for psychometric ratings. We use this to assess the level of measurement of trust in automation using human ratings about the behavior of unmanned aerial systems performing search tasks. Results show that trust is best represented at an ordinal level and that it can be treated as interval in most situations. It is unlikely that trust in automation ratings are ratio. We discuss these results, their implications, and future research.

***

**_Positive bias in the ‘Trust in Automated Systems Survey’? An examination of the Jian et al. (2000) scale_**  
Gutzwiller, Robert S.; Chiou, Erin K.; Craig, Scotty D.; Lewis, Christina M.; Lematta, Glenn J.; Hsiung, Chi-Ping  
https://doi.org/10.1177/1071181319631201  

##### Measuring trust in technology is a mainstay in Human Factors research. While trust may not perfectly predict reliance on technology or compliance with alarm signals, it is routinely used as a design consideration and assessment goalpost. Several methods of measuring trust have been employed in the past decades, but one self-report measure stands out due to its popular use, the Trust in Automated Systems Survey (Jian, Bisantz, & Drury, 2000). We conducted a study to assess whether the survey could create biased responses, and found evidence the original scale is in fact skewed toward positive ratings. Assessing the literature revealed the survey has been used in unaltered form across at least 100 different reports and remains frequently administered – therefore, the potential impact of this bias may be widespread. Future directions, considerations, and caveats for our assessment, and for using this scale, are discussed.

***

**_The Consequences of Purposefulness And Human-Likeness on Trust Repair Attempts Made by Self-Driving Vehicles_**  
Kohn, Spencer C.; Momen, Ali; Wiese, Eva; Lee, Yi-Ching; Shaw, Tyler H.  
https://doi.org/10.1177/1071181319631381  

##### Autonomous systems are rapidly gaining the capacity to recognize their own errors and utilize social strategies to mitigate the trust deficit that accompanies those errors. While previous research has catalogued the effects of trust repair attempts in human-human relationships, much remains unknown about the consequences of similar strategies when administered by autonomous systems such as self-driving vehicles. While we tend to treat computers like social actors, autonomous systems may have a wider spectrum of perceived human-likeness and may be subject to different interpretations of the purposefulness of their errors. This paper seeks to understand the consequences of these factors on the effectiveness of trust repair attempts administered by self-driving cars, and the results highlight the importance of considering human-likeness and purposefulness in the design of autonomous systems.

***

**_Risk Surface: A Visualization of Data Sharing Risk for Enterprise Users_**  
St. John, Mark F.; Gustafson, Woodrow; Martin, April; Moore, Ronald A.; Korkos, Christopher A.  
https://doi.org/10.1177/1071181319631011  

##### Enterprises share a wide variety of data with different partners. Tracking the risks and benefits of this data sharing is important for avoiding unwarranted risks of data exploitation. Data sharing risk can be characterized as a combination of trust in data sharing partners to not exploit shared data and the sensitivity, or potential for harm, of the data. Data sharing benefits can be characterized as the value likely to accrue to the enterprise from sharing the data by making the enterprise’s objectives more likely to succeed. We developed a risk visualization concept called a risk surface to support users monitoring for high risks and poor risk-benefit trade-offs. The risk surface design was evaluated in a series of two focus groups conducted with human factors professionals. Across the two studies, the design was improved and ultimately rated as highly useful. A risk surface needs to 1) convey which data, as joined data sets, are shared with which partners, 2) convey the degree of risk due to sharing that data, 3) convey the benefits of the data sharing and the trade-off between risk and benefits, and 4) be easy to scan at scale, since enterprises are likely to share many different types of data with many different partners.

***

**_Feedback on system or operator performance: Which is more useful for the timely detection of changes in reliability, trust calibration and appropriate automation usage?_**  
Lu, Yidu; Sarter, Nadine  
https://doi.org/10.1177/1071181319631345  

##### Creating safe human-machine systems requires that operators can quickly notice changes in system reliability in the interest of trust calibration and proper automation usage. Operators’ readiness to trust a system is determined not only by the performance of the automation but also by their confidence in their own abilities. This study therefore compared the usefulness of feedback on the performance of either agent. The experiment required two groups of ten participants each to perform an automation-assisted target identification task with “Automation Performance Feedback” (APF) or “Operator Performance Feedback” (OPF). Four different scenarios differed with respect to the degree and duration of changes in system reliability. Findings indicate that APF was more effective for supporting timely adjustments of perceived system reliability, especially with large and long reliability changes. Subjective trust ratings and performance were not affected, however, suggesting that these two factors are closely linked and more relevant for automation reliance.

***

**_Trust Engineering for Human-AI Teams_**  
Ezer, Neta; Bruni, Sylvain; Cai, Yang; Hepenstal, Sam J.; Miller, Christopher A.; Schmorrow, Dylan D.  
https://doi.org/10.1177/1071181319631264  

##### Human-AI teaming refers to systems in which humans and artificial intelligence (AI) agents collaborate to provide significant mission performance improvements over that which humans or AI can achieve alone. The goal is faster and more accurate decision-making by integrating the rapid data ingest, learning, and analyses capabilities of AI with the creative problem solving and abstraction capabilities of humans. The purpose of this panel is to discuss research directions in Trust Engineering for building appropriate bi-directional trust between humans and AI. Discussions focus on the challenges in systems that are increasingly complex and work within imperfect information environments. Panelists provide their perspectives on addressing these challenges through concepts such as dynamic relationship management, adaptive systems, co-discovery learning, and algorithmic transparency. Mission scenarios in command and control (C2), piloting, cybersecurity, and criminal intelligence analysis demonstrate the importance of bi-directional trust in human-AI teams.

***

**_Practical Guidance for Evaluating Calibrated Trust_**  
McDermott, Patricia L.; Brink, Ronna N. ten  
https://doi.org/10.1177/1071181319631379  

##### As automation, autonomy, and AI become more prevalent, human factors engineers are called to evaluate whether users trust that automation. We argue that the true question is whether users trust the automation appropriately. In other words, do they trust it as much as it deserves to be trusted? When automation performance decreases, are users aware so they decrease their momentary trust, and more importantly, their reliance on the automation? There are few metrics that focus specifically on calibrated trust, and the trust literature can be daunting for human factors professionals who are not experts in trust. We offer two aids to human factors practitioners tasked with evaluating trust. The first is an easy-to-use calibrated trust framework that simplifies the aspects of trust into Belief, Understanding, Intent, and Reliance. The second is the introduction of Calibration Points, a way to classify situations in which the automation excels or situations in which the automation is degraded. By identifying these Calibration Points, human factors practitioners can evaluate whether human trust is aligned with automation performance. This approach allows the practitioner to leverage the rich set of evaluation techniques that have been developed to evaluate trust.

***

**_The National Academies Board on Human System Integration (BOHSI) Panel: Explainable AI, System Transparency, and Human Machine Teaming_**  
Warden, Toby; Carayon, Pascale; Roth, Emilie M.; Chen, Jessie; Clancey, William J.; Hoffman, Robert; Steinberg, Marc L.  
https://doi.org/10.1177/1071181319631100  

##### The National Academies Board on Human Systems Integration (BOHSI) has organized this session exploring the state of the art and research and design frontiers for intelligent systems that support effective human machine teaming. An important element in the success of human machine teaming is the ability of the person on the scene to develop appropriate trust in the automated software (including recognizing when it should not be trusted). Research is being conducted in the Human Factors community and the Artificial Intelligence (AI) community on the characteristics that software need to display in order to foster appropriate trust. For example, there is a DARPA program on Explainable AI (XAI). The Panel brings together prominent researchers from both the Human Factors and AI communities to discuss the current state of the art, challenges and short-falls and ways forward in developing systems that engender appropriate trust.

***

**_A System Dynamics Model for Human Trust in Automation under Speed and Accuracy Requirements_**  
Hussein, Aya; Elsawah, Sondoss; Abbass, Hussein  
https://doi.org/10.1177/1071181319631167  

##### Research shows that human trust in automation is a key predictor of human reliance on the automation. Several models have been proposed to capture the interplay between trust and reliance and their combined impacts on task performance. Whereas some models assume that trust is affected by automation reliability, others assume that trust is affected by automation speed. In fact, both speed and reliability can be crucial for mission performance, therefore, these models do not represent the interrelationships among automation speed, automation reliability, human decision making, and subsequent effects on mission performance. To address this gap, we propose a system dynamics model which incorporates both the speed and reliability of automation and their combined effects on trust. Our model explicitly represents the speed-accuracy compromise adopted by the subjects to weigh the perceived relative importance of these aspects while evaluating the reliance decision. The model is calibrated and evaluated using data collected from a human experiment in which 33 subjects interacted with an automated aid for swarm supervision in a foraging mission. The simulation results show that the model can closely replicate and predict the experimental data in terms of the reliance rate and the number of targets collected. Model limitations and further efforts for model extension are discussed.

***

**_A Capacity Coefficient Method for Characterizing the Impacts of Automation Transparency on Workload Efficiency_**  
Fallon, Corey K.; Blaha, Leslie M.; Jefferson, Brett; Franklin, Lyndsey  
https://doi.org/10.1177/1071181319631436  

##### Automation can be unreliable. This makes appropriate trust and reliance difficult to calibrate. One solution to building appropriate trust is to increase automation transparency by displaying information to the operator about the technology’s underlying analytical principles. However, displaying this additional information may increase operator workload. The research and development community must balance the competing demands of providing adequate transparency and keeping operator workload low. To investigate the complex effects of transparency on workload, a modeling approach can be used by computing a measure of processing efficiency called the capacity coefficient. We conducted a study to examine the impact of increasing transparency on operator workload using the capacity coefficient. We present the data from one participant with the goal of demonstrating the utility of the capacity coefficient. We discuss how this participant’s data highlights the inferences possible from capacity analysis for measuring the impact of display design and increased transparency on operator workload.

***

**_Public’s acceptance of automated vehicles: the role of initial trust and subjective norm_**  
Zhang, Tingru; Tan, Haibo; Li, Shuling; Zhu, Haoyu; Tao, Da  
https://doi.org/10.1177/1071181319631183  

##### This study aimed to investigate factors that determine public’s acceptance of automated vehicles (AVs) by proposing and empirically testing an AV acceptance model. The model was developed by incorporating two factors, i.e., trust and subjective norm, into the Technology Acceptance Model. The validity of the model was confirmed with a structure equation modeling analysis based on data collected from 395 survey samples. It was found that trust was the most critical determinant of public’s acceptance of AVs and offered a way for other factors (i.e. perceived usefulness and social norm) to impact AV acceptance. Subjective norm was also identified as an important factor in shaping users’ usage intention, at lease in China, a country dominated by collectivistic culture. Findings from this study provide some guidelines in improving AV products to attract users.

***

**_The psychological factors that influence successful technology adoption in the oil and gas industry_**  
Roberts, Ruby; Flin, Rhona  
https://doi.org/10.1177/1071181319631105  

##### To ensure that the full potential of innovative technology is maximised, it is crucial to understand the psychological factors that influence technology adoption in all industrial consumers. The oil and gas (O&G) industry exemplifies industrial consumers’ reluctance to adopt new technology. Our critical incident interviews identified the key psychological factors that influence technology adoption in the O&G industry. These were personality (innovativeness and risk aversion), attitudes (trust, motivations, “not invented here” syndrome and “engineering mindset”), social (subjective norms and self-image), cognitive (risk perception, uncertainty and familiarity, expertise, and previous experiences) and organizational level factors (leadership, management, organisational culture, adoption culture, and rewards system). In combination with future case studies, these results can be used to develop interventions that support the successful introduction and acceptance of new technology not only in O&G but in other high-risk sectors.

***

**_Human-Robot Interaction with Drones and Drone Swarms in Law Enforcement Clearing Operations_**  
Stone, Richard T.; Schnieders, Thomas M.; Push, Kevin A.; Terry, Stephen; Truong, Mary; Seshie, Inshira; Socha, Kathryn  
https://doi.org/10.1177/1071181319631465  

##### Police officers often must work alone in clearing operations, a procedure that involves surveying a building for threats and appropriately responding. A partnership between drone swarms and officers has potential to increase the safety of officers and civilians during these high-stress operations and reduce the risk of harm from hostile persons. This two part study examines aspects of trust, situational awareness, mental demand, performance, and human-robot interaction during law enforcement building clearing operations using either a single drone or a drone swarm. Results indicate that single drone use can increase time for operation, but accuracy and safety of clearing is enhanced. Single drone use saw increased situational awareness, a decrease in number of targets missed, and a moderate level of trust. For drone swarms, results indicate significant differences in mental workload from swarm data feeds compared to single drone feeds but no substantial difference in accuracy of finding targets.

***

**_Light-Based External Human Machine Interface: Color Evaluation for Self-Driving Vehicle and Pedestrian Interaction_**  
Faas, Stefanie M.; Baumann, Martin  
https://doi.org/10.1177/1071181319631049  

##### In today’s road traffic pedestrians seek eye contact with drivers to move along safely. Such communication is no longer possible with self-driving vehicles. Previous research shows that an external Human-Machine-Interface (eHMI) provides an interface between self-driving vehicles and pedestrians. However, recommendations for standardization are still being developed. The study compares the colors white and turquoise for eHMI lamps indicating that the automated driving system is engaged. The colors are evaluated in a street-crossing scenario and a parking lot scenario with a Wizard-of-Oz vehicle equipped with eHMI lamps mounted on top of the vehicle. We conducted questionnaires and structured interviews with N=59 participants to identify eHMI design guidelines. Our research provides evidence that turquoise facilitates pedestrians’ factors like visibility, discriminability, sense of safety and trust higher than white. The results are consistent among traffic scenarios. This paper contributes in formulating research-based design guidelines to improve pedestrian safety.

***

**_Safety Climate in Military Organizations: A Pilot Study of an Adjusted Multi-Domain Instrument_**  
Schüler, M.; Matuszczyk, J. Vega  
https://doi.org/10.1177/1071181319631253  

##### The aim of this pilot study is to adjust the NOSACQ-50 to the work environment of military organizations. NOSACQ-50 is a validated tool successfully used in several organizational domains to measure occupational safety climate (OSC). In general, few studies have been published investigating OSC in military organizations. NOSACQ-50 consists of 50 items across 7 OSC dimensions, i.e. group members’ shared perceptions of: 1) management safety priority, commitment and competence; 2) management safety empowerment; 3) management safety justice; 4) workers’ safety commitment; 5) workers’ safety priority and risk non-acceptance; 6) safety communication, learning, and trust in co-workers’ safety competence; 7) workers’ trust in the efficacy of safety systems. To assess the relevance of the NOSACQ-50 items, a revised version of the instrument was sent to 11 military safety experts. In addition, 19 items pertaining to areas not covered by NOSACQ-50 were validated by the same experts. After contents validation, data from 517 participants from 4 garrisons were collected. The results showed that NOSACQ-50 had acceptable reliability scores (.70-.89.), and the factor structure was confirmed by confirmatory factor analysis (CFA). Principal component analyses (PCA) of the supplementary 19 items showed that 12 items grouped into three dimensions (alpha .74-.91): Management enabling safety performance, personnel’s knowledge of and competence in national laws regulating safety and Unit ethics. In conclusion, preliminary results showed the adjusted NOSACQ-50 instrument could be used to measure OSC in military organizations. However, additional studies must be performed to improve and develop military specific dimensions not covered by NOSACQ-50.

***

**_The Joint Effect of Scientific Knowledge and Photographic Evidence on Expert Witness Credibility_**  
  
https://doi.org/10.1177/1071181319631418  

##### The present study examines the role of scientific and photographic evidence on mock jurors’ perceptions of witness credibility and whether adding such details to an expert witness’s slideshow increases the credibility of that testimony. To assess credibility, 128 undergraduate students were divided across 4 research groups. The students reviewed narrated slideshows of Human Factors expert witness testimony and used the Witness Credibility Scale (Brodsky et al., 2010) to quantify the credibility of that testimony. We hypothesized that adding scientific data and photographs would lead to an increase in perceived credibility. Final results indicate that scientific data did generate a statistically significant increase in perceived credibility, specifically concerning the knowledge and trustworthiness of the witness. Conversely, the inclusion of images did not produce a statistically significant effect on perceived credibility. The results of this study demonstrate that including specialized scientific information in an expert witness’s testimony affects jurors’ overall perception of credibility of the witness.

***

**_Trust Measurement in Human–Automation Interaction: A Systematic Review_**  
Brzowski, Matthew; Nathan-Roberts, Dan  
https://doi.org/10.1177/1071181319631462  

##### This systematic review summarizes current measurements of trust in human-automation interaction. A total of 217 articles were found, and it was determined that 44 articles contained relevant information and met inclusion criteria. The results of the review showed that 75% (n = 33) of articles used subjective measures of trust only, and 41% (n = 18) used researcher-defined methods of measuring trust instead of peer-reviewed and validated scales. Of 10 defined industries, the highest number of articles (n = 14) were assigned to the automotive industry, followed by aviation, military, and security (n = 6). The automated systems studied in relevant articles were decision aids, automated control and navigation systems, and process control systems. This review showed that research of trust in human-automation interaction (1) has the tendency to use subjective measures of trust as the primary or only measure, (2) has the tendency to individually define trust and how it is measured, and (3) is heavily composed of research on automotive automation. Best practices and future research are discussed.

***

**_Trend Analysis of Cyber Security Research Published in HFES Proceedings from 1980 to 2018_**  
Mouloua, Salim A.; Ferraro, James; Mouloua, Mustapha; Matthews, Gerald; Copeland, Robert R.  
https://doi.org/10.1177/1071181319631467  

##### The prevalence of information technology (IT) and widespread use of electronic data storage systems by individuals, corporations, and government branches has prompted investigation into threats to cyber security and data privacy. Within the human factors community, researchers have sought to identify issues related to cyber-attacks and cyber defense and human-centered design. These issues range from placing too much trust in modern technology, to remaining vigilant in the presence of cyber threats such as phishing emails. This study aimed to evaluate trends in cyber security research published in the Proceedings of the Human Factors and Ergonomics Society Annual Meeting from 1980 to 2018. This paper reviewed 114 unique articles, identified using keyword terms related to cyber security. Results were organized, analyzed, and graphed based on topic areas, author and funding agency affiliations, and applicable domains. Analyses indicated that cyber security research has grown exponentially in recent years, with nearly 73% of relevant proceedings papers produced since 2010. Gaps in the literature, directions for future research, and emerging issues related to training are also discussed.

***

**_Smart Home Devices: Promoting User Trust and Protecting User Data_**  
Goh, Lih Seng; Nathan-Roberts, Dan  
https://doi.org/10.1177/1071181319631525  

##### As smart technology is introduced into our homes, new dangers emerge that threaten our safety. New technology is usually subjected to much scrutiny, but smart home devices face even more because they are brought into the home environment, which is focused on safety and privacy. The potential for smart home technology to improve home life is hindered by the fact that potential users face difficulty in trusting and accepting smart home technology. This paper explores different types of trust that can be used to inform strategies, promote trust, reduce threats towards smart home technologies, and overcome challenges in designing these systems and different methods for designing a trustworthy and secure system. To begin designing a trustworthy product that establishes trust between users and smart home technology, manufacturers should use these findings to understand how human beings form trust with new technology.

***

**_Does Team Interaction Exploration Support Resilience in Human Autonomy Teaming?_**  
Lematta, Glenn J.; Johnson, Craig J.; Chiou, Erin K.; Cooke, Nancy J.  
https://doi.org/10.1177/1071181319631492  

##### Project overviewAs a team explores interactions, they may find opportunities to expand and refine teamwork over time. This can have consequences for team effectiveness in normal and unexpected situations (Woods, 2018). Understanding the role of exploratory team interactions may be relevant for human-autonomy team (HAT) resilience in the face of synthetic agent rigidity and lack of anticipation (Demir et al, 2019). Team interaction exploration was defined as team interactions with qualities (e.g. content, communication medium) unique to a team’s interaction history (Cooke et al., 2013; Hills et al., 2015). This study examines the relationship between team interaction exploration and HAT performance in multiple remotely-piloted aerial system (RPAS) reconnaissance missions with degraded conditions. The goal of the task was to take good photos of target waypoints. In this task, three teammates are assigned to specific roles: the navigator plans the route using a digital map, the pilot (synthetic) controls the RPAS and selects target waypoints, and the photographer calibrates camera settings to take a good photo of a target waypoint. The synthetic agent was capable of routine team coordination without explicit team player qualities. Teams communicated via a text-chat interface. Seven unique degraded conditions were injected throughout ten missions. Three automation failures disrupted RPAS status information on the photographer’s or pilot’s display, and three autonomy failures disrupted the synthetic agent’s comprehension of waypoint information or caused the agent to move on to the next target before a photo was taken. Finally, a malicious cyber-attack caused the synthetic agent to fly the RPAS to an enemy occupied waypoint.MethodForty-four participants were recruited from a large southwestern university in pairs and formed teams (22 teams) to participate in this study. These participants were either undergraduate or graduate students. This experiment consisted of ten 40-minute missions in total that were carried out over two sessions separated by one-to two-week intervals. After a baseline mission, an automation and autonomy failure was injected into each mission while the team processed target waypoints. The malicious cyber-attack occurred during the final 20-minutes of the tenth mission. This study collected a several measures including measures of team process, physiological measures, and surveys of teamwork knowledge, trust, workload, and anthropomorphism which are not considered in this study. Exploratory team interaction was operationalized as any text-message unique in content, sender, or recipient that was unrelated to routine coordination of target waypoints. Teams were grouped using k-means clustering by their target processing efficiency, number of overcome roadblocks, and mission performance. The three clusters (K = 3) were comparatively described as low- (N = 7), middle- (N = 7), and high-performing (N = 5) teams. A mixed-factor ANOVA compared the frequency of each team’s exploratory interactions by mission and cluster.Results and discussionHigh-performing teams were distinguished from middle-and low-performing teams in their ability to maintain high levels of overall performance while efficiently processing targets and overcoming many roadblocks. Middle-performing teams were efficient in overcoming roadblocks but had worse mission performance. The findings indicate that 1) high-performing teams explored team interactions more than middle-performing teams, 2) there was no significant difference in exploration frequency between high-and low-performing teams, and 3) teams explored more in the first session than the second session, with the exception of the final mission. Overall, exploratory team interaction differentiated HAT performance in normal and degraded conditions and should be further examined at other levels of interaction, such as content meaning and interaction patterns.

***

**_Understanding Reliance and Trust in Decision Aids for UAV Target Identification_**  
Rogers, Hunter; Khasawneh, Amro; Bertrand, Jeffrey; Chalil, Kapil  
https://doi.org/10.1177/1071181319631172  

##### The use of automation is prevalent in almost every aspect of modern life, and since its inception researchers have been investigating trust in automation. There are many methods of measuring trust. Given that trust means different things to different people and by nature is subjective, most methods are subjective survey assessments (Freedy, DeVisser, Weltman, & Coeyman, 2007; Jian, Bisantz, & Drury, 2000). Many studies have investigated how the reliability of an automated agent or the level of automation changes subjective trust in the automation (Dixon & Wickens, 2006; Du, Zhang, & Yang, 2018; Khasawneh, Rogers, Bertrand, Madathil, & Gramopadhye, 2019; Rogers, Khasawneh, Bertrand, & Madathil, 2017).

***

**_Mind Perception in a Competitive Human-Robot Interaction Game_**  
Currie, Levern Q.; Wiese, Eva  
https://doi.org/10.1177/1071181319631284  

##### Robotic agents are becoming increasingly pervasive in society, and have already begun advancing fields such as healthcare, education, and industry. However, despite their potential to do good for society, many people still feel unease when imaging a future where robots and humans work and live together in shared environments, partly because robots are not generally trusted or ascribed human-like socio-emotional skills such as mentalizing and empathizing. In addition, performing tasks conjointly with robots can be frustrating and ineffective partially due to the fact that neuronal networks involved in action understanding and execution (i.e., the action-perception network; APN) are underactivated in human-robot interaction (HRI). While a number of studies has linked underactivation in APN to reduced abilities to predict a robot’s actions, little is known about how performing a competitive task together with a robot affects one’s own ability to execute or suppress an action. In the current experiment, we use a Go/No-Go task that requires participants to give a response on Go trials and suppress a response on No-Go trials to examine whether the performance of human players is impacted by whether they play the game against a robot believed to be controlled by a human as opposed to being pre-programmed. Preliminary data shows higher false alarm rates on No-Go trials, higher hit rates on Go trials, longer reaction times on Go trials and higher inverse efficiency scores in the human-controlled versus the pre-programmed condition. The results show that mind perception (here: perceiving actions as human-controlled) significantly impacted action execution of human players in a competitive human-robot interaction game.

***

**_Using a Situational Awareness Display to Improve Rider Trust and Comfort with an AV Taxi_**  
Chang, Chun-Cheng; Grier, Rebecca A.; Maynard, Jason; Shutko, John; Blommer, Mike; Swaminathan, Radhakrishnan; Curry, Reates  
https://doi.org/10.1177/1071181319631428  

##### There is evidence that a significant portion of the population does not trust automated vehicles (AV). Research on trust in automation suggests that providing insight into how automation functions via a situational awareness (SA) display improves trust. However, it is unclear how much information is needed to build trust. A study was conducted to evaluate what amount of information improves passenger trust with an AV. After a ride in a simulated AV with one of four SA displays with varying amounts of information or no SA display, participants completed questions about trust and comfort. In addition, participants completed a card sorting task to determine what content they desired to see on the SA display. Our conclusions suggests that an SA display engenders trust and comfort. However, such a display should present a low amount of information. A possible explanation is that high information density displays might be more difficult for participants to interpret.

***

**_Proceedings of the Human Factors and Ergonomics Society 2019 Annual Meeting_**  
  
https://doi.org/10.1177/1071181319631171  

##### This lecture discusses the validation of a new scale, the Trust of Automated Systems Test (TOAST). As we increasingly rely on automated systems to perform tasks, it becomes ever more important to understand the ways in which real operators will use these systems. Trust is a critical determinant of this use. Previous efforts to translate trust, typically an interpersonal human experience, into the domain of artificial cognition and inanimate objects, has met with mixed success. Existing scales tend to anthropomorphize systems and attribute intent to relatively simplistic decision processes. This anthropomorphization has led to operator dissatisfaction with these scales and, consequently, poor data quality. In two studies, I present the validation effort for a scale that avoids anthropomorphizing while still assessing the theoretically-driven underlying dimensions of trust formation. Confirmatory Factor Analyses provide evidence that the TOAST, a nine-item scale measuring operator Understanding of the system and belief in its Efficacy is a valid metric of operator trust of both military and civilian systems.

***

**_Lessons learned from conducting Alzheimer’s disease caregiver mHealth app training and focus group sessions_**  
Brown, Janetta; Kim, Hyung Nam  
https://doi.org/10.1177/1071181319631056  

##### This paper describes the challenges and lessons learned from conducting mobile health application (mHealth app) training and focus group sessions for Alzheimer’s disease caregivers. We review the process behind planning, recruitment, and conducting the training and focus group sessions. Insights presented were gained from preparation for the study, participant discussion, participant user experience with the mHealth apps, and the authors’ observations during both sessions. We found that proper preparation for conducting training and focus group sessions goes far beyond literature reviews and pilot testing. Establishing relationships and preliminary volunteerism with potential support group programs can enrich the experience of the researchers and participants involved in the investigation. The impartation of knowledge is reciprocal, but in this case, mutual trust and respect for the adult learning process were the deciding factors behind the authors’ success.

***

**_The Impact of Virtual Human Voice on Learner Trust_**  
Craig, Scotty D.; Chiou, Erin K.; Schroeder, Noah L.  
https://doi.org/10.1177/1071181319631517  

##### The current study investigates if a virtual human’s voice can impact the user’s trust in interacting with the virtual human in a learning setting. It was hypothesized that trust is a malleable factor impacted by the quality of the virtual human’s voice. A randomized alternative treatments design with a pretest placed participants in either a low-quality Text-to-Speech (TTS) engine female voice (Microsoft speech engine), a high-quality TTS engine female voice (Neospeech voice engine), or a human voice (native female English speaker) condition. All three treatments were paired with the same female virtual human. Assessments for the study included a self-report pretest on knowledge of meteorology, which occurred before viewing the instructional video, and a measure of system trust. The current study found that voice type impacts a user’s trust ratings, with the human voice resulting in higher ratings compared to the two synthetic voices.

***

**_Cross-Cultural Reactions to Peacekeeping Robots Wielding Non-Lethal Weapons_**  
Bliss, James P.; Long, Shelby K.; Karpinsky-Mosley, Nicole  
https://doi.org/10.1177/1071181319631189  

##### Robots may represent a safer alternative to using only human peacekeepers. However, it is unclear how civilian populations will react to such robots given the cultural diversity of affected civilians and the possibility of non-lethal or lethal weapon use by robot peacekeepers. We investigated compliance rates to simulated armed peacekeeping robots by native and expatriate Americans, Chinese, and Japanese. We predicted that compliance to robot demands would vary as a function of lethal weapon availability, robot patrol orders, and cultural background of the participants. One hundred and forty participants representing seven cultural groups performed a virtual shopping task. They were randomly interrupted six times by an anthropomorphic robotic peacekeeper requesting personal items. Participants decided to “comply” or “not comply” with the robot after each interaction and indicated their trust of the robot. Results showed that participants were more likely to comply with robotic peacekeepers wielding backup lethal weapons than those armed with only a non-lethal weapon. Chinese participants residing in America complied most; Americans living in China complied least. Older participants and those with greater nonlethal weapon familiarity showed more positive attitudes towards weapons. These results suggest that lethality, culture, and familiarity may influence interactions with armed robotic peacekeepers.

***

## [HFES2018](HFES2018.md) 62nd International Annual Meeting of the Human Factors and Ergonomics Society
Link: [[Proceedings](https://journals.sagepub.com/toc/proe/62/1)]
[[Conference](https://www.hfes.org/events/2018-hfes-international-annual-meeting)]
Awardなし  
***
**_Public Safety Communication User Needs: Voices of First Responders_**  
Dawkins, Shaneé; Greene, Kristen; Steves, Michelle; Theofanos, Mary; Choong, Yee-Yin; Furman, Susanne; Prettyman, Sandra Spickard  
https://doi.org/10.1177/1541931218621021  

##### The public safety community is transitioning from land mobile radios to a communications technology ecosystem including a variety of broadband data sharing platforms. Successful deployment and adoption of new communications technology relies on efficient and effective user interfaces based on understanding first responder needs, requirements, and contexts of use; human factors research is needed to examine these factors. As such, this paper presents initial qualitative research results via semi-structured interviews with 133 first responders across the U.S. While there are similarities across disciplines, results show there is no easy “one size fits all” communications technology solution. To facilitate trust in new communications technology, solutions must be dependable, easy to use for first responders, and meet their communication needs through the application of user-centered design principles. During this shift in public safety communications technology, the time is now to leverage existing human factors expertise to influence emerging technology for public safety.

***

**_Trust dynamics in sequential decision making_**  
Kim, Changhoon; Zhang, Mengyuan; Zhang2, Chongjie; Yang, X. Jessie  
https://doi.org/10.1177/1541931218621038  

##### 

***

**_Conveying Automation Reliability and Automation Error Type An Empirical Study in the Cyber Domain_**  
Chen, Jing; Mishler, Scott; Hu, Bin  
https://doi.org/10.1177/1541931218621040  

##### BackgroundEmails have become an integral part of our daily life and work. Phishing emails are often disguised as trustworthy ones and attempt to obtain sensitive information for malicious reasons (Egelman, Cranor, Hong, 2008;). Anti-phishing tools have been designed to help users detect phishing emails or websites (Egelman, et al., 2008; Yang, Xiong, Chen, Proctor, & Li, 2017). However, like any other types of automation aids, these tools are not perfect. An anti-phishing system can make errors, such as labeling a legitimate email as phishing (i.e., a false alarm) or assuming a phishing email as legitimate (i.e., a miss).Human trust in automation has been widely studied as it affects how the human operator interacts with the automation system, which consequently influences the overall system performance (Dzindolet, Peterson, Pomranky, Pierce, & Beck, 2003; Lee & Moray, 1992; Muir, 1994; Sheridan & Parasuraman, 2006). With interacting with an automation system, the human operator should calibrate his or her trust level to trust a system that is capable but distrust a system that is incapable (i.e., trust calibration; Lee & Moray, 1994; Lee & See, 2004; McGuirl & Sarter, 2006).Among the various system capabilities, automation reliability is one of the most important factors that affect trust, and it is widely accepted that higher reliability levels lead to higher trust levels (Desai et al., 2013; Hoff & Bashir, 2015). How well these capabilities are conveyed to the operator is essential (Lee & See, 2004). There are two general ways of conveying the system capabilities: through an explicit description of the capabilities (i.e., description), or through experiencing the system (i.e., experience). These two ways of conveying information have been studied widely in human decision-making literature (Wulff, Mergenthaler-Canseco, & Hertwig, 2018). Yet, there has not been systematic investigation on these different methods of conveying information in the applied area of human-automation interaction (but see Chen, Mishler, Hu, Li, & Proctor, in press; Mishler et al., 2017).Furthermore, trust and reliance on automation is not only affected by the reliability of the automation, but also by the error types, false alarms and misses (Chancey, Bliss, Yamani, & Handley, 2017; Dixon & Wickens, 2006). False alarms and misses affect human performance in qualitatively different ways, with more serious damage being caused by false-alarmprone automation than by miss-prone automation (Dixon, Wickens, & Chang, 2004). In addition, false-alarm-prone automation reduces compliance (i.e., the operator’s reaction when the automation presents a warning); and miss-prone automation reduces reliance (i.e., the operator’s inaction when the automation remains silent; Chancey et al., 2017).Current StudyThe goal of the current study was to examine how the methods of conveying system reliability and automation error type affect human decision making and trust in automation. The automation system was a phishing-detection system, which provided recommendations to users as to whether an email was legitimate or phishing. The automation reliability was defined as the percentage of correct recommendations (60% vs. 90%). For each reliability level, there were a false-alarm condition, with all the automation errors being false alarms, and a miss condition, with all the errors being misses. The system reliability was conveyed through description (with an exact percentage described to the user) or experience (with immediate feedback to help the user learn; Barron, & Erev, 2003).A total of 510 participants were recruited and completed the experiment online through Amazon Mechanical Turk. The experimental task consisted of classifying 20 emails as phishing and legitimate, with a phishing-detection system providing recommendations. At the end of the experiment, participants rated their trust in this automated aid system. The measures included a performance measure (the decision accuracy made by the participants), as well as two trust measures (participants’ agreement rate with the phishing-detection system, and their self-reported trust in the system).Our results showed that higher system reliability and feedback increased accuracy significantly, but description or error type alone did not affect accuracy. In terms of the trust measures, false alarms led to lower agreement rates than did misses. With a less reliable system, though, the misses caused a problem of inappropriately higher agreement rates; this problem was reduced when feedback was provided for the unreliable system, indicating a trust-calibration role of feedback. Self-reported trust showed similar result patterns to agreement rates. Performance was improved with higher system reliability, feedback, and explicit description. Design implications of the results included that (1) both feedback and description of the system reliability should be presented in the interface of an automation aid whenever possible, provided that the aid is reliable, and (2) for systems that are unreliable, false alarms are more desirable than misses, if one has to choose between the two.

***

**_Evaluating effects of automation reliability and reliability information on trust, dependence and dual-task performance_**  
Du, Na; Zhang, Qiaoning; Yang, X. Jessie  
https://doi.org/10.1177/1541931218621041  

##### The use of automated decision aids could reduce human exposure to dangers and enable human workers to perform more challenging tasks. However, automation is problematic when people fail to trust and depend on it appropriately.Existing studies have shown that system design that provides users with likelihood information including automation certainty, reliability, and confidence could facilitate trust- reliability calibration, the correspondence between a person’s trust in the automation and the automation’s capabilities (Lee & Moray, 1994), and improve human–automation task performance (Beller et al., 2013; Wang, Jamieson, & Hollands, 2009; McGuirl & Sarter, 2006).While revealing reliability information has been proposed as a design solution, the concrete effects of such information disclosure still vary (Wang et al., 2009; Fletcher et al., 2017; Walliser et al., 2016). Clear guidelines that would allow display designers to choose the most effective reliability information to facilitate human decision performance and trust calibration do not appear to exist. The present study, therefore, aimed to reconcile existing literature by investigating if and how different methods of calculating reliability information affect their effectiveness at different automation reliability.A human subject experiment was conducted with 60 participants. Each participant performed a compensatory tracking task and a threat detection task simultaneously with the help of an imperfect automated threat detector. The experiment adopted a 2×4 mixed design with two independent variables: automation reliability (68% vs. 90%) as a within- subject factor and reliability information as a between-subjects factor. Reliability information of the automated threat detector was calculated using different methods based on the signal detection theory and conditional probability formula of Bayes’ Theorem (H: hits; CR: correct rejections, FA: false alarms; M: misses):Overall reliability = P (H + CR | H + FA + M + CR).Positive predictive value = P (H | H + FA); negative predictive value = P (CR | CR + M).Hit rate = P (H | H + M), correct rejection rate = P (CR | CR + FA).There was also a control condition where participants were not informed of any reliability information but only told the alerts from the automated threat detector may or may not be correct. The dependent variables of interest were participants’ subjective trust in automation and objective measures of their display-switching behaviors.The results of this study showed that as the automated threat detector became more reliable, participants’ trust in anddependence on the threat detector increased significantly, and their detection performance improved. More importantly, there were significant differences in participants’ trust, dependence and dual-task performance when reliability information was calculated by different methods. Specifically, when overall reliability of the automated threat detector was 90%, revealing positive and negative predictive values of the automation significantly helped participants to calibrate their trust in and dependence on the detector, and led to the shortest reaction time for detection task. However, when overall reliability of the automated threat detector was 68%, positive and negative predictive values didn’t lead to significant difference in participants’ compliance on the detector. In addition, our result demonstrated that the disclosure of hit rate and correct rejection rate or overall reliability didn’t seem to aid human-automation team performance and trust-reliability calibration.An implication of the study is that users should be made aware of system reliability, especially of positive/negative predictive values, to engender appropriate trust in and dependence on the automation. This can be applied to the interface design of automated decision aids. Future studies should examine whether the positive and negative predictive values are still the most effective pieces of information for trust calibration when the criterion of the automated threat detector becomes liberal.

***

**_Eye tracking: a promising method for inferring trust in real time_**  
Lu, Yidu; Sarter, Nadine  
https://doi.org/10.1177/1541931218621042  

##### 

***

**_Automation reliability and trust: A Bayesian inference approach_**  
Wang, Chenlan; Zhang, Chongjie; Yang, X. Jessie  
https://doi.org/10.1177/1541931218621048  

##### Research shows that over repeated interactions with automation, human operators are able to learn how reliable the automation is and update their trust in automation. The goal of the present study is to investigate if this learning and inference process approximately follow the principle of Bayesian probabilistic inference. First, we applied Bayesian inference to estimate human operators’ perceived system reliability and found high correlations between the Bayesian estimates and the perceived reliability for the majority of the participants. We then correlated the Bayesian estimates with human operators’ reported trust and found moderate correlations for a large portion of the participants. Our results suggest that human operators’ learning and inference process for automation reliability can be approximated by Bayesian inference.

***

**_Navigating the Advent of Human-Machine Teaming_**  
Christopher Brill, J.; Cummings, M. L.; Evans, A.w.; Hancock, Peter A.; Lyons, Joseph B.; Oden, Kevin  
https://doi.org/10.1177/1541931218621104  

##### The objective of this panel was to discuss issues related to human-machine (or human-agent) teaming (HMT). Panelists were selected to represent diverse interests and backgrounds (i.e., defense, industry, and academia). Chris Brill provided opening remarks to frame the discussion and introduce the panelists. He then raised several questions related to HMT, such as what is HMT, what level of autonomy is required for HMT, and how do we develop trust in autonomous teammates that learn, change, and potentially, individuate. Missy Cummings built on the issue of learning systems, addressing challenges of certifying systems that, as a function of learning, may cease to be known quantities. Bill Evans spoke to the need for transparency in human-agent teaming. Joseph Lyons addressed social factors in HMT. Peter Hancock detailed his concerns about whether forays into HMT are even advisable, particularly as doing so may lead to dehumanization, or worse, volitional demotion of humans from our current status as apex lifeforms on Earth. Lastly, Kevin Oden expanded the discussion of trust in autonomous systems, while also providing thoughts on how to best leverage human capabilities in the context of HMT. The panel then turned to facilitated discussion with panelists and audience members, constituting the majority of the session time. The session concluded with panelists summarizing their thoughts on how HF/E professionals can or should play a role in the advent of HMT.

***

**_Implications of Trust on Patient Generated Health Data_**  
Papautsky, Elizabeth Lerner; Panganiban, April Rose  
https://doi.org/10.1177/1541931218621125  

##### Propelled by a focus on patient-centered care, technology development is moving in a direction of providing the patient formal avenues of contributing health information. Specifically, patient generated health data (PGHD), ranging from biometric to health status interpretation is an emerging topic in health informatics (Hull, 2015). Further, tools are in development to allow for the electronic delivery of PGHD from the patient to the provider in the electronic health record (EHR).At its core, human factors is concerned with representing information in a way that supports safe and efficient decision making. PGHD is a topic area that requires a human factors perspective for multiple reasons including the need to identify user needs and requirements of data capture on the patient side, data use on the provider side, and supporting technology design to support these users effectively. Much research in health informatics and healthcare human factors is concerned with the EHR, as the system has not reached intended design, forcing clinicians to search through a broad and deep information space to make decisions (Sittig, Wright, Ash, & Singh, 2016). As an emerging concept in health informatics, PGHD will serve as an additional informational category within the EHR for providers to consider in medical decision making. Therefore, one construct that needs to be examined is trust.The topic of trust has considerable relevance as reflected by prolific research efforts in domains in which automated technology and artificial intelligence dominate. Understanding and consideration of trust factors has been integral in complex domains where technological systems carry out functions ranging from representing and delivering information, providing decision support, to carrying out complex tasks.Trust is defined by Mayer, David, & Schoorman as a “willingness to be vulnerable to the actions of another party based on the expectation that the other will perform a particular action important to the trustor, irrespective of the ability to monitor or control that other party” (Mayer, David & Schoorman, 1995, pg 5). In healthcare, examination of trust factors has been limited to trust in technology, from both provider and patient perspectives, and trust in the provider from the patient perspective (interpersonal trust) (Montague, 2010; Montague, Winchester, & Kleiner, 2010). Albeit limited, evidence does suggest that trust plays a role in healthcare outcomes. For instance, higher trust in one’s primary care physician can increase proactive health behaviors such as following up with recommended colorectal cancer screenings (Gupta, Brenner, Ratanawangsa, & Inadomi, 2014).However, as of yet, no literature exists examining trust factors associated with the patient from the provider’s perspective either in face-to-face interactions or technology mediated. Therefore, there is a need to examine and consider trust to inform the design and implementation of electronic PGHD systems addressing the needs of both providers and patients in the capture and delivery of relevant content that may be useful and usable to the provider. Leveraging the knowledge from the trust in automation literature (Parasuraman, Sheridan, & Wickens, 2000), we can begin to examine issues of reliance and trust of PGHD.

***

**_Teaming with Technology at the TSA: An Examination of Trust in Automation’s Influence on Human Performance in Operational Environments_**  
Korbelak, Kristopher; Dressel, Jeffrey; Tweedie, Donald; Wilson, Whitney; Erchov, Simone; Hilburn, Brian  
https://doi.org/10.1177/1541931218621150  

##### Automated systems are not only commonplace but a necessity to complete highly specialized tasks in many operational environments. Problems arise, however, when the automation is used injudiciously. Trust is known to influence how workers use and rely on automated systems, especially when the operational environment poses a great amount of complexity for the user. The environment in which most Transportation Security Administration (TSA) workers operate is characterized by complexity that often demands the use of automation to complete required tasks. The TSA aims to better understand the influence of trust in automation on operational performance to better support its mission and workforce. This paper will discuss the methods, findings, and practical implications gleaned from an examination of the role trust plays on human-automation interactions in the operational environment at TSA.

***

**_Trust and Approachability Mediate Social Decision Making in Human-Robot Interaction_**  
Tulk, Stephanie; Wiese, Eva  
https://doi.org/10.1177/1541931218621160  

##### As humanoid robots become more advanced and commonplace, the average user may perceive their robotic companion as human-like entities that can make social decisions, such as the deliberate choice to act fairly or selfishly. It is important for scientists and designers to consider how this will affect our interactions with social robots. The current paper explores how social decision making with humanoid robots changes as the degree of their human-likeness changes. For that purpose, we created a spectrum of human-like agents via morphing that ranged from very robot-like to very human-like in physical appearance (i.e., in increments of 20%) and measured how this change in physical humanness affected decision-making in two economic games: the Ultimatum Game (Experiment 1) and Trust Game (Experiment 2). We expected increases in human-like appearance to lead to higher rates of punishment for unfair offers and higher ratings of trust in both games. While physical humanness did not have an impact on economic decisions in either of the ex-periments, follow-up analyses showed that both subjective ratings of trust and agent approachability medi-ated the effect of agent appearance on decision-making in both experiments. Possible consequences of these findings for human-robot interactions are discussed.

***

**_Have a Heart: Predictability of Trust in an Autonomous Agent Teammate through Team-Level Measures of Heart Rate Synchrony and Arousal_**  
Tolston, Michael T.; Funke, Gregory J.; Alarcon, Gene M.; Miller, Brent; Bowers, Margaret A.; Gruenwald, Christina; Capiola, August  
https://doi.org/10.1177/1541931218621162  

##### Progression toward sophisticated machines with the capacity to act as partners in tactical and strategic situations means that human operators will increasingly rely on collaborative input from agent teammates (e.g., Masiello, 2013). However, plans to team autonomous agents with humans raise new questions regarding the effects that such teammates might have on important team psychological processes, such as team cognition and trust. Specifically, it is not known how modifications in team structure, such as changes in team size, influence team dynamics and psychological processes when the team includes an artificial agent, nor how trust established in such teams transfers to new environments, nor how measures that have been used to predict trust in humans generalize to agent teammates. Our current research examined these effects through the detection and analysis of an objective team phenomenon known as physio-behavioral coupling (PBC) using Multidimensional Recurrence Quantification Analysis (MdRQA; Wallot, Roepstorff, and Mønster, 2016) of shared physiological arousal during initial team formation and training. In particular, as shared physiological arousal measured in changing heart rhythms within human teams has been shown to be associated with measures of trust (Mitkidis, McGraw, Roepstorff, & Wallot, 2015) and concern for others (Konvalinka et al., 2011), we investigated how shared physiological arousal predicts willingness to trust an agent teammate in a novel task environment.We conducted an experiment consisting of collecting physio-behavioral data (i.e., heart rate) from teams of different sizes as they performed a series of collaborative, consensus building tasks. The independent variable was team size (teams of 2 or 3 human players, with an artificial agent teammate always present), and there were two separate team-oriented tasks: A first-round consensus-building wagering task, and a second-round task in which teams were able to make wagers on the expected performance of the agent teammate in a subsequent maze running task called Checkmate (Alarcon et al., 2017). We predicted that complimentary combinations of PBC (e.g., measures of overall similarity and stability in heart rate dynamics) obtained from MdRQA, along with self-reported measures of team and agent trust, would be positively related to future trusting behaviors in the agent teammate, and that increasing the number of teammates would result in higher order, more complex structure in the physio- behavioral data that would not be reducible to simpler patterns (e.g., Wallot et al., 2016). To this end, we predicted that measures of self-reported trust and multivariate PBC would be reducible to meaningful lower dimensional structures using principal components analysis (PCA), and that PBC calculated from the first task from the full team, but not from averages aggregated from subsets of the team, would significantly predict trusting behavior in the second task.Ninety-two participants (31 men and 61 women) recruited from the campus of a midwestern university in theU.S. took part in this study (19 dyads and 18 triads). Ages ranged from 18 to 42 (M = 22, SD = 5.48). The experiment was a univariate (team size; two or three human teammates with an agent teammate always present) between-subjects design. Self-reported measures were collected from each team member before each of the two tasks and included items that measured: Team ability, team benevolence, team integrity, and team trust (adapted from Mayer & Davis, 1999); trust in human teammates (adapted from Naquin & Paulson, 2003); agent competence, cognitive trust in the agent, emotional trust in the agent, intention to delegate to the agent, and intention to adopt the agent as an aid (adapted from Komiak & Benbasat, 2006); and collective efficacy (adapted from Riggs & Knight, 1994).Factor analysis of the composite scales from aggregated survey data indicated the data loaded well onto factors that corresponded to trust in the team and trust in the agent teammate. Factor analysis of MdRQA from the full team and from the averaged lower order analyses showed that each had one component with an eigenvalue greater than what would be expected by chance. Results from analyses using logistic regression to predict Checkmate betting showed that self-reported measures of trust in the agent and MdRQA of full team PBC in the initial task significantly predicted subsequent trusting behavior in an agent teammate in Checkmate, but lower-order PBC estimated from averages of team subgroups did not. These results suggest that multivariate team-level coupling has predictive power in subsequent team outcomes that cannot be fully captured using data aggregated from subgroup averages, and that measures of PBC measured from human teammates is related to trust in an agent teammate.We note two important contributions of the present study. First, that PBC and subjective measures of trust were significant predictors of observed trusting behavior regardless of team size suggests that important team processesand outcomes are at least partially invariant to changes in team size, a promising outcome for the prospect of meaningfully scaling measures of PBC beyond the typical dyadic context. Second, we have shown that shared team- level arousal is a significant predictor of subsequent trusting behavior in an agent teammate in a novel task, demonstrating that these objective measures are extensible to trust in non-human partners.

***

**_Cue Utilization, Perceptions, and Experience in the Interpretation of Weather Radar Returns_**  
Wiggins, Mark W.; Crane, Monique; Loveday, Thomas  
https://doi.org/10.1177/1541931218621164  

##### This study was designed to examine the role of cue utilization, perceptions, and measures of operational experience in the interpretation of a scenario involving the interpretation of weather radar returns. A total of 47 qualified pilots completed EXPERTise 2.0, an online assessment of cue utilization in the context of weather radar systems. They also completed a scenario involving the interpretation of weather radar returns which required an assessment as to whether they could continue the flight safely in the absence of a change in track or altitude. Consistent with research in other domains, the results revealed a relationship between performance and cue utilization. No relationships were evident on the basis of flight experience nor the inclination to use or trust weather radar systems. The results provide the basis for a tool that might be employed to assess pilots’ cue utilization, thereby enabling more targeted approaches to pilot training and weather radar system design.

***

**_Stereotypical of Us to Stereotype Them: The Effect of System-Wide Trust on Heterogeneous Populations of Unmanned Autonomous Vehicles_**  
Kluck, Molly; Kohn, Spencer C.; Walliser, James C.; de Visser, Ewart J.; Shaw, Tyler H.  
https://doi.org/10.1177/1541931218621253  

##### Operators generalize their trust across all of the autonomous agents they are working with, a phenomenon referred to as System Wide Trust (SWT). As a result, the failure of one aid can cause a trust decrement in —and therefore disuse of— all other competent aids within the system. This study explored two possible SWT mitigation strategies: competence transparency and different appearance of aids. Previous research has shown that transparency and feedback affects trust calibration in systems (Walliser et al., 2016), yet our appearance manipulation is relatively novel, using gestalt principles of grouping to explore whether heterogeneous aids will be more easily differentiated compared to homogenous aids. Participants supervised four UAVs that identified targets as enemies or friendlies. Only one of these UAVs was inaccurate (70% recommended accuracy), which caused a SWT trust decrement for all UAVs. We expected that the heterogeneous UAVs with competence transparency would suffer the least SWT effect, yet the results did not find a difference between conditions. These findings suggest that the System Wide Trust effect is too strong to be affected by our manipulations and that further research on mitigation strategies is required.

***

**_Trust Repair Strategies with Self-Driving Vehicles: An Exploratory Study_**  
Kohn, Spencer C.; Quinn, Daniel; Pak, Richard; de Visser, Ewart J.; Shaw, Tyler H.  
https://doi.org/10.1177/1541931218621254  

##### Trust is important for any relationship, especially so with self-driving vehicles: passengers must trust these vehicles with their life. Given the criticality of maintaining passenger’s trust, yet the dearth of self-driving trust repair research relative to the growth of the self-driving industry, we conducted two studies to better understand how people view errors committed by self-driving cars, as well as what types of trust repair efforts may be viable for use by self-driving cars. Experiment 1 manipulated error type and driver types to determine whether driver type (human versus self-driving) affected how participants assessed errors. Results indicate that errors committed by both driver types are not assessed differently. Given the similarity, experiment 2 focused on self-driving cars, using a wide variety of trust repair efforts to confirm human-human research and determine which repairs were most effective at mitigating the effect of violations on trust. We confirmed the pattern of trust repairs in human-human research, and found that some apologies were more effective at repairing trust than some denials. These findings help focus future research, while providing broad guidance as to potential methods for approaching trust repair with self-driving cars.

***

**_Effects of Automation Type on Human Performance in Proofreading Tasks_**  
Jeong, Heejin; Park, Jangwoon; Park, Jaehyun; Lee, Byung Cheol  
https://doi.org/10.1177/1541931218621261  

##### Automation is ubiquitous and indispensable in modern working environments. It is adopted and used in not only advanced industrial- and technology-oriented operations, but also ordinary home or office computational functions. In general, automated systems aim to improve overall work efficiency and productivity of labor-intensive tasks by decreasing the risk of errors, and cognitive and physical workloads. The systems offer the support for diverse decision-making processes as well. However, the benefits of automation are not consistently achieved and depend on the types and features of automation (Onnasch, Wickens, Li, & Manzey, 2014; Parasuraman, Sheridan, & Wickens, 2000). Possible negative side effects have been reported. Sometimes, automation may lead to multi-tasking environments, which allows operators to be distractive with several tasks. It ultimately prolongs task completion time and causes to neglect monitoring and follow-up steps of the pre-processing tasks (Endsley, 1996). Furthermore, the operators who excessively depend on automation are easily deteriorated in skill acquisition, which is necessary for the emergency or manual operations. Thus, inconsistent performance in automation is a major issue in successful adoption and trust in automation (Jeong, Park, Park, & Lee, 2017). This paper presents an experimental study that investigates the main features and causes of the inconsistency in task performance in different types of automation. Automated proofreading tasks were used in this study, which is one of the most common types of automation we experience in daily life. Based on the similar algorithm of the auto-correct function in Microsoft Word, a custom-built program of five proofreading tasks, including one non-automated and four automated proofreading tasks, were developed using Visual Studio 2015 C#. In the non-automated task used as a reference for individual difference, participants were asked to manually find a typographical error in a sentence. In the automated tasks, auto-correcting functions are provided in two levels (i.e., low and high) of automation and two statuses (i.e., routine and failure of automation). The type of automation is defined as the combinations of a status and a level. Participants identified typographical errors by only an underlined word at the low-level automation, whereas an underlined word with a possible substituting word was given at the high-level. Additionally, in the routine automation status, a correct substituting word is provided. On the other hand, a grammatically incorrect word is given in the failed automation status. Nineteen participants (11 females and 8 males; age mean = 33.8, standard deviation = 19.1) took part in this study. Results of statistical analyses show a clear advantage in high-routine automation, in terms of both task completion time and accuracy. While task performances of high & routine automation types are quite obvious in both task completion time and accuracy, those in the failed automation types are mixed and indistinguishable. Different levels and statues of failed automation do not much influence task performance. Moreover, task completion time and mental demand are strongly correlated, and the accuracy rate and perceived trust show a strong positive correlation. The approaches and outcomes of the current study can provide some insights into the human-automation interaction systems that support human performance and safety, such as in-vehicle warning systems and automated vehicle controls.

***

**_Effects of Automation Reliability and Trust on System Monitoring Performance in Simulated Flight Tasks_**  
Ferraro, James; Clark, Logan; Christy, Naomi; Mouloua, Mustapha  
https://doi.org/10.1177/1541931218621283  

##### The current study was designed to empirically examine the effects of trust and automation reliability on multi-tasking performance in a simulated cockpit setting using the Multi-Attribute Task Battery II (MATB-II). The MATB-II simulates tasks often performed by pilots in-flight, tasking the operator with attending to automated systems and correcting errors when they inevitably occur. Over the course of three 30-minute trials, two levels of automation reliability were presented in the current study (R50% and R90%). It was hypothesized that automation reliability and trust would affect both workload and performance in this multi-tasking environment. Results indicated that reliability significantly affected monitoring performance on the MATB-II. More reliable automation resulted in poorer monitoring performance, while trust appeared to have little impact. These results provide further evidence for how operators trust and interact with automation, a topic that is relevant to the implementation of automated systems in a variety of human-machine systems such as aviation.

***

**_Warnings for Hurricane Irma: Trust of Warning Type and Perceptions of Self-Efficacy and Susceptibility_**  
Parker, Jason A.; Whitmer, Daphne E.; Sims, Valerie K.  
https://doi.org/10.1177/1541931218621312  

##### The purpose of this study was to examine the types of risk communication received about Hurricane Irma by a university sample, along with their perceptions of self-efficacy and susceptibility to the storm. Three days after the storm, 176 individuals completed a survey that asked about how they received alerts, the frequency of the alerts received, and their trust in the different risk communication mediums. Additionally, respondents completed a susceptibility measure, a self-efficacy measure, and a storm fear questionnaire. Results showed that most people received alerts from their university alert system or social media. Participants trusted risk communication the most from text alerts and radio reports, but the least from social media. Additionally, results showed that those who received more alerts also had higher levels of perceived susceptibility to the hurricane, except for those who received 16 to 20 alerts. Perceived self-efficacy was not related to the number of alerts received. These data suggest that although many urge the use of social media for spreading emergency warnings, people distrust social media for risk communication, and that this mistrust may be due to recent cases of misinformation spreading on various platforms. In addition, these data suggest that there may be a “critical point” of alerting, such that receiving more than 5 hurricane alerts may lead to significant increase in perceptions of susceptibility to the storm. Future research should investigate the critical point of effective alerting and the effect that trust in the different mediums of alert technology has on motivation to comply with the warning’s protective action recommendations.

***

**_Understanding Attitudes Towards Self-Driving Vehicles: Quantitative Analysis of Qualitative Data_**  
Lee, John D.; Kolodge, Kristin  
https://doi.org/10.1177/1541931218621319  

##### Self-driving vehicles represent potentially transformative technology. But achieving this potential depends on people’s attitudes towards this technology and willingness to use it. Ratings from surveys estimate acceptance, and open-ended comments provide an opportunity to understand the “why” behind the ratings. One way to understand the content of open-ended comments is through computer-based text analytics. A recent survey of 8,571 nationally representative drivers in J.D. Power’s 2017 U.S. Tech Choice StudySM included a rating of willingness to use self-driving vehicles and an associated open-ended response. We present a quantitative analysis of these qualitative, open-ended responses that uses structural topic modeling to reveal the basis of the respondents’ attitudes. Drivers’ attitude towards self-driving vehicles was quite negative: only 11% stated they “definitely would” trust self-driving technology, whereas 35% stated they “definitely would not.” The structural topic modeling identified 10-topics, such as “Many unknowns” and “Don’t trust” that help explain these negative attitudes.

***

**_Trust Strategies in Consumer Multiple-Component Systems_**  
Lopez, Jeremy; Pak, Richard  
https://doi.org/10.1177/1541931218621397  

##### Trust is a critical factor in successful and productive human-automation interactions. Human trust in machines is sensitive to machine performance. When automation malfunctions, trust is negatively affected. The development of increasingly complex multiple-component systems, or those with several autonomous elements, introduces even more ways for a system to err. One example is in smart home control systems where different subsystems may be controlled by different autonomous routines or rules. Multiple studies suggest that one error-prone component can lower user trust in the remaining components. This has been termed a “pull down effect.” Other research suggests that increasing the amount of information presented to the user can reduce the strength of the pull down effect by promoting heterogeneity of components. Although a majority of this research has been tested in the industrial domain, there exist certain types of information that are best suited for consumer automation (e.g., granting the automation a name and a voice). Providing this kind of information to the user may diminish the strength of the pull down effect. Thus, the current study will investigate the effectiveness of trust-preserving heterogeneity strategies in consumer multiple-component systems.

***

**_Trust in Branded Autonomous Vehicles & Performance Expectations: A Theoretical Framework_**  
Celmer, Natalie; Branaghan, Russell; Chiou, Erin  
https://doi.org/10.1177/1541931218621398  

##### Future autonomous vehicle systems will be diverse in design and functionality because they will be produced by different brands. It is possible these brand differences yield different levels of trust in the automation, therefore different expectations for vehicle performance. Perceptions of system safety, trustworthiness, and performance are important because they help users determine how reliant they can be on the system. Based on a review of the literature, the system’s perceived intent, competence, method, and history could be differentiating factors. Importantly, these perceptions are based on both the automated technology and the brand’s personality. The following theoretical framework reflects a Human Systems Engineering approach to consider how brand differences impact perceived trustworthiness, performance expectations and ultimate safety of autonomous vehicles.

***

**_Revisiting Trust in Machines: Examining Human–Machine Trust Using a Reprogrammed Pasteurizer Task_**  
Lee, Jieun; Yamani, Yusuke; Itoh, Makoto  
https://doi.org/10.1177/1541931218621400  

##### Automated technologies have brought a number of benefits to professional domains, expanding the area in which humans can perform optimally in complex work environments. Human–automation trust has become an important aspect when designing acceptable automated systems considering general users who have no comprehensive knowledge of the systems. Muir and Moray (1996) proposed a model of human–machine trust incorporating predictability, dependability, and faith as predictors of overall trust in machines. Though Muir and Moray (1996) predicted that trust in machines grows from predictability, then dependability, and finally faith, their results suggested the opposite. This study will reexamine their theoretical framework and test which of the three dimensions governs initial trust in automation. Participants will be trained to operate a simulated pasteurization plant, as in Muir and Moray (1996), and they will be asked to maximize system performance in the pasteurizing task. We hypothesized that faith governs overall trust early in the interaction with the automated system, then dependability, and finally predictability as lay automation users become more familiar with the system. We attempt to replicate the results of Muir and Moray (1996) and argue that their model should be revised for trust development for general automation users.

***

**_A Preliminary Study to Investigate the Sensemaking Process of UAV Reports by Operators after Periods of Disconnect for Threat Assessment_**  
Rogers, Hunter; Al Ghalayini, Maher; Madathil, Kapil Chalil  
https://doi.org/10.1177/1541931218621407  

##### Teleoperated robots have been used to minimize human presence and interaction in dangerous or difficult areas or to enhance human capabilities. One of the challenges that still needs investigation is human-robot communication regarding making decisions based on extracted information. As such, the purpose of this research is to address issues of decision making after communication disconnections through interface design by focusing on improving sensemaking. Analyzing the effects of interface design in a UAV threat assessment scenario is ideal to examine not only the sensemaking process but also how that process defines decision making in an environment where efficient decision making and low clutter displays are needed. The data from this study will serve determine elements of an optimal interface for information assimilation. Twenty participants were recruited to complete a series of sixteen threat assessment decisions with different interface designs, varying amounts of information and layouts of information. It was observed that level of detailed information had a significant effect on the subjective trust and decision selected and display layout had a significant effect on the time taken to complete a decision.

***

**_Characterizing Driver Trust in Vehicle Control Algorithm Parameters_**  
Domeyer, Joshua; Venkatraman, Vindhya; Price, Morgan; Lee, John D  
https://doi.org/10.1177/1541931218621413  

##### Human factors research in vehicle automation has focused on user interfaces such as performance feedback through visual and auditory displays (Blanco et al., 2015). Another approach is to use vehicle dynamics and vibrations as communicative tools for guiding attention (e.g., Morando, Victor, & Dozza, 2016; Walker, Stanton, & Young, 2006; Wiese & Lee, 2007). In our previous study (Price, Venkatraman, Gibson, Lee, & Mutlu, 2016), we showed that the steering wheel deadband, or lateral movement of the vehicle while maintaining lane position, was negatively associated with trust—more lateral movement led to less trust in the algorithm. The present study extends these findings by using Bayesian statistical methods with new control algorithm data. Although the inclusion of additional algorithm characteristics did not improve the trust model, the use of Bayesian statistical methods provides a useful tool to incorporate prior knowledge into an analysis.

***

**_Effects of Warning Characteristics on Driver Performance in Connected Vehicle Systems with Missing Warnings_**  
Zhang, Yiqi; Wu, Changxu; Qiao, Chunming; Hou, Yunfei  
https://doi.org/10.1177/1541931218621415  

##### The connected vehicle systems (CVS) aim to provide drivers with information in a timely and reliable way to improve transportation safety. With the emerging wireless communication technologies, the vehicles will be equipped with the ability to communicate with each other about the surrounding traffic situations by exchanging vehicle status and motion data via Dedicated Short-Range Communications (DSRC) network (Kenney, 2011).With the assistance of the cooperative collision warnings, the impact of designed warning parameters on driver performance is increasingly important. Existing empirical studies have studied the warning timing and warning reliability in determining the effectiveness of the collision warning systems in advanced driver assistance systems (ADAS). In terms of warning timing, the studies in reached consistent conclusions that early warnings induced more timely braking and longer braking process, resulted in higher trust of the warning systems, and reduced collision rates (for example, Abe & Richardson, 2006a; Lee, McGehee, Brown, & Reyes, 2002; Yan, Xue, Ma, & Xu, 2014; Yan, Zhang, & Ma, 2015; Wan, Wu, and Zhang, 2016). In terms of the warning reliability, research has shown that warnings with a higher reliability increased driver’s trust of the warning systems, led to higher frequency in warning responses, and reduced crash rates (for example, Abe, Itoh, & Yamamura, 2009; Bliss & Acton, 2003; Maltz & Shinar, 2007; Sullivan, Tsimhoni, & Bogard, 2008). However, the interaction effects of warning lead time and warning reliability on driver performance was not examined especially under the connected vehicle settings.The current research investigated the interaction effects of warning lead time (2.5s vs. 4.5s), warning reliability (73% vs. 89%), and speech warning style (command vs. notification) on driver performance and subjective evaluation of warnings in CVS. A driving simulator study with thirty-two participants was conducted to simulate a connected vehicle environment with missing warnings due to the failures in the data transmission within the communication network of the CVS.The results showed command warnings led to a smaller collision rate compared to notification warnings with the warning lead time of 2.5s, whereas notification warnings resulted in a smaller collision rate compared to command warning with the warning lead time of 4.5s. These results suggested notification warnings should be selected when warning lead time is longer and warning reliability is higher, which resulted in higher safety benefits and higher subjective ratings. Command warnings could be selected when warning lead time is shorter since they led to more safety benefits.However, such selection has to be made with caution since command warnings may limit drivers’ response type and were perceived as less helpful than notification warnings.

***

**_Drivers’ Perceptions of Functionality Implied by Terms Used to Describe Automation in Vehicles_**  
Nees, Michael A.  
https://doi.org/10.1177/1541931218621430  

##### The expectations induced by the labels used to describe vehicle automation are important to understand, because research has shown that expectations can affect trust in automation even before a person uses the system for the first time. An online sample of drivers rated the perceived division of driving responsibilities implied by common terms used to describe automation. Ratings of 13 terms were made on a scale from 1 (“human driver is entirely responsible”) to 7 (“vehicle is entirely responsible”) for three driving tasks (steering, accelerating/braking, and monitoring). In several instances, the functionality implied by automation terms did not match the technical definitions of the terms and/or the actual capabilities of the automated vehicle functions currently described by the terms. These exploratory findings may spur and guide future research on this under-examined topic.

***

**_Investigating Attorney Trust in Machine-enabled Legal Research: A Mixed Methods Approach_**  
Lowry, Katherine M; Kamp, Elaine; Fallon, Corey K; McGhee, Riley  
https://doi.org/10.1177/1541931218621452  

##### ROSS is a new legal research tool leveraging artificial intelligence. This tool is somewhat unique both in terms of its interface and underlying functionality. ROSS’s deviation from more traditional systems may have an impact on the adoption of this new technology. The researchers in the current study conducted a mixed methods evaluation of ROSS to assess user experience and likelihood of adoption with a particular emphasis on evaluating user trust in the technology. The researchers conducted simulation interviews with eleven experienced bankruptcy attorneys. In addition, a human-computer trust survey was administered to assess user trust in the technology at various time points throughout the study. This quantitative survey measured both cognitive and affect-based trust and revealed a substantial increase in trust with exposure to the system. Participants were particularly impressed with attributes of the system that are believed to form the cognitive basis of trust, such as the tool’s reliability and understandability. Despite these positive findings, our qualitative assessment of experiential trust was mixed and most users concluded that they would not use ROSS as their primary research tool. This decision may be attributed to a lack of faith in the technology and concerns related to ROSS’s usability. The simulations were conducted between February and April of 2017. It should be noted that ROSS has been updated since this time and certain findings may no longer be representative of the current platform.

***

**_Pedestrians receptivity in autonomous vehicles: Exploring a video-based assessment_**  
Deb, Shuchisnigdha; Hudson, Christopher R.; Carruth, Daniel W.; Frey, Darren  
https://doi.org/10.1177/1541931218621465  

##### Pedestrian receptivity toward autonomous vehicles (AVs) usually depends on the extent to which they receive indication of the vehicle’s intended action. Previous studies have typically used overt subjective measures (trust measures, ratings, etc.) and few objective measures (walking speed, waiting time, etc.) to identify external features that can improve pedestrians’ receptivity toward AVs. The current study aims to evaluate pedestrians’ behavioral measures of receptivity based on their body (head and foot) movements as they experience an AV in a virtual traffic environment. Videos of pedestrians at a virtual crosswalk, interacting with an AV that was equipped with an external feature indicating different operator statuses were coded. The operator statuses used in this study included: no driver, attentive driver, and distracted driver. The external features used were: no feature, upraised hand, stop sign, walking silhouette, walk in text, music, and a verbal message. Pedestrian body movements were derived from the video to determine frequency for looking at the approaching vehicle while crossing and stops after initiating crossing. Average durations for initiating crossing after signal were calculated. For no feature condition, the waiting time was calculated when participants observed the car. Data were compared with pedestrians’ self-reported ratings for receptivity to investigate body movements’ sensitivity to participants’ receptivity level. Results suggest body movements are sensitive to individual differences in reported receptivity. Future work should further examine the utility of this behavioral metric by further examining situational differences.

***

