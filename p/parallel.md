---
title: "Parallel Stylometric Document Embeddings with Deep Learning Based Language Models in Literary Authorship Attribution"
permalink: /p/parallel/
---

<meta name="citation_title" content="Parallel Stylometric Document Embeddings with Deep Learning Based Language Models in Literary Authorship Attribution">
<meta name="citation_author" content="Mihailo Škorić">
<meta name="citation_author" content="Ranka Stanković">
<meta name="citation_author" content="Milica Ikonić Nešić">
<meta name="citation_author" content="Joanna Byszuk">
<meta name="citation_author" content="Maciej Eder">
<meta name="citation_publication_date" content="2022">
<meta name="citation_journal_name" content="Mathematics">
<meta name="citation_publisher_name" content="Multidisciplinary Digital Publishing Institute">
<meta name="citation_journal_issue" content="10.5">

## Parallel Stylometric Document Embeddings with Deep Learning Based Language Models in Literary Authorship Attribution

### Reference

Škorić, Mihailo, Ranka Stanković, Milica Ikonić Nešić, Joanna Byszuk, and Maciej Eder. "Parallel Stylometric Document Embeddings with Deep Learning Based Language Models in Literary Authorship Attribution", _Mathematics_, 10.5 (2022), 838. DOI: [10.3390/math10050838](https://doi.org/10.3390/math10050838)

### Abstract

This paper explores the effectiveness of parallel stylometric document embeddings in solving the authorship attribution task by testing a novel approach on literary texts in 7 different languages, totaling in 7051 unique 10,000-token chunks from 700 PoS and lemma annotated documents. We used these documents to produce four document embedding models using Stylo R package (word-based, lemma-based, PoS-trigrams-based, and PoS-mask-based) and one document embedding model using mBERT for each of the seven languages. We created further derivations of these embeddings in the form of average, product, minimum, maximum, and l2 norm of these document embedding matrices and tested them both including and excluding the mBERT-based document embeddings for each language. Finally, we trained several perceptrons on the portions of the dataset in order to procure adequate weights for a weighted combination approach. We tested standalone (two baselines) and composite embeddings for classification accuracy, precision, recall, weighted-average, and macro-averaged F1-score, compared them with one another and have found that for each language most of our composition methods outperform the baselines (with a couple of methods outperforming all baselines for all languages), with or without mBERT inputs, which are found to have no significant positive impact on the results of our methods.

### Keywords

Document embeddings, Authorship attribution, Language modelling, Corpus, Stylometry, Stylo R, POS, Tagging

### Direct Access

- [PDF](https://github.com/distantreading/compendium/blob/main/f/parallel.pdf)
- [Article](https://mdpi-res.com/d_attachment/mathematics/mathematics-10-00838/article_deploy/mathematics-10-00838.pdf?version=1646620629)

### BibTex

```

@article{skoric_parallel_2022,
	title = {Parallel {Stylometric} {Document} {Embeddings} with {Deep} {Learning} {Based} {Language} {Models} in {Literary} {Authorship} {Attribution}},
	volume = {10},
	copyright = {http://creativecommons.org/licenses/by/3.0/},
	issn = {2227-7390},
	url = {https://www.mdpi.com/2227-7390/10/5/838},
	doi = {10.3390/math10050838},
	abstract = {This paper explores the effectiveness of parallel stylometric document embeddings in solving the authorship attribution task by testing a novel approach on literary texts in 7 different languages, totaling in 7051 unique 10,000-token chunks from 700 PoS and lemma annotated documents. We used these documents to produce four document embedding models using Stylo R package (word-based, lemma-based, PoS-trigrams-based, and PoS-mask-based) and one document embedding model using mBERT for each of the seven languages. We created further derivations of these embeddings in the form of average, product, minimum, maximum, and l2 norm of these document embedding matrices and tested them both including and excluding the mBERT-based document embeddings for each language. Finally, we trained several perceptrons on the portions of the dataset in order to procure adequate weights for a weighted combination approach. We tested standalone (two baselines) and composite embeddings for classification accuracy, precision, recall, weighted-average, and macro-averaged F1-score, compared them with one another and have found that for each language most of our composition methods outperform the baselines (with a couple of methods outperforming all baselines for all languages), with or without mBERT inputs, which are found to have no significant positive impact on the results of our methods.},
	language = {en},
	number = {5},
	urldate = {2022-03-07},
	journal = {Mathematics},
	author = {Škorić, Mihailo and Stanković, Ranka and Ikonić Nešić, Milica and Byszuk, Joanna and Eder, Maciej},
	month = jan,
	year = {2022},
	note = {Number: 5
Publisher: Multidisciplinary Digital Publishing Institute},
	keywords = {type\_publication},
	pages = {838},
}

```

<span class='Z3988' title='url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_id=info%3Adoi%2F10.3390%2Fmath10050838&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal&amp;rft.genre=article&amp;rft.atitle=Parallel%20Stylometric%20Document%20Embeddings%20with%20Deep%20Learning%20Based%20Language%20Models%20in%20Literary%20Authorship%20Attribution&amp;rft.jtitle=Mathematics&amp;rft.volume=10&amp;rft.issue=5&amp;rft.aufirst=Mihailo&amp;rft.aulast=%C5%A0kori%C4%87&amp;rft.au=Mihailo%20%C5%A0kori%C4%87&amp;rft.au=Ranka%20Stankovi%C4%87&amp;rft.au=Milica%20Ikoni%C4%87%20Ne%C5%A1i%C4%87&amp;rft.au=Joanna%20Byszuk&amp;rft.au=Maciej%20Eder&amp;rft.date=2022-01&amp;rft.pages=838&amp;rft.issn=2227-7390&amp;rft.language=en'></span>
