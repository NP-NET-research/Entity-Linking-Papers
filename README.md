# Neural Entity Linking Papers

This is a repo listing some recommended papers on Neural Entity Linking Paper.

## General Architecture

### Candidate Generation

#### surface form matching

1. **"Combining word and entity embeddings for entity linking"** *Jose G. Moreno, Romaric Besancon , Romain Beaumont* (ESWC 2017) [[paper]](https://perso.limsi.fr/bg/fichiers/2017/combining-word-entity-eswc2017.pdf) [code]

#### dictionary lookup

1. **"Personalized page rank for named entity disambiguation"** *Maria Pershina, Yifan He, Ralph Grishman* (NAACL 2015)[[paper]](https://aclanthology.org/N15-1026.pdf)

2. **"YAGO A core of semantic knowledge unifying wordnet and wikipedia"** *Fabian M. Suchanek, Gjergji Kasneci, Gerhard Weikum* (www 2007) [[paper]](https://www2007.org/papers/paper391.pdf) [code]

#### prior probability

1. **"A Cross-Lingual Dictionary for English Wikipedia Concepts"** *Valentin I. Spitkovsky, Angel X. Chang* (LREC 2012) [[paper]](https://aclanthology.org/L12-1109/) [code]

2. **"Deep joint entity disambiguation with local neural attention"** *Octavian-Eugen Ganea, Thomas Hofmann* (EMNLP 2017) [[paper]](https://aclanthology.org/D17-1277/) [code]

### Context-Mention Encoding

#### recurrent architecture

1. **"Entity linking via joint encoding of types, descriptions, and context"** *Nitish Gupta, Sameer Singh, Dan Roth* (EMNLP 2017) [[paper]](https://aclanthology.org/D17-1284/) [code]

2. **"End-to-end neural entity linking"** *Nikolaos Kolitsas, Octavian-Eugen Ganea, Thomas Hofmann* (CoNLL 2018) [[paper]](https://aclanthology.org/K18-1050/) [code]

3. **"Neural cross-lingual entity linking"** *Avirup Sil, Gourab Kundu, Radu Florian, Wael Hamza* (AAAI 2018) [[paper]](https://arxiv.org/abs/1712.01813) [code]

#### self-attention

1. **"Zero-shot entity linking by reading entity descriptions"** *Lajanugen Logeswaran, Ming-Wei Chang, Kenton Lee* (ACL 2019) [[paper]](https://aclanthology.org/P19-1335/) [code]

2. **"Scalable Zero-shot Entity Linking with Dense Entity Retrieval"** *Ledell Wu, Fabio Petroni, Martin Josifoski* (EMNLP 2020) [[paper]](https://aclanthology.org/2020.emnlp-main.519/) [code]

3. **"Global Entity Disambiguation with Pretrained Contextualized Embeddings of Words and Entities"** *Ikuya Yamada, Koki Washio, Hiroyuki Shindo, Yuji Matsumoto* (2019) [[paper]](https://arxiv.org/abs/1909.00426) [code]

### Entity Encoding

#### pre-trained：基于原始标注文本

1. **"Combining word and entity embeddings for entity linking"** *Jose G. Moreno, Romaric Besancon , Romain Beaumont* (ESWC 2017) [[paper]](https://perso.limsi.fr/bg/fichiers/2017/combining-word-entity-eswc2017.pdf) [code]

2. **"Robust and Collective Entity Disambiguation through Semantic Embeddings Stefan"** *Stefan Zwicklbauer, Christin Seifert, Michael Granitzer* (SIGIR 2016) [[paper]](https://www.semanticscholar.org/paper/Robust-and-Collective-Entity-Disambiguation-through-Zwicklbauer-Seifert/ec1513289f00a49c4135909d517857fd6fba7fc9) [code]

3. **"Jointly Embedding Entities and Text with Distant Supervision"** *Denis Newman-Griffis, Albert M Lai, Eric Fosler-Lussier* (ACL 2018) [[paper]](https://aclanthology.org/W18-3026) [code]

4. **"Improving neural entity disambiguation with graph embeddings"** *Özge Sevgili, Alexander Panchenko, Chris Biemann* (ACL 2019) [[paper]](https://aclanthology.org/P19-2044/) [code]

#### joint encoding and ranking

1. **"Learning dense representations for entity retrieval"** *Daniel Gillick, Sayali Kulkarni, Larry Lansing,* (CoNLL 2019) [[paper]](./papers/Gillick et al. - 2019 - Learning dense representations for entity retrieval.pdf) [code]

2. **"Entity linking via joint encoding of types, descriptions, and context"** *Nitish Gupta, Sameer Singh, Dan Roth* (EMNLP 2017) [[paper]](https://aclanthology.org/D17-1284/) [code]

3. **"Zero-shot entity linking by reading entity descriptions"** *Lajanugen Logeswaran, Ming-Wei Chang, Kenton Lee* (ACL 2019) [[paper]](https://aclanthology.org/P19-1335/) [code]

### Unlinkable Mention Prediction

#### no candidate

1. **"Neural cross-lingual entity linking"** *Avirup Sil, Gourab Kundu, Radu Florian, Wael Hamza* (AAAI 2018) [[paper]](https://arxiv.org/abs/1712.01813) [code]

2. **"Cross-lingual Wikification Using Multilingual Embeddings"** *Chen-Tse Tsai, Dan Roth* (NAACL 2016) [[paper]](.https://aclanthology.org/N16-1072/) [code]

#### threshold

1. **"Plato A Selective Context Model for Entity Resolution"** *Nevena Lazic, Amarnag Subramanya, Michael Ringgaard, Fernando Pereira* (TACL 2015)[[paper]](https://aclanthology.org/Q15-1036/) [code]

2. **"Knowledge enhanced word representation"** *Matthew E. Peters, Mark Neumann, Robert Logan* (EMNLP 2019) [[paper]](https://aclanthology.org/D19-1005/) [code]

#### NIL predictor

1. **"End-to-end neural entity linking"** *Nikolaos Kolitsas, Octavian-Eugen Ganea, Thomas Hofmann* (CoNLL 2018) [[paper]](https://aclanthology.org/K18-1050/) [code]

#### separate model

1. **"Joint learning of named entity recognition and entity linking"** *Pedro Henrique Martins, Zita Marinho, André F. T. Martins* (ACL 2019) [[paper]](https://aclanthology.org/P19-2026/) [code]

2. **"Combining word and entity embeddings for entity linking"** *Jose G. Moreno, Romaric Besancon , Romain Beaumont* (ESWC 2017) [[paper]](https://perso.limsi.fr/bg/fichiers/2017/combining-word-entity-eswc2017.pdf) [code]

## Modifications of the General Architecture

### Joint Entity Recognition and Disambiguation Architecture

#### candidate based

1. **"End-to-end neural entity linking"** *Nikolaos Kolitsas, Octavian-Eugen Ganea, Thomas Hofmann* (CoNLL 2018) [[paper]](https://aclanthology.org/K18-1050/) [code]

2. **"Knowledge enhanced word representation"** *Matthew E. Peters, Mark Neumann, Robert Logan* (EMNLP 2019) [[paper]](https://aclanthology.org/D19-1005/) [code]

#### multitask learning 

1. **"Joint learning of named entity recognition and entity linking"** *Pedro Henrique Martins, Zita Marinho, André F. T. Martins* (ACL 2019) [[paper]](https://aclanthology.org/P19-2026/) [code]

#### sequence labeling

1. **"Investigating entity knowledge in BERT with simple neural end-to-end entity linking"** *Samuel Broscheit* (CoNLL 2019) [[paper]](https://aclanthology.org/K19-1063/) [code]

### Global Context Architecture

#### random walk based

1. **"Robust named entity disambiguation with random walks"** *Zhaochen Guo, Denilson Barbosa* (SWJ 2016) [[paper]](http://www.semantic-web-journal.net/content/robust-named-entity-disambiguation-random-walks) [code]

2. **"Personalized page rank for named entity disambiguation"** *Maria Pershina, Yifan He, Ralph Grishman* (NAACL 2015)[[paper]](https://aclanthology.org/N15-1026.pdf)

3. **"Robust and Collective Entity Disambiguation through Semantic Embeddings Stefan"** *Stefan Zwicklbauer, Christin Seifert, Michael Granitzer* (SIGIR 2016) [[paper]](https://www.semanticscholar.org/paper/Robust-and-Collective-Entity-Disambiguation-through-Zwicklbauer-Seifert/ec1513289f00a49c4135909d517857fd6fba7fc9) [code]

#### maximization of CRF potentials

1. **"Deep joint entity disambiguation with local neural attention"** *Octavian-Eugen Ganea, Thomas Hofmann* (EMNLP 2017) [[paper]](https://aclanthology.org/D17-1277/) [code]

2. **"Improving entity linking by modeling latent relations between mentions"** *Phong Le, Ivan Titov* (ACL 2018) [[paper]](./papers/Le, Titov - 2018 - Improving entity linking by modeling latent relations between mentions.pdf) [code]

#### sequential decision task

1. **"Joint Entity Linking with Deep Reinforcement Learning"** *Zheng Fang, Yanan Cao, Dongjie Zhang* (2019) [[paper]](https://arxiv.org/abs/1902.00330) [code]

2. **"Learning dynamic context augmentation for global entity linking"** *Xiyuan Yang, Xiaotao Gu, Sheng Lin, Siliang Tang* (EMNLP 2019) [[paper]](https://aclanthology.org/D19-1026/) [code]

3. **"Global Entity Disambiguation with Pretrained Contextualized Embeddings of Words and Entities"** *Ikuya Yamada, Koki Washio, Hiroyuki Shindo, Yuji Matsumoto* (2019) [[paper]](https://arxiv.org/abs/1909.00426) [code]

#### neural model component

1. **"Neural Collective Entity Linking"** *Yixin Cao, Lei Hou, Juanzi Li, Zhiyuan Liu* (COLING 2018)[[paper]](https://arxiv.org/abs/1811.08603) [code]

2. **"Collective entity resolution with multi-focal attention"** *Amir Globerson, Nevena Lazic, Soumen Chakrabarti* (ACL 2016) [[paper]](https://aclanthology.org/P16-1059/) [code]

3. **"End-to-end neural entity linking"** *Nikolaos Kolitsas, Octavian-Eugen Ganea, Thomas Hofmann* (CoNLL 2018) [[paper]](https://aclanthology.org/K18-1050/) [code]

#### larger context

1. **"Bridging text and knowledge by learning multi-prototype entity mention embedding"** *Yixin Cao, Lifu Huang, Heng Ji, Xu Chen, Juanzi Li* (ACL 2017) [[paper]](https://aclanthology.org/P17-1149/) [code]

2. **"Entity linking via joint encoding of types, descriptions, and context"** *Nitish Gupta, Sameer Singh, Dan Roth* (EMNLP 2017) [[paper]](https://aclanthology.org/D17-1284/) [code]

3. **"Knowledge enhanced word representation"** *Matthew E. Peters, Mark Neumann, Robert Logan* (EMNLP 2019) [[paper]](https://aclanthology.org/D19-1005/) [code]

### Domain Independent Architecture

#### distant learning

1. **"Distant learning for entity linking with automatic noise detection"** *Phong Le, Ivan Titov* (ACL 2019) [[paper]](https://aclanthology.org/P19-1400/) [code]

2. **"Boosting Entity Linking Performance by Leveraging Unlabeled Documents"** *Phong Le, Ivan Titov* (ACL 2019) [[paper]](https://aclanthology.org/P19-1187) [code]

#### zero-shot

1. **"Learning dense representations for entity retrieval"** *Daniel Gillick, Sayali Kulkarni, Larry Lansing,* (CoNLL 2019) [[paper]](./papers/Gillick et al. - 2019 - Learning dense representations for entity retrieval.pdf) [code]

2. **"Zero-shot entity linking by reading entity descriptions"** *Lajanugen Logeswaran, Ming-Wei Chang, Kenton Lee* (ACL 2019) [[paper]](https://aclanthology.org/P19-1335/) [code]

3. **"Scalable Zero-shot Entity Linking with Dense Entity Retrieval"** *Ledell Wu, Fabio Petroni, Martin Josifoski* (EMNLP 2020) [[paper]](https://aclanthology.org/2020.emnlp-main.519/) [code]

### Cross-lingual Architecture

#### representation based

1. **"Cross-lingual Name Tagging and Linking for 282 Languages"** *Xiaoman Pan, Boliang Zhang, Jonathan May* (ACL 2017) [[paper]](https://aclanthology.org/P17-1178/) [code]

2.  **"Cross-lingual Wikification Using Multilingual Embeddings"** *Chen-Tse Tsai, Dan Roth* (NAACL 2016) [[paper]](.https://aclanthology.org/N16-1072/) [code]

#### zero-shot

1. **"Neural cross-lingual entity linking"** *Avirup Sil, Gourab Kundu, Radu Florian, Wael Hamza* (AAAI 2018) [[paper]](https://arxiv.org/abs/1712.01813) [code]

2. **"Joint multilingual supervision for cross-lingual entity linking"** *Shyam Upadhyay, Nitish Gupta, Dan Roth* ( EMNLP 2018) [[paper]](https://arxiv.org/abs/1809.07657) [code]

## SOTA 

### AIDA-CoNLL

#### entity disambiguation

1. **"Entity-aware ELMo Learning Contextual Entity Representation for Entity Disambiguation"** *Hamed Shahbazi, Xiaoli Z. Fern, Reza Ghaeini,* (2019) [[paper]](https://arxiv.org/abs/1908.05762) [code] [Accuracy: 0.962]

2. **"Global Entity Disambiguation with Pretrained Contextualized Embeddings of Words and Entities"** *Ikuya Yamada, Koki Washio, Hiroyuki Shindo, Yuji Matsumoto* (2019) [[paper]](https://arxiv.org/abs/1909.00426) [code] [Accuracy: 0.950]

3. **"Evaluating the Impact of Knowledge Graph Context on Entity Disambiguation Models"** *Isaiah Onando Mulang', Kuldeep Singh, Chaitali Prabhu* (CIKM 2020) [[paper]](https://arxiv.org/abs/2008.05190) [code] [Accuracy: 0.9494]

4. **"DeepType Multilingual entity linking by neural type system evolution"** *Jonathan Raiman, Olivier Raiman* (AAAI 2018) [[paper]](https://arxiv.org/abs/1802.01021) [code] [Accuracy: 0.909]  [Accuracy: 0.9488]

5. **"Learning Distributed Representations of Texts and Entities from Knowledge Base"** *Ikuya Yamada, Hiroyuki Shindo, Hideaki Takeda* (2017) [[paper]](https://arxiv.org/abs/1705.02494) [code] [Accuracy: 0.931]

#### entity linking 

1. **"Autoregressive Entity Retrieval"** *Nicola De Cao, Gautier Izacard, Sebastian Riedel, Fabio Petroni* (2021) [[paper]](https://arxiv.org/abs/2010.00904) [code] [Micro-f1 strong: 0.837]

2. **"CHOLAN A modular approach for neural entity linking on wikipedia and wikidata"** *Manoj Prabhakar Kannan Ravi, Kuldeep Singh* (EACL 2021) [[paper]](https://arxiv.org/abs/2101.09969f) [code] [Micro-f1 strong: 0.831]

3. **"End-to-end neural entity linking"** *Nikolaos Kolitsas, Octavian-Eugen Ganea, Thomas Hofmann* (CoNLL 2018) [[paper]](https://aclanthology.org/K18-1050/) [code] [Micro-f1 strong: 0.826]

4. **"Investigating entity knowledge in BERT with simple neural end-to-end entity linking"** *Samuel Broscheit* (CoNLL 2019) [[paper]](https://aclanthology.org/K19-1063/) [code]  [Micro-f1 strong: 0.793]

### TAC 2010

1. **"Scalable Zero-shot Entity Linking with Dense Entity Retrieval"** *Ledell Wu, Fabio Petroni, Martin Josifoski* (EMNLP 2020) [[paper]](https://aclanthology.org/2020.emnlp-main.519/) [code]  [Accuracy: 0.940]

2.  **"Neural Collective Entity Linking"** *Yixin Cao, Lei Hou, Juanzi Li, Zhiyuan Liu* (COLING 2018)[[paper]](https://arxiv.org/abs/1811.08603) [code] [Accuracy: 0.910]

3. **"DeepType Multilingual entity linking by neural type system evolution"** *Jonathan Raiman, Olivier Raiman* (AAAI 2018) [[paper]](https://arxiv.org/abs/1802.01021) [code] [Accuracy: 0.909]

4. **"ELDEN Improved entity linking using densified knowledge graphs"** *Priya Radhakrishnan, Partha Talukdar, Vasudeva Varma* (NAACL 2018) [[paper]](https://aclanthology.org/N18-1167/) [code] [Accuracy: 0.896]

5. **"Entity disambiguation by knowledge and text jointly embedding"** *Wei Fang, Jianwen Zhang, Dilin Wang, Zheng Chen, Ming Li* (CoNLL 2016) [[paper]](https://aclanthology.org/K16-1026/) [code] [Accuracy: 0.889]

### ACE 2004

1. **"Global Entity Disambiguation with Pretrained Contextualized Embeddings of Words and Entities"** *Ikuya Yamada, Koki Washio, Hiroyuki Shindo, Yuji Matsumoto* (2019) [[paper]](https://arxiv.org/abs/1909.00426) [code] [Micro-f1: 0.919]

2. **"Entity linking via joint encoding of types, descriptions, and context"** *Nitish Gupta, Sameer Singh, Dan Roth* (EMNLP 2017) [[paper]](https://aclanthology.org/D17-1284/) [code]

3. **"Joint Entity Linking with Deep Reinforcement Learning"** *Zheng Fang, Yanan Cao, Dongjie Zhang* (2019) [[paper]](https://arxiv.org/abs/1902.00330) [code]  [Micro-f1: 0.912]

4. **"Autoregressive Entity Retrieval"** *Nicola De Cao, Gautier Izacard, Sebastian Riedel, Fabio Petroni* (2021) [[paper]](https://arxiv.org/abs/2010.00904) [code][Micro-f1: 0.901]

5. **"Learning dynamic context augmentation for global entity linking"** *Xiyuan Yang, Xiaotao Gu, Sheng Lin, Siliang Tang* (EMNLP 2019) [[paper]](https://aclanthology.org/D19-1026/) [code]  [Micro-f1: 0.901]

### AQUAINT

1. **"Global Entity Disambiguation with Pretrained Contextualized Embeddings of Words and Entities"** *Ikuya Yamada, Koki Washio, Hiroyuki Shindo, Yuji Matsumoto* (2019) [[paper]](https://arxiv.org/abs/1909.00426) [code] [Micro-f1: 0.935]

2.  **"Boosting Entity Linking Performance by Leveraging Unlabeled Documents"** *Phong Le, Ivan Titov* (ACL 2019) [[paper]](https://aclanthology.org/P19-1187) [code] [Micro-f1: 0.907]

3. **"Autoregressive Entity Retrieval"** *Nicola De Cao, Gautier Izacard, Sebastian Riedel, Fabio Petroni* (2021) [[paper]](https://arxiv.org/abs/2010.00904) [code] [Micro-f1: 0.899]

4. **"Deep joint entity disambiguation with local neural attention"** *Octavian-Eugen Ganea, Thomas Hofmann* (EMNLP 2017) [[paper]](https://aclanthology.org/D17-1277/) [code] [Micro-f1: 0.885]

5. **"Improving entity linking by modeling latent relations between mentions"** *Phong Le, Ivan Titov* (ACL 2018) [[paper]](./papers/Le, Titov - 2018 - Improving entity linking by modeling latent relations between mentions.pdf) [code]

### MSNBC

1. **"Global Entity Disambiguation with Pretrained Contextualized Embeddings of Words and Entities"** *Ikuya Yamada, Koki Washio, Hiroyuki Shindo, Yuji Matsumoto* (2019) [[paper]](https://arxiv.org/abs/1909.00426) [code] [Micro-f1: 0.963]

### KILT

1. **"Autoregressive Entity Retrieval"** *Nicola De Cao, Gautier Izacard, Sebastian Riedel, Fabio Petroni* (2021) [[paper]](https://arxiv.org/abs/2010.00904) [code]

2. **"Scalable Zero-shot Entity Linking with Dense Entity Retrieval"** *Ledell Wu, Fabio Petroni, Martin Josifoski* (EMNLP 2020) [[paper]](https://aclanthology.org/2020.emnlp-main.519/) [code]

3. **"KILT a Benchmark for Knowledge Intensive Language Tasks"** *Fabio Petroni, Aleksandra Piktus, Angela Fan* (NAACL 2021) [[paper]](.https://aclanthology.org/2021.naacl-main.200/) [code]

### DuEL

1. **"Overview of the CCKS 2019 Knowledge Graph Evaluation Track Entity"** *Xianpei Han, Zhichun Wang, Jiangtao Zhang* (CCKS 2019) [[paper]](https://arxiv.org/abs/2003.03875) [code]

## Evaluation & Datasets

1. **"General entity annotator benchmarking framework"** *Ricardo Usbeck,  Michael Röder* (WWW 2015) [[paper]](http://svn.aksw.org/papers/2015/WWW_GERBIL/public.pdf)

2. **"Robust disambiguation of named entities in text"** *Johannes Hoffart, Mohamed Amir Yosef, Ilaria Bordino,* (EMNLP 2011) [[paper]](https://aclanthology.org/D11-1072/)  AIDA

3. **"Overview of the TAC 2010 Knowledge Base Population Track"** *Heng Ji , Ralph Grishman , Hoa Trang Dang* [[paper]](https://blender.cs.illinois.edu/paper/kbp2010overview.pdf) TAC KBP 2010

4. **"Large-Scale Named Entity Disambiguation Based on Wikipedia Data"** *Silviu Cucerzan* (EMNLP 2007) [[paper]](https://aclanthology.org/D07-1074/)  MSNBC

5. **"Learning to link with wikipedia"** *David Milne, Ian H. Witten* (CIKM 2008) [[paper]](./papers/Milne, Witten - 2008 - Learning to link with wikipedia.pdf)  AQUAINT

6. **"Local and Global Algorithms for Disambiguation to Wikipedia"** *Lev Ratinov, Dan Roth, Doug Downey, Mike Anderson* (ACL 2011)[[paper]](https://aclanthology.org/P11-1138/)  ACE2004

## Comments

If you find any errors in the above information, please post it in Issues. Pull requests are welcomed for adding papers. 
