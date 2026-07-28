---
layout: default
title: Aboutme
description: Biography, education, research experience, honors, and skills of Minhyuk Jo.
permalink: /aboutme/
---

# About Me

I am an **M.S. student in Information Security at [Korea University](https://www.korea.edu/)** and a researcher at the [Digital Forensic Research Center (DFRC)](https://dfrc.korea.ac.kr/), advised by Prof. Jungheum Park. My work focuses on building trustworthy methods for acquiring, preserving, and interpreting digital evidence across modern computing environments.

My research interests include **digital forensics, AI forensics, incident response, and anti-forensics**. I am particularly interested in forensic methods for on-device AI models, drones, mobile platforms, and systems where timestamps or logs may be manipulated. My goal is to make digital investigations more reliable even when evidence has been altered or deliberately concealed.

Before joining Korea University, I studied Mobile Systems Engineering at [Dankook University](https://www.dankook.ac.kr/) and worked as a research intern on digital and vehicle forensics. I also completed WhiteHat School's information-security program and served as a network operations and maintenance specialist in the Republic of Korea Army. My scholarly publications and patent records appear under the names **Minhyuk Cho** and **Min Hyuk Cho**.

## Education {#education}

<article class="entry">
  <div class="entry-heading">
    <h3>Korea University</h3>
    <span class="entry-date">Mar. 2026 – Present</span>
  </div>
  <p class="entry-subtitle">M.S. in Information Security · Seoul, South Korea</p>
  <ul>
    <li><strong>GPA: 4.5 / 4.5</strong></li>
    <li>Advisor: Prof. Jungheum Park</li>
    <li>Digital Forensic Research Center (DFRC)</li>
  </ul>
</article>

<article class="entry">
  <div class="entry-heading">
    <h3>Dankook University</h3>
    <span class="entry-date">Mar. 2020 – Feb. 2026</span>
  </div>
  <p class="entry-subtitle">B.S. in Mobile Systems Engineering · Yongin, South Korea</p>
  <ul>
    <li><strong>GPA: 4.25 / 4.25</strong> · <strong>Major GPA: 4.25 / 4.25</strong></li>
    <li><strong>Graduated first in class</strong></li>
    <li>Military leave of absence during 2021–2023</li>
  </ul>
</article>

## Research Experience

<article class="entry">
  <div class="entry-heading">
    <h3>M.S. Researcher</h3>
    <span class="entry-date">Mar. 2026 – Present</span>
  </div>
  <p class="entry-subtitle">Digital Forensic Research Center, Korea University</p>
  <p>Research in <strong>digital forensics, AI forensics, and drone forensics</strong>.</p>
</article>

<article class="entry">
  <div class="entry-heading">
    <h3>Research Intern</h3>
    <span class="entry-date">Mar. 2024 – Jun. 2025</span>
  </div>
  <p class="entry-subtitle">Dankook University · Advisor: Prof. Seong-Je Cho</p>
  <p>Research in <strong>digital forensics and vehicle forensics</strong>.</p>
</article>

### Selected Research Projects {#selected-research-projects}

<ul class="detail-list project-list">
  <li>
    <strong>Development of Forensic Technologies for On-Device AI Models</strong>
    <span>Apr. 2026 – Present · Funded by the Korea Institute of Police Technology (KIPoT)</span>
  </li>
  <li>
    <strong>Comprehensive Research to Advance an Industry–Academia–Research–Government Collaboration Ecosystem in Digital Forensics</strong>
    <span>Apr. 2026 – Present · Funded by the Supreme Prosecutors' Office</span>
  </li>
  <li>
    <strong>Phase 4 BK21 Government-Funded Information Security Education and Research Group</strong>
    <span>May 2024 – Present · Funded by the Ministry of Education</span>
  </li>
  <li>
    <strong>Intelligent Building Energy and Environment Integrated Management System (iBEEMS)</strong>
    <span>Mar. 2025 – Jun. 2025 · Funded by KETEP</span>
  </li>
  <li>
    <strong>Collection and Integrated Analysis of In-Vehicle and External Automotive Artifacts</strong>
    <span>Aug. 2024 – Dec. 2024 · Funded by IITP</span>
  </li>
  <li>
    <strong>Mobile Platform–Based Vehicle Forensics Framework</strong>
    <span>May 2024 – Feb. 2025 · Funded by the National Research Foundation of Korea</span>
  </li>
</ul>

## Additional Experience {#additional-experience}

<article class="entry">
  <div class="entry-heading">
    <h3>WhiteHat School, 3rd Cohort</h3>
    <span class="entry-date">Mar. 2025 – Sep. 2025</span>
  </div>
  <p>Completed core and advanced information-security training and implemented a log-based intrusion detection system for an AWS cloud environment.</p>
</article>

<article class="entry">
  <div class="entry-heading">
    <h3>Network Operations and Maintenance Specialist</h3>
    <span class="entry-date">Aug. 2021 – Feb. 2023</span>
  </div>
  <p class="entry-subtitle">Republic of Korea Army</p>
  <p>Completed full-term military service and was honorably discharged as a Sergeant.</p>
</article>

## Honors and Awards

<div class="summary-columns">
  <section aria-labelledby="about-awards">
    <h3 id="about-awards">Awards</h3>
    <ul class="compact-list">
    {% for item in site.data.honors.awards %}
      <li><strong>{{ item.title }}</strong> · {{ item.awarded_by }} · {{ item.date }}</li>
    {% endfor %}
    </ul>
  </section>

  <section aria-labelledby="about-scholarships">
    <h3 id="about-scholarships">Scholarships</h3>
    <ul class="compact-list">
    {% for item in site.data.honors.scholarships %}
      <li><strong>{{ item.title }}</strong> · {{ item.awarded_by }} · {{ item.date }}</li>
    {% endfor %}
    </ul>
  </section>
</div>

<p><a class="button-link" href="{{ '/honors/' | relative_url }}">View full honors and awards</a></p>

## Skills

<h3>Languages</h3>
<ul class="tag-list" role="list">
  <li>Korean</li>
  <li>English</li>
</ul>

<h3>Programming</h3>
<ul class="tag-list" role="list">
  <li>C/C++</li>
  <li>Python</li>
  <li>Java</li>
  <li>Assembly</li>
  <li>LaTeX</li>
</ul>

<h3>Forensics &amp; Systems Tools</h3>
<ul class="tag-list" role="list">
  <li>FTK Imager</li>
  <li>Autopsy</li>
  <li>Wireshark</li>
  <li>GDB</li>
  <li>Elftool</li>
  <li>ADB</li>
  <li>EnCase</li>
  <li>Axiom</li>
  <li>MD-Series</li>
</ul>

<h3>Certifications &amp; Examinations</h3>
<ul>
  <li><strong>AWS Certified Cloud Practitioner</strong> (CLF-C02)</li>
  <li><strong>Digital Forensics Specialist Level 2</strong> — written examination passed</li>
  <li><strong>Linux Master Level 2</strong></li>
  <li><strong>Craftsman Information Processing</strong></li>
</ul>
