### AOM annals topic modeling -  Tim Hannigan 2018

#### This analysis is based on Richard Haans' pull of articles from WoS and Scopus on June 27 2018
Richard's file ->
WoS_Scopus_combined_updated.xlsx

distillation of that file->
Corpus_from_Richard_analysis_2018_06_27.xlsx

This spreadsheet was preprocessed using Python. The code for this can be found in the Jupyter notebook: [AOM_annals_TopicModeling_Richard_June2018_analysis.ipynb](AOM_annals_TopicModeling_Richard_June2018_analysis.ipynb) (the HTML version: [AOM_annals_TopicModeling_Richard_June2018_analysis.html](http://htmlpreview.github.io/?https://github.com/timhannigan/aomannals/blob/master/AOM_annals_TopicModeling_Richard_June2018_analysis.html))

Mallet 2.0.8 was used to run a series of topic models, with the coherence metric showing 65 topics as a good candidate for an optimal model.

The 65 topic model was analyzed using python (Pandas and pyLDAvis) in the Jupyter notebook:
AOM_annals_TopicModeling_processLDAoutput_65_topics_June2018_analysis.ipynb (HTML version: AOM_annals_TopicModeling_processLDAoutput_65_topics_June2018_analysis.html)
