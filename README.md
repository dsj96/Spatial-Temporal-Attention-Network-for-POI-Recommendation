# STAN: Spatial-Temporal-Attention-Network-for-Next-Location-Recommendation
Update! The paper is accepted by the Web conference 2021. https://arxiv.org/abs/2102.04095

Author Reply: 
Thank you for your interest in our work! First I want to apologize for uploading the wrong files.   
Please use the new .py files in this repository if you downloaded the wrong files (before 3/18). (Sorry!)

I have corrected this mistake and I summarize some FAQs:  
1) Can you provide a dataset?  
We use datasets provided in the following links.  
http://snap.stanford.edu/data/loc-gowalla.html;  
https://personal.ntu.edu.sg/404.html;   
http://www-public.imtbs-tsp.eu/~zhang_da/pub/dataset_tsmc2014.zip
2) I ran into some problems in reading the paper or inplementing the codes. May I talk/discuss with you?  
It would be my pleasure to answer your questions. Please do not hesitate to email me or leave comments at any time and explain the problem concisely so I can assist.
3）What does it mean "The number of training set is 𝑚 − 3, with the first 𝑚′ ∈ [1,𝑚 − 3] check-ins as input sequence and the [2,𝑚 − 2]-nd visited location as label"?  
We use [1] as input to predict [2], use [1,2] as input to predict [3], and so on, until we use [1,...,m-3] to predict [m-2].
4) What is the environment to run the code? And version?  
We use python 3.7.2 with CUDA 10.1 and PyTorch 1.7.1. Make sure to install all required libs that we import.  
5) Are you open to cooperation?  
I always welcome collaborations, although it is highly recommended to drop me an outline of research proposal first. :}

