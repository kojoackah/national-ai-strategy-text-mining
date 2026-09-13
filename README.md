# national-ai-strategy-text-mining
Cross-border natural language processing and unsupervised machine learning pipelines analyzing national AI strategies across African and European Union nations.

- **`nlp_european_policy_clustering.ipynb`**: Houses an unsupervised machine learning pipeline that ingests raw national AI policy texts from Austria, Belgium, Bulgaria, Denmark, Estonia, and the Czech Republic. Deploys NLTK tokenization and Scikit-Learn's KMeans clustering algorithms to group international strategies programmatically by semantic and thematic similarity, validating cluster stability via Adjusted Rand Scores.

- - **`nlp_berlin_smart_city_preprocessing.ipynb`**: Implements a complete text normalization and feature engineering pipeline over the "Smart City Strategy Berlin" public policy framework. Automates lowercasing, digit filtering, punctuation stripping, and NLTK lemmatization before constructing a term importance feature matrix via Scikit-Learn `TfidfVectorizer` mapped into structured Pandas data layers.

## Key Programmatic Competencies Demonstrated
- **Multi-National Corpus Ingestion:** Engineered robust batch file-processing loops capable of scaling text-mining operations across diverse country-specific text encodings.
- **Unsupervised Matrix Clustering:** Mapped abstract, qualitative text arrays into sparse TF-IDF coordinate blocks to evaluate latent structural overlaps between different nations' goals.
- **Reproducible NLP Design:** Leveraged standard data science libraries (`pandas`, `numpy`, `scikit-learn`, `nltk`) to verify data transformation consistency across international strategy papers.
