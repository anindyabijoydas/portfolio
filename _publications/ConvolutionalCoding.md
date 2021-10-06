---
title: "Efficient and Robust Distributed Matrix Computations via Convolutional Coding"
collection: publications
Authors: <b>Anindya Bijoy Das</b>, Aditya Ramamoorthy, and Namrata Vaswani.'
date: 07/2021
venue: 'IEEE Transactions on Information Theory'
paperurl: 'https://arxiv.org/abs/2104.08645'
presentationurl: ''
codeurl: 'https://github.com/uclanlp/Robust-XLT'
excerpt: ''
---
---
<a href='https://ieeexplore.ieee.org/abstract/document/9478901' target="_blank">[Download Paper]</a>

<p align="justify">
Distributed matrix computations – matrix-matrix or matrix-vector multiplications – are well-recognized to suffer from the problem of stragglers (slow or failed worker nodes). Much of prior work in this area is (i) either sub-optimal in terms of its straggler resilience, or (ii) suffers from numerical problems, i.e., there is a blow-up of round-off errors in the decoded result owing to the high condition numbers of the corresponding decoding matrices. Our work presents a convolutional coding approach to this problem that removes these limitations. It is optimal in terms of its straggler resilience, and has excellent numerical robustness as long as the workers’ storage capacity is slightly higher than the fundamental lower bound. Moreover, it can be decoded using a fast peeling decoder that only involves add/subtract operations. Our second approach has marginally higher decoding complexity than the first one, but allows us to operate arbitrarily close to the storage capacity lower bound. Its numerical robustness can be theoretically quantified by deriving a computable upper bound on the worst case condition number over all possible decoding matrices by drawing connections with the properties of large block Toeplitz matrices. All above claims are backed up by extensive experiments done on the AWS cloud platform.
</p>

