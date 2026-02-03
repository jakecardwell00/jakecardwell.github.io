---
title: Experience / Projects
linkTitle: Experience / Projects
url: "/projects/"
type: docs
description: >
  Throughout my time at Purdue, J&J, and even highschool I have worked on many projects that I am very proud of. I will display them here. 
menu: {main: {weight: 50}}
cascade:
  - type: "docs"
---

<style>
.exp-proj-layout {
  display: flex;
  gap: 3rem;
}
.exp-proj-left {
  flex: 0 0 220px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding-top: 2rem;
}
.exp-proj-left h2 {
  font-size: 1.2rem;
  margin-bottom: 1rem;
  color: #63b3ed;
}
.exp-proj-left .exp-proj-list {
  margin-bottom: 2.5rem;
}
.exp-proj-left a {
  display: block;
  margin-bottom: 1.2rem;
  color: #fff;
  text-decoration: none;
  font-size: 1rem;
  padding: 0.5rem 0.8rem;
  border-radius: 0.5rem;
  transition: background 0.2s;
}
.exp-proj-left a:hover {
  background: #2d3748;
}
.exp-proj-center {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 2rem;
}
.exp-proj-preview {
  width: 80%;
  max-width: 600px;
  height: 220px;
  background: rgba(44, 62, 80, 0.2);
  border: 2px dashed #4a5568;
  border-radius: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.3rem;
  color: #4a5568;
  margin-bottom: 2rem;
}
.exp-proj-links {
  display: flex;
  gap: 2rem;
  justify-content: center;
  margin-bottom: 2.5rem;
}
.exp-proj-link {
  flex: 1;
  background: #2d3748;
  border: 2px solid #4a5568;
  border-radius: 1rem;
  padding: 2rem;
  text-align: center;
  color: #fff;
  font-size: 1.1rem;
  text-decoration: none;
  transition: box-shadow 0.2s;
}
.exp-proj-link:hover {
  box-shadow: 0 4px 16px rgba(44,62,80,0.2);
}
.exp-proj-divider {
  width: 100%;
  border-top: 2px solid #4a5568;
  margin: 3rem 0;
}
</style>

<div class="exp-proj-layout">
  <div class="exp-proj-left">
    <h2>Experience</h2>
    <div class="exp-proj-list">
      <a href="#">Rainmaker Technology Internship</a>
      <a href="#">Purdue Space Program Hybrids Team</a>
    </div>
    <h2>Projects</h2>
    <div class="exp-proj-list">
      <a href="#">Purdue SLICE</a>
      <a href="#">Senior Design</a>
      <a href="#">Golf Cart</a>
    </div>
  </div>
  <div class="exp-proj-center">
    <h2>Experience</h2>
    <div class="exp-proj-preview">Experience Preview Image</div>
    <div class="exp-proj-links">
      <a class="exp-proj-link" href="#">Rainmaker Technology Internship</a>
      <a class="exp-proj-link" href="#">Purdue Space Program Hybrids Team</a>
    </div>
    <div class="exp-proj-divider"></div>
    <h2>Projects</h2>
    <div class="exp-proj-preview">Projects Preview Image</div>
    <div class="exp-proj-links">
      <a class="exp-proj-link" href="#">Purdue SLICE</a>
      <a class="exp-proj-link" href="#">Senior Design</a>
    </div>
    <div class="exp-proj-links" style="justify-content: flex-start;">
      <a class="exp-proj-link" href="#">Golf Cart</a>
    </div>
  </div>
</div>

