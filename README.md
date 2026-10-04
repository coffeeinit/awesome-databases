# Awesome Databases [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of modern database systems categorized strictly by core architecture.

## Table of Contents

1. [Embedded Databases](https://www.google.com/search?q=%231-embedded-databases)
2. [Vector Databases](https://www.google.com/search?q=%232-vector-databases)
3. [Backend-as-a-Service (BaaS)](https://www.google.com/search?q=%233-backend-as-a-service-baas)
4. [Relational Databases (RDBMS)](https://www.google.com/search?q=%234-relational-databases-rdbms)
5. [Document Databases](https://www.google.com/search?q=%235-document-databases)
6. [Key-Value Stores](https://www.google.com/search?q=%236-key-value-stores)
7. [In-Memory Databases](https://www.google.com/search?q=%237-in-memory-databases)
8. [Columnar Analytics (OLAP) Databases](https://www.google.com/search?q=%238-columnar-analytics-olap-databases)
9. [Graph Databases](https://www.google.com/search?q=%239-graph-databases)
10. [Time-Series Databases](https://www.google.com/search?q=%2310-time-series-databases)
11. [Wide-Column Stores](https://www.google.com/search?q=%2311-wide-column-stores)
12. [Search Engine Databases](https://www.google.com/search?q=%2312-search-engine-databases)
13. [Spatial & Geospatial Databases](https://www.google.com/search?q=%2313-spatial--geospatial-databases)
14. [Immutable & Ledger Databases](https://www.google.com/search?q=%2314-immutable--ledger-databases)
15. [Version-Controlled Databases](https://www.google.com/search?q=%2315-version-controlled-databases)
16. [Event-Sourcing Databases](https://www.google.com/search?q=%2316-event-sourcing-databases)
17. [CRDT & Local-First Sync Engines](https://www.google.com/search?q=%2317-crdt--local-first-sync-engines)

---

### 1. Embedded Databases

*Databases meant to run directly inside application binaries or on device disk/memory.*

* **SQLite** – Serverless file-based transactional database engine
* **DuckDB** – Embedded in-process analytical SQL engine
* **PocketBase** – Embedded Go-based database with admin dashboard
* **LibSQL** – Open-source SQLite fork created for serverless edge deployments
* **PGLite** – Lightweight PostgreSQL engine compiled to WebAssembly
* **Realm** – Mobile-first object database for client applications
* **RocksDB** – Embeddable persistent key-value store optimized for fast storage
* **LevelDB** – Fast key-value storage library written at Google
* **LMDB** – Ultra-fast memory-mapped embedded key-value database
* **UnQLite** – Embedded NoSQL transactional database engine
* **ObjectBox** – High-speed embedded database for mobile and IoT applications
* **WatermelonDB** – High-performance reactive database framework for React Native
* **RxDB** – Local-first reactive database engine for Web Applications
* **BerkeleyDB** – Legacy embedded key-value database library
* **TinyDB** – Lightweight document-oriented embedded database for Python
* **H2** – Lightweight embedded SQL engine written in Java
* **HSQLDB** – HyperSQL relational database engine written in Java
* **Apache Derby** – Open-source relational database implemented entirely in Java
* **BadgerDB** – Fast embedded key-value database written in Go
* **Sled** – Modern embedded key-value store written in Rust

---

### 2. Vector Databases

*Databases engineered specifically for storing, indexing, and querying high-dimensional embeddings.*

* **Pinecone** – Cloud-native managed vector search service
* **Milvus** – Open-source distributed vector database
* **Qdrant** – Vector similarity search engine written in Rust
* **Chroma** – Open-source embedding database for AI application development
* **Weaviate** – Open-source vector engine with native machine-learning integrations
* **LanceDB** – Developer-friendly embedded vector engine powered by Apache Arrow
* **Marqo** – Tensor search engine with integrated multi-modal embeddings
* **Vespa** – Scalable engine for big-data vector indexing and search
* **Vald** – Highly scalable distributed vector search engine built on Kubernetes
* **Faiss** – Library for dense vector similarity search and clustering
* **Deep Lake** – Vector database tailored specifically for deep learning datasets
* **Turbopuffer** – Serverless vector database built on cloud object storage
* **MyScale** – Vector database tailored for SQL-based AI workloads
* **Zilliz** – Cloud-managed enterprise platform powered by Milvus
* **zvec** – Embedded vector database designed for on-device RAG

---

### 3. Backend-as-a-Service (BaaS)

*Fully integrated application platforms combining real-time database, auth, and APIs.*

* **Supabase** – Open-source Firebase alternative built on top of PostgreSQL
* **Firebase Realtime Database** – Cloud-hosted NoSQL JSON store with live synchronization
* **Firestore** – Flexible, scalable NoSQL document backend platform
* **Appwrite** – Self-hosted backend suite providing databases, storage, and authentication
* **Nhost** – Backend platform providing GraphQL APIs over PostgreSQL
* **SurrealDB** – Multi-model cloud platform database
* **Convex** – Reactive, real-time backend platform database
* **InstantDB** – Client-side reactive graph backend engine
* **Parse Platform** – Open-source application backend framework
* **Amplify DataStore** – Offline-first cloud platform database by AWS
* **8base** – Low-code cloud database engine powered by GraphQL
* **Xano** – Scalable visual backend engine with hosted database
* **Backendless** – Visual development platform with built-in database services
* **Hasura** – Instant GraphQL and REST API engine over databases

---

### 4. Relational Databases (RDBMS)

*Classic row-oriented transactional SQL databases supporting strict ACID properties.*

* **PostgreSQL** – Open-source object-relational database management system
* **MySQL** – Popular open-source relational database management system
* **MariaDB** – Enterprise-grade community fork of MySQL
* **Microsoft SQL Server** – Enterprise relational database system developed by Microsoft
* **Oracle Database** – Enterprise multi-model relational database system
* **IBM Db2** – High-performance enterprise relational database
* **Amazon Aurora** – Cloud-optimized relational engine compatible with Postgres and MySQL
* **Google Cloud Spanner** – Fully managed globally distributed relational SQL database
* **CockroachDB** – Distributed SQL database designed for cloud resilience
* **YugabyteDB** – Cloud-native distributed SQL database engine
* **TiDB** – Open-source distributed SQL database compatible with MySQL
* **AlloyDB** – Fully managed PostgreSQL-compatible engine built for enterprise workloads
* **Firebird** – Relational database offering ANSI SQL features in a small footprint
* **SingleStore** – Cloud-native distributed SQL engine for real-time transactions
* **OceanBase** – Enterprise distributed financial-grade relational database
* **Informix** – High-efficiency relational database engine by IBM
* **Percona Server for MySQL** – Enterprise-enhanced drop-in replacement for MySQL
* **Virtuoso** – Hybrid relational engine with SPARQL capabilities
* **SQLite Cloud** – Cloud-distributed implementation of SQLite engines

---

### 5. Document Databases

*Schema-flexible databases storing semi-structured documents (JSON, BSON, XML).*

* **MongoDB** – Document-oriented NoSQL database system
* **CouchDB** – Open-source document database using HTTP and REST APIs
* **Couchbase** – Distributed JSON document database with built-in caching
* **Amazon DocumentDB** – Fully managed JSON document database service
* **Azure Cosmos DB** – Multi-model globally distributed document database
* **RethinkDB** – Real-time JSON database designed for push updates
* **RavenDB** – Fully transactional NoSQL document database engine
* **MarkLogic** – Multi-model enterprise database for XML and JSON
* **FerretDB** – Open-source MongoDB alternative built on PostgreSQL
* **ArangoDB** – Multi-model document and graph database
* **OrientDB** – Multi-model document-graph hybrid database
* **BaseX** – XML database engine and XPath/XQuery processor
* **eXist-db** – Open-source native XML database
* **Tigris** – Serverless document database built for cloud developers
* **Percona Server for MongoDB** – Enterprise replacement for MongoDB Community Edition

---

### 6. Key-Value Stores

*Persistent or persistent-optional data stores operating on single unique keys.*

* **Etcd** – Strongly consistent distributed key-value store used for system state
* **Consul KV** – Distributed key-value store for configuration management
* **Aerospike** – Flash-optimized real-time key-value database
* **TiKV** – Distributed transactional key-value database engine
* **FoundationDB** – Distributed key-value database built for ACID transactions
* **BoltDB** – Pure Go persistent key-value store
* **BerkleyDB KV** – Low-level key-value data storage framework
* **UnQLite KV** – Transactional key-value engine
* **Sled KV** – Embedded lock-free key-value database
* **Redict** – Copy-left open-source key-value database
* **HyperDex** – Searchable key-value store offering consistency and speed
* **Oracle Coherence** – Enterprise-grade distributed key-value data grid

---

### 7. In-Memory Databases

*Databases holding all active records in system RAM for minimal query latency.*

* **Redis** – In-memory key-value data structure store
* **Valkey** – Open-source, high-performance in-memory data store
* **Memcached** – Distributed memory object caching system
* **Dragonfly** – High-throughput in-memory data store compatible with Redis
* **KeyDB** – Multithreaded high-performance fork of Redis
* **Garnet** – High-performance in-memory cache store developed by Microsoft
* **Hazelcast** – Distributed in-memory data grid system
* **Apache Geode** – Real-time in-memory data management system
* **GridGain** – Enterprise in-memory computing platform built on Apache Ignite
* **MemDB** – Distributed transactional in-memory database engine
* **Tarantool** – In-memory database and application server engine
* **Mnesia** – Distributed in-memory DBMS built into Erlang/OTP

---

### 8. Columnar Analytics (OLAP) Databases

*Column-oriented databases built specifically for heavy aggregation and analytical data warehousing.*

* **ClickHouse** – Fast open-source columnar database management system
* **Apache Druid** – Real-time analytical data store designed for low-latency queries
* **Apache Pinot** – Distributed analytical store built for real-time aggregation
* **Snowflake** – Enterprise cloud data warehouse platform
* **Amazon Redshift** – Cloud data warehouse built for large-scale data analytics
* **Google BigQuery** – Serverless enterprise data warehouse
* **Databricks Lakehouse** – Unified data analytics platform using Delta Lake
* **Apache Doris** – Real-time analytical database based on columnar engine
* **StarRocks** – High-performance sub-second analytical database
* **Greenplum** – Open-source massively parallel processing (MPP) analytical database
* **Teradata Vantage** – Enterprise multi-cloud data analytics database
* **Exasol** – In-memory columnar analytics database
* **Vertica** – Massively parallel processing columnar database engine
* **Hydra** – Open-source columnar PostgreSQL extension for analytics
* **SlothDB** – In-process analytical SQL database written in C++
* **chDB** – Embedded ClickHouse engine running in-process

---

### 9. Graph Databases

*Databases using node and edge structures to represent and query interconnected data networks.*

* **Neo4j** – Enterprise graph database management system
* **Amazon Neptune** – Managed graph database service
* **Memgraph** – In-memory graph database running on native C++
* **Dgraph** – Distributed graph database with native GraphQL support
* **JanusGraph** – Scalable distributed graph database
* **TigerGraph** – Enterprise graph analytics engine for real-time deep queries
* **NebulaGraph** – Open-source distributed graph database engine
* **Cayley** – Open-source graph database created at Google
* **ArcadeDB** – Multi-model graph database supporting Cypher and SQL
* **FalkorDB** – Low-latency graph database built on top of Redis
* **TypeDB** – Strongly-typed knowledge-graph engine
* **Stardog** – Enterprise knowledge graph database platform
* **GraphDB** – Semantic RDF graph database engine
* **Apache HugeGraph** – Distributed graph database designed for massive data graphs
* **Omnigraph** – Typed graph database built natively for agentic workloads
* **Actionbase** – Graph engine built for user interactions

---

### 10. Time-Series Databases

*Databases engineered for indexing timestamped data, telemetry, metrics, and streams.*

* **TimescaleDB** – PostgreSQL-based time-series database engine
* **InfluxDB** – High-throughput open-source time-series platform
* **Prometheus** – Cloud-native monitoring system with a time-series store
* **VictoriaMetrics** – Scalable long-term storage time-series system
* **QuestDB** – Fast SQL time-series database engine
* **TDengine** – Big data time-series database designed for IoT metrics
* **Apache IoTDB** – High-performance time-series database for IoT infrastructure
* **Graphite** – Scalable real-time graphing time-series database
* **OpenTSDB** – Distributed time-series database built on top of Apache HBase
* **VictoriaMetrics Cloud** – Managed time-series infrastructure platform
* **ReductStore** – High-performance blob and time-series storage engine

---

### 11. Wide-Column Stores

*Horizontally scalable NoSQL databases based on Google's Bigtable architecture.*

* **Apache Cassandra** – Distributed wide-column NoSQL database system
* **ScyllaDB** – High-performance C++ implementation of Apache Cassandra
* **Apache HBase** – Distributed wide-column store built on Apache Hadoop
* **Amazon DynamoDB** – Managed serverless wide-column NoSQL service
* **Google Cloud Bigtable** – Enterprise NoSQL wide-column database service
* **Apache Accumulo** – Sorted distributed key-value store with cell-level access controls
* **Azure Managed Cassandra** – Cloud-managed Apache Cassandra database

---

### 12. Search Engine Databases

*Databases designed for fast text indexing, fuzzy matching, and real-time search queries.*

* **Elasticsearch** – Distributed full-text search and analytics engine
* **OpenSearch** – Open-source search and analytics suite derived from Elasticsearch
* **Meilisearch** – Fast, open-source localized full-text search engine
* **Typesense** – Fast, typo-tolerant open-source search engine
* **Apache Solr** – Enterprise search platform built on Apache Lucene
* **Manticore Search** – Open-source search database for full-text and vector search
* **Sphinx** – Legacy open-source full-text search engine
* **Quickwit** – Distributed log search engine designed for cloud storage
* **Tantivy** – Rust-based full-text search engine library
* **Bleve** – Modern text indexing engine written in Go
* **Sonic** – Lightweight, fast search backend written in Rust

---

### 13. Spatial & Geospatial Databases

*Databases specialized for indexing, calculating, and querying spatial coordinates.*

* **PostGIS** – Spatial database extender for PostgreSQL
* **Tile38** – In-memory spatial index and real-time geofence server
* **SpatiaLite** – Spatial extension for SQLite database engine
* **H3 Engine** – Hexagonal hierarchical spatial indexing database engine
* **GeoServer** – Open-source server for sharing geospatial data

---

### 14. Immutable & Ledger Databases

*Databases providing cryptographically verifiable, append-only, and tamper-proof logs.*

* **ImmuDB** – Lightweight open-source immutable database built for audit logs
* **Amazon QLDB** – Fully managed quantum ledger database service
* **Fluree** – Immutable graph ledger database platform
* **BigchainDB** – Decentralized database with blockchain characteristics

---

### 15. Version-Controlled Databases

*Databases featuring Git-like branching, merging, and version history operations.*

* **Dolt** – Git-style version-controlled SQL database
* **TerminusDB** – Knowledge graph database with version-control revision workflows
* **Datomic** – Transactional database offering time-travel historical queries
* **Noms** – Versionable, Git-like decentralized database engine

---

### 16. Event-Sourcing Databases

*Databases designed to record changes in application state as an append-only stream of events.*

* **EventStoreDB** – Operational database built specifically for Event Sourcing
* **Axon Server** – Dedicated event store built for CQRS and Event Sourcing architectures

---

### 17. CRDT & Local-First Sync Engines

*Sync layers designed to synchronize state between distributed devices without conflict.*

* **ElectricSQL** – Sync engine linking PostgreSQL with edge SQLite databases
* **PowerSync** – Local-first synchronization layer for mobile and edge applications
* **Triplit** – Full-stack relational database with real-time automatic synchronization
