# Safety-At-Your-Fingertips
A platform designed to enhance women’s safety through real-time alerts, emergency features, and location tracking. Empowering women with the tools to stay secure at all times.

# Problem Statement
Personal safety has become an increasing concern, particularly for individuals who may be at risk of harassment, assault, or other emergencies. In these situations, immediate help is crucial, but many people struggle to reach out for assistance due to factors like physical limitations, fear, or a lack of awareness. Furthermore, language barriers and technology issues can prevent effective communication during crises. Many existing safety tools do not provide real-time location tracking, distress sound detection, or support for multiple languages, making them less effective in urgent situations.

Our challenge was to create a simple yet comprehensive solution that enables individuals to act swiftly in emergencies. This solution needed to allow users to alert their emergency contacts, detect distress signals, and offer real-time location tracking. It had to be user-friendly, inclusive, and accessible, regardless of the user's technological skills or language.

# Innovative Idea and Solution
To solve this problem, we developed Safety-At-Your-Fingertips, a gender-neutral website that ensures the safety of individuals. Safety-At-Your-Fingertips integrates multiple innovative features that offer immediate assistance during emergencies, such as distress sound detection, real-time location sharing, and emergency alerts. Our platform is designed to be intuitive, accessible, and supportive, empowering users to get the help they need quickly and effectively.

# Our Innovative Approach
Safety-At-Your-Fingertips leverages crowd-sensing technology to suggest the safest routes for users and sends notifications if they stray from their path, helping them avoid potential hazards in emergency situations. By combining AI, real-time tracking, and multilingual support, our platform offers a unique and all-encompassing solution for personal safety. These features work together to empower individuals, giving them the tools to stay in control of their safety and communicate effectively during critical moments.

# Features
# SOS Button:
The website features an SOS button that, when pressed, sends an SMS to predefined emergency contacts and shares the user’s real-time location.

# Send SMS to Emergency Contacts:
When the SOS button is clicked, an SMS is automatically sent to the user’s emergency contacts, notifying them of the user's distress and location.

# Real-Time Location Tracking:
Upon pressing the SOS button, the website tracks and shares the user’s real-time location with emergency contacts, using the Leaflet API.

# Distress Sound Detection:
The website uses a speech model and TensorFlow for scream recognition, automatically triggering the SOS function when distress sounds (e.g., screams) are detected.

# Chatbot Integration:
A chatbot on the website assists users by performing safety-related actions. It is powered by Google API and OpenAI API. While OpenAI API is not yet fully implemented, we aim to complete this feature in future updates.

# Safe Route Detection:
Using Leaflet API and Twilio, the website can identify the safest route to the user’s destination based on crowd-sensing data and will alert users if they deviate from the route.

# Multilingual Support:
The website currently supports English, Malayalam, and Hindi, with plans to extend language support to reach a larger audience.

# Audio/Video Evidence:
The website can record audio and video for evidence. These media files can be kept for reference in case of emergency.
