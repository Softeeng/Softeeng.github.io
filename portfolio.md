---
layout: default
title: Portfolio
permalink: /portfolio/
---

# My Projects

Welcome to my portfolio! Below are some of the projects I've worked on as part of my development journey.

<style>
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
    margin-top: 1.5rem;
  }

  .project-card {
    background: linear-gradient(145deg, #1c1c1c, #232323);
    border-radius: 14px;
    padding: 1.2rem;
    color: #f5f5f5;
    box-shadow: 0 3px 8px rgba(0, 0, 0, 0.4);
    transition: all 0.3s ease;
    border: 1px solid transparent;
  }

  .project-card:hover {
    transform: translateY(-7px) scale(1.02);
    box-shadow: 0 6px 16px rgba(0, 0, 0, 0.6);
    border: 1px solid #66ccff;
  }

  .project-card h2 {
    margin-top: 0;
    color: #66ccff;
  }

  .project-card a {
    color: #66ccff;
    text-decoration: none;
    font-weight: bold;
    display: inline-block;
    margin-top: 0.5rem;
    transition: color 0.2s ease;
  }

  .project-card a:hover {
    color: #99e6ff;
    text-decoration: underline;
  }
</style>

<div class="projects-grid">

  <div class="project-card">
    <h2>Medication Reminder App</h2>
    <p>A Python desktop app built with Tkinter that helps users schedule, edit, and view medication reminders easily.</p>
    <a href="https://github.com/Softeeng/Medication-Reminder" target="_blank">View Project</a>
  </div>

  <div class="project-card">
    <h2>Patient Record Manager</h2>
    <p>A command-line healthcare management system that stores and retrieves patient data securely using a local database.</p>
    <a href="https://github.com/Softeeng/PatientRecordManager" target="_blank">View Project</a>
  </div>

  <div class="project-card">
    <h2>Horror Game Project</h2>
    <p>A psychological horror adventure where players explore rooms, collect artifacts, and uncover the curse of a haunted mansion.</p>
    <a href="https://github.com/Softeeng/horror-game" target="_blank">View Project</a>
  </div>

</div>
