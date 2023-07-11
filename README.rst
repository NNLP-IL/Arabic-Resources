Arabic NLP Resources
####################

**An online interface of this resource index is also available** `HERE <https://resources.nnlp-il.mafat.ai/>`_.

This repository collects resources for NLP in MSA (Modern Standard Arabic), Levantine and Egyptian Arabic, as part of the `National NLP Plan <https://www.nationalplanil.ai/>`_. Resources are divided to folders by type. If you have a resource you can contribute, to be released under some open license, please submit a pull request, or contact us at `contact@nlph.org.il <mailto:contact@nlph.org.il>`_. 

When contributing to the list, please add a link to the license for all non-paper resources, e.g. {`AGPL-3.0`_}, {?} for an unkonwn licesnse or {X} for unreleased/closed/copyrighted resources. For code resource, please also add the main language in which the tool is written, e.g. [Python] or [?] for an unknown programming language. Please add hosting mirrors with pointy brackets, e.g. `<Zenodo mirror> <https://zenodo.org/record/2707356>`_.




.. contents::

.. section-numbering::


**Corpora**
========== 

Unannotated Corpora
------------------------------

General Corpora
^^^^^^^^^^^^^^
* `Arabic Stories <https://github.com/motazsaad/Arabic-Stories-Corpus>`_ {`Apache License 2.0`_} - 146 Arabic children stories (MSA).

* `OSAC <https://sourceforge.net/projects/ar-text-mining/files/Arabic-Corpora/>`_ {?} - 22,000 text documents, each belonging to 1 of 10 categories: Economics, History, Entertainments, etc (MSA).

* `Shami <https://github.com/GU-CLASP/shami-corpus>`_ {`Apache License 2.0`_} - A Corpus of Levantine Arabic Dialects. 117,805 natural sentences from conversations in various Levantine dialects: Jordania, Palestinian, Lebanese, Syrian.

* `Abuelkhair Corpus <https://www.abuelkhair.net/cgi-sys/suspendedpage.cgi>`_ {?} - More than 5 million newspaper articles in MSA.



Specialized Corpora
^^^^^^^^^^^^^^^^^

* `ArCOV-19 <https://gitlab.com/bigirqu/ArCOV-19>`_ {?} - The First Arabic COVID-19 Twitter Datast with Propagation Networks. About 3.2M tweets in mixed dialect Arabic associated with COVID-19, an ongoing collection starting at January 2020.

* `Habibi <http://ucrel-web.lancaster.ac.uk/habibi/>`_ {?} - a multi Dialect multi National Arabic Song Lyrics Corpus. More than 30,000 Arabic song lyrics in 6 Arabic dialects (Egyptian, Levantine, etc.) for singers from 18 different Arabic countries, segmented into sentences and words and labeled with song information.



Crawls and Dumps
^^^^^^^^^^^^^^^^^

* `ArabicWeb16 <https://sites.google.com/view/arabicweb16/?pli=1>`_ {?} - A New Crawl for Today’s Arabic Web. 150M Arabic Web pages with high coverage of dialectal Arabic, Egyptian, Gulf, Levantine (~7M) and Maghrebi, as well as MSA, from a variety of sources - Wikipedia, Alexa, ArClueWeb09, and Twitter, etc.

* `Arabic Wiki Data Dumps <https://dumps.wikimedia.org/arwiki/>`_ {?} - Wikipedia, the free encyclopedia, publishes dumps of its content as XML files on a monthly basis.



Multilingual Corpora
----------------------------

* `OSCAR <https://oscar-corpus.com/>`_ {`CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>`_} - OSCAR or Open Super-large Crawled Aggregated coRpus is a huge multilingual corpus obtained by language classification and filtering of the Common Crawl corpus using the Ungoliant architecture.

* `CC100 <https://data.statmt.org/cc-100/?fbclid=IwAR2czQ8iHkINcK3oAoYTtIRcsj0TaiKOedor6S3Xzb-9-djTnHrK5D69lD0>`_ {`MIT`_} - This corpus is an attempt to recreate the dataset used for training XLM-R. This corpus comprises monolingual data for 100+ languages, including Hebrew. This was constructed using the urls and paragraph indices provided by the CC-Net repository by processing January-December 2018 Commoncrawl snapshots.

* `WikiQAar <https://github.com/qcri/WikiQAar>`_ {?} - a bilingual English-Arabic Question Answering corpus built on top of WIKIQA. See also: https://huggingface.co/datasets/wiki_qa_ar



Annotated Datasets by Task
----------------------------------------

Content Moderation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
* `AraCOVID19-MFH <https://github.com/MohamedHadjAmeur/AraCOVID19-MFH>`_ {`CC BY-NC-SA 4.0`_} - Arabic COVID-19 Multi-label Fake News & Hate Speech Detection Dataset. 10,828 mixed dialect Arabic tweets annotated with 10 different labels concerning fake news and hate speech.

* `L-HSAB <https://github.com/Hala-Mulki/L-HSAB-First-Arabic-Levantine-HateSpeech-Dataset>`_ {?} - A Levantine Twitter Dataset for Hate Speech and Abusive Language. 5,846 Syrian/Lebanese political tweets labeled as normal, abusive or hate.

* `Let-Mi <https://github.com/bilalghanem/let-mi>`_ {?} - An Arabic Levantine Twitter Dataset for Misogynistic Language. 6,603 tweets in Levantine Arabic annotated as either non-misogynistic or one of seven misogynistic language categories.

* `MPOLD <https://github.com/shammur/Arabic-Offensive-Multi-Platform-SocialMedia-Comment-Dataset>`_ {`Apache License 2.0
`_} - Arabic Offensive Comments dataset from Multiple Social Media Platforms. Annotated social media comment dataset with (not) offensive language tags for Arabic social media comments collected from three different online platforms: Twitter, Facebook and YouTube.

* `A Corpus of Offensive Language in Arabic <https://onedrive.live.com/?authkey=%21ACDXj%5FZNcZPqzy0&id=6EF6951FBF8217F9%21105&cid=6EF6951FBF8217F9>`_ {?} - 16,000 comments on YouTube videos from different nationalities annotated for offensive language.

* `Religious Hate Speech Detection for Arabic Tweets <https://github.com/nuhaalbadi/Arabic_hatespeech>`_ {?} - Tweets in MSA and Dialectal Arabic annotated for hate speech, training dataset contains 5,569 examples, while the testing dataset contains 567 examples.

* `COVID-FAKES <https://github.com/mohaddad/COVID-FAKES>`_ {?} - Bilingual (Arabic/English) COVID-19 Twitter dataset for misleading information detection. Automatically annotated Arabic/English COVID-19 Twitter dataset, using the shared information on the official websites Twitter accounts of the WHO, UNICEF, and UN as a source of reliable information, tweets annotated using 13 different machine learning algorithms and employing 7 different feature extraction technique.

* `Adult Content Detection on Arabic Twitter <https://arbml.github.io/masader/card?id=218>`_ {?} - 6k manually annotated Twitter accounts who post adult content and 44k ordinary Twitter accounts in addition to a tweet from each account, in mixed dialectal Arabic.

* `Fine-Grained Hate Speech Detection on Arabic Twitter <https://codalab.lisn.upsaclay.fr/competitions/2324>`_ {`CC BY 4.0`_} - 12,700 tweets in mixed dialect Arabic, no bias towards specific topics, genres, or dialects, each judged by 3 annotators for offensiveness classified into one of the hate speech types: Race, Religion, Ideology, Disability, Social Class, and Gender, and also judged whether a tweet has vulgar language or violence.

* `ArCOV19-Rumors <https://gitlab.com/bigirqu/ArCOV-19/-/tree/master/ArCOV19-Rumors>`_ {?} - An Arabic COVID-19 Twitter dataset for misinformation detection. 138 verified claims, mostly from popular fact-checking websites, and identified 9.4K relevant tweets to those claims, then manually-annotated the tweets by veracity to support research on misinformation detection.

* `AraFacts Dataset <https://gitlab.com/bigirqu/AraFacts/>`_ {`CC BY-NC 4.0`_} - an Arabic dataset of naturally-occurring professionally-verified claims. A dataset of 6,222 claims collected from 5 Arabic fact-checking websites: Misbar, Verify-sy, Fatabyyano, FactuelAFP and Maharat-news, that have been standardized and made available for research purposes.


Dependency Treebanks
^^^^^^^^^^^^^^^^^

* `Prague Arabic Dependency Treebank 1.0 <https://ufal.mff.cuni.cz/padt/PADT_1.0/docs/index.html>`_ {`Custom Terms of Use`_} - Language resource for Arabic natural language processing (NLP), a collection of parsed sentences annotated with syntactic structures.

* `UD_Arabic-PADT <https://github.com/UniversalDependencies/UD_Arabic-PADT>`_ {`CC BY-NC-SA 3.0`_} - The Arabic-PADT UD treebank is based on the Prague Arabic Dependency Treebank (PADT), created at the Charles University in Prague. The treebank consists of 7,664 sentences (282,384 tokens) and its domain is mainly newswire.


Dialect Identification
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `PADIC <https://sourceforge.net/projects/padic/>`_ {`GPLv3`_} - A multilingual Parallel Arabic DIalectal Corpus. A parallel corpus of 6,400 sentences in multiple Arabic dialects: Algerian, Maghreb, Syrian, Palestinian and MSA, for dialect detection and machine translation.

* `DART <https://www.dropbox.com/s/jslg6fzxeu47flu/DART.zip?dl=0>`_ {?} - A Large Dataset of Dialectal Arabic Tweets. About 25K tweets that are annotated via crowdsourcing for 5 Arabic dialects: Egyptian, Maghrebi, Levantine, Gulf, and Iraqi.

* `The MADAR Arabic Dialect Corpus <https://camel.abudhabi.nyu.edu/madar-parallel-corpus/>`_ {`Custom Terms of Use`_} - A collection of ~12,000 parallel sentences covering the dialects of 25 cities from the Arab World, in addition to English, French, and MSA.

