Augustine Rapheal - Lead Engineer (Government Industry)

Explaining Rest APIs and why its better than XML

**.Net vs .Net core**
1. Lighter
2. Deployment on any env possible e.g. (AWS, Linux)

Single Threading - Run one function at a time.
Multi Threading - Run multiple functions at the same time.

Parallelism
Concurrency

Dependency Injection - Its an architecture. Reduces strongly coupled services. Makes code maintenance easy.

**Types of DI / Life cycle**
1. Transient - New instance per every information
2. Scoped - Per full life time of the user request
3. Singleton - One life time

Socket exhaustion - every number of database there is a final number of threads that can be opened

Garbage collect - If open a call to the DB it does not close it, it leaves it open. Imagine open 100 calls. the new request starts failing cause no sockets available.

ORM - Entityframwork core, Dapper, Link

DBcontext - Creating entities for the database, running queries, saving queries. When it comes to tracking it is slow. Fluent validation is a package.

DTOs - Data transfer Objects