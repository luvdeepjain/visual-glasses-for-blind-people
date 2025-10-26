# visual-glasses-for-visually-impaired-people

Project Overview: Smart Glasses for Visually Impaired People
Smart Glasses for Visually Impaired People is an innovative, glasses-mounted device designed to enhance the safety and independence of visually impaired individuals. It integrates two crucial technologies—an ultrasonic sensor and a web camera—to provide comprehensive environmental awareness through intuitive, customizable voice commands.

Why It Matters (The Problem)
Current mobility aids fall short. Traditional white canes only detect ground-level obstacles, missing dangers at head height. High-tech solutions, while powerful, are prohibitively expensive (over ₹1 Lakh), making them inaccessible to most. Smart Glasses for Visually Impaired People bridges this critical gap, offering an affordable yet advanced solution.

How It Works (Functionality)
The device operates on two parallel, prioritized systems:

1. Real-Time Obstacle Detection (Ultrasonic):

Function: Continuously scans the area ahead.

Feedback: Provides instant audio cues: "Go" if the path is clear (beyond 3.3 meters) and "Don't Go" if an obstacle is detected within 3.3 meters. This is a critical safety alert.

Customization: All voice commands are language-customizable (e.g., Hindi, English, Tamil).

2. On-Demand Visual Information (Camera):

Function: When the user presses a button, the integrated web camera captures an image (e.g., a sign, a notice board).

Feedback: Uses OCR (Optical Character Recognition) to convert text in the image into digital text, which is then spoken aloud via Text-to-Speech (TTS).

Purpose: Allows users to "double-check" their surroundings for specific information.

Technology & Status
Built on a Raspberry Pi 5, Smart Glasses for Visually Impaired People uses Python programming with libraries like gpiozero, opencv-python, pytesseract, and pyttsx3. We have a fully integrated working prototype (TRL 5), with current efforts focused on software refinement, bug fixing, and optimizing audio priority.

Impact & Vision
Smart Glasses for Visually Impaired People directly addresses UN Sustainable Development Goals 3 (Good Health & Well-being) and 10 (Reduced Inequalities). By offering dual-sensor technology for under ₹4,000, it empowers visually impaired individuals with unprecedented safety and independence, transforming accessibility from a luxury into an affordable reality.
