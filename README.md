# FFNet

**To facilitate reviewers to verify the performance of our proposed method, we will provide test and model codes upon request after the first review.**

We provide here the results of our model prediction error tests in the UNIV scenario with and without noise.
**The proposed method can effectively resist the influence of noise!**

**************************************************
Model being tested are: ['./checkpoints/FFNet/univ']
**************************************************
Evaluating model: ./checkpoints/FFNet/univ
  0%|          | 0/947 [00:00<?, ?it/s]Processing Data .....
100%|██████████| 947/947 [00:01<00:00, 494.95it/s]
**************************************************
Clean trajectory - Testing ....
ade: 0.23467277  fde: 0.42339092
**************************************************
**************************************************
0.1 times Gaussian noise + Clean trajectory - Testing ....
ade: 0.23467304  fde: 0.42340538
**************************************************
**************************************************
0.2 times Gaussian noise + Clean trajectory - Testing ....
ade: 0.23469396  fde: 0.42343852
**************************************************
**************************************************
0.3 times Gaussian noise + Clean trajectory - Testing ....
ade: 0.23471934  fde: 0.42358536
**************************************************
Number of parameters: 5192

See you later!
