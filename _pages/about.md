---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About Me
Welcome to my homepage! I am a Ph.D. student studying Artificial Intelligence at Sungkyunkwan University. I am advised by Professor <a href='https://professor.skku.edu/researcher/professorList.do?mode=view&perId=LZStrLISwEgpgTgqgDgDwDbACoGUBSBDA9gDkwBMBnAUQHEBzAXhqA%20&categoryId=U&jojikCode1=3191'>Moohong Min</a> in the <a href='https://swlab.skku.edu/'>Software Laboratory</a>. My research sits at the intersection of large language models and security, spanning jailbreak and multimodal attacks, retrieval-augmented generation, and also forensic analysis of AI agents. I aim to understand how AI systems fail under adversarial pressure, and to turn those failure modes into defenses and accountability mechanisms that hold up outside the lab.

Here is a <a href='/files/Minseok_Hur_cv.pdf' target='_blank' rel='noopener'>link to my curriculum vitae</a>. (Last updated October 2026)


# 🔥 News
- *2026.08.07*: &nbsp;🎉🎉 "Cite Unseen: Measuring Citation-Channel Vulnerabilities in Retrieval-Augmented Generation" was accepted to **CIKM 2026**! See you in Rome.
- *2026.07.10*: &nbsp;🎉🎉 "STAFT: Privacy-Preserving Semantic Trace Abstraction for Forensic Triage of Personal AI Agent Incidents" was accepted to **DFRWS APAC 2026**! See you in Singapore.


# 📖 Education
- *2026.03 - Present*, Ph.D. in Artificial Intelligence, Sungkyunkwan University
- *2024.03 - 2026.02*, Master of Engineering in Immersive Media Engineering, Sungkyunkwan University (GPA: 4.40/4.5)
- *2020.03 - 2024.02*, Bachelor of Science in Computer Education, Sungkyunkwan University (GPA: 3.96/4.5)


# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2026 | Conference</div><img src='images/citeunseen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**CiteUnseen: Weaponizing Citations in Retrieval-Augmented Generation**

**Minseok Hur**, Jiho Shin, Damin Kim, Moohong Min

35th ACM International Conference on Information and Knowledge Management (CIKM 2026)

