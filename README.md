🎙️ Zoom Meeting Transcriber & Summarizer

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Whisper AI](https://img.shields.io/badge/AI-Whisper-000000?style=for-the-badge&logo=openai&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)


---

## 🌟 Features

- ✅ **100% Offline** — No internet required  
- 🚀 **Fast Transcription** — 1× real-time or better  
- 🔐 **Private by Design** — All data stays on your machine  
- 🧠 **AI-Powered Summaries** — Get concise meeting overviews  
- 🎧 **Speaker Detection** — See who said what  
- 📊 **Speaker Analytics Dashboard** *(coming soon)*

---

## 🖼️ Screenshots

| 🎛️ Terminal Interface | 📝 AI Summary |
|------------------------|----------------|
| ![Terminal Demo](./assets/terminal-demo.png) | ![Summary Output](./assets/summary-output.png) |

---

## 📄 Sample Outputs

### ✅ Transcription Output
[00:01:23] John: Let's discuss the Q3 roadmap.
[00:01:30] Sarah: I suggest prioritizing the mobile app updates first.

shell
Copy
Edit

### 🎬 Subtitles (.srt)
1
00:01:23,000 --> 00:01:29,000
Let's discuss the Q3 roadmap.

shell
Copy
Edit

### ✨ Summary Output
Meeting Summary (Generated: 2023-11-15)
Key Decisions

✅ Mobile app updates will be Q3 priority

❌ Backend refactoring postponed to Q4

Action Items

 Sarah to draft mobile update plan by Friday

 Mike to review security requirements

yaml
Copy
Edit

---

## ⚡ Quick Start

### 🔧 Prerequisites

```bash
# Mac/Linux
brew install ffmpeg

# Windows (PowerShell)
winget install Gyan.FFmpeg
📦 Installation
bash
Copy
Edit
git clone https://github.com/your-username/zoom-transcriber.git
cd zoom-transcriber
pip install -r requirements.txt
▶️ Run It
bash
Copy
Edit
python zoom_transcribe.py --input "My Meeting.mp4" --model medium --summary --speakers 3
⚙️ Configuration
🧾 Command Arguments
Flag	Description	Default
--input	Path to input media file	Required
--model	Whisper model size	small
--language	Language code (optional)	Auto-detect
--speakers	Number of speakers	Auto-detect
--summary	Enable summary generation	False
--gui	Launch web interface	False

🗂️ Config File: config.ini
ini
Copy
Edit
[default]
model = medium
output_dir = ./transcripts
keep_temp_files = False
🚀 Performance Benchmarks
Model	🔄 Speed	📈 Accuracy	🧠 RAM Usage	🏆 Best For
Tiny	🚀 3x RT	68% WER	1GB	Quick drafts
Small	⚡ 2x RT	80% WER	2GB	Daily use
Medium	⏱️ 1x RT	85% WER	5GB	Important meetings
Large	🧠 0.5x RT	92% WER	10GB	Research-grade quality

<p align="center"> <img src="./assets/benchmark-graph.png" width="80%" /> </p>
🛣️ Roadmap
✅ Core transcription (v1.0)

✅ SRT subtitles export (v1.2)

🧪 Speaker diarization (v2.0)

🖥️ Web Interface (v2.1)

📡 Live Meeting Capture (v3.0)

❓ FAQ
❌ Terminal Icons Not Showing?
Use Nerd Fonts like FiraCode

Ensure terminal encoding is set to UTF-8

⚠️ FFmpeg Not Found?
bash
Copy
Edit
ffmpeg -version  # verify installation

# Add to PATH
export PATH="/path/to/ffmpeg:$PATH"
🐢 Slow Performance?
Use --model tiny for speed

Close background apps

Run from SSD

🤝 Contributing
We love community involvement!

See CONTRIBUTING.md

Follow CODE_OF_CONDUCT.md

📜 License
MIT License © 2023 [Your Name]

🌟 Support
If you found this useful, please ⭐ star the repo — it motivates us to improve!

yaml
Copy
Edit

---




