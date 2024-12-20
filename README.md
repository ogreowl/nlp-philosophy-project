<h1>Philosophy Text Analysis Project</h1>

<h2>Overview</h2>
This project applies natural language processing & network analysis to study citation patterns across 500+ philosophy texts. Through computational techniques applied to our texts, we aim to generate & visualize citation networks, analyze the evolution of philosophical ideas, and innovate on methodological practices within the digital humanities. 

<h2>Current Files</h2>

**Artifact:**
* artifact.ipynb: An interactive tool that visualizes the citation network of all philosophers within our database. Our most recent version is publicly accessible through Google Colab: https://drive.google.com/file/d/10WSpHmoNz_bt8gjRz9YhbcNOIerAQlzP/view?usp=sharing
* helpers.py: Supporting functions for the interactive visualization

**Data Collection & Processing**

* scraper.py: Downloads our data using Gutenberg API
* reference_fetcher.py: Generates Dataframe of the citation network
* classifier.ipynb: classifies references into predefined philosophical topics
* test_classifier.ipynb: runs our reference collection on a smaller scale
* data_cleaning.ipynb: preliminary cleaning of our data to reduce noise

**Development**
* draftscripts/: Development scripts & prototypes
* draftimages/: Preliminary visualizations

<h2>Planned Additions</h2>

**Analysis Notebooks**
* network_analysis: Key visualizations & analysis of our citation network
* embedding_analysis.ipynb: Vector space analysis of philosophical texts
* cleaner.ipynb: Efforts to eliminate false references to reduce noise

**Extended Research**
* llm_philosophy_network/: EDA of outputs obtained through iteratively prompting Large Language Models to reference philosophers. Our preliminary research can be found here:
* subset_analysis/: Analysis of curated philosophy texts

<h2>Recourses</h2>

**Tools**
* BERT: https://arxiv.org/abs/1810.04805
* BART: https://arxiv.org/abs/1910.13461
* NetworkX: https://networkx.org/

**Related Research**

The following papers have informed the techniques & methodology of this project:

* Fractality of sentiment arcs for literary quality assessment
> https://aclanthology.org/2022.nlp4dh-1.5

* Text Analysis Using Deep Neural Networks in Digital Humanities and Information Science
> https://arxiv.org/abs/2307.16217

* Domain-specific Evaluation of Word Embeddings for Philosophical Text using Direct Intrinsic Evaluation
> https://aclanthology.org/2022.nlp4dh-1.14/

* Epic social networks and Eve's centrality in Milton’s Paradise Lost
> https://academic.oup.com/dsh/article-abstract/35/1/146/5365481?redirectedFrom=fulltext

* Social network analysis of the Babylonian Talmud
> https://academic.oup.com/dsh/article-abstract/39/3/968/7716505?redirectedFrom=fulltext

* Topic modeling literary interviews from The Paris Review
> https://academic.oup.com/dsh/article/39/1/142/7515230

* Visualization of Categorization: How to see the wood and the trees
> https://www.digitalhumanities.org/dhq/vol/17/3/000703/000703.html

**Data**

All data was downloaded from Project Gutenberg, a free provider of digital books within the public domain: https://www.gutenberg.org/

<h2>About the Authors</h2>
This research is primarily developed by Bobby Becker under the supervision of Dr. Aron Culotta at Tulane University. You can contact us at bobbybeckerdev@gmail.com.
