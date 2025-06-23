## Codes of the ProVerif model of Mutual Enforcement Policy (MPE) Protocols

The ProVerif model of the protocols, proposed in the paper with title _"Policy Enforcement Protocols with Split Keys"_, can be found in this repository. This paper is submitted to MIST 2025.

# Protocol Models

We have to ProVerif models: 

1. *PolicyCheck_SIGN.pv* - Signature-based Mutual Policy Enforcement Protocol (MPE-SIGN)
2. *PolicyCheck_MAC.pv* - MAC-based Mutual Policy Enforcement Protocol (MPE-MAC)

# ProVerif 

ProVerif uses applied pi-calculus as a formal language, translates the protocol into a set of Horn clauses, and considers an unbounded number of sessions and an unbounded message space for the protocol analysis. The tool can detect attacks. If a protocol property cannot be proven, ProVerif attempts to construct an execution trace that contradicts that property. We utilize ProVerif to formally verify the security goals of our protocols.

For more information, [ProVerif Manual](https://bblanche.gitlabpages.inria.fr/proverif/manual.pdf) is available online.
