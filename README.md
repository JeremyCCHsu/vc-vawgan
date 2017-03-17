# Demo
https://jeremycchsu.github.io/vc-vawgan/

# Hyper-parameters and other Experimental Settings  
`z_dim: 64` the dimenstion of the phonetic content space  
`y_dim: 10` the number of speakers  
`merge_dim: 171`  the dimension of speaker space  
`clamping: 0.01`  the K-Lipschitz scalar  
<br/>
For the CNN architecture, please see the `architecture.json` file.


# Mean Opinion Scores (MOS)
In the intra-gender experiment (SF1 to TF2), the evaluators have access to two extra audio files for reference: a GMM baseline whose mean MOS was 1.53 and the true target whose mean MOS was 4.72.
