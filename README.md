# SIMD LDPC software decoders for DVB-S2/S2x codes

## Introduction

The contents of this repository concern the scientific publication “Scalable high-throughput and low-latency DVB-S2(x) LDPC decoders on SIMD devices” [1] currently submitted to the scientific journal “IEEE Open Journal of the Communications Society”. It contains data relating to the experiments carried out:

- Numerical values of decoding throughputs and latencies of LDPC decoders for DVB-S2 and DVB-S2x standards.
- The precise characteristics of the INTEL/ARM platforms used to carry out these experiments.

All this data should make it easier to compare results with those of future projects.


## Repository organisation

The repository is structured into 3 directories, each one containing the results of experiments on a particular platform. The 3 platforms considered are:

- Platform 1 - A MacBook Pro desktop computer equipped with an Apple M1 Pro ARM processor.
- Platform 2 - A DELL Optiplex desktop with an INTEL Core i7-12700T processor.
- Platform 3 - An INTEL server with two INTEL Xeon Gold 6148 processors.


## Software decoders

Each of these directories contains:
- an “lscpu.txt” file containing detailed information on the CPU used. 
- a directory named INTER which contains the performances of the decoders presented in [2] with some source code optimization.
- a directory named INTRA containing the performance of the decoders presented in article [1].

Unlike the source codes of the decoders presented in article [2], those of article [1] are not currently available under an open-source license. A license can be purchased from my former employer (Bordeaux-INP, Université de Bordeaux). For more information, please contact me.

## Contact

For further information, please contact me:

- bertrand.le-gal(at)irisa.fr

## References

[1] B. Le Gal. Scalable high-throughput and low-latency DVB-S2(x) LDPC decoders on SIMD devices. IEEE Open Journal of the Communications Society, pages XX–YY, July 2024.

[2] B. Le Gal and C. Jego. High-throughput multi-core LDPC decoders based on x86 processor. IEEE Transactions on Parallel and Distributed Systems (TPDS), 27(5):1373–1386, May 2016.