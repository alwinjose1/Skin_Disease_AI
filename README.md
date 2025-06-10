# 🧠 Skin Disease AI

Skin Disease AI is an intelligent web-based tool that uses deep learning to predict skin diseases from images and symptoms. This project helps users get fast, preliminary analysis of common dermatological conditions using an AI model trained on real-world skin data.

🌐 **Live Demo:**  
🔗 [https://teledermatologis-ai.streamlit.app/](https://teledermatologis-ai.streamlit.app/)

---

## 🔍 Features

- 📷 Upload skin images for disease detection using Convolutional Neural Networks (CNNs)
- 🩺 Input symptoms for enhanced prediction accuracy
- 🧑‍⚕️ Doctor-patient module for consultation & management
- 📊 Admin dashboard for managing data and users
- 💬 Instant results with modern UI and easy navigation

---

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript (or Flutter, if applicable)
- **Backend**: Python, Flask / FastAPI
- **AI/ML**: CNN models (Keras/TensorFlow or PyTorch)
- **Database**: MySQL / Firebase
- **Deployment**: Streamlit, GitHub, Heroku / Render

---

## 🚀 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/alwinjose1/Skin_Disease_AI.git
cd Skin_Disease_AI

# (Optional) Create a virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows
source venv/bin/activate  # On macOS/Linux

# Install required packages
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
