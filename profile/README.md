![DriftlessAF logo](./logo/horizontal/driftlessaf-bl-horizontal.png)

# DriftlessAF

DriftlessAF is an agentic framework that enables bots to use traditional and
agentic AI eval approaches for reconciliation automation at massive scale.

DriftlessAF consists of Terraform modules for the event-driven reconciliation
infrastructure and Go packages for the agentic foundation. 

The Terraform modules include the generic core reconciler, a multi-regional work
queue, and a reconciler for resources at specific paths in GitHub repositories.

The Go packages include executors for Google Gemini and Anthropic Claude,
evaluators for tracing and metrics, and Go libraries to facilitate
reconciliation across GitHub repositories, OCI containers, and APK packages.

Using DriftlessAF you can configure the desired state, configure reconciler
bots, and affected system, such as source code in GitHub repositories. The
framework can then monitor state and the traditional and agentic AI reconciler
bots can queue work items and the automated processing will avoid any drift off
the desired state.

## Practical use

Chainguard uses DriftlessAF as the foundation for numerous custom reconciler
bots in Chainguard Factory. The factory is used to build and maintain over 2000
unique containers, hundreds of thousands of package versions, and hundreds of
CVE patch backports. DriftlessAF replaces a legacy event-driven architecture and
is critical to achieve the necessary efficiency and reliability at scale. 

The work queue is fed by events and tackled by a large number of bots. They
constantly reconcile the discovered state changes from code repositories,
security feeds, and other sources to the desired state - up to date containers
with zero known CVEs. 

## Projects

* [terraform-infra-reconcilers](https://github.com/driftlessaf/terraform-infra-reconcilers)
  provides Terraform modules for the reconciler infrastructure
* [go-driftlessaf](https://github.com/driftlessaf/go-driftlessaf) provides Go
  implementations for LLM execution and evaluation in the framework and
  libraries to facilitate reconciliation across GitHub repositories, OCI
  containers, and APK packages.

## Open source and community

The DriftlessAF open source project provides a production-grade framework for your
own use. Note that the project is primarily offered for read-only access,
inspection, and expansion with your own bots for your specific use cases.

We currently do not have plans for community calls or active community
development. Contact us if you use DriftlessAF or are interested in further
collaboration and contribution.

## Contact

* Find us to chat live on the `questions` channel in the [Chainguard Community
  on Slack](https://communityinviter.com/apps/chainguardcommunity/invite)
* Ask questions and discuss related topics such as bug fixes or feature
  proposals on [GitHub
  discussions](https://github.com/orgs/driftlessaf/discussions)

## Logos

Black:

<img src="./logo/black/driftlessaf-b-216.png" alt="DriflessAF black Logo" height="72"/>

* [32px](./logo/black/driftlessaf-b-32.png)
* [216px](./logo/black/driftlessaf-b-216.png)
* [512px](./logo/black/driftlessaf-b-512.png)
* [1080px](./logo/black/driftlessaf-b-1080.png)

Blurple:

<img src="./logo/blurple/driftlessaf-bl-216.png" alt="DriflessAF blurple Logo" height="72"/>

* [32px](./logo/blurple/driftlessaf-bl-32.png)
* [216px](./logo/blurple/driftlessaf-bl-216.png)
* [512px](./logo/blurple/driftlessaf-bl-512.png)
* [1080px](./logo/blurple/driftlessaf-bl-1080.png)

White:

<img src="./logo/white/driftlessaf-w-216.png" alt="DriflessAF white logo" height="72"/>

* [32px](./logo/white/driftlessaf-w-32.png)
* [216px](./logo/white/driftlessaf-w-216.png)
* [512px](./logo/white/driftlessaf-w-512.png)
* [1080px](./logo/white/driftlessaf-w-1080.png)

Decorative:

<img src="./logo/decorative/driftlessaf-b-decorative.png" alt="DriflessAF decorative black logo" height="72"/>
<img src="./logo/decorative/driftlessaf-w-decorative.png" alt="DriflessAF decorative white logo" height="72"/>

Horizontal:

<img src="./logo/horizontal/driftlessaf-b-horizontal.png" alt="DriftlessAF black horizontal logo" height="72"/>
<img src="./logo/horizontal/driftlessaf-bl-horizontal.png" alt="DriftlessAF blurple horizontal logo" height="72"/>
<img src="./logo/horizontal/driftlessaf-w-horizontal.png" alt="DriftlessAF white horizontal logo" height="72"/>
