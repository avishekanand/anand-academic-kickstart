---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Tutorial: Explainable Information Retrieval"
event: SIGIR 2023
event_url: "https://sigir.org/sigir2023/"
location: "Taipei(SIGIR)"
address:
  street:
  city:
  region:
  postcode:
  country:
summary: "Explainable Information Retrieval"
abstract: "This tutorial presents explainable information retrieval (ExIR), an emerging area focused on fostering responsible and trustworthy deployment of machine learning systems in the context of information retrieval. As the field has rapidly evolved in the past 4-5 years, numerous approaches have been proposed that focus on different access modes, stakeholders, and model development stages. This tutorial aims to introduce IR-centric notions, classification, and evaluation styles in ExIR, while focusing on IR-specific tasks such as ranking, text classification, and learning-to-rank systems. We will delve into method families and their adaptations to IR, extensively covering post-hoc methods, axiomatic and probing approaches, and recent advances in interpretability-by-design approaches. We will also discuss ExIR applications for different stakeholders, such as researchers, practitioners, and end-users, in contexts like web search, patent and legal search, and high-stakes decision-making tasks. To facilitate practical understanding, we will provide a hands-on session on applying ExIR methods, reducing the entry barrier for students, researchers, and practitioners alike.
"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2023-07-22T9:00:22+02:00
date_end: 2023-07-22T12:30:22+02:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-07-19T14:47:22+02:00

authors: [Rishiraj Saha Roy and Avishek Anand]
tags: []

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: "https://arxiv.org/pdf/2211.02405.pdf"

url_code:
url_pdf: "https://arxiv.org/pdf/2211.02405.pdf"
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
This half-day tutorial is divided into two parts of 90 minutes each -- In the first part we explore the notions of explainable IR, probing neural models and explainable-by-design approaches. In the second half, we delve deeper into axiomatic IR and its connection to interpretability and some of the popular posthoc approaches. 

<br>

