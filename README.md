# Hybrid AI Harassment Detector

This project is a demo web application that showcases a Hybrid AI Harassment Detector. The application simulates a chat interface where users can type messages, and the system detects harassment or toxic language in real-time using AI.

## Features

- **Real-time Harassment Detection:** As you type and send messages in the chat, the system uses AI to analyze your input and returns a toxicity score.
- **System Interventions:** If harassment or toxic language is detected, the system may display intervention messages or badges as feedback.
- **Simple and Interactive UI:** The interface is web-based with a clean, easy-to-use chat layout.

## How It Works

1. **User Input:** Type a message in the chat input box and click "Send" or press Enter.
2. **Detection Endpoint:** The frontend sends the message as a POST request to the `/detect` endpoint.
3. **AI Evaluation:** The backend analyzes the message for toxicity and harassment using a machine learning model.
4. **Feedback:** The UI displays the toxicity score, any system interventions, and badges if applicable.

## File Structure

- `index.html`: The main frontend file for the chat UI. 
- (Other backend and static files should be present in the project, but are not detailed here.)

## Usage

1. **Start the Backend Server:**  
   Ensure you have the backend server running that provides the `/detect` endpoint.

2. **Open the Frontend:**  
   Open `index.html` in your browser or access the deployed web application.

3. **Simulate Chat:**  
   Type messages and observe how the system responds to different kinds of input.

## Example

```
User: You are so dumb!
System: Toxicity score: 0.85
System: Please refrain from using abusive language.
Badge: Warning issued
```

## Requirements

- Python (for backend, if using Flask or similar framework)
- HTML/CSS/JavaScript for frontend
- AI/ML model for harassment detection (not included in this repo)

## Credits

Developed for the Hackathon project by [Mohan-sabbavarapu](https://github.com/Mohan-sabbavarapu).

## License

This project is for demonstration and educational purposes.
