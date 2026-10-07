# Application notes for ECI-1 to ECI-7

Canonical page: [oathor.com/execution-control#application-notes](https://oathor.com/execution-control#application-notes). If this file and the website ever differ, the website prevails.

These application notes explain how ECI-1 to ECI-7 are applied. They do not modify, replace or extend the criteria. Where there is any inconsistency, the published criteria control. The notes are read with the definitions of the Execution Boundary, Independent Clearance Determination and Independence, and do not prescribe any product or implementation.

## Applying all seven questions

G1. The questions apply to the control relied upon at the Execution Boundary for a consequential action, whatever the source of the action and whatever the control is called. Where an action is delegated, they apply to the action that becomes consequence, and the acting system includes every system in the chain of delegation. The assessor records which control is relied upon for each type of consequential action.

G2. Each question is answered for the control as it operates, not only as designed, including when the control or the acting system fails, is unavailable or is being updated.

G3. Where a component other than the control, including one that establishes the identity of the actor or the action, can set, change, satisfy, bypass or override the conditions or the outcome of the determination, that ability is taken into account in answering each question. Shared infrastructure, such as hosting, networks or identity services, is relevant only where it gives that ability to the actor or to the function or provider that operates or supplies the acting system.

G4. An answer is yes only where documentation, configuration, testing or records of operation show that the condition is met, and no where they show that it is not met. Otherwise the answer is silent: the available evidence does not yet answer the question. Silent is not a result of the test; it records what the evidence shows. Assertions from the actor or its provider, without supporting evidence, do not by themselves establish a yes.

G5. A yes to one question does not compensate for a no to another.

G6. A control that answers yes to all seven meets the criteria for Execution Control Infrastructure. A control that answers no to any of the first three remains inside the authority of the system it governs. Every answer, including silent, is reported as given.

## ECI-1
Question: Is the determination made outside the system that takes the action?
Note: The system that takes the action includes every component that requests, prepares or carries out the action, such as models, agents, workflows, orchestration, tools, memory and the runtime in which they execute, and any person who acts as or for that system. A component does not become outside that system by being separately named, separately deployed or described as a separate layer. A control does not become part of that system only because the action passes through it.

## ECI-2
Question: Is it beyond the reach of the actor, so that the actor cannot determine, alter, satisfy, bypass or substitute the conditions of its own clearance?
Note: The actor includes the acting system, anyone who requests the action or directs the acting system in preparing or carrying it out, and instructions or content the acting system receives. A function independent of the acting system that sets the conditions is not the actor. The answer is no where the actor, by virtue of being the actor, can determine, alter, satisfy, bypass or substitute the conditions of its own clearance, including where an action can proceed without the control being applied or when no determination is made.

## ECI-3
Question: Is it free of control by the function or provider that operates or supplies the acting system?
Note: Control means the practical ability to set, change, suspend or override the conditions or the outcome of the determination. A relationship alone is not control: an organisation or provider may host, integrate, support or supply technology used in the arrangement without controlling the determination. The question applies to the internal function that operates the acting system and to its external provider, where either holds that ability. A provider that neither operates nor supplies the acting system is not within this question. Whether an arrangement meets the criteria depends on the actual allocation of authority and control, not on who supplied the technology.

## ECI-4
Question: Is it made before consequence exists, while the action is still preventable?
Note: Consequence includes any operational, institutional, financial, legal or public effect of the action. A preparatory step that has such an effect outside the acting system, and that refusing the action cannot undo, such as data disclosed to a third party or a commitment communicated, is a consequential action in its own right, to which the questions apply, and the assessor records the control relied upon for it. Where a single action is carried out in several steps, the determination precedes the first step that is consequence.

## ECI-5
Question: Does it decide whether this specific action is cleared to become consequence, or only whether the actor is permitted?
Note: The determination concerns the specific action, with its actual parameters, at the time it is to proceed. A permission, approval, mandate, policy or session covering a class of actions does not by itself answer this question. The determination must resolve whether the action that becomes consequence is cleared.

## ECI-6
Question: Is it applied at the Execution Boundary as a matter of course, not only as an occasional review or exception?
Note: As a matter of course means that every consequential action of each type for which the control is relied upon (G1) reaches the determination, without depending on sampling, on the actor's choice or on an exception being detected. A label such as low-risk or routine does not by itself take an action outside the questions where the action otherwise becomes consequence, whoever applies the label. Any exclusion by value, type or other condition is recorded with the answer. Where an excluded consequential action falls within the class of actions for which the control is relied upon, the answer is no.

## ECI-7
Question: Is the record created at the moment of determination, rather than reconstructed afterwards?
Note: The record must be created contemporaneously with the determination and must identify the determination sufficiently to show that it existed at that time.
