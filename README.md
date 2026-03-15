✈️ AI Tour Planner Pro
AI Tour Planner Pro is an intelligent travel companion built with Python, Streamlit, and Google’s Gemini 2.0 Flash. It transforms your travel preferences—destination, budget, duration, and interests—into a detailed, day-by-day itinerary complete with cultural insights, dining recommendations, and logistical tips.

✨ Features
Custom Itinerary Generation: Uses AI to create structured travel plans based on your specific pace and style (Balanced, Relaxed, Fast-Paced, etc.).

Interactive Chat: Refine your trip, ask for alternatives, or get specific advice through a natural conversational interface.

Quick Action Presets: Instantly generate packing lists, weather reports, or budget-friendly activity suggestions with one click.

Trip Dashboard: Keep track of your travel stats, including total trips planned and days covered.

Save & Export: Save your favorite itineraries to session storage or export the entire chat history as a JSON file for offline use.

Adaptive UI: A clean, sidebar-driven interface with emoji-rich formatting and a responsive layout.

🛠️ Tech Stack
Framework: Streamlit

AI Model: Google Gemini 2.0 Flash

Language: Python 3.9+

Data Handling: JSON for exports and Python Session State for persistence.

🚀 Getting Started
1. Prerequisites
A Google AI Studio API Key. Get one for free at aistudio.google.com.

Python installed on your machine.

2. Installation
Clone this repository and navigate to the project folder:

Bash
git clone https://github.com/yourusername/ai-tour-planner-pro.git
cd ai-tour-planner-pro
Install the required dependencies:

Bash
pip install streamlit google-generativeai
3. Configuration
The app looks for your API key in two places:

Streamlit Secrets: Create a .streamlit/secrets.toml file:

Ini, TOML
GEMINI_API_KEY = "your_api_key_here"
Environment Variable: Or set it in your terminal:

Bash
export GEMINI_API_KEY="your_api_key_here"
4. Running the App
Launch the application using Streamlit:

Bash
streamlit run app.py
📖 How to Use
Input Details: Use the sidebar to enter your destination and travel parameters.

Generate: Click "🚀 Generate Itinerary" to let the AI build your plan.

Refine: Use the chat box at the bottom to ask follow-up questions like "Can you swap Day 3 for more beach time?"

Save: Use the sidebar buttons to save the trip to your local session or export the data.

🗺️ Roadmap
[ ] Integration with Google Maps API for real-time location pins.

[ ] Multi-language support for international travelers.

[ ] PDF export functionality for printed itineraries.

[ ] Real-time flight and hotel price tracking.

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

Made with ❤️ for travelers everywhere.
