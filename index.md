---
title: I'm Darren Liu, nice to meet you!
feature_image: "/uploads/website_banner_final.svg"
feature_text:
---

<style>

.feature .container {
  min-height: 60vh;
}

.container {
  max-width: 1200px;
  width: 95%;
}

@media screen and (min-width: 40em) {
  .content {
    width: 80%;
  }
}


.cv-card {
  background: #c5bebe6e;
  border-radius: 12px;
  padding: 20px;
  color: #3d3b3b;
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
  font-size: 0.9rem;
  list-style-position: inside;
  font-family: "Avenir", "Avenir Next", "Helvetica Neue", Arial, sans-serif;
  height: fit-content;
}

.cv-card p {
  margin: 0.25rem 0 -1rem;
}

.cv-card ul {
  margin: 0 0 0.25rem;
  padding-left: 1rem;
}

.cv-card ul + p {
  margin-top: -1rem;
}

.cv-card li {
  margin: 0rem 0;   /* reduce vertical gap */
  line-height: 1.2;   /* tighter line spacing */
}

.cv-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 24px;
  align-items: start;
}

.cv-date {
  font-size: 0.9rem;
  color: #aaa;
  margin-bottom: 10px;
}

.cv-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

h3.cv-title {
  color: #070805; 
  margin: 0 0 -1rem 0;   /* less space under title */
  line-height: 1.2;
  font-family: "Avenir", "Avenir Next", "Helvetica Neue", Arial, sans-serif;
}

.typeset h3.cv-title {
  font-size: 1.2rem;
}

.cv-subtitle {
  font-size: 0.82rem;
  color: #777;
  margin-top: 0.2rem;
}

.cv-org {
  color: #ee0000;
  margin-top: 5px;
}

.cv-logo {
  width: 60px;
  height: auto;
}

h2.cv-col-title {
  margin: 0 0 -1rem 0;
  font-size: 1.6rem;
  font-weight: 700;
  line-height: 1.2;
  font-family: "Avenir", "Avenir Next", "Helvetica Neue", Arial, sans-serif;
}


.cv-left-image {
  width: 100%;
  max-width: 800px;
  height: auto;
  border-radius: 12px;
  align-self: start;
}
</style>

<!-- ![Darren Liu](/uploads/Darren_banner_full.jpg){: .profile-image} -->

I'm a fourth year Ph.D. student in the Biophysical Sciences, co-advised by [Aaron Dinner](https://dinner-group.uchicago.edu/) and [Arvind Murugan](http://muruganlab.uchicago.edu/) at the University of Chicago. 

<div class="button-group">
{% include button.html text="CV" link="/uploads/Darren_Liu_CV_20260320.pdf" new_tab=true %}{% include button.html icon="ai-google-scholar-square" text="Google Scholar" link="https://scholar.google.com/citations?user=MZdBLWwAAAAJ&hl=en" %}{% include button.html icon="linkedin" text="LinkedIn" link="https://www.linkedin.com/in/darren-liu-555808185" %}{% include button.html icon="github" text="Github" link="https://github.com/liudarren3" %}{% include button.html icon='twitter' text="Twitter" link="https://x.com/darrenjliu" %}
</div> 

If you would like to get in touch, feel free to send me an email at: <br>**liudarren3 [at] gmail.com**

<div class="cv-grid">
  <!-- left column -->
  <h2 class="cv-col-title">Education</h2>
  <h2 class="cv-col-title">Research Experience</h2>
  <div class="cv-card">
    <!-- content -->
      <div class = "cv-content">
      <div class="cv-date">2022 – Present</div> 
      <img class="cv-logo" src="/uploads/UChicago-logo.png" alt="University of Chicago logo">
      </div>
      <h3 class="cv-title">Biophysics PhD – University of Chicago</h3>
      <p>Advisors: Aaron Dinner, Arvind Murugan</p>
      <p>Department of Biophysical Sciences</p>
      <p><strong>Interests:</strong></p>
      <ul>
        <li>Molecular evolution</li>
        <li>Labratory automation</li>
        <li>Protein language models</li>
      </ul>
      
  </div>

  <!-- right column -->
  <div class="cv-card">
    <!-- content -->
    <div class = "cv-content">
      <div class="cv-date">2022 – Present</div> 
      <img class="cv-logo" src="/uploads/UChicago-logo.png" alt="University of Chicago logo">
      </div>
      <h3 class="cv-title">University of Chicago</h3>
      <p>Graduate Researcher</p>
      <p><strong>Experiments:</strong></p>
      <ul>
        <li>High-throughput directed protein evolution</li>
        <li>Labratory automation</li>
      </ul>
      <p><strong>Computation:</strong></p>
      <ul>
        <li>Dimensionality reduction</li>
        <li>Machine learning for biology</li>
      </ul>
  </div>
</div>

<div class="cv-grid">
  <div style="visibility:hidden;"></div>

  <div class="cv-card">
    <!-- content -->
    <div class = "cv-content">
      <div class="cv-date">Summer of 2026</div> 
      <img class="cv-logo" src="/uploads/Abbvie-logo.png" alt="Stanford logo">
      </div>
      <h3 class="cv-title">AbbVie</h3>
      <p style="line-height:1.5; margin:-5;">
        CMC Biologics Drug Substance Intern - Cell Culture Development 
      </p>
      <p><strong>Skills:</strong></p>
      <ul>
        <li>AI/ML for cell culture development</li>
      </ul>
  </div>
