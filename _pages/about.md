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

I am **Zesong Jiang**, a Ph.D. student in Electrical, Computer and Energy Engineering at **Arizona State University**, advised by [**Prof. Jeff Zhang**](https://search.asu.edu/profile/4346755) and working closely with [**Cheng Tan**](https://tancheng.github.io/). I received my M.S. from the **University of Science and Technology of China (USTC)** in 2025 and my B.S. from **Jilin University** in 2022.

My research focuses on **AI for Chip Design** and **Computer Architecture**, particularly **LLM-based Design Automation**, **Reconfigurable Accelerators (CGRA)**, and **Hardware/Software Co-Design**. I am currently a Research Intern at **IBM Silicon Valley Lab**.

<!-- <span class="tag">LLM-based Hardware Architecture Generation</span> <span class="tag">LLM for Chip Physical Design</span> <span class="tag">Reconfigurable Accelerators (CGRA)</span> <span class="tag">HW/SW Co-Design for Efficient AI</span> -->

I welcome research discussions and collaborations. You can reach me at <a href="mailto:zjian137@asu.edu">zjian137@asu.edu</a>.

# 🔥 News
- <span class="news-date">[May. 2026]</span> <span class="news-type news-type--position">[Position]</span> Joined **IBM Silicon Valley Lab** as a Research Intern.
- <span class="news-date">[May. 2026]</span> <span class="news-type news-type--publication">[Publication]</span> Our work **"MACO: A Multi-Agent LLM Framework for Automated CGRA Hardware/Software Co-Design"** was accepted to **ICLAD 2026**.
- <span class="news-date">[May. 2026]</span> <span class="news-type news-type--publication">[Publication]</span> Our work **"CAPO: Certification-Guided Agentic Workflow for Physical Design Parameter Optimization"** was accepted to **GLSVLSI 2026**.
- <span class="news-date">[Mar. 2026]</span> <span class="news-type news-type--talk">[Invited Talk]</span> Presented **MACO** at the **NSF Workshop on Agents for Chip Design Automation**.
- <span class="news-date">[Aug. 2025]</span> <span class="news-type news-type--education">[Education]</span> Began my Ph.D. at **Arizona State University**.
- <span class="news-date">[Jun. 2025]</span> <span class="news-type news-type--honor">[Honor]</span> Named an **Outstanding Graduate of Anhui Province** upon graduating from **USTC**.

# 📝 Publications

<div class="pub-card">
<div class="pub-thumb"><a href="images/maco.png" title="Click to enlarge"><img src="images/maco.png" alt="MACO"></a></div>
<div class="pub-body" markdown="1">
**MACO: A Multi-Agent LLM Framework for Automated CGRA Hardware/Software Co-Design** <span class="pub-venue">ICLAD 2026</span>
<span class="pub-authors"><u>Zesong Jiang</u>, Yuqi Sun, Qing Zhong, Mahathi Krishna, Deepak Patil, Cheng Tan, Jeff Zhang</span>
<span class="pub-intro">Automates CGRA hardware/software co-design through four collaborative stages: design generation, error correction, best-design selection, and evaluation with feedback. Evaluation reports 25.9% lower power, 20.0% higher performance, and 5× faster design-space search, with final designs validated through a complete 7 nm ASIC flow.</span>
<span class="pub-links">[Paper](https://arxiv.org/pdf/2509.13557)</span>
</div>
</div>

<div class="pub-card">
<div class="pub-thumb"><a href="images/capo.png" title="Click to enlarge"><img src="images/capo.png" alt="CAPO"></a></div>
<div class="pub-body" markdown="1">
**CAPO: Certification-Guided Agentic Workflow for Physical Design Parameter Optimization** <span class="pub-venue">GLSVLSI 2026</span>
<span class="pub-authors"><u>Zesong Jiang</u>, Qihang Wu, Bing-yue Wu, Jeff Zhang</span>
<span class="pub-intro">Formulates physical-design optimization as certified trajectory control, combining structured flow-state abstraction, bottleneck-aware planning, and transition certification to reject harmful actions and support recovery across coupled design stages.</span>
<span class="pub-links">[Paper](https://doi.org/10.1145/3787109.3816403)</span>
</div>
</div>

<div class="pub-card">
<div class="pub-thumb"><a href="images/publications/iicpilot.png" title="View full figure"><img src="images/publications/iicpilot.png" alt="IICPilot multi-agent backend design framework"></a></div>
<div class="pub-body" markdown="1">
**IICPilot: An Intelligent Integrated Circuit Backend Design Framework Using Open EDA** <span class="pub-venue">Preprint 2024</span>
<span class="pub-authors"><u>Zesong Jiang</u>, Qing Zhang, Cheng Liu, Long Cheng, Huawei Li, Xiaowei Li</span>
<span class="pub-intro">Automates backend-design script generation, EDA-tool execution, parameter exploration, container resource allocation, and exception handling through specialized agents and a unified interface for OpenROAD and iEDA.</span>
<span class="pub-links">[Paper](https://arxiv.org/pdf/2407.12576)</span>
</div>
</div>

<div class="pub-card">
<div class="pub-thumb"><img src="images/publications/cryofpga.svg" alt="Cryogenic FPGA study"></div>
<div class="pub-body" markdown="1">
**Break the Cold Barrier: An In-Depth Study on FPGA Performance and Design Optimization at Cryogenic Temperature** <span class="pub-venue">Integrated Circuits and Systems 2024</span>
<span class="pub-authors"><u>Zesong Jiang</u>, Muhan Zhang, Qingyun Liu, Runze Liu</span>
<span class="pub-intro">Characterizes FPGA behavior at cryogenic temperature and uses CryoFPGA-Pilot to explore a 500-point architecture space for low-delay and low-power designs.</span>
<span class="pub-links">[Paper](https://doi.org/10.23919/ICS.2024.3499944)</span>
</div>
</div>

<div class="pub-card">
<div class="pub-thumb"><a href="images/publications/sigdla.png" title="View full figure"><img src="images/publications/sigdla.png" alt="SigDLA accelerator architecture"></a></div>
<div class="pub-body" markdown="1">
**SigDLA: A Deep Learning Accelerator Extension for Signal Processing** <span class="pub-venue">Preprint 2024</span>
<span class="pub-authors">Fangfa Fu, Wenyu Zhang, <u>Zesong Jiang</u>, Zhiyu Zhu, Guoyu Li, Bing Yang, Cheng Liu, Liyi Xiao, Jinxiang Wang, Huawei Li, et al.</span>
<span class="pub-intro">Extends a conventional deep-learning accelerator with programmable data shuffling and a reconfigurable compute array, converting irregular signal-processing patterns into regular operations while preserving deep-learning support.</span>
<span class="pub-links">[Paper](https://arxiv.org/pdf/2407.12565)</span>
</div>
</div>

<div class="pub-card">
<div class="pub-thumb"><a href="images/publications/lfmri.png" title="View full figure"><img src="images/publications/lfmri.png" alt="Eight-channel low-field MRI signal processing board"></a></div>
<div class="pub-body" markdown="1">
**A Low-Field Magnetic Resonance Signal Transmission and Reception Processing Platform** <span class="pub-venue">ICICSP 2024</span>
<span class="pub-authors"><u>Zesong Jiang</u>, Muhan Zhang, Qing Zhang, Yuchong Xie</span>
<span class="pub-intro">Implements low-field MRI transmission and reception on an FPGA: direct digital synthesis generates adjustable RF pulses, while digital downconversion and CIC/FIR filters recover baseband signals.</span>
<span class="pub-links">[Paper](https://arxiv.org/pdf/2409.08671)</span>
</div>
</div>

<div class="pub-card">
<div class="pub-thumb"><a href="images/publications/piezo.jpg" title="View full figure"><img src="images/publications/piezo.jpg" alt="Piezoelectric scaffold fabrication and spinal cord repair concept"></a></div>
<div class="pub-body" markdown="1">
**A Biodegradable Piezoelectric Scaffold Promotes Spinal Cord Injury Nerve Regeneration** <span class="pub-venue">Nano Energy 2024</span>
<span class="pub-authors">Jinjing Zhang, Qiong Wang, Xiaoyi Tang, Mingyang Chai, Nuo Liu, <u>Zesong Jiang</u>, Xingjiang Li, Ping Chen</span>
<span class="pub-intro">Develops a biodegradable PLLA/KNN@PDA piezoelectric scaffold that provides structural guidance and sustained electrical stimulation, promoting neural growth and functional recovery in a rat spinal-cord injury model.</span>
<span class="pub-links">[Paper](https://doi.org/10.1016/j.nanoen.2024.110382)</span>
</div>
</div>

# 💻 Experience

<div class="exp-item" markdown="1">
**IBM Silicon Valley Lab**, San Jose, CA, USA <span class="exp-date">May 2026 – Present</span>
<span class="exp-role">Research Intern — building a reliable agentic workflow for long-horizon physical design, optimizing chip PPA and reducing manual design effort.</span>
</div>

<div class="exp-item" markdown="1">
**Arizona State University**, Tempe, AZ, USA <span class="exp-date">Aug 2025 – Present</span>
<span class="exp-role">Graduate Research Assistant — LLM for Chip Design; Reconfigurable Accelerator; HW/SW Co-Design.</span>
</div>

# 🎤 Talks
- *2026.03*: &nbsp;**MACO: A Multi-Agent Framework for LLM-Driven Hardware/Software Co-Design**, NSF Workshop on Agents for Chip Design Automation.

# 🎖 Honors and Awards
- *2026*: Student Travel Award, NSF Agents4Chip.
- *2025*: Outstanding Graduate of Anhui Province (12 out of 305).
- *2025*: Outstanding Graduate of the University of Science and Technology of China.
- *2022 – 2024*: Graduate Scholarship — First Prize, University of Science and Technology of China.
- *2018 – 2022*: Undergraduate Scholarship — First Prize, Jilin University.

# 📖 Education
- *2025.08 - Present*, Ph.D. Student, Electrical, Computer and Energy Engineering, **Arizona State University**. Advisor: [Prof. Jeff Zhang](https://search.asu.edu/profile/4346755).
- *2022.09 - 2025.06*, M.S., Electrical & Computer Engineering, **University of Science and Technology of China**. Advisor: Prof. Bensheng Qiu. (GPA 3.87/4.3, Rank 1/27)
- *2018.09 - 2022.06*, B.S., Electrical & Computer Engineering, **Jilin University**. (GPA 3.76/4.0, Rank 21/335)

# 🛠 Skills
- **Programming**: Verilog, C/C++, Python
- **EDA Tools**: Synopsys Design Compiler, OpenROAD, Yosys, VTR, COFFE, Vivado, Quartus, Hspice, Verilator, Altium Designer
- **Tools**: Git, Bash, MATLAB, LaTeX, VS Code
