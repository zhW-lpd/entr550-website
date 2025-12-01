---
layout: default
---

<section class="hero">
  <div class="hero-content">
    <p class="eyebrow">Student-led Tutoring Services Initiative</p>
    <h1>University of Michigan Peer-to-Peer Tutoring</h1>
    <p class="lead">
      This is a student-led initiative to connect students to peer tutors who might be in the same program as them or
      have taken the same course(s), in order to help them learn and grow academically. The goal is to have a directory
      of active tutors (who are also UoM students) available for students to contact and be able to get help. This
      resource is for graduate studies at the School of Information, Computer Science, and Electrical and Computer
      Engineering. Please find links to the tutoring resource and for tutor sign-up below.
    </p>
    <div class="hero-cta">
      <a class="btn primary" href="#resources">Explore resources</a>
      <a class="btn secondary" href="#registration">Become a tutor</a>
    </div>
  </div>
</section>

<section id="project-description" class="project-description">
  <h2>Project Description</h2>
  <p>
    This grassroots project is maintained by graduate student volunteers who understand the value of connecting with
    peers who have already navigated the same coursework. We are steadily expanding the directory and processes needed
    to make peer-led tutoring more accessible across the University of Michigan's School of Information, Computer
    Science, and Electrical and Computer Engineering programs.
  </p>
</section>

<section id="resources" class="resource-section">
  <div class="section-heading">
    <h2>Available Tutoring Resources</h2>
    <p>Browse the growing list of tutors who are ready to support you.</p>
  </div>
  <div class="card-grid">
    <article class="info-card">
      <h3>Existing Tutor Directory</h3>
      <ul class="link-list">
        <li>
          <strong>UMSI:</strong>
          <a href="https://docs.google.com/spreadsheets/d/1yysrhL4NU9YjcQxBL2rdFVTXEULv2Q7KedEoUycke6M/edit?usp=sharing" target="_blank" rel="noopener">Google Sheet</a>
        </li>
        <li>
          <strong>ECE/CSE:</strong>
          <a href="https://docs.google.com/spreadsheets/d/12I3PiCiVA8ShNPx4MfZJ8IiDhGO19FkJGYP7-wUERRw/edit?usp=sharing" target="_blank" rel="noopener">Google Sheet</a>
        </li>
      </ul>
    </article>
    <article class="info-card" id="registration">
      <h3>Peer Tutor Registration</h3>
      <ul class="link-list">
        <li><strong>UMSI:</strong> <a href="https://forms.gle/4rvr5CTNZFKFrW1v7">Form link</a></li>
        <li><strong>ECE/CSE:</strong> <a href="https://forms.gle/ziq5snjG8Ku2iK5N9">Form link</a></li>
      </ul>
    </article>
    <article class="info-card">
      <h3>UMich Resources &amp; Support</h3>
      <ul class="link-list">
        <li><a href="https://ece.engin.umich.edu/academics/undergraduate/advising/tutoring/">EE Undergraduate Tutoring Information</a></li>
        <li><a href="https://ecas.engin.umich.edu/">Engineering Center for Academic Success (ECAS)</a></li>
        <li><a href="https://sites.google.com/umich.edu/umsitutoring/home">UMSI Tutoring &amp; Peer Support</a></li>
      </ul>
      <p><em>Note: These resources are primarily for undergraduate courses.</em></p>
    </article>
    <article class="info-card" style="grid-column: 1 / -1; background: transparent; border: none; box-shadow: none; text-align: center;">
      <h3>Contact Information</h3>
      <p><a href="mailto:peer.tutoring@umich.edu">peer.tutoring@umich.edu</a></p>
    </article>
  </div>
</section>

<section class="flyer-section" id="flyer">
  <div class="section-heading">
    <h2>Program Flyers</h2>
    <p>Download and share these flyers with your classmates to spread the word about peer tutoring.</p>
  </div>
  <div class="flyer-grid">
    <div class="flyer-card">
      <h3>UMSI Flyer</h3>
      <div class="flyer-image">
        <img src="assets/images/UMSI.png" alt="UMSI Peer Tutoring Flyer" loading="lazy">
      </div>
      <a class="btn secondary" href="assets/images/UMSI.png" download>Download Image</a>
    </div>
    <div class="flyer-card">
      <h3>ECE/CSE Flyer</h3>
      <div class="flyer-image">
        <img src="assets/images/ECE and CSE.png" alt="ECE and CSE Peer Tutoring Flyer" loading="lazy">
      </div>
      <a class="btn secondary" href="assets/images/ECE and CSE.png" download>Download Image</a>
    </div>
  </div>
</section>

<style>
.flyer-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.flyer-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
}

.flyer-card h3 {
  margin: 0;
  font-size: 1.25rem;
  text-align: center;
}

.flyer-image {
  width: 100%;
  max-width: 500px;
  border: 1px solid #ddd;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.flyer-image:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 12px rgba(0, 0, 0, 0.15);
}

.flyer-image img {
  width: 100%;
  height: auto;
  display: block;
}

.flyer-card .btn {
  margin-top: 0.5rem;
}
</style>
