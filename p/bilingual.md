---
title: "Stylometry in a Bilingual Setup"
permalink: /p/bilingual/
---

<meta name="citation_title" content="Stylometry in a Bilingual Setup">
<meta name="citation_author" content="Silvie Cinková">
<meta name="citation_author" content="Jan Rybicki">
<meta name="citation_publication_date" content="2020">
<meta name="citation_conference_name" content="12th Language Resources and Evaluation Conference">
<meta name="citation_proceedings_title" content="Proceedings of The 12th Language Resources and Evaluation Conference, LREC 2020">
<meta name="citation_publication_place" content="Marseille, France">
<meta name="citation_publisher_name" content="European Language Resources Association">

## Stylometry in a Bilingual Setup

### Reference

Cinková, Silvie, and Jan Rybicki. "Stylometry in a Bilingual Setup", in _Proceedings of The 12th Language Resources and Evaluation Conference_, Marseille, France, May 11-16, 2020, ed. by Nicoletta Calzolari, Frédéric Béchet, Philippe Blache, Khalid Choukri, Christopher Cieri, Thierry Declerck, and others (presented at the 12th Language Resources and Evaluation Conference, LREC (2020), European Language Resources Association), 977–984. URL: https://www.aclweb.org/anthology/2020.lrec-1.123/

### Abstract

The method of stylometry by most frequent words does not allow direct comparison of original texts and their translations, i.e. across languages. For instance, in a bilingual Czech-German text collection containing parallel texts (originals and translations in both directions, along with Czech and German translations from other languages), authors would not cluster across languages, since frequency word lists for any Czech texts are obviously going to be more similar to each other than to a German text, and the other way round. We have tried to come up with an interlingua that would remove the language-specific features and possibly keep the linguistically independent features of individual author signal, if they exist. We have tagged, lemmatized, and parsed each language counterpart with the corresponding language model in UDPipe, which provides a linguistic markup that is cross-lingual to a significant extent. We stripped the output of language-dependent items, but that alone did not help much. As a next step, we transformed the lemmas of both language counterparts into shared pseudolemmas based on a very crude Czech-German glossary, with a 95.6% success. We show that, for stylometric methods based on the most frequent words, we can do without translations.

### Keywords

Stylometry, Multilinguality, Authorship attribution, Translation, Czech-German, POS, Lemmatization, ELTeC

### Direct Access

- [PDF](https://github.com/distantreading/compendium/blob/main/f/bilingual.pdf)
- [Paper](https://aclanthology.org/2020.lrec-1.123.pdf)

### BibTex

```
@inproceedings{cinkova_stylometry_2020,
	address = {Marseille},
	title = {Stylometry in a {Bilingual} {Setup}},
	url = {https://www.aclweb.org/anthology/2020.lrec-1.123/},
	booktitle = {Proceedings of {The} 12th {Language} {Resources} and {Evaluation} {Conference}, {LREC} 2020, {Marseille}, {France}, {May} 11-16, 2020},
	publisher = {European Language Resources Association},
	author = {Cinková, Silvie and Rybicki, Jan},
	editor = {Calzolari, Nicoletta and Béchet, Frédéric and Blache, Philippe and Choukri, Khalid and Cieri, Christopher and Declerck, Thierry and Goggi, Sara and Isahara, Hitoshi and Maegaard, Bente and Mariani, Joseph and Mazo, Hélène and Moreno, Asunción and Odijk, Jan and Piperidis, Stelios},
	year = {2020},
	keywords = {type\_publication},
	pages = {977--984},
}

```

<span class='Z3988' title='url_ver=Z39.88-2004&amp;ctx_ver=Z39.88-2004&amp;rfr_id=info%3Asid%2Fzotero.org%3A2&amp;rft_val_fmt=info%3Aofi%2Ffmt%3Akev%3Amtx%3Abook&amp;rft.genre=proceeding&amp;rft.atitle=Stylometry%20in%20a%20Bilingual%20Setup&amp;rft.btitle=Proceedings%20of%20The%2012th%20Language%20Resources%20and%20Evaluation%20Conference%2C%20LREC%202020%2C%20Marseille%2C%20France%2C%20May%2011-16%2C%202020&amp;rft.place=Marseille&amp;rft.publisher=European%20Language%20Resources%20Association&amp;rft.aufirst=Silvie&amp;rft.aulast=Cinkov%C3%A1&amp;rft.au=Silvie%20Cinkov%C3%A1&amp;rft.au=Jan%20Rybicki&amp;rft.au=Nicoletta%20Calzolari&amp;rft.au=Fr%C3%A9d%C3%A9ric%20B%C3%A9chet&amp;rft.au=Philippe%20Blache&amp;rft.au=Khalid%20Choukri&amp;rft.au=Christopher%20Cieri&amp;rft.au=Thierry%20Declerck&amp;rft.au=Sara%20Goggi&amp;rft.au=Hitoshi%20Isahara&amp;rft.au=Bente%20Maegaard&amp;rft.au=Joseph%20Mariani&amp;rft.au=H%C3%A9l%C3%A8ne%20Mazo&amp;rft.au=Asunci%C3%B3n%20Moreno&amp;rft.au=Jan%20Odijk&amp;rft.au=Stelios%20Piperidis&amp;rft.date=2020&amp;rft.pages=977%E2%80%93984&amp;rft.spage=977&amp;rft.epage=984'></span>
