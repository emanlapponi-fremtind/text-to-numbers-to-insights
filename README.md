# 📝 🧮 💡 Text to numbers to insight
A practical and friendly primer on neural NLP.

### 📦 Install

From your python 3.8 env of choice:

```
pip install -r requirements.txt
```

Then run these in your env to get the language models:

```
python -m spacy download en_core_web_sm
python -c "from sentence_transformers import SentenceTransformer; SentenceTransformer('distiluse-base-multilingual-cased-v2'); SentenceTransformer("msmarco-distilbert-base-v2")"
```

### 🏃🏻‍♀️ Run

Run `jupyter lab` in the terminal, then click on `notebook.ipynb`
