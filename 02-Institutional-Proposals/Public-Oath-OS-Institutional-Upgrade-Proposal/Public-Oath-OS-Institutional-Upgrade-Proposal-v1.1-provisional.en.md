# National Institutional Upgrade Proposal through a Notarized Oath OS

**Public Oath OS — v1.1-provisional**

> This document presents a provisional institutional design proposal developed primarily on the basis of existing Japanese institutions.
> It does not provide a definitive interpretation of current law, a legal assessment of any individual case, or a completed institutional framework that can be implemented immediately.
> Any reference to or implementation of this proposal in another country or jurisdiction requires reconsideration and redesign in accordance with the applicable constitution, laws, administrative system, judicial system, authentication framework, and social environment.

---

## 0. Summary

This proposal seeks to reposition the oath as a common protocol at the level of a national institutional OS by rediscovering and reallocating existing institutional resources, including:

* the notarial system and notary offices;
* existing stamp-duty and fee-collection systems;
* the Nationality Act;
* election laws;
* the Political Funds Control Act;
* the National Public Service Act;
* the Penal Code; and
* other administrative, judicial, and authentication systems.

The purpose of this proposal is to bootstrap structures for transparency, loyalty, accountability, and the evidentiary assessment of intent while minimizing additional costs through the use of existing institutions.

This OS consists of the following layers:

* Core Principles;
* Oath Protocol Types: OP-L1 to OP-L3;
* Architecture: Physical / Digital Twin / Trust Badge / Modules;
* I/O Design: Triggers and Three-Way Synchronization;
* Oath-Breach State Machine: S0 to S3;
* Abstract Responsibility Rules for Strong-Presumption Facts;
* Anti-Fragility: resistance to attack and misuse; and
* Transition and Implementation Framework.

---

## 1. Core Principles

### 1.1 Transparency Core

The system seeks to minimize areas associated with public office or public authority that are left invisible, including:

* interests and conflicts of interest;
* funding;
* loyalty;
* access to information; and
* intent and purpose.

However, this OS is not intended to establish comprehensive surveillance.

Its focus is limited to falsehood, betrayal, unauthorized disclosure of confidential information, and other misconduct capable of causing serious harm to public institutions or the survival and trust of the relevant community.

---

### 1.2 Oath Protocol

Through a notarized oath or another oath procedure with adequate assurance of authenticity, an oath-taker may be required to make explicit commitments such as:

* not intentionally making false statements;
* not engaging in acts of betrayal; and
* not unlawfully disclosing confidential information.

This creates a record showing that the oath-taker understood and voluntarily accepted the relevant standards of conduct in advance.

Where a later act appears inconsistent with the oath, this record may form a Strong-Presumption Fact relevant to the assessment of intent, knowledge, accountability, or other matters.

The existence of an oath alone does not automatically establish intent, illegality, or legal liability under any applicable law.

---

### 1.3 Accountability Bond

The OS incorporates an accountability obligation that is automatically triggered when reasonable grounds for doubt arise.

A person holding a certain public position, exercising public authority, or possessing access to high-risk information must provide a coherent explanation within a reasonable period when reasonable grounds arise to question the consistency between that person’s conduct and the oath.

This obligation is not intended to establish liability immediately.

Its purpose is to enable clarification, provide an opportunity for rebuttal, organize the relevant facts, and connect the matter to an appropriate decision-making procedure.

---

### 1.4 Non-Coercive Upgrade

An oath should not be designed as a tool for punishment or labeling.

Instead, it should operate as a voluntary upgrade structure in which:

> Taking the oath becomes rationally beneficial, while the rational basis for refusing it gradually diminishes over time.

Within voluntary-oath and Trust Badge contexts, completion of an oath should be treated as positive information, while the absence of an oath should not, by itself, be treated as negative information.

Where an oath is legally or institutionally required as a condition of appointment, qualification, naturalization, or another procedure, failure to complete the oath should be treated separately as a failure to satisfy a procedural requirement, rather than as a judgment of personal character.

---

### 1.5 Strong-Fact Handling Principle

A Strong-Presumption Fact relating to a possible oath breach is a powerful fact capable of producing substantial social, institutional, and legal consequences.

Accordingly, any actor that handles such a fact arbitrarily, inaccurately, or conclusively without sufficiently verifying its content, scope, or procedural status should bear a reasonable duty of explanation, regardless of whether that actor is:

* public or private;
* an individual or an organization; or
* a media entity or another information distributor.

Further details are provided in Section 6, “Abstract Responsibility Rules for Strong-Presumption Facts.”

---

