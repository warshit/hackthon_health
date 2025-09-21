
## How It Works

- **User Interaction**:  
  Users enter their symptom description in the text field, or select a common symptom button.  
  The system then simulates message processing by analyzing the input text and determining the urgency.

- **Triage Analysis**:  
  The app uses pre-defined symptom keywords and triage rules to evaluate the user's input.  
  It assigns a level of urgency (`mild`, `moderate`, `severe`, `emergency`) and picks appropriate guidance.

- **Chat & Dashboard**:  
  The chat interface shows a conversation view populated with user messages and bot responses.  
  A clinician dashboard is available to view a historical log of all triage sessions along with timestamps and details.

- **Speech & Multilingual Support**:  
  Users can use the voice input feature to describe their symptoms, which leverages the Web Speech API for transcription.  
  A language selector is provided for extending support beyond English.

## Setup and Demo

1. **Download the Project**:  
   Save the `hello.html` file to your local machine.
2. **Run in Browser**:  
   Open the file in any modern browser (Chrome, Firefox, Edge, etc.).  
   No additional server setup is required since this app runs purely on the client side.

3. **Usage**:  
   - Type your symptom description or click on one of the common symptom buttons to get started.
   - Interact with the chatbot and observe guidance recommended based on the input.
   - Use the navigation buttons ('Dashboard' and 'FAQs') in the header for additional features.

## Customization

- **Sanity GROQ API Integration**:  
  While this demo uses local triage rules and mock data, you can integrate it with a Sanity GROQ API endpoint to fetch symptom details dynamically.  
  In that case, adjust the JavaScript fetch logic to query your Sanity dataset.

- **Styling and Layout**:  
  The project uses custom CSS with a responsive design. Feel free to tweak the styles to adjust the theme or accommodate additional components.

## Future Enhancements

- Implement a backend service to persist user sessions and improve analytics.
- Enhance multilingual support with automatic language detection.
- Integrate real-time location services to show nearby clinics based on user geolocation.

## License

This project is intended for demonstration purposes for hackathons and educational use.  
For any commercial usage or distribution, please consider appropriate licensing and compliance with healthcare data regulations.

---

This project was created to provide a hands-on demonstration of how digital triage can be implemented with modern web technologies. Enjoy exploring, and feel free to extend it for your needs!