</div>

<div class="cv-grid">
  <!-- left column -->
  <div class="cv-card">
    <!-- content -->
      <div class = "cv-content">
      <div class="cv-date">2018 – 2022</div> 
      <img class="cv-logo" src="/uploads/BU-logo.png" alt="Boston University logo">
      </div>
      <h3 class="cv-title"> B.A. Chemistry – Boston University</h3>
      <p>Double minors in Biology and Computer Science</p>
      <p><strong>Interests:</strong></p>
      <ul>
        <li>Protein chemistry</li>
        <li>Machine learning</li>
        <li>Statistical mechanics</li>
      </ul>
      
  </div>
  <!-- right column -->
  <div class="cv-card">
    <div class = "cv-content">
        <div class="cv-date">2021 – 2022</div> 
        <img class="cv-logo" src="/uploads/BU-logo.png" alt="Boston University logo">
        </div>
        <h3 class="cv-title"> Boston University</h3>
        <p style="line-height:1.5; margin:-5;">
          Undergraduate Researcher
          <span style="display:block; height:-2px;"></span>
          Advisor: William Lehman
        </p>
        <p><strong>Skills:</strong></p>
        <ul>
          <li>Molecular dynamics</li>
        </ul>
  </div>
</div>

<div class="cv-grid">
  <div style="visibility:hidden;"></div>

  <div class="cv-card">
    <!-- content -->
    <div class = "cv-content">
      <div class="cv-date">Summers of 2018 – 2022</div> 
      <img class="cv-logo" src="/uploads/Stanford-logo.png" alt="Stanford logo">
      </div>
      <h3 class="cv-title">Stanford University</h3>
      <p style="line-height:1.5; margin:-5;">
        Summer Researcher
        <span style="display:block; height:-2px;"></span>
        Advisor: Julia Salzman
      </p>
      <p><strong>Skills:</strong></p>
      <ul>
        <li>Spatial transcriptomics</li>
        <li>Computer Vision</li>
      </ul>
  </div>
</div>

<div class="cv-grid">
  <h2 class="cv-col-title">Service and Teaching</h2>
  <h2 class="cv-col-title"></h2>
  <img class="cv-left-image" src="/uploads/UCombo-low.png" alt="Description">
  <div class="cv-card">
    <!-- right column content -->
    <h3 class="cv-title"><a href = "https://centerforlivingsystems.uchicago.edu/"> Center for Living Systems</a> Chalk Talk Organizer</h3>
    <p style="line-height:1.5; margin:0;"></p>
    <h3 class="cv-title"><a href = "https://uccompbio.github.io/">UChicago Computational Biology Outreach</a></h3>
    <p style="line-height:1.5; margin:-0;">Taught computational biology (Python, DNA) in elementary, middle, and high schools</p>
    <h3 class="cv-title">Biophysical Sciences Student Advisory Board Member</h3>
    <p style="line-height:1.5; margin:0;">Elected by peers to coordinate and lead program-wide events and community building activities.</p>
    <h3 class="cv-title">GirlsWhoCode</h3>
    <p style="line-height:1.5; margin:-0;">Taught fundamentals of coding to girls in elementary and middle school</p>
    <h3 class="cv-title">Volunteer for <a href="https://eyhchicago.wordpress.com/">Expanding Your Horizons </a> </h3>
    <p style="line-height:1.5; margin:0;"></p>
    <!--<h3 class="cv-title">TA for "Computational Biology in Microbial Ecosystems"</h3>
    <p style="line-height:1.5; margin:0;"></p> -->
    <h3 class="cv-title"><span>&#64;</span>rtifice Volunteer</h3>
    <p style="line-height:1.5; margin:-0;">Taught middle school kids basics of circuits and coding</p>
    <h3 class="cv-title">BU Chemia</h3>
    <p style="line-height:1.5; margin:-0;">Tutored undergraduates in organic and physical chemistry</p>
    

  </div>
</div>

<h1>About me</h1>

I enjoy combining experiments, theory, and computation in order to tackle the most exciting questions in biology. Broadly, my interests are in the physics of protein evolution and machine learning for biology. My thesis investigates the constraints that shape how and why proteins acquire new functions after mutation. To this end, I am combining **experimental directed evolution**, **automated liquid handling**, and **physical computational models** to measure protein evolvability at scale. From this data, I will use advanced dimensionality reduction techniques to identify low-dimensional relationships between protein sequence, phenotype, and evolvability.

I did my undergrad at Boston University where I earned a degree in Chemistry: Biochemistry with minors in both Biology and Computer Science. Most of my previous research experience was at Stanford University, where I worked with [Julia Salzman](https://salzmanlab.stanford.edu/) to analyze RNA-sequencing data from COVID positive patients with a statistical splicing algorithm and develop spatial transcriptomics methods with computer vision . I also worked with [William Lehman](https://www.bumc.bu.edu/camed/profile/william-lehman/) in the BU School of Medicine to predict the effect of point mutations on myosin filaments with molecular dynamics simulations and relate those effects to cardiovascular disease. I also love volunteering for STEM outreach programs and have an extensive history teaching children computer science, biology, and chemistry concepts from elementary to high school. 