* `AOC <https://github.com/sjeblee/AOC>`_ {?} - Arabic Commentary Dataset. 108K sentences in mixed-dialect informal Arabic labeled for dialectal content.

* `MSDA <https://msda.um6p.ma/msda_datasets>`_ {?} - An open access NLP dataset for Arabic dialects. +50K tweets in five (5) national dialects, labeled for several applications: dialect detection, topic detection and sentiment analysis.

* `Dialectal Arabic Code-Switching Dataset <https://github.com/qcri/Arabic_speech_code_switching>`_ {`MIT`_} - Transcribed audio in Egyptian dialect annotated at word-level for Code Switching (CS).

* `BAEC <https://github.com/TaghreedT/BAEC>`_ {?} - The Bangor Arabic–English Code-switching (BAEC) corpus. 45,251 words manually annotated for code-switching between Saudi, Egyptian and MSA Arabic and English.


Diacritization/Vocalization
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
* `Tashkeela <https://www.kaggle.com/datasets/linuxscout/tashkeela>`_ {`GPLv2`_} - Arabic diacritization corpus. Data is a collection of Arabic vocalized texts, which covers modern and classical Arabic language. The Data contains over 75 million of fully vocalized words obtained from 97 books, structured in text files. The corpus is collected mostly from Islamic classical books [14], and using semi-automatic web crawling process. The Modern Standard Arabic texts crawled from the Internet represent 1.15% of the corpus, about 867,913 words, while the most part is collected from Shamela Library, which represent 98.85%, with 74,762,008 words contained in 97 books.


Morphological Analysis
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `Annotated Shami Corpus <https://github.com/christios/annotated-shami-corpus>`_ {?} - Lebanese Arabic corpus annotated for numerous morphological features and for orthography standardization.

Named Entity Recognition (NER)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `ANERcorp <https://camel.abudhabi.nyu.edu/anercorp/>`_ {`CC BY-SA 4.0`_} - 300 documents annotated for entity recognition.

* `KALIMAT <https://sourceforge.net/projects/kalimat/>`_ {?} - 20,200 from the Omani newspaper Al Watan with summaries, named entities, art-of-speech tagging, and morphological analysis.

Part-of-speech (POS) Tagging
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `KALIMAT <https://sourceforge.net/projects/kalimat/>`_ {?} - 20,200 from the Omani newspaper Al Watan with summaries, named entities, art-of-speech tagging, and morphological analysis.

* `Dialectal Arabic Datasets <https://github.com/qcri/dialectal_arabic_resources>`_ {`Apache License 2.0`_} - 1,400 manually segmented and POS tagged tweets in four dialects, Egyptian, Levantine, Gulf, and Maghrebi.


Question Answering (QA)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `WikiQAar <https://github.com/qcri/WikiQAar>`_ {?} - a bilingual English-Arabic Question Answering corpus built on top of WIKIQA. See also: https://huggingface.co/datasets/wiki_qa_ar

* `ARCD <https://huggingface.co/datasets/arcd>`_ {`MIT`_} - Wikipedia open-domain Question Answering. 1,395 questions posed by crowdworkers on Wikipedia articles, and a machine translation of SQuAD.

* `DAWQAS <https://github.com/masun/DAWQAS>`_ {`MIT`_} - A Dataset for Arabic Why Question Answering System. 3,205 why question-answer pairs scraped from public Arabic websites.

* `TyDiQA <https://github.com/google-research-datasets/tydiqa>`_ {`Apache License 2.0`_} - A Dataset for Arabic Why Question Answering System. 3,205 why question-answer pairs scraped from public Arabic websites. Arabic dataset is 15,645 question-answer pairs.

* `AQAD <https://github.com/adelmeleka/AQAD>`_ {?} - 17,000+ Arabic Questions & Answers dataset. 17,000+ questions, collected via fully automated data collector on a set of Arabic Wikipedia articles for extractive question answering task


Question Classification
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `Journalist Questions on Twitter <https://sites.google.com/view/bigir/datasets#h.uy2uanu7u6b8>`_ {?} - 10,000 mixed dialect Arabic tweets manually annotated for question type.




Sentiment Analysis
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `Arabic 100k Reviews <https://www.kaggle.com/datasets/abedkhooli/arabic-100k-reviews>`_ {?} - Reviews with three classes from different services. 100k good, bad and medium reviews in Arabic from different services.
`HARD: Hotel Arabic-Reviews Dataset <https://github.com/elnagara/HARD-Arabic-Dataset>`
`BRAD: Books Reviews in Arabic Dataset <https://github.com/elnagara/BRAD-Arabic-Dataset>`
`Large Arabic Sentiment Analysis Resouces <https://github.com/hadyelsahar/large-arabic-sentiment-analysis-resouces/tree/master/datasets>` - 3K Automatically annotated Reviews in Domains of Movies, Hotels, Restaurants and Products

* `AGJT <https://github.com/komari6/Arabic-twitter-corpus-AJGT>`_ {?} - Arabic Twitter Corpus. 1,800 tweets annotated as positive and negative. Modern Standard Arabic (MSA) or Jordanian dialect.

* `ArSAS <https://homepages.inf.ed.ac.uk/wmagdy/resources.htm>`_ {?} - An Arabic Speech-Act and Sentiment Corpus of Tweets. 21,000 tweets manually annotated for six different classes of speech-act labels.

* `ASTD <https://github.com/mahmoudnabil/ASTD>`_ {`GPLv2`_} - Arabic Sentiment Tweets Dataset. 10,000 tweets classified as objective, subjective positive, subjective negative, and subjective mixed.

* `AraSenCorpus <https://github.com/yemen2016/AraSenCorpus>`_ {`MIT`_} - 4.5 million tweets annotated positive, negative and neutral.

* `LABR <https://github.com/mohamedadaly/LABR>`_ {`GPLv2`_} - A Large-SCale Arabic Book Reviews Dataset. 63,000 book reviews in mixed dialect Arabic for sentiment analysis.

* `Arabic Sentiment Analysis and Cross-lingual Sentiment Resources<https://saifmohammad.com/WebPages/ArabicSA.html>`_ {`Custom Terms of Use`_} - `BBN Blog Posts Sentiment Corpus<https://www.google.com/url?q=https://saifmohammad.com/WebDocs/Arabic-Sentiment-Corpora/bbn_shared-2.xls&sa=D&source=docs&ust=1687688165193615&usg=AOvVaw1ID4x19RecFLrun8-7cBiN>`_ - A random subset of 1200 Levantine dialectal sentences. `Syria Tweets Sentiment Corpus<https://saifmohammad.com/WebDocs/Arabic-Sentiment-Corpora/syr_twts%20_shared.xlsx>`_ - A dataset of 2000 tweets originating from Syria.

* `TEAD <https://github.com/HSMAabdellaoui/TEAD>`_ {`GPLv3`_} - 6 million mixed dialect Arabic tweets with a vocabulary of 602,721 distinct entities, annotated by emojis and sentiment lexicon as subjective positive, subjective negative and neutral, dialectal tweets “translated” into MSA.

* `MASC <https://github.com/almoslmi/masc>`_ {?} - Multi-domain Arabic Sentiment Corpus. 8,860 positive and negative reviews from different domains, in a variety of dialects, as well as a list of 3,880 positive and negative synsets annotated with their part of speech, polarity scores, dialects synsets and inflected forms.

* `MSDA <https://msda.um6p.ma/msda_datasets>`_ {?} - An open access NLP dataset for Arabic dialects. +50K tweets in five (5) national dialects, labeled for several applications: dialect detection, topic detection and sentiment analysis.

* `OCLAR <https://huggingface.co/datasets/oclar>`_ {?} - Opinion Corpus for Lebanese Arabic Reviews. 3900 Arabic customer reviews, on a wide scope of domain, including restaurants, hotels, hospitals, local shops, etc.

* `Omcca <https://github.com/AhmedObaidi/omcca>`_ {?} - Opinion Mining: Analysis of Comments Written in Arabic Colloquial. 28,576 reviews, which represents sentiments of 5,422 different reviewers, covering 27 different categories, collected from Jeeran web site, in Saudi and Jordanian Arabic.

* `NSAR <https://github.com/amahany/NSAR>`_ {?} - Negation and Speculation in Arabic Review. 3K review sentences annotated with negation and speculation in Egyptian dialect.

* `DAICT <https://www.hbku.edu.qa/en/DAICT>`_ {?} - A Dialectal Arabic Irony Corpus Extracted from Twitter. 5,588 tweets - written in both MSA and mixed dialectal Arabic - manually annotated by two professional linguistics from HBKU for irony.

* `IDAT <https://github.com/bilalghanem/multilingual_irony>`_ {`GPLv3`_} - Irony Detection in Arabic Tweets. ~5.5k mixed dialect Arabic tweets annotated by two native Arabic speakers appended with another randomly 5.5k sampled tweets from the original unannotated corpus.

* `iSarcasm <https://github.com/iabufarha/iSarcasmEval>`_ {`MIT`_} - A Dataset of Intended Sarcasm. Dataset of tweets in Arabic and English labeled for sarcasm directly by their authors.

* `AraCovid19-SSD <https://github.com/MohamedHadjAmeur/AraCovid19-SSD>`_ {`CC BY-NC-SA 4.0`_} - Arabic COVID-19 Sentiment and Sarcasm Detection Dataset. Manually annotated multi-label Arabic COVID-19 Sentiment and Sarcasm Detection Dataset. The dataset contains 5,162 annotated tweets.

* `Arabic Sentiment Analysis <https://github.com/motazsaad/arabic-sentiment-analysis>`_ {`Apache License 2.0`_} - 36K tweets labeled into positive and negative, employed distant supervision and self-training approaches into the corpus to annotate it. 8K tweets manually annotated as a gold standard. Corpus evaluated intrinsically by comparing it to human classification and pre-trained sentiment analysis models. Extrinsic evaluation methods exploiting sentiment analysis task applied, achieving an accuracy of 86%.


