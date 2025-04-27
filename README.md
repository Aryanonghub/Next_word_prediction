
# ✍️ Next Word Prediction with LSTM

A **Streamlit web app** that predicts the next word in a given sequence using a **trained LSTM model** on a text corpus.  
Helps demonstrate how Recurrent Neural Networks can learn language patterns and complete sentences.

---

## 📚 Project Overview

This project allows users to input the beginning of a sentence, and the app predicts the **next most likely word** based on a trained **LSTM model**.  
It uses **Keras Tokenizer** for text processing and **Streamlit** for building a clean, interactive interface.

---

## 🚀 Features

- **Next Word Prediction:** Predicts the most probable next word given a sequence.
- **Simple UI:** Built with Streamlit for easy and intuitive user interaction.
- **Language Modeling:** Demonstrates basic NLP using deep learning techniques.
- **Custom Trained Model:** Model trained on a corpus like Shakespeare’s works or any large text dataset.

---

## 🛠️ Technologies Used

- **Python**
- **TensorFlow / Keras**
- **Streamlit**
- **Pickle** (for loading tokenizer)

---

## 🧠 How It Works

- Loads a pre-trained **LSTM model** (`next_word_lstm.h5`) and corresponding **tokenizer**.
- The user enters a **sequence of words**.
- The sequence is tokenized and padded to match the model's expected input size.
- The model predicts the next word’s token, which is then mapped back to the actual word.
- The result is displayed instantly on the web app.

---

## ⚙️ How to Run Locally

1. **Clone this repository:**
   ```bash
   git clone https://github.com/your-username/next-word-prediction-lstm.git
   cd next-word-prediction-lstm
   ```

2. **Install the required packages:**
   ```bash
   pip install tensorflow streamlit numpy
   ```

3. **Ensure you have the necessary files:**
   - `next_word_lstm.h5` (the trained model)
   - `tokenizer.pickle` (the tokenizer used during model training)

4. **Run the Streamlit app:**
   ```bash
   streamlit run app.py
   ```

5. **Open the app** in your browser at:
   ```
   http://localhost:8501
   ```

---

## 📂 Project Structure

```bash
├── app.py                  # Main Streamlit application
├── next_word_lstm.h5        # Pre-trained LSTM model
├── tokenizer.pickle         # Tokenizer used for text encoding
└── README.md                # Project documentation
```

---

## 📢 Future Improvements

- Predict multiple next words (not just one word).
- Fine-tune on a larger modern dataset (e.g., Wikipedia, Reddit).
- Improve UI with multiple prediction options.
- Deploy online with Streamlit Cloud or Hugging Face Spaces.

---

## 🤝 Contributing

Pull requests are welcome!  
If you find any bugs or have suggestions for improvement, feel free to open an issue or submit a PR.

---

## 📜 License

This project is open source under the [MIT License](LICENSE).

---

## 🌟 Show Your Support

If you like this project, don't forget to ⭐ star the repository!

---

Would you also like me to create a ready-to-use **GitHub repo folder structure** + **requirements.txt** for you for both projects together? 🚀  
(So you can instantly upload and show it off!)  
Just say "**yes GitHub setup**"! 🎯
