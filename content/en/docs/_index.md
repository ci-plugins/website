
---
title: "BKCI Documentation"
linkTitle: "Documentation"
weight: 20
menu:
  main:
    weight: 20
---

a free & open source CI server, bk-ci(BlueKing Continuous Integration) helps you automate your build-test-release workflows, continuous delivery of your product faster, easier, with fewer bugs.

bk-ci removes all the tedious tasks in R&D process and enables you to focus on coding. It is often used for:

- Project compilation
- Static code analysis
- Running test cases to find bugs in time
- Deployment and release

bk-ci provides five core services, namely Process, Repository, Ticket, Environment and Store. They can be combined in multiple ways to meet business needs in different scenarios.

- **Process**: It visualizes current R&D process of the team. One pipeline can handle compilation, testing and deployment.
- **Repository**: It links current source code hosting service of the enterprise to bk-ci.
- **Ticket**: It provides the management of various kinds of tickets and certificates for services like Repository and Process.
- **Environment**: It can host the internal agents of the enterprise on bk-ci.
- **Store**: It consists of pipeline plugins and pipeline templates. Plugins are used to integrate with various third-party services of the enterprise and templates help to standardize its internal R&D process.

## Overview

- [Architecture](docs/overview/architecture.en.md)
- [Code Directory](docs/overview/code_framework.en.md)
- [Design](docs/overview/design.en.md)

## Features

- Continuous integration and continuous delivery: Due to the scalability of the framework, bk-ci can not only be used in simple CI scenarios, but also as the continuous delivery center of all the projects of the enterprise.
- What you see is what you get: bk-ci provides flexible and visualized pipelines for you to orchestrate. Move your fingers and you can describe the R&D process here.
- Parallel and scalable framework: The flexible framework can be scaled horizontally at will to meet the enterprise’s need for large-scale use.
- Distributed system: bk-ci can manage multiple agents easily to help you perform cross-platform build, testing and deployment in a faster manner.
- Pipeline plugins: bk-ci has a complete plugin development system with properties like low barrier to entry and scalability.
- Pipeline templates: It promotes the standardization of R&D within the enterprise.

## Experience

- [bk-ci in docker](https://hub.docker.com/r/blueking/bk-ci)

## Getting started

- [Download and Compile](docs/overview/source_compile.en.md)
- [Install and Deploy Within One Minute](docs/overview/installation.en.md)
