## 综述：

- 潘巍,李战怀,杜洪涛,周陈超,苏静.新型非易失存储环境下事务型数据管理技术研究.软件学报,2017,28(1)
- Justin A. DeBrabant, Joy Arulraj, Andrew Pavlo, Michael Stonebraker, Stanley B. Zdonik, Subramanya Dulloor: A Prolegomenon on OLTP Database Systems for Non-Volatile Memory. ADMS@VLDB 2014: 57-63
- Stratis D. Viglas: Data Management in Non-Volatile Memory. SIGMOD Conference 2015: 1707-1711
- Shashank Gugnani, Arjun Kashyap, Xiaoyi Lu: Understanding the Idiosyncrasies of Real Persistent Memory. Proc. VLDB Endow. 14(4): 626-639 (2020)
- Dimitrios Koutsoukos, Raghav Bhartia, Ana Klimovic, Gustavo Alonso:How to use Persistent Memory in your Database. CoRR abs/2112.00425 (2021)

## 系统架构\存储：

- Justin A. DeBrabant, Andrew Pavlo, Stephen Tu, Michael Stonebraker, Stanley B. Zdonik: Anti-Caching: A New Approach to Database Management System Architecture. Proc. VLDB Endow. 6(14): 1942-1953 (2013)

- Ruicheng Liu, Peiquan Jin, Xiaoliang Wang, Zhou Zhang, Shouhong Wan, Bei Hua: NVLevel: A High Performance Key-Value Store for Non-Volatile Memory. HPCC/SmartCity/DSS 2019: 1020-1027

- Lawrence Benson, Hendrik Makait, Tilmann Rabl: Viper: An Efficient Hybrid PMem-DRAM Key-Value Store. Proc. VLDB Endow. 14(9): 1544-1556 (2021)

- Gang Liu, Leying Chen, Shimin Chen: Zen: a High-Throughput Log-Free OLTP Engine for Non-Volatile Main Memory. Proc. VLDB Endow. 14(5): 835-848 (2021)

- Hideaki Kimura: FOEDUS: OLTP Engine for a Thousand Cores and NVRAM. SIGMOD Conference 2015: 691-706

- Alexander van Renen, Viktor Leis, Alfons Kemper, Thomas Neumann, Takushi Hashida, Kazuichi Oe, Yoshiyasu Doi, Lilian Harada, Mitsuru Sato: Managing Non-Volatile Memory in Database Systems. SIGMOD Conference 2018: 1541-1555

- Xianzhang Chen, Edwin Hsing-Mean Sha, Ahmad Abdullah, Qingfeng Zhuge, Lin Wu, Chaoshu Yang, Weiwen Jiang: UDORN: A design framework of persistent in-memory key-value database for NVM. NVMSA 2017:1-6

- Ahmad Hassan, Dimitrios S. Nikolopoulos, Hans Vandierendonck:Fast and Energy-Efficient OLAP Data Management on Hybrid Main Memory Systems. IEEE Trans. Computers 68(11): 1597-1611 (2019)

- Jinfeng Yang, Bingzhe Li, David J. Lilja:HeuristicDB:  a hybrid storage database system using a non-volatile memory block device. SYSTOR 2021: 16:1-16:12

- Robert Lasch, Robert Schulze, Thomas Legler, Kai-Uwe Sattler: Workload-Driven Placement of Column-Store Data Structures on DRAM and NVM. DaMoN 2021: 5:1-5:8

- Yongping Luo, Peiquan Jin, Shouhong Wan: Optimal Data Placement for Data-Centric Algorithms on NVM-Based Hybrid Memory. DSAA 2020: 226-235

  

## 恢复技术研究：

- Steven Pelley, Thomas F. Wenisch, Brian T. Gold, Bill Bridge: Storage Management in the NVRAM Era. Proc. VLDB Endow. 7(2): 121-132 (2013)

- Joel Coburn, Trevor Bunker, Meir Schwarz, Rajesh Gupta, Steven Swanson: From ARIES to MARS: transaction support for next-generation, solid-state drives. SOSP 2013: 197-212

- Jian Huang, Karsten Schwan, Moinuddin K. Qureshi: NVRAM-aware Logging in Transaction Systems. Proc. VLDB Endow. 8(4): 389-400 (2014)

- Shen Gao, Jianliang Xu, Theo Härder, Bingsheng He, Byron Choi, Haibo Hu: PCMLogging: Optimizing Transaction Logging and Recovery Performance with PCM. IEEE Trans. Knowl. Data Eng. 27(12): 3332-3346 (2015)

- Joy Arulraj, Matthew Perron, Andrew Pavlo: Write-Behind Logging. Proc. VLDB Endow. 10(4): 337-348 (2016)

