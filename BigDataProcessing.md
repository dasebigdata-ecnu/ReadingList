# 分布式数据处理系统

**注：加粗的论文是具有代表性的分布式数据处理系统，有助于基本了解。**

## 分布式文件系统

* GFS
    + **Ghemawat, S., Gobioff, H., & Leung, S.-T. (2003). The Google File System. In SOSP (pp. 29–43).**

## 协调服务系统

* ZooKeeper
    + **Hunt, P., Konar, M., Junqueira, F. P., & Reed, B. (2010). ZooKeeper : Wait-free coordination for Internet-scale systems. In USENIX Annual Technology Conference (pp. 1–14).**
* Chubby
    + Burrows, M. (2006). The Chubby lock service for loosely-coupled distributed systems. In OSDI (pp. 335–350).

## 资源管理系统

* Yarn
    + **Vavilapalli, V. K., Murthy, A. C., Douglas, C., Agarwal, S., Konar, M., Evans, R., … Saha, B. (2013). Apache Hadoop yarn: Yet another resource negotiator. In SoCC (p. 5:1-5:16).**
* Mesos
    + Hindman, B., Konwinski, A., Zaharia, M., Ghodsi, A., Joseph, A. D., Katz, R., … Stoica, I. (2010). Mesos : A Platform for Fine-Grained Resource Sharing in the Data Center. In NSDI.

## 批处理系统

* MapReduce
    + **Dean, J., & Ghemawat, S. (2004). MapReduce : Simplified Data Processing on Large Clusters. In OSDI (pp. 137–149).**
	+ Yang, H., Dasdan, A., Hsiao, R., & Parker, D. S. (2007). Map-Reduce-Merge : Simplified Relational Data Processing on Large Clusters. In SIGMOD Conference (pp. 1029–1040).
	+ Ekanayake, J., Li, H., Zhang, B., Gunarathne, T., Bae, S., Qiu, J., & Fox, G. (2010). Twister: a runtime for iterative MapReduce. In HPDC (pp. 810–818).
	+ Bu, Y., Howe, B., & Ernst, M. D. (2010). HaLoop : Efficient Iterative Data Processing on Large Clusters. PVLDB, 3(1), 285–296.
	+ Dittrich, J., Quiané-Ruiz, J.-A., Jindal, A., Kargin, Y., Setty, V., & Schad, J. (2010). Hadoop++: Making a yellow elephant run like a cheetah (without it even noticing). PVLDB, 3(1), 515–529.
	+ Chambers, C., Raniwala, A., Perry, F., Adams, S., Henry, R. R., Bradshaw, R., & Weizenbaum, N. (2010). FlumeJava: Easy, Efficient Data-parallel Pipelines. In PLDI (Vol. 45, pp. 363--375).

* Spark
    + **Zaharia, M., Chowdhury, M., Das, T., Dave, A., Ma, J., Mccauley, M., … Stoica, I. (2012). Resilient Distributed Datasets : A Fault-Tolerant Abstraction for In-Memory Cluster Computing. In NSDI (pp. 15–28).**
    + Zaharia, M., Chowdhury, M., Franklin, M. J., Shenker, S., & Stoica, I. (2010). Spark : Cluster Computing with Working Sets. In HotCloud (pp. 1–7).

* Stratosphere
    + Battré, D., Ewen, S., & Hueske, F. (2010). Nephele / PACTs : A Programming Model and Execution Framework for Web-Scale Analytical Processing. In SoCC (pp. 119–130).	
	+ Ewen, S. (2012). Spinning Fast Iterative Data Flows. PVLDB, 5(11), 1268–1279.
	+ Hueske, F., Peters, M., Sax, M. J., & Rheinl, A. (2012). Opening the Black Boxes in Data Flow Optimization. PVLDB, 5(11), 1256–1267.
	+ Alexandrov, A., Bergmann, R., Ewen, S., Freytag, J. C., Hueske, F., Heise, A., … Warneke, D. (2014). The Stratosphere platform for big data analytics. VLDB Journal, 23(6), 939–964.
	
* Dryad
    + Isard, M., Birrell, A., & Fetterly, D. (2007). Dryad : Distributed Data-Parallel Programs from Sequential Building Blocks. In EuroSys (pp. 59–72).

## 流计算系统

* Streaming系统雏形
    + Condie, T., Conway, N., Alvaro, P., Hellerstein, J. M., Elmeleegy, K., & Sears, R. (2010). MapReduce Online. In NSDI (pp. 313–328). 
	+ Lam, W., Liu, L., Prasad, S., Rajaraman, A., Vacheri, Z., & Doan, A. (2012). Muppet: MapReduce-style Processing of Fast Data. PVLDB, 5(12), 1814–1825.
	+ Neumeyer, L., Robbins, B., Nair, A., & Kesari, A. (2010). S4: Distributed Stream Computing Platform. In ICDMW (pp. 170–177).