Emotion Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Topic Classification
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `MSDA <https://msda.um6p.ma/msda_datasets>`_ {?} - An open access NLP dataset for Arabic dialects. +50K tweets in five (5) national dialects, labeled for several applications: dialect detection, topic detection and sentiment analysis.

* `Kawarith <https://github.com/alaa-a-a/kawarith>`_ {`CC BY-NC 4.0`_} - an Arabic Twitter Corpus for Crisis Events. A large-scale crisis-related multi-dialect Arabic Twitter corpus of 1,658,795 unique tweets from 22 emergency events.

* `Arabic Twitter Corpus for Flood Detection <https://github.com/alaa-a-a/Arabic-Twitter-Corpus-for-Flood-Detection>`_ {?} - 4,037 human-labelled Arabic Twitter messages in Middle Eastern dialects, for four high-risk flood events that occurred in 2018, labelled based on relatedness to the crisis and information type.


Text Summarization
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `KALIMAT <https://sourceforge.net/projects/kalimat/>`_ {?} - 20,200 from the Omani newspaper Al Watan with summaries, named entities, art-of-speech tagging, and morphological analysis.

Transliteration
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
* `BOLT <https://catalog.ldc.upenn.edu/LDC2017T07>`_ {`Custom Terms of Use`_} - Egyptian Arabic SMS/Chat and Transliteration. 1,856 naturally-occuring Arabizi conversations transliterated from the original romanized Arabizi script into standard Arabic orthography.


Semantic Role Labeling (SRL)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Coreference Resolution
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Relation Extraction
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Text Classification
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `Satirical Fake News Dataset <https://github.com/sadanyh/Arabic-Satirical-Fake-News-Dataset>`_ {?} - Scraped from two satirical news websites, Al-Hudood and Al-Ahram Al-Mexici, for training fake news classifier/identifier.

Discourse Analysis
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Dialogue Modeling
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Machine Translation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Readability Assessment
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
* `ARC-WMI <https://github.com/iwan-rg/ARC-WMI>`_ {`CC BY-NC-SA 4.0`_} - Arabic collection of written medicine information annotated with readability levels, contains 4476 sentences with over 61k words, extracted from 94 sources of Arabic written medicine information, annotated and assigned a readability level by a panel of health-care professionals.




Aligned/Parallel Corpora
-----------------------------------

Recorded Speech and Audio Corpora
----------------------------------------------------

* `DiaCorpus <https://idc-dsi.github.io/DiaCorpus/>`_ {`CC BY-SA 4.0`_} - The DiaCorpus project is a collaboration between the Data Science Institute (DSI) and Israeli Innovation authority. The purpose of the project is to create a first of a kind Arabic textual repository, in a local dialect (Israeli / Palestinian). This project is part of the National Language Processing plan of Israel.

* `QASR <https://arabicspeech.org/qasr/>`_ {?} - QCRI Al Jazeera Speech Resource. The largest transcribed Arabic speech corpus with around 2,000 hours with multi-layer annotation, in multi-dialect and code-switching speech, crawled from the Al Jazeera news channel, for speech recognition, dialect identification, punctuation restoration, speaker identification, speaker linking, etc.

* `CHILDES <https://childes.talkbank.org/access/Other/Arabic/Salama.html>`_ {?} - Egyptian Arabic Salama Corpus. Transcripted utterances + audio by children in Egyptian dialect.


**Lexical Resources**
================

Lexicons
--------------

Monolingual Lexicons
^^^^^^^^^^^^^^^^^^^^^^^^^
* `NileULex <https://github.com/NileTMRG/NileULex>`_ {?} - Nile University's Arabic sentiment Lexicon. Egyptian Arabic and Modern Standard Arabic sentiment words and their polarity, available for research, commercial use requires author permission.

* `SenZi <https://tahatobaili.github.io/project-rbz/>`_ {?} - A Sentiment Analysis Lexicon for the Latinised Arabic (Arabizi) - Lebanese dialect Arabizi sentiment lexicon, sentiment annotated datasets, and a Facebook corpus.




Bilingual/Multilingual Lexicons
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
* `Maknuune <https://sites.google.com/nyu.edu/palestine-lexicon>`_ {`CC BY-SA 4.0`_} - A large open lexicon for the Palestinian Arabic dialect. Maknuune has over 36K entries from 17K lemmas, and 3.7K roots. All entries include diacritized Arabic orthography, phonological transcription and English glosses. Some entries are enriched with additional information

* `word2word <https://github.com/Kyubyong/word2word>`_ {`Apache License 2.0`_} - Easy-to-use word-to-word translations for 3,564 language pairs. Hebrew is one of the 62 supported languages, and thus word-to-word translation to/from Hebrew is supported for 61 languages.


Dictionaries & Word Lists
-------------------------------------------

* `Arabizi-Transliteration Corpus <https://github.com/bashartalafha/Arabizi-Transliteration>`_ {?} - the first large-scale "Arabizi to Arabic script" parallel corpus focusing on the Jordanian dialect and consisting of more than 25k pairs carefully created and inspected by native speakers to ensure highest quality, taken from Twitter, Facebook and ASK.

* `Arabic Stop Words <https://github.com/mohataher/arabic-stop-words/tree/master>`_ {?} - A list of ~750 possible stop words in Arabic.

* `Arabic Stop Words <https://github.com/mohataher/arabic-stop-words/tree/master>`_ {?} - A list of ~750 possible stop words in Arabic.

* `Buckwalter’s list of Arabic roots <https://www.angelfire.com/tx4/lisan/roots1.htm>`_ {?}


Word Embeddings
------------------------------

* `Spark NLP for Arabic <https://www.johnsnowlabs.com/arabic-natural-language-processing-with-spark-nlp/>`_ {Multiple} - 45 pre-trained models covering Named entity recognition, Translation, Word and sentence embeddings, Named Entity Recognition (NER), Stop words removal, Part-of-Speech (POS), and Lemmatization.

* `DiaLex <https://github.com/UBC-NLP/dialex>`_ {?} - A testbank of word pairs for six syntactic and semantic relations across five important Arabic dialects was created, and used to evaluate a set of existing and new Arabic word embeddings.


**Models and Tools**
================

Models and Tools by Task
------------------------------------------

Text Preprocessing and Morphological Analysis
^^^^^^^^^^^^^^^^^^^^^^

Tokenization
~~~~~~~~~~~~

* `Light10 <https://github.com/linguatools/ArabicStemmer>`_ {`Apache License 2.0`_} - A tokenizer and stemmer for Arabic based on Lucene's UTF-8 tokenizer and ArabicStemmer. The ArabicStemmer is Lucene's implementation of Larkey’s light stemmer Light10. 

* `MADAMIRA <https://inventions.techventures.columbia.edu/technologies/arabic-language-for--CU14012>`_ {`Custom Terms of Use`_} - MADAMIRA is a morphological analyzer that provides tokenization, part-of-speech tagging, Morphological disambiguation for full range of morphological features, lemmatization, diacritization, named entity recognition and base phrase chunking. 

* `CAMeL Tools <https://github.com/CAMeL-Lab/camel_tools>`_ {`MIT`_} - an open-source Python toolkit that supports Arabic and Arabic dialect pre-processing, morphological modeling, dialect identification, named entity recognition and sentiment analysis. CAMeL Tools provides command-line interfaces (CLIs) and application programming interfaces (APIs) covering these utilities.

* `SAFAR <http://arabic.emi.ac.ma/safar/>`_ (`Demo <http://arabic.emi.ac.ma/safar/>`_) {Multiple} - Software Architecture For ARrabic. It is open source, cross-platform, modular, and provides an integrated development environment (IDE). It includes: 1) resources needed for different treatments of Arabic NLP, 2) basic levels modules of language, especially those of the Arabic language, namely morphology, syntax and semantics, and 3) applications for the ANLP. All integrated tools and resources remain under the copyright of their original authors. Each layer is developed as a set of reusable Java API: 1) Tools: includes a range of technical services (statistical functions, test tools, tokenization, sentences splitting etc.). 2) Resource Services: Provides resource language consultation such as lexicons and corpora. 3) NLP services: Contains three layers of processing language Regular (morphology, syntax and semantics). 4) Applications: Contains high-level applications that use layers listed above. 5) Client: In case the user needs to directly use the services layer.


Transliteration
~~~~~~~~~~~~~~~~

* `CAMeL Tools <https://github.com/CAMeL-Lab/camel_tools>`_ {`MIT`_} - an open-source Python toolkit that supports Arabic and Arabic dialect pre-processing, morphological modeling, dialect identification, named entity recognition and sentiment analysis. CAMeL Tools provides command-line interfaces (CLIs) and application programming interfaces (APIs) covering these utilities.

* `ElixirFM <https://github.com/otakar-smrz/elixir-fm>`_ {?} - ElixirFM is a functional morphological analyzer that utilizes syntactic features to distinguish a word's sense. ElixirFM uses the correlation between Arabic grammar and morphology to improve the root extraction process; it uses Prague Arabic Dependency Treebank (PADT) to provide annotated syntactic features associated with stem dictionary (ElixirFM lexicon) for additional morphological knowledge. The lexicon of ElixirFM is derived from the open source Buckwalter lexicon.

* `SAFAR <http://arabic.emi.ac.ma/safar/>`_ (`Demo <http://arabic.emi.ac.ma/safar/>`_) {Multiple} - Software Architecture For ARrabic. It is open source, cross-platform, modular, and provides an integrated development environment (IDE). It includes: 1) resources needed for different treatments of Arabic NLP, 2) basic levels modules of language, especially those of the Arabic language, namely morphology, syntax and semantics, and 3) applications for the ANLP. All integrated tools and resources remain under the copyright of their original authors. Each layer is developed as a set of reusable Java API: 1) Tools: includes a range of technical services (statistical functions, test tools, tokenization, sentences splitting etc.). 2) Resource Services: Provides resource language consultation such as lexicons and corpora. 3) NLP services: Contains three layers of processing language Regular (morphology, syntax and semantics). 4) Applications: Contains high-level applications that use layers listed above. 5) Client: In case the user needs to directly use the services layer.

