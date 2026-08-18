---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Contact: abdullahiusmanidris@outlook.com](mailto:abdullahiusmanidris@outlook.com) &middot; Sakarya, Türkiye &middot; [Google Scholar](https://scholar.google.com/citations?user=3uQ9DN4AAAAJ&hl=en) &middot; [LinkedIn](https://www.linkedin.com/in/abdullahi-usman-idris/) &middot; [Download CV (PDF)]({{ base_path }}/files/Abdullahi_Idris_Usman_CV.pdf)

Research Interests
======
Non-linear solid and structural mechanics; finite element modelling under compressive or impact loading conditions; crashworthiness and energy-absorbing potential of lattice and composite structures; additive manufacturing of architected materials; experimental–numerical correlations and mechanical characterization.

Education
======
* **M.Sc. in Mechanical Design and Manufacturing**, Sakarya University, Sakarya, Türkiye — *Sep 2025 – Jul 2027 (Expected)*
  * CGPA: 3.5/4.0 (Top 5%) &middot; Distinction
  * Thesis: *Investigation of the Impact Resistance of Vacuum-Formed and PU Resin Foam-Reinforced 3D-Printed Chain-Fabrics*
  * Supervisor: Assoc. Prof. Dr. Muhammet Muaz Yalçın

* **Exchange Student, Mechanical Engineering (Erasmus+)**, VŠB – Technical University of Ostrava, Ostrava, Czech Republic — *Feb 2027 – May 2027 (Expected)*
  * Erasmus+ Scholar

* **Turkish Language Preparation Programme**, Sakarya University TÖMER — *Oct 2024 – Aug 2025*
  * CEFR Level: C1 &middot; Completed intensive Turkish-language training to prepare for graduate study in Türkiye

* **B.Eng. in Mechanical Engineering**, Abubakar Tafawa Balewa University (ATBU), Bauchi, Nigeria — *Mar 2017 – Sep 2023*
  * CGPA: 4.5/5.0 (Scholaro-converted: 3.7/4.0, Top 1%) &middot; First Class Honors
  * Thesis: *Development and Characterization of Doum Palm Shell–Recycled LDPE Composite for Crash Helmet Applications*

Research and Teaching Experience
======
* **M.Sc. Researcher — Structural Mechanics & Additive Manufacturing**, Sakarya University, MMY Structural Mechanics & AM Research Lab, Sakarya, Türkiye — *Sep 2025 – Present*
  * Develop finite-element models in LS-DYNA to predict quasi-static and/or dynamic deformation, force–displacement response, absorbed energy, and failure-critical regions
  * Investigate the impact response of vacuum-formed and PU-resin-foam-reinforced 3D-printed chain-fabric structures for lightweight energy-absorption applications
  * Fabricate polymer specimens by FDM and conduct impact tests; validate numerical predictions against experimental force–displacement and deformation data
  * Designed convex and concave lattice structure topologies as an extension to conventional lattice structures for energy-absorption applications
  * Reviewed and synthesized literature on functionally graded lattice structures, compiled into a review manuscript

* **Graduate Assistant — Department of Mechanical and Production Engineering**, Kaduna Polytechnic (National Youth Service Corps), Kaduna, Nigeria — *Nov 2023 – Oct 2024*
  * Assisted in conducting laboratory sessions and workshop training for students
  * Provided support to lecturers with course preparation, grading, and classroom activities

* **Undergraduate Researcher — Sustainable Composite Materials**, Abubakar Tafawa Balewa University (ATBU), Bauchi, Nigeria — *Nov 2022 – Aug 2023*
  * Led a 9-month experimental programme developing natural fiber-recycled polymer composites, testing 5 formulations and achieving 66.67 kJ/m² peak impact strength

* **Tutor — Department of Mechanical and Production Engineering**, Abubakar Tafawa Balewa University (ATBU), Bauchi, Nigeria — *Nov 2022 – Aug 2023*
  * Taught Heat Transfer, Strength of Materials III, Machine Design II, and Thermodynamics to course mates

Professional and Industrial Experience
======
* **Summer Mechanical Engineering Intern**, Sentürkler Makina, Sakarya, Türkiye — *Aug 2025 – Sep 2025*
  * Operated CNC machines with 10–15 daily tool changes, inspected parts to ±0.02 mm using coordinate measurement, and updated 3+ SolidWorks drawings, improving shop floor documentation and traceability

* **CAD & Simulation Analyst**, Etona Engineering Services, Remote — *Jul 2024 – Jan 2025*
  * Conducted static and dynamic FEA on 5+ engineering structures (ANSYS Mechanical), identifying failure-critical zones; performed modal and harmonic analysis on 2+ rotating systems

* **Mechanical Engineering Intern**, Defense Industries Corporation of Nigeria, Kaduna, Nigeria — *Jun 2022 – Nov 2022*
  * Characterized 12+ metallic and ammunition samples using Spectro Maxx OES, Rockwell/Vickers hardness testing, and optical microscopy, contributing to a 15% reduction in test turnaround time

* **Mechanical Engineering Intern**, Peugeot Automobile Nigeria (PAN), Kaduna, Nigeria — *Feb 2020 – Mar 2020*
  * Supported the assembly of a 19-seat bus engine and Peugeot 301 axles, and MIG-welded stretcher rails for ambulance vehicles, gaining hands-on experience in automotive assembly and fabrication

Publications
======
{% for category in site.publication_category %}
  {% assign cat_pubs = site.publications | where: "category", category[0] | reverse %}
  {% if cat_pubs.size > 0 %}
### {{ category[1].title }}
<ul>
    {% for post in cat_pubs %}
      {% include archive-single-cv.html %}
    {% endfor %}
</ul>
  {% endif %}
{% endfor %}

Selected Engineering Projects
======
See the [Portfolio](/portfolio/) page for full write-ups.
* **TEKNOFEST Unmanned Surface Vehicle** — Design & Additive Manufacturing Lead, ADASTRA, Sakarya University — *Feb 2026 – Present*
* **TEKNOFEST Roboligue** — Mechanical Design & Prototyping Team Member, ADASTRA, Sakarya University — *April 2026 – Present*

Technical Skills
======
* **FEA / Simulation:** ANSYS Mechanical, LS-DYNA (Explicit Dynamics for Impact & Crashworthiness Simulation)
* **CAD / Design:** SolidWorks (CSWA & CSWP certified), NX Siemens
* **Additive Manufacturing:** FDM process parameters, TPMS/BCC/FCC lattice topology design, architected material optimization
* **Programming:** MATLAB, Python
* **Research Tools:** LaTeX, Zotero, MS Office Suite, technical report writing, systematic literature review
* **Languages:** English (C1), Turkish (C1), Hausa (Native), Arabic (A2)

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Selected Honors, Awards and Scholarships
======
* Türkiye Bursları (YTB) Scholarship — 2024
* Boston University College of Engineering Graduate Scholarship — 2024
* EducationUSA Opportunity Funds Program — 2024
* Vice-Chancellor's List — 2023
* Best Graduating Student — Prof. Adisa Bello's Award for Best Graduating Student — 2023
* Dean's List (2017–2022, 4 consecutive years) — 2018
* Royal Academy of Engineering — Forging Africa's Future Mechanical Engineers (FAFME) Programme Finalist (Top team from 43 across Nigeria) — 2020
* Chevron JV Scholarship — 2019
* Agbami Medical & Engineering Professional Scholarship — 2018

Selected Professional Development and Certifications
======
* Additive Manufacturing Specialization — Arizona State University — 2024
* Digital Manufacturing & Design Technology Specialization — University of Buffalo — 2024
* MATLAB Programming for Engineers Specialization — Vanderbilt University — 2024
* Python for Everybody — University of Michigan — 2024

Conferences, Seminars and Workshops
======
* Harnessing the Power of Industry 4.0: Transforming Manufacturing with Smart Technologies — EIT Webinar (2024)
* Article Publication in Reputable Journals Workshop — Maryam Abacha American University of Nigeria (2024)
* Nigerian Institution of Mechanical Engineers (NIMechE) 34th Annual International Conference (2021)

Service and leadership
======
* **Mentor**, Northern Elites Scholars Forum — *Jun 2021 – Present*
* **Founder & Technical Lead**, ATBU CAD Club — *Feb 2021 – Sep 2023*
* **President**, NIMechE ATBU Student Branch — *Nov 2019 – Feb 2021*

Professional Membership and Affiliations
======
* American Society of Mechanical Engineers (ASME)
* Nigerian Society of Engineers (NSE)
* Nigerian Institution of Mechanical Engineers (NIMechE)
* International Association of Engineers (IAENG)
* Institution of Mechanical Engineers (IMechE)
