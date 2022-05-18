# twitter-deliberative-politics

Please do not share without permission from Kokil Jaidka, kokil.jaidka@gmail.com
For now, you can cite our JoC paper if you use these predictive models or annotated data.

Jaidka, K., Zhou, A., & Lelkes, Y. (2019). Brevity is the soul of Twitter: The constraint affordance and political discussion. Journal of Communication, 69(4), 345-372.

Dashboard for model inspection:
https://share.streamlit.io/sriramelango/nus-political-discourse-quality/app.py

Models used in the dashboard:
Are in the pickles folder

Other resources corresponding to this paper are at:
https://osf.io/u2nfp/

Which variables to use?
Please refer to the most recent results discussed at 
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3870554


#################################################Folder structure
data/trainingdata/jaidka.csv comprises the raw annotated data

supplement/codingscheme.docx describes the coding scheme

Each observation was labeled for each of the deliberative qualities with a 0, 1, or NULL depending on whether there was agreement between at least 3 if not 4 annotators out of 4 total annotators. 


###################################################Variable names

message_id and message: an id and the text of the tweet
relevance: see coding scheme, codes whether the tweet is relevant to politics.
>>positive: whether the tweet shows empathy and respect (note that "positive" means empathy and respect)
>>uncivil: any kind of incivility, whether, abuse, threat, or exaggeration
>>uncivil_abuse: incivility that is abusive (see coding scheme)
>>uncivil_threat: incivility that involves threats (see coding scheme)
>>uncivil_exag: incivility that involves exaggerated claims (see coding scheme)
>>reciprocal: deliberation which involves a genuine question (supposed to encode engagement)
>>justif: justification whether internal or external.
>>justif_int: internal justification
>>justif_ext: external justification
>>const: constructiveness whether fact-checking, solution-finding, or common-ground-finding
>>const_fact: constructiveness involving fact-checking behavior
>>const_com: constructiveness involving common ground finding
>>const_sol: constructiveness involving solution finding
>>len: length of tweet (is not used as an iv)


