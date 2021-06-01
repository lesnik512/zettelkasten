For a distributed data store you can provide only 2 of 3: [[consistency]], [[availability]], [[partition tolerance]].

A system that is not tolerant to network partitions can achieve data consistency and availability, and often does so by using transaction protocols with [[ACID properties]].

In larger distributed-scale systems, network partitions are given -> [[consistency]] and [[availability]] cannot be achieved at the same time.