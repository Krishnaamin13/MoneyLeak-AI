💰 MoneyLeak AI

AI-powered financial leakage detection system built during GDG Hackathon.

📌 Live Demo

🔗 https://money-ai-39np.onrender.com
MoneyLeak AI is deployed using Streamlit and allows users to:

- Set monthly budgets
- Track expenses
- Detect financial leakage patterns
- Get AI-based insights
- Perform “What-If” simulations

⚠️ Note: The deployed version may use temporary/demo data for demonstration purposes.

📌 Problem Statement

Many individuals and small businesses lose money due to unnoticed recurring subscriptions, hidden charges, and inefficient spending patterns.
MoneyLeak AI helps detect such financial leaks using intelligent analysis and visualization.

🛠 Tech Stack

Python
Streamlit
Pandas
SQLite
Scikit-learn

⚙️ Core Features

- 🧠 Behavioral AI – Learns user spending habits
- 📊 Risk Intelligence – Detects financial leakage patterns
- 🔮 What-If Simulation – Simulate financial decisions safely
- 📈 Interactive Dashboard – Visual insights using Streamlit

🗂 Project Structure
app.py          → Streamlit frontend
backend.py      → Core logic & processing
moneyleak.db    → SQLite database

▶️ Run Locally
pip install -r requirements.txt
streamlit run app.py
