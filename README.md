# 🚀 Log Event Intelligence - Inference Pipeline (Non-Modifiable)

> 🧠 A fully working log classification system built using **TensorFlow/Keras** with **NLP** – designed for production-grade inference on unseen log data using a **multi-input, multi-output model architecture**.

## ✅ What It Does

- Predicts log severity: `Error`, `Warning`, `Information`, `Verbose`
- Uses **NLP** to extract patterns and summarize insights
- Employs **multi-input** (text, time, source, event metadata) and **multi-output** (Level, Source, Task Category, Event ID)
- Adds confidence scores, severity scaling, and message summaries
- Produces **Power BI-ready** enhanced CSV output
- Generates a log distribution **bar/pie chart** using Matplotlib

## 🔍 Output Preview

📊 Enhanced results: `enhanced_inference_results.csv`  
📈 Chart: `log_level_pie.png`  
🧠 NLP Insights: Included in report  
📁 Dashboard-ready: Fields normalized and cleaned for BI

## 🧠 Architecture Highlights

- **Framework**: TensorFlow/Keras  
- **Model Type**: Multi-Input Multi-Output Functional Model  
- **Inputs**:  
  - Log message text (vectorized)  
  - Source, Task Category (label encoded)  
  - Event ID (log-scaled)  
  - Hour & Weekday (temporal context)  
- **Outputs**:  
  - Predicted Severity Level  
  - Event ID (regression)  
  - Source  
  - Task Category  

## 📜 License

Licensed under the **MIT License**  
✔ Free to **use or copy as-is**  
❌ **Modification of code is not permitted**  
📎 Attribution must be retained (see `LICENSE.txt`)

## 📌 About Me

> 👩‍💻 I bring 11 years of EUC & 1.5 years of GEN expertise, with focus on practical automation using AI — including inference design, system intelligence, and production-ready analytics.

🔗 Let's connect: [LinkedIn](www.linkedin.com/in/joyita-roy-barman-dasgupta-77287985) | [Email](mailto:jrafflashia@gmail.com)

