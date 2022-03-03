---
layout: default
title: Tool Categorization
nav_order: 5
has_children: false
permalink: /docs/toolcategorization
---
# Tool Paper Selection
---

We systematically collected a list of malware detection papers by searching top conferences and journals in software engineering and security (based on CORE ranking and Journal Citation Reports) between 2010 and 2021.

The software engineering conferences/journals:

1. IEEE/ACM International Conference on Software Engineering (ICSE)
2. ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE)
3. IEEE/ACM International Conference on Automated Software Engineering (ASE)
4. ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA)
5. IEEE Transactions on Software Engineering (TSE)
6. Springer Empirical Software Engineering (EMSE)
7. Elsevier Journal of Systems and Software (JSS)
8. ACM Transactions on Software Engineering and Methodology (TOSEM)
9. IEEE Software
10. Elsevier Information and Software Technology (IST)

The security conferences/journals include:

1. ACM Conference on Computer and Communications Security (CCS)
2. IEEE Symposium on Security and Privacy (S&P)
3. USENIX Security Symposium
4. Network and Distributed System Security Symposium (NDSS)
5. ACM Annual Computer Security Applications Conference (ACSAC)
6. Elsevier Journal of Computers & Security
7. IEEE Security & Privacy Journal
8. IEEE Transactions on Information Forensics and Security (TIFS)
9. IEEE Transactions on Dependable and Secure Computing (TDSC)
10. Springer International Journal of Information Security (IJIS)

We further augmented the resulting list with malware detection techniques from seven recent surveys:

1. Qiu, Junyang, Jun Zhang, Wei Luo, Lei Pan, Surya Nepal, and Yang Xiang. "A survey of Android malware detection with deep neural models." ACM Computing Surveys (CSUR) 53, no. 6 (2020): 1-36.
2. Arshad, Saba, Munam Ali Shah, Abid Khan, and Mansoor Ahmed. "Android malware detection & protection: a survey." International Journal of Advanced Computer Science and Applications 7, no. 2 (2016): 463-475.
3. Rashidi, Bahman, and Carol J. Fung. "A Survey of Android Security Threats and Defenses." J. Wirel. Mob. Networks Ubiquitous Comput. Dependable Appl. 6, no. 3 (2015): 3-35.
4. Tam, Kimberly, Ali Feizollah, Nor Badrul Anuar, Rosli Salleh, and Lorenzo Cavallaro. "The evolution of android malware and android analysis techniques." ACM Computing Surveys (CSUR) 49, no. 4 (2017): 1-41.
5. Faruki, Parvez, Ammar Bharmal, Vijay Laxmi, Vijay Ganmoor, Manoj Singh Gaur, Mauro Conti, and Muttukrishnan Rajarajan. "Android security: a survey of issues, malware penetration, and defenses." IEEE communications surveys & tutorials 17, no. 2 (2014): 998-1022.
6. Alqahtani, Ebtesam J., Rachid Zagrouba, and Abdullah Almuhaideb. "A Survey on Android Malware Detection Techniques Using Machine Learning Algorithms." In 2019 Sixth International Conference on Software Defined Systems (SDS), pp. 110-117. IEEE, 2019.
7. Souri, Alireza, and Rahil Hosseini. "A state-of-the-art survey of malware detection approaches using data mining techniques." Human-centric Computing and Information Sciences 8, no. 1 (2018): 1-22.

---

## Tool Paper Categorization

We further categorized the identified papers into ten categories:

<!-- ![](../img/tools_mind_map.PNG) -->
[<img src="../img/tools_mind_map.svg" width="70%"/>](../img/tools_mind_map.svg)

These categories include:

1. Not Malware Detection - Android research irrelevant to malware detection, such as tools for testing, detecting bugs, documentation, code recommendation, etc.
2. Generic Malware - Tools that detect malware by learning features from a large set of benign and malicious applications.
3. Payload Specific - Tools that target a specific type of payload (e.g., info-leak, overlay phishing, privilege escalation)
4. Condition Detection - Tools that focus on conditions that lead to the malicious payload
5. Forced Execution - Tools that force app execution into the malicious path
6. Hiding Detection - Tools that flag the difference between app behavior and its presented user interface
7. Dynamic Loading - Tools that detect dynamic code loading
8. Sandboxing - Tools that create analysis frameworks to aid researchers in analyzing malware samples
9. Repackaged Malware - Tools that detect repackaged apps
10. Inter App Attacks - Tools that detect apps colluding together to perform an attack

Detailed list of papers in each category can be found in this [excel file](../../../assets/data/excelsheets/Tools.xlsx).

---
