# cervical-cancer-diagnostic-ai
🔬 Cervical Cancer Diagnostic AI A Deep Learning Project for "Add your preferred project Title"

👩‍💻 Project Team

*Lead Engineer: Theresa Mapfumo
**Institution: Harare Institute of Technology (HIT)
📌 Project Overview
This application leverages a ResNet-34 Convolutional Neural Network (CNN) to classify microscopic cervical cell images into four diagnostic levels (0-3). The model was trained using the SIPaKMeD dataset and achieved a validation accuracy of 97.8%.

🧬 Diagnostic Levels & Mapping
Level 0 (Normal): Superficial-Intermediate / Parabasal cells.
Level 1 (Benign): Metaplastic cells.
Level 2 (Pre-Cancerous): Koilocytotic cells.
Level 3 (Malignant): Dyskeratotic cells.
🚀 Deployment Instructions
1. Repository Preparation
Ensure your GitHub repository contains:

app.py: The main Streamlit interface script.
requirements.txt: Dependencies (fastai, streamlit, gdown, torch, torchvision).
README.md: This documentation.
2. Connect to Streamlit Cloud
Log in to Streamlit Share.
Click Create App > I already have an app.
Select this repository and set the Main file path to app.py.
Click Deploy.
🎨 Frontend Creative Brief
Note to the Frontend Developer: The "Engine" (AI Model) is ready. You have full creative control over the user interface. Please use your creativity to make this app look like a high-end medical tool.

Recommended Creative Tasks:

Visual Storytelling: Add a "Project Journey" section or an "About the Tech" expander that explains how the ResNet-34 architecture works.
Interactive UI: Use st.columns to create a side-by-side view of the uploaded image and the AI's heat-map or confidence charts.
UX Design: Design custom CSS or use Streamlit's "Wide Mode" to make the diagnostic results feel urgent and clear (e.g., using specific hex colors for medical warnings).
Documentation: Create an "Instructions for Pathologists" section in the sidebar to make the tool feel ready for a clinic.
🧪 How to Test the System
Open the App: Navigate to your live Streamlit URL.
Upload Image: Select a microscopic image from the SIPaKMeD dataset.
Analyze: The system will process the image and display the Diagnostic Level, a Confidence Score, and a color-coded risk assessment.
🛠️ Technical Stack
Backend: Python, Fastai, PyTorch
Frontend: Streamlit
Model Architecture: ResNet-34 (Transfer Learning)
Storage: Google Drive API (via gdown)
Disclaimer: This tool is developed for research and educational purposes as part of an Engineering Final Year Project. It is not intended for clinical use without professional medical supervision.
