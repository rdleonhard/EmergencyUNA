# EmergencyUNA

**EmergencyUNA is an experimental legal-engineering repository for DAO governance and contingency planning.** It explores how a decentralized autonomous organization might preserve operational continuity and designate a forum, manager, and counsel if a court, regulator, or counterparty attempts to characterize the DAO as an unincorporated nonprofit association ("UNA").

> **Not legal advice.** This repository is for research, drafting, and educational experimentation only. It is not legal advice, does not create an attorney-client relationship, and should not be relied upon to form, operate, defend, or restructure any organization. DAOs, token holders, multisig participants, contributors, and developers should consult qualified counsel in every relevant jurisdiction before taking action.

## Why this matters

A DAO may not intend to be a legal entity. That does not prevent a plaintiff, regulator, court, or other third party from arguing that the DAO is an association of persons acting together for a common purpose. In an adverse proceeding, that characterization can matter because it may affect:

- who can be served with process;
- whether the DAO can appear through counsel;
- whether token holders, voters, delegates, developers, multisig signers, or other participants face personal-liability arguments;
- which jurisdiction's association law applies;
- whether the association has capacity to contract, hold property, appoint agents, or retain counsel; and
- whether governance has any emergency procedure for responding to litigation, regulatory action, treasury compromise, or protocol-level crisis.

EmergencyUNA is intended to help think through those problems before a crisis occurs.

## What is a UNA?

An unincorporated nonprofit association is generally a group of persons joined together by mutual consent for a nonprofit purpose, without having formed a corporation, LLC, foundation, trust, or other formal legal entity. Historically, many such associations lacked a legal identity distinct from their members, which created uncertainty around property ownership, contract capacity, litigation capacity, and member liability.

Modern statutes based on, or inspired by, the Uniform Unincorporated Nonprofit Association Act ("UUNAA") may give an UNA a more coherent legal status. Depending on the jurisdiction and statute, an UNA may be able to own property, contract, sue or be sued, appoint agents, and limit member liability for association obligations.

The exact result is jurisdiction-specific. The statute, case law, facts, governance records, member conduct, and applicable conflict-of-laws rules all matter.

## DAO-specific concern

DAOs create a hard version of the UNA problem. A DAO may have no board, no manager, no conventional registered agent, no entity wrapper, and no obvious person authorized to retain counsel. At the same time, it may have token holders, voters, delegates, multisig signers, developers, service providers, treasury assets, governance forums, protocol documentation, and public statements that an adversary may try to treat as evidence of association.

The Ooki DAO enforcement action highlighted the risk that a DAO may be treated as an unincorporated association for procedural or liability purposes. The more decentralized the DAO, the more important it becomes to have a credible emergency governance pathway for service, representation, treasury authorization, and litigation response.

## Project objective

The goal of this repository is to explore a framework under which a DAO can state, in advance:

1. it does **not** concede that it is a UNA or any other legal entity merely by publishing emergency procedures;
2. if a competent authority nevertheless characterizes it as a UNA, the DAO designates a fallback jurisdiction and procedural framework;
3. the DAO has an emergency method for appointing a manager, agent, or committee;
4. the DAO can authorize counsel to appear, defend, settle, or otherwise respond on behalf of the asserted association;
5. governance participants can distinguish emergency legal-defense authority from ordinary protocol governance; and
6. token holders, voters, and passive participants receive clearer notice of the intended limits of their role.

## Suggested repository structure

The project should evolve toward a structure like this:

```text
EmergencyUNA/
├── README.md                  # Project overview and warnings
├── docs/
│   ├── design-principles.md   # Goals, assumptions, and drafting posture
│   ├── jurisdiction-matrix.md # Statutory comparison by state/jurisdiction
│   └── threat-model.md        # Litigation/regulatory/treasury crisis scenarios
├── templates/
│   ├── emergency-una-resolution.md
│   ├── manager-appointment.md
│   ├── counsel-engagement-authority.md
│   └── no-admission-of-status.md
└── examples/
    └── sample-dao-emergency-process.md
```

## Drafting principles

Any future documents in this repository should preserve the following drafting posture:

- **No admission by publication.** A DAO should not accidentally concede entity status merely by preparing contingency documents.
- **Emergency-only authority.** Litigation-defense or crisis-response authority should be narrowly scoped and should not silently centralize ordinary governance.
- **Jurisdiction specificity.** Each statutory claim should be tied to a specific jurisdiction and verified against current law.
- **Role clarity.** Token holders, voters, delegates, multisig signers, contributors, and service providers should not be lumped together without analysis.
- **Counsel-first execution.** Any real-world use should be reviewed and tailored by qualified counsel before adoption.
- **Operational realism.** The framework should account for how DAOs actually coordinate: governance forums, Snapshot votes, on-chain proposals, multisigs, delegates, Discord/Telegram, and emergency security councils.

## Immediate next improvements

High-value next steps for this repository:

1. Add a jurisdiction matrix comparing states that have adopted UUNAA-style statutes.
2. Add model emergency resolutions with bracketed drafting notes.
3. Add a threat model for service of process, regulatory enforcement, treasury compromise, and protocol governance capture.
4. Add a disclaimer and contribution policy for legal-template pull requests.
5. Add citations to primary legal authorities and clearly separate law, commentary, and open questions.

## Contributing

Contributions are welcome, but legal templates require special care. A useful contribution should:

- cite primary authority where possible;
- distinguish statutory text from commentary;
- avoid presenting experimental language as settled law;
- identify the jurisdiction being discussed;
- include assumptions and open questions; and
- avoid uploading confidential client materials, privileged analysis, or non-public DAO communications.

## Status

Experimental. Not production-ready. Not a substitute for counsel.
