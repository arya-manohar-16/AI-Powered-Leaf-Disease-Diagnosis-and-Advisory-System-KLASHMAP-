# AI-Powered-Leaf-Disease-Diagnosis-and-Advisory-System-KLASHMAP-

🌱 Plant Disease Diagnosis AI Web App
📌 Overview
The Plant Disease Diagnosis AI Web App helps farmers and gardeners identify plant diseases instantly by uploading an image of the plant.
The app connects to an AI workflow in Relay App which analyzes the plant image and returns:


    🦠 Disease name

    📆 Expected life span

    💊 Solution / Treatment

    🧪 Recommended pesticides

The Advices are displayed directly on the web frontend in a clean, user-friendly interface.

🚀 Features
  Image Upload – Upload any plant image from your device.

  AI Diagnosis – Integrated with Relay App workflow for plant disease detection.

  Instant Results – Get plant type, disease, and treatment within seconds.

  Responsive Design – Works on desktop, tablet, and mobile.

  Error Handling – Displays an error message if no diagnosis is found.

🛠️ Tech Stack
  Frontend:

    HTML5, CSS3, JavaScript

    Responsive styling with Flexbox/Grid

  Backend / AI Integration:

  Relay App API (AI workflow)

  Fetch API for async data retrieval

⚙️ How It Works
User uploads plant image via the frontend.

Frontend sends the image to Relay App AI workflow endpoint.

Relay App processes the image and returns a JSON response.

Frontend extracts details and displays them in a results section.

🔧 Setup Instructions

1️⃣ Clone the Repository

    git clone https://github.com/<your-username>/plant-disease-diagnosis.git
    cd plant-disease-diagnosis

2️⃣ Configure Relay App API

Open script.js

Find the section:

    const RELAY_API_URL = "<Your Relay App Endpoint>";
    const RELAY_API_KEY = "<Your API Key>";
Replace with your actual Relay App endpoint & API key.

3️⃣ Run Locally

Simply open index.html in a browser, or use a local server.

🤝 Contributing
Pull requests are welcome!
If you find a bug or have suggestions, open an issue.

💡 Future Scope
Add multilingual support for farmers in different regions.

Offline mode with TensorFlow.js model.

Mobile app integration.
