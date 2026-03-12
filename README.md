# ML-regional-variation
Created as part of MACSS 30100 coursework (Machine Learning for Computational Social Sciences Winter 2026)

# Description

RQ: How do patterns of language use among African American English (AAE) speakers reflect shared regional speech communities and which linguistic features are most indicative of regional differences?

To examine whether shared regional speech communities are reflected in patterns of language use, data is analyzed using both unsupervised and supervised learning methods. Using the transcript text, linguistic features are extracted and represented using n-grams and TF-IDF methods. Unsupervised learning analysis involves exploring whether regional structure emerges organically from text data without imposing predefined regional categories. Dimensionality reduction techniques are used to find patterns of linguistic variation. Clustering methods can then be used to examine whether language naturally groups into regional clusters. Linguistic entropy is also calculated within each regional community to measure internal diversity. Supervised learning involves classification methods using region as the target feature to assess whether regional speech communities can be predicted from linguistic patterns. This would involve a multi-class methodology involving 8 categories (8 labeled regions). Classification performance is evaluated using cross-validation and then interpreted alongside the unsupervised findings to identify where the model fails. 

# Structure

- final_project.ipynb - final project code
- CORAALUserGuide_current.pdf - User guide for interpreting variables and other relevant data
  - from CORAAL website: https://oraal.github.io/coraal
- CORAAL_text_ml_dataset.csv - collected data from CORAAL corpus and metadata
  - assembled using R code sourced from CORAAL website
- AAE_Regional_Variation_Presentation.pptx - final presentation submission with video recording

# Additional Details

Research Domain: Computational Lingusitics, Sociolinguistics, and Anthropology

Data Source: I use the Corpus of Regional African American Language (CORAAL), a publicly available corpus consisting of sociolinguistic interviews with African American speakers from multiple regions across the US. Interviews were conducted over a wide span of time, from late 1960s to 2010s, with speakers born between 1888 and 2005. The corpus includes audio recordings and transcripts of naturalistic, conversational speech along with speaker-level metadata such as geographic location, age, and gender. Topics of discussion range from daily life, personal experiences, to family history. 

Libraries: pandas, numPy, scikit-learn, nltk, matplotlib, seaborn, graphviz, os, re
