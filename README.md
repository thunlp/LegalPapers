# Must-read Papers on Legal Intelligence

Contributed by Chaojun Xiao, Haoxi Zhong, Yutao Sun

## Overview of Legal Intelligence

1. **How Does NLP Benefit Legal System: A Summary of Legal Artificial Intelligence**.

   *Haoxi Zhong, Chaojun Xiao, Cunchao Tu, Tianyang Zhang, Zhiyuan Liu, Maosong Sun*. ACL 2020. [[pdf](https://arxiv.org/pdf/2004.12158)]



## Datasets

| Dataset                                          | Task                    | Language        | Size                           |
| ------------------------------------------------ | ----------------------- | --------------- | ------------------------------ |
| [Gamper (2000)](#Gamper)                         | Parallel Corpus         | Italian, German | 5m words                       |
| [Grover et al. (2004)](#Grover)                  | Summarization           | English         | 40 documents, 12k sentences    |
| [Hoekstra et al. (2007)](#Hoekstra)              | Ontology                | English         | 2378 concepts                  |
| [Demenko et al. (2008)](#Demenko)                | Speech                  | Polish          | 2h vocal material              |
| [Cvrcek et al. (2012)](#Cvrcek)                  | Dictionary              | Czech           | 10k entries, 20k terms         |
| [Fawei et al. (2016)](#Fawei)                    | Question Answering      | English         | 400 questions                  |
| [Locke et al. (2018)](#Locke)                    | Information Retrieve    | English         | 3m decisions, 2572 assessments |
| [Araujo et al. (2018)](#Lenerbr)               | Name Entity Recognition | Portuguese      | 70 documents                   |
| [Kano et al. (2018)](#Kano)                      | IR and QA               | Japanese        | 285 queries, 651 questions     |
| [Xiao et al. (2018)](#XiaoCAIL2018)              | Judgment Prediction     | Chinese         | 2.68m documents                |
| [Manor et al. (2019)](#Manor)                    | Summarization           | English         | 505 sets, 175 documents        |
| [Chalkidis et al. (2019a)](#ChalkidisNeural)     | Judgment Prediction     | English         | 11.5k documents                |
| [Chalkidis et al. (2019b)](#ChalkidisLargeScale) | Classification          | English         | 57k documents, 4.3k labels     |
| [Duan et al. (2019)](#Duan)                      | Reading Comprehension   | Chinese         | 50k questions, 10k documents   |
| [Xiao et al. (2019)](#XiaoCAIL2019)              | Similar Case Matching   | Chinese         | 9k triplets of documents       |
| [Zhong et al. (2020)](#ZhongJECQA)               | Question Answering      | Chinese         | 30k questions, 80k articles    |

1. <span id="Gamper">**A parallel corpus of Italian/German legal texts.**</span>

   *Johann Gamper.* LREC 2000. [[pdf](http://www.lrec-conf.org/proceedings/lrec2000/pdf/140.pdf)]

2. <span id = "Grover">**The HOLJ corpus: supporting summarisation of legal texts**.</span>

   *Claire Grover, Ben Hachey, Ian Hughson.* COLING 2004. [[pdf](https://www.aclweb.org/anthology/W04-1907)]

3. <span id = "Hoekstra">**The lkif core ontology of basic legal concepts.**</span>

   *Rinke Hoekstra, Joost Breuker, Marcello Di Bello, Alexander Boer.* 2007. [[pdf](http://ceur-ws.org/Vol-321/LOAIT07-Proceedings.pdf#page=43)]

4. <span id = "Demenko">**JURISDIC: Polish speech database for taking dictation of legal texts.**</span>

   *Grazyna Demenko, Stefan Grocholewski, Katarzyna Klessa, Jerzy Ogorkiewicz, Agnieszka Wagner, Marek Lange, Daniel Sledzinski, Natalia Cylwik.* LREC 2008. [[pdf](http://www.lrec-conf.org/proceedings/lrec2008/pdf/326_paper.pdf)]

5. <span id = "Cvrcek">**Legal electronic dictionary for Czech.** </span>

   *Frantisek Cvrcek, Karel Pala, Pavel Rychly*. LREC 2012. [[pdf](http://www.lrec-conf.org/proceedings/lrec2012/pdf/775_Paper.pdf)]

6. <span id = "Fawei">**Passing a USA national bar exam: a first corpus for experimentation.**</span>

   *Biralatei Fawei, Adam Wyner, Jeff Pan.* LREC 2016. [[pdf](https://www.aclweb.org/anthology/L16-1538)]

7. <span id = "Locke">**A Test Collection for Evaluating Legal Case Law Search**.</span>

   *Daniel Locke, Guido Zuccon.* SIGIR 2018. [[pdf](https://dl.acm.org/doi/abs/10.1145/3209978.3210161)]

8. <span id = "Kano">**Coliee-2018: Evaluation of the competition on legal information extraction and entailment.**</span>

   *Yoshinobu Kano, Mi-Young Kim, Masaharu Yoshioka, Yao Lu, Juliano Rabelo, Naoki Kiyota, Randy
   Goebel, Ken Satoh.* JSAI 2018. [[pdf](https://sites.ualberta.ca/~rabelo/COLIEE2019/COLIEE2018_CL_summary.pdf)]

9. <span id = "Lenerbr">**Lener-br: A dataset for named entity recognition in brazilian legal text.**</span>

   *Pedro Henrique Luz de Araujo, Te¨®filo E. de Campos, Renato R. R. de Oliveira, Matheus Stauffer, Samuel Couto, Paulo Bermejo.* PROPOR 2018. [[pdf](https://link.springer.com/chapter/10.1007/978-3-319-99722-3_32)]

10. <span id = "XiaoCAIL2018">**CAIL2018: A Large-Scale Legal Dataset for Judgment Prediction**.</span>

   *Chaojun Xiao, Haoxi Zhong, Zhipeng Guo, Cunchao Tu, Zhiyuan Liu, Maosong Sun, Yansong Feng, Xianpei Han, Zhen Hu, Heng Wang, Jianfeng Xu*. [[pdf](<https://arxiv.org/pdf/1807.02478.pdf>)]

11. <span id = "Manor">**Plain English summarization of contracts.**</span>

    *Laura Manor, Junyi Jessy Li.* Natural Legal Language Processing Workshop 2019. [[pdf](https://doi.org/10.18653/v1/W19-2201)]

12. <span id = "ChalkidisNeural">**Neural Legal Judgment Prediction in English**.</span>

    *Ilias Chalkidis, Ion Androutsopoulos, Nikolaos Aletras*. ACL 2019. [[pdf](<https://arxiv.org/pdf/1906.02059.pdf>)]

13. <span id = "ChalkidisLargeScale">**Large-Scale Multi-Label Text Classification on EU Legislation**.</span>

    *Ilias Chalkidis, Manos Fergadiotis, Prodromos Malakasiotis, Ion Androutsopoulos*. ACL 2019. [[pdf](<https://arxiv.org/pdf/1906.02192.pdf>)]

14. <span id = "Duan">**Cjrc: A reliable human-annotated benchmark dataset for chinese judicial reading comprehension.**</span>

    *Xingyi Duan, Baoxin Wang, Ziyue Wang, Wentao Ma, Yiming Cui, Dayong Wu, Shijin Wang, Ting Liu, Tianxiang Huo, Zhen Hu.* CCL 2019. [[pdf](https://arxiv.org/pdf/1912.09156.pdf)]

15. <span id = "XiaoCAIL2019">**Cail2019-scm: A dataset of similar case matching in legal domain.**</span>

    *Chaojun Xiao, Haoxi Zhong, Zhipeng Guo, Cunchao Tu, Zhiyuan Liu, Maosong Sun, Tianyang Zhang, Xianpei Han, Heng Wang, Jianfeng Xu.* [[pdf](https://arxiv.org/pdf/1911.08962)]

16. <span id = "ZhongJECQA">**Jec-qa: A legal-domain question answering dataset.**</span>

    *Haoxi Zhong, Chaojun Xiao, Cunchao Tu, Tianyang Zhang, Zhiyuan Liu, Maosong Sun.* AAAI 2020. [[pdf](https://arxiv.org/pdf/1911.12011)]

    

## Legal Judgment Prediction

1. **Learning to predict charges for criminal cases with legal basis**.

   *Bingfeng Luo, Yansong Feng, Jianbo Xu, Xiang Zhang, Dongyan Zhao*. EMNLP 2017. [[pdf](<https://arxiv.org/pdf/1707.09168.pdf>)]

2. **Few-shot charge prediction with discriminative legal attributes**.

   *Zikun Hu, Xiang Li, Cunchao Tu, Zhiyuan Liu, Maosong Sun*. COLING 2018. [[pdf]((https://www.aclweb.org/anthology/papers/C/C18/C18-1041/))]

3. **Legal Judgment Prediction via Topological Learning**.

   *Haoxi Zhong, Zhipeng Guo, Cunchao Tu, Chaojun Xiao, Zhiyuan Liu, Maosong Sun*. EMNLP 2018. [[pdf](<https://www.aclweb.org/anthology/D18-1390>)]

4. **Interpretable Rationale Augmented Charge Prediction System**.

   *Xin Jiang, Hai Ye, Zhunchen Luo, Wenhan Chao, Wenjia Ma*. COLING 2018. [[pdf](<https://www.aclweb.org/anthology/C18-2032>)]

5. **Legal Article-Aware End-To-End Memory Network for Charge Prediction**.

   *Yatian Shen, Jun Sun, Xiaopeng Li, Lei Zhang, Yan Li, Xiajiong Shen*. CSAE 2018. [[pdf](https://dl.acm.org/citation.cfm?id=3278068)]

6. **SECaps: A Sequence Enhanced Capsule Model for Charge Prediction**.

   *Congqing He, Li Peng, Yuquan Le, Jiawei He, and Xiangyu Zhu*. [[pdf](<https://arxiv.org/pdf/1810.04465.pdf>)]

7. **Automatic Judgment Prediction via Legal Reading Comprehension**.

   *Shangbang Long, Cunchao Tu, Zhiyuan Liu, Maosong Sun*. [[pdf](<https://arxiv.org/pdf/1809.06537.pdf>)]

8. **A Markov Logic Networks Based Method to Predict Judicial Decisions of Divorce Cases**.

   *Jiajing Li, Guoying Zhang, Hongfei Yan, Longxue Yu, Tao Meng*. IEEE SmartCloud. [[pdf](<https://ieeexplore.ieee.org/abstract/document/8513727>)]

9. **Legal Judgment Prediction via Multi-Perspective Bi-Feedback Network**.

   *Wenmian Yang, Weijia Jia, Xiaojie Zhou, Yutao Luo*. IJCAI 2019. [[pdf](<https://arxiv.org/pdf/1905.03969.pdf>)]

10. **Law text classification using semi-supervised convolutional neural networks**.

    *Penghua Li, Fen Zhao, Yuanyuan Li, Ziqin Zhu*. CCDC. [[pdf](<https://ieeexplore.ieee.org/abstract/document/8407150>)]

11. **Exploring the Use of Text Classification in the Legal Domain**.

    *Octavia-Maria Sulea, Marcos Zampieri, Shervin Malmasi, Mihaela Vela, Liviu P. Dinu, Josef van Genabith*.  [[pdf]([http://ceur-ws.org/Vol-2143/paper5.pdf](http://ceur-ws.org/Vol-2143/paper5.pdf))]

12. **Predicting the Law Area and Decisions of French Supreme Court Cases**.

    *Octavia-Maria Sulea, Marcos Zampieri, Mihaela Vela, Josef van Genabith*. RANLP 2017. [[pdf](https://www.acl-bg.org/proceedings/2017/RANLP%202017/pdf/RANLP092.pdf)]

13. **JUMPER: Learning When to Make Classification Decisions in Reading**.

    *Xianggen Liu, Lili Mou, Haotian Cui, Zhengdong Lu, Sen Song*. IJCAL 2018. [[pdf](https://www.ijcai.org/proceedings/2018/0589.pdf)]

14. **Generalize Symbolic Knowledge With Neural Rule Engine**.

    *Shen Li, Hengru Xu, Zhengdong Lu*. [[pdf](https://arxiv.org/pdf/1808.10326.pdf)]
    
15. **An External Knowledge Enhanced Multi-label Charge Prediction Approach with Label Number Learning**.

    *Duan Wei, Li Lin*. [[pdf](https://arxiv.org/pdf/1907.02205.pdf)]

16. **Machine learning for explaining and ranking the most influential matters of law**.

    *Max R. S. Marques, Tommaso Bianco, Maxime Roodnejad, Thomas Baduel, Claude Berrou*. ICAIL 2019. [[pdf](https://dl.acm.org/citation.cfm?id=3326734)]

17. **Charge-Based Prison Term Prediction with Deep Gating Network**.
    *Huajie Chen, Deng Cai, Wei Dai, Zehui Dai, Yadong Ding*. EMNLP-IJCNLP 2019. [[pdf](https://www.aclweb.org/anthology/D19-1667.pdf)]
    
18. **Iteratively Questioning and Answering for Interpretable Legal Judgment Prediction**.

    *Haoxi Zhong, Yuzhong Wang, Cunchao Tu, Tianyang Zhang, Zhiyuan Liu, Maosong Sun*. AAAI 2020. [[pdf](https://www.aaai.org/Papers/AAAI/2020GB/AAAI-ZhongH.7101.pdf)] 
    
19. **Distinguish Confusing Law Articles for Legal Judgment Prediction**.

    *Nuo Xu, Pinghui Wang, Long Chen, Li Pan, Xiaoyan Wang, Junzhou Zhao*. ACL 2020. [[pdf](https://arxiv.org/pdf/2004.02557.pdf)]



## Court Views Generation

1. **Interpretable Charge Predictions for Criminal Cases: Learning to Generate Court Views from Fact Descriptions**.

   *Hai Ye, Xin Jiang, Zhunchen Luo, Wenhan Chao*. NAACL-HLT 2018. [[pdf](<https://www.aclweb.org/anthology/N18-1168>)]

2. **De-Biased Court’s View Generation with Causality**.

   *Yiquan Wu, Kun Kuang, Yating Zhang, Xiaozhong Liu, Changlong Sun, Jun Xiao1, Yueting Zhuang, Luo Si, Fei Wu*. EMNLP 2020. [[pdf](<https://www.aclweb.org/anthology/2020.emnlp-main.56.pdf>)]

## Information Extraction

#### Named Entity Recognition

1. **Named entity recognition in the legal domain for ontology population.**

   *Mirian Bruckschen, Caio Northfleet, Paulo Bridi, Roger Granada, Renata Vieira, Prasad Rao, Tomas Sander.* 2010. [[pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.232.9181&rep=rep1&type=pdf#page=21)] 

2. **Legal NERC with ontologies, Wikipedia and curriculum learning.**

   *Cristian Cardellino, Milagro Teruel, Laura Alonso Alemany, Serena Villata.* EACL 2017. [[pdf](https://www.aclweb.org/anthology/E17-2041.pdf)]

3. **A Low-cost, High-coverage Legal Named Entity Recognizer, Classifier and Linker.**

   *Cristian Cardellino, Milagro Teruel, Laura Alonso Alemany, Serena Villata.* 2017. [[pdf](https://hal.archives-ouvertes.fr/hal-01541446/file/main.pdf)]

4. **Legal Entity Extraction with NER Systems.**

   *Ines Badji.* 2018. [[pdf](https://pdfs.semanticscholar.org/a842/960783d6b734eeb18ec6173218d7d34d6bbb.pdf)]

5. **Deep Learning for Named-Entity Linking with Transfer Learning for Legal Documents.**

   *Ahmed  Elnaggar, Robin  Otto, Florian  Matthes.* AICCC 2018. [[pdf](https://dl.acm.org/doi/abs/10.1145/3299819.3299846)]

6. **Neural Entity Reasoner for Global Consistency in Named Entity Recognition.**

   *Xiaoxiao Yin, Daqi Zheng, Zhengdong Lu, Ruifang Liu.* 2018. [[pdf](https://arxiv.org/pdf/1810.00347)]

7. **Fine-Grained Named Entity Recognition in Legal Documents.**

   *Elena Leitner, Georg Rehm, Julian Moreno-Schneider.* SEMANTiCS 2019. [[pdf](https://link.springer.com/chapter/10.1007/978-3-030-33220-4_20)]



#### Event Extraction

1. **Event extraction and temporal reasoning in legal documents.**

   *Frank Schilder.* 2005. [[pdf](https://dl.acm.org/doi/10.5555/1783514.1783519)]

2. **Event extraction for legal case building and reasoning.**

   *Nikolaos Lagos, Frederique Segond, Stefania Castellani, Jacki O¡¯Neill.* IIP 2010. [[pdf](https://link.springer.com/chapter/10.1007/978-3-642-16327-2_14)]

3. **Event Identification as a Decision Process with Non-linear Representation of Text.**

   *YukunYan, Daqi Zheng, Zhengdong Lu, Sen Song*. [[pdf](https://arxiv.org/pdf/1710.00969.pdf)]

4. **Apply event extraction techniques to the judicial field.**

   *Chuanyi Li, Yu Sheng, Jidong Ge, Bin Luo.* 2019. [[pdf](https://dl.acm.org/doi/abs/10.1145/3341162.3345608)]



#### Others

1. **Semantic mark-up of Italian legal texts through NLPbased techniques. **

   *Roberto Bartolini, Alessandro Lenci, Simonetta Montemagni, Vito Pirrelli, Claudia Soria.* LREC 2004. [[pdf](http://www.lrec-conf.org/proceedings/lrec2004/pdf/709.pdf)]

2. **Legal aspects of text mining.**

   *Maarten Truyens and Patrick Van Eecke.* LREC 2014. [[pdf](https://repository.uantwerpen.be/docman/irua/3dadb2/127790.pdf)]

3. **Litigation Analytics: Case Outcomes Extracted from US Federal Court Dockets**.

   *Thomas Vacek, Ronald Teo, Dezhao Song, Conner Cowling, Frank Schilder, Timothy Nugent*. NAACL Workshop 2019. [[pdf](https://www.aclweb.org/anthology/W19-2206)]

4. **A Sequence Approach to Case Outcome Detection**.

   *Tom Vacek, Frank Schilder*. ICAIL 2017. [[pdf](https://dl.acm.org/citation.cfm?doid=3086512.3086534)]

5. **Extracting the Gist of Chinese Judgments of the Supreme Court.**

   *Chaolin Liu, Kuanchun Chen.* ICAIL 2019. [[pdf](https://dl.acm.org/doi/abs/10.1145/3322640.3326715)]



## Information Retrieval

1. **Analyzing the extraction of relevant legal judgments using paragraph-level and citation information**.

   *Raghav K, Reddy P K, Reddy V B*. ECAI 2016. [[pdf](http://www.ecai2016.org/content/uploads/2016/08/W2-ai4j-2016.pdf#page=34)]

2. **On the concept of relevance in legal information retrieval**.

   *Marc Van Opijnen, Cristiana Santos*. ECAI 2016. [[pdf](http://www.ecai2016.org/content/uploads/2016/08/W2-ai4j-2016.pdf#page=82)]

3. **Building legal case retrieval systems with lexical matching and summarization using a pretrained phrase scoring model**.

   *Vu Tran, Minh Le Nguyen, Ken Satoh*. [[pdf](https://dl.acm.org/doi/abs/10.1145/3322640.3326740)]

4. **Legal document retrieval using document vector embeddings and deep learning**.

   *Keet Sugathadasa, Buddhi Ayesha, Nisansa de Silva, Amal Shehan Perera, Vindula Jayawardana, Dimuthu Lakmal, Madhavi Perera*. [[pdf](https://arxiv.org/pdf/1805.10685.pdf)]



## Legal Text Summarization

1. **Automatic summarisation of legal documents.**

   *Claire Grover, Ben Hachey, Lan Hugson, Chris Korycinski.* ICAIL 2003. [[pdf](https://dl.acm.org/doi/abs/10.1145/1047788.1047839)]

2. **Summarising legal texts: Sentential tense and argumentative roles.**

   *Claire Grover, Ben Hachey, Chris Korycinski.* NAACL 2003. [[pdf](https://www.aclweb.org/anthology/W03-0505.pdf)]

3. **A Rhetorical Status Classifier for Legal Text Summarisation.**

   *Ben Hachey, Claire Grover.* ACL Workshop 2004. [[pdf](https://www.aclweb.org/anthology/W04-1007.pdf)]

4. **Sentence extraction for legal text summarisation.**

   *Ben Hachey, Claire Grover.* IJCAI 2005. [[pdf](http://benhachey.info/pubs/poster450.pdf)]

5. **Legal Document Summarization using Latent Dirichlet Allocation.**

   *Ravi Kumar V, K. Raghuveer.* IJCST 2012. [[pdf](https://pdfs.semanticscholar.org/40de/6ed958c78d17a687851105fc6e95f80b05f9.pdf)]

6. **Text summarization from legal documents: a survey**.

   *Ambedkar Kanapala, Sukomal PalRajendra Pamula*. Artificial Intelligence Review 2019. [[pdf](https://doi.org/10.1007/s10462-017-9566-2)]

7. **A Comparative Study of Summarization Algorithms Applied to Legal Case Judgments**.

   *Paheli Bhattacharya, Kaustubh Hiware, Subham Rajgaria, Nilay Pochhi, Kripabandhu Ghosh, Saptarshi Ghosh*. ECIR 2019. [[pdf](https://link.springer.com/chapter/10.1007/978-3-030-15712-8_27)]

8. **A Novel Approach of Augmenting Training Data for Legal Text Segmentation by Leveraging Domain Knowledge.**

   *Rupali Sunil Wagh, Deepa Anand.* Technologies and Applications 2020. [[pdf](https://link.springer.com/chapter/10.1007/978-981-13-6095-4_4)]



## Legal Question Answering

1. **Lexical-Morphological Modeling for Legal Text Analysis**.

   *Danilo S. Carvalho, Minh-Tien Nguyen, Chien-Xuan Tran, Minh-Le Nguyen*. COLIEE 2017. [[pdf](<https://link.springer.com/chapter/10.1007/978-3-319-50953-2_21>)]

2. **Legal Question Answering using Ranking SVM and Deep Convolutional Neural Network**.

   *Phong-Khac Do, Huy-Tien Nguyen, Chien-Xuan Tran, Minh-Tien Nguyen, Minh-Le Nguyen*. COLIEE 2017. [[pdf](<https://arxiv.org/pdf/1703.05320.pdf>)]

3. **Multi-Task CNN for Classification of Chinese Legal Questions**.

   *Guangyi Xiao,  Jiqian Mo, Even Chow, Hao Chen,  Jingzhi Guo, Zhiguo Gong*. ICEBE 2017. [[pdf](https://ieeexplore.ieee.org/abstract/document/8119134)]

4. **Chinese Questions Classification in the Law Domain**.

   *Guangyi Xiao, Even Chow, Hao Chen, Jiqian Mo, Jingzhi Guo, Zhiguo Gong*. ICEBE 2017. [[pdf](https://ieeexplore.ieee.org/abstract/document/8119153)]

5. **Answering Legal Questions by Learning Neural Attentive Text Representation**
   
   *Phi Manh Kien, Ha-Thanh Nguyen, Ngo Xuan Bach, Vu Tran, Minh Le Nguyen, Tu Minh Phuong*. ACL 2020. [[pdf](https://www.aclweb.org/anthology/2020.coling-main.86/)]



## Semantical Parsing

1. **Object-oriented Neural Programming (OONP) for Document Understanding**.

   *Zhengdong Lu, Xianggen Liu, Haotian Cui, Yukun Yan, Daqi Zheng*.  ACL 2018. [[pdf](https://www.aclweb.org/anthology/P18-1253)]
