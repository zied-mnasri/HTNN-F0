A. Functions

1. train_HTNN_F0.m       --> Train a neural network's model based on Hilbert transform parameters to estimate F0
   
2. eval_f0_clean_noisy.m --> Evaluate HTNN_F0 methods (Ours) and benchmarking PDA's (Crepe and YANG)
 
   2.1. HTNN_F0.m          --> Evaluate HTNN_F0 methods (Ours)
   
   2.2. fi_delta_extract.m   --> Extraction instantaneous frequency and amplitude by applying Hilbert Transform
   
3. Benchmarking methods
 
   3.1. For Crepe, use pitchcnn (built-in function in matlab 2024a)
   
   3.2. For YANG, download from https://github.com/google/yang_vocoder 

B. Models

net (male voice) in f0_value_net_male.mat

net (female voice) in f0_value_net_female.mat