## Contents

 1. **[Notions of Explainable IR](https://arxiv.org/pdf/2211.02405.pdf)** by [Avishek Anand](http://www.avishekanand.com). 
 2. **[Intrinsic Methods for ExIR](https://arxiv.org/pdf/2211.02405.pdf)** by [Avishek Anand](http://www.avishekanand.com). 
 3. **[Probing transformer models](https://arxiv.org/pdf/2211.02405.pdf)** by [Avishek Anand](http://www.avishekanand.com). 

<br>    

4. **[Posthoc approaches in ExIR](https://arxiv.org/pdf/2211.02405.pdf)** by [Procheta Sen](https://procheta.github.io/sprocheta/). 
5. **[Axiomatic IR for Interpretability](https://arxiv.org/pdf/2211.02405.pdf)** by [Sourav Saha](https://souravsaha.github.io). 
6. **[Outlook and Conclusion](https://arxiv.org/pdf/2211.02405.pdf)** by [Avishek Anand](https://www.avishekanand.com). 


<br>


---
## References

<br>

[1] Julius Adebayo, Justin Gilmer, Michael Muelly, Ian J. Goodfellow, Moritz Hardt, and Been Kim. 2018. Sanity Checks for Saliency Maps. In Advances in Neural Information Processing Systems 31: Annual Conference on Neural Information Processing Systems 2018, NeurIPS 2018, December 3-8, 2018, Montréal, Canada, Samy Bengio, Hanna M. Wallach, Hugo Larochelle, Kristen Grauman, Nicolò Cesa-Bianchi, and Roman Garnett (Eds.). 9525–9536. https://proceedings. neurips.cc/paper/2018/hash/294a8ed24b1ad22ec2e7efea049b8737- Abstract.html

[2] Julius Adebayo, Michael Muelly, Harold Abelson, and Been Kim. 2022. Post hoc Explanations may be Ineffective for Detecting Unknown Spurious Correlation. In The Tenth International Conference on Learning Representations, ICLR 2022,VirtualEvent,April25-29,2022.OpenReview.net. https://openreview.net/forum?id=xNOVfCCvDpM

[3] Gianni Amati and Cornelis Joost Van Rijsbergen. 2002. Probabilistic Models of Information Retrieval Based on Measuring the Divergence from Randomness. ACM Trans. Inf. Syst. 20, 4 (2002), 357–389. https://doi.org/10.1145/ 582415.582416

[4] Sebastian Bach, Alexander Binder, Grégoire Montavon, Frederick Klauschen, Klaus-Robert Müller, and Wojciech Samek. 2015. On pixel-wise explanations for non-linear classifier decisions by layer-wise relevance propagation. PloS one 10, 7 (2015), e0130140.

[5] Seojin Bang, Pengtao Xie, Heewook Lee, Wei Wu, and Eric Xing. 2021. Explaining A Black-box By Using A Deep Variational Information Bottleneck Approach. Proceedings of the AAAI Conference on Artificial Intelligence 35, 13 (2021),11396–11404. https://doi.org/10.1609/aaai.v35i13.17358
[6] Jasmijn Bastings, Wilker Aziz, and Ivan Titov. 2019. Interpretable Neural Predictions with Differentiable Binary Variables. In Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics. Association for ComputationalLinguistics,Florence,Italy,2963–2977. https://doi.org/10.18653/v1/P19-1284
[7] Jasmijn Bastings, Sebastian Ebert, Polina Zablotskaia, Anders Sandholm, and Katja Filippova. 2021. "Will You Find These Shortcuts?" A Protocol for Evaluating the Faithfulness of Input Salience Methods for Text Classification. ArXiv preprint abs/2111.07367 (2021). https://arxiv.org/abs/2111.07367
[8] JasmijnBastingsandKatjaFilippova.2020.Theelephantintheinterpretabilityroom:Whyuseattentionasexplanation when we have saliency methods?. In Proceedings of the Third BlackboxNLP Workshop on Analyzing and Interpreting NeuralNetworksforNLP.AssociationforComputationalLinguistics,Online,149–155. https://doi.org/10.18653/v1/ 2020.blackboxnlp-1.14
[9] Yonatan Belinkov. 2022. Probing Classifiers: Promises, Shortcomings, and Advances. Comput. Linguistics 48, 1 (2022), 207–219. https://doi.org/10.1162/coli_a_00422
[10] Adam Berger and John Lafferty. 1999. Information retrieval as statistical translation. In Proceedings of the 22nd annual international ACM SIGIR conference on Research and development in information retrieval. 222–229.
[11] Umang Bhatt, Alice Xiang, Shubham Sharma, Adrian Weller, Ankur Taly, Yunhan Jia, Joydeep Ghosh, Ruchir Puri, José M. F. Moura, and Peter Eckersley. 2020. Explainable Machine Learning in Deployment. In Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency (Barcelona, Spain) (FAT* ’20). Association for Computing Machinery, New York, NY, USA, 648–657. https://doi.org/10.1145/3351095.3375624
[12] Adrien Bibal, Rémi Cardon, David Alfter, Rodrigo Wilkens, Xiaoou Wang, Thomas François, and Patrick Watrin. 2022. Is Attention Explanation? An Introduction to the Debate. In Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). Association for Computational Linguistics, Dublin, Ireland, 3889–3900. https://doi.org/10.18653/v1/2022.acl-long.269
[13] Amin Bigdeli, Negar Arabzadeh, Shirin Seyedsalehi, Morteza Zihayat, and Ebrahim Bagheri. 2022. Gender Fairness in Information Retrieval Systems. In SIGIR ’22: The 45th International ACM SIGIR Conference on Research and Development inInformationRetrieval,Madrid,Spain,July11-15,2022.ACM,3436–3439. https://doi.org/10.1145/3477495.3532680
[14] Alexander Bondarenko, Maik Fröbe, Jan Heinrich Reimer, Benno Stein, Michael Völske, and Matthias Hagen. 2022. Axiomatic Retrieval Experimentation with ir_axioms. In SIGIR ’22: The 45th International ACM SIGIR Conference on Research and Development in Information Retrieval, Madrid, Spain, July 11 - 15, 2022. ACM, 3131–3140. https: //doi.org/10.1145/3477495.3531743
[15] Leonid Boytsov and Zico Kolter.2021.Exploringclassicandneurallexicaltranslationmodelsforinformationretrieval: Interpretability, effectiveness, and efficiency benefits. In European Conference on Information Retrieval. Springer, 63–78.

[16] Peter Bruza and Theo W. C. Huibers. 1994. Investigating Aboutness Axioms using Information Fields. In Proceedings of SIGIR Forum 1994. 112–121.

[17] Jie Cai, Zhengzhou Zhu, Ping Nie, and Qian Liu. 2020. A Pairwise Probe for Understanding BERT Fine-Tuning on Machine Reading Comprehension. In Proceedings of the 43rd International ACM SIGIR conference on research and development in Information Retrieval, SIGIR 2020, Virtual Event, China, July 25-30, 2020, Jimmy Huang, Yi Chang, Xueqi Cheng,JaapKamps,VanessaMurdock,Ji-RongWen,andYiqunLiu(Eds.).ACM,1665–1668. https://doi.org/10.1145/ 3397271.3401195

[18] Jamie Callan, Mark Hoy, Changkuk Yoo, and Le Zhao. 2009. Clueweb09 data set. http://lemurproject.org/clueweb09/

[19] Arthur Câmara and Claudia Hauff. 2020. Diagnosing BERT with Retrieval Heuristics. In Proceedings of ECIR 2020,
Vol. 12035. Springer, 605–618.

[20] Oana-Maria Camburu, Tim Rocktäschel, Thomas Lukasiewicz, and Phil Blunsom. 2018. e-SNLI: Natural Language
Inference with Natural Language Explanations. In Advances in Neural Information Processing Systems 31: Annual Conference on Neural Information Processing Systems 2018, NeurIPS 2018, December 3-8, 2018, Montréal, Canada. 9560–9572. https://proceedings.neurips.cc/paper/2018/hash/4c7a167bb329bd92580a99ce422d6fa6-Abstract.html

[21] MarkJamesCarman,FabioCrestani,MorganHarvey,andMarkBaillie.2010.Towardsquerylogbasedpersonalization using topic models. In Proceedings of the 19th ACM Conference on Information and Knowledge Management, CIKM 2010,Toronto,Ontario,Canada,October26-30,2010.ACM,1849–1852. https://doi.org/10.1145/1871437.1871745