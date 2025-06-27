# 🌍Smart City Sustainability Assistant

An *AI-powered urban sustainability toolkit* built using *Gradio* and *IBM Granite LLM*.  
This assistant helps citizens, city planners, and researchers with tools for *waste management, **energy saving, **eco challenges, **policy summarization, **KPI forecasting, **anomaly detection, and **citizen feedback collection*.

---

## 🚀 Features

| Tab | Feature |
|-----|---------|
| ♻ Waste Management | Get recycling/disposal instructions for common items |
| ⚡ Energy Savings | Personalized energy-saving tips based on usage habits |
| 📝 Feedback Collection | Collect and export citizen feedback (Excel & CSV support) |
| 🌿 Daily Challenge | Randomized green challenges to promote eco-behavior |
| 📑 Policy Summary | Summarize long policy documents using IBM Granite |
| 📊 KPI Forecast | Forecast future water/energy usage from CSV data |
| 💡 Eco Tips | Generate sustainability tips for any topic |
| 🔍 Anomaly Detection | Detect spikes in energy data using statistical thresholds |
| 💬 Chat Assistant | Ask sustainability questions and get detailed answers |

---

## 🛠 Tech Stack

- [Gradio](https://www.gradio.app/) — UI framework for ML apps
- [IBM Granite LLM](https://huggingface.co/ibm-granite/granite-3.3-2b-instruct) — for natural language processing
- [Transformers](https://huggingface.co/docs/transformers) — model interface
- [Pandas, OpenPyXL, Tempfile] — for data processing and export
- Python 3.10+ recommended

---






## 🧪 Installation

First, install the required libraries:

```bash
pip install gradio pandas transformers openpyxl

Run the app:

python app.py  # or run the notebook in Google Colab

## 📁 Input File Formats
CSV Uploads: Required for KPI Forecasting & Anomaly Detection
Must contain columns: usage and date

## 📌 Notes
Uses IBM's granite-3.3-2b-instruct for all AI outputs.

Outputs are full and descriptive for policy, chat, and summaries.

Beautiful and responsive UI with tabs, gradients, and custom styles.

📚 Acknowledgements
🤖 IBM Granite LLM

🧪 HuggingFace Transformers

🎨 Gradio Interface

📊 Pandas

📄 License
This Project is licensed under the MIT License. See LICENSE file for details

## 🙌 Contributions
Bollavaram Anil Preetham - Designer & Developer
