# Smart Email Assistant

An automated email processing system that classifies incoming emails into HR/IT/Other categories using machine learning (Random Forest/XGBoost). The current implementation shows classification confidence percentages but response generation functionality is temporarily disabled. Includes Streamlit UI for testing.

## 🚀 Setup
1. **Download ZIP**:
   - Click `Code` → `Download ZIP` on GitHub
   - Unzip using: `unzip smart-email-assistant.zip` (Linux/Mac) or right-click → "Extract All" (Windows)

2. **Install requirements**:
   ```bash
   pip install -r requirements.txt
   python -m nltk.downloader punkt stopwords

      python -m nltk.downloader punkt stopwords
# Run the app:

streamlit run app.py
⚠️ Note: Currently only shows classification results (category + confidence). Response generation is under maintenance.

Project Structure
text
smart-email-assistant/
├── agents/           # Classification logic
├── data/            # Sample emails dataset
├── models/          # Pretrained ML model
└── app.py           # Streamlit interface

Key features:
- Focuses on working ML classification
- Clear download/unzip instructions
- Explicit note about disabled response generation
- Minimal setup steps
