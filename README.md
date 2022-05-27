# Memory-efficient Fano Decoding of PAC Codes

If you find this algorithm useful, please cite the following paper. Thanks.

M. Rowshan, A. Burg and E. Viterbo, "Polarization-Adjusted Convolutional (PAC) Codes: Sequential Decoding vs List Decoding," in IEEE Transactions on Vehicular Technology, vol. 70, no. 2, pp. 1434-1447, Feb. 2021, doi: 10.1109/TVT.2021.3052550.

https://ieeexplore.ieee.org/abstract/document/9328621

M. Rowshan, A. Burg and E. Viterbo, "Complexity-efficient Fano Decoding of Polarization-adjusted Convolutional (PAC) Codes," 2020 International Symposium on Information Theory and Its Applications (ISITA), 2020, pp. 200-204.

https://ieeexplore.ieee.org/document/9366116

This Python project provides different versions of Fano-like decoder for PAC codes (also can be used for polar codes by choosing convolutional polynomial $\mathbf{g}=[1]$) described in the aformentioned papers.
This algorithm requires to store $N-1$ intermediate LLRs and partial sums. Alternatively, you can store all of them, i.e., $N \cdot \log_2 N$.
The algorithm might be confusing. If you have questions about it, you can contact me.

Note that the algorithmic procedure of updating the intermediate LLRs can be simplified using the method discussed in the following paper. 

https://arxiv.org/abs/2109.10466


Please report any bugs to mrowshan at ieee dot org
