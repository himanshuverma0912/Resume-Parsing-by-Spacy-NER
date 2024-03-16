# NLP Resume Parser with Python and SpaCy
This project aims to develop an intelligent resume parser that can efficiently extract structured data from unstructured resume documents (like .pdf or .docx). The parser will leverage the powerful natural language processing (NLP) capabilities of the SpaCy library in Python.

### Installation
To install the dependencies run:
```buildoutcfg
pip install -r requirements.txt
```

### Dataset
The dataset is containing resume contents in JSON format which has been retrieved from DataTurks.

### Train the model
To train the model run:
```buildoutcfg
python Engine.py
```

### Predictions
To make prediction on a new resume content

### NER in SpaCy:
<ol>
<li>spaCy provides highly efficient and accurate statistical NER models.</li>
<li>These models are pre-trained on large datasets, giving them a strong baseline for recognizing common entities.</li>
</ol>

### How it works (Simplified):
<ol>
<li><strong>Text Tokenization:</strong> SpaCy breaks a text into individual words (tokens).</li>
<li><strong>Statistical Model:</strong> The NER model analyzes tokens and their context, assigning probabilities to possible entity labels.</li>
<li><strong>Entity Prediction:</strong> The model selects the label with the highest probability for each token or group of tokens.</li>
</ol>

### Accessing NER results:
<ol>
<li>After processing a document (Doc object) in spaCy, the identified entities are available in the doc.ents attribute.</li>
<li>You can iterate through the entities to obtain their text, label, and start/end positions within the document.</li>
</ol>