## 2. Oath Protocol Types

The internal specification of this OS classifies oath protocols into the following three layers:

* OP-L1: Base Protocols;
* OP-L2: Position-Specific Protocols; and
* OP-L3: Contextual Protocols.

---

### 2.1 OP-L1: Base Protocols

These protocols constitute the common core included in every oath and consist of three factors that should, in principle, not be removable from the OS.

#### Truthfulness Protocol

* Do not intentionally make false statements, conceal material facts, or fabricate information.
* Do not intentionally distort legally required reports or records.

#### Non-Betrayal Protocol

* Do not intentionally act against the interests of the public entity to which the person belongs, including the state, a local government, or a public institution.
* Do not transfer benefits to an external actor in a manner constituting betrayal.

#### Confidentiality Protocol

* Do not unlawfully provide confidential information or high-risk personal information obtained through official duties to a third party.
* Do not obstruct disclosures made under law, legitimate whistleblowing, lawful reporting to judicial or administrative authorities, or other justified disclosures.

---

### 2.2 OP-L2: Position-Specific Protocols

These are additional oaths applied according to a particular public position, office, or authority.

#### Political-Financial Protocol

* Accurately record and report political-funding income and expenditure.
* Do not conceal the substantive nature of transactions through nominee arrangements, indirect transactions, or other circumvention methods.

#### Public-Office Protocol

* Where conduct conflicts with a public pledge, prior explanation, or previous representation, explain the reasons to voters or other relevant stakeholders.
* Where a conflict of interest is detected, carry out the required disclosure, recusal, avoidance, or management procedure.

#### Security-Clearance Protocol

* Apply additional standards of conduct to persons with access to confidential or national-security-related information.
* Clarify responsibility for the acquisition, use, storage, sharing, and disposal of such information.

---

### 2.3 OP-L3: Contextual Protocols

These are oaths added according to a specific situation, matter, qualification, procedure, or project.

#### Naturalization Protocol

* Respect the Constitution of Japan and the Japanese legal order.
* Do not intentionally engage in conduct that harms Japan.
* Express loyalty to Japan to the extent reasonably required by the applicable institutional framework.

#### High-Risk Data Handling Protocol

* Apply to persons or projects handling large quantities of personal, medical, financial, or other high-risk data.
* Establish additional responsibilities concerning access to, use of, sharing of, and protection of such data.

#### Special Mission Protocol

* Apply to persons participating in international negotiations, crisis response, national-security missions, or other specific assignments.
* Establish mission-specific rules concerning confidentiality, conflicts of interest, accountability, and other standards of conduct.

---

### 2.4 Purpose of the Layered Structure

The three-layer structure clarifies:

* which elements constitute the common core of all oaths;
* which elements are specific to a position or authority; and
* which elements depend on a particular situation, matter, or jurisdiction.

This structure allows the OS to accommodate exceptions, revisions, differences among positions and situations, and differences among countries and jurisdictions.

---

## 3. Architecture

### 3.1 L1: Physical Oath Layer

The Physical Oath Layer is responsible for the creation, signing, authentication, and official preservation of the oath document.

Its anticipated components include:

* an in-person oath before a notary office or another authorized authentication body;
* preparation of the oath document;
* signature by the oath-taker;
* authentication of the signature and identity of the oath-taker;
* collection of stamp duties, notarial fees, or other institutional charges; and
* official preservation of the oath document.

For example, if the system were introduced into a naturalization procedure, the application fee, stamp duty, and notarial costs could be integrated into a unified institutional fee structure.

---

### 3.2 L2: Digital Twin Layer

The oath document itself should be preserved by a notarial institution or another appropriate public body.

A hash calculated from the document may then be recorded in a tamper-resistant ledger, such as:

* a blockchain;
* a public hash ledger;
* a publicly verifiable ledger with resistance to alteration; or
* another verifiable recording infrastructure.

Publicly accessible information may include:

* the hash value;
* the timestamp;
* the applicable Oath Protocol Types; and
* the minimum authentication status necessary for verification.

This makes it practically difficult for a person to deny later that the oath was made, without requiring unlimited disclosure of the oath document itself.

---

### 3.3 L3: Trust Badge / VC Layer

A person who completes an oath may receive a Verifiable Credential or another form of verifiable proof showing that the oath has been completed.

The individual may voluntarily associate the credential with:

* a personal profile;
* a website;
* a social-media account;
* election materials;
* an administrative account;
* a corporate account; or
* a governance report.

Within voluntary-oath and Trust Badge contexts, completion of an oath should be treated as positive information, while the absence of an oath should not, by itself, be treated as negative information.

