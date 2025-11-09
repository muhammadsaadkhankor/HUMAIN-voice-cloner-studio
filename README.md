# 🎙️ HUMAIN Voice Clone Studio

**HUMAIN Voice Clone Studio is an advanced AI-powered voice cloning system designed for creating realistic, expressive, and adaptive speech models. The platform enables users to record or upload voice samples, automatically generate transcriptions, and fine-tune personalized TTS voices capable of natural, emotion-aware speech synthesis**.

---

## 🚀 Features
- 🎧 **Voice Recording & Uploading:** Capture or upload custom voice samples.
- 🧠 **Automatic Transcription:** Speech-to-text processing for reference alignment.
- 🗣️ **Personalized Speech Generation:** Generate lifelike speech using cloned voices.
- 🧩 **Modular Design:** Separate backend (Python) and frontend (React/Next.js).
- 🧪 **Research-Oriented:** Built for experimentation and AI model testing within HUMAIN.

---

## 🛠️ Installation & Run

```bash
# 1. Create Conda Environment
conda create -n <env-name> python==3.11
conda activate <env-name>
# Tested with Python 3.11; versions >=3.11 are also supported

# 2. Clone the Repository
git clone https://github.com/muhammadsaadkhankor/HUMAIN-voice-clone-studio.git
cd HUMAIN-voice-cloner-studio

# 3. Install Backend Dependencies
pip install -r backend_requirements.txt
pip install -r requirements.txt

# 4. Setup Frontend
cd frontend
npm install
cd ..

# 5. Run Backend
python app.py

# 6. Run Frontend
cd frontend
npm start
# HUMAIN-voice-clone-studio
# HUMAIN-voice-cloner-studio
