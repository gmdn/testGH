This file contains the description of GRIUM(University of Montreal, Team from lab of professor Jian-Yun Nie) CLEF baseline experiments
results and the scripts of index and retrieval. 

It contains:
1) the directory /results, which contains the final retrieval results
2) the directory /scripts, which contains the scripts used to index and retrieve.(produce the results of directory /results)
3) ClefExperiments.pdf, which contains the table of the corpora and topics used
4) ReadMe.txt, first read it please

Method Description:
  xiao jie liu(James Liu), the student of Professor Jian-Yun Nie, submits the CLEF baseline experiments results. James used Lemur/Indri to be 
the basic retrieval platform and used language model with Dirichlet Smoothing(mu=2000) for the retrieval model. James dealed with 12 languages
for the topics and corpora. They are Hungarian(hu),Italian(it),Dutch(nl),Portuguese(pt),Russian(ru),Swedish(sv),German(de),Spanish(es),Finnish(fi),
French(fr),Bulgarian(bg) and Persian(fa).
  James Liu pre-processed the topics files and Corpora by removing the stopwords and stemming the contents. Stopwords list files are provided
by Maria Maistro (maistro@dei.unipd.it), you can download from https://github.com/mmaistro/IR-Reproducibility/tree/mmaistro. The stemming methods
used are from Professfor Jacques.Savoy (Jacques.Savoy@unine.ch)(http://members.unine.ch/jacques.savoy/clef/index.html) for language Bulgarian;
from Jonsafari (https://www.ling.ohio-state.edu/~jonsafari/persian_nlp.html) for language Persian; from Snowball (http://snowball.tartarus.org/)
for other languages (Hungarian,Italian,Dutch,Portuguese,Russian,Swedish,German,Spanish,Finnish and French).
  In the final result, for each topic, there are 1000 documents returned. And the format is Trec standard format. 


Zipball:
   All the files are zipped into the file GRIUM_CLEF_Baseline.zip.
 
