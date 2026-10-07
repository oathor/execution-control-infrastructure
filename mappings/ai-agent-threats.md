# AI agent threats and the Execution Boundary

Canonical page: [oathor.com/ai-agent-threats](https://oathor.com/ai-agent-threats). If this file and the website ever differ, the website prevails.

Prompt injection, agent hijacking, tool misuse and excessive agency take different routes to the same place: an action that becomes consequence. That point is the Execution Boundary, and the control relied upon there can be tested.

The Execution Boundary is the final control location before a requested digital action becomes operational, institutional, financial, legal or public consequence.

AI agents are one class of actor. Execution Control Infrastructure applies across consequential digital and autonomous systems, whatever the source of the action.

A system should not be the sole authority over its own consequential actions.

## How do you stop prompt injection or agent hijacking from causing harm?

A hijacked agent does not need new permissions. It acts with the permissions it already holds, so its requests can appear authorised. Instructions hidden in content, poisoned memory and drift from an agent’s intended function all reach consequence the same way: through an action.

The control relied upon at that point must sit outside the agent and beyond its reach.

**A decision point the agent calls, and is trusted to honour, remains inside the agent’s own authority.**

Questions that apply: [ECI-1](https://oathor.com/execution-control-infrastructure#eci-1), [ECI-2](https://oathor.com/execution-control-infrastructure#eci-2), [ECI-5](https://oathor.com/execution-control-infrastructure#eci-5).

OWASP reference: [ASI01 Agent Goal Hijack](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/); [ASI06 Memory & Context Poisoning](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/); [ASI10 Rogue Agents](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/); [LLM01:2025 Prompt Injection](https://genai.owasp.org/resource/owasp-top-10-for-llm-applications-2025/). MITRE ATLAS reference: [AML.T0051 LLM Prompt Injection](https://atlas.mitre.org/techniques/AML.T0051); [AML.T0080 AI Agent Context Poisoning](https://atlas.mitre.org/techniques/AML.T0080).

## What stops an AI agent from misusing its tools or exceeding its authority?

Tool misuse, excessive agency and privilege abuse share one feature: the agent is permitted to use the tool or the credential. Permission establishes what an agent may do. It does not decide whether this specific action is cleared to become consequence.

Least privilege reduces what an agent can reach. Within what it can reach, each consequential action still crosses the Execution Boundary.

**Permissioned, authenticated, approved or prepared does not necessarily mean cleared to become consequence.**

Questions that apply: [ECI-2](https://oathor.com/execution-control-infrastructure#eci-2), [ECI-5](https://oathor.com/execution-control-infrastructure#eci-5), [ECI-6](https://oathor.com/execution-control-infrastructure#eci-6).

OWASP reference: [ASI02 Tool Misuse and Exploitation](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/); [ASI03 Identity and Privilege Abuse](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/); [LLM06:2025 Excessive Agency](https://genai.owasp.org/resource/owasp-top-10-for-llm-applications-2025/). MITRE ATLAS reference: [AML.T0053 AI Agent Tool Invocation](https://atlas.mitre.org/techniques/AML.T0053); [AML.T0083 Credentials from AI Agent Configuration](https://atlas.mitre.org/techniques/AML.T0083); [AML.T0086 Exfiltration via AI Agent Tool Invocation](https://atlas.mitre.org/techniques/AML.T0086); [AML.T0101 Data Destruction via AI Agent Tool Invocation](https://atlas.mitre.org/techniques/AML.T0101).

## Can the provider of an agent or tool control whether its own agent’s actions proceed?

Agents run on models, tools and servers supplied by third parties. A compromised component acts with the agent’s access. Where the same provider also controls whether the agent’s actions proceed, the institution relies on that provider at the point of greatest consequence.

**Independence also requires that the determination is not controlled by the function or provider that operates or supplies the acting system.**

Questions that apply: [ECI-1](https://oathor.com/execution-control-infrastructure#eci-1), [ECI-3](https://oathor.com/execution-control-infrastructure#eci-3).

OWASP reference: [ASI04 Agentic Supply Chain Vulnerabilities](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/). MITRE ATLAS reference: [AML.T0010 AI Supply Chain Compromise](https://atlas.mitre.org/techniques/AML.T0010); [AML.T0110 AI Agent Tool Poisoning](https://atlas.mitre.org/techniques/AML.T0110).

## How do you stop a harmful agent action before it spreads?

Generated code can run with an agent’s privileges, messages between agents can be spoofed, and one agent’s action can trigger others across systems. After consequence, monitoring can identify the harm. It cannot prevent it.

Speed shortens the path to consequence. It does not remove the Execution Boundary.

**Only a cleared action proceeds.**

Questions that apply: [ECI-1](https://oathor.com/execution-control-infrastructure#eci-1), [ECI-4](https://oathor.com/execution-control-infrastructure#eci-4), [ECI-6](https://oathor.com/execution-control-infrastructure#eci-6).

OWASP reference: [ASI05 Unexpected Code Execution (RCE)](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/); [ASI07 Insecure Inter-Agent Communication](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/); [ASI08 Cascading Failures](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/). MITRE ATLAS reference: [AML.T0050 Command and Scripting Interpreter](https://atlas.mitre.org/techniques/AML.T0050).

## Is human approval enough to control an AI agent?

An agent can present its own output in a way that persuades the person approving it. Where approval rests on what the agent shows, the agent can satisfy the conditions of its own clearance.

Authority is measured by its effect on consequence, not by its proximity to the action.

**Permission, authentication, approval, authorisation or preparation do not by themselves constitute clearance.**

Questions that apply: [ECI-2](https://oathor.com/execution-control-infrastructure#eci-2), [ECI-5](https://oathor.com/execution-control-infrastructure#eci-5), [ECI-7](https://oathor.com/execution-control-infrastructure#eci-7).

OWASP reference: [ASI09 Human-Agent Trust Exploitation](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/). MITRE ATLAS reference: [AML.T0067 LLM Trusted Output Components Manipulation](https://atlas.mitre.org/techniques/AML.T0067).

## Two points when applying the test

If the actor can act without the control being applied, the control is within the reach of the actor. That is tested by ECI-2.

Under the definition of Independent Clearance Determination, only a cleared action proceeds. An action that proceeds without a determination was not cleared.

## Self-assessment

Use [`self-assessment.csv`](../self-assessment.csv) for any control relied upon at the Execution Boundary, under any name and from any provider. Record yes where the control meets the question and no where it does not, with the evidence and explanation for the answer. Leave both blank where the available evidence does not answer the question, and report it as silent. Apply each question with its application note ([`APPLICATION-NOTES.md`](../APPLICATION-NOTES.md)). Report the answer to each question, for example: yes on ECI-4 to ECI-7; no on ECI-2; silent on ECI-1 and ECI-3. Answers are reported together, not selectively. The test has no scores or levels.

A completed self-assessment is the record of the person who completed it. It is not an assessment, certification or endorsement by OATHOR LTD. The form may be completed, reproduced, incorporated into assessment or procurement materials, and shared for the purpose of applying the criteria, with credit to OATHOR LTD and a link to the canonical source, provided that the wording, identifiers and meaning of the criteria are not altered.

## Notes

- This is the analysis of OATHOR LTD. It describes what a control relied upon at the Execution Boundary must meet, not how any control works.
- OWASP and MITRE ATLAS identifiers and names are used for reference only. No association with, or endorsement by, OWASP or MITRE is implied.
- Machine-readable version: [`ai-agent-threats.json`](ai-agent-threats.json).
