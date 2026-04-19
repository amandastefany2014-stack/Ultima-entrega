# Ultima-entrega
voice-assistant-whisper-chatgpt/ │ ├── main.py ├── requirements.txt ├── README.md └── audio_exemplo.wav (opcional)
# código principal do seu assistente de voz
# Whisper + modelo IA + gTTS
openai-whisper
transformers
torch
gtts

# 🎤 Voice AI Assistant

Projeto que converte áudio em texto, processa com IA e devolve resposta em voz.

---

## 🚀 Tecnologias usadas

- Whisper (Speech-to-Text)
- Transformers (IA local)
- gTTS (Text-to-Speech)
- Python

---

## ⚙️ Como funciona

1. Usuário envia áudio
2. Whisper transcreve
3. IA gera resposta
4. gTTS transforma em voz

---

## 🧠 Fluxo

Áudio → Texto → IA → Voz

---

## ▶️ Como executar

```bash
pip install -r requirements.txt
python main.py

---

# 🌐 6. COMO SUBIR NO GITHUB

No terminal:

```bash id="git1"
git init
git add .
git commit -m "projeto voice assistant"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPO.git
git push -u origin main
