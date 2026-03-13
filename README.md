# Social Engineering Awareness & Phishing Simulation Lab

## Table of Contents
- [Project Highlights](#project-highlights)
- [Project Overview](#project-overview)
- [Live Demo](#live-demo)
- [Architecture Overview](#architecture-overview)
- [Phishing attack simualtion](#Phishing-attack-simualtion-understanding)
- [Phishing Detection Guide & Analysis Toolkit](#phishing-detection-summary--analysis-toolkit)
- [Security & Ethical Disclaimer](#security--ethical-disclaimer)
- [About the Author](#about-the-author)
- [Contact](#contact)

# Project Highlights

- Built an interactive Social Engineering & Phishing Awareness Lab to demonstrate how attackers manipulate users using psychological techniques such as curiosity, urgency, reward, and FOMO.

- Implemented AI-powered phishing message simulation using OpenAI GPT to demonstrate how attackers can generate convincing phishing messages and how users can recognize suspicious patterns.

- Integrated Telegram-based user verification using Telegram Bot API to ensure that only real users access the lab environment without requiring traditional signup systems.

- Developed a Phishing Detection & Analysis Module with 25+ investigation tools and structured detection categories including URL analysis, email header analysis, domain intelligence, SSL validation, and IOC identification.

- Created a SOC-style detection checklist with clear Do & Don’t guidelines to help users identify suspicious URLs, phishing domains, and manipulated login pages.

- Implemented SMTP attack awareness simulation to demonstrate how attackers may abuse email infrastructure to distribute phishing messages while highlighting defensive detection techniques.

- Designed simulated login pages for multiple platforms to help users recognize phishing page characteristics and visual deception tactics.

- Deployed the platform using Vercel to provide a live interactive learning environment.

# Project Overview: 
This project is an educational platform designed to demonstrate how social engineering and phishing attacks works practically. The lab helps users understand the psychological techniques attackers use and teaches how such attacks can be detected and prevented. The platform includes both phishing simulation and Phishing Detection Summary module designed to help users understand how real attacks works and how Security Operations Center (SOC) analysts investigate suspicious emails, URLs, and domains. And Also provides a structured analysis guide with 25+ detection tools and step-by-step investigation techniques.
Thid platform simulates phishing scenarios in a controlled environment to improve cybersecurity awareness and SOC investigation skills.

# Live Demo
//My lab website access: https://practicalabyxoin.vercel.app     
//Use demo credential to access: username: @The_Minimum | Psd: @The_MinimuM 

> Telegram-Based User Verification: 
The platform integrates the Telegram Bot API to verify real users before allowing access to the lab.

> Workflow:
User enters their Telegram username > A custom bot checks whether the username exists > If the account is verified, the user can create a password to access the lab > If the username cannot be verified, access is denied.

> Why Telegram verification is used?
This platform is a cybersecurity lab environment, not a production service.
The goal is to allow users to access the learning environment without creating a traditional account system.
Instead of building a full signup system with email or Google authentication, Telegram verification is used to confirm that the user is a real person and not an automated bot.

> Password reset mechanism:
If a user forgets their password, they can generate a new password using their verified Telegram username.
No personal data or credentials are permanently stored in the platform.
The verification system is used only to validate legitimate access to the lab.
This approach keeps the platform simple, privacy-focused, and suitable for an educational cybersecurity lab environment.

# Architecture Overview

> Tech Stack:
This project demonstrates the use of multiple technologies and APIs:
- HTML, CSS, JS, React For Development
- AI message generation using OpenAI GPT
- User verification using Telegram Bot API
- SMTP simulation for phishing awareness
- Frontend deployment via Vercel

> Key Learning Goals
- This lab helps demonstrate:
- Social engineering psychology
- Phishing message creation patterns
- Email attack techniques
- Security awareness training
- Detection guide with tools
- AI misuse in phishing campaigns
- Understanding attacker workflows
  
> Target Audience
- This project is useful for:
- Cybersecurity students
- SOC analyst learners
- Security awareness trainers
- Developers interested in phishing detection
- Anyone learning about social engineering threats

> Purpose of the Detection Module
This module is designed to help users:
- Understand how phishing attacks are detected
- Learn basic SOC investigation workflows
- Explore real-world security analysis tools
- Identify phishing indicators and red flags
- The goal is to provide a practical reference guide for phishing detection and analysis.

# Phishing attack simualtion understanding

1. Social Engineering Technique Simulator
Demonstrates common manipulation techniques used in phishing attacks:
- Curiosity
- Urgency
- Fear
- Reward
- FOMO (Fear of Missing Out)
- Fake Support Requests
- Users can explore how attackers craft messages using these psychological triggers.

2. AI Phishing Message Generator
The platform includes an AI tool that demonstrates how phishing messages can be generated based on specific social engineering techniques.
> Users can:
- Select a social engineering technique
- Generate a sample phishing message
- Customize the message
- Learn why the message may trick users
- This feature is designed for awareness training purposes only.

3. Hook and Message Combination System
> Users can select:
- Social engineering technique
- Message template
- Hook scenario
- The system demonstrates how attackers combine these elements to craft convincing phishing messages.
- This helps users understand how phishing campaigns are structured.

4. Social Media Simulation Pages
The lab includes simulated login pages to demonstrate how attackers replicate popular platforms.
Examples include:
- Instagram
- Facebook
- Twitter
- LinkedIn
- Youtube
- TikTok
- Snapchat
- Spotify
- and other social platforms
- These pages are visual simulations only used to teach how phishing websites look.

5. AI Phishing Message Awareness Tool
The platform integrates the OpenAI GPT API to demonstrate how attackers may use AI to generate convincing phishing messages.
Users can:
- Select a social engineering technique
- Generate example phishing messages
- Customize message structure using Ai
- Understand how AI can be misused to craft suspicious emails
- The feature helps users recognize AI-generated phishing attempts and understand the risks of automated social engineering.

6. SMTP Phishing Simulation
The lab includes a simulated SMTP demonstration to explain how attackers may abuse email infrastructure to distribute phishing messages.
The module demonstrates:
- How SMTP servers are used to send emails
- How attackers may attempt to disguise email sources
- Why SMTP misuse is a common phishing technique
- The purpose of this module is to educate users about how phishing emails are distributed and how to detect them.
- No real phishing campaigns are executed in the demo environment.

# Phishing Detection Guide & Analysis Toolkit

1. The detection module covers multiple areas used in phishing investigations:
- URL Analysis = Inspect suspicious links before interacting with them
- Email Header Analysis = Verify sender authenticity and mail routing
- Purpose & Intent Analysis = Identify psychological manipulation techniques
- IP & Domain Intelligence = Trace domain reputation and origin
- HTTP Headers & SSL Validation = Verify website authenticity
- IOC & Red Flags Detection = Identify indicators of compromise
These categories help users understand how phishing attacks can be identified and analyzed systematically.

2. Recommended Phishing Analysis Tools
The platform includes direct links to commonly used investigation tools that analysts use during phishing analysis.
> Examples include:
- VirusTotal – URL and file reputation scanning
- URLScan.io – Analyze website behavior and resources
- Google Safe Browsing – Check if URLs are flagged as malicious
- PhishTank – Community-verified phishing reports
- ANY.RUN – Dynamic analysis environment
- More than 25 investigation tools are included to help users explore different phishing detection techniques

3. Detection Checklist (Do & Don't Guide)
Each category includes a structured checklist to help users quickly identify suspicious behavior.
> Examples include: URL Analysis
Do:         
- Verify the domain spelling
- Check HTTPS certificate validity
- Confirm the legitimate domain structure
- Inspect URL parameters carefully
Don't:
- Trust shortened URLs without previewing them
- Ignore suspicious subdomains
- Click links with unusual redirects
- Trust domains with look-alike characters

> Example comparisons:
- ✔ facebook.com  ❌ faceb00k.com
- ✔ login.facebook.com  ❌ facebook.login.evil.com


# Security & Ethical Disclaimer
- This project was created strictly for cybersecurity education and social engineering awareness
- The platform demonstrates how phishing and social engineering techniques work so that users can better understand how attackers operate and how such attacks can be detected and prevented.
- All simulations in this lab are performed in a controlled environment.
  
The project does not support or encourage illegal activities, and the platform is intended only for:
- Security awareness training
- Cybersecurity research
- Educational demonstrations
- Features such as message generation, SMTP simulation, and phishing page examples are implemented only to help users recognize and defend against real-world phishing attacks.

Responsible Use Notice:
- Users of this platform are expected to use it responsibly and ethically.
- The knowledge provided in this lab should only be used to:
- Improve cybersecurity awareness
- Understand social engineering techniques
- Strengthen defenses against phishing attacks
- Any misuse of the concepts demonstrated in this project is strictly discouraged.

Final Note
- Understanding how attackers operate is a critical step in building stronger security defenses 
- This project aims to help students, cybersecurity enthusiasts, and professionals learn how social engineering attacks are structured and how they can be identified and prevented 


# About the Author
This project was developed by Vishnu Biradar, a cybersecurity enthusiast interested in understanding how cyber attacks work and how they can be detected and prevented.

My focus areas include:
- Social Engineering Analysis
- Phishing Detection
- Security Awareness Training
- SOC Analyst Investigation Techniques
- Cybersecurity Lab Development
Through projects like this lab, I aim to explore how attackers use psychological manipulation techniques and how security professionals can identify and stop such threats.

Contact
> If you have feedback, suggestions, or would like to discuss cybersecurity topics, feel free to connect.
- GitHub: https://github.com/vishnu026-coder
- Linkedin: https://www.linkedin.com/in/vishnu-biradar-138abb287/
- social media: https://biolinko.me/Maxz
- Portfolio: www.itzvishnu.bio
- Blog Website: https://xoin.in

> Support the Project
- If you found this project useful for learning about phishing detection and social engineering awareness, consider:
⭐ Starring the repository
- Sharing it with other cybersecurity learners
- Providing feedback or suggestions for improvement.