Where an oath is institutionally mandatory, non-completion should be treated as a failure to satisfy the applicable institutional requirement, rather than as a character judgment within the Trust Badge system.

---

### 3.4 L4: Application Modules

Individual institutional modules may operate on the common infrastructure of the Notarized Oath OS.

Potential modules include:

* a political-funding transparency module;
* an anti-espionage and national-security module;
* a naturalization and nationality module;
* an election-system add-on module;
* a high-risk information access-management module; and
* a public conflict-of-interest management module.

Each module maintains the common OP-L1 core while adding OP-L2 or OP-L3 protocols according to the relevant position, authority, situation, and jurisdiction.

---

## 4. I/O Design: Synchronization with the National Institutional OS

### 4.1 Triggers

The OS defines the following four types of trigger for generating an oath obligation or oath opportunity.

#### 4.1.1 Authority Trigger

An oath obligation arises when a person assumes a position involving a specified level of public authority.

Examples may include:

* members of the National Diet;
* members of local assemblies;
* specified positions within the national or local civil service;
* officers of important regulatory bodies; and
* persons with authority to allocate public funds or public resources.

#### 4.1.2 Access Trigger

An oath obligation arises when a person obtains access to confidential information, national-security information, large-scale personal information, or other high-risk information.

#### 4.1.3 Procedure Trigger

An oath obligation arises where a limited oath is established as an institutional requirement in a statutory procedure, such as naturalization or the granting of a qualification.

The content of the oath must be limited to matters reasonably related to the purpose of the procedure and must not require comprehensive conformity in thought, belief, or expression.

#### 4.1.4 Voluntary Trigger

A voluntary route should be available through which the following persons may take an oath and obtain a VC or other verifiable proof:

* members of the general public;
* persons who already held a covered public position before implementation of the system;
* persons naturalized before implementation of the system;
* persons holding important positions in the private sector; and
* individuals or organizations seeking to implement public self-governance.

---

### 4.2 Three-Way Synchronization

The OS has synchronization interfaces in the following three directions:

* National Institutional OS ⇄ Individual / Position;
* National Institutional OS ⇄ Administration / Judiciary; and
* National Institutional OS ⇄ Voters / Society / Information Environment.

Synchronization with the individual or position connects the oath with authority, qualification, and accountability.

Synchronization with administrative and judicial institutions connects reasonable grounds for doubt with opportunities for explanation, evidence, breach-determination procedures, and necessary legal measures.

Synchronization with voters and society enables the oath status, explanation history, and minimum necessary verification information to be made publicly accessible where appropriate.

---

## 5. Oath-Breach State Machine

Procedures concerning a possible oath breach are divided into four states, from S0 to S3.

---

### 5.1 S0: Normal State

This is the default state following completion of the oath.

The oath-taker may exercise authority, perform official duties, and display the relevant VC where appropriate.

No additional explanation or investigation is required unless reasonable grounds for doubt arise.

---

### 5.2 S1: Doubt Raised State

The system transitions from S0 to S1 where reasonable grounds arise to question the consistency between the oath and a specific observed fact, and the applicable preliminary-screening requirements are satisfied.

Potential initiating actors include:

* administrative bodies;
* judicial bodies;
* audit bodies;
* whistleblowers or information providers satisfying specified requirements; and
* other institutionally authorized actors.

The system must not transition to S1 solely on the basis of:

* general impressions;
* reporting that lacks a concrete connection to the oath;
* political or emotional labeling;
* unsupported assertions; or
* the oath-taker’s beliefs, opinions, or personal attributes.

At S1, a preliminary assessment is conducted to identify which specific oath provision may be relevant to the conduct in question.

---

### 5.3 S2: Explanation State

Where the preliminary assessment at S1 is satisfied, the system transitions from S1 to S2.

At S2, the Accountability Bond is activated.

The person concerned must be given a reasonable period in which to provide an explanation and submit rebuttal evidence.

The assessment should consider:

* objective facts;
* the concrete relationship between the conduct and the oath;
* the applicable OP-L1, OP-L2, and OP-L3 protocols;
* the oath-taker’s explanation;
* rebuttal materials;
* legitimate exceptions;
* whether the conduct was permitted by law; and
* whether the investigation or acquisition of information was lawful.

Where the explanation resolves the reasonable grounds for doubt, the system returns from S2 to S0.

Where the reasonable grounds for doubt remain unresolved after an opportunity for explanation and rebuttal, and the requirements for commencing a formal determination procedure are satisfied, the system transitions from S2 to S3.

---

### 5.4 S3: Violation Determination State

