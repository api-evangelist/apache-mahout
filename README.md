# Apache Mahout (apache-mahout)
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
