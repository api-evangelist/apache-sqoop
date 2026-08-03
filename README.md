# Apache Sqoop (apache-sqoop)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
