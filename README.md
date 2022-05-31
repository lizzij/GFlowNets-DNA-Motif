# GFlowNets-DNA-Motif
DNA Motif Mining Using GFlowNets

## Usage
Please refer to each sub-directory for READMEs on how to install, setup and run.

## Code Structure
- notebooks/  
  - Exploratory notebooks for replicating TF-Modisco [1].
  - Gibbs sampling vs GFlowNets comparison [2].
- bioseq/
  - Replicate TF Bind 8 experiment [3].
- gflownets/
  - Replicate original GFlowNets paper [4].
- benchmarking/
  - Compare GFlowNets, Gibbs sampling models against other TF binding models (pwm_HOCOMOCO, DeepBind, lsgkm-SVM, DeepSEA, BPNet) from the Kipoi model zoo [5].

## References
[1] Avsec, Žiga, Melanie Weilert, Avanti Shrikumar, Sabrina Krueger, Amr Alexandari, Khyati Dalal, Robin Fropf, et al. “Base-Resolution Models of Transcription-Factor Binding Reveal Soft Motif Syntax.” Nature Genetics 53, no. 3 (March 2021): 354–66. https://doi.org/10.1038/s41588-021-00782-6.

[2] Chen, Xin, Lingqiong Guo, Zhaocheng Fan, and Tao Jiang. “W-AlignACE: An Improved Gibbs Sampling Algorithm Based on More Accurate Position Weight Matrices Learned from Sequence and Gene Expression/ChIP-Chip Data.” Bioinformatics 24, no. 9 (May 1, 2008): 1121–28. https://doi.org/10.1093/bioinformatics/btn088.

[3] Jain, Moksh, Emmanuel Bengio, Alex-Hernandez Garcia, Jarrid Rector-Brooks, Bonaventure F. P. Dossou, Chanakya Ekbote, Jie Fu, et al. “Biological Sequence Design with GFlowNets.” ArXiv:2203.04115 [Cs, q-Bio], March 2, 2022. http://arxiv.org/abs/2203.04115.

[4] Bengio, Emmanuel, Moksh Jain, Maksym Korablyov, Doina Precup, and Yoshua Bengio. “Flow Network Based Generative Models for Non-Iterative Diverse Candidate Generation.” In Ad-vances in Neural Information Processing Systems, 34:27381–94. Curran Associates, Inc., 2021. https://papers.nips.cc/paper/2021/hash/e614f646836aaed9f89ce58e837e2310-Abstract.html.

[5] Avsec, Žiga, Roman Kreuzhuber, Johnny Israeli, Nancy Xu, Jun Cheng, Avanti Shrikumar, Abhimanyu Banerjee, et al. “The Kipoi Repository Accelerates Community Exchange and Reuse of Predictive Models for Genomics.” Nature Biotechnology 37, no. 6 (June 2019): 592–600. https://doi.org/10.1038/s41587-019-0140-0.