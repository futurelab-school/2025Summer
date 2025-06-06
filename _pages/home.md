---
layout: splash
title: "2025 Future Labs Summer School"
permalink: /home/

header:
  overlay_color: "#000" #"#5e616c"
  overlay_filter: "0.5"
  overlay_image: /assets/images/igor-omilaev-FHgWFzDDAOs-unsplash.jpg
  actions:
    - label: "Learn More"
      url: /home/#schedule
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Robotic Synthesis Coupled with Machine Learning for Energy Materials."

intro: 
  - title: 'Join us at the Lawrence Berkeley National Lab, CA, from August 13-15 for activities and workshops for applying machine learning to material science'

feature_schedule:
  - image_path: /assets/images/louis-reed-pwcKF7L4-no-unsplash.jpg
    # title: "Day 1"
    # excerpt: "Get hands on experience with robotic synthesis!"
    btn_label: "Day 1"
    btn_class: "btn--primary"
    excerpt: "Get hands-on experience with robotic synthesis!"
    url: /schedule/#day-1-molecular-foundry-summer-school-only

  - image_path: /assets/images/choong-deng-xiang--WXQm_NTK0U-unsplash.jpg
    # title: "Day 2"
    btn_label: "Day 2"
    btn_class: "btn--primary"
    excerpt: "Apply active learning algorithms for material optimization!"
    url: /schedule/#day-2-molecular-foundry---open-to-all-user-meeting-attendees-tutorial
        
  - image_path: /assets/images/ilya-pavlov-OqtafYT5kTw-unsplash.jpg
    #title: "Day 3"
    excerpt: "Join leaders in the field for the AI/ML enabled Materials Development Symposium!"
    btn_label: "Day 3"
    btn_class: "btn--primary"
    url: /schedule/#day-3-open-to-all-user-meeting-attendees-symposium

feature_row3:
  - url: "https://usermeeting2025.foundry.lbl.gov/meeting-registration/"
    btn_label: "Register"
    btn_class: "btn--primary"

portrait_1:
  - title: "Meet our Hosts"
    excerpt: "Meet our hosts, workshop leader and teaching assistants: "
  - image_path: /assets/images/shijing_sun.png
    caption: "Host"
    excerpt: "Dr. Shijing Sun | Univeristy of Washington, Professor"
  - image_path: /assets/images/carolin_sutterfella.png
    caption: "Host"
    excerpt: "Dr. Carolin M. Sutter-Fella | Molecular Foundry, Staff Scientist" 

portrait_2: 
   - image_path: assets/images/maher.png
     caption: "Workshop Lead"
     excerpt: "Dr. Maher Alghalayini | Molecular Foundry, Postdoc"
   - image_path: /assets/images/shuan_cheng.png
     caption: "Workshop Lead"
     excerpt: "Shuan Cheng Univeristy of Washington, PhD Student"
   - image_path: /assets/images/ansuman.png
     caption: "Workshop Lead"
     excerpt: "Ansuman_halder Molecular Foundry, Postdoc"
   - image_path: /assets/images/clara_tamura.png
     caption: "Workshop Lead"
     excerpt: "Clara Tamura Univeristy of Washington, PhD Student" 
   - image_path: /assets/images/abby_hering.png
     caption: "Workshop"
     excerpt: "Abby Hering UC Davis, PhD Student" 
   - image_path: assets/images/rapha_moral.png
     caption: "Workshop"
     excerpt: "Rapha Moral Molecular Foundry, Postdoc" 
   - image_path: assets/images/yiru_liu.png
     caption: "Workshop"
     excerpt: "Yi-Ru Liu Molecular Foundry, Phd Student" 
   - image_path: assets/images/thong_nguyen.png
     caption: "Teaching Assistant"
     excerpt: "Thong Nguyen | University of Washington, Undergraduate Student" 
   - image_path: assets/images/ed_bernard.png
     caption: "Workshop"
     excerpt: "Ed Bernard Molecular Foundry, Staff Scientist" 


feature_row4:
  - # image_path: /assets/images/lawrence.png
    url: "https://www.uwsunlab.com/papers"
    btn_label: "Read More @ UWSunLab"
    btn_class: "btn--primary"

  - # image_path: /assets/images/uwlogo.png
    url: https://sutterfellalab.lbl.gov/publications/
    btn_label: "Read More @ Lawrence National Labs"
    btn_class: "btn--primary"
---
{% include feature_row id="intro" type="center" %} 

Robotics and AI are regarded as transformative tools for scientific discovery and integral components of future laboratories. The primary goal of the summer school is to engage students in laboratory automation for the discovery of energy materials. Through lectures, coding tutorials, and robotic synthesis experiments, participants will explore closed-loop experiment design, machine learning, data handling and visualization, as well as hands-on lab work to create thin-film semiconductors using a robotic platform.

We aim to foster the development of the future workforce in materials science, engineering, computer science, physics, and related fields, anticipating that science and research will increasingly integrate artificial intelligence and machine learning (AI/ML).

The summer school is a 2.5 day event and open to all students and postdocs from interdisciplinary backgrounds. No prior coding experience is required. Participation in hands-on lab experiments is limited to selected participants due to space constraints.

<br/>

## Schedule
{% include feature_row id = "feature_schedule"%}

## Who is eligible to register for the summer course?
- Those registered for the 2025 Molecular Foundary Annual Meeting.
- Professionals,  Postdocs,  Graduate Students,  Undergraduate Students.

All coding activities will have ChatGPT-assisted coding, so no Python or coding mastery is required.

## Invited Speakers
- Dr. Maria Chan [Argonne National Laboratory ]
- Dr. Amalie Trewartha [Toyota Research Institute]
- Dr. Luis Barroso-Luque [Meta]
  
* Speaker list to be updated



{% include feature_row id = "feature_row3" %}

<!-- ## "Readings from our Hosts"
#  'Learn more through some of the publications from our host!' -->

{% include portrait_row id = "portrait_1"  type = "center" %}

{% include portrait_row id = "portrait_2" %}

<!-- {% include feature_row id="feature_row4" type="center" %}  -->
<div style="display: flex; justify-content: center; gap: 20px;">
  <a href="https://www.uwsunlab.com/papers" class="btn btn--primary">Read More @ UWSunLab</a>
  <a href="https://sutterfellalab.lbl.gov/publications/" class="btn btn--primary">Read More @ SutterFellaLab</a>
</div>
<!-- One of the placeholders can be reading materials (not sure how to call it) but it can provide links to Shijing/my papers;-->

{% if page.page_css %}
  {% for stylesheet in page.page_css  type = "center" %}
    <link rel="stylesheet" href="{{ stylesheet | relative_url }}">
  {% endfor %}
{% endif %}


<!-- 
another placeholder can be info about preparing for the summer school/ good to know. here we will add safety information, min. PPE
another placeholder can be data that we generate during the summer school and openly share through the website
another placeholder can be codes that we share as part of the summer school -->

<!-- 
{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %} -->

