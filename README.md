# Demo
https://jeremycchsu.github.io/vc-vawgan/

# Hyper-parameters and other Experimental Settings  
`z_dim: 64` the dimenstion of the phonetic content space  
`y_dim: 10` the number of speakers  
`merge_dim: 171`  the dimension of speaker space  
`clamping: 0.01`  the K-Lipschitz scalar  
<br/>
<br/>
For the CNN architecture, please see the `architecture.json` file.  
We treat a 513-dimensional frame as a 513-point signal.  
The choice of CNN is only out of simplicity of pssible later extensions.
<br/>
<br/>

# Mean Opinion Scores (MOS)
Scales:  
5: Excellent  
4: Good  
3: Fair  
2: poor  
1: bad  

In the intra-gender experiment (SF1 to TF2), the evaluators have access to two extra audio files for reference (per pair): a GMM baseline whose mean MOS was 1.53 and the true target whose mean MOS was 4.72.  

Note:
 - The error bar in Fig. 2 indicates **standard deviation** of the sample, not **confidence interval** of the mean.
 - The paired Student-t tests on the MOS scores returned very small p-values, so we used the word **significant** in our paper.
 (intra-gender: VAW-GAN against VAE; inter-gender: VAW-GAN against VAE)

