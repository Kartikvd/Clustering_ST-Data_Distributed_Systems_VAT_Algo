# Clustering_ST_Data_in_Distributed_Systems_VAT_Algo
Clustering Tendency Assessment of IoT-Generated Spatio-Temporal Data in Distributed Systems

The image below provides scatter plots of clustered physical parameters on the left and clustered spatio-temporal parameters on the right, which are the outputs of the code.
<img width="2560" height="955" alt="untitled" src="https://github.com/user-attachments/assets/b5f752de-d6a5-48d1-93f2-f87731dfd2c8" />

*** Code is written understandably with comments wherever required. ***

Steps to run the code:
1) Open the git_dnccVAT_MIT.m in MATLAB software.
2) With all the files in the same folder, run the code.
3) You will get the output as displayed above, along with the MST-iVAT image and scatter plot of the physical parameters.

Files:
1) git_dnccVAT_MIT.m : Is the main file.
2) distance2.m : To find euclidean distance between points, else use other distance metric.
3) MST-iVAT.m : Is the minimum spanning tree improved visual assessment of clustering tendency function to develop an MST-iVAT image.
4) SXYTHLEI_MIT.mat : Is the MIT data used in the main code.


Paper link at: https://www.computer.org/csdl/journal/td/5555/01/11363457/2dB0ba9CMCI
For citation use: 
@ARTICLE{11363457,
author={Deshpande, Kartik Vishal and Kumar, Dheeraj and Zaiane, Osmar R},
journal={ IEEE Transactions on Parallel \& Distributed Systems },
title={{ dnccVAT : A Fully Distributed Approach for Clustering Tendency Assessment of IoT Generated Spatio-Temporal Data }},
year={2026},
volume={37},
number={04},
ISSN={1558-2183},
pages={762-774},
abstract={ Clustering spatio-temporal data in distributed systems is crucial for various applications such as traffic management, smart cities, telecommunications, and environmental monitoring. Despite the notable progress made in this field, several significant challenges persist: (a) in centralized systems, spatio-temporal data clustering necessitates that data be sent to the cloud for processing, which raises concerns about data transmission costs, latency, and privacy and security, (b) centralized systems incur high computational costs and require expensive hardware, resulting in prolonged runtime for algorithms, and (c) lack of well-defined space and time contiguous clusters adversely affects the overall usability of the clusters produced. These challenges are addressed by the proposed dnccVAT algorithm for assessing clustering tendency in spatio-temporal data within distributed systems, which is part of the visual assessment of clustering tendency family of algorithms. This algorithm effectively navigates the complexities associated with spatial-temporal relationships while minimizing communication overhead and ensuring scalability across distributed participant nodes. Extensive experiments were carried out on six real-world datasets, one of them being high-dimensional Big Data, comparing the proposed method with four state-of-the-art spatio-temporal data clustering algorithms and evaluating seven different performance measures to provide valuable insights into the effectiveness of the proposed approach. },
keywords={Clustering algorithms;Distributed databases;Internet of Things;Databases;Runtime;Temperature sensors;Sensors;Spatiotemporal phenomena;Prediction algorithms;Temperature measurement},
doi={10.1109/TPDS.2026.3657795},
url = {https://doi.ieeecomputersociety.org/10.1109/TPDS.2026.3657795},
publisher={IEEE Computer Society},
address={Los Alamitos, CA, USA},
month=apr}






