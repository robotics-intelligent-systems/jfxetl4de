# AI-Powered Data Engineering Platform

CayenneModeler is a complete GUI mapping tool that supports reverse-engineering. Titanoboa is a low-code workflow orchestration platform. Apache Camel Karavan a Low-code Data Integration Platform. λ-Sim converts simulation models into REST APIs. Dolly, a LLM trained on the Databricks Machine Learning Platform. MindsDB enables humans, AI, agents, and applications to get highly accurate answers across large scale data sources. OWL is a cutting-edge framework for multi-agent collaboration. SAND is an application to annotate semantic descriptions of tables. Pulsar is a distributed pub-sub messaging platform. Apache Fory is a blazingly-fast multi-language serialization framework. Pentaho Data Integration (ETL). Apache DolphinScheduler. Apache NiFi is a visual data flow based system. n8n is a workflow automation platform. Oryx 2 lambda architecture on Apache Spark and Kafka. SQLing build domain model from SQL file. Babelfish provides the capability for PostgreSQL to work with applications written for MSSQL. Logica is an open source declarative logic programming language for data manipulation. Coral is a SQL translation, analysis and rewrite engine. DuckDB is an analytical in-process SQL DBMS. SQLFlow is a compiler that compiles a SQL program to a workflow that runs on Kubernetes. SQLines Database Migration Tools. Obevo is a database deployment tool. Flyway is a database-migration tool. Bytebase is an open-source database DevOps tool. Apache Beam is a unified model for defining both batch and streaming data-parallel processing pipelines. Apache SeaweedFS is a fast distributed storage system. Airbyte is a data integration platform. OpenWhisk is a serverless functions platform. Apache Paimon is a lake format. Dremio is the Agentic Lakehouse. Hermes is an asynchronous message broker. Delta Lake is an open-source storage framework. MinIO is a high-performance, S3 compatible object store. Apache Hive data warehouse. Robot Framework is a generic open source automation framework

The directory structure includes a specific folder for each phase of development and engineering programs:

- __MBSE__: The root folder Arcadia (ARChitecture Analysis and Design Integrated Approach) is a method of tools dedicated to systems engineering and architecture, supported by the Capella modeling tool.    
  - __CAD__: For computer-aided design.
  - __CAM__: Dedicated to the part manufacturing and assembly process.
  - __CAS__: For simulation of end-to-end functionality and performance analysis.
  
# Free Software Dependencies

This document details the free and open-source software (FOSS) packages, libraries, and tools used in this project. It also includes their versions and corresponding license types to ensure legal compliance.

## 📌 License Summary
* **Permissive Licenses (MIT, Apache 2.0):** X packages.

* **Weak Licenses / Copyleft (LGPL, MPL):** X packages.

* **Strong Licenses (GPL):** X packages.

---

## 🛠️ System Dependencies
Global tools or environments required to run the project.

* **[Tool/Environment Name]**

* **Required Version:** >= X.X.X

* **License:** [e.g., MIT / Apache 2.0 / GPLv3]

* **Description:** Brief explanation of its use in the project.

* **Link:** [Official website or repository]

---

## 📦 Production (Runtime) Dependencies
Packages that are compiled or run directly in the production environment.

| Package | Version | License | Description / Use |

| :--- | :---: | :---: | :--- |

**[Package-Name-1]** | `^1.2.3` | MIT | HTTP request handling. |


**[Package-Name-2]** | `~4.0.0` | Apache 2.0 | Data processing and analysis. |


**[Package-Name-3]** | `>=2.5` | BSD 3-Clause | Graphical interface and visual components. |

---

## 🧪 Development Dependencies (DevDependencies)
Tools used only during the development, testing, or compilation phases.

| Package | Version | License | Description / Use |

| :--- | :---: | :---: | :--- |

**[Testing-Tool]** | `^5.0.0` | MIT | Framework for unit testing. |

**[Linter/Linter-Name]** | `^8.0.0` | Ext-MIT | Code formatting and static analysis. |

---

## ⚖️ Compliance and Auditing
To verify and keep this project's licenses up to date, we use the following automation tools:

* **Vulnerability Audits:** `[e.g., npm audit / pip-audit / cargo audit]`
* **License Scans:** `[e.g., FOSSA / LicenseFinder / Snyk]`

---

## 📝 Contribution Notes
If you want to add a new dependency to the project:
1. Make sure the license is **compatible** with this project's main license.

2. Avoid dependencies with highly restrictive licenses (strong copyleft) unless approved by the team.

3. Update this file (`DEPENDENCIES.md`) along with your pull request.
