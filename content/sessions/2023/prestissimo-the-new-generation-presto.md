---
title: "Prestissimo : The new generation Presto"
slug: prestissimo-the-new-generation-presto
speakers:
 - Aditi Pandit
time_start: 2023-12-12T17:00:00-04:00
time_end: 2023-12-12T17:25:00-04:00
---

Prestissimo is the latest innovation in the Presto SQL query engine (https://prestodb.io/). It is an ambitious endeavor to replace Presto's Java based runtime execution with a new state of the art C++ engine based on the concepts of vectorization and runtime optimizations.  
 
The Native engine has many benefits : 
 i) Huge Performance boost and CPU efficiency on account of use of vectorization, SIMD and sophisticated adaptive runtime optimizations. 
 ii) Eliminates spiky and unpredictable Java GC issues. The Prestissimo memory management framework provides better accounting and features like memory arbitration. This offers the engine more explicit memory control than Java GC. 
 iii) Better operational guidance. 
 
In early results in production workloads (at Meta and Bytedance) and the TPC-H benchmark, we have seen CPU use drop down to as much as 1/3rd of Presto Java. 
 
Prestissimo leverages the Velox open source initiative https://velox-lib.io/. Velox is a library of data processing primitives of vectors, functions, operators, data cache, memory management framework that powers Prestissimo. Velox is also used with Spark, streaming and other machine learning workloads at Meta.
 
Prestissimo/Velox is a very active project with community participation from Meta, IBM, Intel, Bytedance and Uber. This talk will give more insight into this project and goals for the next few years.