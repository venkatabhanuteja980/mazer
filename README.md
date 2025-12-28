🦁 Task 3 – Front-End Skill Assessment
Safari-Themed Mazer Dashboard Customization
📌 Objective

This task evaluates a developer’s ability to understand, customize, and adapt an existing real-world admin dashboard rather than building from scratch.

The base project used is Mazer, an open-source Bootstrap 5 admin dashboard.

🧩 Base Template

Template Name: Mazer Admin Dashboard

Original Repository: https://github.com/zuramai/mazer

License: MIT

This repository is a fork of the original Mazer project and has been customized as part of the assessment.

🎨 Customization Overview (Safari Theme)

The dashboard has been customized into a Safari / Wildlife-themed admin interface.

✅ UI & UX Changes

Updated color palette using SCSS variables

Safari-inspired visual theme

Custom logo replacement (SVG → PNG)

Modified layout and landing dashboard

Maintained Bootstrap 5 responsiveness

✅ Code-Level Changes

Edited src/assets/scss/_variables.scss for global theming

Updated index.html and master layout

Replaced branding assets (logo)

Preserved original component structure while adapting visuals

🛠 Technologies Used

HTML5

SCSS / CSS3

Bootstrap 5

JavaScript (ES6)

Vite (Bundler & Dev Server)

Git & GitHub

⚠️ Challenges Faced

During this task, I faced multiple real-world development issues, including:

Dependency conflicts between Vite versions and plugins

Peer dependency resolution errors (ERESOLVE)

Platform-specific build issues on Windows

esbuild binary and optional dependency errors

Understanding a large, pre-built codebase structure

These challenges required:

Debugging npm dependency trees

Using --legacy-peer-deps and --ignore-scripts

Learning how modern build tools work internally

📚 Learning Outcome

This task significantly improved my understanding of:

Working with existing production-grade projects

Customizing dashboards without breaking structure

Managing dependencies in large frontend projects

Real-world Git workflows (fork → commit → push)

Bootstrap-based admin UI architecture

▶️ Project Setup & Run
npm install --legacy-peer-deps --ignore-scripts
npm run dev
