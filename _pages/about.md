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

Hello! I am **Zesong Jiang**, a Ph.D. student in the School of Electrical, Computer and Energy Engineering (ECEE) at **Arizona State University**, advised by [**Prof. Jeff Zhang**](https://search.asu.edu/profile/4346755). I received my M.S. from the **University of Science and Technology of China (USTC)** in 2025, and my B.S. from **Jilin University** in 2022.

My research focuses on **AI for Chip Design** and **Computer Architecture**. I am also currently a Research Intern at **IBM Silicon Valley Lab**.

<span class="tag">LLM-based Hardware Architecture Generation</span> <span class="tag">LLM for Chip Physical Design</span> <span class="tag">Reconfigurable Accelerators (CGRA)</span> <span class="tag">HW/SW Co-Design for Efficient AI</span>

Always happy to discuss research and collaborations — reach me at <a href="mailto:zjian137@asu.edu">zjian137@asu.edu</a>.

# 🔥 News
- *2026.05*: &nbsp;🔬 Joined **IBM Silicon Valley Lab** as a Research Intern.
- *2026.05*: &nbsp;📄 **MACO** and **CAPO** accepted (see [Publications](#-publications)).
- *2026.03*: &nbsp;🎤 Gave an invited talk on **MACO** at the **NSF Workshop on Agents for Chip Design Automation** — received the **Student Travel Award**.
- *2025.08*: &nbsp;🚀 Started my **Ph.D.** at **Arizona State University**.
- *2025.06*: &nbsp;🎓 Graduated from **USTC** as **Outstanding Graduate of Anhui Province**.

# 📝 Publications

<div class="pub-card">
<div class="pub-thumb"><a href="images/maco.png" title="Click to enlarge"><img src="images/maco.png" alt="MACO"></a></div>
<div class="pub-body" markdown="1">
**MACO: A Multi-Agent LLM Framework for Automated CGRA Hardware/Software Co-Design** <span class="pub-venue">ICLAD 2026</span>
<span class="pub-authors"><u>Zesong Jiang</u>, Yuqi Sun, Qing Zhong, Mahathi Krishna, Deepak Patil, Cheng Tan, Jeff Zhang</span>
<span class="pub-intro">Specialized LLM agents co-design CGRA hardware and software end-to-end (OpenCGRA + commercial EDA, ASAP7 7nm), <span class="pub-note">−25.9% power and +20.0% performance</span> over human experts and prior LLM methods. Long paper (20% acceptance).</span>
</div>
</div>

<div class="pub-card">
<div class="pub-thumb"><a href="images/capo.png" title="Click to enlarge"><img src="images/capo.png" alt="CAPO"></a></div>
<div class="pub-body" markdown="1">
**CAPO: Certification-Guided Agentic Workflow for Physical Design Parameter Optimization** <span class="pub-venue">GLSVLSI 2026</span>
<span class="pub-authors"><u>Zesong Jiang</u>, Qihang Wu, Bing-yue Wu, Jeff Zhang</span>
<span class="pub-intro">An agentic workflow that optimizes physical-design parameters, using certification/verification feedback to steer the search toward better PPA.</span>
</div>
</div>

<div class="pub-card">
<div class="pub-thumb"><img src="images/publications/iicpilot.svg" alt="IICPilot"></div>
<div class="pub-body" markdown="1">
**IICPilot: An Intelligent Integrated Circuit Backend Design Framework Using Open EDA** <span class="pub-venue">arXiv 2024</span>
<span class="pub-authors"><u>Zesong Jiang</u>, Qing Zhang, Cheng Liu, Long Cheng, Huawei Li, Xiaowei Li</span>
<span class="pub-intro">A multi-agent LLM framework that automates IC backend design on open-source EDA, exploring design parameters inside resource-optimized containers.</span>
<span class="pub-links">[arXiv](https://arxiv.org/abs/2407.12576)</span>
</div>
</div>

<div class="pub-card">
<div class="pub-thumb"><img src="images/publications/cryofpga.svg" alt="Cryogenic FPGA study"></div>
<div class="pub-body" markdown="1">
**Break the Cold Barrier: An In-Depth Study on FPGA Performance and Design Optimization at Cryogenic Temperature** <span class="pub-venue">Integrated Circuits and Systems 2024</span>
<span class="pub-authors"><u>Zesong Jiang</u>, Muhan Zhang, Qingyun Liu</span>
<span class="pub-intro">An in-depth study of FPGA performance at cryogenic temperature, with design optimizations for reliable cold operation.</span>
<span class="pub-links">[IEEE](https://ieeexplore.ieee.org/document/10755040)</span>
</div>
</div>

<div class="pub-card">
<div class="pub-thumb"><img src="images/publications/sigdla.svg" alt="SigDLA"></div>
<div class="pub-body" markdown="1">
**SigDLA: A Deep Learning Accelerator Extension for Signal Processing** <span class="pub-venue">arXiv 2024</span>
<span class="pub-authors">Fangfa Fu, Wenyu Zhang, <u>Zesong Jiang</u>, Zhiyu Zhu, Guoyu Li, Bing Yang, Cheng Liu, Liyi Xiao, Jinxiang Wang, Huawei Li, et al.</span>
<span class="pub-intro">A deep-learning accelerator extension that unifies signal-processing and DL workloads by extending NVDLA.</span>
<span class="pub-links">[arXiv](https://arxiv.org/abs/2407.12565)</span>
</div>
</div>

<div class="pub-card">
<div class="pub-thumb"><img src="images/publications/lfmri.svg" alt="Low-Field MRI platform"></div>
<div class="pub-body" markdown="1">
**A Low-Field Magnetic Resonance Signal Transmission and Reception Processing Platform** <span class="pub-venue">ICICSP 2024</span>
<span class="pub-authors"><u>Zesong Jiang</u>, Muhan Zhang, Qing Zhang, Yuchong Xie</span>
<span class="pub-intro">A signal transmission and reception processing platform for low-field magnetic resonance imaging.</span>
<span class="pub-links">[arXiv](https://arxiv.org/abs/2409.08671)</span>
</div>
</div>

<div class="pub-card">
<div class="pub-thumb"><img src="images/publications/piezo.svg" alt="Biodegradable piezoelectric scaffold"></div>
<div class="pub-body" markdown="1">
**A Biodegradable Piezoelectric Scaffold Promotes Spinal Cord Injury Nerve Regeneration** <span class="pub-venue">Nano Energy 2024</span>
<span class="pub-authors">Jinjing Zhang, Qiong Wang, Xiaoyi Tang, Mingyang Chai, Nuo Liu, <u>Zesong Jiang</u>, Xingjiang Li, Ping Chen</span>
<span class="pub-intro">A biodegradable piezoelectric scaffold that promotes nerve regeneration after spinal cord injury (co-authored). <em>Nano Energy</em>, vol. 132, p. 110382.</span>
</div>
</div>

# 💻 Experience

<div class="exp-item" markdown="1">
**IBM Silicon Valley Lab**, San Jose, CA, USA <span class="exp-date">May 2026 – Present</span>
<span class="exp-role">Research Intern — building a reliable agentic workflow for long-horizon physical design, optimizing chip PPA and reducing manual design effort.</span>
</div>

<div class="exp-item" markdown="1">
**Arizona State University**, Tempe, AZ, USA <span class="exp-date">Aug 2025 – Present</span>
<span class="exp-role">Graduate Research Assistant — NAIRR Pilot (with Microsoft): an end-to-end automated LLM-based multi-agent RTL workflow on Microsoft Discovery; **MACO** multi-agent CGRA co-design; **X-Stream** algorithm–hardware co-design for explainable AI.</span>
</div>

<div class="exp-item" markdown="1">
**Institute of Computing Technology, CAS**, Beijing, China <span class="exp-date">Aug 2023 – Sep 2024</span>
<span class="exp-role">Research Intern — **IICPilot**, an LLM-based multi-agent IC backend design automation platform; and a programmable data-reordering deep learning accelerator extending NVDLA for unified signal and DL workloads.</span>
</div>

<div class="exp-item" markdown="1">
**SOPHGO**, Beijing, China <span class="exp-date">Dec 2022 – Feb 2023</span>
<span class="exp-role">IC Front-end Verification Intern — built and maintained verification environments and participated in front-end functional validation of the Athena-2 SoC.</span>
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
