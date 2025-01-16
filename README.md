# AI Call Agent 📞🤖

This project is an AI-powered call agent built using **Node.js**, **Twilio**, and **Google Generative AI**. The application allows users to interact with an AI chatbot via phone calls or SMS. 

---

## Features

- **Voice Interaction**: Speak to the AI chatbot during a phone call, and it responds in a conversational tone.
- **SMS Support**: Send SMS messages with optional image attachments.
- **Twilio Integration**: Manages phone call and SMS functionalities.
- **AI-Powered Responses**: Uses Google Generative AI (Gemini) to generate natural and relevant conversational responses.
- **Web Dashboard**: Includes static web pages for system interaction.
- **Car Sales Assistant**: There is also a Car-guide Web app (created with html (for frontend) and python (for backend)) which allows customers to communicate with AI to guide in purchasing cars through voice.
---

## Installation

1. **Clone the repository**: 
    ```
    git clone https://github.com/Kausheya2006/ai_call_agent.git
    cd ai-call-agent
    ```

2. **Install Dependencies**
    ```
    npm install
    ```

3. **Set Up Environment Variables**
    ```
    TWILIO_ACCOUNT_SID=your_twilio_account_sid
    TWILIO_AUTH_TOKEN=your_twilio_auth_token
    TWILIO_PHONE_NUMBER=your_twilio_phone_number
    GEMINI_API_KEY=your_google_generative_ai_api_key
    PORT=3000
    ```


4. **Start the server**

    Inside /encode2/ai-phone-agent, type
    ```
    node server.js
    ```

### Alternately, if you wish to use the python server follow the steps:

1. **Create a virtual environment**
    ```
    python -m venv venv
    source venv/bin/activate   # venv\Scripts\activate (for windows)
    ```

2. **Install Dependencies**
    ```
    pip install -r requirements.txt 
    ```

## How to Use

1. Enter your phone number(used for verifying twilio number).

2. Click on Make Call.

3. Wait for the call to arrive from your twilio number.

4. Press any key to execute the code.

5. Press 1 to enable the AI interactive call.


## Demo
[Watch the demo for Car-Sales-Assistant on YouTube](https://youtu.be/i9_xem5R6eA)

