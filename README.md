# TravelItinera

A personalized, AI-powered day trip itinerary generator built using **LangChain**, **Groq API**, **LangGraph**, and **Gradio**. Users can input a city and their interests, and the system generates a structured, interest-aligned itinerary in seconds.

## ✨ Features

- 🧠 Powered by LLaMA 3 (Groq API) for fast, high-quality itinerary generation
- 🔄 Modular flow built using LangGraph for easy step-by-step processing
- 🎨 Simple and elegant UI with Gradio
- 📍 User inputs: City + Interests → 📋 Output: Bullet-style itinerary with tips

---
## Important Note

This project was originally created in a Jupyter notebook environment (like Google Colab or Jupyter Lab). The code is designed to be run in a notebook environment for the best experience, especially for visualizations and interactive components.

## 🚀 How to Set Up and Run the Project

### 🔧 Prerequisites

- Python 3.8 or higher
- An API key from [Groq](https://console.groq.com/)
- pip (Python package manager)

### 📁 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/travel-itinerary-planner.git
   cd travel-itinerary-planner

2. **(Optional but Recommended) Create a Virtual Environment**

```bash
python -m venv venv
source venv/bin/activate          # macOS/Linux
.\venv\Scripts\activate           # Windows
```
3. **Install the Required Packages**

```bash
pip install -r requirements.txt
Set Your Groq API Key
```

You can either:

Replace the hardcoded value in the Python script:

python
groq_api_key="your_actual_groq_api_key"
Or export it as an environment variable:

```bash
export GROQ_API_KEY=your_actual_key    # macOS/Linux
set GROQ_API_KEY=your_actual_key       # Windows
```
🧾 Requirements
Below is the content of the requirements.txt file:

txt
langchain
langchain_core
langchain_groq
langchain_community
langgraph
gradio
If you're not using a requirements.txt file, you can install them manually:

```bash
pip install langchain langchain_core langchain_groq langchain_community langgraph gradio
```

🖼️ How to Run
Run the following command in your terminal:
```bash
python main.py
Then open the link in your browser provided by Gradio.
Input your city and interests, and receive a customized itinerary instantly!
```
🗂️ Project Structure
```bash
travel-itinerary-planner/
├── main.py               # Core application with LangGraph and Gradio
├── requirements.txt      # List of dependencies
└── README.md             # Project documentation (this file)
```

🔮 Example Use Case
City: Tokyo
Interests: Anime, street food, temples

🧾 Output: A curated morning to night plan with local breakfast spots, anime-related attractions, temple visits, food markets, and sunset views — all based on your interests.

🔧 Future Enhancements
🗓️ Multi-day itinerary support

🧭 Map & navigation integration

📂 Save and export options (PDF/Share)

🧑‍🤝‍🧑 Social travel planning features

📍 Integration with user location and real-time events

🤝 Contributing
Contributions are welcome!
Feel free to fork this repo and submit pull requests. For major changes, please open an issue first to discuss the idea.

📜 License
This project is licensed under the MIT License.

🙌 Acknowledgments
LangChain

Groq API

LangGraph

Gradio