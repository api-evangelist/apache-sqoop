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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
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
