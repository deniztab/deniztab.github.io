---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: custom_home
title: Home
---

<!-- Section 1: Introduction -->
<section class="introduction">
  <div class="intro-left">
    <div class="name">
      <h1>Deniz Tabakci</h1>
    </div>
  </div>
  <div class="intro-right">
    <div class="bar">
      <a href="{{ '/Projects' | relative_url }}" class="button">Projects</a>
    </div>
    <div class="intro-title">
      <p>Hello.</p>
    </div>
    <div class="intro-text">
      <p>I am a software developer passionate about creating innovative solutions and tackling complex challenges. My experience spans image and video processing, machine learning, reinforcement learning, and data processing.</p>
    </div>
  </div>
</section>

<!-- Section 2: Projects -->
<section class="projects">
  <div class="title">
    <h1>Technical Projects</h1>
  </div>
  <div class="project-row">
    <div class="project-block project-block-left">
      <div class="project-title">Movement Detection & Shutter Control</div>
    </div>
    <div class="project-description project-description-left">
        <p>This project involves large rotating shutters which react to movements ooccuring in front of it. It utilizes OpenCV's background subtractors to detect changes in its field of view and move shutters corresponding to location where the movement was detected. The project runs on Raspberry Pi and Arduino units.</p>
        <a href="{{ '/projects#shutter' | relative_url }}" class="details-button">Details</a>
    </div>
  </div>
  <div class="project-row">
    <div class="project-description project-description-right">
        <p>My capstone project at UBC, in collaboration with MDA. Utilizing image processing techniques to create detailed images of Earth orbiting sattelites using low quality videos taken from Earth. </p>
        <a href="{{ '/projects#sat' | relative_url }}" class="details-button">Details</a>
    </div>
    <div class="project-block project-block-right">
      <div class="project-title">Sattelite Video Processing</div>
    </div>
  </div>
  <div class="project-row">
    <div class="project-block project-block-left">
      <div class="project-title">Hand Tracking and Detection</div>
    </div>
    <div class="project-description project-description-left">
        <p>A small personal project focusing on detecting and tracking hand movements. It runs on multiple processes and supports up to 6 different hands being tracked in real time.</p>
        <a href="{{ '/projects#hand' | relative_url }}" class="details-button">Details</a>
    </div>
  </div>
</section>

<!-- Section 3: Work Experience -->
<section class="work">
  <div class="title">
    <h2>Work Experiences</h2>
  </div>
  </div>
  <div class="work-row">
    <div class="work-description project-description-right">
        <p>Took ownership of 2 mission-critical project pipelines in my first 4 months including Data Ingestion and ISP Market Share while working with Billion+ rows of data on a daily basis. Developed and deployed multiple production-level SQL scripts including highly sophisticated Anomaly detection and filtering algorithms.</p>
    </div>
    <div class="work-block project-block-right">
      <div class="work-title">ThinkCX</div>
      <div class="work-subtitle">Junior Data Engineer</div>
    </div>
  </div>
  <div class="work-row">
    <div class="work-description project-description-right">
        <p>Led the integration of a client-side metrics monitoring tool using Ruby on Rails. Participated in Agile software development including all of the Agile ceremonies. Produced, tested and deployed production ready code. </p>
    </div>
    <div class="work-block project-block-right">
      <div class="work-title">Amazon</div>
      <div class="work-subtitle">SDE Intern</div>
    </div>
  </div>
  <div class="work-row">
    <div class="work-block project-block-left">
      <div class="work-title">Cadex Electronics Inc.</div>
      <div class="work-subtitle">Research Co-op</div>
    </div>
    <div class="work-description project-description-left">
        <p>Created from scratch, a Hyper-parameter tuning algorithm in Python, utilizing Reinforcement Learning. Built a tool around the algorithm to train high accuracy XGBoost Machine Learning models. Co-authored a published research paper as a result of my work on the algorithm. The research paper can be found <a href="https://ieeexplore.ieee.org/document/10194065" target="_blank">here</a>.</p>
    </div>
  </div>
    <div class="work-row">
    <div class="work-description project-description-right">
        <p>Contributed to six sprints within an Agile team employing Scrum methodology for Agile software development. I developed and assisted in the development of REST APIs for the mobile banking application using Java in conjunction with the Spring framework. </p>
    </div>
    <div class="work-block project-block-right">
      <div class="work-title">Garanti Technology BBVA</div>
      <div class="work-subtitle">Software Development Intern</div>
    </div>
  </div>
</section>
<!-- Section 4: Quotes -->
<section class="quotes">
<blockquote>
    <p>"He has proven himself to be a valuable asset to any team, capable of leading projects to successful outcomes through his knowledge and proactive approach... I highly recommend Deniz Tabakci for any opportunity that aligns with his skills and interests. He would undoubtedly contribute positively to any organization."</p>
    <div class="author">MDA - Balaji Shankar Kumar</div>
</blockquote>
<blockquote>
    <p>"From day one, Deniz set the tone with a clear question: “How can I best support my manager, team, and company?” He answered it daily through his actions." \n"Deniz is candid, reliable, and keeps the mission front and center. He’s the teammate who volunteers for the hard parts and sees them through." \n"Amid an exceptionally tight delivery window, Deniz assumed full ownership of our legacy products in half the usual ramp‑up time..."</p>
    <div class="author">ThinkCX - Derek Muxworthy</div>
</blockquote>
<!-- Add more quotes as needed -->
</section>

<!-- Section 5: Contact -->
<div class="contact">
  <h2>Contact Me</h2>
  <div class="contact-info">
    <div class="contact-item">
      <i class="fa fa-envelope" aria-hidden="true"></i><a href="mailto:deniz.tabakci2000@gmail.com">deniz.tabakci2000@gmail.com</a>
    </div>
    <div class="contact-item">
      <i class="fa-brands fa-linkedin" aria-hidden="true"></i><a href="https://www.linkedin.com/in/deniz-tabakci/" target="_blank">LinkedIn</a>
    </div>
    <div class="contact-item">
      <i class="fa-brands fa-github" aria-hidden="true"></i><a href="https://github.com/deniztab" target="_blank">GitHub</a>
    </div>
  </div>
</div>