* `ATAR <https://github.com/bashartalafha/Arabizi-Transliteration>`_ {?} - An ATtention-based LSTM model for ARabizi transliteration.

* `Tafqit <https://github.com/MohsenAlyafei/tafqit>`_ {`MIT`_} - Transliteration of numbers to words.



Morphological Analysis
~~~~~~~~~~~~~~~~~~~~~~~~

* `BAMA 2.0 <https://catalog.ldc.upenn.edu/LDC2004L02>`_ {`Custom Terms of Use`_} - Buckwalter Arabic Morphological Analyzer Version 2.0. A stem-based morphological analyzer (stemmer).

* `SAMA 3.1 <https://catalog.ldc.upenn.edu/LDC2010L01>`_ {`Custom Terms of Use`_} - Standard Arabic Morphological Analyzer (SAMA) Version 3.1. The LDC Standard Arabic Morphological Analyzer (SAMA) Version 3.1 is based on, and updates, Buckwalter Arabic Morphological Analyzer (BAMA) 2.0. SAMA is a software tool for the morphological analysis of Standard Arabic. It considers each Arabic word token in all possible prefix-stem-suffix segmentations, and lists all known/possible annotation solutions, with assignment of all diacritic marks, morpheme boundaries (separating clitics and inflectional morphemes from stems), and all Part-of-Speech (POS) labels and glosses for each morpheme segment. The generated output may then be reviewed by users, and the most appropriate annotation selected from among several choices. The input format, output format, and data layer of SAMA 3.1 were designed to be backward compatible with BAMA. Incremental changes to the data layer in SAMA have resulted in: 1) increased lexicon coverage in the dictionary files, 2) important changes and additions to the inventory of POS tags, and 3) more possible solutions generated for numerous word forms.

* `AlKhalil <http://oujda-nlp-team.net/category/programms/>`_ {`Apache License 2.0`_} - A diacritizer, POS-Tagger, root extractor, stemmer, lemmatizer, and morphosyntactic analyzer.

* `MADAMIRA <https://inventions.techventures.columbia.edu/technologies/arabic-language-for--CU14012>`_ {`Custom Terms of Use`_} - MADAMIRA is a morphological analyzer that provides tokenization, part-of-speech tagging, Morphological disambiguation for full range of morphological features, lemmatization, diacritization, named entity recognition and base phrase chunking. 

* `CAMeL Tools <https://github.com/CAMeL-Lab/camel_tools>`_ {`MIT`_} - an open-source Python toolkit that supports Arabic and Arabic dialect pre-processing, morphological modeling, dialect identification, named entity recognition and sentiment analysis. CAMeL Tools provides command-line interfaces (CLIs) and application programming interfaces (APIs) covering these utilities.

* `ElixirFM <https://github.com/otakar-smrz/elixir-fm>`_ {?} - ElixirFM is a functional morphological analyzer that utilizes syntactic features to distinguish a word's sense. ElixirFM uses the correlation between Arabic grammar and morphology to improve the root extraction process; it uses Prague Arabic Dependency Treebank (PADT) to provide annotated syntactic features associated with stem dictionary (ElixirFM lexicon) for additional morphological knowledge. The lexicon of ElixirFM is derived from the open source Buckwalter lexicon.

* `ADAM <https://github.com/WaelSalloum/adam>`_ {`Custom Terms of Use`_} - Analyzer for Dialectal Arabic Morphology. ADAM is built based on the `SAMA<https://catalog.ldc.upenn.edu/LDC2010L01>`_ database, and can analyze both Egyptian and Levantine dialects.

* `Qutuf <https://github.com/Qutuf/Qutuf>`_ {`Apache License 2.0`_} - An Arabic Morphological Analyzer (Including Stemming and Root Extraction) and Part-Of-Speech Tagger as an Expert System. Qutuf is aimed to be the Core of a Framework for Arabic NLP. At Qutuf, some new concepts have been identified and implemented. Like First Normalization and Second Normalization text forms at the preprocessing phase and the Premature and Overdue Tagging at the Part-Of-Speech tagging task. Moreover, the POS tagging is designed and implemented as a rule-based expert system. A POS tagset, which is built based on a morphological feature tagset, has been designed and used in Qutuf. Morphological Analysis Includes both Stemming (light stemming) and Root Extraction (heavy stemming). It achieves this by using finite state automata and rules for agreement developed for cliticization parsing. It also uses AlKhalil Morpho Sys open source database for root extraction, pattern matching, morphological feature and POS assignment and closed nouns after enriching it. See also `online interface <http://qutuf.com/>`_.

* `Qalsadi <https://pypi.org/project/qalsadi/>`_ {GPL} - Arabic morphological analyzer Library for python.

* `SAFAR <http://arabic.emi.ac.ma/safar/>`_ (`Demo <http://arabic.emi.ac.ma/safar/>`_) {Multiple} - Software Architecture For ARrabic. It is open source, cross-platform, modular, and provides an integrated development environment (IDE). It includes: 1) resources needed for different treatments of Arabic NLP, 2) basic levels modules of language, especially those of the Arabic language, namely morphology, syntax and semantics, and 3) applications for the ANLP. All integrated tools and resources remain under the copyright of their original authors. Each layer is developed as a set of reusable Java API: 1) Tools: includes a range of technical services (statistical functions, test tools, tokenization, sentences splitting etc.). 2) Resource Services: Provides resource language consultation such as lexicons and corpora. 3) NLP services: Contains three layers of processing language Regular (morphology, syntax and semantics). 4) Applications: Contains high-level applications that use layers listed above. 5) Client: In case the user needs to directly use the services layer.

* `MADA+TOKAN <https://academiccommons.columbia.edu/doi/10.7916/D86D60BS>`_ {`Custom Terms of Use`_} - A versatile and freely available system that can derive extensive morphological and contextual information from raw Arabic text, and then use this information for a multitude of crucial NLP tasks. Applications include high-accuracy part-of-speech tagging, diacritization, lemmatization, disambiguation, stemming, and glossing. 


Morphological Inflection
~~~~~~~~~~~~~~~~~~~~~~~~

* `ElixirFM <https://github.com/otakar-smrz/elixir-fm>`_ {?} - ElixirFM is a functional morphological analyzer that utilizes syntactic features to distinguish a word's sense. ElixirFM uses the correlation between Arabic grammar and morphology to improve the root extraction process; it uses Prague Arabic Dependency Treebank (PADT) to provide annotated syntactic features associated with stem dictionary (ElixirFM lexicon) for additional morphological knowledge. The lexicon of ElixirFM is derived from the open source Buckwalter lexicon.

* `Qutrub <https://github.com/linuxscout/qutrub>`_ {GPL} - An Arabic verb conjugation software. 



Morphological Segmentation
~~~~~~~~~~~~~~~~~~~~~~~~

* `Tashaphyne <https://github.com/linuxscout/tashaphyne>`_ {`GPLv3`_} - Arabic light stemmer and segmenter. It mainly supports light stemming (removing prefixes and suffixes) and gives all possible segmentations. It uses a modified finite state Automaton which allows generating all segmentations. It extracts all possible affixation from a word and provides all possible segmentations of a given word. To extract stem, Tashaphyne removes the longest affix from the word, then the affixes can be validated against a valid affixes list.



Part-of-speech (POS) Tagging
~~~~~~~~~~~~~~~~~~~~~~~~

* `CAMeLBERT <https://github.com/CAMeL-Lab/CAMeLBERT>`_ {`MIT`_} - A collection of pre-trained models for Arabic NLP tasks. The models were fine-tuned for Sentiment Analysis, Dialect Identification, Poetry Classification, NER, POS Tagging.

* `Spark NLP for Arabic <https://www.johnsnowlabs.com/arabic-natural-language-processing-with-spark-nlp/>`_ {Multiple} - 45 pre-trained models covering Named entity recognition, Translation, Word and sentence embeddings, Named Entity Recognition (NER), Stop words removal, Part-of-Speech (POS), and Lemmatization.

* `AlKhalil <http://oujda-nlp-team.net/category/programms/>`_ {`Apache License 2.0`_} - A diacritizer, POS-Tagger, root extractor, stemmer, lemmatizer, and morphosyntactic analyzer.

* `MADAMIRA <https://inventions.techventures.columbia.edu/technologies/arabic-language-for--CU14012>`_ {`Custom Terms of Use`_} - MADAMIRA is a morphological analyzer that provides tokenization, part-of-speech tagging, Morphological disambiguation for full range of morphological features, lemmatization, diacritization, named entity recognition and base phrase chunking. 

* `ElixirFM <https://github.com/otakar-smrz/elixir-fm>`_ {?} - ElixirFM is a functional morphological analyzer that utilizes syntactic features to distinguish a word's sense. ElixirFM uses the correlation between Arabic grammar and morphology to improve the root extraction process; it uses Prague Arabic Dependency Treebank (PADT) to provide annotated syntactic features associated with stem dictionary (ElixirFM lexicon) for additional morphological knowledge. The lexicon of ElixirFM is derived from the open source Buckwalter lexicon.

* `ADAM <https://github.com/WaelSalloum/adam>`_ {`Custom Terms of Use`_} - Analyzer for Dialectal Arabic Morphology. ADAM is built based on the `SAMA<https://catalog.ldc.upenn.edu/LDC2010L01>`_ database, and can analyze both Egyptian and Levantine dialects.

