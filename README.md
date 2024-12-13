\# KubeCraft

\[!\[Go Report Card\](<https://goreportcard.com/badge/github.com/partha-architect/KubeCraft)\](https://goreportcard.com/report/github.com/partha-architect/KubeCraft)> !\[GitHub release (latest SemVer)\](<https://img.shields.io/github/v/release/partha-architect/KubeCraft?sort=semver>)

&lt;img src="<https://github.com/kubernetes/kubernetes/raw/master/logo/logo.png>" width="100"&gt;

\---

KubeCraft is a streamlined version of Kubernetes designed for developers and enthusiasts who want to understand, explore, or modify Kubernetes core concepts. It includes key directories for core functionalities such as builds, clusters, commands, and third-party integrations.

This repository is a public fork of Kubernetes with a reduced structure, allowing for easier navigation and customization. It retains essential components while excluding files unrelated to the focus of this repository.

\---

\## Key Features

\- Simplified structure with essential directories for development and learning.

\- Focused on providing clarity in Kubernetes core components like `cmd`, `build`, `docs`, and `cluster`.

\- Easy to fork, modify, and use in custom projects.

\---

\## Repository Overview

\### Directory Structure

\- **build/**: Contains scripts and resources for building Kubernetes components.

\- **cluster/**: Includes cluster-specific scripts and tools for deployment.

\- **cmd/**: Entry points for Kubernetes commands.

\- **docs/**: Documentation related to Kubernetes.

\- **hack/**: Utility scripts for testing and development.

\- **third_party/**: External dependencies and third-party integrations.

\### Repository URL

This repository is public and available at:

\[<https://github.com/partha-architect/KubeCraft.git\](https://github.com/partha-architect/KubeCraft.git)>

\---

\## To Start Using KubeCraft

\### Requirements

Ensure you have the following installed:

\- **Go** (refer to \[Go installation guide\](<https://go.dev/doc/install>))

\- **Docker** (refer to \[Docker installation guide\](<https://docs.docker.com/engine>))

\### Steps to Build and Run

\#### Using Go Environment:

\`\`\`bash

git clone <https://github.com/partha-architect/KubeCraft.git>

cd KubeCraft

make

\`\`\`

\#### Using Docker Environment:

\`\`\`bash

git clone <https://github.com/partha-architect/KubeCraft.git>

cd KubeCraft

make quick-release

\`\`\`

\---

\## Contributing to KubeCraft

This repository welcomes contributions! If you would like to contribute:

1\. Fork the repository.

2\. Create a feature branch.

3\. Make your changes.

4\. Submit a pull request.

\---

\## Support

If you encounter issues, please check the \[Kubernetes troubleshooting guide\](<https://kubernetes.io/docs/tasks/debug/>) or open an issue in this repository.

\---

\## Governance and Roadmap

This project follows the principles of Kubernetes governance. For more details, see the \[Kubernetes Governance Model\](<https://github.com/kubernetes/community/blob/master/governance.md>).

The roadmap for this project is aligned with Kubernetes' core development goals, with a focus on providing a learning-friendly version of Kubernetes.