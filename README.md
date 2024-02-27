# 📝 🧮 💡 Text to numbers to insight
A practical and friendly primer on neural representations for NLP.

### 📦 🏃‍♂️ Install & Run

- Download and install [Anaconda](https://www.anaconda.com/products/distribution) for your OS.
- Make sure you are using python 3.10 environment (your mileage may vary with other versions).
- Start a jupyter lab environment and run the first cell in the notebook.

Alternatively, you can install the dependencies manually and run the notebook however you want 👇

From your python 3.10 env of choice:

```
pip install -r requirements.txt
```

Then run these in your env to get the language models:

```
python -m spacy download en_core_web_sm
python -m spacy download nb_core_news_sm
python -c "from sentence_transformers import SentenceTransformer; SentenceTransformer('distiluse-base-multilingual-cased-v2');"
```