* `Qutuf <https://github.com/Qutuf/Qutuf>`_ {`Apache License 2.0`_} - An Arabic Morphological Analyzer (Including Stemming and Root Extraction) and Part-Of-Speech Tagger as an Expert System. Qutuf is aimed to be the Core of a Framework for Arabic NLP. At Qutuf, some new concepts have been identified and implemented. Like First Normalization and Second Normalization text forms at the preprocessing phase and the Premature and Overdue Tagging at the Part-Of-Speech tagging task. Moreover, the POS tagging is designed and implemented as a rule-based expert system. A POS tagset, which is built based on a morphological feature tagset, has been designed and used in Qutuf. Morphological Analysis Includes both Stemming (light stemming) and Root Extraction (heavy stemming). It achieves this by using finite state automata and rules for agreement developed for cliticization parsing. It also uses AlKhalil Morpho Sys open source database for root extraction, pattern matching, morphological feature and POS assignment and closed nouns after enriching it. See also `online interface <http://qutuf.com/>`_.

* `Qalsadi <https://pypi.org/project/qalsadi/>`_ {GPL} - Arabic morphological analyzer Library for python.

* `SAFAR <http://arabic.emi.ac.ma/safar/>`_ (`Demo <http://arabic.emi.ac.ma/safar/>`_) {Multiple} - Software Architecture For ARrabic. It is open source, cross-platform, modular, and provides an integrated development environment (IDE). It includes: 1) resources needed for different treatments of Arabic NLP, 2) basic levels modules of language, especially those of the Arabic language, namely morphology, syntax and semantics, and 3) applications for the ANLP. All integrated tools and resources remain under the copyright of their original authors. Each layer is developed as a set of reusable Java API: 1) Tools: includes a range of technical services (statistical functions, test tools, tokenization, sentences splitting etc.). 2) Resource Services: Provides resource language consultation such as lexicons and corpora. 3) NLP services: Contains three layers of processing language Regular (morphology, syntax and semantics). 4) Applications: Contains high-level applications that use layers listed above. 5) Client: In case the user needs to directly use the services layer.

* `MADA+TOKAN <https://academiccommons.columbia.edu/doi/10.7916/D86D60BS>`_ {`Custom Terms of Use`_} - A versatile and freely available system that can derive extensive morphological and contextual information from raw Arabic text, and then use this information for a multitude of crucial NLP tasks. Applications include high-accuracy part-of-speech tagging, diacritization, lemmatization, disambiguation, stemming, and glossing. 

Stemming and Lemmatization
~~~~~~~~~~~~~~~~~~~~~~~~
* `Spark NLP for Arabic <https://www.johnsnowlabs.com/arabic-natural-language-processing-with-spark-nlp/>`_ {Multiple} - 45 pre-trained models covering Named entity recognition, Translation, Word and sentence embeddings, Named Entity Recognition (NER), Stop words removal, Part-of-Speech (POS), and Lemmatization.

* `Khoja <https://github.com/motazsaad/khoja-stemmer-command-line>`_ {`Apache License 2.0`_} - A root-based stemmer (heavy stemming; root extractor; rule-based). The algorithm was widely used in Arabic IR. It renders inflectional forms of words to produce their roots by removing their longest prefixes and suffixes, at first. The resulting word is then matched with some predefined patterns and some list-driven roots. The selected pattern depends on the length of the extracted word. Finally, in the algorithm, the extracted root is compared to a list of roots to check its validity.

* `Light10 <https://github.com/linguatools/ArabicStemmer>`_ {`Apache License 2.0`_} - A tokenizer and stemmer for Arabic based on Lucene's UTF-8 tokenizer and ArabicStemmer. The ArabicStemmer is Lucene's implementation of Larkey’s light stemmer Light10. 

* `BAMA 2.0 <https://catalog.ldc.upenn.edu/LDC2004L02>`_ {`Custom Terms of Use`_} - Buckwalter Arabic Morphological Analyzer Version 2.0. A stem-based morphological analyzer (stemmer).

* `SAMA 3.1 <https://catalog.ldc.upenn.edu/LDC2010L01>`_ {`Custom Terms of Use`_} - Standard Arabic Morphological Analyzer (SAMA) Version 3.1. The LDC Standard Arabic Morphological Analyzer (SAMA) Version 3.1 is based on, and updates, Buckwalter Arabic Morphological Analyzer (BAMA) 2.0. SAMA is a software tool for the morphological analysis of Standard Arabic. It considers each Arabic word token in all possible prefix-stem-suffix segmentations, and lists all known/possible annotation solutions, with assignment of all diacritic marks, morpheme boundaries (separating clitics and inflectional morphemes from stems), and all Part-of-Speech (POS) labels and glosses for each morpheme segment. The generated output may then be reviewed by users, and the most appropriate annotation selected from among several choices. The input format, output format, and data layer of SAMA 3.1 were designed to be backward compatible with BAMA. Incremental changes to the data layer in SAMA have resulted in: 1) increased lexicon coverage in the dictionary files, 2) important changes and additions to the inventory of POS tags, and 3) more possible solutions generated for numerous word forms.

* `Tashaphyne <https://github.com/linuxscout/tashaphyne>`_ {`GPLv3`_} - Arabic light stemmer and segmenter. It mainly supports light stemming (removing prefixes and suffixes) and gives all possible segmentations. It uses a modified finite state Automaton which allows generating all segmentations. It extracts all possible affixation from a word and provides all possible segmentations of a given word. To extract stem, Tashaphyne removes the longest affix from the word, then the affixes can be validated against a valid affixes list.

* `Assem <https://github.com/assem-ch/arabicstemmer>`_ {`Custom Terms of Use`_} - Assem's Arabic Light Stemmer is a snowball-based stemming algorithm for Arabic aimed mainly to improve search. Assem stemmer is fast and can be generated in many programming languages through Snowball (a small string processing language designed for creating stemming algorithms to be used in IR systems). Assem stemmer offers light stemming and text normalization. It can be configured to run as root extractor or stemmer, but in two separate packages, because the Snowball framework does not support stemming and rooting at the same time. See code: https://arabicstemmer.com/

* `MOTAZ <https://github.com/motazsaad/arabic-light-stemmer>`_ {`Apache License 2.0`_} - Motaz stemmer provides both root extraction and light stemming. The root extraction part is an implementation of Khoja stemmer with the only difference being using another stopwords list. For the light stemming part, it is an implementation of the Light10 Arabic light stemming algorithm proposed by Larkey and colleagues. Before applying the Light10 algorithm, Motaz stemmer normalizes the input word by removing diacritics, replacing all the forms of Hamza with ا, replacing ة with ه and replacing ى with ي.

* `Al-Stem (Darwish) <https://tides.umiacs.umd.edu/software.html>`_ {?} - Al-stem is a light stemmer, which lightly chops off the following prefixes but in order from right to left (وال، فال، بال، بت، يت، لت، مت، وت، ست، نت، بم، لم، وم، كم، فم، ال، لل، في، وا، وا، فا، لا،با) plus the following suffixes starting from right to left, too (ات، وا، ون، وه، ان، تي، ته، تم، كم، هم، هن، ها، ية، تك، نا، ين، يه، ة، هـ، ي، ا). Darwish and Oard used Al-stem in their experiment to develop a technique for Arabic-English cross-language information retrieval at TREC 2002. By the term cross-language IR, it means the query is written in a language that is different from the documents’ language. Later, Al-Stem has been modified by David Graff from the Linguistic data Consortium (LDC) to strip-off the suffixes (تا and ا) and the prefixes (سي and تت) from the list of suffixes in Al-Stem.

* `Sebawai (Darwish) <https://tides.umiacs.umd.edu/software.html>`_ {?} - a root-based analyzer that is based on automatically derived rules and statistics. Sebawai has two main modules: The first module constructs a list of “word-root” pairs, using a morphological analyzer called ALPNET. Then, it extracts a list of prefixes, suffixes and stem templates, and estimates the probability that a prefix, suffix or stem template would occur. The second module takes a word and produces the possible combinations among prefixes, suffixes and templates. These combinations are obtained by eliminating prefixes and suffixes from words and then comparing all the produced stems to templates. As a result, a list of ranked roots is produced. These roots will be matched automatically against the list of the 10,000 roots extracted from an electronic copy of Lisan Al-Arab to confirm their existence.

* `AlKhalil <http://oujda-nlp-team.net/category/programms/>`_ {`Apache License 2.0`_} - A diacritizer, POS-Tagger, root extractor, stemmer, lemmatizer, and morphosyntactic analyzer.

* `MADAMIRA <https://inventions.techventures.columbia.edu/technologies/arabic-language-for--CU14012>`_ {`Custom Terms of Use`_} - MADAMIRA is a morphological analyzer that provides tokenization, part-of-speech tagging, Morphological disambiguation for full range of morphological features, lemmatization, diacritization, named entity recognition and base phrase chunking. 

* `CAMeL Tools <https://github.com/CAMeL-Lab/camel_tools>`_ {`MIT`_} - an open-source Python toolkit that supports Arabic and Arabic dialect pre-processing, morphological modeling, dialect identification, named entity recognition and sentiment analysis. CAMeL Tools provides command-line interfaces (CLIs) and application programming interfaces (APIs) covering these utilities.

* `ElixirFM <https://github.com/otakar-smrz/elixir-fm>`_ {?} - ElixirFM is a functional morphological analyzer that utilizes syntactic features to distinguish a word's sense. ElixirFM uses the correlation between Arabic grammar and morphology to improve the root extraction process; it uses Prague Arabic Dependency Treebank (PADT) to provide annotated syntactic features associated with stem dictionary (ElixirFM lexicon) for additional morphological knowledge. The lexicon of ElixirFM is derived from the open source Buckwalter lexicon.

* `ADAM <https://github.com/WaelSalloum/adam>`_ {`Custom Terms of Use`_} - Analyzer for Dialectal Arabic Morphology. ADAM is built based on the `SAMA<https://catalog.ldc.upenn.edu/LDC2010L01>`_ database, and can analyze both Egyptian and Levantine dialects.

