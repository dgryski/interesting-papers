
These are in no particular order:

Simpira: cryptographic permutations designed to be fast on modern 64-bit
processors, yet provide a comfortable security margin against all
currently-known attacks.
    - http://mouha.be/simpira/

A High-Performance Algorithm for Identifying Frequent Items in Data Streams
    - https://arxiv.org/abs/1705.07001

Autoscaling Bloom Filter: Controlling Trade-off Between True and False Positives
    - https://arxiv.org/abs/1705.03934

Adaptive Cuckoo-Filters
    - https://arxiv.org/abs/1704.06818

Consistent Hashing with Bounded Loads
    - https://arxiv.org/abs/1608.01350

Continuous Top-k Queries over Real-Time Web Streams
    - https://arxiv.org/abs/1610.06500

Partial Key Grouping: Load-Balanced Partitioning of Distributed Streams
    - https://arxiv.org/abs/1510.07623

A practical index for approximate dictionary matching with few mismatches
    - https://arxiv.org/abs/1501.04948

LogLog-Beta and More: A New Algorithm for Cardinality Estimation Based on LogLog Counting
    - https://arxiv.org/abs/1612.02284

Robust benchmarking in noisy environments
    - https://arxiv.org/abs/1608.04295

New Algorithms for Heavy Hitters in Data Streams
    - https://arxiv.org/abs/1603.01733

An Optimal Bloom Filter Replacement
    - http://www.itu.dk/people/pagh/papers/bloom.pdf

Fast intersection of sorted lists with SSE:
    - https://highlyscalable.wordpress.com/2012/06/05/fast-intersection-sorted-lists-sse/
    - Also, https://arxiv.org/abs/1401.6399

PAD: Performance Anomaly Detection in Multi-Server Distributed Systems
    https://www.microsoft.com/en-us/research/wp-content/uploads/2014/06/PAD-Performance-Anomaly-Detection-in-Multi-Server-Distributed-Systems.pdf

Detecting Abnormal Machine Characteristics in Cloud Infrastructures
    - https://ti.arc.nasa.gov/publications/4268/download/

PerfAugur: Robust Diagnostics for Performance Anomalies in Cloud Services
    - https://www.microsoft.com/en-us/research/publication/perfaugur-robust-diagnostics-for-performance-anomalies-in-cloud-services/

Fast table-driven base64 encoding/decoding:
    - https://github.com/powturbo/TurboBase64/blob/master/turbob64d.c

Assembly versions of hash functions / cryptographic algorithms:
    - t1ha (Go version: https://github.com/dgryski/go-t1ha )
    - rc5 / rc6 (Go version: https://github.com/dgryski/go-rc5 / https://github.com/dgryski/go-rc6 )

In-memory data layout for Netflix's Hollow:
    - http://hollow.how/advanced-topics/#in-memory-data-layout

Omnisearch Index Formats
    - https://blog.twitter.com/2016/omnisearch-index-formats

NORX8 and NORX16: Authenticated Encryption for Low-End Systems
    - https://eprint.iacr.org/2015/1154

LightMAC: A MAC Mode for Lightweight Block Ciphers:
    - https://eprint.iacr.org/2016/190.pdf

Fast Deterministic Selection (adaptive QuickSelect)
    - https://arxiv.org/abs/1606.00484

A Bloom filter based semi-index on q-grams
    - https://arxiv.org/abs/1507.02989

Faster Population Counts using AVX2 Instructions
    - https://arxiv.org/abs/1611.07612

Quasi-Succinct Indices (compressed inverted indexes):
    - http://vigna.di.unimi.it/ftp/papers/QuasiSuccinctIndices.pdf

Efficient Summing over Sliding Windows (stream statistics)
    - http://arxiv.org/pdf/1604.02450v1.pdf

A Novel Technique for Long-Term Anomaly Detection in the Cloud
    - https://www.usenix.org/system/files/conference/hotcloud14/hotcloud14-vallis.pdf
    - Twitter's anomaly detection algorithm
    - related, http://www.ebaytechblog.com/2015/08/19/statistical-anomaly-detection/
    - related, http://nerds.airbnb.com/anomaly-detection/

TinySet - An Access Efficient Self Adjusting Bloom Filter Construction
    - http://www.cs.technion.ac.il/users/wwwb/cgi-bin/tr-get.cgi/2015/CS/CS-2015-03.pdf

Detecting Change in Data Streams:
    - https://cs.uwaterloo.ca/~shai/vldb04.pdf

Optimal Probabilistic Cache Stampede Prevention:
    - http://www.vldb.org/pvldb/vol8/p886-vattani.pdf 

Hierarchical Delta Debugging:
    - https://blog.acolyer.org/2015/11/17/hierarchical-delta-debugging/
    - (to go with https://github.com/dgryski/go-ddmin )

FastDTW: Toward Accurate Dynamic Time Warping in Linear Time and Space
    - http://cs.fit.edu/~pkc/papers/tdm04.pdf
    - many implementations to use as base, for example https://github.com/slaypni/fastdtw/blob/master/fastdtw.py

Mining frequent items in the time fading model
    - http://arxiv.org/pdf/1601.03892v1.pdf

Hierarchical Agglomerative Clustering:
    - http://nlp.stanford.edu/IR-book/html/htmledition/hierarchical-agglomerative-clustering-1.html
    - needed for https://www.microsoft.com/en-us/research/wp-content/uploads/2016/07/rebucket-icse2012.pdf
    - preliminary implementation of rebucket:  https://github.com/dgryski/go-rebucket

Balanced Allocation: Patience is not a Virtue (FirstDiff load balancing):
    - http://arxiv.org/abs/1602.08298

Continuously Maintaining Quantile Summaries of the Most Recent N Elements over a Data Stream
    - http://www.cs.ubc.ca/~xujian/paper/quant.pdf

The Eternal Sunshine of the Sketch Data Structure
    - http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.146.2889&rep=rep1&type=pdf

Copysets and Chainsets: A Better Way to Replicate
    http://hackingdistributed.com/2014/02/14/chainsets/

A Fast Algorithm for Approximate Quantiles in High Speed Data Streams
    - http://web.cs.ucla.edu/~weiwang/paper/SSDBM07_2.pdf
    - this algorithm has haunted me for ages, I could never get my code working
    - unresponsive authors, details missing from papers, etc
    - there now appear to be more implementations that could be used as a base
