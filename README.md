# FastDPeak
Density Peak is not applicable for large scale data, due to the two quantities, i.e, density ρ and δ, are both obtained by brute force algorithm with complexity O(n2). Then, a simple but fast Density Peak Clustering, namely FastDPeak, is proposed, which runs in about O(nlog(n)) expected time in the intrinsic dimensionality. It replaces density with kNN-density, which is computed by fast kNN algorithm such as cover tree, yielding the huge improvement for density computations. Based on kNN-density, local density peaks and non-local density peaks are identiﬁed, and a fast algorithm, whichusestwodifferentstrategiestocomputeδ for them, is also proposed with complexity O(n). Experimental results show that FastDPeak is effective and outperforms other variants of DPeak.
