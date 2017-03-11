# cws-seq2seq

### Model
- Sequence to sequence with attention modeling
  
  e.g., 
  
        x: 扬帆远东做与中国合作的先行。<eos>
        
        y：扬帆<eow>远东<eow>做<eow>与<eow>中国<eow>合作<eow>的<eow>先行<eow>。<eow><eos>

### Dataset
- icwb2: sighan bakeoff2005, http://sighan.cs.uchicago.edu/bakeoff2005/

### Results
- MSR: 

  Recall = 0.956, Precision =	0.956, F1-Measure =	0.956
  
- PKU:

  Recall = 0.911, Precision =	0.920, F1-Measure =	0.915

### Comments
- Surprised me that a seq2seq framework (based on neural machine translation) can get a 90+ F1. 