* `Qutuf <https://github.com/Qutuf/Qutuf>`_ {`Apache License 2.0`_} - An Arabic Morphological Analyzer (Including Stemming and Root Extraction) and Part-Of-Speech Tagger as an Expert System. Qutuf is aimed to be the Core of a Framework for Arabic NLP. At Qutuf, some new concepts have been identified and implemented. Like First Normalization and Second Normalization text forms at the preprocessing phase and the Premature and Overdue Tagging at the Part-Of-Speech tagging task. Moreover, the POS tagging is designed and implemented as a rule-based expert system. A POS tagset, which is built based on a morphological feature tagset, has been designed and used in Qutuf. Morphological Analysis Includes both Stemming (light stemming) and Root Extraction (heavy stemming). It achieves this by using finite state automata and rules for agreement developed for cliticization parsing. It also uses AlKhalil Morpho Sys open source database for root extraction, pattern matching, morphological feature and POS assignment and closed nouns after enriching it. See also `online interface <http://qutuf.com/>`_.

* `Qalsadi <https://pypi.org/project/qalsadi/>`_ {GPL} - Arabic morphological analyzer Library for python.

* `SAFAR <http://arabic.emi.ac.ma/safar/>`_ (`Demo <http://arabic.emi.ac.ma/safar/>`_) {Multiple} - Software Architecture For ARrabic. It is open source, cross-platform, modular, and provides an integrated development environment (IDE). It includes: 1) resources needed for different treatments of Arabic NLP, 2) basic levels modules of language, especially those of the Arabic language, namely morphology, syntax and semantics, and 3) applications for the ANLP. All integrated tools and resources remain under the copyright of their original authors. Each layer is developed as a set of reusable Java API: 1) Tools: includes a range of technical services (statistical functions, test tools, tokenization, sentences splitting etc.). 2) Resource Services: Provides resource language consultation such as lexicons and corpora. 3) NLP services: Contains three layers of processing language Regular (morphology, syntax and semantics). 4) Applications: Contains high-level applications that use layers listed above. 5) Client: In case the user needs to directly use the services layer.

* `MADA+TOKAN <https://academiccommons.columbia.edu/doi/10.7916/D86D60BS>`_ {`Custom Terms of Use`_} - A versatile and freely available system that can derive extensive morphological and contextual information from raw Arabic text, and then use this information for a multitude of crucial NLP tasks. Applications include high-accuracy part-of-speech tagging, diacritization, lemmatization, disambiguation, stemming, and glossing. 


Dependency Parsing
~~~~~~~~~~~~~~~~~~~~~~~~

* `ElixirFM <https://github.com/otakar-smrz/elixir-fm>`_ {?} - ElixirFM is a functional morphological analyzer that utilizes syntactic features to distinguish a word's sense. ElixirFM uses the correlation between Arabic grammar and morphology to improve the root extraction process; it uses Prague Arabic Dependency Treebank (PADT) to provide annotated syntactic features associated with stem dictionary (ElixirFM lexicon) for additional morphological knowledge. The lexicon of ElixirFM is derived from the open source Buckwalter lexicon.

* `SAFAR <http://arabic.emi.ac.ma/safar/>`_ (`Demo <http://arabic.emi.ac.ma/safar/>`_) {Multiple} - Software Architecture For ARrabic. It is open source, cross-platform, modular, and provides an integrated development environment (IDE). It includes: 1) resources needed for different treatments of Arabic NLP, 2) basic levels modules of language, especially those of the Arabic language, namely morphology, syntax and semantics, and 3) applications for the ANLP. All integrated tools and resources remain under the copyright of their original authors. Each layer is developed as a set of reusable Java API: 1) Tools: includes a range of technical services (statistical functions, test tools, tokenization, sentences splitting etc.). 2) Resource Services: Provides resource language consultation such as lexicons and corpora. 3) NLP services: Contains three layers of processing language Regular (morphology, syntax and semantics). 4) Applications: Contains high-level applications that use layers listed above. 5) Client: In case the user needs to directly use the services layer.


Spell Checking and Correction
~~~~~~~~~~~~~~~~~~~~~~~~


Diacritization/Vocalization
~~~~~~~~~~~~~~~~~~~~~~~~

* `Arabic-Tashkeela-Model <https://github.com/Anwarvic/Arabic-Tashkeela-Model>`_ {?} - A diacritization model for Arabic language. This model was built/trained using the Tashkeela: the Arabic diacritization corpus on Kaggle.

* `AlKhalil <http://oujda-nlp-team.net/category/programms/>`_ {`Apache License 2.0`_} - A diacritizer, POS-Tagger, root extractor, stemmer, lemmatizer, and morphosyntactic analyzer.

* `MADAMIRA <https://inventions.techventures.columbia.edu/technologies/arabic-language-for--CU14012>`_ {`Custom Terms of Use`_} - MADAMIRA is a morphological analyzer that provides tokenization, part-of-speech tagging, Morphological disambiguation for full range of morphological features, lemmatization, diacritization, named entity recognition and base phrase chunking. 

* `CAMeL Tools <https://github.com/CAMeL-Lab/camel_tools>`_ {`MIT`_} - an open-source Python toolkit that supports Arabic and Arabic dialect pre-processing, morphological modeling, dialect identification, named entity recognition and sentiment analysis. CAMeL Tools provides command-line interfaces (CLIs) and application programming interfaces (APIs) covering these utilities.

* `MADA+TOKAN <https://academiccommons.columbia.edu/doi/10.7916/D86D60BS>`_ {`Custom Terms of Use`_} - A versatile and freely available system that can derive extensive morphological and contextual information from raw Arabic text, and then use this information for a multitude of crucial NLP tasks. Applications include high-accuracy part-of-speech tagging, diacritization, lemmatization, disambiguation, stemming, and glossing. 


Stopwords Removal
~~~~~~~~~~~~~~~~~~~~~~~~
* `Spark NLP for Arabic <https://www.johnsnowlabs.com/arabic-natural-language-processing-with-spark-nlp/>`_ {Multiple} - 45 pre-trained models covering Named entity recognition, Translation, Word and sentence embeddings, Named Entity Recognition (NER), Stop words removal, Part-of-Speech (POS), and Lemmatization.

* `SAFAR <http://arabic.emi.ac.ma/safar/>`_ (`Demo <http://arabic.emi.ac.ma/safar/>`_) {Multiple} - Software Architecture For ARrabic. It is open source, cross-platform, modular, and provides an integrated development environment (IDE). It includes: 1) resources needed for different treatments of Arabic NLP, 2) basic levels modules of language, especially those of the Arabic language, namely morphology, syntax and semantics, and 3) applications for the ANLP. All integrated tools and resources remain under the copyright of their original authors. Each layer is developed as a set of reusable Java API: 1) Tools: includes a range of technical services (statistical functions, test tools, tokenization, sentences splitting etc.). 2) Resource Services: Provides resource language consultation such as lexicons and corpora. 3) NLP services: Contains three layers of processing language Regular (morphology, syntax and semantics). 4) Applications: Contains high-level applications that use layers listed above. 5) Client: In case the user needs to directly use the services layer.


Language modeling
~~~~~~~~~~~~~~~~~~~~~~~~


Text Normalization
~~~~~~~~~~~~~~~~~~~~~~~~

* `Assem <https://github.com/assem-ch/arabicstemmer>`_ {`Custom Terms of Use`_} - Assem's Arabic Light Stemmer is a snowball-based stemming algorithm for Arabic aimed mainly to improve search. Assem stemmer is fast and can be generated in many programming languages through Snowball (a small string processing language designed for creating stemming algorithms to be used in IR systems). Assem stemmer offers light stemming and text normalization. It can be configured to run as root extractor or stemmer, but in two separate packages, because the Snowball framework does not support stemming and rooting at the same time. See code: https://arabicstemmer.com/

* `CAMeL Tools <https://github.com/CAMeL-Lab/camel_tools>`_ {`MIT`_} - an open-source Python toolkit that supports Arabic and Arabic dialect pre-processing, morphological modeling, dialect identification, named entity recognition and sentiment analysis. CAMeL Tools provides command-line interfaces (CLIs) and application programming interfaces (APIs) covering these utilities.

* `Qutuf <https://github.com/Qutuf/Qutuf>`_ {`Apache License 2.0`_} - An Arabic Morphological Analyzer (Including Stemming and Root Extraction) and Part-Of-Speech Tagger as an Expert System. Qutuf is aimed to be the Core of a Framework for Arabic NLP. At Qutuf, some new concepts have been identified and implemented. Like First Normalization and Second Normalization text forms at the preprocessing phase and the Premature and Overdue Tagging at the Part-Of-Speech tagging task. Moreover, the POS tagging is designed and implemented as a rule-based expert system. A POS tagset, which is built based on a morphological feature tagset, has been designed and used in Qutuf. Morphological Analysis Includes both Stemming (light stemming) and Root Extraction (heavy stemming). It achieves this by using finite state automata and rules for agreement developed for cliticization parsing. It also uses AlKhalil Morpho Sys open source database for root extraction, pattern matching, morphological feature and POS assignment and closed nouns after enriching it. See also `online interface <http://qutuf.com/>`_.

* `SAFAR <http://arabic.emi.ac.ma/safar/>`_ (`Demo <http://arabic.emi.ac.ma/safar/>`_) {Multiple} - Software Architecture For ARrabic. It is open source, cross-platform, modular, and provides an integrated development environment (IDE). It includes: 1) resources needed for different treatments of Arabic NLP, 2) basic levels modules of language, especially those of the Arabic language, namely morphology, syntax and semantics, and 3) applications for the ANLP. All integrated tools and resources remain under the copyright of their original authors. Each layer is developed as a set of reusable Java API: 1) Tools: includes a range of technical services (statistical functions, test tools, tokenization, sentences splitting etc.). 2) Resource Services: Provides resource language consultation such as lexicons and corpora. 3) NLP services: Contains three layers of processing language Regular (morphology, syntax and semantics). 4) Applications: Contains high-level applications that use layers listed above. 5) Client: In case the user needs to directly use the services layer.


