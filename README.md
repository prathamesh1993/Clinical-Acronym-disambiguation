# Clinical-Acronym-disambiguation

# Literature review and explanation
https://medium.com/@pprabhudesai09/clinical-abbreviations-and-acronyms-9ef3223ebba2

[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/prathamesh1993/Clinical-Acronym-disambiguation/master)

(Click on the 'launch binder' button ^^^)


This repository contains Jupyter notebooks, trained word embedding files and datasets of medical acronyms (clinical and biomedical). It is an unconventional use case of GitHub, through [binder](https://github.com/jupyterhub/binderhub), for collaboratively editing/running different algorithms on Acronym data.
Currently, the project is under development and uses [GitHub LFS](https://github.com/git-lfs/git-lfs/wiki/Tutorial) to store the trained word embeddings model developed by [Language Technology Lab](https://github.com/cambridgeltl/BioNLP-2016). Due to bandwidth limitations, the best way to use this repo is by downloading files. Another option is running it with [repo2docker](https://github.com/jupyter/repo2docker).

#Acronyms from Clinical Notes (75- manually annotated)
Clinical Abbreviation Sense Inventory 
Moon, Sungrim; Pakhomov, Serguei; Melton, Genevieve (2012)
https://conservancy.umn.edu/handle/11299//137703

# Acronym extracted from PubMed abstracts
ADAM: Another Database of Abbreviations in MEDLINE
Zhou W, Torvik VI, Smalheiser NR. ADAM: another database of abbreviations in MEDLINE. Bioinformatics 2006; 22(22): 2813-2818.
http://arrowsmith.psych.uic.edu/arrowsmith_uic/adam.html

# Word vectors
The scripts, code, and vectors for the ACL BioNLP 2016 workshop paper:
Chiu et al. How to Train good Word Embeddings for Biomedical NLP
https://drive.google.com/open?id=0BzMCqpcgEJgiUWs0ZnU0NlFTam8

# Jupyter Notebooks
They are based on trained word embeddings provided in the link above. Billy Chiu et al. trained the model after analyzing results from different combinations of parameters like the size of biomedical literature dataset, hyperparameters, and architecture. I implemented their model on clinical note data and PubMed data to compare the results and also built an interpretation module to derive a reasoning for those predictions. 

# Articles
These are the articles on word sense disambiguation and clinical acronyms that I came across during my work.

[Pakhomov, S., Pedersen, T., & Chute, C. G. (2005). Abbreviation and acronym disambiguation in clinical discourse. In AMIA Annual Symposium Proceedings (Vol. 2005, p. 589). American Medical Informatics Association.
](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1560669/)

[Xu, H., Stetson, P. D., & Friedman, C. (2012). Combining corpus-derived sense profiles with estimated frequency information to disambiguate clinical abbreviations. In AMIA Annual Symposium Proceedings (Vol. 2012, p. 1004). American Medical Informatics Association.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3540457/)

[Xu, H., Wu, Y., Elhadad, N., Stetson, P. D., & Friedman, C. (2012). A new clustering method for detecting rare senses of abbreviations in clinical notes. Journal of biomedical informatics, 45(6), 1075-1083.](https://www.sciencedirect.com/science/article/pii/S1532046412000937)

[Wu, Y., Denny, J. C., Rosenbloom, S. T., Miller, R. A., Giuse, D. A., & Xu, H. (2012). A comparative study of current clinical natural language processing systems on handling abbreviations in discharge summaries. In AMIA annual symposium proceedings (Vol. 2012, p. 997). American Medical Informatics Association.](https://www.ncbi.nlm.nih.gov/pubmed/23304375)

[Moon, S., Berster, B. T., Xu, H., & Cohen, T. (2013). Word sense disambiguation of clinical abbreviations with hyperdimensional computing. In AMIA Annual Symposium Proceedings (Vol. 2013, p. 1007). American Medical Informatics Association.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3900125/)

[Moon, S., Pakhomov, S., Liu, N., Ryan, J. O., & Melton, G. B. (2013). A sense inventory for clinical abbreviations and acronyms created using clinical notes and medical dictionary resources. Journal of the American Medical Informatics Association, 21(2), 299-307.](http://doi.org/10.1136/amiajnl-2012-001506)

[Suominen, H., Salanterä, S., Velupillai, S., Chapman, W. W., Savova, G., Elhadad, N., ... & Leveling, J. (2013, September). Overview of the ShARe/CLEF eHealth evaluation lab 2013. In International Conference of the Cross-Language Evaluation Forum for European Languages (pp. 212-231). Springer, Berlin, Heidelberg.](http://doi.org/10.1186/s13326-016-0084-y)

[Wu, Y., Denny, J. C., Rosenbloom, S. T., Miller, R. A., Giuse, D. A., Song, M., & Xu, H. (2015). A preliminary study of clinical abbreviation disambiguation in real time. Applied clinical informatics, 6(02), 364-374.](http://doi.org/10.4338/ACI-2014-10-RA-0088)

[Xu, J., Zhang, Y., & Xu, H. (2015). Clinical abbreviation disambiguation using neural word embeddings. Proceedings of BioNLP 15, 171-176.](https://pdfs.semanticscholar.org/2133/d4d7410de5385b577698bd7dbccad41b5fdc.pdf)

[Wang, Y., Zheng, K., Xu, H., & Mei, Q. (2016). Clinical word sense disambiguation with interactive search and classification. In AMIA Annual Symposium Proceedings (Vol. 2016, p. 2062). American Medical Informatics Association.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5333264/)

[Tulkens, S., Šuster, S., & Daelemans, W. (2016). Using distributed representations to disambiguate biomedical and clinical concepts. arXiv preprint arXiv:1608.05605.](http://arxiv.org/abs/1608.05605)

[Chiu, B., Crichton, G., Korhonen, A., & Pyysalo, S. (2016). How to train good word embeddings for biomedical NLP. In Proceedings of the 15th Workshop on Biomedical Natural Language Processing (pp. 166-174).](http://aclweb.org/anthology/W/W16/W16-2922.pdf)

[Kreuzthaler, M., Oleynik, M., Avian, A., & Schulz, S. (2016). Unsupervised Abbreviation Detection in Clinical Narratives. In Proceedings of the Clinical Natural Language Processing Workshop (ClinicalNLP) (pp. 91-98).](http://www.aclweb.org/anthology/W16-4213)

[Mowery, D. L., South, B. R., Christensen, L., Leng, J., Peltonen, L. M., Salanterä, S., ... & Savova, G. (2016). Normalizing acronyms and abbreviations to aid patient understanding of clinical texts: ShARe/CLEF eHealth Challenge 2013, Task 2. Journal of biomedical semantics, 7(1), 43.](http://doi.org/10.1186/s13326-016-0084-y)

[Finley, G. P., Pakhomov, S. V., McEwan, R., & Melton, G. B. (2016). Towards comprehensive clinical abbreviation disambiguation using machine-labeled training data. In AMIA Annual Symposium Proceedings (Vol. 2016, p. 560). American Medical Informatics Association.](https://www.ncbi.nlm.nih.gov/pubmed/28269852)

[Wang, Y., Liu, S., Afzal, N., Rastegar-Mojarad, M., Wang, L., Shen, F., & Liu, H. (2018). A Comparison of Word Embeddings for the Biomedical Natural Language Processing. arXiv preprint arXiv:1802.00400.](http://arxiv.org/abs/1802.00400)

