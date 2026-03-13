# Social Engineering Awareness & Phishing Simulation Lab

Project Overview: 
This project is an educational platform designed to demonstrate how social engineering and phishing attacks work. The lab helps users understand the psychological techniques attackers use and teaches how such attacks can be detected and prevented.
The platform simulates phishing scenarios in a controlled environment to improve cybersecurity awareness and SOC investigation skills.


< Live Demo: https://practicalabyxoin.vercel.app     //demo access: username: @The_Minimum | Psd: @The_MinimuM >

# Telegram-Based User Verification 
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

=========================================================================================================================================================================
# Tech Stack:
This project demonstrates the use of multiple technologies and APIs:
- HTML, CSS, JS, React For Development
- AI message generation using OpenAI GPT
- User verification using Telegram Bot API
- SMTP simulation for phishing awareness
- Frontend deployment via Vercel

# Key Learning Goals
- This lab helps demonstrate:
- Social engineering psychology
- Phishing message creation patterns
- Email attack techniques
- Security awareness training
- AI misuse in phishing campaigns
- Understanding attacker workflows
  
# Target Audience
- This project is useful for:
- Cybersecurity students
- SOC analyst learners
- Security awareness trainers
- Developers interested in phishing detection
- Anyone learning about social engineering threats

=========================================================================================================================================================================

* Features:

1. Social Engineering Technique Simulator
Demonstrates common manipulation techniques used in phishing attacks:
- Curiosity
- Urgency
- Fear
- Reward
- FOMO (Fear of Missing Out)
- Fake Support Requests
# Users can explore how attackers craft messages using these psychological triggers.

2. AI Phishing Message Generator
The platform includes an AI tool that demonstrates how phishing messages can be generated based on specific social engineering techniques.
Users can:
1.Select a social engineering technique
2.Generate a sample phishing message
3.Customize the message
4.Learn why the message may trick users
# This feature is designed for awareness training purposes only.

3. Hook and Message Combination System
Users can select:
1.Social engineering technique
2.Message template
3.Hook scenario
4.The system demonstrates how attackers combine these elements to craft convincing phishing messages.
# This helps users understand how phishing campaigns are structured.

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
# These pages are visual simulations only used to teach how phishing websites look.

5. AI Phishing Message Awareness Tool
The platform integrates the OpenAI GPT API to demonstrate how attackers may use AI to generate convincing phishing messages.
Users can:
- Select a social engineering technique
- Generate example phishing messages
- Customize message structure using Ai
- Understand how AI can be misused to craft suspicious emails
# The feature helps users recognize AI-generated phishing attempts and understand the risks of automated social engineering.

6. SMTP Phishing Simulation
The lab includes a simulated SMTP demonstration to explain how attackers may abuse email infrastructure to distribute phishing messages.
The module demonstrates:
- How SMTP servers are used to send emails
- How attackers may attempt to disguise email sources
- Why SMTP misuse is a common phishing technique
- The purpose of this module is to educate users about how phishing emails are distributed and how to detect them.
# No real phishing campaigns are executed in the demo environment.

5. Phishing Awareness Education
The platform also explains:
- How phishing emails are crafted
- Psychological manipulation tactics
- Warning signs of phishing
- How users can protect themselve

=========================================================================================================================================================================

# Security & Ethical Disclaimer:

> This project was created strictly for cybersecurity education and social engineering awareness

> The platform demonstrates how phishing and social engineering techniques work so that users can better understand how attackers operate and how such attacks can be detected and prevented.

> All simulations in this lab are performed in a controlled environment.

> The project does not support or encourage illegal activities, and the platform is intended only for:
- Security awareness training
- Cybersecurity research
- Educational demonstrations
- Features such as message generation, SMTP simulation, and phishing page examples are implemented only to help users recognize and defend against real-world phishing attacks.


# Responsible Use Notice:

> Users of this platform are expected to use it responsibly and ethically.

> The knowledge provided in this lab should only be used to:

> Improve cybersecurity awareness

> Understand social engineering techniques

> Strengthen defenses against phishing attacks

> Any misuse of the concepts demonstrated in this project is strictly discouraged.


# Final Note

< Understanding how attackers operate is a critical step in building stronger security defenses >

< This project aims to help students, cybersecurity enthusiasts, and professionals learn how social engineering attacks are structured and how they can be identified and prevented > 







