# Clinical-Acronym-disambiguation

[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/prathamesh1993/Clinical-Acronym-disambiguation/master)

(Click on the 'launch binder' button ^^^)


This repository contains Jupyter notebooks, trained word embedding files and datasets of medical acronyms (clinical and biomedical). It is an unconventional use case of GitHub, through binder, for collaboratively editing/running different algorithms on Acronym data.
Currently, the project is under development and uses GitHub LFS to store the trained word embeddings model developed by Language Technology Lab. Due to bandwidth limitations, the best way to use this repo is by downloading files. Another option is running it with repo2docker

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

Pakhomov, S., Pedersen, T., & Chute, C. G. (2005). Abbreviation and Acronym Disambiguation in Clinical Discourse. AMIA Annual Symposium Proceedings, 2005, 589–593.

Xu, H., Stetson, P. D., & Friedman, C. (2012). Combining Corpus-derived Sense Profiles with Estimated Frequency Information to Disambiguate Clinical Abbreviations. AMIA Annual Symposium Proceedings, 2012, 1004–1013.

Xu H, Wu Y, Elhadad N, Stetson PD, Friedman C. A new clustering method for detecting rare senses of abbreviations in clinical notes. J Biomed Inform. 2012;45(6):1075-83.

Wu, Y., Denny, J. C., Rosenbloom, S. T., Miller, R. A., Giuse, D. A., & Xu, H. (2012). A comparative study of current clinical natural language processing systems on handling abbreviations in discharge summaries. AMIA Annual Symposium Proceedings, 2012, 997–1003.

Moon, S., Berster, B.-T., Xu, H., & Cohen, T. (2013). Word Sense Disambiguation of Clinical Abbreviations with Hyperdimensional Computing. AMIA Annual Symposium Proceedings, 2013, 1007–1016.

Moon, S., Pakhomov, S., Liu, N., Ryan, J. O., & Melton, G. B. (2014). A sense inventory for clinical abbreviations and acronyms created using clinical notes and medical dictionary resources. Journal of the American Medical Informatics Association : JAMIA, 21(2), 299–307. http://doi.org/10.1136/amiajnl-2012-001506

ShARe/CLEF eHealth Challenge 2013, Task 2. Journal of Biomedical Semantics, 7, 43. http://doi.org/10.1186/s13326-016-0084-y

Wu, Y., Denny, J. C., Rosenbloom, S. T., Miller, R. A., Giuse, D. A., Song, M., & Xu, H. (2015). A Preliminary Study of Clinical Abbreviation Disambiguation in Real Time. Applied Clinical Informatics, 6(2), 364–374. http://doi.org/10.4338/ACI-2014-10-RA-0088

Wu, Y., Xu, J., Zhang, Y., Xu, H., (2015) Clinical Abbreviation Disambiguation Using Neural Word Embeddings. Proceedings of BioNLP 15

Wang, Y., Zheng, K., Xu, H., & Mei, Q. (2016). Clinical Word Sense Disambiguation with Interactive Search and Classification. AMIA Annual Symposium Proceedings, 2016, 2062–2071.

Stéphan Tulkens, Simon Šuster: “Using Distributed Representations to Disambiguate Biomedical and Clinical Concepts”, 2016, Proceedings of the 15th Workshop on Biomedical Natural Language Processing, Berlin, Germany, 2016, pages 77-82. Association for Computational Linguistics; arXiv:1608.05605.

Billy Chiu, Gamal Crichton, Anna Korhonen, Sampo Pyysalo. How to Train Good Word Embeddings for Biomedical NLP http://aclweb.org/anthology/W/W16/W16-2922.pdf

Michel Oleynikb , Alexander Avianb, Stefan Schulzb. http://www.aclweb.org/anthology/W16-4213

Mowery, D. L., South, B. R., Christensen, L., Leng, J., Peltonen, L.-M., Salanterä, S., … Chapman, W. W. (2016). Normalizing acronyms and abbreviations to aid patient understanding of clinical texts: 

Finley, G. P., Pakhomov, S. V. S., McEwan, R., & Melton, G. B. (2016). Towards Comprehensive Clinical Abbreviation Disambiguation Using Machine-Labeled Training Data. AMIA Annual Symposium Proceedings, 2016, 560–569.

Yanshan Wang, Sijia Liu, Naveed Afzal, Majid Rastegar-Mojarad, Liwei Wang, Feichen Shen, Paul Kingsbury: “A Comparison of Word Embeddings for the Biomedical Natural Language Processing”, 2018; arXiv:1802.00400.

