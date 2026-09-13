# national-ai-strategy-text-mining
Cross-border natural language processing and unsupervised machine learning pipelines analyzing national AI strategies across African and European Union nations.

- **`nlp_european_policy_clustering.ipynb`**: Houses an unsupervised machine learning pipeline that ingests raw national AI policy texts from Austria, Belgium, Bulgaria, Denmark, Estonia, and the Czech Republic. Deploys NLTK tokenization and Scikit-Learn's KMeans clustering algorithms to group international strategies programmatically by semantic and thematic similarity, validating cluster stability via Adjusted Rand Scores.

- **`nlp_berlin_smart_city_preprocessing.ipynb`**: Implements a complete text normalization and feature engineering pipeline over the "Smart City Strategy Berlin" public policy framework. Automates lowercasing, digit filtering, punctuation stripping, and NLTK lemmatization before constructing a term importance feature matrix via Scikit-Learn `TfidfVectorizer` mapped into structured Pandas data layers.

- **`nlp_strategy_ingestion_blueprint.ipynb`**: Houses the core template infrastructure and modular code blocks utilized across the research pipelines. Consolidates Python logic frameworks for sentence-level NADER polarity scoring, cleaning regex routines, TfidfVectorizer fit-transform operations, and token frequency calculations (`FreqDist`) exported to standalone CSV tables.

- **`nlp_berlin_vader_sentiment.ipynb`**: Deploys rule-based sentiment extraction loops over the 730 parsed sentences of the Berlin municipal framework. Employs the NLTK VADER lexicon engine to programmatically calculate polarity vector weights (negative, neutral, positive, and compound metrics) across administrative statements, merging arrays into structured data outputs via Pandas.
- **`nlp_policy_sentence_tokenizer.ipynb`**: Implements a modular sentence-chunking pipeline utilizing the NLTK Punkt tokenization engine. Programmatically parses unstructured policy texts into discrete, index-aligned string arrays, handling newline removals and converting raw strategy data tables into exportable CSV datasets via Pandas matrix constructions.

- **`nlp_batch_pdf_text_extraction.ipynb`**: Houses the batch data ingestion pipeline that standardizes, cleans, and converts multi-national policy documents. Automates string file-renaming loops and deploys the Apache Tika parser engine (`tika.parser`) to programmatically extract raw textual metadata across 26 European Union national AI strategies, resolving encoding anomalies into sanitized `utf-8` text matrices.





## Key Programmatic Competencies Demonstrated
- **Multi-National Corpus Ingestion:** Engineered robust batch file-processing loops capable of scaling text-mining operations across diverse country-specific text encodings.
- **Unsupervised Matrix Clustering:** Mapped abstract, qualitative text arrays into sparse TF-IDF coordinate blocks to evaluate latent structural overlaps between different nations' goals.
- **Reproducible NLP Design:** Leveraged standard data science libraries (`pandas`, `numpy`, `scikit-learn`, `nltk`) to verify data transformation consistency across international strategy papers.
