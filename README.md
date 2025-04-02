# AI Media Assistant 🎥🖼️  

An AI-powered media assistant that can **generate images, create image captions, and summarize videos** using **Google's Gemini API**. Built with **Streamlit**, this interactive web app allows users to explore AI-driven media generation and analysis effortlessly.  

## 🚀 Features  
🔹 **AI Image Generator** – Generates high-quality images based on user prompts.  
🔹 **Image Caption Generator** – Automatically generates captions for uploaded images.  
🔹 **Video Summary Generator** – Extracts and summarizes key points from videos.  
🔹 **Interactive Web App** – Built with **Streamlit** for easy user interaction.  
🔹 **Deployed with ngrok** – Provides a public link to access the app.  

## 🛠️ Tech Stack  
- **Python** 🐍  
- **Streamlit** (for UI)  
- **Google Gemini API** (AI-powered image & text processing)  
- **ngrok** (for public deployment)  

## 📌 How to Run Locally  
1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/your-username/AI-Media-Assistant.git  
   cd AI-Media-Assistant  


Install Dependencies:

pip install -r requirements.txt  

Run the Application:

streamlit run AI_Media_Assistant.py  

(Optional) Deploy Using ngrok:

ngrok authtoken YOUR_NGROK_AUTH_TOKEN  
ngrok http 8501  
