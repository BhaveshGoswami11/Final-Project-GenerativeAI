# Medical-Personalized-ChatBot
# 🩺 AI Medical Chatbot 🤖  
[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-ff4b4b?logo=streamlit&logoColor=white)](https://streamlit.io)
[![LangChain](https://img.shields.io/badge/Powered%20by-LangChain-4b8bbe)](https://www.langchain.com/)
[![OpenAI GPT](https://img.shields.io/badge/Model-GPT--3-green?logo=openai)](https://platform.openai.com)

An interactive chatbot built to provide accurate and insightful responses to **medical questions** — from symptoms and treatments to health tips. 🧠💊

---

## 🧩 Features

✨ **Smart Medical Answers**  
🤝 **User-Friendly Chat Interface**  
⚡ **Fast Response Time**  
📚 **Backed by GPT-3 and LangChain**  
🌐 **Web-based Access with Streamlit**

---

## 📸 Sneak Peek

![Screenshot](https://github.com/BhaveshGoswami11/Final-Project-GenerativeAI/blob/main/Sneak%20Peek.png)

---

## 🚀 Quick Start

### 📥 Clone & Install

```bash
git clone https://github.com/your-username/medical-chatbot.git
cd medical-chatbot
pip install -r requirements.txt


Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/medical-chatbot.git
cd medical-chatbot
Create a virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Set environment variables:

OpenAI API Key:

bash
Copy
Edit
export OPENAI_API_KEY="your_openai_api_key"
Neo4j (if using):

bash
Copy
Edit
export NEO4J_URI="your_neo4j_url"
export NEO4J_USERNAME="neo4j"
export NEO4J_PASSWORD="your_neo4j_password"
Run the application:

bash
Copy
Edit
streamlit run app.py
Usage
Once the application is running, navigate to http://localhost:8501 in your browser.

Type your medical questions in the input box and receive responses from the chatbot.

Example questions:

"What are the symptoms of COVID-19?"

"How do I manage high blood pressure?"

"What are the common treatments for asthma?"

Project Structure
app.py: The main Streamlit app file where the chatbot is set up and the conversation logic is defined.

main.py: Contains the logic for generating responses based on user input (using OpenAI GPT-3).

requirements.txt: Lists the Python packages required to run the application.

assets/: Folder for any assets like images or external files (if any).

README.md: This file!

Contributing
Feel free to fork the repository, create a branch, and submit pull requests with improvements or bug fixes. If you have any suggestions, open an issue.

License
This project is licensed under the MIT License - see the LICENSE file for details.

References
LangChain Documentation

Streamlit Documentation

OpenAI GPT-3

Neo4j Documentation

Acknowledgements
Thanks to the OpenAI community for providing GPT-3 API.

Special thanks to Streamlit for creating an easy-to-use interface for deploying applications.

🔐 Set Environment Variables
bash
Copy
Edit
export OPENAI_API_KEY="your_openai_key"
If using Neo4j (optional):

bash
Copy
Edit
export NEO4J_URI="bolt://localhost:7687"
export NEO4J_USERNAME="neo4j"
export NEO4J_PASSWORD="yourpassword"
▶️ Run the App
bash
Copy
Edit
streamlit run app.py
💬 Sample Questions to Try

🧪 Category	                    💡 Example Questions
Diseases	                       What are the symptoms of diabetes?
Medications                    	 What is paracetamol used for?
First Aid	                       How should I treat a minor burn?
Nutrition	                       What are some foods rich in iron?
Mental Health	                   What are signs of anxiety or depression?
Fitness & Wellness	             How often should I exercise in a week?
📁 Project Structure
text
Copy
Edit
├── app.py                # Streamlit app
├── main.py               # Query logic & LLM integration
├── requirements.txt      # Required dependencies
└── README.md             # You're here!
📚 References
Here are the primary sources used to power and validate the medical content:

WebMD

Mayo Clinic

World Health Organization (WHO)

Healthline

MedlinePlus - U.S. National Library of Medicine

National Institute of Mental Health

Centers for Disease Control and Prevention (CDC)

Drugs.com - Drug Information Database

NIH: National Institutes of Health

Johns Hopkins Medicine

Cleveland Clinic

PubMed


🧠 Contributing
We welcome PRs, suggestions, and new features.
Feel free to fork and star ⭐ the project!
