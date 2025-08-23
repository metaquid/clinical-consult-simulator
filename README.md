Clinical Consult Simulator

![alt text](https://img.shields.io/badge/License-MIT-yellow.svg)
![alt text](https://img.shields.io/badge/version-7.2-blue)
![alt text](https://img.shields.io/badge/status-active-success)

An AI-powered training platform designed to help medical professionals master the art of doctor-patient communication in a safe, repeatable, and insightful environment.
(Placeholder for a GIF showing the app workflow: Setup -> Consultation -> Debriefing)
A brief animated GIF demonstrating the core loop of configuring a case, chatting with the AI patient, and reviewing the performance analysis dashboard would go here.

About The Project 
Medical education excels at teaching clinical science, but often falls short in providing practical, hands-on training for the nuanced art of communication. How does a resident practice delivering a terminal diagnosis? How can a doctor learn to build rapport with a skeptical patient?
Clinical Consult Simulator is a "flight simulator for doctors." It leverages the power of Large Language Models (LLMs) to create dynamic, realistic patient encounters. Practitioners can engage in challenging conversations, make decisions, and receive immediate, actionable feedback on their performance, all without the real-world consequences.
The goal is to build more empathetic, effective, and confident medical professionals, which leads to better patient trust and improved health outcomes.

Key Features

🧠 Dynamic AI Patient Generation: Go beyond static scripts. Define a patient's key symptoms and personality archetype (e.g., "anxious," "stoic," "angry"), and the AI generates a rich, detailed clinical and psychosocial profile for a unique encounter every time.

🎭 Three Distinct Training Modes:
Guided Tour: An interactive walkthrough of the app's features and a pre-scripted "best practice" consultation.
Manual Training Mode: You play the role of the doctor and interact directly with the AI patient.
AI Doctor Mode: Observe the AI playing both the doctor and patient roles to learn different communication strategies.

📊 Instant Performance Debriefing: Receive an immediate post-consultation analysis that includes:
Quantitative Dashboard: Graphical scores (1-10) for core competencies like Empathy & Rapport, Active Listening, History Taking, and Patient Management.
Qualitative Report: Written feedback from an "AI medical education expert" detailing your strengths, areas for improvement, and specific suggestions.

🚑 Realistic Scenario Presets: Start immediately with a range of challenging presets, including "ER: Potential Cardiac Event," "Primary Care: Breaking Bad News," and "Ethics: Disclosing a Medical Error."

🗣️ Immersive Audio Experience: An optional text-to-speech feature gives a voice to the patient, doctor, and narrator, enhancing realism.

🎨 Customizable UI: Choose from multiple themes (Teal, Medical Blue, Night Shift) to suit your preference.

🚀 Zero Backend Required: The entire application runs client-side in your browser. It's a single HTML file, making it incredibly portable and private. Your conversations and API keys are not stored on any server.

##Technology Stack
Frontend: Vanilla JavaScript (ES6+), HTML5, CSS3

##Core Logic:
Integration with Google Gemini API for patient generation, dialogue, and performance analysis.
Support for NVIDIA API for alternative LLM-driven dialogue.
Audio: Browser's native Web Speech API (SpeechSynthesis).
Getting Started
To get a local copy up and running, follow these simple steps.

##Prerequisites
You will need API keys from a supported provider to power the simulation. The analysis feature specifically requires a Google Gemini key.
Google Gemini API Key: Get one from Google AI Studio.
NVIDIA API Key (Optional): Get one from the NVIDIA API Catalog.

##Installation
Clone the repository:
code
Sh
git clone https://github.com/your-username/clinical-consult-simulator.git
Open the file:
Navigate to the cloned directory and open the ccs-v29.html file directly in a modern web browser (like Chrome, Firefox, or Edge). No web server is needed.
Enter your API Key:
Click the "Configure Case" button to open the settings panel.
In the "1. Setup" tab, paste your Google Gemini API key into the appropriate field.
The simulator is now ready to use!

##Usage
Choose Your Mode:
For a first-time user, keep Demo Mode enabled and click "Start Guided Tour".
To start training, disable Demo Mode.
Configure Your Case:
Patient Profile Tab: Enter key symptoms and a patient archetype, then click "Generate Profile via LLM".
Clinical Scenario Tab: Select a preset or write your own description of the clinical setting.
Start the Consultation: Click "Start Consultation". The AI patient will deliver an opening line.
Interact: Type your responses as the doctor and click "Send". The AI will generate the patient's reply based on their profile and the conversation history.
Get a Debrief: When the consultation feels complete, click "Request Debrief". The system will analyze the entire conversation and generate your performance report.

##Roadmap
Here are some planned enhancements for future versions:
Voice Input (Speech-to-Text): Allow the user to speak their responses as the doctor for a more natural interaction.
Case Import/Export: Activate the functionality to save, load, and share complete case configurations as .json files.
User Progress Dashboard: Implement a system to track performance metrics across multiple sessions to visualize improvement over time.
Expanded Scenario Library: Add more complex scenarios covering a wider range of medical specialties and ethical dilemmas.
License
Distributed under the MIT License. See LICENSE for more information.
