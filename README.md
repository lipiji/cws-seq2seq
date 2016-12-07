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

  Recall = 0.946, Precision =	0.942, F1-Measure =	0.944
  
- PKU:

  Recall = 0.906, Precision =	0.910, F1-Measure =	0.908

### Comments
- Surprised me that a seq2seq (based on neural machine translation) framework can get a 90+ F1. 
