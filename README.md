# 🛡️ Al-Muraqib (المراقب) | AI-Powered Gheeba Detection

**Al-Muraqib** is an intelligent assistant that helps users monitor their conversations in real-time to avoid "Gheeba" (backbiting). By leveraging state-of-the-art Deep Learning models, the system analyzes Egyptian Arabic speech to detect negative context and alerts the user.

## 🚀 Technical Stack
* **Speech-to-Text (ASR):** OpenAI Whisper (Tiny/Base) for high-accuracy Arabic transcription.
* **NLP/Deep Learning:** Fine-tuned **MARBERTv2** for Egyptian Dialect Hate Speech & Offensive Language detection.
* **Backend:** Python (FastAPI/Flask) - *[Work in Progress]*
* **Mobile:** Flutter - *[Planned]*

## 🛠️ How it Works
1. **Audio Capture:** Records or stream audio conversations.
2. **Transcription:** Converts Egyptian Arabic speech into text with timestamps.
3. **Sentiment & Intent Analysis:** Uses a Deep Learning classifier to detect if the context involves "Gheeba" or negative mention of others.
4. **Instant Alerting:** Notifies the user with a timeline of the detected moments.

## 📈 Model Information
The core analysis is powered by a fine-tuned version of `MARBERTv2` specifically trained on Egyptian-Arabic datasets to understand slang, sarcasm, and cultural nuances.
