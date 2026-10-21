# Latent_Dirichlet_Allocation
LDA Topic Modeling Project Report
**Project Overview**
This project applies Latent Dirichlet Allocation (LDA) to discover underlying themes within a collection of documents. The pipeline covers text preprocessing, bag-of-words vectorization, model training, topic interpretation, and interactive dashboard visualization.


**1. Text Preprocessing & Vectorization**
Tokenization: Converting documents into individual lowercase terms.
Stop Words Removal: Filtering out standard English stop words using CountVectorizer(stop_words='english') to retain content-rich terms.
Vectorization: Representing documents in a Document-Term Matrix using Bag-of-Words word frequency counts.


**2. LDA Model Configuration**
Number of Topics ( K ): 3
Algorithm: Latent Dirichlet Allocation (scikit-learn)
Random State: 42 (for reproducibility)


**3. Discovered Topics & Interpretation**
Based on the top words associated with each latent topic, the themes are categorized as follows:

Topic 1 (Culinary/Food): Dominated by terms like meal, prepared, organic, pasta, and chef.
Topic 2 (Space Exploration): Dominated by terms like space, new, telescope, study, and black.
Topic 3 (Software Development): Dominated by terms like write, web, python, software, and code.


**4. Visualizations**
Interactive Visualizations: Implemented using pyLDAvis to show the multi-dimensional mapping of topics and word saliency/relevance dynamically.
