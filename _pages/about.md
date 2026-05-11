---
permalink: /
title: "About Me - Qihao Wang 王麒昊"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
/* Clear simple layout */
.main-content-wrapper {
  display: flex;
  width: 100%;
  gap: 20px;
  align-items: flex-start;
}

.main-text-content {
  flex: 1 1 auto;
  min-width: 0;
  padding-right: 0;
}

.publications-sidebar {
  flex: 0 0 280px;
  width: 280px;
  padding: 16px 16px 14px;
  background: linear-gradient(180deg, #f5f9ff 0%, #ffffff 100%);
  border: 1px solid #d8e4f3;
  border-radius: 8px;
  box-shadow: 0 6px 16px rgba(24, 58, 106, 0.08);
  font-size: 0.82em;
  position: sticky;
  top: 70px;
  align-self: flex-start;
  height: fit-content;
}

.publications-sidebar h3 {
  margin-top: 0;
  margin-bottom: 10px;
  font-size: 1.05em;
  color: #1f4f8f;
  border-bottom: 1px solid #cfe0f4;
  padding-bottom: 6px;
  letter-spacing: 0.2px;
}

.publications-sidebar ul {
  margin: 0;
  padding-left: 16px;
  list-style-type: disc;
}

.publications-sidebar li {
  margin-bottom: 7px;
  line-height: 1.45;
}

.publications-sidebar a {
  color: #1f5fa8;
  text-decoration: none;
}

.publications-sidebar a:hover {
  color: #143f73;
  text-decoration: underline;
}

@media (max-width: 1100px) {
  .main-content-wrapper {
    display: block;
    gap: 0;
  }

  .main-text-content {
    display: block;
    width: 100%;
    padding-right: 0;
  }

  .publications-sidebar {
    display: block;
    width: 100%;
    margin-top: 20px;
    position: static;
  }
  .author__sidebar {
  margin-left: -30rem !important;
  padding-left: 0;
  }
}
</style>

<div class="main-content-wrapper">

  <!-- LEFT CELL: main text -->
  <div class="main-text-content" markdown="1">

I am a researcher/student in [Your Department], [Your University]. My research interests include [Research Area 1], [Research Area 2], and [Research Area 3].

<!-- Add your biography here -->

---

Works
------

<!-- Add your works/research projects here -->

 - **Your Research Project Title** (with Co-authors). *Journal Name*. Year. [DOI/URL](#)

Description of your research project goes here.

---

 - **Another Research Project Title** (with Co-authors). *Preprint*. Year. Available at [link](#)

Description of your research project goes here.

---

Contact
------
Feel free to reach out via email: your-email@example.com

  </div> <!-- end of main-text-content -->

  <div class="publications-sidebar">
    <h3>Publications</h3>
    <ul>
      <li><a href="#">Your Publication Title</a> (Year). <em>Journal</em></li>
      <li><a href="#">Another Publication</a> (Year)</li>
    </ul>
  </div> <!-- end of publications-sidebar -->

</div> <!-- end of main-content-wrapper -->
