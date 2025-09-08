# Fine-Tuning Whisper for Speech Recognition

## 📖 Project Description
This project focuses on **fine-tuning OpenAI’s Whisper model** on a specific dataset for speech recognition tasks.  
The goal is to improve transcription accuracy for a targeted dataset, such as **TIMIT Acoustic-Phonetic Continuous Speech Corpus**, by applying preprocessing, model training, and evaluation.  

---

## 🎯 Objective
- Train Whisper on a specific dataset and evaluate its performance.  
- Produce a fine-tuned model capable of accurately transcribing audio samples.  

---

## ⚙️ Steps

### 1. Data Collection
- Collect a diverse audio dataset with transcriptions.  

### 2. Preprocessing
- Convert all audio files to a consistent format **16kHz WAV**.  
- Apply noise reduction and normalization.  
- Extract features using **Log-Mel Spectrograms** for model input.  

### 3. Model Training
- Fine-tune **openai/whisper-small** on the preprocessed dataset.  
- Use a **GPU** for faster training.  

### 4. Inference
- Run the trained model on unseen audio samples.  
- Evaluate performance using **Word Error Rate (WER)**.  

---

## 📊 Expected Outcome
- A fine-tuned **Whisper model** capable of accurately transcribing audio from the chosen dataset.  
- Improved performance compared to the base model on the selected dataset.  

---

## 🛠️ Technologies Used
- **Python**  
- **PyTorch**  
- **OpenAI Whisper**  
- **Librosa** (for audio preprocessing)  
- **Scikit-learn** (for evaluation)
- **soundfile** (for read and write sound files)