<a href="/files/cikm2026_short_cite_unseeen.pdf" target="_blank" rel="noopener">Paper</a> | [GitHub](https://github.com/alexhur3535/CiteUnseen) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DFRWS APAC 2026 | Conference</div><img src='images/staft.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**STAFT: Privacy-Preserving Semantic Trace Abstraction for Forensic Triage of Personal AI Agent Incidents**

**Minseok Hur**, Jiho Shin, Moohong Min

Digital Forensic Research Workshop Asia–Pacific (DFRWS APAC 2026)

<a href="/files/dfrwsapac2026_staft.pdf" target="_blank" rel="noopener">Paper</a> | [GitHub](https://github.com/alexhur3535/STAFT) 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJIS | Journal</div><img src='images/ijis.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**Are large language models effective for detecting spam messages?**

**Minseok Hur**, Sooyon Seo, Jaeho Hwang, Moohong Min

International Journal of Information Security (Q1)

[Paper](https://link.springer.com/article/10.1007/s10207-026-01283-5) | [GitHub](https://github.com/gr8alex35/MD-SRA)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Scientometrics | Journal</div><img src='images/scientometrics.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**Evidence access design for llm-based scientometrics: graph-based evidence augmentation over semantic retrieval**

Yunseop Lee, **Minseok Hur**, Moohong Min

Scientometrics (Q1)

[Paper](https://link.springer.com/article/10.1007/s11192-026-05729-4)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SAC 2026 | Conference</div><img src='images/mdsra.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**MD-SRA: Multimodal Detection of SEO-based Redirection Attacks**

**Minseok Hur**, Jiho Shin, Moohong Min

SAC '26: Proceedings of the 41th ACM/SIGAPP Symposium on Applied Computing

[Paper](https://dl.acm.org/doi/abs/10.1145/3748522.3779877) | [GitHub](https://github.com/gr8alex35/MD-SRA) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SAC 2026 | Conference</div><img src='images/sensitivemamba.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**SensitiveMamba: Selective State Space Modeling for Robust Time Series Anomaly Detection**

**Minseok Hur**, Dongho Kim, Moohong Min

SAC '26: Proceedings of the 41th ACM/SIGAPP Symposium on Applied Computing

[Paper](https://dl.acm.org/doi/abs/10.1145/3748522.3779727) | [GitHub](https://github.com/gr8alex35/SensitiveMamba) 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2025 | Conference</div><img src='images/cikm2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**Jailbreaking LLMs Through Cross-Cultural Prompts**

Damin Kim, **Minseok Hur**, Jeongin Lee, Moohong Min

CIKM '25: Proceedings of the 34th ACM International Conference on Information and Knowledge Management

[Paper](https://dl.acm.org/doi/abs/10.1145/3746252.3760892)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SAC 2025 | Conference</div><img src='images/qarag.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**From RAG to QA-RAG: Integrating Generative AI for Pharmaceutical Regulatory Compliance Process**

Jaewoong Kim, **Minseok Hur**, Moohong Min

SAC '25: Proceedings of the 40th ACM/SIGAPP Symposium on Applied Computing

[Paper](https://dl.acm.org/doi/abs/10.1145/3672608.3707749) | <a href="/files/sac2025_poster.pdf" target="_blank" rel="noopener">Poster</a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISOFIC 2024 | Conference</div><img src='images/isofic2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**Procedures for Developing Secure FPGA in Nuclear Power Plants**

**Minseok Hur**, Jiho Shin, Moohong Min, Aram Kim

8th International Symposium on Future Instrumentation and Control for Nuclear Power Plants 

<a href="/files/isofic2024.pdf" target="_blank" rel="noopener">Paper</a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CSA 2024 | Conference</div><img src='images/csa2024_fpga.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**Analysis of FPGA Development Processes and Associated Security Threats**

**Minseok Hur**, Jiho Shin, Moohong Min, Aram Kim

16th International Conference on Computer Science and its Applications

<a href="/files/csa2024_fpga_analysis.pdf" target="_blank" rel="noopener">Paper</a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CSA 2024 | Conference</div><img src='images/csa2024_attackcase.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**Development of an Attack Case Generation Model Based on the Characteristics of Digital Assets of Nuclear Power Plants**

**Minseok Hur**, Eunji Lee, Sooyon Seo, Jaeho Hwang, Dongmin Kim, Moohong Min, Aram Kim

16th International Conference on Computer Science and its Applications

<a href="/files/csa2024_attackcase.pdf" target="_blank" rel="noopener">Paper</a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MobiSec 2024 | Conference</div><img src='images/mobisec2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**A Study on Evaluation Items and Indicators for Ensuring Cyber Resilience**

Sooyon Seo, Jaeho Hwang, **Minseok Hur**, Dongmin Kim, Sechan Lee, Moohong Min

The 8th International Conference on Mobile Internet Security (MobiSec)

<a href="/files/mobisec2024_resilience.pdf" target="_blank" rel="noopener">Paper</a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MobiSec 2024 | Conference</div></div></div>
<div class='paper-box-text' markdown="1">


**Analysis of Deepfake Detection Models Against Deepfake Crimes**

Sechan Lee, Sooyon Seo, Jaeho Hwang, **Minseok Hur**, Dongmin Kim, Aram Kim, Moohong Min

The 8th International Conference on Mobile Internet Security (MobiSec)

<a href="/files/mobisec2024_analysis.pdf" target="_blank" rel="noopener">Paper</a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KCC 2025 | Conference</div></div></div>
<div class='paper-box-text' markdown="1">


**BAG: "BERT-AttentionGNN"HTML 하이브리드 모델을 활용한 불법사이트 구조 탐지**

이세찬, **허민석**, 민무홍

2025 한국컴퓨터종합학술대회 논문집 (KCC)

<a href="/files/kcc2025_bag.pdf" target="_blank" rel="noopener">Paper</a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KCC 2024 | Conference</div></div></div>
<div class='paper-box-text' markdown="1">


**스팸 메시지 발생 빈도 및 패턴 분석에 관한 연구**

서수연, **허민석**, 황재호, 장지원, 신지호, 민무홍

2024 한국컴퓨터종합학술대회 논문집 (KCC)

<a href="/files/kcc2024_spam.pdf" target="_blank" rel="noopener">Paper</a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KCC 2024 | Conference</div></div></div>
<div class='paper-box-text' markdown="1">


**대규모 온라인으로 진행되는 비전공자 대상 인공지능 교양필수 과목의 효과적인 운영 사례 연구**

황재호, **허민석**, 서수연, 민무홍

2024 한국컴퓨터종합학술대회 논문집 (KCC)

<a href="/files/kcc2024_lecture.pdf" target="_blank" rel="noopener">Paper</a>
</div>
</div>


<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->



# 🔬 Research Experience

- *2026.06 - Present*, **AI-based Diagnosis of Floor Impact Sound Reduction Performance in Apartment Buildings**, funded by the Korea Agency for Infrastructure Technology Advancement (KAIA), in industry collaboration with MetaInnotech. - Advancing the AI analysis engine for AIoT-measured floor impact sound data for automatic measurement quality assessment and an MLOps pipeline for continuous retraining and performance monitoring.

- *2026.01 - Present*, **Development of an Integrated Narcotics Investigation System Linked to Dark Web and Virtual Asset Transaction Tracing**, funded by the Korean National Police Agency (KNPA) and the Ministry of Science and ICT (MSIT), managed by the Korea Institute of Police Technology (KIPoT). - Developing deep learning techniques for detecting and identifying illicit drug advertisements on social media, dark web, and Telegram, covering drug slang database construction, multimodal advertisement classification, and adaptive handling of evolving slang and obfuscation patterns.

- *2026.01 - Present*, **Attack Scenario Analysis and Hybrid RAG Knowledge Base Construction Based on MITRE ATT&CK and D3FEND**, part of the *Development of an AI White-Hacker-based Zero-Hacking System* program led by the Korea Institute of Science and Technology Information (KISTI), in collaboration with KAIST. - Designing and building the ATT&CK/D3FEND-grounded knowledge database that enables an LLM-based attack profiler to reason over multi-stage intrusion scenarios.

- *2025.03 - 2025.12*, **Development of Cyber Security Regulation Technologies for Programmable Logic Devices in the Development Phase of New Nuclear Reactors**, funded by Korea Foundation of Nuclear Safety (KoFONS). - Analyzed the FPGA development lifecycle, existing nuclear safety regulatory requirements, and known security vulnerabilities to derive development-phase cybersecurity requirements.

- *2024.07 - 2024.12*, **Analysis of Security Evaluation Techniques for Boundary Protection to Support Defense-in-Depth Strategies in Nuclear Facilities**, funded by the Korea Institute of Nuclear Nonproliferation and Control (KINAC). - Surveyed boundary protection technologies applied to essential digital assets in nuclear facilities, developed security inspection procedures, and proposed regulatory application measures supporting the revision of the KINAC/RS-015 inspection and audit guideline.

<!-- - *2025.03 - 2025.12*, **	Development of cyber security regulation technologies for programmable logic devices in the development phase of new nuclear reactors** — one-line description.
  [[GitHub]](https://github.com/...){:target="_blank" rel="noopener"} -->



# 📚 Teaching Experience

- *2026 Fall*, **Machine Learning**, Teaching Assistant, Sungkyunkwan University.

- *2026 Fall*, **Derivatives**, Teaching Assistant, Sungkyunkwan University.

- *2026 Spring*, **Introduction to Data Analysis and AI**, Teaching Assistant, Sungkyunkwan University.

- *2024 Spring - 2025 Fall*, **AI Basics & Uses**, Teaching Assistant, Sungkyunkwan University. - Six semesters: 2024 Spring, Summer, Fall, and Winter; 2025 Spring and Fall.

- *2024.03 - 2024.12*, **R&E (Research and Education) Program**, Seoul Science High School. - Designed and led the R&E program organized by Seoul Science High School, mentoring the student project *Developing a Spam Detection Model Specifically Designed for Adolescents*.

- *2023 Fall*, **Problem Solving and Algorithm**, Teaching Assistant, Sungkyunkwan University.

- *2023.04*, **Teaching Practicum Student**, Sunae High School.


# 🎖 Honors and Awards
- *2026.03* Graduate School Scholarship Type 2 (half-tuition, worth ≈ $11,500), Sungkyunkwan University, Korea.
- *2024.12* Best Student Paper Award/ISOFIC 2024, "Procedures for Developing Secure FPGA in Nuclear Power Plants", Korea 
- *2024.03* ICT Innovation Human Resources Development Scholarship (full-tuition, worth ≈ $23,000), Ministry of Science and ICT (MSIT) / IITP, Korea.
- *2023.11* Grand Award/Gyeonggi-do Metaverse Ideathon, Ministry of Science and ICT, Korea. 
- *2022.09* Bronze Award/2022 2nd SKKU College of Education AI Education Hackathon, SKKU, Korea. 
- *2021.12* Silver Award/College of Education AI Education Capstone Design Contest, SKKU, Korea. 
- *2021.10* Encouragement Award/2021 Capstone Design and Idea Hackathon Contest, Korea Internet & Security Agency, Korea.


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
