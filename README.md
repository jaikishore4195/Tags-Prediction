# Tags-Prediction
ModelIntroduction:
Built  a  Model  which  is  used  to  automatically  extract  tags  from  the  stack  overflow  questions.  For  this  model  but  a  Logistic  Regression  classifier  to  classify  the  code  and  built  a  Resuidual  recurrentnetwork  to  do  the  Key  word  extraction  from  the  question,  Used  ElMo(byAllen  NLP  group)and  Word2Vecembeddingsfor  this  model.

Model  Use  cases  in  Industry:Can  be  used  to  tag  articles,  internal  tickets  or  notes  so  that  user  search  and  recommendation  would  be  more  relevent.  This  Model  with  very  Minor  tweaks  can  be  used  to  do  any  sequence  tagging  tasks  like  POS  tagging,  entity  extarction,  or  finding  for  a  specifc  flag  in  a  stream  of  data.

Model  Performace:Trained  the  model  on  700,000  questions  and  tested  on  400,000  and  the  model  is  performing  with  an  F1  score  of  0.48.  And  the  model  is  underperforming  on  tags  with  multiple  words  in  them  which  I  am  actively  fixing.
