# Publications

## 2024

### CyMed: A Framework for Testing Connected Medical Devices
*Proceedings of the 4th Conference Society 5.0 - Innovation for Sustainable and Inclusive Social Good*

**Authors:** Christopher Scherb, Adrian Hadayah, Luc Bryan, Hermann Grieder, Petra Maria Asprion  
**Publisher:** Springer CCIS 2173  
**Volume:** 1

Connected Medical Devices (CMDs) significantly benefit patients but are also vulnerable to malfunctions that can harm. Despite strict safety regulations for market entry, there's a notable shortage of specific cybersecurity frameworks for CMDs. Existing regulations on cybersecurity practices are often broad and lack detailed implementation steps. This paper introduces the CyMed framework, designed for vendors and end-users, offering explicit strategies to enhance the cybersecurity of CMDs. The effectiveness of CyMed is assessed through practical testing and expert interviews.

### Divide and Conquer based Symbolic Vulnerability Detection
*arXiv preprint arXiv:2409.13478*

**Authors:** Christopher Scherb, Luc Bryan Heitz, Hermann Grieder  
**Publication Date:** September 20, 2024

In modern software development, vulnerability detection is crucial due to the inevitability of bugs and vulnerabilities in complex software systems. Effective detection and elimination of these vulnerabilities during the testing phase are essential. Current methods, such as fuzzing, are widely used for this purpose. While fuzzing is efficient in identifying a broad range of bugs and vulnerabilities by using random mutations or generations, it does not guarantee correctness or absence of vulnerabilities. Therefore, non-random methods are preferable for ensuring the safety and security of critical infrastructure and control systems. This paper presents a vulnerability detection approach based on symbolic execution and control flow graph analysis to identify various types of software weaknesses. Our approach employs a divide-and-conquer algorithm to eliminate irrelevant program information, thus accelerating the process and enabling the analysis of larger programs compared to traditional symbolic execution and model checking methods.

## 2023

### Divide, Conquer and Verify: Improving Symbolic Execution Performance
*arXiv preprint arXiv:2310.03598*

**Authors:** Christopher Scherb, Luc Bryan Heitz, Hermann Grieder, Olivier Mattmann  
**Publication Date:** October 2023

Symbolic Execution is a formal method that can be used to verify the behavior of computer programs and detect software vulnerabilities. Compared to other testing methods such as fuzzing, Symbolic Execution has the advantage of providing formal guarantees about the program. However, despite advances in performance in recent years, Symbolic Execution is too slow to be applied to real-world software. This is primarily caused by the path explosion problem as well as by the computational complexity of SMT solving. In this paper, we present a divide-and-conquer approach for symbolic execution by executing individual slices and later combining the side effects. This way, the overall problem size is kept small, reducing the impact of computational complexity on large problems.

### A Cyber Attack Simulation for Teaching Cybersecurity
*EPiC Series in Computing*

**Authors:** Christopher Scherb, Luc Bryan Heitz, Frank Grimberg, Hermann Grieder, Marcel Maurer  
**Publication Date:** May 26, 2023  
**Volume:** 93  
**Pages:** 129-140  
**Publisher:** EasyChair

With the rising number of cyberattacks, such as ransomware attacks and cyber espionage, educating non-cybersecurity professionals to recognize threats has become more important than ever before. However, traditional training methods, such as phishing awareness campaigns, training videos and assessments have proven to be less effective over time. Therefore, it is time to rethink the approach on how to train cyber awareness. In this paper we suggest an alternative approach–a serious game–to educate awareness for common cyberattacks. While many serious games for cybersecurity education exist, all follow a very similar approach: showing people the effects of a cyber attack on their own system or company network. For example, one of the main tasks in these games is to sort out phishing mails. We developed and evaluated a new type of cybersecurity game: an attack simulator, which shows the entire setting from a different perspective. Instead of sorting out phishing mails the players should write phishing mails to trick potential victims and use other forms of cyberattacks. Our game explains the intention of each attack and shows the consequences of a successful attack. This way, we hope, players will get a better understanding on how to detect cyberattacks.
