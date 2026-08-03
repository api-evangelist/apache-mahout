# Apache Mahout (apache-mahout)

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

Apache Mahout is an open-source framework for building scalable machine learning applications. The project has evolved to include Qumat, a unified Python API for building quantum circuits that runs across multiple quantum backends including Qiskit, Cirq, and Amazon Braket, along with QDP for GPU-accelerated classical-to-quantum data encoding.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-mahout/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Distributed Computing, Machine Learning, Python, Quantum Computing, Scala

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Qumat
Qumat is a unified Python API for building and executing quantum circuits across multiple quantum computing backends including Qiskit, Cirq, and Amazon Braket. It provides a hardware-agnostic interface for quantum gate operations, parameterized circuits, measurement, and state vector retrieval.

**Human URL:** [https://mahout.apache.org/docs/qumat](https://mahout.apache.org/docs/qumat)

#### Tags:

 - Python, Quantum Computing, Quantum Circuits

#### Properties

- [Documentation](https://mahout.apache.org/docs/qumat)
- [APIReference](https://mahout.apache.org/docs/qumat/api)
- [GettingStarted](https://mahout.apache.org/docs/qumat/getting-started)
- [Python SDK (PyPI)](https://pypi.org/project/qumat/)
- [GitHubRepository](https://github.com/apache/mahout)

### Apache Mahout Samsara
Mahout Samsara is a distributed linear algebra DSL in Scala for building machine learning algorithms on Apache Spark. It provides matrix decompositions, collaborative filtering, clustering, and other algorithms as a mathematically expressive API.

**Human URL:** [https://mahout.apache.org/docs/latest/](https://mahout.apache.org/docs/latest/)

#### Tags:

 - Distributed Computing, Linear Algebra, Machine Learning, Scala, Spark

#### Properties

- [Documentation](https://mahout.apache.org/docs/latest/)
- [GitHubRepository](https://github.com/apache/mahout)

## Common Properties

- [Portal](https://mahout.apache.org/)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/mahout)
- [IssueTracker](https://issues.apache.org/jira/browse/MAHOUT)
- [MailingList](https://mahout.apache.org/docs/community/mailing-lists)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)

## Features

| Name | Description |
|------|-------------|
| Hardware-Agnostic Quantum API | Qumat provides a unified API that runs the same quantum circuit code on Qiskit, Cirq, and Amazon Braket backends without modification. |
| Quantum Gate Operations | Complete library of single-qubit gates (H, X, Y, Z, T, Rx, Ry, Rz, U) and multi-qubit gates (CNOT, Toffoli, SWAP, CSWAP). |
| Parameterized Quantum Circuits | Support for symbolic parameters in rotation gates for variational quantum algorithms and quantum machine learning. |
| GPU-Accelerated Data Encoding | QDP provides zero-copy tensor transfer for encoding classical data into quantum states with GPU acceleration. |
| Distributed Linear Algebra | Samsara DSL enables large-scale matrix operations distributed across Apache Spark clusters. |
| Collaborative Filtering | Distributed recommendation algorithms including ALS-based collaborative filtering for large-scale datasets. |
| Clustering | Distributed K-Means, fuzzy K-Means, and spectral clustering algorithms running on Spark. |
| Dimensionality Reduction | Distributed SVD, PCA, and random projection methods for large-scale feature reduction. |

## Use Cases

| Name | Description |
|------|-------------|
| Quantum Machine Learning | Build variational quantum algorithms and quantum neural networks using parameterized circuits via the Qumat API. |
| Quantum Algorithm Research | Prototype and test quantum algorithms across different hardware backends without rewriting circuit code. |
| Large-Scale Recommendation | Build distributed recommendation systems processing billions of user-item interactions using Mahout on Spark. |
| Distributed Clustering | Cluster large datasets using distributed K-Means and other algorithms running on Apache Spark. |

## Integrations

| Name | Description |
|------|-------------|
| Qiskit | IBM Qiskit quantum computing framework as a Qumat execution backend for IBM quantum hardware and simulators. |
| Cirq | Google Cirq quantum computing framework as a Qumat execution backend for Google quantum hardware. |
| Amazon Braket | AWS Braket quantum computing service as a Qumat execution backend for cloud quantum hardware. |
| Apache Spark | Primary distributed computing backend for Mahout Samsara linear algebra and machine learning algorithms. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