S3 does not represent an automatic and final determination that the oath has been breached.

It is the stage at which an authorized institution conducts a formal procedure to determine whether an Oath Protocol Violation occurred.

The following matters may be examined:

* whether an Oath Protocol Violation occurred;
* the oath-taker’s knowledge and intent;
* the causal and normative relationship between the conduct and the oath;
* the evidentiary status of the Strong-Presumption Fact;
* the connection with criminal, administrative, or other applicable law; and
* the proportionality of any sanction or measure.

A Strong-Presumption Fact does not automatically establish an oath breach, criminal liability, or administrative liability.

Final responsibility must be determined separately in accordance with the elements, evidence, authority, and due process required under the applicable law.

Where the requirements of the applicable law are satisfied, potential connections may include:

* unauthorized disclosure of confidential information;
* false statements in official records;
* breaches of public duties;
* violations of conflict-of-interest rules;
* betrayal-related transfers of benefits;
* offenses concerning foreign aggression or other national-security matters; and
* administrative sanctions, including removal from office or suspension of qualification.

---

### 5.5 Expected Effects

#### Prevention of False Accusations and Misidentification

By making S1 and S2 mandatory intermediate stages, the OS clarifies the procedures separating the existence of doubt from the formal determination of a violation.

This prevents the improper leap from “a question has been raised” to “a violation has been established.”

#### Alignment of Judicial and Administrative Procedures

The OS provides the following consistent process:

> Reasonable grounds for doubt
> → Preliminary assessment
> → Accountability obligation
> → Opportunity for rebuttal
> → Resolution of doubt or formal violation-determination procedure

#### Prevention of Political Misuse

The system structurally prohibits a violation determination from being made solely on the basis of impression management, hostile labeling, or sensational information distribution.

---

## 6. Abstract Responsibility Rules for Strong-Presumption Facts

For the purposes of this document, a Strong-Presumption Fact is a factual relationship that may possess substantial evidentiary or explanatory force concerning knowledge, intent, or accountability because it is formed through:

* an explicit oath by the individual;
* assurance of identity and authenticity of signature;
* an oath record;
* reasonable grounds for doubt;
* an opportunity for explanation and rebuttal; and
* other relevant procedures.

A Strong-Presumption Fact does not necessarily constitute a statutory presumption or a final determination of liability under applicable law.

---

### 6.1 Problem Statement

A Strong-Presumption Fact relating to a possible oath breach may directly affect:

* public elections;
* reputation and honor;
* political fairness;
* social standing;
* economic interests;
* professional position; and
* legal or administrative assessment.

If such a powerful fact is used arbitrarily by any of the following actors, the OS itself could become a weapon for political conflict, information warfare, social exclusion, or abuse of authority:

* mass media;
* political parties;
* politicians;
* administrative bodies;
* corporations;
* organizations;
* individual influencers; and
* other information distributors.

---

### 6.2 OS-Level Response

Rather than singling out particular actors for regulation, the OS establishes a universal responsibility principle applicable to every actor using a Strong-Presumption Fact.

Responsibility is determined by conduct rather than by the identity or institutional category of the speaker.

Relevant conduct may include:

* quoting information without confirming its content;
* generalizing beyond its proper scope;
* making conclusive statements while ignoring the procedural stage;
* confusing the existence of doubt with a formal violation determination;
* distributing information after removing its context;
* arbitrary or inaccurate labeling; and
* continuing distribution without regard to the possibility of correction.

---

### 6.3 Abstract Responsibility Rule

#### Responsibility Principle for the Handling of Strong-Presumption Facts

Any public or private actor that arbitrarily or inaccurately quotes, summarizes, evaluates, or makes conclusive assertions concerning an alleged oath breach or another Strong-Presumption Fact generated through this OS, without sufficiently verifying its content, scope, evidence, and procedural status, bears a reasonable duty of explanation.

This principle applies equally to all information distributors, including media organizations.

However, it is not intended to restrict freedom of the press, freedom of expression, freedom of criticism, or legitimate whistleblowing.

The principle functions as an OS-level safeguard designed to:

* prevent social harm caused by misuse of Strong-Presumption Facts; and
* preserve an accurate distinction among doubt, procedure, violation determination, and final legal responsibility.

The principal elements of this rule are as follows:

* Any actor using a Strong-Presumption Fact bears the same responsibility.
* No specific media entity, political party, administrative body, or individual is singled out.
* Expression is not prohibited in advance; instead, an explanation is required where information has been used inaccurately.
* Legitimate criticism, verification, reporting, rebuttal, and whistleblowing are not obstructed.
* The OS must not be transformed into a tool for suppressing speech or attacking political opponents.