Text Analysis
^^^^^^^^^^^^^^^

Content Moderation
~~~~~~~~~~~~~~~~~~~~~~~~

* `ARBERT & MARBERT <https://github.com/UBC-NLP/marbert>`_ {?} - a large scale pre-training masked language model focused on both Dialectal Arabic (DA) and MSA; fine-tuned on ArBench: Sentiment Analysis, Social Meaning, Topic Classification, Dialect Identification, Named Entity Recogntion.


Dialect Identification
~~~~~~~~~~~~~~~~~~~~~~~~
* `CAMeLBERT <https://github.com/CAMeL-Lab/CAMeLBERT>`_ {`MIT`_} - A collection of pre-trained models for Arabic NLP tasks. The models were fine-tuned for Sentiment Analysis, Dialect Identification, Poetry Classification, NER, POS Tagging.

* `ARBERT & MARBERT <https://github.com/UBC-NLP/marbert>`_ {?} - a large scale pre-training masked language model focused on both Dialectal Arabic (DA) and MSA; fine-tuned on ArBench: Sentiment Analysis, Social Meaning, Topic Classification, Dialect Identification, Named Entity Recogntion.

* `CAMeL Tools <https://github.com/CAMeL-Lab/camel_tools>`_ {`MIT`_} - an open-source Python toolkit that supports Arabic and Arabic dialect pre-processing, morphological modeling, dialect identification, named entity recognition and sentiment analysis. CAMeL Tools provides command-line interfaces (CLIs) and application programming interfaces (APIs) covering these utilities.


Question Answering (QA)
~~~~~~~~~~~~~~~~~~~~~~~~

* `AraBERT <https://github.com/aub-mind/araBERT>`_ {Multiple} - Transformer-based Model for Arabic Language Understanding.

* `AraELECTRA <https://github.com/aub-mind/arabert/tree/master/araelectra>`_ {`Custom Terms of Use`_} - An Arabic language representation model, pretrained using the replaced token detection objective on large Arabic text corpora. ARAELECTRA’s performance is validated on three Arabic NLP tasks i.e. question answering (QA), sentiment analysis (SA) and named-entity recognition (NER).


Sentiment Analysis
~~~~~~~~~~~~~~~~~~~~~~~~

* `AraBERT <https://github.com/aub-mind/araBERT>`_ {Multiple} - Transformer-based Model for Arabic Language Understanding.

* `CAMeLBERT <https://github.com/CAMeL-Lab/CAMeLBERT>`_ {`MIT`_} - A collection of pre-trained models for Arabic NLP tasks. The models were fine-tuned for Sentiment Analysis, Dialect Identification, Poetry Classification, NER, POS Tagging.

* `ARBERT & MARBERT <https://github.com/UBC-NLP/marbert>`_ {?} - a large scale pre-training masked language model focused on both Dialectal Arabic (DA) and MSA; fine-tuned on ArBench: Sentiment Analysis, Social Meaning, Topic Classification, Dialect Identification, Named Entity Recogntion.

* `AraELECTRA <https://github.com/aub-mind/arabert/tree/master/araelectra>`_ {`Custom Terms of Use`_} - An Arabic language representation model, pretrained using the replaced token detection objective on large Arabic text corpora. ARAELECTRA’s performance is validated on three Arabic NLP tasks i.e. question answering (QA), sentiment analysis (SA) and named-entity recognition (NER).

* `CAMeL Tools <https://github.com/CAMeL-Lab/camel_tools>`_ {`MIT`_} - an open-source Python toolkit that supports Arabic and Arabic dialect pre-processing, morphological modeling, dialect identification, named entity recognition and sentiment analysis. CAMeL Tools provides command-line interfaces (CLIs) and application programming interfaces (APIs) covering these utilities.


Emotion Detection
~~~~~~~~~~~~~~~~~~~~~~~~
* `ARBERT & MARBERT <https://github.com/UBC-NLP/marbert>`_ {?} - a large scale pre-training masked language model focused on both Dialectal Arabic (DA) and MSA; fine-tuned on ArBench: Sentiment Analysis, Social Meaning, Topic Classification, Dialect Identification, Named Entity Recogntion.


Text Summarization
~~~~~~~~~~~~~~~~~~~~~~~~

Text Classification
~~~~~~~~~~~~~~~~~~~~~~~~

* `CAMeLBERT <https://github.com/CAMeL-Lab/CAMeLBERT>`_ {`MIT`_} - A collection of pre-trained models for Arabic NLP tasks. The models were fine-tuned for Sentiment Analysis, Dialect Identification, Poetry Classification, NER, POS Tagging.


Topic Classification
~~~~~~~~~~~~~~~~~~~~~~~~

* `ARBERT & MARBERT <https://github.com/UBC-NLP/marbert>`_ {?} - a large scale pre-training masked language model focused on both Dialectal Arabic (DA) and MSA; fine-tuned on ArBench: Sentiment Analysis, Social Meaning, Topic Classification, Dialect Identification, Named Entity Recogntion.



Topic Modeling
~~~~~~~~~~~~~~~~~~~~~~~~

Irony/Sarcasm Detection
~~~~~~~~~~~~~~~~~~~~~

Discourse Analysis
~~~~~~~~~~~~~~~~~~~~~~~~

Dialogue Modeling
~~~~~~~~~~~~~~~~~~~~~~~~

Information Extraction
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Named Entity Recognition (NER)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* `AraBERT <https://github.com/aub-mind/araBERT>`_ {Multiple} - Transformer-based Model for Arabic Language Understanding.

* `CAMeLBERT <https://github.com/CAMeL-Lab/CAMeLBERT>`_ {`MIT`_} - A collection of pre-trained models for Arabic NLP tasks. The models were fine-tuned for Sentiment Analysis, Dialect Identification, Poetry Classification, NER, POS Tagging.

* `Spark NLP for Arabic <https://www.johnsnowlabs.com/arabic-natural-language-processing-with-spark-nlp/>`_ {Multiple} - 45 pre-trained models covering Named entity recognition, Translation, Word and sentence embeddings, Named Entity Recognition (NER), Stop words removal, Part-of-Speech (POS), and Lemmatization.

* `ARBERT & MARBERT <https://github.com/UBC-NLP/marbert>`_ {?} - a large scale pre-training masked language model focused on both Dialectal Arabic (DA) and MSA; fine-tuned on ArBench: Sentiment Analysis, Social Meaning, Topic Classification, Dialect Identification, Named Entity Recogntion.

* `AraELECTRA <https://github.com/aub-mind/arabert/tree/master/araelectra>`_ {`Custom Terms of Use`_} - An Arabic language representation model, pretrained using the replaced token detection objective on large Arabic text corpora. ARAELECTRA’s performance is validated on three Arabic NLP tasks i.e. question answering (QA), sentiment analysis (SA) and named-entity recognition (NER).

* `MADAMIRA <https://inventions.techventures.columbia.edu/technologies/arabic-language-for--CU14012>`_ {`Custom Terms of Use`_} - MADAMIRA is a morphological analyzer that provides tokenization, part-of-speech tagging, Morphological disambiguation for full range of morphological features, lemmatization, diacritization, named entity recognition and base phrase chunking. 

* `CAMeL Tools <https://github.com/CAMeL-Lab/camel_tools>`_ {`MIT`_} - an open-source Python toolkit that supports Arabic and Arabic dialect pre-processing, morphological modeling, dialect identification, named entity recognition and sentiment analysis. CAMeL Tools provides command-line interfaces (CLIs) and application programming interfaces (APIs) covering these utilities.



Semantic Role Labeling (SRL)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Temporal Information Extraction
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


Event Extraction
~~~~~~~~~~~~~~~~~~~~~~~~

Coreference Resolution
~~~~~~~~~~~~~~~~~~~~~~~~


Relation Extraction
~~~~~~~~~~~~~~~~~~~~~~~~

Speech and Image Processing
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Speech Recognition
~~~~~~~~~~~~~~~~~~~~~~~~

Speech Synthesis
~~~~~~~~~~~~~~~~~~~~~~~~

Text-to-Speech (TTS)
~~~~~~~~~~~~~~~~~~~~~~~~

Speech-to-Text (STT)
~~~~~~~~~~~~~~~~~~~~~~~~~


Optical Character Recognition (OCR)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


Language Generation
~~~~~~~~~~~~~~~~~~~~~~~~
* `AraGPT2 <https://github.com/aub-mind/arabert/tree/master/aragpt2>`_ {`Custom Terms of Use`_} - Pre-Trained Transformer for Arabic Language Generation.


Machine Translation
~~~~~~~~~~~~~~~~~~~~~~~~
* `Spark NLP for Arabic <https://www.johnsnowlabs.com/arabic-natural-language-processing-with-spark-nlp/>`_ {Multiple} - 45 pre-trained models covering Named entity recognition, Translation, Word and sentence embeddings, Named Entity Recognition (NER), Stop words removal, Part-of-Speech (POS), and Lemmatization.

* `Turjuman <https://github.com/UBC-NLP/turjuman>`_ {`Apache License 2.0`_} - a neural machine translation toolkit. It translates from 20 languages into Modern Standard Arabic (MSA).



Models by Type
----------------------------

Pre-Trained Language Models
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `AraBERT <https://github.com/aub-mind/araBERT>`_ {Multiple} - Transformer-based Model for Arabic Language Understanding.

* `CAMeLBERT <https://github.com/CAMeL-Lab/CAMeLBERT>`_ {`MIT`_} - A collection of pre-trained models for Arabic NLP tasks. The models were fine-tuned for Sentiment Analysis, Dialect Identification, Poetry Classification, NER, POS Tagging.

