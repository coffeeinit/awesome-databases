# Awesome Databases [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of modern database systems categorized strictly by core architecture.

## Table of Contents

1. [Embedded Databases](#1-embedded-databases)
2. [Vector Databases](#2-vector-databases)
3. [Backend-as-a-Service (BaaS)](#3-backend-as-a-service-baas)
4. [Relational Databases (RDBMS)](#4-relational-databases-rdbms)
5. [Document Databases](#5-document-databases)
6. [Key-Value Stores](#6-key-value-stores)
7. [In-Memory Databases](#7-in-memory-databases)
8. [Columnar Analytics (OLAP) Databases](#8-columnar-analytics-olap-databases)
9. [Graph Databases](#9-graph-databases)
10. [Time-Series Databases](#10-time-series-databases)
11. [Wide-Column Stores](#11-wide-column-stores)
12. [Search Engine Databases](#12-search-engine-databases)
13. [Spatial & Geospatial Databases](#13-spatial--geospatial-databases)
14. [Immutable & Ledger Databases](#14-immutable--ledger-databases)
15. [Version-Controlled Databases](#15-version-controlled-databases)
16. [Event-Sourcing Databases](#16-event-sourcing-databases)
17. [CRDT & Local-First Sync Engines](#17-crdt--local-first-sync-engines)

---

### 1. Embedded Databases

*Databases meant to run directly inside application binaries or on device disk/memory.*

* [**SQLite**](https://sqlite.org) – Serverless file-based transactional database engine
* [**DuckDB**](https://duckdb.org) – Embedded in-process analytical SQL engine
* [**PocketBase**](https://pocketbase.io) – Embedded Go-based database with admin dashboard
* [**LibSQL**](https://github.com/tursodatabase/libsql) – Open-source SQLite fork created for serverless edge deployments
* [**PGLite**](https://pglite.dev) – Lightweight PostgreSQL engine compiled to WebAssembly
* [**Realm**](https://github.com/realm/realm-core) – Mobile-first object database for client applications
* [**RocksDB**](https://rocksdb.org) – Embeddable persistent key-value store optimized for fast storage
* [**LevelDB**](https://github.com/google/leveldb) – Fast key-value storage library written at Google
* [**LMDB**](https://www.symas.com/lmdb) – Ultra-fast memory-mapped embedded key-value database
* [**UnQLite**](https://unqlite.org) – Embedded NoSQL transactional database engine
* [**ObjectBox**](https://objectbox.io) – High-speed embedded database for mobile and IoT applications
* [**WatermelonDB**](https://watermelondb.dev) – High-performance reactive database framework for React Native
* [**RxDB**](https://rxdb.info) – Local-first reactive database engine for Web Applications
* [**BerkeleyDB**](https://www.oracle.com/database/technologies/related/berkeleydb.html) – Legacy embedded key-value database library
* [**TinyDB**](https://github.com/msiemens/tinydb) – Lightweight document-oriented embedded database for Python
* [**H2**](https://h2database.com) – Lightweight embedded SQL engine written in Java
* [**HSQLDB**](https://hsqldb.org) – HyperSQL relational database engine written in Java
* [**Apache Derby**](https://db.apache.org/derby/) – Open-source relational database implemented entirely in Java
* [**BadgerDB**](https://github.com/dgraph-io/badger) – Fast embedded key-value database written in Go
* [**Sled**](https://github.com/spacejam/sled) – Modern embedded key-value store written in Rust

---

### 2. Vector Databases

*Databases engineered specifically for storing, indexing, and querying high-dimensional embeddings.*

* [**Pinecone**](https://www.pinecone.io) – Cloud-native managed vector search service
* [**Milvus**](https://milvus.io) – Open-source distributed vector database
* [**Qdrant**](https://qdrant.tech) – Vector similarity search engine written in Rust
* [**Chroma**](https://www.trychroma.com) – Open-source embedding database for AI application development
* [**Weaviate**](https://weaviate.io) – Open-source vector engine with native machine-learning integrations
* [**LanceDB**](https://lancedb.com) – Developer-friendly embedded vector engine powered by Apache Arrow
* [**Marqo**](https://www.marqo.ai) – Tensor search engine with integrated multi-modal embeddings
* [**Vespa**](https://vespa.ai) – Scalable engine for big-data vector indexing and search
* [**Vald**](https://vald.vdaas.org) – Highly scalable distributed vector search engine built on Kubernetes
* [**Faiss**](https://github.com/facebookresearch/faiss) – Library for dense vector similarity search and clustering
* [**Deep Lake**](https://github.com/activeloop-ai/deeplake) – Vector database tailored specifically for deep learning datasets
* [**Turbopuffer**](https://turbopuffer.com) – Serverless vector database built on cloud object storage
* [**MyScale**](https://github.com/myscale/myscaledb) – Vector database tailored for SQL-based AI workloads
* [**Zilliz**](https://zilliz.com) – Cloud-managed enterprise platform powered by Milvus
* [**zvec**](https://github.com/alibaba/zvec) – Embedded vector database designed for on-device RAG

---

### 3. Backend-as-a-Service (BaaS)

*Fully integrated application platforms combining real-time database, auth, and APIs.*

* [**Supabase**](https://supabase.com) – Open-source Firebase alternative built on top of PostgreSQL
* [**Firebase Realtime Database**](https://firebase.google.com/products/realtime-database) – Cloud-hosted NoSQL JSON store with live synchronization
* [**Firestore**](https://firebase.google.com/products/firestore) – Flexible, scalable NoSQL document backend platform
* [**Appwrite**](https://appwrite.io) – Self-hosted backend suite providing databases, storage, and authentication
* [**Nhost**](https://nhost.io) – Backend platform providing GraphQL APIs over PostgreSQL
* [**SurrealDB**](https://surrealdb.com) – Multi-model cloud platform database
* [**Convex**](https://www.convex.dev) – Reactive, real-time backend platform database
* [**InstantDB**](https://www.instantdb.com) – Client-side reactive graph backend engine
* [**Parse Platform**](https://parseplatform.org) – Open-source application backend framework
* [**Amplify DataStore**](https://docs.amplify.aws/gen1/javascript/build-a-backend/more-features/datastore/) – Offline-first cloud platform database by AWS
* [**8base**](https://www.8base.com) – Low-code cloud database engine powered by GraphQL
* [**Xano**](https://www.xano.com) – Scalable visual backend engine with hosted database
* [**Backendless**](https://backendless.com) – Visual development platform with built-in database services
* [**Hasura**](https://hasura.io) – Instant GraphQL and REST API engine over databases

---

### 4. Relational Databases (RDBMS)

*Classic row-oriented transactional SQL databases supporting strict ACID properties.*

* [**PostgreSQL**](https://www.postgresql.org) – Open-source object-relational database management system
* [**MySQL**](https://www.mysql.com) – Popular open-source relational database management system
* [**MariaDB**](https://mariadb.org) – Enterprise-grade community fork of MySQL
* [**Microsoft SQL Server**](https://www.microsoft.com/sql-server) – Enterprise relational database system developed by Microsoft
* [**Oracle Database**](https://www.oracle.com/database/) – Enterprise multi-model relational database system
* [**IBM Db2**](https://www.ibm.com/products/db2) – High-performance enterprise relational database
* [**Amazon Aurora**](https://aws.amazon.com/rds/aurora/) – Cloud-optimized relational engine compatible with Postgres and MySQL
* [**Google Cloud Spanner**](https://cloud.google.com/spanner) – Fully managed globally distributed relational SQL database
* [**CockroachDB**](https://www.cockroachlabs.com) – Distributed SQL database designed for cloud resilience
* [**YugabyteDB**](https://www.yugabyte.com) – Cloud-native distributed SQL database engine
* [**TiDB**](https://github.com/pingcap/tidb) – Open-source distributed SQL database compatible with MySQL
* [**AlloyDB**](https://cloud.google.com/alloydb) – Fully managed PostgreSQL-compatible engine built for enterprise workloads
* [**Firebird**](https://firebirdsql.org) – Relational database offering ANSI SQL features in a small footprint
* [**SingleStore**](https://www.singlestore.com) – Cloud-native distributed SQL engine for real-time transactions
* [**OceanBase**](https://www.oceanbase.com) – Enterprise distributed financial-grade relational database
* [**Informix**](https://www.ibm.com/products/informix) – High-efficiency relational database engine by IBM
* [**Percona Server for MySQL**](https://www.percona.com/mysql/software/percona-server-for-mysql) – Enterprise-enhanced drop-in replacement for MySQL
* [**Virtuoso**](https://virtuoso.openlinksw.com) – Hybrid relational engine with SPARQL capabilities
* [**SQLite Cloud**](https://sqlitecloud.io) – Cloud-distributed implementation of SQLite engines

---

### 5. Document Databases

*Schema-flexible databases storing semi-structured documents (JSON, BSON, XML).*

* [**MongoDB**](https://www.mongodb.com) – Document-oriented NoSQL database system
* [**CouchDB**](https://couchdb.apache.org) – Open-source document database using HTTP and REST APIs
* [**Couchbase**](https://www.couchbase.com) – Distributed JSON document database with built-in caching
* [**Amazon DocumentDB**](https://aws.amazon.com/documentdb/) – Fully managed JSON document database service
* [**Azure Cosmos DB**](https://azure.microsoft.com/products/cosmos-db) – Multi-model globally distributed document database
* [**RethinkDB**](https://rethinkdb.com) – Real-time JSON database designed for push updates
* [**RavenDB**](https://ravendb.net) – Fully transactional NoSQL document database engine
* [**MarkLogic**](https://www.progress.com/marklogic) – Multi-model enterprise database for XML and JSON
* [**FerretDB**](https://www.ferretdb.com) – Open-source MongoDB alternative built on PostgreSQL
* [**ArangoDB**](https://arangodb.com) – Multi-model document and graph database
* [**OrientDB**](https://orientdb.org) – Multi-model document-graph hybrid database
* [**BaseX**](https://basex.org) – XML database engine and XPath/XQuery processor
* [**eXist-db**](https://exist-db.org) – Open-source native XML database
* [**Tigris**](https://github.com/tigrisdata/tigris) – Serverless document database built for cloud developers
* [**Percona Server for MongoDB**](https://www.percona.com/mongodb/software/percona-server-for-mongodb) – Enterprise replacement for MongoDB Community Edition

---

### 6. Key-Value Stores

*Persistent or persistent-optional data stores operating on single unique keys.*

* [**Etcd**](https://etcd.io) – Strongly consistent distributed key-value store used for system state
* [**Consul KV**](https://developer.hashicorp.com/consul/docs/dynamic-app-config/kv) – Distributed key-value store for configuration management
* [**Aerospike**](https://aerospike.com) – Flash-optimized real-time key-value database
* [**TiKV**](https://tikv.org) – Distributed transactional key-value database engine
* [**FoundationDB**](https://www.foundationdb.org) – Distributed key-value database built for ACID transactions
* [**BoltDB**](https://github.com/etcd-io/bbolt) – Pure Go persistent key-value store
* [**BerkleyDB KV**](https://www.oracle.com/database/technologies/related/berkeleydb.html) – Low-level key-value data storage framework
* [**UnQLite KV**](https://unqlite.org) – Transactional key-value engine
* [**Sled KV**](https://github.com/spacejam/sled) – Embedded lock-free key-value database
* [**Redict**](https://redict.io) – Copy-left open-source key-value database
* [**HyperDex**](https://github.com/rescrv/HyperDex) – Searchable key-value store offering consistency and speed
* [**Oracle Coherence**](https://coherence.community) – Enterprise-grade distributed key-value data grid

---

### 7. In-Memory Databases

*Databases holding all active records in system RAM for minimal query latency.*

* [**Redis**](https://redis.io) – In-memory key-value data structure store
* [**Valkey**](https://valkey.io) – Open-source, high-performance in-memory data store
* [**Memcached**](https://memcached.org) – Distributed memory object caching system
* [**Dragonfly**](https://www.dragonflydb.io) – High-throughput in-memory data store compatible with Redis
* [**KeyDB**](https://github.com/Snapchat/KeyDB) – Multithreaded high-performance fork of Redis
* [**Garnet**](https://microsoft.github.io/garnet/) – High-performance in-memory cache store developed by Microsoft
* [**Hazelcast**](https://hazelcast.com) – Distributed in-memory data grid system
* [**Apache Geode**](https://geode.apache.org) – Real-time in-memory data management system
* [**GridGain**](https://www.gridgain.com) – Enterprise in-memory computing platform built on Apache Ignite
* [**MemDB**](https://github.com/search?q=memdb&type=repositories) – Distributed transactional in-memory database engine
* [**Tarantool**](https://www.tarantool.io) – In-memory database and application server engine
* [**Mnesia**](https://www.erlang.org/doc/apps/mnesia/) – Distributed in-memory DBMS built into Erlang/OTP

---

### 8. Columnar Analytics (OLAP) Databases

*Column-oriented databases built specifically for heavy aggregation and analytical data warehousing.*

* [**ClickHouse**](https://clickhouse.com) – Fast open-source columnar database management system
* [**Apache Druid**](https://druid.apache.org) – Real-time analytical data store designed for low-latency queries
* [**Apache Pinot**](https://pinot.apache.org) – Distributed analytical store built for real-time aggregation
* [**Snowflake**](https://www.snowflake.com) – Enterprise cloud data warehouse platform
* [**Amazon Redshift**](https://aws.amazon.com/redshift/) – Cloud data warehouse built for large-scale data analytics
* [**Google BigQuery**](https://cloud.google.com/bigquery) – Serverless enterprise data warehouse
* [**Databricks Lakehouse**](https://www.databricks.com) – Unified data analytics platform using Delta Lake
* [**Apache Doris**](https://doris.apache.org) – Real-time analytical database based on columnar engine
* [**StarRocks**](https://www.starrocks.io) – High-performance sub-second analytical database
* [**Greenplum**](https://greenplum.org) – Open-source massively parallel processing (MPP) analytical database
* [**Teradata Vantage**](https://www.teradata.com/platform/vantage) – Enterprise multi-cloud data analytics database
* [**Exasol**](https://www.exasol.com) – In-memory columnar analytics database
* [**Vertica**](https://www.vertica.com) – Massively parallel processing columnar database engine
* [**Hydra**](https://github.com/hydradatabase/hydra) – Open-source columnar PostgreSQL extension for analytics
* [**SlothDB**](https://github.com/search?q=slothdb&type=repositories) – In-process analytical SQL database written in C++
* [**chDB**](https://github.com/chdb-io/chdb) – Embedded ClickHouse engine running in-process

---

### 9. Graph Databases

*Databases using node and edge structures to represent and query interconnected data networks.*

* [**Neo4j**](https://neo4j.com) – Enterprise graph database management system
* [**Amazon Neptune**](https://aws.amazon.com/neptune/) – Managed graph database service
* [**Memgraph**](https://memgraph.com) – In-memory graph database running on native C++
* [**Dgraph**](https://dgraph.io) – Distributed graph database with native GraphQL support
* [**JanusGraph**](https://janusgraph.org) – Scalable distributed graph database
* [**TigerGraph**](https://www.tigergraph.com) – Enterprise graph analytics engine for real-time deep queries
* [**NebulaGraph**](https://www.nebula-graph.io) – Open-source distributed graph database engine
* [**Cayley**](https://github.com/cayleygraph/cayley) – Open-source graph database created at Google
* [**ArcadeDB**](https://arcadedb.com) – Multi-model graph database supporting Cypher and SQL
* [**FalkorDB**](https://www.falkordb.com) – Low-latency graph database built on top of Redis
* [**TypeDB**](https://typedb.com) – Strongly-typed knowledge-graph engine
* [**Stardog**](https://www.stardog.com) – Enterprise knowledge graph database platform
* [**GraphDB**](https://graphdb.ontotext.com) – Semantic RDF graph database engine
* [**Apache HugeGraph**](https://hugegraph.apache.org) – Distributed graph database designed for massive data graphs
* [**Omnigraph**](https://github.com/search?q=omnigraph&type=repositories) – Typed graph database built natively for agentic workloads
* [**Actionbase**](https://github.com/kakao/actionbase) – Graph engine built for user interactions

---

### 10. Time-Series Databases

*Databases engineered for indexing timestamped data, telemetry, metrics, and streams.*

* [**TimescaleDB**](https://github.com/timescale/timescaledb) – PostgreSQL-based time-series database engine
* [**InfluxDB**](https://www.influxdata.com) – High-throughput open-source time-series platform
* [**Prometheus**](https://prometheus.io) – Cloud-native monitoring system with a time-series store
* [**VictoriaMetrics**](https://victoriametrics.com) – Scalable long-term storage time-series system
* [**QuestDB**](https://questdb.com) – Fast SQL time-series database engine
* [**TDengine**](https://tdengine.com) – Big data time-series database designed for IoT metrics
* [**Apache IoTDB**](https://iotdb.apache.org) – High-performance time-series database for IoT infrastructure
* [**Graphite**](https://graphiteapp.org) – Scalable real-time graphing time-series database
* [**OpenTSDB**](http://opentsdb.net) – Distributed time-series database built on top of Apache HBase
* [**VictoriaMetrics Cloud**](https://victoriametrics.com/products/cloud/) – Managed time-series infrastructure platform
* [**ReductStore**](https://www.reduct.store) – High-performance blob and time-series storage engine

---

### 11. Wide-Column Stores

*Horizontally scalable NoSQL databases based on Google's Bigtable architecture.*

* [**Apache Cassandra**](https://cassandra.apache.org) – Distributed wide-column NoSQL database system
* [**ScyllaDB**](https://www.scylladb.com) – High-performance C++ implementation of Apache Cassandra
* [**Apache HBase**](https://hbase.apache.org) – Distributed wide-column store built on Apache Hadoop
* [**Amazon DynamoDB**](https://aws.amazon.com/dynamodb/) – Managed serverless wide-column NoSQL service
* [**Google Cloud Bigtable**](https://cloud.google.com/bigtable) – Enterprise NoSQL wide-column database service
* [**Apache Accumulo**](https://accumulo.apache.org) – Sorted distributed key-value store with cell-level access controls
* [**Azure Managed Cassandra**](https://azure.microsoft.com/products/managed-instance-apache-cassandra) – Cloud-managed Apache Cassandra database

---

### 12. Search Engine Databases

*Databases designed for fast text indexing, fuzzy matching, and real-time search queries.*

* [**Elasticsearch**](https://www.elastic.co/elasticsearch) – Distributed full-text search and analytics engine
* [**OpenSearch**](https://opensearch.org) – Open-source search and analytics suite derived from Elasticsearch
* [**Meilisearch**](https://www.meilisearch.com) – Fast, open-source localized full-text search engine
* [**Typesense**](https://typesense.org) – Fast, typo-tolerant open-source search engine
* [**Apache Solr**](https://solr.apache.org) – Enterprise search platform built on Apache Lucene
* [**Manticore Search**](https://manticoresearch.com) – Open-source search database for full-text and vector search
* [**Sphinx**](http://sphinxsearch.com) – Legacy open-source full-text search engine
* [**Quickwit**](https://quickwit.io) – Distributed log search engine designed for cloud storage
* [**Tantivy**](https://github.com/quickwit-oss/tantivy) – Rust-based full-text search engine library
* [**Bleve**](https://blevesearch.com) – Modern text indexing engine written in Go
* [**Sonic**](https://github.com/valeriansaliou/sonic) – Lightweight, fast search backend written in Rust

---

### 13. Spatial & Geospatial Databases

*Databases specialized for indexing, calculating, and querying spatial coordinates.*

* [**PostGIS**](https://postgis.net) – Spatial database extender for PostgreSQL
* [**Tile38**](https://tile38.com) – In-memory spatial index and real-time geofence server
* [**SpatiaLite**](https://www.gaia-gis.it/fossil/libspatialite/) – Spatial extension for SQLite database engine
* [**H3 Engine**](https://h3geo.org) – Hexagonal hierarchical spatial indexing database engine
* [**GeoServer**](https://geoserver.org) – Open-source server for sharing geospatial data

---

### 14. Immutable & Ledger Databases

*Databases providing cryptographically verifiable, append-only, and tamper-proof logs.*

* [**ImmuDB**](https://immudb.io) – Lightweight open-source immutable database built for audit logs
* [**Amazon QLDB**](https://aws.amazon.com/qldb/) – Fully managed quantum ledger database service
* [**Fluree**](https://flur.ee) – Immutable graph ledger database platform
* [**BigchainDB**](https://www.bigchaindb.com) – Decentralized database with blockchain characteristics

---

### 15. Version-Controlled Databases

*Databases featuring Git-like branching, merging, and version history operations.*

* [**Dolt**](https://github.com/dolthub/dolt) – Git-style version-controlled SQL database
* [**TerminusDB**](https://terminusdb.com) – Knowledge graph database with version-control revision workflows
* [**Datomic**](https://www.datomic.com) – Transactional database offering time-travel historical queries
* [**Noms**](https://github.com/attic-labs/noms) – Versionable, Git-like decentralized database engine

---

### 16. Event-Sourcing Databases

*Databases designed to record changes in application state as an append-only stream of events.*

* [**EventStoreDB**](https://github.com/EventStore/EventStore) – Operational database built specifically for Event Sourcing
* [**Axon Server**](https://www.axoniq.io) – Dedicated event store built for CQRS and Event Sourcing architectures

---

### 17. CRDT & Local-First Sync Engines

*Sync layers designed to synchronize state between distributed devices without conflict.*

* [**ElectricSQL**](https://electric-sql.com) – Sync engine linking PostgreSQL with edge SQLite databases
* [**PowerSync**](https://www.powersync.com) – Local-first synchronization layer for mobile and edge applications
* [**Triplit**](https://www.triplit.dev) – Full-stack relational database with real-time automatic synchronization