* Storm
    + **Toshniwal, A., Donham, J., Bhagat, N., Mittal, S., Ryaboy, D., Taneja, S., … Fu, M. (2014). Storm@twitter. In SIGMOD Conference (pp. 147–156).**
	+ Kulkarni, S., Bhagat, N., Fu, M., Kedigehalli, V., Kellogg, C., Mittal, S., … Taneja, S. (2015). Twitter Heron: Stream Processing at Scale. In SIGMOD Conference (pp. 239–250).
	+ Fu, M., Agrawal, A., Floratou, A., Graham, B., Jorgensen, A., Li, M., … Wang, C. (2017). Twitter Heron: Towards Extensible Streaming Engines. In ICDE (pp. 1165–1172).

* Spark Streaming
    + Zaharia, M., Das, T., Li, H., Shenker, S., & Stoica, I. (2012). Discretized streams: an efficient and fault-tolerant model for stream processing on large clusters. In HotCloud (pp. 10–10).
	+ **Zaharia, M., Das, T., Li, H., Hunter, T., Shenker, S., & Stoica, I. (2013). Discretized Streams: Fault-Tolerant Streaming Computation at Scale. In SOSP (pp. 423–438).**
	
* MillWheel
    + Chernyak, S., Haberman, J., Akidau, T., Balikov, A., Bekiro, K., Lax, R., … Whittle, S. (2013). MillWheel : Fault-Tolerant Stream Processing at Internet Scale. PVLDB, 6(11), 1033–1044.	

## 批流融合系统

* Google Dataflow
    + **Akidau, T., Bradshaw, R., Chambers, C., Chernyak, S., Fer Andez-Moctezuma, R. J., Lax, R., … Google, S. W. (2015). The Dataflow Model: A Practical Approach to Balancing Correctness, Latency, and Cost in Massive-Scale, Unbounded, Out-of-Order Data Processing. PVLDB, 8(12), 1792–1803.**

* Flink
    + Carbone, P., Ewen, S., Haridi, S., Katsifodimos, A., Markl, V., & Tzoumas, K. (2015). Apache Flink: Unified Stream and Batch Processing in a Single Engine. IEEE Data Eng. Bull., 38(4), 28–38.
	+ Carbone, P., Ewen, S., Richter, S., & Gyula, F. (2017). State Management in Apache Flink. PVLDB, 10(20), 1718–1729.
	
* Spark Structured Streaming
	+ Armbrust, M., Das, T., & Torres, J. (2018). Structured Streaming: A Declarative API for Real-Time Applications in Apache Spark. In SIGMOD Conference (pp. 465–476).	

* Beam
    + FlumeJava
    + MillWheel
    + Google Dataflow	

## 图处理系统

* Pregel
    + **Malewicz, G., Austern, M. H., Bik, A. J. C., Dehnert, J. C., Horn, I., Leiser, N., & Czajkowski, G. (2010). Pregel : A System for Large-Scale Graph Processing. In SIGMOD Conference (pp. 135–145).**
	+ Zhou, C., Gao, J., Sun, B., & Yu, J. X. (2014). MOCgraph : Scalable Distributed Graph Processing Using Message Online Computing. PVLDB, 8(4), 377–388.
	+ Tian, Y., Balmin, A., Corsten, S. A., Tatikonda, S., & Mcpherson, J. (2013). From “Think Like a Vertex” to “Think Like a Graph.” PVLDB, 7(3), 193–204.
	
* GraphX
    + Xin, R. S., Gonzalez, J. E., Franklin, M. J., & Stoica, I. (2013). GraphX: A Resilient Distributed Graph System on Spark. In GRADES (p. 2:1-2:6).	
	+ Gonzalez, J. E., Xin, R. S., Dave, A., Crankshaw, D., Franklin, M. J., Stoica, I., & Amplab, B. (2014). GraphX : Graph Processing in a Distributed Dataflow Framework. In OSDI (pp. 599–613).
	

## 综述

* 王珊,王会举,覃雄派,周烜.架构大数据:挑战、现状与展望[J].计算机学报,2011,34(10):1741-1752.
* 覃雄派,王会举,杜小勇,王珊.大数据分析——RDBMS与MapReduce的竞争与共生[j].软件学报,2012,23(1):32-45.
* 申德荣,于戈,王习特,聂铁铮,寇月.支持大数据管理的NoSQL系统研究综述[j].软件学报,2013,24(8):1786-1803.
* 程学旗,靳小龙,王元卓,郭嘉丰,张铁赢,李国杰.大数据系统和分析技术综述[J].软件学报,2014,25(09):1889-1908.
* 孙大为,张广艳,郑纬民.大数据流式计算:关键技术及系统实例[J].软件学报,2014,25(04):839-862.
* 杜小勇,卢卫,张峰.大数据管理系统的历史、现状与未来[J].软件学报,2019,30(01):127-141.
* 崔斌,高军,童咏昕,许建秋,张东祥,邹磊.新型数据管理系统研究进展与趋势[j].软件学报,2019,30(1):164-193