- Yongseok Son, Hara Kang, Heon Young Yeom,  Hyuck Han: 2017. A log-structured buffer for database systems using non-volatile memory. In Proceedings of the Symposium on Applied Computing (SAC '17). Association for Computing Machinery, New York, NY, USA, 880–886. 

- Ru Fang, Hui-I Hsiao, Bin He, C. Mohan, Yun Wang: High performance database logging using storage class memory. ICDE 2011: 1221-1231

- Jian Huang, Karsten Schwan, Moinuddin K. Qureshi: NVRAM-aware Logging in Transaction Systems. Proc. VLDB Endow. 8(4): 389-400 (2014)

- Joy Arulraj, Andrew Pavlo, Subramanya Dulloor: Let's Talk About Storage & Recovery Methods for Non-Volatile Memory Database Systems. SIGMOD Conference 2015: 707-722

- Tianzheng Wang, Ryan Johnson: Scalable Logging through Emerging Non-Volatile Memory. Proc. VLDB Endow. 7(10): 865-876 (2014)

- Ismail Oukid, Daniel Booss, Wolfgang Lehner, Peter Bumbulis, Thomas Willhalm: SOFORT: a hybrid SCM-DRAM storage engine for fast data recovery. DaMoN 2014: 8:1-8:7

- Aasheesh Kolli, Steven Pelley, Ali G. Saidi, Peter M. Chen, Thomas F. Wenisch: High-Performance Transactions for Persistent Memories. ASPLOS 2016: 399-411

  

## 并发控制技术研究：

- Per-Åke Larson, Spyros Blanas, Cristian Diaconu, Craig Freedman, Jignesh M. Patel, Mike Zwilling: High-Performance Concurrency Control Mechanisms for Main-Memory Databases. Proc. VLDB Endow. 5(4): 298-309 (2011)
- Ryan Johnson, Ippokratis Pandis, Anastasia Ailamaki: Improving OLTP Scalability using Speculative Lock Inheritance. Proc. VLDB Endow. 2(1): 479-489 (2009)
- Ippokratis Pandis, Ryan Johnson, Nikos Hardavellas, Anastasia Ailamaki:
  Data-Oriented Transaction Execution. Proc. VLDB Endow. 3(1): 928-939 (2010)
- Ippokratis Pandis, Pinar Tözün, Miguel Branco, Dimitris Karampinas, Danica Porobic, Ryan Johnson, Anastasia Ailamaki: A data-oriented transaction execution engine and supporting tools. SIGMOD Conference 2011: 1237-1240
- Kun Ren, Alexander Thomson, Daniel J. Abadi: Lightweight Locking for Main Memory Database Systems. Proc. VLDB Endow. 6(2): 145-156 (2012)
- Kun Ren, Alexander Thomson, Daniel J. Abadi: VLL: a lock manager redesign for main memory database systems. VLDB J. 24(5): 681-705 (2015)



## 索引技术研究：

- Shimin Chen, Qin Jin: Persistent B+-Trees in Non-Volatile Main Memory. Proc. VLDB Endow. 8(7): 786-797 (2015)
- Pengfei Zuo, Yu Hua, Jie Wu: Write-Optimized and High-Performance Hashing Index Scheme for Persistent Memory. OSDI 2018: 461-476
- Se Kwon Lee, Jayashree Mohan, Sanidhya Kashyap, Taesoo Kim, Vijay Chidambaram: Recipe: converting concurrent DRAM indexes to persistent-memory indexes. SOSP 2019: 462-477
- Moohyeon Nam, Hokeun Cha, Young-ri Choi, Sam H. Noh, Beomseok Nam: Write-Optimized Dynamic Hashing for Persistent Memory. FAST 2019: 31-44
- Yoav Zuriel, Michal Friedman, Gali Sheffi, Nachshon Cohen, Erez Petrank:
  Efficient lock-free durable sets. Proc. ACM Program. Lang. 3(OOPSLA): 128:1-128:26 (2019)
- Baotong Lu, Xiangpeng Hao, Tianzheng Wang, Eric Lo: Dash: Scalable Hashing on Persistent Memory. Proc. VLDB Endow. 13(8): 1147-1161 (2020)
- Zhangyu Chen, Yu Hua, Bo Ding, Pengfei Zuo: Lock-free Concurrent Level Hashing for Persistent Memory. USENIX Annual Technical Conference 2020: 799-812
- Daokun Hu, Zhiwen Chen, Jianbing Wu, Jianhua Sun, Hao Chen: Persistent Memory Hash Indexes: An Experimental Evaluation. Proc. VLDB Endow. 14(5): 785-798 (2021)
- Saeed Kargar, Faisal Nawab: Hamming Tree: The Case for Memory-Aware Bit Flipping Reduction for NVM Indexing. CIDR 2021



## 排序技术研究：

- Zhaole Chu, Yongping Luo, Peiquan Jin: An Efficient Sorting Algorithm for Non-Volatile Memory.
  International Journal of Software Engineering and Knowledge Engineering (2021): n. pag.

- Yongping Luo, Zhaole Chu, Peiquan Jin, Shouhong Wan: Efficient Sorting and Join on NVM-Based Hybrid Memory. ICA3PP (1) 2020: 15-30

- Mohammed Bey Ahmed Khernache, Arezki Laga, Jalil Boukhobza: MONTRES-NVM: An External Sorting Algorithm for Hybrid Memory. NVMSA 2018: 49-54

  