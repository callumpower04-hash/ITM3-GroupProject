## Social Defenders — Cybersecurity Consultancy  
### MTU ITM3 Group Project (2025)

This repository contains the complete website source code for **Social Defenders**, a cybersecurity consultancy specialising in **Social Engineering Defense, SETA Training, and AI-driven threat awareness**.  
The website forms a major component of our **MTU Group Project**, including a **proof-of-concept demonstration**, **interactive training modules**, and **client-focused educational material**.

---

## Project Overview

Social Defenders is a fictional cybersecurity consultancy created as part of the **ITM3 Group Project 2025**.  
Our focus area is:

### Social Engineering & AI-Enhanced Cyber Threats
Including:
- Modern phishing and impersonation techniques  
- AI-powered scams & deepfake fraud  
- SETA (Security Education, Training & Awareness) programme design  
- Defence strategies for organisations and individuals

This repository serves two purposes:
1. **Showcase our consultancy website**  
2. **Provide a shared codebase** for the team to access, update and maintain remotely

---

## Website Features

The website is built entirely using **HTML + CSS**, designed with a modern, responsive UI using our custom stylesheet (`style.css`) and FontAwesome icons.

### Core Pages
| Page | Description |
|------|-------------|
| `index.html` | Homepage, intro to Social Defenders, hero section, services |
| `about.html` | Mission, values, and team member profiles |
| `contact.html` | Contact form, business hours, MTU map section |
| `training.html` | Overview of training programmes (Social Engineering + Deepfake Module) |
| `training-section.html` | Interactive tests hub (phishing, deepfakes, general knowledge) |

---

## Social Engineering Training Modules

###  Introduction to Social Engineering  
_File: `introSocial.html`_  
- What is Social Engineering?  
- Psychological manipulation  
- Historical context  
- Key terminology (Phishing, Pretexting, Baiting)

###  Common Social Engineering Attacks 
_File: `common-attacks.html`_  
Covers:
- Phishing  
- Spear phishing  
- Whaling  
- Baiting  
- Pretexting  
Each attack includes images, definitions, and real-world behaviour indicators.

###  Defence Strategies  
_File: `defense-strategies.html`_  
Includes:
- Email red flags  
- Spear phishing protection  
- Baiting avoidance  
- Pretexting detection  
- General "Verify Before Trusting" principles

---

## Interactive Deepfake Training Module (Proof of Concept)

###  Deepfake Detection Training  
_File: `learn.html` + `deep.mp4`_

This module is our **Proof-of-Concept** for the project.

It includes:
- Visual analysis techniques  
- Audio inconsistency detection  
- Context-based evaluation  
- Interactive quiz  
- Real vs Deepfake classification challenge  
- Video playback controls  
- Awareness messages and best practices  

Users attempt to classify the provided video as *real or fake*, and are redirected to:

### `right.html` — Success screen  
Includes:
- Confetti animation  
- Progress bar  
- Certificate-style achievement section  
- Mastered skills breakdown

### `wrong.html` — (possible add on if user fails)

---

## Training Test Hub

_File: `training-section.html`_

Contains three interactive test categories:
- **Phishing Detection Test**
- **Deepfake Recognition Test**
- **General Knowledge Test**

Each test card includes:
- Difficulty indicators  
- Duration  
- Pass rate  
- CTA to begin test

*(Note: test HTML files are stubs to be expanded as part of project growth.)*

---

##  Styling & UI

All UI styling is handled through:

### `style.css`
This includes:
- Global theme variables  
- Navigation styling  
- Hero section  
- Features grid  
- Responsive training card layouts  
- Footer design  
- Mobile menu handling  
- Contact form + map section styling  
- Team grid  
- Course cards & test cards  

The colour theme aligns with modern cybersecurity aesthetic:
- Navy + cyber-blue gradients  
- Neon accent (`--accent: #64ffda`)

---

##  Repository Structure

