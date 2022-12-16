[![Twitter Follow](https://img.shields.io/twitter/follow/oskar_at_net?style=social)](https://twitter.com/oskar_at_net) [![Github Sponsors](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&link=https://github.com/sponsors/oskardudycz/)](https://github.com/sponsors/oskardudycz/) [![blog](https://img.shields.io/badge/blog-event--driven.io-brightgreen)](https://event-driven.io/)

# PostgreSQL is Awesome!

This repository contains resources I found during my journey with PostgreSQL.

### Hostings
- [Neon](https://neon.tech/)
- [ElephantSql](https://www.elephantsql.com/)

## Partitioning
- [Postgres Documentation - Table Partitioning](https://pgdash.io/blog/partition-postgres-11.html)
- [EDB - Postgres Table Partitioning](https://www.enterprisedb.com/blog/postgres-table-partitioning)
- [David Rowley - Partition Elimination in PostgreSQL 11](https://www.2ndquadrant.com/en/blog/partition-elimination-postgresql-11/)
- [Amit Jain - How to Take Advantage of the New Partitioning Features in PostgreSQL 11](https://severalnines.com/database-blog/how-take-advantage-new-partitioning-features-postgresql-11)
- [pgDash - PostgreSQL 11 Partitioning Improvements](https://pgdash.io/blog/partition-postgres-11.html)
- [StreamBright - Creating partitions automatically in PostgreSQL](https://medium.com/@StreamBright/creating-partitions-automatically-in-postgresql-7006d68c0fbb)
- [Daniel Westermann - PostgreSQL 14: Automatic hash and list partitioning?](https://blog.dbi-services.com/postgresql-14-automatic-hash-and-list-partitioning/)
- [Denish Patel - Is there a limit on number of partitions handled by Postgres?](https://elephas.io/is-there-a-limit-on-number-of-partitions-handled-by-postgres/)
- [AWS - Managing PostgreSQL partitions with the pg_partman extension](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/PostgreSQL_Partitions.html)
- [Automatically Creating Partition in PostgreSQL](https://www.tencentcloud.com/document/product/409/47394)

### WAL
- [Devrim Gündüz -WAL: Everything you want to know](https://www.youtube.com/watch?v=feTihjJJs3g)

### Logical Replication
- [Fujistsu - How PostgreSQL 15 improved communication in logical replication](https://www.postgresql.fastware.com/blog/how-postgresql-15-improved-communication-in-logical-replication)
- [Amit Kapila  - Replication Improvements In PostgreSQL-14](https://amitkapila16.blogspot.com/2021/09/logical-replication-improvements-in.html)
- [Thiago - How to use Change Data Capture (CDC) with Postgres](https://dev.to/thiagosilvaf/how-to-use-change-database-capture-cdc-in-postgres-37b8)
- [Ramesh naik E - Change Data Capture(CDC) in PostgreSQL](https://medium.com/@ramesh.esl/change-data-capture-cdc-in-postgresql-7dee2d467d1b)
- [Percona - The 1-2-3 for PostgreSQL Logical Replication Using an RDS Snapshot](https://www.percona.com/blog/postgresql-logical-replication-using-an-rds-snapshot/)
- [Konstantin Evteev - Recovery use cases for Logical Replication in PostgreSQL 10](https://medium.com/avitotech/recovery-use-cases-for-logical-replication-in-postgresql-10-a1e6bab03072)
- [Several9s - Using PostgreSQL Logical Replication to Maintain an Always Up-to-Date Read/Write TEST Server](https://severalnines.com/blog/using-postgresql-logical-replication-maintain-always-date-readwrite-test-server/)
- [Wal2Json - JSON output plugin for changeset extraction](https://github.com/eulerto/wal2json)
- [AWS Database Blog - Stream changes from Amazon RDS for PostgreSQL using Amazon Kinesis Data Streams and AWS Lambda](https://aws.amazon.com/blogs/database/stream-changes-from-amazon-rds-for-postgresql-using-amazon-kinesis-data-streams-and-aws-lambda/)
- [PGDeltaStream - Streaming Postgres logical replication changes atleast-once over websockets ](https://github.com/hasura/pgdeltastream)
- [Hrvoje Milković - Replicate PostreSQL data to Elasticsearch via Logical replication slots](http://staging.kraken.hr/blog/2018/postgresql-replication-elasticsearch)
- [Azure Database for PostgreSQL—Logical decoding and wal2json for change data capture](https://azure.microsoft.com/en-us/updates/azure-database-for-postgresql-logical-decoding-and-wal2json-for-change-data-capture/)
- [Npgsql - Logical Replication](https://www.npgsql.org/doc/replication.html)
- [Postgresql To Kinesis For Java - Disney Streaming](https://github.com/disneystreaming/pg2k4j)

### Locks
- [Chris Hanks - Turning PostgreSQL into a queue serving 10,000 jobs per second](https://gist.github.com/chanks/7585810)
- [Alvaro Herrera - Postgres - Waiting for 9.5 – Implement SKIP LOCKED for row-level locks](https://www.depesz.com/2014/10/10/waiting-for-9-5-implement-skip-locked-for-row-level-locks/)
- [Vlad Mihalcea - How do PostgreSQL advisory locks work](https://vladmihalcea.com/how-do-postgresql-advisory-locks-work/)
- [Marco Slot - When Postgres blocks: 7 tips for dealing with locks](https://www.citusdata.com/blog/2018/02/22/seven-tips-for-dealing-with-postgres-locks/)
- [Marco Slot - PostgreSQL rocks, except when it blocks: Understanding locks](https://www.citusdata.com/blog/2018/02/15/when-postgresql-blocks/)
- [Nickolay Ihalainen - PostgreSQL locking, Part 1: Row Locks](https://www.percona.com/blog/2018/10/16/postgresql-locking-part-1-row-locks/)
- [Nickolay Ihalainen - PostgreSQL locking, part 2: heavyweight locks](https://www.percona.com/blog/2018/10/24/postgresql-locking-part-2-heavyweight-locks/)
- [Nickolay Ihalainen - PostgreSQL locking, part 3: lightweight locks](https://www.percona.com/blog/2018/10/30/postgresql-locking-part-3-lightweight-locks/)

### JSON
- [PostgresPro - SQL/JSON patches committed to PostgreSQL 15!](https://postgrespro.com/blog/pgsql/5969433)

## Graph Usage
- [Apache AGE - Postgres extension - Graph database optimized for fast analysis and real-time data processing](https://github.com/apache/incubator-age)

## Keys
- [Supabase - Choosing a Postgres Primary Key](https://supabase.com/blog/choosing-a-postgres-primary-key)

## Testing
- [IntegreSQL - Manages isolated PostgreSQL databases for your integration tests](https://github.com/allaboutapps/integresql)

## Releases
- [Postgres 15 released!](https://www.postgresql.org/about/news/postgresql-15-released-2526/)
