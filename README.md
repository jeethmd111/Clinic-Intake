# Jithendra Clinic Intake

A healthcare web app that helps clinics collect patient symptoms and suggests how urgent each case is.

Live demo: https://jeethmd111.github.io/Clinic-Intake/

## Features
- Patient intake form: name, age, symptoms, duration, severity, allergies/medications, preferred time
- Urgency suggestion: Emergency, Urgent or Routine, with the reason shown
- Emergency red-flag alerts that tell patients to call 000
- Symptom category detection (respiratory, digestive, skin, etc.)
- Copyable and printable clinic intake sheet
- Responsive design with light and dark mode

## How it works
Keyword rules check for red-flag and urgent symptoms. Severity score, duration and age then adjust the result. The triage is rule-based, not live AI, so it can miss unfamiliar wording.

## Built with
- HTML, CSS and JavaScript (single file, no installation needed)
- Claude (Anthropic) as the AI tool used to plan, write and refine the code

## Run it
Download index.html and open it in any browser.

## Disclaimer
This is a demonstration prototype and is not medical advice. In an emergency call 000 (Australia).

## Author
Jithendra
