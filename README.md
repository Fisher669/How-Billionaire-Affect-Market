# 📈 How-Billionaire-Affect-Market

Some billionaires aligned with political congress members influence the stock market — so why not use NLP to technically analyze this phenomenon?

---

## 🏆 Competition Info

- **Competition**: 2025 (11th) National Undergraduate Statistical Modeling Competition  
- **University**: Southwestern University of Finance and Economics  
- **Paper Title**: *Construction of a Financial Opinion Leader Influence Evaluation Model Based on Deep Semantic Understanding — An Analysis of 270,000 Statements by Forbes Global Billionaires*  
- **Team Members**: Jiang Minrui, Li Yu, Cheng Qihang  
- **Submission ID**: xxx

---

## 📁 Project Structure

```txt
.
├── code
│   ├── DataEDA.ipynb             # Exploratory Data Analysis
│   ├── 0.Preprocess.ipynb        # Data Preprocessing
│   ├── 1.StageModel1.ipynb       # First Stage Modeling
│   ├── 2.StageModel2.ipynb       # Second Stage Modeling
├── data
│   ├── USA index/                # US market index data
│   ├── Custom_Test_Data/
│   │   ├── AlikoDangote/
│   │   ├── BillGates/
│   │   ├── elonmusk/
│   │   ├── ericschmidt/
│   │   ├── ...
│   │   └── profile_pictures/     # Avatar collection
│   └── Training_Data/            # Kaggle sentiment training data
```
---

## ⚙️ Runtime Environment

| Library       | Version               |
|---------------|------------------------|
| Python        | 3.9.19 (May 6, 2024)   |
| numpy         | 1.25.0                 |
| pandas        | 2.2.3                  |
| nltk          | 3.9.1                  |
| re            | 2.2.1                  |
| scikit-learn  | 1.5.2                  |
| torch         | 1.9.1+cpu              |
| torchtext     | 0.10.1                 |

> 💡 All code was developed and executed using **Jupyter Notebook**.

---

## 🧠 Data Description

