# Apache Sqoop (apache-sqoop)
Apache Sqoop is a command-line tool designed for efficiently transferring bulk data between Apache Hadoop and structured data stores such as relational databases. Note: Apache Sqoop has been retired to the Apache Attic as of 2021. Users are encouraged to migrate to Apache Spark or Apache NiFi.

**URL:** [https://sqoop.apache.org/](https://sqoop.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Big Data, Data Transfer, ETL, Hadoop, RDBMS, Retired

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Sqoop CLI
Apache Sqoop provides a command-line interface for bulk data transfer between Hadoop and relational databases including sqoop-import, sqoop-export, sqoop-job, and sqoop-eval commands.

**Human URL:** [https://sqoop.apache.org/docs/1.4.7/SqoopUserGuide.html](https://sqoop.apache.org/docs/1.4.7/SqoopUserGuide.html)

#### Tags:

 - CLI, Data Transfer, ETL, Hadoop, RDBMS

#### Properties

- [Documentation](https://sqoop.apache.org/docs/1.4.7/SqoopUserGuide.html)

## Common Properties

- [GitHubRepository](https://github.com/apache/sqoop)
- [Documentation](https://sqoop.apache.org/docs/1.4.7/)
- [Portal](https://sqoop.apache.org/)
- [TermsOfService](https://www.apache.org/licenses/)

## Features

| Name | Description |
|------|-------------|
| Bulk Import | High-throughput parallel import from RDBMS to HDFS, Hive, or HBase. |
| Bulk Export | Export data from HDFS back to relational database tables. |
| Incremental Loads | Delta-based incremental loading using append or lastmodified strategies. |
| Direct Import Mode | Native database utility-based transfers for MySQL and PostgreSQL. |
| Hive Integration | Auto-create Hive tables and load imported data directly into Hive. |

## Use Cases

| Name | Description |
|------|-------------|
| Data Warehouse Loading | Load relational database data into Hadoop-based data warehouses. |
| Database Offloading | Move historical data from RDBMS to HDFS for cost-effective storage. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Hadoop | Primary target storage for Sqoop imports via HDFS. |
| Apache Hive | Create and populate Hive tables from RDBMS imports. |
| MySQL | MySQL JDBC and direct mysqldump-based connector. |
| Oracle | Oracle JDBC connector for enterprise database data transfer. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