* `Spark NLP for Arabic <https://www.johnsnowlabs.com/arabic-natural-language-processing-with-spark-nlp/>`_ {Multiple} - 45 pre-trained models covering Named entity recognition, Translation, Word and sentence embeddings, Named Entity Recognition (NER), Stop words removal, Part-of-Speech (POS), and Lemmatization.

* `ARBERT & MARBERT <https://github.com/UBC-NLP/marbert>`_ {?} - A large scale pre-training masked language model focused on both Dialectal Arabic (DA) and MSA; fine-tuned on ArBench: Sentiment Analysis, Social Meaning, Topic Classification, Dialect Identification, Named Entity Recogntion.

* `AraELECTRA <https://github.com/aub-mind/arabert/tree/master/araelectra>`_ {`Custom Terms of Use`_} - An Arabic language representation model, pretrained using the replaced token detection objective on large Arabic text corpora. ARAELECTRA’s performance is validated on three Arabic NLP tasks i.e. question answering (QA), sentiment analysis (SA) and named-entity recognition (NER).

* `AraGPT2 <https://github.com/aub-mind/arabert/tree/master/aragpt2>`_ {`Custom Terms of Use`_} - Pre-Trained Transformer for Arabic Language Generation.

* `QARiB <https://github.com/qcri/QARiB>`_ {`Apache License 2.0`_} - QCRI Arabic and Dialectal BERT (QARiB) model, was trained on a collection of ~ 420 Million tweets and ~ 180 Million sentences of text.


Fine-Tuned Language Models
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
* `AraBERT <https://github.com/aub-mind/araBERT>`_ {Multiple} - Transformer-based Model for Arabic Language Understanding.

* `CAMeLBERT <https://github.com/CAMeL-Lab/CAMeLBERT>`_ {`MIT`_} - A collection of pre-trained models for Arabic NLP tasks. The models were fine-tuned for Sentiment Analysis, Dialect Identification, Poetry Classification, NER, POS Tagging.

* `Spark NLP for Arabic <https://www.johnsnowlabs.com/arabic-natural-language-processing-with-spark-nlp/>`_ {Multiple} - 45 pre-trained models covering Named entity recognition, Translation, Word and sentence embeddings, Named Entity Recognition (NER), Stop words removal, Part-of-Speech (POS), and Lemmatization.

* `ARBERT & MARBERT <https://github.com/UBC-NLP/marbert>`_ {?} - a large scale pre-training masked language model focused on both Dialectal Arabic (DA) and MSA; fine-tuned on ArBench: Sentiment Analysis, Social Meaning, Topic Classification, Dialect Identification, Named Entity Recogntion.

* `AraELECTRA <https://github.com/aub-mind/arabert/tree/master/araelectra>`_ {`Custom Terms of Use`_} - An Arabic language representation model, pretrained using the replaced token detection objective on large Arabic text corpora. ARAELECTRA’s performance is validated on three Arabic NLP tasks i.e. question answering (QA), sentiment analysis (SA) and named-entity recognition (NER).


Multilingual Models
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `BERT's multilingual model <https://github.com/google-research/bert/blob/master/multilingual.md>`_ - Trained (also) on Hebrew.


Pipelines/Parsers
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `MADAMIRA <https://inventions.techventures.columbia.edu/technologies/arabic-language-for--CU14012>`_ {`Custom Terms of Use`_} - MADAMIRA is a morphological analyzer that provides tokenization, part-of-speech tagging, Morphological disambiguation for full range of morphological features, lemmatization, diacritization, named entity recognition and base phrase chunking. 

* `CAMeL Tools <https://github.com/CAMeL-Lab/camel_tools>`_ {`MIT`_} - an open-source Python toolkit that supports Arabic and Arabic dialect pre-processing, morphological modeling, dialect identification, named entity recognition and sentiment analysis. CAMeL Tools provides command-line interfaces (CLIs) and application programming interfaces (APIs) covering these utilities.

* `ElixirFM <https://github.com/otakar-smrz/elixir-fm>`_ {?} - ElixirFM is a functional morphological analyzer that utilizes syntactic features to distinguish a word's sense. ElixirFM uses the correlation between Arabic grammar and morphology to improve the root extraction process; it uses Prague Arabic Dependency Treebank (PADT) to provide annotated syntactic features associated with stem dictionary (ElixirFM lexicon) for additional morphological knowledge. The lexicon of ElixirFM is derived from the open source Buckwalter lexicon.




Causal Language Models (CLM)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `AraGPT2 <https://github.com/aub-mind/arabert/tree/master/aragpt2>`_ {`Custom Terms of Use`_} - Pre-Trained Transformer for Arabic Language Generation.


**Commercial and Online Services**
===========================

* `verbit.ai <https://verbit.ai/>`_ - Transcription.

* `Text Analytics for health containers <https://learn.microsoft.com/en-us/azure/cognitive-services/language-service/text-analytics-for-health/how-to/use-containers?tabs=language>`_ 


**Annotation Tools**
=================

* `LightTag <https://www.lighttag.io/>`_  - A tool for managing annotation projects. Handles right-to-left and part-of-word marking. Tutorial video: https://www.youtube.com/watch?v=eTlrTC_n_yg

* `Recogito <http://recogito.pelagios.org/>`_ [Scala, JavaScript, HTML] {`Apache License 2.0`_} - A tool for linked data annotation.

* `CATMA <http://catma.de/>`_ [HTML, Java] {unclear} - A web-based tool for research and collaboration over text data. Handles right-to-left and part-of-word marking. See the system itself here: http://portal.catma.de/catma/, and the code here: https://github.com/mpetris/catma

* `WebAnno <https://webanno.github.io/>`_ [Java] {`Apache License 2.0`_} - Web-based. Support RTL and project management. Repository: https://github.com/webanno/webanno

* `Arethusa: Annotation Environment <https://www.perseids.org/tools/arethusa/app/#/>`_ [JavaScript] {`MIT`_} - A backend-independent client-side annotation framework. `Repository here <https://github.com/alpheios-project/arethusa>`_.

* `rasa-nlu-trainer <https://github.com/RasaHQ/rasa-nlu-trainer>`_ [JavaScript] {`MIT`_} - A tool to edit training examples for `rasa NLU <https://github.com/rasahq/rasa_nlu>`_. Handles right-to-left and part-of-word marking.

* `brat <http://brat.nlplab.org/>`_ [Python, JavaScript] {`MIT`_} - An online environment for collaborative text annotation. Does not support right-to-left. `Repository here <https://github.com/nlplab/brat>`_.

* `openNLP <https://opennlp.apache.org/>`_ [Java] {`Apache License 2.0`_} - OpenNLP has a tagging tool.

* `opeNER <http://www.opener-project.eu/>`_ [Ruby, HTML, Java, Python] - opeNER has a tagging tool.

* `pybossa <http://pybossa.com/>`_ [Python] {`AGPL-3.0`_} - A framework for crowdsourcing of data analysis and enrichment tasks. `GitHub <https://github.com/Scifabric/pybossa>`_.

* `TextThrasher <https://github.com/Goodly/TextThresher>`_ [JavaScript, Python] - A crowdsourced text annotator. Built with React and Redux (possibly also with pybossa). 

* `doccano <https://github.com/doccano/doccano>`_ {MIT} - an open source text annotation tool for humans. It provides annotation features for text classification, sequence labeling and sequence to sequence tasks. So, you can create labeled data for sentiment analysis, named entity recognition, text summarization and so on.

**Evaluation**
============

Benchmark Datasets
-----------------------------------


Evaluation Metrics
--------------------------------


**Labs & Organizations**
=====================

* `CAMeL Labs <https://nyuad.nyu.edu/en/research/faculty-labs-and-projects/computational-approaches-to-modeling-language-lab/research/arabic-natural-language-processing.html>`_ - NLP projects by NYU Abu-Dabi.

* `SIGARAB <https://www.sigarab.org/>`_ - The Special Interest Group of the Association for Computational Linguistics for researchers concerned with all aspects of Arabic NLP.

* `Stanford University NLP Group <https://nlp.stanford.edu/projects/arabic.shtml>`_ - Articles and tools for Arabic NLP.

* `John Snow Labs <https://www.johnsnowlabs.com/arabic-natural-language-processing-with-spark-nlp/>`_ - Spark NLP for Arabic.

* `Project RBZ <https://tahatobaili.github.io/project-rbz/>`_ - Resourcing Arabizi for NLP.

* `CADIM Consortium <https://www.cadim.net/>`_ - Computational Approaches to Arabic & Arabic Dialect Modeling Consortium.



**Courses, Presentations and Meetups**
===================================

Meetup & Discussion Groups
----------------------------------------


Specific Talks
----------------------------------------



.. _Public Domain: https://en.wikipedia.org/wiki/Public_domain
.. _CC-BY-SA 3.0: https://creativecommons.org/licenses/by-sa/3.0/
.. _AGPL-3.0: https://opensource.org/licenses/AGPL-3.0
.. _GPLv3: http://www.gnu.org/copyleft/gpl.html
.. _CC BY-NC-SA 4.0: https://creativecommons.org/licenses/by-nc-sa/4.0/
.. _CC BY-NC 4.0: https://creativecommons.org/licenses/by-nc/4.0/
.. _Apache License 2.0: https://www.apache.org/licenses/LICENSE-2.0
.. _MIT: https://en.wikipedia.org/wiki/MIT_License
.. _CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/
.. _CC0 1.0: https://creativecommons.org/publicdomain/zero/1.0/
.. _CC BY-NC-ND 4.0: https://creativecommons.org/licenses/by-nc-nd/4.0/
.. _CC-BY-SA 4.0: https://creativecommons.org/licenses/by-sa/4.0/legalcode
.. _Custom Terms of Use: http://web.nli.org.il/sites/JPress/English/about/Pages/tems-of-use.aspx
.. _GPLv2: https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html
.. _Open: https://opendefinition.org/od/2.1/en/

