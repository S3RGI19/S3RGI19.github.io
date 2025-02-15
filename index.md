---
layout: home
title: "Sergi | Robotics, AI, Computer Vision"
markdown: kramdown
---

{% capture content %}
## <span id="about">About Me</span>  
I am an **MSc student in Robotics, Systems and Control at ETH Zürich**, specializing in **perception, computer vision, and AI**. My passion lies in developing **autonomous mobile robots** that can **navigate and solve complex challenges in the real world**. I have worked on **robot perception and state estimation**, including research in **event-based vision** and **autonomous systems**, always striving to build **intelligent, adaptable robots** that **understand their environment and make real-time decisions**.  

Excited by the potential of **robotics to reshape industries and human interaction**, I am committed to **pushing the boundaries of autonomy** to create **robotic systems that can operate reliably**.  

---

## <span id="skills">Skills</span>  
- **Programming**: Python (very experienced), MATLAB (very experienced), C/C++ (good), VHDL (very good).  
- **Libraries & Frameworks**: ROS2, OpenCV, PyTorch, NumPy, Pandas.  
- **Software & Tools**: Git, Docker, LaTeX, Conda, VSCode, Simulink, KiCad, Fusion360, LabView, Quartus, Vivado, Orcad Capture, PSpice.  

---

## <span id="projects">Research Projects</span>  

### **Gaussian Belief Propagation for VSLAM (ETH Zürich, 2025)** - *Work In Progress*
Applying **Gaussian Belief Propagation (GBP) to distributed continuous-time Visual SLAM**, improving probabilistic inference efficiency for large-scale, real-time localization and mapping. This method is particularly useful for **complex, dynamic robotic environments**.

### **Event-Based Egomotion Estimation (IRI-CSIC, 2023-2024)**  
Developed a **model-based method for egomotion estimation** using an event camera. The approach consisted of **normal flow estimation, inverse depth estimation, and a robust linear solver**, aiming for **efficient state estimation in resource-constrained environments**. 

Read more [(UPCommons)](https://upcommons.upc.edu/handle/2117/422144) or download [pdf](/assets/pdf/Event-based_egomotion_estimation_Sergi_Sanchez_Orvay_TFG.pdf).


---

## Work Experience  
<div class="work-entry">
    <div class="work-left">
        <img src="/assets/img/iri-csic-logo.png" alt="IRI-CSIC Logo">
        <div class="work-info">
            <h3>
                Robotics Research Intern, <span class="company-name">IRI-CSIC</span>
                <a href="https://www.iri.upc.edu/" target="_blank" class="company-link">(iri.upc.edu)</a>
            </h3>
        </div>
    </div>
    <div class="work-right">
        <span class="work-dates">Sept. 2023 - July 2024</span>
    </div>
</div>
<ul>
    <li>Developed <strong>event-based optical flow estimation</strong> methods.</li>
    <li>Implemented a <strong>corner detection algorithm</strong> for event cameras.</li>
    <li>Conducted research on <strong>event-based egomotion estimation</strong>, leveraging <strong>geometric models and optimization techniques</strong>.</li>
</ul>

<div class="work-entry">
    <div class="work-left">
        <img src="/assets/img/upc-logo.png" alt="UPC Logo">
        <div class="work-info">
            <h3>
                Research Assistant, <span class="company-name">Universitat Politècnica de Catalunya</span>
                <a href="https://www.upc.edu/en?set_language=en" target="_blank" class="company-link">(upc.edu)</a>
            </h3>
        </div>
    </div>
    <div class="work-right">
        <span class="work-dates">Nov. 2022 - March 2023</span>
    </div>
</div>
<ul>
    <li>Collaborated on an <strong>Electrostatic Dust Shield (EDS) system</strong> with the MNT-MarsLab research group.</li>
    <li>Designed and simulated <strong>the EDS system using CAD tools</strong>.</li>
    <li>Designed, assembled, and tested <strong>PCBs for the EDS system</strong>, achieving successful results.</li>
</ul>

---

## Education  
<div class="education-entry">
    <div class="education-left">
        <img src="/assets/img/eth-logo.png" alt="ETH Zürich Logo">
        <div class="education-info">
            <h3>
                MSc in Robotics, Systems and Control, <span class="university-name">ETH Zürich</span>
                <a href="https://ethz.ch/en.html" target="_blank" class="university-link">(ethz.ch)</a>
            </h3>
        </div>
    </div>
    <div class="education-right">
        <span class="education-dates">2024 - Present</span>
    </div>
</div>
<ul>
    <li><strong>Fall 2024 courses:</strong> Probabilistic AI, Robot Dynamics, Vision Algorithms for Mobile Robotics, Dynamic Programming & Optimal Control, Planning & Decision-Making for Autonomous Robots.</li>
    <li><strong>Spring 2025 courses:</strong> Recursive Estimation, 3D Vision, Computational Control, Semester Project.</li>
</ul>

<div class="education-entry">
    <div class="education-left">
        <img src="/assets/img/upc-logo.png" alt="UPC Logo">
        <div class="education-info">
            <h3>
                BSc in Electronic Engineering and Telecommunications, <span class="university-name">Universitat Politècnica de Catalunya</span>
                <a href="https://www.upc.edu/en?set_language=en" target="_blank" class="university-link">(upc.edu)</a>
            </h3>
        </div>
    </div>
    <div class="education-right">
        <span class="education-dates">2020 - 2024</span>
    </div>
</div>
<ul>
    <li><strong>Thesis:</strong> Event-Based Egomotion Estimation (9.8/10).</li>
    <li><strong>Grade:</strong> 9/10, Honors in <strong>30%+</strong> courses.</li>
    <li><strong>Best student award</strong> in the initial phase of the degree (2020-21).</li>
</ul>



---

## <span id="contact"> Contact</span>  
<div class="contact-container">
    <p>If you'd like to connect, feel free to reach out:</p>
    
    <ul class="contact-list">
        <li>
            <img src="/assets/img/email.svg" class="contact-icon" alt="Email Icon">
            <strong>Email:</strong> 
            <a href="mailto:sergi.sanchez.orvay@gmail.com">sergi.sanchez.orvay@gmail.com</a>
        </li>
        <li>
            <img src="/assets/img/linkedin-black.svg" class="contact-icon" alt="LinkedIn Icon">
            <strong>LinkedIn:</strong> 
            <a href="https://www.linkedin.com/in/sergisanchezz" target="_blank">Sergi Sánchez Orvay</a>
        </li>
    </ul>
</div>


{% endcapture %}

<div class="container">
{{ content | markdownify }}
</div>
