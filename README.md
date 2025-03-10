# EDC Samples

This repository provides samples for the Eclipse Dataspace Components (EDC) project, that aim to support the
onboarding process for new community members. The samples are sorted by scope for easy navigation and serve as a
step-by-step guide for getting familiar with the project. The code and a detailed documentation for each sample reside
in the respective module.

## Prerequisites

The samples assume a working knowledge of the **EDC nomenclature**. If you do not know about the EDC nomenclature we
strongly advise reading the [documentation](https://eclipse-edc.github.io/docs/#/) and/or watching the
[introductory videos](https://www.youtube.com/@eclipsedataspaceconnector9622/featured).

Also, a working knowledge of **Git**, **Gradle**, **Java** and **HTTP** is presumed.

We'll assume that you've just checked out the samples code base and have **Java 17+** installed on your development
machine. If not, please download and install JDK 17+ for your OS.

Command examples in this document will use the `bash` syntax and use Unix-style paths, but any other shell should be
fine as well. If you're using Windows you either need to adapt the paths or use WSL2.

## Scopes

The samples are separated by scope, where each scope has a different focus. Depending on what you want to learn more
about, you can choose the scope to look at. More scopes may be added in the future, so be sure to check back regularly.

> **If you are new to the project, it is advisable to start with the `basic` scope. The samples in this scope teach the
> very basics about using the EDC framework, which are presupposed in all other scopes!**

### [Basic](./basic/README.md)

The samples in this scope teach you how to get started with the EDC framework. You will e.g. learn how to set up and run
a connector and how to create your own extensions. What you learn here will be used in all other samples. Click the
link above to learn about the basic samples in more detail.

All basic samples are located in the `basic` directory.

### [Transfer](./transfer/README.md)

This scope revolves around the topic of data transfer. In these samples you will learn how a data transfer works in the
EDC and run different transfer scenarios. Click the link above to learn about the transfer samples in more detail.

All transfer samples are located in the `transfer` directory.

### [Advanced](./advanced/README.md)

Collection of advanced topics regarding the EDC framework.
Click the link above to learn about the transfer samples in more detail.

All transfer samples are located in the `advanced` directory.

### [Policy](./policy/README.md)

These samples deal with the topic of policies and their evaluation and enforcement. They will teach you what
configurations you need to make to enable the evaluation of specific policy rules and constraint and how to provide
custom code for their enforcement.

All policy samples are located in the `policy` directory.

### [Federated Catalog](./federated-catalog/README.md)

These samples focus on the implementation of federated catalogs, covering scenarios such as deploying it as 
a standalone runtime or as part of a connector. This also includes demonstration of how to implement a target 
node resolver, which resolves the participant connectors in the dataspace and crawls these connectors to compile 
a set of all offered catalogs.

All federated catalog samples are located in the [`federated-catalog`](./federated-catalog/README.md) directory.

## Contributing

See [how to contribute](https://github.com/eclipse-edc/docs/blob/main/CONTRIBUTING.md).

## License

This project is licensed under the Apache License 2.0 - see [here](LICENSE) for details.
