<h1>Philosophy Text Analysis Project</h1>

<h2>Overview</h2>
This repository contains code, visualizations, and analysis from applying natural language processing tools to 500+ philosophy books. Our tools analyze citation patterns, classify philosophical topics, and explore relationships between philosophical works through various computational methods.

<h2>Current Files</h2>

**Interactive Tools:**
* artifact.ipynb: An interactive tool that visualizes the citation network of all philosophers within our database. Our most recent version is accessible to anyone through a public Google Colab file: https://drive.google.com/file/d/10WSpHmoNz_bt8gjRz9YhbcNOIerAQlzP/view?usp=sharing
* helpers.py: Supporting functions for the interactive visualization

**Data Collection & Processing**

* scraper.py: Downloads our data using Gutenberg API
* reference_fetcher.py: Generates Dataframe of the citation network
* topic_classifier.py: classifies references into predefined philosophical topics

**Development**
* draftwork/: Development scripts & prototypes
* draftimages/: Preliminary visualizations

<h2>Planned Additions</h2>

**Analysis Notebooks**
* network_analysis: Key visualizations & analysis of our citation network
* embedding_analysis.ipynb: Vector space analysis of philosophical texts
* cleaner.ipynb: Efforts to eliminate false references to reduce noise

**Extended Research**
* llm_philosophy_network/: EDA of outputs obtained through iteratively prompting Large Language Models to reference philosophers. Preliminary research can be found here:
* subset_analysis/: Analysis of currated philosophy texts

