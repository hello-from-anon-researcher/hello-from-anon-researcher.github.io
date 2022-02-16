---
layout: default
title: Tool Collection
nav_order: 5
has_children: false
permalink: /docs/toolcollection
---
# Tool Collection
---

## Tool Selection

We systematically collected a list of malware detection papers by searching top conferences/journals based on CORE ranking and Journal Citation Reports (JCR) between 2010 and 2021.

The software engineering conferences/journals include:

1. International Conference on Automated Software Engineering (ASE)
2. Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE)
3. International Conference on Software Engineering (ICSE)
4. International Symposium on Software Testing and Analysis (ISSTA)
5. Empirical Software Engineering (EMSE)
6. IEEE Software
7. Information and Software Technology (IST)
8. Journal of Systems and Software (JSS)
9. Transactions on Software Engineering (TSE)
10. Transactions on Software Engineering and Methodology (TOSEM)

The security conferences/journals include:

1. Conference on Computer and Communications Security (CCS)
2. Symposium on Security and Privacy (S&P)
3. Network and Distributed System Security Symposium (NDSS)
4. USENIX Security Symposium
5. Transactions on Information Forensics and Security (TIFS)
6. Transactions on Dependable and Secure Computing (TDSC)
7. Journal of Computers & Security
8. International Journal of Information Security (IJIS)
9. Security & Privacy Journal
10. Annual Computer Security Applications Conference (ACSAC)

We further augmented the resulting list with malware detection techniques from seven recent surveys:

1. Qiu, Junyang, Jun Zhang, Wei Luo, Lei Pan, Surya Nepal, and Yang Xiang. "A survey of Android malware detection with deep neural models." ACM Computing Surveys (CSUR) 53, no. 6 (2020): 1-36.
2. Arshad, Saba, Munam Ali Shah, Abid Khan, and Mansoor Ahmed. "Android malware detection & protection: a survey." International Journal of Advanced Computer Science and Applications 7, no. 2 (2016): 463-475.
3. Rashidi, Bahman, and Carol J. Fung. "A Survey of Android Security Threats and Defenses." J. Wirel. Mob. Networks Ubiquitous Comput. Dependable Appl. 6, no. 3 (2015): 3-35.
4. Tam, Kimberly, Ali Feizollah, Nor Badrul Anuar, Rosli Salleh, and Lorenzo Cavallaro. "The evolution of android malware and android analysis techniques." ACM Computing Surveys (CSUR) 49, no. 4 (2017): 1-41.
5. Faruki, Parvez, Ammar Bharmal, Vijay Laxmi, Vijay Ganmoor, Manoj Singh Gaur, Mauro Conti, and Muttukrishnan Rajarajan. "Android security: a survey of issues, malware penetration, and defenses." IEEE communications surveys & tutorials 17, no. 2 (2014): 998-1022.
6. Alqahtani, Ebtesam J., Rachid Zagrouba, and Abdullah Almuhaideb. "A Survey on Android Malware Detection Techniques Using Machine Learning Algorithms." In 2019 Sixth International Conference on Software Defined Systems (SDS), pp. 110-117. IEEE, 2019.
7. Souri, Alireza, and Rahil Hosseini. "A state-of-the-art survey of malware detection approaches using data mining techniques." Human-centric Computing and Information Sciences 8, no. 1 (2018): 1-22.

---

## Tool Categorization

The image below lists the categorization of Android security papers found:

![](../img/tools_mind_map.PNG)

These categories include:

1. Not Malware Detection - Papers irrelevant to malware detection
2. Generic Malware - Papers aimed to detect malware by learning features from a large set of benign and malicious applications.
3. Payload Specific - Papers aimed to targeting a specific type of payload (ex., info-leak, overlay phishing, privilege escalation)
4. Condition Detection - Papers aimed at focusing on conditions that lead to the malicious payload
5. Forced Execution - Papers aimed to force app execution into the malicious path
6. Hiding Detection - Papers aimed at flagging the difference between app behavior and its presented user interface
7. Dynamic Loading - Papers aimed at detecting dynamic code loading
8. Sandboxing - Papers aimed at creating analysis frameworks to aid researchers in analyzing malware samples
9. Repackaged Malware - Papers aimed at detecting repackaged apps
10. Inter App Attacks - Papers aimed at detecting apps that collude together to perform an attack

Details of the papers within each category can be found within this [excel file](../../../assets/data/excelsheets/Tools.xlsx).

---
