README
========

Persistence Benchmark

This is the standard benchmark of Get & Put operations on POCO C# objects against the different permutations of common durable stores and serialization techniques. Note the interesting behavior as complexity of the object increases.

Included "databases" in this benchmark:
- CouchDB
- MongoDB
- Redis
- SQLServer Filestream

Included serialization techniques:
- .NET BinaryFormatter
- Google Protocol Buffers

~samtj