### 📚 Training Data
- **Source**: [Kaggle - Tweet Sentiment Extraction](https://www.kaggle.com/competitions/tweet-sentiment-extraction/)
- **Details**: Contains tweet texts labeled with sentiment classes.

### 🧪 Test Data
- **Source**: Crawled from **X.com** (formerly Twitter)
- **Includes**: Billionaire profiles, tweet content, and avatar images

### 📉 Stock Market Data
- **Source**: WIND Terminal
- **Details**: U.S. stock index with **unadjusted closing prices**

---

## 🚦 Execution Order

1. `DataEDA.ipynb` – Perform exploratory data analysis  
2. `0.Preprocess.ipynb` – Clean and structure the dataset  
3. `1.StageModel1.ipynb` – Train the first stage of the model  
4. `2.StageModel2.ipynb` – Extend and fine-tune predictions  

> 🎨 Visualizations are embedded throughout each notebook. No separate chart script is used.

## ⭐ Cite or Star Our Work

If you find this work helpful, please consider citing us or giving us a ⭐ on GitHub!

👉 [Star on GitHub](https://github.com/Fisher669/How-Billionaire-Affect-Market/)

---

## 🙏 Thanks

Special thanks to **Kaggle** for providing the sentiment dataset and for fostering such a supportive community for beginners.

## Citation for previous Work

[1] 洪永淼, 汪寿阳. 大数据如何改变经济学研究范式?[J]. 管理世界, 2021, 37(10): 40–55.
[2] 姜富伟, 刘雨旻, 孟令超. 大语言模型、文本情绪与金融市场[J]. 管理世界, 2024, 40(8): 42–64.
[3] 林建浩, 孙乐轩. 大语言模型与经济金融文本分析: 基本原理、应用场景与研究展望[J]. 计量经济学报, 2025, 5(1): 1–34.
[4] 沈艳, 陈赟, 黄卓. 文本大数据分析在经济学和金融学中的应用: 一个文献综述[J]. 经济学(季刊), 2019, 18(4): 1153–1186.
[5] 姚加权, 张锟澎, 罗平. 金融学文本大数据挖掘方法与研究进展[J]. 经济学动态, 2020(4): 143–158.
[6] BAKER S R, BLOOM N, DAVIS S J. Measuring economic policy uncertainty[J]. The Quarterly Journal of Economics, 2016, 131(4): 1593–1636.
[7] BAMLER R, MANDT S. Dynamic word embeddings[J/OL]. arXiv preprint arXiv:1702.08359, 2017 [2025-04-20]. https://arxiv.org/abs/1702.08359.
[8] BELLONI A, CHERNOZHUKOV V. Least squares after model selection in high-dimensional sparse models[J]. Bernoulli, 2013, 19(2): 521–547. DOI:10.3150/11-BEJ410.
[9] CHEN T, GUESTRIN C. XGBoost: A scalable tree boosting system[C]//Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining. New York: ACM, 2016: 785–794. DOI:10.1145/2939672.2939785.
[10] DADA L. Elon Musk tweets 2010 to 2025 (March)[DB/OL]. Kaggle, 2025. DOI:10.34740/KAGGLE/DSV/11241059.
[11] DEVLIN J, CHANG M W, LEE K, et al. BERT: Pre-training of deep bidirectional transformers for language understanding[J/OL]. arXiv preprint arXiv:1810.04805, 2018 [2025-04-20]. https://arxiv.org/abs/1810.04805.
[12] EISFELDT A L, SCHUBERT G. AI and finance[R]. Cambridge, MA: National Bureau of Economic Research, 2024: w33076.
[13] FLASIŃSKI M. History of artificial intelligence[M]//Introduction to Artificial Intelligence. Cham: Springer, 2016: 3–13. DOI:10.1007/978-3-319-40022-8_1.
[14] HOERL A E, KENNARD R W. Ridge regression: Biased estimation for nonorthogonal problems[J]. Technometrics, 1970, 12(1): 55–67. DOI:10.2307/1267351.
[15] JI Z, LEE N, FRIESKE R, et al. Survey of hallucination in natural language generation[J]. ACM Computing Surveys, 2023, 55(12): 1–38.
[16] KIM Y. Convolutional neural networks for sentence classification[C]//Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP). Doha, Qatar: Association for Computational Linguistics, 2014: 1746–1751. DOI:10.3115/v1/D14-1181.
[17] KINGMA D P, BA J. Adam: A method for stochastic optimization[J/OL]. arXiv preprint arXiv:1412.6980, 2017 [2025-04-20]. https://arxiv.org/abs/1412.6980.
[18] LECUN Y, BOTTOU L, BENGIO Y, et al. Gradient-based learning applied to document recognition[J]. Proceedings of the IEEE, 1998, 86(11): 2278–2324. DOI:10.1109/5.726791.
[19] PENNINGTON J, SOCHER R, MANNING C D. GloVe: Global vectors for word representation[C]//Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP). Doha, Qatar: Association for Computational Linguistics, 2014: 1532–1543. DOI:10.3115/v1/D14-1162.
[20] RADFORD A, NARASIMHAN K, SALIMANS T, et al. Improving language understanding by generative pre-training[R/OL]. 2018 [2024-07-25]. https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf.
[21] ROZEMBERCZKI B, WATSON L, BAYER P, et al. The Shapley value in machine learning[J/OL]. arXiv preprint arXiv:2202.05594, 2022 [2025-04-20]. https://arxiv.org/abs/2202.05594.
[22] WU L, HOI S C H, YU N. Semantics-preserving bag-of-words models and applications[J]. IEEE Transactions on Image Processing, 2010, 19(7): 1908–1920. DOI:10.1109/TIP.2010.2045169.
[23] YAO J Y, NING K P, LIU Z H, et al. LLM lies: Hallucinations are not bugs, but features as adversarial examples[J/OL]. arXiv preprint arXiv:2310.01469, 2023 [2025-04-20]. https://arxiv.org/abs/2310.01469.

