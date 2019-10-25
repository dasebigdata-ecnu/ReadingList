# 数据库系统实现


经典教材：[《数据库系统实现》](https://book.douban.com/subject/4838430/)

## 查询处理

- 查询优化
  - Begoli E, Camacho-Rodríguez J, Hyde J, et al. Apache calcite: A foundational framework for optimized query processing over heterogeneous data sources[C]//Proceedings of the 2018 International Conference on Management of Data. ACM, 2018: 221-230.
- 查询执行
  - tuple-at-a-time
    - Graefe G. Volcano - an extensible and parallel query evaluation system[J]. IEEE Transactions on Knowledge and Data Engineering, 1994, 6(1): 120-135.
    - Graefe G. Encapsulation of parallelism in the Volcano query processing system[M]. ACM, 1990.
  - vector-at-a-time
    - Padmanabhan S, Malkemus T, Jhingran A, et al. Block oriented processing of relational database operations in modern computer architectures[C]//Proceedings 17th International Conference on Data Engineering. IEEE, 2001: 567-574.
    - Boncz P A, Zukowski M, Nes N. MonetDB/X100: Hyper-Pipelining Query Execution[C]//Cidr. 2005, 5: 225-237.
    - Zukowski M, Boncz P A, Nes N, et al. MonetDB/X100-A DBMS In The CPU Cache[J]. IEEE Data Eng. Bull., 2005, 28(2): 17-22.
  - Code Generation
    - Neumann T. Efficiently compiling efficient query plans for modern hardware[J]. Proceedings of the VLDB Endowment, 2011, 4(9): 539-550.
    - Chrysogelos P, Karpathiotakis M, Appuswamy R, et al. HetExchange: Encapsulating heterogeneous CPU-GPU parallelism in JIT compiled engines[J]. Proceedings of the VLDB Endowment, 2019, 12(5): 544-556.
  - SIMD
    - Polychroniou O, Raghavan A, Ross K A. Rethinking SIMD vectorization for in-memory databases[C]//Proceedings of the 2015 ACM SIGMOD International Conference on Management of Data. ACM, 2015: 1493-1508.


## 事务管理
