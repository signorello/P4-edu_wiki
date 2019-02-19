
This project contains ideas for projects that can be completed during a one-day hackathon.
The projects are roughly divided to projects that enable people to practice P4 and projects that contribute to the P4 community, and are not necessarily written in P4.

***

**Title:** Multi-target applications

**Description:** One of the limitations of existing P4 code is that different architectures require different code. The goal of this project will be to take some existing P4 applications, written for a given architecture, and port it to other architectures. Recommended architectures include v1model, PSA and SimpleSumeSwitch, but all open-source architectures can be used. The code can then be used for educational purposes.

**Type (P4 Practice / Community Contribution):** Mainly P4 practice, but for a community contribution.

***

**Title:** P4Fun

**Description:** Implement a classic game in P4. Examples include tic-tac-toe, Battleship, and others.

**Type (P4 Practice / Community Contribution):** P4 practice. 

***

**Title:** PSA bug fixes

**Description:** The architecture workgroup requests assistance in fixing some of the bugs currently documented in [its issues list](https://github.com/p4lang/p4-spec/issues). Bug fixes are especially encouraged for PSA.

**Type (P4 Practice / Community Contribution):** Community contribution

**Proposed by:** Calin Cascaval 

***

**Title:** Improving NetCache and NetChain

**Description:** Improve the quality of the open source code of [NetCache](https://github.com/netx-repo/netcache-p4) and  [NetChain](https://github.com/netx-repo/netchain-p4).

Goal 1: Turn the code into a tutorial / programming assignment.

Goal 2: Add and improve documentation.

**Type (P4 Practice / Community Contribution):** Both!

**Proposed by:** Xin Jin

***


**Title:** Dynamic programming in P4

**Description:** Implement a dynamic programming exercise in P4, like subset string matching.

**Type:** P4 Practice 

***

**Title:** Using latest protobuf 

**Description:**  Users may have apps on their machine which use higher version of gRPC/protobuf which messes up p4c/P4Runtime. This project will try and have p4c and P4Runtime use as latest a protobuf version as possible. 

**Type:** Community Contribution

**Proposed by:** Hemant

***

**Title:** Tests for nested structs

**Description:** nested struct support is new in p4c p4runtime generation and PI server. The goal of this project is to develop more tests in p4c and PI.

**Type:** Community Contribution

**Proposed by:** Hemant

***

**Title:** More bug fixes

**Description:** various bug fixes requested by community members:

* [Support emit for struct in bmv2](https://github.com/p4lang/p4c/issues/1659)

* [Flexsai/p4](https://github.com/opencomputeproject/SAI/issues/896)

**Type:** Community Contribution

**Proposed by:** Hemant


***

**Title:** Network forwarding based on credential in packet.

**Type (P4 Practice / Community Contribution):** P4 Practice 

**Proposed by:** Mathias Kolehmainen


***

**Title:** Network coding or packet steering for distributed MIMO

**Type (P4 Practice / Community Contribution):** P4 Practice

**Proposed by:** Michael Sherman



***

**Title:** In-network security-violation detection

**Type (P4 Practice / Community Contribution):** P4 Practice

**Proposed by:** Bingzhe Liu



***

**Title:** Split/Merge Payload

**Description:** Implement a version of Split/Merge Payload. This is in VNF context where packet headers are processed separately from the payload. Consider a Firewall VNF deployed on the server. Here, ToR switch will only forward packet headers to the Firewall and keep the packet payload on ToR buffer. The payload is merged back to the packet once processed header comes back from the server. We have an NSDI poster on this with title "Cutting Packet Fat in Shallow VNF Chain Processing".

**Type (P4 Practice / Community Contribution):** P4 Practice

**Proposed by:** Nodir	Kodirov


***

## Template

**Title:**

**Description:** (2-5 sentences)

**Type (P4 Practice / Community Contribution):**

***