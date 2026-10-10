# Execution Control Infrastructure: definitions and criteria

Public reference materials: canonical definitions, the seven criteria questions (ECI-1 to ECI-7) and application notes for **Execution Control Infrastructure**, the category originated by [OATHOR LTD](https://oathor.com), Abu Dhabi Global Market.

Execution Control Infrastructure applies across consequential digital and autonomous systems, whatever the source of the action. AI agents are one class of actor.

Execution Control Infrastructure first defined May 2026 in the Foundation Paper, Version 1.0, by OATHOR LTD. The criteria were first set out in that paper; ECI-2 and ECI-3 follow the definition of independence published 24 September 2026.

The canonical source is [oathor.com/execution-control-infrastructure](https://oathor.com/execution-control-infrastructure). If this repository and the website ever differ, the website prevails.

## AI agent threats and the self-assessment

[`mappings/ai-agent-threats.md`](mappings/ai-agent-threats.md) shows where prompt injection, agent hijacking, tool misuse, excessive agency, supply chain compromise and the exploitation of human approval become consequence, and which of ECI-1 to ECI-7 test the control relied upon at that point, with OWASP and MITRE ATLAS references. Canonical page: [oathor.com/ai-agent-threats](https://oathor.com/ai-agent-threats).

[`self-assessment.csv`](self-assessment.csv) is a form for assessing any control against the seven questions, with evidence and explanation for each answer. A completed self-assessment is the record of the person who completed it. It is not an assessment, certification or endorsement by OATHOR LTD.

[`APPLICATION-NOTES.md`](APPLICATION-NOTES.md) explains how each question is applied. The notes do not modify, replace or extend the criteria. Canonical page: [oathor.com/execution-control#application-notes](https://oathor.com/execution-control#application-notes).

## Stewardship

OATHOR LTD maintains the criteria for Execution Control Infrastructure. The seven questions are fixed in number, order and wording, and each has a permanent identifier, ECI-1 to ECI-7. They apply to any control, under any name, from any provider. The test decides, not the label. The test does not prescribe any product or implementation.

## Definitions

**Execution Control Infrastructure.** Execution Control Infrastructure is the independent control layer that governs the Execution Boundary and determines whether a consequential action is cleared to proceed. ([source](https://oathor.com/execution-control-infrastructure))

**Execution Boundary.** The Execution Boundary is the final control location before a requested digital action becomes operational, institutional, financial, legal or public consequence. ([source](https://oathor.com/category-reference))

**Independent Clearance Determination.** Independent Clearance Determination is the control function within Execution Control Infrastructure: the independent determination, made at the Execution Boundary and before consequence, of whether a consequential action is cleared to proceed. Only a cleared action proceeds. ([source](https://oathor.com/category-reference))

**Independence.** Independence is the structural separation between the system seeking to create a consequence and the control layer that determines whether that consequence may proceed. A clearance determination is independent when the actor seeking execution cannot, by virtue of being the actor, unilaterally determine, alter, satisfy, bypass or substitute the conditions under which its own consequential action is cleared to proceed. Independence also requires that the determination is not controlled by the function or provider that operates or supplies the acting system. ([source](https://oathor.com/execution-control-infrastructure#independence-definition))

**Human Authority Layer.** The Human Authority Layer is the requirement that accountable human authority remains effective as systems act with increasing autonomy. Execution Control Infrastructure is the independent control layer at the Execution Boundary. ([source](https://oathor.com/category-reference))

## Principles

- Permissioned, authenticated, approved or prepared does not necessarily mean cleared to become consequence.
- A system should not be the sole authority over its own consequential actions.

## The test: seven questions

| ID | Question |
|---|---|
| [ECI-1](https://oathor.com/execution-control-infrastructure#eci-1) | Is the determination made outside the system that takes the action? |
| [ECI-2](https://oathor.com/execution-control-infrastructure#eci-2) | Is it beyond the reach of the actor, so that the actor cannot determine, alter, satisfy, bypass or substitute the conditions of its own clearance? |
| [ECI-3](https://oathor.com/execution-control-infrastructure#eci-3) | Is it free of control by the function or provider that operates or supplies the acting system? |
| [ECI-4](https://oathor.com/execution-control-infrastructure#eci-4) | Is it made before consequence exists, while the action is still preventable? |
| [ECI-5](https://oathor.com/execution-control-infrastructure#eci-5) | Does it decide whether this specific action is cleared to become consequence, or only whether the actor is permitted? |
| [ECI-6](https://oathor.com/execution-control-infrastructure#eci-6) | Is it applied at the Execution Boundary as a matter of course, not only as an occasional review or exception? |
| [ECI-7](https://oathor.com/execution-control-infrastructure#eci-7) | Is the record created at the moment of determination, rather than reconstructed afterwards? |

A control that answers yes to all seven meets the criteria for Execution Control Infrastructure. A control that answers no to any of the first three remains inside the authority of the system it governs.

Machine-readable version: [`criteria.json`](criteria.json).

## How to cite

```
OATHOR LTD. "ECI-n." Criteria for Execution Control Infrastructure. https://oathor.com/execution-control-infrastructure#eci-n
```

Replace n with 1 to 7.

More citation formats: [oathor.com/cite](https://oathor.com/cite)

## Public record

- Foundation Paper, Version 1.0, May 2026: [oathor.com/whitepaper](https://oathor.com/whitepaper)
- Comment to the Basel Committee on Banking Supervision, 25 June 2026, hosted by the BIS: [bis.org](https://www.bis.org/2026-07/oathorltd.pdf)
- Response published by the Financial Stability Board, 6 August 2026: [fsb.org](https://www.fsb.org/uploads/OATHOR-Ltd.pdf)
- Wikidata: [OATHOR LTD (Q141636063)](https://www.wikidata.org/wiki/Q141636063), [Execution Control Infrastructure (Q141636104)](https://www.wikidata.org/wiki/Q141636104)

Publication of a consultation response by the Basel Committee, the BIS or the FSB is a public record, not an endorsement.
Research paper, Independent Clearance Before Consequence, Version 1.0, October 2026: [oathor.com/research](https://oathor.com/research#independent-clearance-before-consequence) · DOI: [10.2139/ssrn.7584298](https://doi.org/10.2139/ssrn.7584298)

## Permission to reproduce

OATHOR LTD permits reproduction of its canonical definitions of Execution Control Infrastructure, Execution Boundary, Independent Clearance Determination, Independence and Human Authority Layer, and of the criteria questions ECI-1 to ECI-7, including in commercial contexts, provided that the wording is reproduced unchanged, OATHOR LTD is clearly credited, and the applicable canonical OATHOR source is linked or, where a link cannot be given, cited by URL. The identifiers ECI-1 to ECI-7 may be used only to refer to the corresponding questions exactly as published by OATHOR LTD. The self-assessment form published by OATHOR LTD, including self-assessment.csv, may be completed, reproduced, incorporated into assessment or procurement materials, and shared for the purpose of applying the criteria, with the credit and link required above, provided that the wording, identifiers and meaning of the criteria are not altered. Translation or other adaptation requires the written permission of OATHOR LTD. No one may state or imply that an assessment, product, service or organisation is certified, approved or endorsed by OATHOR LTD without its written permission.

The application notes and the threat analysis in the mappings folder may be quoted with attribution to OATHOR LTD and a link to the canonical page. OWASP and MITRE ATLAS identifiers and names are used for reference only.

The full and governing text is at [oathor.com/terms#licence](https://oathor.com/terms#licence). See also [LICENSE.md](LICENSE.md).
