# Docker Internals Guide

> **Docker Internals: The Real Magic Behind Containers**  
A presentation that dives deep into the underlying mechanisms of containers, focusing on Linux kernel features such as namespaces and cgroups. Built using [reveal.js](https://revealjs.com/).

## 📦 Overview

This project is a slide-based presentation that explains:
- Why containers are important
- The difference between containers and virtual machines
- The inner workings of Docker: namespaces and cgroups
- CPU management in containers
- Common myths about containers
- The lifecycle of Docker containers

## 🛠 Prerequisites

You only need Python installed (for serving the static HTML). No need to install reveal.js manually—it's pulled from a CDN.

## 🚀 How to Run

1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Run a simple HTTP server:

   ````bash
   python -m http.server
   ````

4. Open your browser and navigate to:

   ````
   http://localhost:8000
   ````

## 📁 Files

- `index.html` – The main presentation file.
- `images/` – Folder containing supporting images (if any).
- `README.md` – You're reading it!

## 👤 Author

Prepared by **Harsh Raj Dubey**  

---

Enjoy learning how containers really work under the hood! 🐳
