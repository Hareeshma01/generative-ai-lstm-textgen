# generative-ai-lstm-textgen


## 🌟 Overview
Character-level text generator using an LSTM model trained on Shakespeare's works. The model predicts the next character in a sequence, enabling generation of text similar in style to the training data.

## 📝 Dataset
- **Source:**  - Shakespeare’s Complete Works.
- **Used:** First 100,000 characters for demonstration.

## ⚙️ Files
- `text_generation_lstm.ipynb` : Colab notebook with preprocessing, model, training, and text generation.

## 🔬 Model Summary
- **Input:** Sequences of 100 characters
- **Architecture:** LSTM (128 units) + Dense output
- **Total Parameters:** ~73k
- **Loss reduction:** ~2.56 → ~2.42 over 10 epochs

## ✨ Sample Generated Text

Seed:
"ly april of her prime,
so thou through windows of thine age shalt see,
despite of wrinkles this thy "

Generated Text:
ho the sore,
and the tore the tore the tore the tore...

## 💡 Notes
- Model trained on reduced data for demonstration.  
- Future improvements: More data, deeper models, and longer training for better coherence.