---

## 7. Anti-Fragility: Resistance to Attack and Misuse

### 7.1 Prevention of Labeling Abuse

The Notarized Oath OS is not a labeling device for judging people.

It is an infrastructure for maintaining institutional trust by incorporating:

* oaths;
* explanations;
* opportunities for rebuttal; and
* verifiability

into public institutional environments.

Within voluntary-oath contexts, a person must not be labeled untrustworthy, dangerous, or uncooperative solely because that person has not taken an oath.

Completion of an oath is positive information.

The absence of an oath is not, by itself, negative information.

---

### 7.2 Prevention of Authoritarian Misuse

Mandatory oaths must be limited to persons for whom there is a rational institutional basis for requiring an oath, including:

* persons exercising public authority;
* persons with access to public funds or public resources;
* persons with access to confidential information or large-scale personal information;
* persons with significant decision-making authority within public institutions; and
* persons for whom a limited oath is reasonably required as part of naturalization or another statutory procedure.

Members of the general public must not be compelled to conform in:

* thought;
* belief;
* expression;
* culture;
* political opinion; or
* values.

The content of an oath must be limited and clear and must be reasonably related to the authority, access, qualification, or statutory procedure concerned.

---

### 7.3 Protection against False Accusations and Abuse

The S0-to-S3 State Machine structurally prohibits an immediate violation determination without the required procedure.

Oath language must be limited and clear.

Where abstract or comprehensive language is used, the following must be specified:

* the scope of application;
* the prohibited conduct;
* the applicable exceptions; and
* the determination procedure.

Expansive interpretation of an oath must be limited by the interpretive principles of this OS.

The oath-taker must be guaranteed:

* a reasonable period for explanation;
* an opportunity for rebuttal;
* an opportunity to submit materials; and
* a mechanism for review or appeal.

---

### 7.4 Integration with the Strong-Presumption Fact Responsibility Rules

Under Section 6, the same accountability principle applies whenever a Strong-Presumption Fact is used by:

* media organizations;
* political parties;
* politicians;
* administrative bodies;
* judicial institutions;
* corporations;
* organizations;
* individual influencers; or
* other information distributors.

This structure rejects both:

* the use of the Oath OS as a tool for regulating the press; and
* the use of the Oath OS as a tool for attacking political opponents or particular groups.

The OS therefore combines:

* a structure for generating Strong-Presumption Facts; and
* a responsibility structure for preventing their misuse.

---

## 8. Transition and Implementation Framework

### 8.1 Initial Introduction

At the initial stage of implementation, the system should generally apply first to newly covered persons.

Examples include:

* newly appointed officials;
* persons newly granted access to high-risk information;
* newly naturalized persons; and
* persons newly obtaining a covered qualification or authority.

A reasonable transition period should be provided for persons who already held a covered office, qualification, or status before implementation of the system.

Where appropriate, voluntary oath and VC routes may be introduced in advance.

---

### 8.2 Process Design

Procedural routes among the relevant institutions should be integrated in order to reduce the administrative burden on participants.

For example, where the system is introduced into naturalization procedures, the following may be recommended:

* locating the Legal Affairs Bureau and the notary office in the same building or in adjacent facilities; or
* establishing an electronic connection between them.

Application, identity verification, preparation of the oath document, signing, authentication, payment of fees, and registration of the record should be integrated into a one-stop process to the greatest extent possible.

---

### 8.3 Social Adoption of Verifiable Credentials

Display of oath-completion VCs should be introduced gradually according to the maturity of the system.

Potential display locations include:

* government websites;
* election materials;
* official profiles of politicians and public officials;
* corporate governance reports;
* public qualification records; and
* websites or social-media accounts voluntarily selected by the individual.

The VC should not disclose the oath document without limitation.

It should contain only the minimum information necessary to verify authenticity and the applicable protocols.

---

### 8.4 Public Explanation

The OS should not be presented as an expansion of surveillance.

It should instead be explained as:

> A system that makes it possible to verify who, among those entrusted with public authority, important information, or significant social responsibility, has explicitly committed to which standards of conduct.

The central function of the OS is not continuous monitoring.

Its function is to:

* clarify the content of the oath;
* provide an opportunity for explanation and rebuttal where doubt arises; and
* connect the matter to a formal determination procedure only where necessary.

By integrating oaths, accountability, opportunities for rebuttal, breach verification, and responsibility for handling Strong-Presumption Facts, public trust can be supported through verifiable procedures rather than unconditional reliance on authority.
