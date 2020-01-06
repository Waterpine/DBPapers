# DBPapers
Classic or recent papers of each topic

Contributed by Song Bian (The Chinese University of Hong Kong)

### Content

1. [DB + ML](#DB-+-ML)

2. [Data Exploration & Integration](#Data-Exploration-&-Integration)

   - [Provenance & Explanation](#Provenance-&-Explanation)

   - [Data Exploration](#Data-Exploration)

   - [Fairness](#Fairness)

   - [Data Visualization](#Data-Visualization)

3. [Graph Database](#Graph-Database)

   - [Shortest Path](#Shortest-Path)

   - [Influence Maximization](#Influence-Maximization)

   - [Personalized PageRank](#Personalized-PageRank)

   - [Knowledge Graph](#Knowledge-Graph)

   - [Graph Dependence](#Graph-Dependence)

4. [Query Processing & Optimization](#Query-Processing-&-Optimization)

   - [Approximate Query Processing](#Approximate-Query-Processing)

   - [Query Optimization](#Query-Optimization)

5. [New Hardware](#New-Hardware)

   - [NVM](#NVM)

   - [GPU](#GPU)

   - [SSD](#SSD)

6. [Stream & Sketch](#Stream-&-Sketch)



### DB + ML

### Data Exploration & Integration

#### Provenance & Explanation

1. **Hypothetical Reasoning via Provenance Abstraction.** SIGMOD 2019. [paper](https://web.eecs.umich.edu/~yuvalm/docs/sigmod19.pdf)
2. **Ariadne: Online Provenance for Big Graph Analytics.** SIGMOD 2019. [paper](http://www.sysnet.ucsd.edu/sysnet/miscpapers/ariadne-sigmod19.pdf)
3. **Going Beyond Provenance: Explaining Query Answers with Pattern-based Counterbalances.** SIGMOD 2019. [paper](https://users.cs.duke.edu/~sudeepa/papers/SIGMOD2019-cape.pdf)
4. **Explaining Wrong Queries Using Small Examples** SIGMOD 2019. [paper](https://users.cs.duke.edu/~sudeepa/papers/SIGMOD2019-ratest.pdf)
5. **Answering Why-questions by Exemplars in Attributed Graphs.** SIGMOD 2019. [paper](https://dl.acm.org/doi/pdf/10.1145/3299869.3319890?download=true)
6. **Explaining Query Answers with Explanation-Ready Databases.** PVLDB 2015. [paper](http://www.vldb.org/pvldb/vol9/p348-roy.pdf)
7. **A Formal Approach to Finding Explanations for Database Queries.** SIGMOD 2014. [paper](https://homes.cs.washington.edu/~suciu/main_explanation.pdf)
8. **Provenance for Aggregate Queries.** PODS 2011. [paper](https://www.cs.tau.ac.il/~danielde/publications/pods2011b.pdf)

#### Data Exploration

1. **Fast Approximation of Empirical Entropy via Subsampling.** KDD 2019. [paper](https://www.microsoft.com/en-us/research/uploads/prod/2019/07/kdd19entropy.pdf)
2. **Constraint-based Explanation and Repair of Filter-based Transformations.** PVLDB 2018. [paper](http://www.vldb.org/pvldb/vol11/p947-antenucci.pdf)
3. **DIFF: A Relational Interface for Large-Scale Data Explanation.** PVLDB 2018. [paper](#http://www.vldb.org/pvldb/vol12/p419-abuzaid.pdf)

#### Fairness

1. **Interventional Fairness : Causal Database Repair for Algorithmic Fairness.** SIGMOD 2019. [paper](https://homes.cs.washington.edu/~suciu/sigmod-2019-fairness.pdf)
2. **Operationalizing Individual Fairness with Pairwise Fair Representations.** PVLDB 2019. [paper](http://www.vldb.org/pvldb/vol13/p506-lahoti.pdf)
3. **Certifying and Removing Disparate Impact.** KDD 2015. [paper](http://sorelle.friedler.net/papers/kdd_disparate_impact.pdf)
4. **Learning Fair Representations.** ICML 2013. [paper](https://www.cs.toronto.edu/~toni/Papers/icml-final.pdf)
5. **Fairness Through Awareness.** ITCS 2012. [paper](http://www.cs.toronto.edu/~zemel/documents/fairAwareItcs2012.pdf)

#### Data Visualization

1. **Anti-Freeze for Large and Complex Spreadsheets: Asynchronous Formula Computation.** SIGMOD 2019. [paper](https://dl.acm.org/doi/pdf/10.1145/3299869.3319876?download=true)
2. **Towards Democratizing Relational Data Visualization.** SIGMOD 2019. [paper](http://dbgroup.cs.tsinghua.edu.cn/ligl/papers/sigmod19-tutorial-paper.pdf)
3. **Efficient Selection of Geospatial Data on Maps for Interactive and Visualized Exploration.**  SIGMOD 2018. [paper](https://dl.acm.org/doi/pdf/10.1145/3183713.3183738?download=true)
4. **Adaptive Sampling for Rapidly Matching Histograms.** PVLDB 2018. [paper](http://www.vldb.org/pvldb/vol11/p1262-macke.pdf)

### Graph Database

#### Shortest Path

1. **Scaling Distance Labeling on Small-World Networks.** SIGMOD 2019. [paper](https://dl.acm.org/doi/pdf/10.1145/3299869.3319877?download=true)
2. **Efficiently Answering Regular Simple Path Queries on Large Labeled Networks.** SIGMOD 2019. [paper](https://dl.acm.org/doi/pdf/10.1145/3299869.3319882?download=true)
3. **When Hierarchy Meets 2-Hop-Labeling: Efficient Shortest Distance Queries on Road Networks.** SIGMOD 2018. [paper](https://dl.acm.org/doi/pdf/10.1145/3183713.3196913?download=true)

#### Influence Maximization

1. **Maximizing Welfare in Social Networks under A Utility Driven Influence Diffusion model.** SIGMOD 2019. [paper](https://www.microsoft.com/en-us/research/uploads/prod/2019/05/sigmod2019-epic.pdf)
2. **Online Processing Algorithms for Influence Maximization.** SIGMOD 2018. [paper](https://dl.acm.org/doi/pdf/10.1145/3183713.3183749?download=true)
3. **Finding Seeds and Relevant Tags Jointly: For Targeted Influence Maximization in Social Networks.** SIGMOD 2018. [paper](https://www.ntu.edu.sg/home/arijit.khan/Papers/Tag_InfMax_SIGMOD18.pdf)
4. **Efficient Algorithms for Adaptive Influence Maximization.** PVLDB 2018. [paper](http://www.vldb.org/pvldb/vol11/p1029-han.pdf)
5. **Influence Maximization in Near-Linear Time: A Martingale Approach.** SIGMOD 2015. [paper](https://dl.acm.org/doi/pdf/10.1145/2723372.2723734?download=true)
6. **Influence Maximization: Near-Optimal Time Complexity Meets Practical Efficiency.** SIGMOD 2014. [paper](https://arxiv.org/pdf/1404.0900.pdf)

#### Personalized PageRank (PPR)

1. **TopPPR: Top-k Personalized PageRank Queries with Precision Guarantees on Large Graphs** SIGMOD 2018. [paper](http://www.weizhewei.com/papers/SIGMOD18.pdf)
2. **FORA: Simple and Effective Approximate Single-Source Personalized PageRank.** KDD 2017. [paper](http://www.weizhewei.com/papers/kdd17.pdf)
3. **HubPPR: Effective Indexing for Approximate Personalized PageRank.** PVLDB 2016. [paper](http://www.vldb.org/pvldb/vol10/p205-wang.pdf)
4. **Approximate Personalized PageRank on Dynamic Graphs.** KDD 2016. [paper](https://www.kdd.org/kdd2016/papers/files/rfp1146-zhangA.pdf)
5. **Personalized PageRank Estimation and Search: A Bidirectional Approach.** WSDM 2016. [paper](https://dl.acm.org/doi/pdf/10.1145/2835776.2835823?download=true)
6. **Local Computation of PageRank Contributions.** WAW 2007. [paper](http://jenniferchayes.com/Papers/LocalPR.pdf)
7. **Local Graph Partitioning using PageRank Vectors.** FOCS 2006. [paper](http://www.leonidzhukov.net/hse/2015/networks/papers/andersen06localgraph.pdf)
8. **Scaling Personalized Web Search.** WWW 2003. [paper](https://dl.acm.org/doi/pdf/10.1145/775152.775191?download=true)

#### Knowledge Graph

1. **Efficient Knowledge Graph Accuracy Evaluation.** PVLDB 2019. [paper](http://www.vldb.org/pvldb/vol11/p1029-han.pdf)
2. **Maverick: Discovering Exceptional Facts from Knowledge Graphs.** SIGMOD 2018. [paper](http://ranger.uta.edu/~cli/pubs/2018/maverick-sigmod18-zhang.pdf)
3. **Question Answering Over Knowledge Graphs: Question Understanding Via Template Decomposition.** PVLDB 2018. [paper](http://www.vldb.org/pvldb/vol11/p1373-zheng.pdf)

#### Graph Dependence

1. **Deducing Certain Fixes to Graphs.** PVLDB 2019. [paper](http://www.vldb.org/pvldb/vol12/p752-fan.pdf)
2. **Discovering Graph Functional Dependencies.** SIGMOD 2018. [paper](https://dl.acm.org/doi/pdf/10.1145/3183713.3196916?download=true)
3. **Dependencies for Graphs.** PODS 2017. [paper](https://dl.acm.org/doi/pdf/10.1145/3034786.3056114?download=true)

### Query Processing

#### Approximate Query Processing

1. **DBEst: Revisiting Approximate Query Processing Engines with Machine Learning Models.** SIGMOD 2019. [paper](https://dl.acm.org/doi/pdf/10.1145/3299869.3324958?download=true)
2. **Deep Unsupervised Cardinality Estimation** PVLDB 2019. [paper](http://www.vldb.org/pvldb/vol13/p279-yang.pdf)
3. **Learning to Sample: Counting with Complex Queries.** PVLDB 2019. [paper](http://www.vldb.org/pvldb/vol13/p390-walenz.pdf)
4. **Random Sampling over Joins Revisited.** SIGMOD 2018. [paper](https://home.cse.ust.hk/~xhuam/sigmod18.pdf)
5. **AQP++: Connecting Approximate Query Processing With Aggregate Precomputation for Interactive Analytics.** SIGMOD 2018. [paper](http://www.sfu.ca/~jinglinp/sigmod2018-aqp++.pdf)
6. **Two-Level Sampling for Join Size Estimation.** SIGMOD 2017. [paper](https://www.cse.ust.hk/~yike/sigmod17.pdf)

#### Query Optimization

1. **Pessimistic Cardinality Estimation: Tighter Upper Bounds for Intermediate Join Cardinalities.** SIGMOD 2019. [paper](https://waltercai.github.io/assets/pessimistic-query-optimization.pdf)
2. **Exact Cardinality Query Optimization with Bounded Execution Cost.** SIGMOD 2019. [paper](https://dl.acm.org/doi/pdf/10.1145/3299869.3300087?download=true)
3. **Adaptive Optimization of Very Large Join Queries.** SIGMOD 2018. [paper](https://db.in.tum.de/~radke/papers/hugejoins.pdf)

#### Skyline Query & Regret

1. **RRR: Rank-Regret Representative.** SIGMOD 2019. [paper](https://dl.acm.org/doi/pdf/10.1145/3299869.3300080?download=true)
2. **Efficient k-Regret Query Algorithm with Restriction-free Bound for any Dimensionality.** SIGMOD 2018. [paper](http://www.cse.ust.hk/~raywong/paper/sigmod18-regret.pdf)
3. **On Obtaining Stable Rankings.** PVLDB 2018. [paper](http://www.vldb.org/pvldb/vol12/p237-asudeh.pdf)

### New Hardware

#### GPU

#### NVM

#### SSD

### Stream & Sketch