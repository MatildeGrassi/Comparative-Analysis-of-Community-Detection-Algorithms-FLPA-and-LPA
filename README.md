# Comparative-Analysis-of-Community-Detection-Algorithms-FLPA-and-LPA
This project evaluates and compares the performance of three community detection algorithms: the synchronous label propagation algorithm, the asynchronous label propagation algorithm and the fast label propagation algorithm. The comparison focuses on execution speed and clustering quality across different types of networks, including synthetic networks such as Erdos-Renyi, Barabasi-Albert, Forest Fire, Stochastic Block Model and empirical networks.

## Requirements
Please be sure to have installed the following python packages:
- Networkx
- Timeit
- Numpy
- Random
- Matplotlib.pyplot
- Tqdm

## Codes Description
- **1.ER_withFLPAandLPA**: Evaluating computational time for the FLPA, Asyn. LPA, Syn. LPA acting on ER synthetic networks.
- **2.BA_withFLPAandLPA**: Evaluating computational time for the FLPA, Asyn. LPA, Syn. LPA acting on BA synthetic networks.
- **3.ForestFire_withLPAandFLPA**: Evaluating computational time for the FLPA, Asyn. LPA, Syn. LPA acting on Forest Fire synthetic networks.
- **4.SBM_mix_param**: Evaluating computational time for the FLPA, Asyn. LPA, Syn. LPA acting on SBM synthetic networks with fixed number of nodes and groups number of equal size, increasing the mixing parameter.
- **5.SBM_NMI**: Evaluating the NMI for the FLPA, Asyn. LPA, Syn. LPA acting on SBM synthetic networks with fixed number of nodes and groups number of equal size, increasing the mixing parameter.
- **6.NMI_smallEmpNet**: Evaluating the NMI for the FLPA, Asyn. LPA, Syn. LPA acting on three small empirical networks with a known sociological division of nodes into communities.
- **7.FLPA_LPA_EmpNet**: Evaluating computational time and Modularity for the FLPA, Asyn. LPA, Syn. LPA acting on six large empirical network.
- **8.SBM_random_NMI**: Evaluating the NMI for the LPA Asyn., LPA Ayn., FLPA on a SBM synthetic network with fixed number of nodes, increasing the mixing parameter and the groups' number with randomic generated sizes.
- **9.SBM_random**: Evaluating computational time for the LPA Asyn., LPA Ayn., FLPA on a SBM synthetic network with fixed number of nodes, increasing the mixing parameter and the groups' number with randomic generated sizes.
