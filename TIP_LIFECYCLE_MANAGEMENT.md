# TIP Lifecycle Management

## Concept

### What is a TIP?
As we seek solutions for an interoperable digital trust marketplace, we must recognize that market dynamics will often drive solution incubation and adoption. In the context of a ToIP, *Market Dynamics* are the market forces that impact the validation and adoption behaviors of producers and consumers of a specific solution architectures.

A **ToIP Interoperability Profile (TIP)** is a specific type of specification produced by members of the Technical Stack WG ("TSWG"). Analogous to how cooking recipes are composed of specific ingredients, a TIP describes a target solution architecture that is based on a specific set of standards, protocols and technologies.

A TIP represents a solution architecture that once matured can be the basis for a market proven solution specification. TIPs can be designed, refined and supported by interoperable vendors.

A TIP definition will:

* articulate the motivating design principles behind the solution profile
* clearly position standards, protocols and software components (collectively, "technologies") against each layer of the [ToIP Technical Stack]().  
* demonstrate incubation activity towards the market adoption of the architecture using a set of *key adoption indicators (KAI)*.

As a TIP is incubated in the marketplace, several work-products will provide evidence of its maturation.

* **Core Principles**: Market requirements are necessary when combining technology to formulate a solution architecture.
* **White-paper**: Documentation outlining purpose, principles and architecture for the TIP.
* **Market Dynamics**:

    * **Adoption Metrics**: Use case correlation backed by case study references demonstrate adoption.
    * **Interoperability Testing**: Community driven certification of test cases and results.
    * **Vendor Support**: Vertical integration of the technical stack must be supported by vendors that can demonstrate the interoperability between vendor solutions that adhere to a common vertical architecture.

* **Best Practices**: Implementation guidance for adoption as well as recommendations for interlock with the Governance Stack.

### Why do we need TIPs?
Ultimately, entities (business, governments, organizations) that seek to participate in an interoperable digital trust marketplace will need to assess (compare) solution architectures. Analogous to a Request for Proposal (RFP) process, entities should be able to align their requirements with the principles and expectations described by a TIP and use such a comparison exercise to make educated decisions. Allow when to compare apples-to-apples and when necessary enable clear articulation of apples-to-oranges activities.

### Who would use a TIP?
As Ecosystem Projects (See Ecosystem Foundry WG) evolve they will need to define governance frameworks and select a TIP.

### What is the scope of interoperability for a TIP?
In a utopian world solution architectures would be interoperable both vertically and horizontally across the Technology Stack. But this is not the goal of ToIP and in fact at some layers of the technology Stack, horizontal interoperability is not even necessary.

For clarity, TIPs needs to first focus on vertical interoperability where the connecting of the technology components at each layer is seamless and well understood. Horizontal interoperability across TIPs is not important until we have 2 or more TIPs with enough market adoption to necessitate community energy.  

While horizontal interoperability at layer 3 (a wallet affiliated with TIP-A can exchange data with a wallet that supports TIP-B and both TIPs use different Layer 3 tech) would be important, the ability of a Layer 1 Utility based of on technology-A needing to exchange data with a Utility based on technology-B is less important.

## TSWG Responsibilities
The Technical Stack WG is responsible for the processes and procedures of the WG as well as the lifecycle of TIP incubation.

* **Stack Attributes**: One of the deliverables of the Tech Stack WG (TSWG) is to provide guidance on the type of technology that can (could) be considered applicable at each layer of the Technology Stack. Additionally, what the architectural requirements are for vertical interoperability between the layers. This work effort MUST be technology neutral.
* **TIP Criteria**: What are the requirements for proposing a TIP to the WG?
* **TIP Incubation**: Establishment and Management of the TIP Lifecycle Process
* **TIP Graduation**: Review and approval process for the formalization of a TIP into a recommendation (TSS?)

## Lifecycle Management Process
The ToIP Foundation, which is technology agnostic, represents a collaborative forum where solution “recipes” can be matured and vetted in the market.

* **Proposed**: Using a predefined template, propose a TIP to the TSWG to get the approval to establish a ToIP TIP repo.
* **Demonstrated**: incubate the TIP within the community to address the maturation criteria outlined by the TSWG.
* **Accepted**: The TSWG believes a TIP is worthy of a recommendation as a specification and the community has decided to formalize it as a recommendation.
* **Adopted**: The TIP has graduated to a formal recommendation.
* **Retired**: The proposers of the TIP have determined that the maturation process has failed or permanently stalled.

## Getting Started
[Discover exiting TIPs or learn how to create your own](./TIP_GETTING_STARTED.md).
