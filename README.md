# AI-Powered Travel Planner 🌍✈️

Welcome to the AI-Powered Travel Planner! This innovative project leverages the power of AI to create personalized travel itineraries, making your trip planning process smoother and more enjoyable.

## 🚀 Features

- **7-Day Travel Itinerary**: Get a detailed day-by-day plan for your trip.
- **City Selection**: AI-powered analysis to choose the best city for your vacation.
- **Local Insights**: Gain valuable information from a virtual local tour guide.
- **Budget Planning**: Receive a breakdown of expected costs for your trip.
- **Packing Suggestions**: Get customized packing tips based on your destination and travel dates.
- **Safety Tips**: Stay informed with important safety advice for your chosen location.

## 🛠️ Technologies Used

- [CrewAI](https://github.com/joaomdmoura/crewAI): For orchestrating AI agents
- [LangChain](https://python.langchain.com/): For building AI applications
- [Groq](https://groq.com/): Powering our language models
- [DuckDuckGo Search](https://pypi.org/project/duckduckgo-search/): For web searches

## 📋 Prerequisites

- Python 3.8+
- Groq API key

## 🔧 Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/ai-powered-travel-planner.git
   cd ai-powered-travel-planner
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Set up your environment variables:
   Create a `.env` file in the root directory and add your Groq API key:
   ```
   GROQ_API_KEY=your_api_key_here
   ```

## 🚀 Usage

Run the main script to start planning your trip:

```
python main.py
```

Follow the prompts to input your travel preferences:
- Origin city
- Potential destination cities
- Date range for your trip
- Your interests and hobbies

The AI will then generate a comprehensive travel plan for you!

## 🧠 How It Works

This project uses a crew of AI agents, each with specific roles:

1. **Expert Travel Agent**: Orchestrates the overall planning process.
2. **City Selection Expert**: Analyzes and selects the best city based on your preferences.
3. **Local Tour Guide**: Provides detailed insights about the chosen destination.

These agents work together to create a tailored travel experience just for you!

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- [Groq](https://groq.com/) for providing the powerful language models.
- [CrewAI](https://github.com/joaomdmoura/crewAI) for the AI agent orchestration framework.
- [LangChain](https://python.langchain.com/) for the tools to build AI applications.

## 📞 Contact

For any questions or feedback, please open an issue on this repository.

Happy travels! 🌴🗺️🧳
