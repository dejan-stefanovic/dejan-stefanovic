# Hi, I'm Dejan 👋
**Machine Learning Engineer** | B.Sc. Actuarial Science, Simon Fraser University

## About Me:
I am a recent Actuarial Science graduate from Simon Fraser University with a strong interest in Machine Learning Engineering, AI systems, and applied data science. I enjoy building practical AI-driven tools that solve real problems, from automating business workflows to developing full-stack ML applications. My experience spans Python, PyTorch, XGBoost, SQL, AWS, and local LLM systems, with projects focused on predictive modeling, intelligent automation, voice AI, and computer vision.

## What I'm Building
 
### [Project LOGOS](https://github.com/dejan-stefanovic/project-logos) — Local AI Assistant
A fully local voice-enabled AI assistant with hybrid LLM routing, web intelligence, and persistent memory.
 
- **Hybrid orchestration**: Confidence-thresholded intent classifier (`CONFIDENCE_THRESHOLD = 0.7`) routes between a local Gemma 4 model (via Ollama) and web search, fast for known queries, grounded for uncertain ones
- **Voice I/O pipeline**: Whisper STT → LLM inference → edge-tts synthesis (`en-GB-RyanNeural`), fully offline
- **Web intelligence module**: Brave Search primary, DuckDuckGo fallback, with an Ollama-powered synthesis layer that resolves conflicts across sources
- **Stack**: Python, Ollama, Whisper, edge-tts, Tavily/Brave APIs

> Built because I wanted to understand how production AI assistants actually work, not just call an API.

## Projects
 
| Project | What it does | Stack | Result |
|---|---|---|---|
| **F1 Race Outcome Predictor** | Predicts race outcomes from telemetry + historical data | XGBoost, AWS, feature engineering | 90% accuracy — 14pp over naive baseline, 4.6pp over engineered logistic regression |
| **Diabetes Risk Classifier** | Binary classification on 300K+ patient records | Scikit-learn, Pandas | Corrected 12,000+ data inconsistencies; built full preprocessing pipeline |
| **Gesture Recognition System** | Real-time hand gesture classifier | PyTorch, MediaPipe | 93% accuracy — up from 73% after targeted training data diversification |

## 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![R](https://img.shields.io/badge/r-%23276DC3.svg?style=flat&logo=r&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=PyTorch&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white) ![AMD](https://img.shields.io/badge/AMD-%23000000.svg?style=flat&logo=amd&logoColor=white)

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/www.linkedin.com/in/dejan-stefanovic-231551261) 

## 📊 GitHub Stats:
![](https://github-readme-stats.shion.dev/api?username=dejan-stefanovic&theme=dark&hide_border=true&include_all_commits=false&count_private=false)<br/>
![](https://streak-stats.demolab.com/?user=dejan-stefanovic&theme=dark&hide_border=true)<br/>
![](https://github-readme-stats.shion.dev/api/top-langs/?username=dejan-stefanovic&theme=dark&hide_border=true&include_all_commits=false&count_private=false&layout=compact)
