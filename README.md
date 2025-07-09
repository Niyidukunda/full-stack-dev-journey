# Web Development Learning Journal

* An interactive learning journal documenting my journey into full-stack web development.

Welcome to my technical learning journal — a personal record of my practical exploration into full-stack web development, including HTML, CSS, JavaScript, Node.js, React, and deployment strategies.

This repository captures my practical experience, challenges, and achievements as I explore concepts like front-end design, backend architecture, and modern web technologies.

## Mission

This repository serves as a resource for anyone looking to understand full-stack web development and its ecosystem. It aims to provide:

Step-by-step guides for setting up and using web development tools

Reflections on challenges and solutions encountered during the learning process

Practical examples and use cases for web development in real-world scenarios

## Tech Stack

HTML & CSS: For structuring and styling web pages

JavaScript: For dynamic and interactive web functionality

Node.js: For backend development and server-side scripting

React: For building modern, component-based user interfaces

Git & GitHub: For version control and collaboration

PostgreSQL: For relational database management

Web3 & DApps: For decentralized applications and blockchain integration

## Simon Game Project

This file documents how I created and deployed the Simon Game, an interactive memory game built with HTML, CSS, and JavaScript.

Features

Interactive gameplay with increasing difficulty

Responsive design for mobile and desktop

Modular code structure for easy updates

Deployment

The Simon Game is hosted on GitHub Pages.

* Reflections

Building the Simon Game helped me understand DOM manipulation and event handling in JavaScript.

Debugging gameplay logic improved my problem-solving skills and attention to detail.

Deploying the project taught me the basics of hosting static sites and using GitHub Pages.

The Simon Game was inspired by concepts and projects from The Complete Full-Stack Web Development Bootcamp by Dr. Angela Yu.

To avoid the “unrelated histories” issue in the future, here’s the golden rule:
Start your GitHub repo empty if you plan to push from local

When creating a new repo on GitHub, do not check any of the following:

“Add a README file”

“Add a .gitignore”

“Add a license”

This ensures the remote repo has no commits and is ready to receive your local commit history cleanly.

💡 Alternative approach (if you want GitHub to generate files first)

If you do check “Add README” or other files on GitHub:

Clone the repo locally instead of initializing a new local Git repo from scratch

git clone https://github.com/your-username/your-repo.git

Then add and commit your changes

git add .
git commit -m "Add local content"
git push

This way, your local repo shares the same history from the beginning.

What happened in my case

I created the repo on GitHub with a README, then initialized a local repo separately. So Git saw two different starting points — one on GitHub, one local — and refused to merge them unless I explicitly told it that I wanted to allow unrelated histories.

To resolve this, I ran:

git pull origin main --allow-unrelated-histories

This command merged the remote README with my local commits, preserving both histories.

After the merge, I pushed the combined history back to GitHub:

git push -u origin main

This process ensured that my local and remote repositories were synchronized without losing any commits.



