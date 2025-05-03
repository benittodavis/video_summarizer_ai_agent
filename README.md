# 🎥 Video Summarizer AI Agent

A multimodal AI-powered video analysis tool built with **Google Gemini 2.0**, **Streamlit**, and **Phi Framework**. Upload any video and ask questions—the agent will understand the video content, perform real-time web search (via DuckDuckGo), and generate a smart, context-aware summary.

---

## 🚀 Features

- ✅ Upload `.mp4`, `.mov`, or `.avi` video files
- 🧠 Ask any question about the video content
- 🔍 Real-time web search for added context using DuckDuckGo
- ⚡ Powered by Gemini 2.0 Flash Exp
- 🎨 Clean and interactive UI built with Streamlit
- 📁 Temporary video storage with automatic cleanup

---

## 🛠️ Tech Stack

- **[Streamlit](https://streamlit.io/)** – Frontend interface
- **[Google Generative AI (Gemini)](https://ai.google.dev/)** – Vision + language model
- **[Phi Framework](https://phi.build/)** – Agent orchestration and tool management
- **DuckDuckGo Tool** – Web search integration
- **Python**, **dotenv**, **tempfile**, **Pathlib**

---

## ⚙️ Installation

1. **Clone the repo:**

   
   git clone https://github.com/your-username/video-summarizer-agent.git
   cd video-summarizer-agent
   
3. **Install dependencies:**

    pip install -r requirements.txt

4. **Set your environment variables:**
    Create a .env file with your Google API Key:
      GOOGLE_API_KEY=your_api_key_here

5. **Run the app:**

    streamlit run app.py


   
