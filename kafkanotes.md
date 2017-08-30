

Kafka 
 - Messaging 
 - Horizontal scaling/Distributed
 - Ordered

- Central Hub of Distributed processing
- Distributed Event Ledger  = Distributed Commit Log - append only
- Linear Clustering perfomance - increase 
- Has Messaging Scemantics
- Core is clustering
- Durability and Ordering garauntee

Key Terms
Records -> 
(K,V,Timestamp), immutable, Persisted and Appendonly to Ledger
Broker ->
	Member in a cluster or Node has one or more 
Producer ->

Consumer ->

Topics & Partitions
	Topics are logical name for adressing partitioned
	Partitioned are replicated
	Ordering is garaunteed for a partition
	Offset -> Used for ordering of message, a sequential Id assigned to record on write.
			  Offset is unique within a partition	 
			  Consumer tracks offsets	
			  Offset : Used for replay,Reading at different pace/speed.


---

Single Unpartioned Topic -> 
	Single Write
	Single Read

	Single Write
	Multi Read -> Is it possible ?

Single Partioned Topic

	Single Write
	Single Read


	Single Write
	Multi Read


	Multi Write
	Multi Read
