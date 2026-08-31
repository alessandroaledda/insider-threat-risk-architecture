---
title: Insider Threat and Risk Architecture
subtitle: A living three level framework for building an insider risk management program in Europe. Nine pillars, the measures under them, and what each European jurisdiction has established on each of them, every row from a source that has been read.
reviewed: 2026-08-30
contributors: Jiri Holoska · https://www.linkedin.com/in/holoska/ · holoska-doucek · The first Czech source in the library, and the map of the Czech and Slovak statutes that will follow it.; Simon Ball ·  · MD018 · Asked whether covert monitoring reads as a capability rather than an exception, which is why the measure now says what the prior suspicion is for.
---

Insider Threat and Risk Architecture (INTRA™) is a [r:living] three level framework for building an insider risk management program in Europe.
- **Pillar.** One of the nine parts a program is built out of. The nine do not change from one jurisdiction to another: what the law varies is what a program does inside a pillar, never which pillars it has.
- **Measure.** A single action or deliverable under a pillar, and the unit a practitioner plans, budgets, and hands over. Almost all of them are the same thing in one European country as in another. A few exist only because a law somewhere created the need for them, and those are the ones that travel least.
- **Control.** A measure as one European jurisdiction binds it. Where an instrument that binds there sets a condition on a measure, the measure so conditioned is a control, and it carries an identifier of its own. Where a standard or a study speaks to a measure instead, what stands against it is a row and not a control.

A control states the condition and names the source it comes from. It does not state what an organization should do, it does not compare one jurisdiction with another, and it is not advice on compliance.

Thirty-four jurisdictions [y:in scope].
The European Union, the Council of Europe, every state in which Union or European Economic Area law applies, the United Kingdom, and Switzerland. A source qualifies if it is European in origin and if it sets out how a program is built, states a legal constraint on how one may operate, or reports research findings. American material is not listed: that part of the record is gathered already, and what is collected here can be used in a European organization without first subtracting the assumptions that do not hold there.
What a measure carries depends on what has been found for it.
- **A source worked in.** A control is written from it.
- **A source not yet worked in.** It is named on the measure, and nothing follows from it.
- **No source at all.** Nothing in the European record has been found to bear on the measure, which leaves it inside the framework and the question open.
Every row states its standing, and the standing is not a judgment about the row.
- [mandatory] where the source is an instrument that binds in that jurisdiction.
- [recommended] where it is a standard or a guidance document.
- [reported] where it is research.
The standing is taken from the kind of the source, not decided row by row, and where a row rests on more than one the strongest governs. Nothing here weighs an obligation against a recommendation or records one as the other. A binding row is a mandatory one, and it is the only kind that carries a control identifier, since a standard and a study are cited by their own reference.

Everything here is written in two files, and both are [b:public].
The framework and the library are kept as markdown in a repository, under a license that lets anyone use them, change them, and build on them as long as they credit them. The data the site reads is generated from those two files, so a correction goes to the markdown and never to the JSON. What the repository holds is what this page is built from rather than a copy of it, and anyone who thinks a control is formulated wrongly, or knows a source that belongs here, can open the question there.

Part of what INTRA maps does not exist. There is no European insider symposium: the reference event in the field is American, in its eleventh edition. There is no European professional body for the discipline. There is no program standard at Union level, the only thematic report from the Union agency dating from 2020 and the only program development manual from 2019. INTRA records those absences the way it records a jurisdiction that has said nothing.

## GV · Governance and mandate {#gv}
Summary: The authority under which an insider risk management program operates, its ownership, and the record of both.

### GV001 · Program charter and mandate {#gv001}
What it is: The instrument that establishes the program, states its authority, names its sponsor, and bounds what it may reach.

EU · established · [coess-manual] · The Union-funded manual addresses how a program is structured, and states no legal basis for any of it.
GB · established · [npsa-framework] · The charter is written to be reviewed against rather than filed: governance and culture are set out as things a program is measured on, not as preamble to the controls.

### GV002 · Declared perimeter {#gv002}
What it is: The single account of what the program does, what it does not do, and on what authority, written to be shown outside it.
GB · established · [uk-dpa-2018] · Where an employer processes a closed category under the employment condition, an appropriate policy document has to be in place when the processing is carried out, and it has to have been produced: a document explaining the procedures for securing compliance with the principles for that processing, and the policies on retention and erasure with an indication of how long the data are likely to be kept. It is a condition of the processing being lawful and not a record made afterwards.

### GV003 · Cross-functional governance body {#gv003}
What it is: The standing body in which the functions a program touches meet and decide together: security, human resources, legal, compliance, and technology. What makes it this measure rather than a mailing list is that it decides, and that it decides in one room rather than one function at a time.
GB · established · [npsa-stakeholders] · The group is named and its membership drawn: physical and information security, technology, human resources, vetting, facilities, contracts, procurement, finance, counter fraud, legal, training, communications, and a staff or trade union representative. What the group decides is not stated.

### GV004 · Roles and decision rights {#gv004}
What it is: The statement of which decisions the program may take, of the role entitled to take each, and of the person holding that role. The decisions are the ones the framework names elsewhere: to open a case on a person, to reach for the content of what they wrote, to withdraw their access before any finding, and to recommend a consequence.
GB · established · [npsa-stakeholders] [npsa-board] · One board member holds overall responsibility for protective security, and a non-executive director acts as an independent champion for it. Below them a director carries the strategy into policy, and senior staff in each business area answer for the risk assessment and for implementation in their own.
IT · established · [garante-framos-2026] · The technician who reached into the accounts held the role and not the instruction. A signed confidentiality undertaking is not the documented instruction the Regulation asks of anyone processing on the controller's behalf.

### GV005 · Shared definitions and severity scale {#gv005}
What it is: A written agreement among the functions on what constitutes an event, what constitutes a condition, and what a given severity denotes.

GB · established · [npsa-definitions] · The definitions of insider, insider risk, insider threat, and insider event were revised, and they are organized around intent.
GB · established · [npsa-five-principles] · The definitions are agreed to be used consistently, and intentional and unintentional events are held on one spectrum so that a severity scale does not have to choose between them.
DE · established · [bsi-grundschutz] · What counts as a security incident has to be defined clearly and marked off, as far as it can be, from the disruptions of ordinary operation. Everyone involved in handling one has to know the definition, and the definition and the thresholds at which it is met should follow the protection the affected processes, systems, and applications need. A single procedure for classifying incidents and disruptions should be settled, and agreed between security management and the function that handles ordinary faults.
BE · established · [be-cyfun] · The organization is to define what an insider threat is, clearly, and the definition offered runs on intent and on standing: malicious, negligent, or compromised, and covering employees and contractors alike.

### GV006 · Escalation triggers and owners {#gv006}
What it is: The agreement, settled between the functions before any case exists, on which conditions pass out of the team that observed them, to whom they pass, and within what time. As distinct from moving a live matter upward during a response, which the incident pillar holds.
DE · established · [bsi-grundschutz] · An escalation strategy is formulated beyond the communication and contact strategy and agreed between the people who handle ordinary faults and information security management. It should say unambiguously who is to be brought in, by what route, and when, for each kind of detected or suspected disturbance, what measures an escalation leads to, and how the response is to run. The contact strategy under it settles who must be informed and who may be, by whom, in what order, and in what depth, and who may pass information about an incident outside. It is reviewed at intervals and the paths are practiced in exercises.
NL · established · [nl-bio2] · The monitoring process in the security operations function has unambiguous rules about when an incident is reported to the management answerable for it.

### GV007 · Lawful basis register {#gv007}
What it is: The record naming, for each stream of data the program collects and each use it puts that data to, the ground it rests on and the condition the jurisdiction attaches to that ground. Written before the collection starts, and held in a form that can be shown rather than asserted.

EU · established · [gdpr] [wp249] · A ground under article 6 has to be recorded for each stream the program collects, before it collects it, and the register has to survive the article 5(2) test of being shown rather than asserted.
DE · established · [bag-workday] · The national employment provision cannot carry the register on its own: the ground recorded has to be one that stands under article 6 itself, the employer's legitimate interests among them.
FI · established · [fi-privacy-working-life] · Only data directly necessary for the employment relationship may be processed, and no exception to that test can be made even with the employee's consent.
BE · established · [be-cct-81] · Four purposes are listed and the list is closed: unlawful or defamatory acts, the confidential economic interests of the undertaking, the security and technical functioning of its systems, and good faith observance of the rules it has set for using the technology.
NO · established · [no-aml-kontroll] [no-innsyn-epost] · A control measure rests on objective grounds in the circumstances of the undertaking and must not be a disproportionate burden on the person subject to it. No instruction and no agreement may depart from that to the worker's detriment, so an agreement cannot be the ground for reaching further.

### GV008 · Impact assessment before deployment {#gv008}
What it is: The written assessment, made before a measure operates and kept afterwards, of what it will do to the people subject to it: what it will collect about them, what may follow from what it collects, and what they can do about either. It is a document, and its absence is a finding on its own.
Also: DPIA data protection impact assessment

EU · established · [gdpr] · The assessment has to be completed before the measure operates, not compiled after it, wherever the processing is likely to result in a high risk.
IT · established · [garante-243-2025] · Its absence is enough on its own: a decision has turned on the missing procedural steps without reaching the purpose the processing served.
GB · established · [ico-monitoring] · An assessment must be carried out before any processing likely to cause high risk, and the examples given reach an insider risk management program directly: the biometric data of workers, keystroke monitoring, monitoring that may result in financial loss, and the use of profiling or special category data to decide on access. Where there is a data protection officer, their independent advice must be sought and recorded. Anyone else the monitoring captures, a customer or a member of a worker's household, is to be considered in it.

### GV009 · Accountability evidence {#gv009}
What it is: The material by which the program can show how it reached a decision about itself: a threshold set, an instrument chosen, a policy changed. As distinct from asserting that the decision was reached properly, and as distinct from the record of a single case, which the investigation pillar holds.

EU · established · [gdpr] · The program has to be able to produce, for any decision, the material showing how it was reached. Holding a defensible view of it is not the same evidence.

### GV010 · Worker representative engagement {#gv010}
What it is: The involvement of the body representing the workforce in the design of the program, as distinct from any instrument deployed under it.

FR · established · [code-travail-controle] · The body brought in is the social and economic committee, informed and consulted before the decision, and informed again before automated personnel management processing is introduced.
DE · established · [betrvg-87] · The body brought in is the works council, and its role is co-determination rather than consultation: the employer cannot proceed over its objection.
IT · established · [statuto-art-4] · The body brought in is the union representation, and its agreement is the condition on which any instrument capable of remote monitoring may exist at all.
NL · established · [wor-27] · The body brought in is the works council, and its consent is required for the arrangement itself, not only for the instrument under it.
FI · established · [fi-privacy-working-life] · Camera surveillance, access control, other technical monitoring, and the use of electronic mail and the network go through the cooperation procedure before the employer decides. Where the cooperation acts do not apply, the employees or their representatives are heard first.
BE · established · [be-cct-81] · The works council is informed on every aspect of the monitoring before the system is installed, and failing a works council the prevention committee, then the union delegation, then the workers.
NO · established · [no-aml-kontroll] · The need for the measure, its design, its implementation, and any material change to it are discussed with the elected representatives as early as possible.
AT · established · [at-arbvg-96] · The works council does not consent to a control measure as a step before it, but as the condition of its legal effect. What brings a measure inside the requirement is whether it touches human dignity.
GB · established · [ico-monitoring] · The views of the workforce or its representatives should be sought and documented before monitoring is introduced, unless there is a good reason not to, and where the decision is not to, that decision should be recorded with a clear explanation. It should be done early in the planning and as part of the impact assessment.

### GV011 · Notice before an algorithmic system is deployed {#gv011}
What it is: Notice that a system of a named class is about to be put into use, owed to the representatives of the workforce and to the workers themselves. It falls due by reason of what the system is, so it is owed even where the representatives hold no right to be consulted, and even where they have already been consulted about the same system.

EU · established · [ai-act] [digital-omnibus-ai] · Workers' representatives have to be told before a high-risk system is put into use. The duty applies from 2 December 2027 for the Annex III categories.

### GV012 · Program metrics and reporting {#gv012}
What it is: What the program reports about its own operation to the body that governs it, and how often. Not what the program found, but how much of it there was, how long it took, and what it cost.
GB · established · [npsa-board] · The board member who holds the responsibility is to be regularly engaged with the people running the program and to hold a firm understanding of the risks it addresses. What is to be reported, and how often, is not stated.

### GV013 · Periodic program review {#gv013}
What it is: The revision of each component of the program at a stated interval.


GB · established · [npsa-framework] · The framework is offered as something an organization reviews itself against, which makes the review a recurring act rather than a one-off inspection.
GB · established · [stewart-hobbs] · The advice literature has itself been coded and characterised, so what guidance instructs can be examined rather than assumed.
NO · established · [no-aml-kontroll] · The need for the measures is evaluated at intervals, and the evaluation is made together with the elected representatives rather than by the employer alone.

### GV014 · Answering a request from the person {#gv014}
What it is: The program's answer when a person asks what is held about them and what is done with it. It is a measure once there is a route the request reaches, someone answerable for the reply, a period inside which it is given, and a rule for what is withheld and on what ground. An answer given late, or given in part without saying what was taken out and why, is not an answer.
Also: subject access request SAR data subject access
EU · established · [gdpr] · The reply is owed within one month of the request. It can be extended by two more where the request is complex or the requests are many, but the extension and the reasons for it have to reach the person inside the first month. Where the program will not act at all, that is said inside the same month, with the routes to a complaint and to a court named.
IT · established · [garante-itas-2026] · Answering in stages across five months, and then handing over the correspondence purged of many elements without saying what had been taken out or why, was held not to be an answer.
GB · established · [ico-monitoring] · What monitoring collects must be made available on a request unless an exemption applies, and the guidance turns that into a constraint on design: how easily information can be retrieved should bear on the choice of monitoring system in the first place, and that should be settled in the impact assessment. A system that cannot answer a request is a choice made earlier, not a difficulty met later.

## PS · Personnel security {#ps}
Summary: The measures directed at the person: what is verified before and during employment, what is asked of the people who manage them, what the program may hold about them, and what happens when they leave.

### PS001 · Pre-employment screening {#ps001}
What it is: The verification, before employment begins, of who the candidate is, that they may lawfully work, and that the account they give of their own history holds against evidence that does not come from them.

GB · established · [npsa-ongoing-persec] · Good practice treats screening at recruitment as the opening of a process rather than its completion.
AT · established · [at-arbvg-96] · What needs the works council's consent is the form put to the person: a personnel questionnaire asking beyond general particulars and the professional qualifications for the work intended. Verification carried out against a third party is not reached by it.
EU · established · [nis2-ir] · Verification of an employee's background is required as far as it can be done, where it is necessary for the role, the responsibilities, and the authorizations held. The mechanisms for hiring are named in the same place: reference checks, vetting procedures, validation of certifications, or written tests.
IT · established · [acn-379907] · The people authorized to reach the systems that matter are identified on a prior assessment of experience, capability, and trustworthiness, and have to give suitable guarantee that they will keep to the rules on information security. The trustworthiness of human resources is one of the areas the determination requires a written policy to cover.
DE · established · [bsi-grundschutz] · A new employee should be checked for trustworthiness before being hired, and everyone taking part in the selection should check whether what the candidate says bearing on that is credible. The curriculum vitae is examined for correctness, plausibility, and completeness, and whatever looks conspicuous in it is followed up. Separately, the qualifications a post requires are to be formulated exactly, and a post filled only by someone who has them.
ES · established · [es-ens] · The requirements a person has to satisfy to hold a post are defined, in particular on confidentiality, and they are taken into account in selecting who will hold it. What is verified is named: the employment history, the training, and other references, in conformity with the law and with respect for fundamental rights.
BE · established · [be-cyfun] · A background verification check should be carried out before a person is brought into a sensitive role, and it takes into account the applicable laws, regulations, and ethics in proportion to the business requirements.
NL · established · [nl-bio2] · Every entity has a screening policy that has been settled. On entering service, and on a change of function, a certificate of conduct may be asked for on the basis of a weighing of the risk.

### PS002 · Risk-tiered screening standards {#ps002}
What it is: The written standard setting, for each level of exposure a role carries, what is checked and how far. Exposure, not seniority: a systems administrator two grades down reaches further than the director above them.
EU · established · [nis2-ir] · Criteria are laid down setting out which roles, responsibilities, and authorities may be exercised only by a person whose background has been verified, and the verification is done before that person begins to exercise them. What it takes into account is stated: the classification of the assets, the systems to be reached, and the risks perceived, in proportion to the business requirements. The policy is reviewed at planned intervals.
DE · established · [bsi-grundschutz] · Depth follows the area and not the person. In a high security area a further check is carried out on top of the basic check of trustworthiness, and where the work touches classified material the person goes through the statutory security clearance. This sits at the grade the compendium keeps for a raised protection need, which is itself settled by an individual risk analysis.
ES · established · [es-ens] · For each post directly bound up with the handling of information or services, the security responsibilities it carries are defined, and they are based on the risk analysis. The measure does not apply at the basic category and applies at the two above it, so the scheme grades the obligation itself by what the system holds.
BE · established · [be-cyfun] · What the background check weighs is the classification of the information to be reached and the risks perceived, so the depth follows what the role will hold rather than where the role sits.
FI · established · [fi-katakri] · The authority has to recognize which of its functions call for special trustworthiness and reliability in the people employed in them. The clearance that follows can rest on a concise, a basic, or a comprehensive investigation, and which of the three is used depends on the information at stake.
NL · established · [nl-bio2] · The certificate of conduct is asked for on a weighing of the risk rather than as a matter of course, so what sets the depth is the assessment and not the grade of the post.

### PS003 · Screening of privileged-role holders {#ps003}
What it is: The further verification applied to a person because of what their access reaches, triggered by the entitlement itself rather than by the title attached to it.
EU · established · [nis2-ir] · Among the things the verification takes into account are the network and information systems the person is to reach, so what the access reaches is part of what sets the depth of the check. Separately, the people holding administrative or privileged access are to be made aware of their roles, responsibilities, and authorities, and to act in accordance with them.
IT · established · [acn-379907] · System administrators are a category of their own. They are identified on the same prior assessment of experience, capability, and trustworthiness, stated in a requirement separate from the one covering everyone else admitted to the systems that matter.
ES · established · [es-ens] · Security and system administrators hold a personal security clearance granted by the competent authority, either because the risk analysis called for it or because a particular system requires it.
BE · established · [be-cyfun] · Personnel with access to the organization's most critical information or technology are to be authenticated at the point of access, and the framework says what that means: the person proves their identity technically when they reach the asset, and is not merely validated once at onboarding.
FI · established · [fi-katakri] · Where international requirements demand it, a person is given access to information at the third classification level and above only after a personnel security clearance has been issued for that level.

### PS004 · Screening during employment {#ps004}
What it is: The repetition of verification, in whole or in part, at a stated interval and on stated events: a move into a role of greater exposure, a return after a long absence, and a concern raised through any of the routes the program keeps open.

GB · established · [npsa-ongoing-persec] · Contracting is covered alongside employment, so the standard is set for people the organization does not employ.
EU · established · [nis2-ir] · The assignment of people to the roles that carry security responsibilities is reviewed at planned intervals and at least once a year, and changed where the review calls for it.
BE · established · [be-cyfun] · The background check is repeated periodically for the people in sensitive roles, so it is a standing condition of holding the role rather than a gate at the entrance.
FI · established · [fi-katakri] · The clearances, the handling rights, the rights of use, the access rights, and the awareness of the duty not to disclose are all kept updated as changes occur, and the training that goes with a change is given before the change.

### PS005 · Contractor and third-party personnel standards {#ps005}
What it is: The personnel standard applied to people working in the organization under someone else's contract, carried through the contract that brings them in and evidenced by the party that employs them.

GB · established · [npsa-ongoing-persec] · Briefing at joining is treated as part of ongoing personnel security rather than as an administrative step.
DE · established · [bsi-grundschutz] · External personnel are bound to the same laws, rules, and internal regulations as employees. Those brought in briefly or once are to be supervised in security relevant areas, and those there longer are inducted as employees are and given a deputizing arrangement of their own. A written confidentiality agreement is concluded before an external person is given access to confidential information, and on leaving they hand over their work and give back whatever access they were issued.
ES · established · [es-ens] · Where staff are contracted through a third party, the duties and obligations of each party and of the contracted staff are established, and so is the procedure for resolving an incident arising from a failure to meet them.

### PS006 · Onboarding security briefing {#ps006}
What it is: What a person is told at the point of joining: what is observed about them and why, what is expected of them, what they are to report and to whom, and what follows from a breach. Recorded as having been given, since it is relied on afterwards.
DE · established · [bsi-grundschutz] · At the start of the employment the person is informed of the rules, the instructions, and the procedures that exist, and a checklist and a named contact should be set up to carry it. Every employee is obliged to keep to the law and to the internal rules, has to know the legal frame of their own work, and has their tasks and responsibilities documented. They are told that what they receive at work is for internal use only, and made aware that they protect the organization's information security outside working hours and away from its premises as well.
ES · established · [es-ens] · Each person working on the system is informed of the duties and responsibilities their post carries: the disciplinary measures that may follow, what is owed during the post and what is owed on its ending or on a move to another, and the duty of confidentiality over the data they reach, both while they hold the post and afterwards. Above the basic category, express confirmation that the person knows the security instructions and accepts them has to be obtained.
NL · established · [nl-bio2] · Everyone, internal and external, is pointed to their responsibilities for information security on appointment or on a change of function, and the rules and instructions that apply to them are to be simple to reach.

### PS007 · Role change and internal transfer {#ps007}
What it is: The reassessment of what a person holds and owes when they move within the organization, including the withdrawal of what the previous role needed. Without the withdrawal, access accrues across a career and the person ends up reaching everywhere they have ever been.
EU · established · [nis2-ir] · Access rights are modified on a change of employment and not only on its end, so a move inside the organization is an event the entitlements have to answer to.
IT · established · [acn-379907] · Accounts and the authorizations on them are verified periodically on the systems that matter, and updated or revoked when something changes. A transfer of personnel is named as such a change, alongside the end of an employment.
FR · established · [fr-anssi] · The procedures for arrival, departure, and change of function are defined together with the human resources function, and what they have to reach is listed: the creation and deletion of accounts and the mailboxes attached to them, the rights to grant and to withdraw from a person whose function changes, physical access to the premises with badges and keys issued and returned, the mobile equipment assigned, and the handling of sensitive information, transferring or changing the passwords and codes on existing systems among it.
BE · established · [be-cyfun] · A human resources process for cybersecurity is developed and maintained, and it runs across recruitment, onboarding, employment, change of function, and offboarding rather than attaching to any one of them.
FI · established · [fi-katakri] · Changes in what a person may handle are noted at each phase of the employment, and a change of responsibilities is named alongside recruitment and termination as one of the three the attention goes to.
NL · established · [nl-bio2] · A change of function is one of the two occasions on which the certificate of conduct may be asked for, the other being entry into service.

### PS008 · Leaver process {#ps008}
What it is: What happens when employment ends: access withdrawn, assets recovered, continuing obligations restated, and the accounts themselves closed within a period the organization has stated in advance.

GB · established · [npsa-ongoing-persec] · Exit is covered as a stage of personnel security, with what is withdrawn and what is restated set out together.
NO · established · [no-innsyn-epost] · The mailbox is closed when the employment ends, and stays open only where there is a particular need and only for a short period.
IT · established · [garante-framos-2026] [acn-379907] · Leaving the account running after the employment ends is itself a processing and needs a ground of its own. Telling correspondents the person has gone, and keeping what may be wanted later, are not grounds, and running past the period the employer itself declared counts against it. Separately, obligations in the field of information security that stay valid after the employment ends, or changes, are fixed at the contractual level, confidentiality clauses among the examples given, on essential subjects.
EU · established · [nis2-ir] · Access rights are modified on termination, and the register of what was granted is what the withdrawal is checked against.
DE · established · [bsi-grundschutz] · The successor is briefed in time, by the person leaving where that can be done, and where it cannot the person leaving writes the documentation instead. Every document, key, device, badge, and access right received in the course of the work is collected back. The obligations of confidentiality are put to the person once more before they go, and to keep conflicts of interest from arising a non-competition clause and a waiting period should be agreed. Contingency and other plans are updated, and every part of the organization affected is told, the security staff and the IT function among them.
FR · established · [fr-anssi] · The rights assigned to a person are revoked on their departure, and the procedure covers the accounts and mailboxes, the badges and keys, the mobile equipment issued, and the passwords and codes on existing systems, which are transferred or changed.
FI · established · [fi-katakri] · On the termination of the employment the keys, the badges, and the classified material are collected in, the access, handling, and use rights are deleted, and the person is reminded of the responsibilities of non-disclosure that remain.

### PS009 · Line management engagement {#ps009}
What it is: The involvement of managers in noticing and raising concern about the people they supervise, structured by a named route, a stated threshold for using it, and instruction in both. Unstructured, it is a manager's instinct and reaches the program by chance.

GB · established · [npsa-ongoing-persec] · Line management is treated as the route by which concern reaches the program, which makes the manager part of the control.
CZ · established · [holoska-doucek] · The person's own line manager usually takes part in the examination, and what they supply is the context of the activity that was observed rather than a judgment on it.

### PS010 · Line management records of personal circumstances {#ps010}
What it is: Records of a worker's personal or family circumstances kept by the people who manage them, including those held outside any system the program runs: a manager's notebook, a shared drive, a private note.

IT · established · [garante-107-2026] · Notes kept by managers about a worker's circumstances are processing like any other: outside a declared purpose and a lawful ground they have neither.

### PS011 · Records concerning trade union activity {#ps011}
What it is: Records disclosing a worker's membership of a trade union or participation in its activity.

IT · established · [garante-107-2026] · A record touching union membership or activity falls in the stricter category, whatever the file it sits in and whoever wrote it.
EU · established · [gdpr] · Trade union membership is one of the categories article 9 prohibits the processing of outright. The prohibition lifts only on one of that article's own grounds, and the employment one requires that Union or member state law or a collective agreement authorize the processing and provide appropriate safeguards for the person.
GB · established · [uk-gdpr] [uk-dpa-2018] · Trade union membership is one of the categories the processing of which is prohibited, and in domestic law the prohibition lifts only where the processing also rests on a ground in article 6(1) and one of the article 9 grounds applies. The employment ground requires domestic law or a collective agreement, which is the Schedule 1 condition and the document it carries. In turn, the employment condition is met only where the processing is necessary to perform or exercise an obligation or a right imposed by law in connection with employment, and where the appropriate policy document is in place at the time.

### PS012 · Records concerning health held for security purposes {#ps012}
What it is: Records of absence, illness, or fitness held for the purposes of the program.

IT · established · [garante-107-2026] · A record of absence or illness held for the program falls in the stricter category, and holding it for security purposes does not move it out.
EU · established · [gdpr] · Data concerning health are one of the categories article 9 prohibits the processing of outright, so a security purpose is not on its own what makes holding them lawful. The prohibition lifts only on one of that article's grounds, and the employment one requires that Union or member state law or a collective agreement authorize it and provide appropriate safeguards.
GB · established · [uk-gdpr] [uk-dpa-2018] · Data concerning health are one of the prohibited categories, and the prohibition lifts only where the processing also rests on a ground in article 6(1) and one of the article 9 grounds applies. A security purpose is not among them. In turn, holding such a record for the program runs through the employment condition, which asks whether the processing is necessary to perform an obligation or a right imposed by law, and which requires the appropriate policy document to be in place when it is carried out.

### PS013 · Self-declaration of changed circumstances {#ps013}
What it is: The route by which a worker reports a change in their own circumstances bearing on their position. It is a measure once it is named, reaches someone answerable for it, and states what becomes of what is declared.


GB · established · [npsa-ongoing-persec] · Reporting routes are covered as good practice, including the route by which a person reports about themselves.
AT · established · [at-arbvg-96] · A standing route on which a worker reports about themselves becomes a personnel questionnaire once it asks beyond general particulars and qualifications, and introducing it then needs the works council's consent.

## DP · Data and asset protection {#dp}
Summary: The protection of the information and assets the organization holds, and of the records the program itself generates.

### DP001 · Identification of critical assets {#dp001}
What it is: The list of the information, systems, and physical assets whose loss, alteration, or destruction would cause the organization material harm, and the record of who decided that and when. It is the list that is the measure. A program that knows in principle what matters, and cannot produce the list, does not hold it.
EU · established · [nis2] · Asset management is named among the measures an entity in scope has to take, alongside access control policies and human resources security in the same point. What the identification covers, and how far it goes, is left to the state of the art.

### DP002 · Information classification scheme {#dp002}
What it is: The categories information is assigned to, the handling rules that follow from each, and what happens to information nobody has assigned. The default is part of the scheme: a category that only the careful apply leaves everything else outside it.
EU · established · [nis2-ir] · A system of classification levels is laid down and every asset is placed in one, on confidentiality, integrity, and authenticity. The handling policy that follows runs from acquisition through use, storage, and transport to disposal, and reaches everyone who handles an asset.
CZ · established · [holoska-doucek] · The classification level of a document governs how a person may work on it, with whom it may be shared, and where and how it may be kept. A document carrying the right level can then be followed by the loss prevention tooling, and access to it that was not permitted is raised as an incident.

### DP003 · Data discovery and inventory {#dp003}
What it is: The location of regulated or sensitive data across the estate, as distinct from where policy assumes it is.
EU · established · [nis2-ir] · The inventory is to be complete, accurate, up to date, and consistent, and changes to its entries are recorded so that they can be traced.

### DP004 · Access control and least privilege {#dp004}
What it is: The entitlements each person actually holds, held to what their task requires and no wider. The measure is the state of the entitlements, not the policy that describes the state they ought to be in.
EU · established · [nis2] [nis2-ir] · Access control policies are named among the measures an entity in scope has to take, and for one class of entity the implementing rules say what they hold: rights assigned and revoked on need to know, least privilege, and separation of duties, modified on termination or change of employment, authorized by the relevant persons, limited in scope and duration for suppliers and visitors, held in a register, and logged.
IT · established · [acn-379907] · Permissions are assigned on least privilege, separation of functions, and need to know. How an account authenticates is set against the risk, weighed on the privileges it holds, the criticality of the systems, and the kind of operations it can perform on them, and multi-factor authentication is used on the systems that matter.
DE · established · [bsi-grundschutz] · An identifier or an entitlement may be granted only on actual need and on what the task requires, and what is no longer needed is removed when the person changes. Anything beyond the standard is granted only after a further justification and a check of it. Every entitlement is set up through separate administrative roles, and the duties the organization has declared incompatible are held apart by the entitlement system itself.
ES · established · [es-ens] · The access control system is organized so that two or more people have to concur on a critical task, and the decree says what that is for: to cancel the possibility that a single authorized individual could abuse their rights to commit an unlawful or unauthorized act. All access is forbidden save on express authorization, privileges are cut to the minimum needed to do the work, and only staff with the competence to do so may grant, alter, or annul an authorization.

### DP005 · Privileged access management {#dp005}
What it is: The separation, brokering, and time-bounding of access that exceeds ordinary entitlement.
EU · established · [nis2-ir] · Privileged and system administration accounts carry policies of their own, strong identification and authentication among them, and the systems used to administer are kept for administration and separated from everything else.
IT · established · [acn-379907] · Every account is inventoried and approved by someone inside the organization, those with administrative privileges and those used for remote access included, and accounts are individual to a user unless there is a documented technical reason otherwise. A system administrator's privileged and unprivileged accounts are to be completely distinct, and to carry different credentials.
DE · established · [bsi-grundschutz] · An administrative activity should be one that two people have to carry out together. Where multi-factor authentication is used the factors are split between the two of them, and where a password is used it is divided in two and each of them holds a half. This sits at the grade the compendium keeps for a raised protection need.
ES · established · [es-ens] · Development and operation are not to fall to the same person, nor are authorizing a use and controlling it. At the high category the same person may not hold configuration and maintenance together, and auditing or supervision may not be combined with any other function at all. Accounts carrying audit privileges are strictly controlled and personal to their holder, and the system's security information is reachable only by the authorized administrators.
FR · established · [fr-anssi] · An exhaustive inventory of the privileged accounts is kept current, and reviewed periodically to make sure access to sensitive items is held, the working directories and the mailboxes of senior managers named among them. The review is also what removes the access left behind by a departure. A simple naming convention for service and administration accounts is wanted, because it makes both the review and the detection of an intrusion easier.
NL · established · [nl-bio2] · Only authorized personnel reach the system utilities, and only at the moments when reaching them is strictly necessary. Their use is logged, and the log is available for examination for half a year.

### DP006 · Access recertification {#dp006}
What it is: The periodic comparison of the access a person holds against the work they perform, and its adjustment.
EU · established · [nis2-ir] · Access rights are reviewed at planned intervals and changed on organizational change, and the result of the review is documented together with the changes it called for.
IT · established · [acn-379907] · Accounts and the authorizations on them are verified periodically on the systems that matter, and updated or revoked where a change calls for it.
DE · established · [bsi-grundschutz] · Which identifiers, groups, and rights profiles have been permitted and created is documented, and the documentation is checked at intervals against the state the entitlements are actually in, and against whether what has been granted still answers to the security requirements and to what the users now do. The documentation itself is protected from unauthorized access.
NL · established · [nl-bio2] · Every access right that has been issued is assessed at least once a year.

### DP007 · Data loss prevention deployment {#dp007}
What it is: The introduction of a capability that inspects content in motion, at rest, or in use, and acts on it against a policy.
Also: DLP

EU · established · [gdpr] [wp249] · A ground under article 6 has to be identified before anything is collected through the loss prevention capability, and whatever more specific rule the member state has made under article 88 applies on top of it. Consent is not that ground in an employment relationship.
CoE · established · [barbulescu] · Private life and correspondence extend into the workplace, including where a worker's private use of a work device breaks the employer's rules, and a monitoring measure is to be assessed against six criteria, prior notification and the availability of a less intrusive method among them. The case concerned the reading of a worker's messages, and whether the criteria reach a capability that inspects material other than correspondence is not decided in it.
FR · established · [code-travail-controle] · The social and economic committee has to be informed and consulted before the decision to deploy the capability, and the worker informed before content of theirs is inspected.
DE · established · [betrvg-87] · The works council has to agree before the loss prevention capability is introduced at all.
IT · established · [statuto-art-4] · An agreement with the union representatives, or failing that an authorization from the labor inspectorate, is required before installing the loss prevention capability.
NL · established · [wor-27] · The works council has to consent before the arrangement bringing the loss prevention capability in is adopted.
ES · established · [lo-3-2018] · Express prior information to the workers is required before the loss prevention capability is put into operation.
AT · established · [at-arbvg-96] · The works council's consent is the condition of the loss prevention capability having legal effect, and the threshold is whether it touches human dignity.

### DP008 · Data loss prevention policy and tuning {#dp008}
What it is: The rules the capability enforces, the thresholds at which it acts, and their revision against what it turned out to catch. Distinct from its deployment because the two are settled separately: in several jurisdictions the workforce is consulted once on bringing the capability in and again on the manner in which it is used, so changing a threshold reopens the question.
Also: DLP
DE · established · [betrvg-87] · The agreement is owed twice: once on introducing the capability and again on the manner in which it is used, so a change to the rules it enforces reopens it.
AT · established · [at-arbvg-96] · The consent that conditions the capability's legal effect attaches to the measure as it is operated, so rules that alter what it reaches fall to be consented to as the capability itself was.
NL · established · [wor-27] · Consent is owed on the arrangement being amended and on its being withdrawn, not only on its adoption, so the rules cannot be revised around the works council.
ES · established · [lo-3-2018] · The criteria for using the capability are drawn up with the participation of the workers' representatives, which places the rules themselves, and not only the decision to deploy, inside what is settled with them.

### DP009 · Egress channel control {#dp009}
What it is: The restriction of the routes by which data can leave: removable media, personal cloud storage, webmail, printing, and unmanaged devices.
EU · established · [nis2-ir] · Removable media carry a policy of their own, communicated to employees and to the third parties who connect them, and it provides for a technical prohibition of connections the entity has not allowed.
CZ · established · [holoska-doucek] · Restricting the channels through which a person can move data, personal mail, printing, writing to external media and to cloud storage, is treated as a proactive measure, and where it cannot be applied to the whole workforce it is applied to the people serving out notice.

### DP010 · Encryption and rights management {#dp010}
What it is: The protection of information such that possession of the file is not possession of its contents.
EU · established · [nis2] · Policies and procedures on the use of cryptography and, where appropriate, on encryption are named among the measures an entity in scope has to take.

### DP011 · Retention and disposal of business records {#dp011}
What it is: The period for which the organization keeps what it holds, and the manner of its destruction.

IT · established · [garante-364-2024] [garante-243-2025] [garante-itas-2026] · Twenty-one days is the outer limit for email metadata before the article 4 route is engaged, and ninety days of it alongside browsing logs has drawn a fine. A five year backup of everything passing through the mailboxes, kept to preserve the information estate, was held unlawful where no notice given to the staff described it.
BE · established · [be-cct-81] · Whether personal data are kept, where they are kept, and for how long are among the things stated to the workforce before the monitoring begins.
NO · established · [no-innsyn-epost] · What is left in the mailbox and in the worker's own areas, and is not necessary for the daily running of the undertaking, is deleted within a reasonable time of the employment ending.

### DP012 · Retention and disposal of program records {#dp012}
What it is: The period for which the program keeps what it produced rather than what it observed: the alert, the case file, the note, the export, the assessment. Distinct from the retention of the business records the program reads, which the organization sets for its own reasons and the program does not control.
NO · established · [no-innsyn-epost] · What is opened and proves not to be necessary or relevant to the purpose is closed at once, and any copy of it deleted.
NO · established · [no-nsm] · The security relevant data are to be used only to safeguard the security of the systems, and kept long enough that unwanted activity can be discovered and mapped after the fact. What weighs on the period is that the data may later be wanted for an investigation, for assessing damage, and for trend analysis, held against the point that they can hold confidential information about the individual employee.
AT · established · [at-ishb] · Log files hold personal data in many cases, so they may be used only for purposes compatible with the one they were collected for. Where that restriction bites, the handbook says it is resolved by removing the personal data or by anonymizing them, and states that pseudonymizing them is not enough.
GB · established · [uk-dpa-2018] · The appropriate policy document has to explain the policies on retention and erasure of the data processed under the condition, and to give an indication of how long they are likely to be kept. An indication is what is asked for, not a period.
GB · established · [ico-monitoring] · What monitoring produces must not be kept longer than is necessary for the purpose. The period should rest on business need and be reviewed regularly, and it should not be kept in case a purpose is found for it later. A retention schedule must exist and what is collected must be deleted in line with it.

### DP013 · Separation of program data {#dp013}
What it is: The keeping of the program's own holdings apart from the systems the organization runs its business on, so that a case file is not reachable by whoever can reach the human resources record, and the stated conditions on which something crosses from one to the other.
DE · established · [bsi-grundschutz] · The collected security relevant data are to be held centrally, as a log server assembly placed in a network segment set up for the purpose, and the administrators who operate it should hold no entitlement to alter or delete what it has recorded. The separation is of the store from the estate it observes and from the people who run that estate.
GB · established · [ico-monitoring] · Access to what monitoring produces should be restricted to the people who need it, the most appropriate people to hold it should be identified rather than assumed, and they should be trained to handle it. The security risks of the monitoring itself should be assessed and the measures decided from that assessment.

### DP014 · Personal material in company accounts {#dp014}
What it is: The handling of a worker's personal material held on systems the employer controls, during employment and after it.

IT · established · [garante-165-2026] · A former worker retains a claim on personal material left in the account, and the employer has to be able to answer a request for access to it.
FI · established · [fi-privacy-working-life] · What the employer may reach is the message belonging to it, identified from the sender, the recipient, or the title, and what is opened may not be processed further than the purpose requires nor disclosed during the employment or after it.
NO · established · [no-innsyn-epost] · The worker's personal areas on the undertaking's network and equipment are reached on the same conditions as the mailbox, and so is what was deleted from them and survives on a backup.
AT · established · [at-ishb] · There is no right for a worker to use the employer's resources privately. Minor private or half private use within ordinary human social behavior should nonetheless be allowed or ignored, and a total prohibition pronounced only in extreme cases.

### DP015 · Live data in non-production environments {#dp015}
What it is: The processing of real personal data outside a production environment.


DE · established · [bag-workday] · Live personal data may be used for a test where depersonalized data would not answer the question, and the legitimate interests ground carries it.

## MD · Monitoring and detection {#md}
Summary: The technical means by which work is observed, and the conditions attaching to their deployment.

### MD001 · Threat modelling and detection scoping {#md001}
What it is: The derivation of what the program will look for from the harm it is trying to prevent, before any tool is chosen.

EU · established · [enisa-2020] · Scoping starts at the level of control categories rather than of tools, and the only Union report to work from stops there and dates from 2020.
GB · established · [uk-monitoring-regs] · What may be looked for is a closed list. Interception on the employer's own system is authorized to establish the existence of facts, to ascertain compliance with regulatory or self-regulatory practices, to ascertain or demonstrate the standards achieved by the people using the system, in the interests of national security, to prevent or detect crime, to investigate or detect the unauthorized use of that or any other telecommunication system, or to secure the effective operation of the system. A purpose outside the list is not authorized by these regulations.

### MD002 · Log collection and centralization {#md002}
What it is: The aggregation of records of activity from systems across the estate into a single store.
EU · established · [nis2-ir] · The list of assets to be logged is derived from the risk assessment, and what the logs hold is named: inbound and outbound traffic, the creation, modification, and deletion of users and the extension of their permissions, access to systems and applications, authentication events, all privileged access and everything done by administrative accounts, access or changes to critical configuration and backup files, physical access to facilities, and the activation, stopping, and pausing of the logs themselves. They are kept for a period fixed in advance and protected from unauthorized access or change, time sources are synchronized so that logs can be correlated across systems, and the availability of the logging systems is monitored independently of the systems they log.
IT · established · [acn-379907] · All remote access and all access made with administrative privileges are recorded. For the systems that matter, the logs needed to monitor security events are acquired and kept securely and, where it can be done, centrally, and how long they are kept is fixed from the risk assessment and documented.
DE · established · [bsi-grundschutz] · A logging policy of its own is drawn up, saying how, where, and what is logged, with the kind and the extent of it following the protection the information needs. All security relevant events on systems and applications are logged, the clocks of everything that logs are kept synchronized and the date and time format made uniform, and it is checked at defined intervals that the logging still works. Data protection law and the co-determination rights of the workforce representation are to be kept to, logging data are deleted on a defined process, and their uncontrolled deletion or alteration is prevented technically. The data should be held centrally, on a log server assembly in a network segment set up for it, and filtered, normalized, aggregated, and correlated for evaluation while a copy is kept in unaltered original form. The administrators who run it should have no entitlement to change or delete what has been recorded.
ES · established · [es-ens] · The audit record carries at least the identifier of the user or entity the event belongs to, the date and time, what information the event was performed on, the type of event, and whether it succeeded or failed. Above the low level the security documentation states which events are audited and how long the records are kept before deletion, the clock is an administration function protected by authentication and integrity, and the records and their backups may be reached or deleted only by duly authorized personnel.
FR · established · [fr-anssi] · The critical components are determined first, the workstations of sensitive users named among them, and the logging on each is configured to match. Security critical events are kept for at least a year, or longer where the sector's legal obligations require it, and the time synchronization source is the same across components so that events can be correlated. At the reinforced level the logs are centralized on a dedicated device, which is wanted for three reasons: automated searching, long archiving, and preventing an attacker from erasing the traces of their passage on what they compromised.
FI · established · [fi-katakri] · The retention follows what the records may later have to answer. At the fourth classification level the essential recordings are kept at least six months; where the limitation periods of the criminal law bear on the information, at least five years, which is also the floor at the two levels above. The clocks within a security domain are synchronized to a single reference, the log files are backed up, a procedure covers their integrity, and they and the register services are protected against unauthorized access.
NO · established · [no-nsm] · A written strategy for security monitoring settles the purpose and the field of use of what is collected, which data are collected, their secure storage including for legal proceedings, capacity planning, who may reach them, the consolidation of logs from the different units and services, deletion, and the interval at which the strategy is reviewed, at least once a year and after a major incident. What is collected is verified against what was meant to be, the data are archived and digitally signed at intervals for integrity, functionality is put in place that detects attempts to alter or delete a log, everything is synchronized to one and the same time source, and what has lost its operational or security relevance is removed.
NL · established · [nl-bio2] · There is an overview of the log files that are generated. How long the log files and the data in the security information and event monitoring are kept is settled against the risk, and the scenario it is settled against is named: that the attackers have been inside for a long time. Improper alteration or deletion of log data, and any attempt at it, is reported as soon as it can be.
AT · established · [at-ishb] · Logging security relevant events works as a security measure only where the data are evaluated at regular intervals by an independent reviewer. Where no independent reviewer can be put in place the administrators may do it, and the handbook states the consequence rather than leaving it: checking the administrators' own activity then becomes hard. The evaluation is to be laid before the data protection officer or the security officer in any case, the responsibility for carrying it out is to be fixed exactly, the four eyes principle should be used in the security critical cases, and it must be ensured by technical or organizational means that the administrators' activities can be adequately checked.
BE · established · [be-cyfun] · The logging functionality of the protection and detection tools is enabled, the logs are backed up and kept for a period fixed in advance, and they are reviewed regularly for unusual or potentially harmful activity, on a documented procedure.

### MD003 · Detection use case development {#md003}
What it is: The construction of a specific, testable rule or query that raises an alert on a defined pattern of activity.

GB · established · [citd] · A characterization framework and a working tool came out of the research program, which is a starting point a use case can be derived from rather than invented.
GB · established · [citd-deployment] · Deploying a research tool inside three organizations for a year surfaced the operational constraints that the detection literature leaves out.
EU · established · [nis2-ir] · Alarm thresholds are set where appropriate, an alarm is raised automatically once one is exceeded, and a qualified response follows in good time. Monitoring is to be automated as far as it can be and built so as to minimize both false positives and false negatives, and a process for correlating and analyzing logs is put in place.
IT · established · [acn-379907] · Qualitative and quantitative parameters for detecting unauthorized access, or access abusing the privileges granted, are defined, monitored, and documented. The requirement is on essential subjects, and the same annexes do not place it on important ones.
ES · established · [es-ens] · At the high category, measures are applied to prevent, detect, and react to attempts at data mining: the queries are limited, their volume and frequency are monitored, and suspicious behavior is alerted to the security administrators in real time. Systems for detecting advanced threats and anomalous behavior are required at the same category, alongside tools that analyze the activity and the audit information looking for possible or actual compromises.
NL · established · [nl-bio2] · Use cases for the misuse of authentication data are defined, monitored, and acted on, and two of them are named in the text: logins from unusual places, and spikes in failed login attempts. Separately, the creation and modification of accounts carrying special rights is monitored, and where such a change was not authorized it is an information security incident and is recorded and handled as one.
AT · established · [at-ishb] · The handbook sets out what an evaluation looks for: logon and logoff times outside working hours, a build-up of failed logon attempts, a build-up of impermissible access attempts, conspicuously long intervals in which nothing was logged, which points to records having been deleted, and conspicuously long intervals in which no user appears to have changed. Particular attention is to go to every access carried out under an administrator identifier.
NO · established · [no-nsm] · Tools are taken into use that allow manual and automatic searching and alerting on criteria across everything collected, and that assemble data from different sources on their own so that it can be decided whether the event is real rather than a false positive, and what its extent and character are. Knowledge of the normal state and of the threats is what the searches and the alerting criteria are improved from.
GB · established · [uk-monitoring-regs] · Investigating or detecting the unauthorized use of that or any other telecommunication system is named in the list of purposes in its own right, so the misuse of the employer's own system is a purpose the regulations authorize interception for rather than one that has to be brought under another.

### MD004 · Endpoint activity monitoring {#md004}
What it is: The deployment of an agent that records what is done on a workstation or laptop.

EU · established · [gdpr] [wp249] · A ground under article 6 has to be identified before anything is collected through the endpoint agent, and whatever more specific rule the member state has made under article 88 applies on top of it. Consent is not that ground in an employment relationship.
CoE · established · [barbulescu] · Private life and correspondence extend into the workplace, including where a worker's private use of a work device breaks the employer's rules, and a monitoring measure is to be assessed against six criteria, prior notification and the availability of a less intrusive method among them. The case concerned the reading of a worker's messages, and whether the criteria reach an agent recording what is done on a device is not decided in it.
FR · established · [code-travail-controle] · The social and economic committee has to be informed and consulted before the decision to put the endpoint agent in place, and the worker informed before it reaches them.
DE · established · [betrvg-87] · The works council has to agree before introducing the endpoint agent, and again on the manner in which it is used.
IT · established · [statuto-art-4] · An agreement with the union representatives, or failing that an authorization from the labor inspectorate, is required before installing the endpoint agent.
NL · established · [wor-27] · The works council has to consent before any arrangement governing the endpoint agent is adopted, amended, or withdrawn.
ES · established · [lo-3-2018] · Criteria for use, drawn up with the participation of the workers' representatives, and express prior information to the workers, are required before putting the endpoint agent into operation.
AT · established · [at-arbvg-96] · The works council's consent is the condition of the endpoint agent having legal effect, and the threshold is whether it touches human dignity.
BE · established · [be-cyfun] · Endpoint and network protection tools that monitor the behavior of end users for dangerous activity are to be implemented and to be managed. What they are for is stated without euphemism: detecting risky or suspicious behavior by users on devices and networks, including the misuse of systems and attempts to get around the controls, whether these come from an attacker outside or from an insider.
GB · established · [ico-monitoring] · Keystroke monitoring is named as an example of processing likely to cause high risk, so an assessment is owed before the agent is put on the device rather than after.

### MD005 · Network and egress monitoring {#md005}
What it is: The inspection of traffic leaving the organization's control for volume, destination, or content.

EU · established · [gdpr] [wp249] · A ground under article 6 has to be identified before anything is collected through the traffic inspection, and whatever more specific rule the member state has made under article 88 applies on top of it. Consent is not that ground in an employment relationship.
CoE · established · [barbulescu] · Private life and correspondence extend into the workplace, including where a worker's private use of a work device breaks the employer's rules, and a monitoring measure is to be assessed against six criteria, prior notification and the availability of a less intrusive method among them. The case concerned the reading of a worker's messages, and whether the criteria reach the inspection of traffic is not decided in it.
FR · established · [code-travail-controle] · The social and economic committee has to be informed and consulted before the decision to put the traffic inspection in place, and the worker informed before it reaches them.
DE · established · [betrvg-87] [bag-headset] · The works council has to agree before introducing the traffic inspection, and again on the manner in which it is used. What brings a device under that agreement is what it is capable of: a system that let supervisors hear conversations between employees was caught by it although nothing was recorded or kept.
IT · established · [statuto-art-4] · An agreement with the union representatives, or failing that an authorization from the labor inspectorate, is required before installing the traffic inspection.
NL · established · [wor-27] · The works council has to consent before any arrangement governing the traffic inspection is adopted, amended, or withdrawn.
ES · established · [lo-3-2018] · Criteria for use, drawn up with the participation of the workers' representatives, and express prior information to the workers, are required before putting the traffic inspection into operation.
BE · established · [be-cct-81] · What is collected is aggregate and by workstation. Attributing it to a worker is a separate operation with conditions of its own.
NO · established · [no-innsyn-epost] · Monitoring a worker's use of electronic equipment, internet use included, is not open to the employer at all unless the purpose is administering the network or detecting and resolving a security breach in it.
AT · established · [at-arbvg-96] · The works council's consent is the condition of the traffic inspection having legal effect, and the threshold is whether it touches human dignity.
DE · established · [bsi-grundschutz] · Proxies that break the encrypted connection should be placed at the boundary to external networks so that what passes can be examined, they are themselves protected from unauthorized access, and security relevant events on them are detected automatically. An organizational rule is to be drawn up stating the data protection conditions under which the log data may be evaluated by hand.
GB · established · [uk-monitoring-regs] · Inspection that amounts to interception in the course of transmission is authorized only on the express consent of the system controller, only for a purpose in the list, and only where it is effected solely to monitor or record communications relevant to the activities carried on and the system is provided wholly or partly in connection with them.

### MD006 · Electronic mail and collaboration monitoring {#md006}
What it is: The recording of what passes through the organization's messaging and collaboration platforms.

EU · established · [gdpr] [wp249] · A ground under article 6 has to be identified before anything is collected through the recording of the messaging platform, and whatever more specific rule the member state has made under article 88 applies on top of it. Consent is not that ground in an employment relationship.
CoE · established · [barbulescu] · Private life and correspondence extend into the workplace, including where a worker's private use of a work device breaks the employer's rules, and a monitoring measure is to be assessed against six criteria, prior notification and the availability of a less intrusive method among them. The case was decided on that monitoring itself: the employer read the content of a worker's messaging account.
FR · established · [code-travail-controle] · The committee has to be informed and consulted before the decision to record the platform, and the worker informed that what passes through it is kept.
DE · established · [betrvg-87] · The works council has to agree before introducing the recording of the messaging platform, and again on the manner in which it is used.
IT · established · [statuto-art-4] · An agreement with the union representatives, or failing that an authorization from the labor inspectorate, is required before installing the recording of the messaging platform.
NL · established · [wor-27] · The works council has to consent before any arrangement governing the recording of the messaging platform is adopted, amended, or withdrawn.
ES · established · [lo-3-2018] · Criteria for use, drawn up with the participation of the workers' representatives, and express prior information to the workers, are required before putting the recording of the messaging platform into operation.
FI · established · [fi-privacy-working-life] · Retrieval of messages belonging to the employer is open only after the employer has arranged the absence alternatives in section 18, and only on the four conditions in section 19, with a signed report of the retrieval given to the employee.
NO · established · [no-innsyn-epost] · The mailbox provided for the work is reached only where it is necessary for daily operations or another legitimate interest, or on reasonable suspicion of a gross breach of the duties of the employment or of grounds for dismissal. The same holds for what was deleted from it and survives on a backup.
AT · established · [at-arbvg-96] · The works council's consent is the condition of the recording of the messaging platform having legal effect, and the threshold is whether it touches human dignity.
GB · established · [uk-monitoring-regs] · Recording what passes through the employer's own messaging system is interception in the course of transmission. It is authorized on the express consent of the system controller, for a purpose in the closed list, and on four conditions, of which the third is that the system controller has made all reasonable efforts to inform every person who may use the system that communications transmitted by it may be intercepted.

### MD007 · Retention of communications metadata {#md007}
What it is: The retention of the transmission data of a message: its parties, times, size, and routing.

IT · established · [garante-364-2024] [garante-243-2025] [garante-165-2026] · Twenty-one days is the outer limit before the article 4 route is engaged, and the limit reaches the envelope only: parties, times, size, and routing.

### MD008 · Access to the content of communications {#md008}
What it is: The opening and reading of the content of a communication, for a stated purpose and on a named person. It is an event, done at a moment and answerable for itself, and it is separate from holding a copy of the store the message sits in.

EU · established · [wp249] · The balance has to be struck before the content is opened, and it is struck differently for technology used outside the workplace than inside it.
CoE · established · [barbulescu] · Correspondence keeps its protection even where private use of a work device breaks the rules, so the six criteria apply to opening it and not only to logging it.
IT · established · [cassazione-24204-2025] · What is taken from personal correspondence on a company system cannot be relied on afterwards, so opening it forecloses the use of what it yields.
ES · established · [lo-3-2018] · Content may be looked at only to check that work obligations are being met and that the device is sound, and no further.
FI · established · [fi-privacy-working-life] · Opening is done with the system administrator and a second person present, and the report states which message was opened, why, when, by whom, and to whom its content was given.
NO · established · [no-innsyn-epost] · Where it is possible the worker is told first, given the chance to comment, and allowed to be present with a representative of their choosing. Where it was not possible, they are told in writing once the access is done.
GB · established · [uk-ipa-2016] [uk-monitoring-regs] · Intercepting a communication in the course of its transmission without lawful authority is a criminal offence. A person with a right to control the operation or use of a private system, or who has that person's express or implied consent, is outside the offence, so an employer reading on its own system does not commit it by that route. What the offence does is put the question of authority before the question of proportionality. As to that authority, opening the content in transmission is what these regulations authorize, and they authorize it only for a purpose in the closed list and only where the interception is effected solely to monitor or record communications relevant to the activities carried on.

### MD009 · Retention of web and network activity records {#md009}
What it is: The retention of a record of the network resources a worker reached, and when.

IT · established · [garante-243-2025] [garante-165-2026] · Browsing logs are an instrument from which remote monitoring may follow, so retaining them engages the article 4 route as metadata does.
NO · established · [no-innsyn-epost] · A record of what the worker reached may be kept where the purpose is administering the network or detecting and resolving a security breach in it, the regulation putting other purposes outside what the employer may do.

### MD010 · Mailbox and file store imaging {#md010}
What it is: The holding of a copy of a named worker's mailbox or file store as a whole, taken and kept whether or not anyone opens it. It is a state and not an event, which is what separates it from reading the content of a communication: an organization can hold an image it never opens, and can read a message it never imaged. What each answers for differs accordingly. The reading answers for its purpose and its proportionality. The holding answers for whether it was declared, and on what basis it is kept.

IT · established · [garante-165-2026] · Holding a mailbox as a whole engages the article 4 route in the same way as retaining the traffic around it, and a former holder retains a claim on what is personal in it.

### MD011 · Privileged session recording {#md011}
What it is: The capture of what is done during a session held under elevated entitlement.

EU · established · [gdpr] [wp249] · A ground under article 6 has to be identified before anything is collected through the session recorder, and whatever more specific rule the member state has made under article 88 applies on top of it. Consent is not that ground in an employment relationship.
CoE · established · [barbulescu] · Private life and correspondence extend into the workplace, including where a worker's private use of a work device breaks the employer's rules, and a monitoring measure is to be assessed against six criteria, prior notification and the availability of a less intrusive method among them. The case concerned the reading of a worker's messages, and whether the criteria reach the recording of a session held under elevated entitlement is not decided in it.
FR · established · [code-travail-controle] · The social and economic committee has to be informed and consulted before the decision to put the session recorder in place, and the worker informed before it reaches them.
DE · established · [betrvg-87] · The works council has to agree before introducing the session recorder, and again on the manner in which it is used.
IT · established · [statuto-art-4] · An agreement with the union representatives, or failing that an authorization from the labor inspectorate, is required before installing the session recorder.
NL · established · [wor-27] · The works council has to consent before any arrangement governing the session recorder is adopted, amended, or withdrawn.
ES · established · [lo-3-2018] · Criteria for use, drawn up with the participation of the workers' representatives, and express prior information to the workers, are required before putting the session recorder into operation.
AT · established · [at-arbvg-96] · The works council's consent is the condition of the session recorder having legal effect, and the threshold is whether it touches human dignity.

### MD012 · User and entity behavior analytics {#md012}
What it is: The automated derivation of a baseline of activity and the treatment of departures from it as signals.

EU · established · [ai-act] [digital-omnibus-ai] · The engine falls in the high-risk category, which brings the full set of obligations, and none of that settles whether the detection method is lawful under data protection or employment law.
CoE · established · [barbulescu] · Private life and correspondence extend into the workplace, including where a worker's private use of a work device breaks the employer's rules, and a monitoring measure is to be assessed against six criteria, prior notification and the availability of a less intrusive method among them. The case concerned the reading of a worker's messages, and whether the criteria reach an engine deriving a baseline from activity is not decided in it.
FR · established · [code-travail-controle] · The social and economic committee has to be informed and consulted before the decision to put the analytics engine in place, and the worker informed before it reaches them.
DE · established · [betrvg-87] · The works council has to agree before introducing the analytics engine, and again on the manner in which it is used.
IT · established · [statuto-art-4] · An agreement with the union representatives, or failing that an authorization from the labor inspectorate, is required before installing the analytics engine.
NL · established · [wor-27] · The works council has to consent before any arrangement governing the analytics engine is adopted, amended, or withdrawn.
ES · established · [lo-3-2018] · Criteria for use, drawn up with the participation of the workers' representatives, and express prior information to the workers, are required before putting the analytics engine into operation.
GB · established · [pathirana-2026] · The models and data sources the research has used are catalogued and untested, so an engine built on them inherits an evidence base nobody has validated.
AT · established · [at-arbvg-96] · The works council's consent is the condition of the analytics engine having legal effect, and the threshold is whether it touches human dignity.
NO · established · [no-nsm] · Knowledge of the normal state of the systems is established and maintained so that a change or an abnormality pointing to unauthorized action can be seen. The maintenance is the requirement: the normal state has to answer to reorganizations, acquisitions, mergers, downsizing, and a change of operating concept. What it is meant to expose is named as data flowing against the flow that was decided, data flowing at abnormal times, and abnormally large volumes.
BE · established · [be-cyfun] · Behavior analytics that learn what is normal and flag departures from it are named among the tools, and so is a class aimed at the misuse of user accounts, stolen credentials and insider threats among what it is said to be for.
CZ · established · [holoska-doucek] · The pattern is built by watching behavior over a long period, and what is looked for against it is named: a person taking an interest in documents from projects they do not ordinarily work on, and a rise in documents pulled down from central repositories onto a workstation.

### MD013 · Physical access monitoring {#md013}
What it is: The recording of entry to and movement within controlled premises.

EU · established · [gdpr] [wp249] · A ground under article 6 has to be identified before anything is collected through the access-control recording, and whatever more specific rule the member state has made under article 88 applies on top of it. Consent is not that ground in an employment relationship.
CoE · established · [barbulescu] · Private life and correspondence extend into the workplace, including where a worker's private use of a work device breaks the employer's rules, and a monitoring measure is to be assessed against six criteria, prior notification and the availability of a less intrusive method among them. The case concerned the reading of a worker's messages, and whether the criteria reach a record of entry to premises is not decided in it.
FR · established · [code-travail-controle] · The social and economic committee has to be informed and consulted before the decision to put the access-control recording in place, and the worker informed before it reaches them.
DE · established · [betrvg-87] · The works council has to agree before introducing the access-control recording, and again on the manner in which it is used.
IT · established · [statuto-art-4] · An agreement with the union representatives, or failing that an authorization from the labor inspectorate, is required before installing the access-control recording.
NL · established · [wor-27] · The works council has to consent before any arrangement governing the access-control recording is adopted, amended, or withdrawn.
ES · established · [lo-3-2018] · Criteria for use, drawn up with the participation of the workers' representatives, and express prior information to the workers, are required before putting the access-control recording into operation.
FI · established · [fi-privacy-working-life] · Access control is named among the systems the cooperation procedure governs, so it is settled with the workforce before it is introduced.

### MD014 · Video surveillance of the workplace {#md014}
What it is: The recording of images of places in which work is carried out.

EU · established · [gdpr] [wp249] · A ground under article 6 has to be identified before anything is collected through the cameras, and whatever more specific rule the member state has made under article 88 applies on top of it. Consent is not that ground in an employment relationship.
CoE · established · [lopez-ribalda] · Cameras without notice have survived where a specific suspicion came first and the scope and duration were held tight. The criteria are weighed, not counted.
FR · established · [code-travail-controle] · The committee has to be informed and consulted before the decision to install the cameras, and the workers informed before they are recorded.
DE · established · [betrvg-87] · The works council has to agree before introducing the cameras, and again on the manner in which it is used.
IT · established · [statuto-art-4] · An agreement with the union representatives, or failing that an authorization from the labor inspectorate, is required before installing the cameras.
NL · established · [wor-27] · The works council has to consent before any arrangement governing the cameras is adopted, amended, or withdrawn.
ES · established · [lo-3-2018] · Camera images may be processed for the control functions in article 20.3, on condition of express prior information to the workers and their representatives.
FI · established · [fi-privacy-working-life] · Cameras are for the security of persons, the protection of property, and the supervision of production, and may not be aimed at a particular employee outside three named cases, nor placed in lavatories, changing rooms, or rooms set aside for personal use. Less intrusive means are examined first, and a notice is displayed where the cameras are.
AT · established · [at-arbvg-96] · The works council's consent is the condition of the cameras having legal effect, and the threshold is whether they touch human dignity.

### MD015 · Geolocation of vehicles and devices {#md015}
What it is: The recording of the position of a vehicle or device issued to a worker.

EU · established · [gdpr] [wp249] · A ground under article 6 has to be identified before anything is collected through the tracking device, and whatever more specific rule the member state has made under article 88 applies on top of it. Consent is not that ground in an employment relationship.
CoE · established · [gramaxo] [mole-mangan] · Tracking a company vehicle through and beyond working hours has survived on its facts, on a bench divided four to three, with the mileage relied on separated from the location data as a whole. A case note reads the majority as having placed the technology itself largely beyond examination, so the survival is weaker authority than it appears.
FR · established · [code-travail-controle] · The social and economic committee has to be informed and consulted before the decision to put the tracking device in place, and the worker informed before it reaches them.
DE · established · [betrvg-87] · The works council has to agree before introducing the tracking device, and again on the manner in which it is used.
IT · established · [cassazione-3462-2026] · Tracking requires notification to the supervisory authority wherever the driver can be identified, and identification through vehicle assignment is enough.
NL · established · [wor-27] · The works council has to consent before any arrangement governing the tracking device is adopted, amended, or withdrawn.
ES · established · [lo-3-2018] · Location data may be processed for the control functions in article 20.3, on the same condition of express prior information.
AT · established · [at-arbvg-96] · The works council's consent is the condition of the tracking device having legal effect, and the threshold is whether it touches human dignity.

### MD016 · Measurement of pace and performance {#md016}
What it is: The derivation of a rate of work from the traces the work itself produces.

EU · established · [gdpr] [wp249] · A ground under article 6 has to be identified before anything is collected through the measurement, and whatever more specific rule the member state has made under article 88 applies on top of it. Consent is not that ground in an employment relationship.
CoE · established · [barbulescu] · Private life and correspondence extend into the workplace, including where a worker's private use of a work device breaks the employer's rules, and a monitoring measure is to be assessed against six criteria, prior notification and the availability of a less intrusive method among them. The case concerned the reading of a worker's messages, and whether the criteria reach a rate of work derived from the traces of the work is not decided in it.
FR · established · [ce-amazon] · Measuring warehouse work through handheld scanners has been found unlawful in its detail, and the fine for it stands at 15,000,000 euros after review.
DE · established · [betrvg-87] · The works council has to agree before introducing the measurement, and again on the manner in which it is used.
IT · established · [statuto-art-4] · An agreement with the union representatives, or failing that an authorization from the labor inspectorate, is required before installing the measurement.
NL · established · [wor-27] · The works council has to consent before any arrangement governing the measurement is adopted, amended, or withdrawn.
ES · established · [lo-3-2018] · Criteria for use, drawn up with the participation of the workers' representatives, and express prior information to the workers, are required before putting the measurement into operation.
AT · established · [at-arbvg-96] · A rate of work derived from statistical, data capture, or micro timing methods is named in its own right among the measures the works council has to consent to, alongside the general requirement for systems that control employees.
GB · established · [ico-monitoring] · Monitoring that may result in financial loss, performance management given as the example, is named among the processing likely to cause high risk.

### MD017 · Monitoring on worker-owned devices {#md017}
What it is: The operation of the program's instruments on equipment owned by the worker.

ES · established · [aepd-ares-capital] · Requiring a worker's own telephone to carry the instruments has drawn infringements of articles 13, 5(1)(c), and 6(1), a fine of 200,000 euros, and an order to bring the processing into line within two months.

### MD018 · Covert monitoring on prior suspicion {#md018}
What it is: Observation conducted without notice, following a specific suspicion already held. The suspicion is what permits the observation, not what the observation is for. Every source in the record that reaches this measure sets conditions on it.

CoE · established · [lopez-ribalda] · The suspicion has to exist before the observation begins, and the scope and duration have to answer to it.
GB · established · [ico-monitoring] · Watching without telling is unlikely to be justified in most circumstances, and where it is, the conditions are set out. It should be authorized only by senior management. An impact assessment must be carried out. There should be grounds for suspecting criminal activity or an equivalent such as gross misconduct, and a view that telling the workforce would prejudice detecting it. It should be strictly targeted at obtaining evidence within a set timeframe, kept to the shortest possible, and it should not continue once the investigation is complete. It should not reach places where a worker would reasonably expect privacy, and in most circumstances it should not capture communications a worker would reasonably expect to be private.

### MD019 · Monitoring outside working hours {#md019}
What it is: Observation continuing when the person is not at work.

EU · established · [wp249] · The balance covers technology used outside the workplace as well as inside it, so continuing after hours does not fall outside the assessment.
CoE · established · [gramaxo] · Observation running through and beyond working hours has survived on its facts, which does not settle that it survives on any others.

### MD020 · Alert triage and case creation {#md020}
What it is: The disposition of what the instruments raise: what is closed, what is held, and what becomes a case.
BE · established · [be-cct-81] · Collecting and naming are two operations. The convention calls the second individualization and governs it separately from the monitoring that produced the data.
EU · established · [nis2-ir] · A suspicious event is assessed against criteria laid down in advance and against a triage that decides what is dealt with first. The relevant logs are reviewed for that assessment, and an event is reassessed and reclassified when new information arrives or when what was already held has been analyzed.
NO · established · [no-nsm] · The log data are gone through and the relevant data about the event gathered to give a decision a basis, which may mean assembling data from several sources or running tests to confirm or rule out an event. The severity is then settled against the plan laid down in advance: whether it is a possible or a confirmed security incident or a false alarm, its class under the classification regime, which roles are brought in, and whether the contingency plan is triggered.

### MD021 · Detection coverage assessment {#md021}
What it is: The holding of two lists against each other: what the program declared it has to be able to detect, and what its instruments actually deliver today, given where the agents are installed, which systems send their records, and which rules are live. Its output is a named gap. Without it coverage is assumed rather than known, and it decays quietly, since a source that stops sending announces nothing.
EU · established · [nis2-ir] · Two lists are required: the assets that are to be logged, derived from the risk assessment, and the assets that are actually being logged. The second, and the procedures behind it, are reviewed and where appropriate updated at regular intervals and after a significant incident. That the two are to be held against each other is not stated.
DE · established · [bsi-grundschutz] · The detection systems in place and the measures taken should be examined in regular audits for whether they are still current and still effective. The metrics that arise when a security relevant event is taken in, reported, and escalated are evaluated, the results of the audit are documented so that they can be followed, and they are compared against the state the systems are supposed to be in. A departure from it is pursued.
ES · established · [es-ens] · Analyzing an incident is what reopens the question of what is audited: the determination of the auditable events is reviewed as a consequence of the analysis.
NO · established · [no-nsm] · It is verified that the collection works as it was meant to. The log settings are checked to see that they function and that what was to be gathered is being gathered, every system that regularly stores security relevant data is given enough space that nothing needed is lost, and a standardized format is used so the data can be read by a third party's analysis tool.

## BA · Behavioral assessment {#ba}
Summary: The derivation of concern from the person rather than from an act.

### BA001 · Risk indicator catalogue {#ba001}
What it is: The defined set of observable circumstances the program treats as bearing on the likelihood of harm.

DK · established · [sok-psychology] · An indicator taken from this literature carries thin foundations with it, and findings that cannot readily be compared between studies.
GB · established · [nurse-2014] · A published vocabulary is available to build the catalogue on: catalyst, actor, attack, and organization, grounded in case studies rather than telemetry.
GB · established · [npsa-data-collection] · Real cases have been reviewed and what preceded the acts described, which is where an indicator can be taken from rather than supposed.
BE · established · [be-cyfun] · Behavioral signs are named as things training should teach people to recognize, and three are given: unusual access patterns, the hoarding of data, and sudden changes in behavior.

### BA002 · Individual risk assessment {#ba002}
What it is: The assignment to a named person of a judgment expressing the degree of concern they warrant.
AT · established · [at-arbvg-96] · A system for assessing employees needs the works council's consent where it gathers data the operational use does not justify, and here the consent can be replaced by a decision of the conciliation board.

### BA003 · Multidisciplinary case review {#ba003}
What it is: The examination of a person's situation by security, human resources, and legal together, rather than by any one of them.
CZ · established · [holoska-doucek] · The examination is divided between three functions rather than held by one. Security analysts secure, process, and interpret the digital traces. Human resources holds the communication with the person and the impartial and dignified treatment of them, coordinates the other teams, documents the examination, and makes the final assessment against the organization's own rules. Legal answers for its conformity with the law of the state and of the sector, evaluates what is found, and states where a public authority has to be told. The person's line manager usually takes part, to supply the context of the activity that was observed.

### BA004 · Use of psychological and dispositional indicators {#ba004}
What it is: The treatment of traits, psychological states, or situational factors as grounds for attention.

DK · established · [sok-psychology] · What has been published on psychological indicators does not establish which of them are observable in an employment setting.
GB · established · [pathirana-2026] · Reviews of the detection literature map which human factors have been modelled and on what data, and test none of them.
FI · established · [fi-privacy-working-life] · A personality or aptitude assessment is taken with the employee's consent, and the employer answers for the reliability of the method, the expertise of the assessor, and the findings being free from error.
EU · established · [gdpr] · Article 9 reaches an indicator only where it reveals one of the categories it closes off, data concerning health among them, and where it does the processing is prohibited unless one of that article's own grounds applies. An assessment of disposition that reveals none of them is not caught by it, and falls back on the ordinary grounds.

### BA005 · Use of linguistic indicators {#ba005}
What it is: The derivation of concern from a person's written or spoken language.

GB · established · [insider-language-index] · The differences were measured in interview language, so an index built on the ordinary flow of workplace communication is extrapolating beyond what was observed.

### BA006 · Inference of emotional state {#ba006}
What it is: The derivation of a person's emotional state from observable data.

EU · established · [ai-act] · Inferring emotion at work is prohibited outright, with narrow exceptions for medical and safety purposes.

### BA007 · Automated decision-making about a worker {#ba007}
What it is: A decision producing effects for a worker taken by automated means without human intervention.

EU · established · [ai-act] [digital-omnibus-ai] [gdpr] · A person has the right not to be subject to a decision taken solely by automated processing, profiling included, that produces legal effects concerning them or affects them similarly significantly. It is open only on contractual necessity, on a Union or member state law that lays down safeguards, or on explicit consent, and on the first and the third of those the person is owed at least human intervention, the chance to put their point of view, and the right to contest the outcome. Such a decision may not rest on the article 9 categories at all save on two narrow grounds. Separately, a decision of this kind falls in the high-risk category, and the obligations that follow apply from 2 December 2027.
GB · established · [uk-gdpr] · The rule here is not the Union's. A decision is based solely on automated processing where there is no meaningful human involvement in taking it, and how far it was reached by profiling is among the things to be weighed in judging whether the involvement was meaningful. A decision is significant where it produces a legal effect or a similarly significant one. The prohibition on taking such a decision by machine alone bites only where it rests entirely or partly on the closed categories, or where the processing relies on the recognized legitimate interests ground. Outside those it may be taken by machine alone, provided the safeguards are in place: the person is informed of the decision, can make representations about it, can obtain human intervention, and can contest it.

### BA008 · Deployment of an algorithmic system in employment {#ba008}
What it is: The introduction of a system of that class in a setting in which the people it reaches are workers.

EU · established · [ai-act] [digital-omnibus-ai] · The system falls in the high-risk category on the ground of where it is deployed rather than of what it does, and the representatives have to be told before it is put into use.
AT · established · [at-arbvg-96] · A system for the automated collection, processing, and transmission of a worker's personal data beyond general particulars and qualifications needs the works council's consent, unless what is done with the data goes no further than obligations arising from statute, collective norms, or the contract.

### BA009 · Model validation and bias testing {#ba009}
What it is: The examination of an assessment method for accuracy and for differential effect before and during its use.

GB · established · [pathirana-2026] · The evaluation methods used across the published work have been mapped, which is the starting point for validating one.
EU · established · [ai-act] · The training, validation, and testing sets behind a high-risk system fall under data governance practices, and what those have to cover is listed: the design choices, where the data came from and, for personal data, what they were originally collected for, the assumptions about what the data are supposed to measure, an examination for biases likely to bear on health and safety, to affect fundamental rights adversely, or to lead to prohibited discrimination, especially where the outputs feed the inputs of later operations, and measures to detect, prevent, and mitigate what the examination finds. The sets are to be relevant, sufficiently representative, and so far as possible free of errors and complete, with statistical properties appropriate to the people the system is to be used on.

### BA010 · Disclosure of an assessment to its subject {#ba010}
What it is: The communication to a person of the existence and content of an assessment concerning them.
FI · established · [fi-privacy-working-life] · The person assessed is given a written statement on the assessment free of charge on request, and where the employer received it orally, its content is told to them.

## IV · Investigation and digital forensics {#iv}
Summary: The examination of an identified person, and the handling of the material on which it rests.

### IV001 · Internal reporting channel {#iv001}
What it is: The route through which a person inside the organization reports a concern about another, and the protection owed to them for doing so.

GB · established · [npsa-ongoing-persec] · Reporting routes are treated as a control in their own right, and their value as depending on whether they are trusted.
DE · established · [bsi-grundschutz] · Reporting routes suited to each kind of incident should be built, so that an employee can report quickly and simply over channels that are reliable and can be trusted, and where a central point is set up for it that is communicated to everyone. A communication and contact strategy should state who must be informed and who may be, by whom, in what order, and in what depth, and who passes information about an incident outside. That nobody unauthorized passes it on is to be ensured.
NL · established · [nl-bio2] · Everyone, internal and external, has demonstrably taken notice of the procedure for reporting an information security incident.
AT · established · [at-ishb] · The routes by which something conspicuous in the logs is reported onward are to be laid down, alongside the fixing of who is responsible for the evaluation that found it.
BE · established · [be-cyfun] · Staff are to be trained on how and where to report suspicious activity and on why reporting it in time matters, and the organization is to promote a culture in which an employee feels safe reporting a concern without fear of retaliation.

### IV002 · Case intake and triage {#iv002}
What it is: The assessment of what arrives, from any route, against a threshold for opening a case.

GB · established · [npsa-data-collection] · The threshold has real cases to be set against: how the acts occurred and what preceded them, in a national population now some years old.
BE · established · [be-cyfun] · The criteria for categorizing, prioritizing, and escalating are documented in the response plan and applied consistently, and the indicators that guide the prioritizing are named as the scope, the severity, and how time sensitive the matter is.

### IV003 · Authorization to open a case {#iv003}
What it is: The decision, and the person entitled to take it, that moves examination from a population to an identified person.
BE · established · [be-cct-81] · Individualization is direct where the monitoring pursued the first three purposes. Where it pursued observance of the undertaking's own rules, it is open only after the workers have been told an anomaly was found and warned that a further one of the same kind will be attributed.

### IV004 · Investigation plan and scope {#iv004}
What it is: The statement, made before the work, of what will be examined and what will not.
DE · established · [bsi-grundschutz] · A forensic examination should begin by defining its objectives, or the work it has been asked to do, as concretely as they can be put, and only then identifying the data sources it needs. A written guide should set out how evidence is to be secured, naming the procedures, the technical tools, the legal conditions, and what has to be documented.

### IV005 · Forensic acquisition {#iv005}
What it is: The capture of data from a device or system in a manner that preserves what it contained.

EU · established · [nth-haustechnik] · What a court admits has to be confined to the adequate, relevant, and necessary, and anonymization or pseudonymization considered before it goes to other parties.
NO · established · [no-innsyn-epost] · The access is carried out so that the data are so far as possible not altered, and so that what it produced can be checked afterwards.
DE · established · [bsi-grundschutz] · The order in which data are secured follows how volatile they are: what is quickly lost is taken first, then what is not, the contents of fixed storage, and last of all the backups. A storage medium should be duplicated forensically in full, and where that cannot be done, on memory or on a storage network partition, the method chosen is the one that alters least. Originals are kept sealed, written cryptographic checksums are made of them and held separately in several copies and secured against alteration, and for the result to be usable in court a witness should confirm how it was done and attest the checksums. Only trained staff or a forensic service provider should carry out the securing.
BE · established · [be-cyfun] · The sequence of events is reconstructed and the systems, assets, and resources involved identified, with forensic analysis used on the collected data where it is needed, and the analysis is to reach the underlying systemic cause rather than stopping at what triggered the event.

### IV006 · Chain of custody {#iv006}
What it is: The unbroken record of who held what, when, and in what state.
DE · established · [bsi-grundschutz] · Every step taken in securing evidence should be documented, and the documentation should show without a gap how the original evidence was handled, which methods were used, and why the people responsible chose them. The originals should be stored so that only the staff conducting the examination, known by name, can reach them.
BE · established · [be-cyfun] · Everyone involved in the response records what they did, in a way that prevents the record being tampered with or deleted, and the lead is answerable for documenting the whole investigation, its timelines, its decisions, and the sources of what it relied on. The incident data and their metadata, the source and the time of collection among them, are collected and protected so that they stay accurate, authentic, and traceable to where they came from.

### IV007 · Legal hold and preservation {#iv007}
What it is: The suspension of ordinary deletion over material bearing on a matter under examination.
DE · established · [bsi-grundschutz] · It should be settled in advance which secondary data, log data and traffic captures among them, are held against a possible securing of evidence, in what way, and for how long within what the law allows.
NL · established · [nl-bio2] · An incident and everything needed to analyze and resolve it are kept for at least three years, and what that covers is named: the logging, the resolution, and the advice given.

### IV008 · Use of records held for other purposes {#iv008}
What it is: The examination, for the purposes of a case, of records the organization holds for unrelated reasons.

IT · established · [garante-107-2026] · Records held by line management are the same material by another route: reaching into them needs the ground the monitoring system would have needed.

### IV009 · Interview of the subject {#iv009}
What it is: The questioning of the person under examination, and the safeguards owed to them during it.

### IV010 · Decision record {#iv010}
What it is: The record of what was examined, on what basis, by whom the decision was taken, and what was concluded.
FI · established · [fi-privacy-working-life] · Both the retrieval and the opening are written up, signed by those who carried them out, and submitted to the employee without undue delay.
NO · established · [no-innsyn-epost] · The written notice states the method of access used, which messages or documents were opened, and what the access found.
ES · established · [es-ens] · Every action bearing on the handling of an incident is recorded, the initial, intermediate, and final reports among them. Evidence that may have to be settled before a court is recorded as such, and the decree names when that matters most: where the incident may lead to disciplinary action against internal staff or an external supplier, or to the prosecution of an offense. Specialized legal advice is taken on what those evidences have to comprise.

### IV011 · Engagement of external investigators {#iv011}
What it is: The instruction of a party outside the organization to conduct or assist the examination.
DE · established · [bsi-grundschutz] · An organization without a forensic team of its own has to identify possible service providers in the preparation phase, before there is anything to examine, and to document which of them come into question. Call-off agreements or framework contracts with them should be concluded so that an incident can be examined sooner.

### IV012 · Case closure and disposition {#iv012}
What it is: The formal ending of a case, the conclusion recorded, and what becomes of the material.
DE · established · [bsi-grundschutz] · A period is fixed for how long secured originals and evidence are kept, and when it has run out it is examined whether they still have to be. After it, evidence should be securely deleted or destroyed and the original media returned.

### IV013 · Investigator competence {#iv013}
What it is: The qualification, training, and independence of the people who conduct examinations.
DE · established · [bsi-grundschutz] · Everyone who is responsible for it should know how to secure traces correctly and how to use the forensic tools, and suitable training should be given for that.

## IR · Incident response {#ir}
Summary: The measures taken while an incident is open: containment, preservation, and notification.

### IR001 · Insider incident playbooks {#ir001}
What it is: The prepared sequences for the insider scenarios the program has decided it must be able to answer.
EU · established · [nis2-ir] · Response follows documented procedures and is given in good time, and the stages those procedures have to include are named: containment, so that the consequences do not spread, eradication, so that the incident does not continue or return, and recovery where it is needed.
IT · established · [acn-379907] · A plan for handling incidents and notifying the national CSIRT is defined, implemented, kept current, and documented, and it carries the stages and the procedures with the roles and responsibilities attaching to each, the contacts for reporting, how communication runs inside and outside, and the reporting to be used to document the incident. The management bodies approve it. That the scenarios it covers include insider ones is not stated.
DE · established · [bsi-grundschutz] · A policy on handling security incidents has to be drawn up, stating its purpose and its aim and settling every aspect of the handling, with rules of conduct described for the different kinds of incident and instructions that are addressed to their audience and can actually be applied. It has to be known to everyone, agreed with the IT function, adopted by the leadership of the organization, and checked and updated at intervals.

### IR002 · Containment of an incident in progress {#ir002}
What it is: The interruption of activity while it is happening, before its nature has been established.
EU · established · [nis2-ir] · Containment is the first of the named stages of the response, and what it is for is stated: to prevent the consequences of the incident from spreading.
ES · established · [es-ens] · At the high category the system carries out predetermined responses to its own alerts automatically, and the decree names them: ending the process that caused the alert, disabling particular services, disconnecting users, and blocking accounts.
BE · established · [be-cyfun] · The response strategy is to weigh the need for a rapid recovery against what might be gained by observing the behavior for longer or investigating it more deeply, which makes the decision to contain a decision and not a reflex.

### IR003 · Withdrawal of access during a case {#ir003}
What it is: The removal of a person's entitlements on suspicion, before any finding.
ES · established · [es-ens] · At the high category the system carries out predetermined responses to its own alerts automatically, and two of the four named reach the person: disconnecting users, and blocking accounts. The decree puts them under the detection measure, so what triggers them is an alert and not a finding.

### IR004 · Preservation of systems and records {#ir004}
What it is: The holding of systems and records in the state they were in when the case opened.
EU · established · [nis2-ir] · The activities of the response are logged under the same procedures that govern the logging of everything else, and evidence is recorded. In what state a system is to be held, and for how long, is not stated.

### IR005 · Coordination with security operations {#ir005}
What it is: The joint working of the insider function with the teams that answer external intrusion.
DE · established · [bsi-grundschutz] · The interfaces between ordinary fault handling, emergency management, and security management are to be analyzed, and the resources they might share identified. The staff who handle ordinary faults are to be made aware of what handling a security incident involves, and security management should have read access to the incident management tools in use.

### IR006 · Notification to a supervisory authority {#ir006}
What it is: The reporting of the incident, or of its handling, to an authority outside the organization.
EU · established · [nis2-ir] · Communication plans and procedures are established with the incident response teams or, where applicable, the competent authorities, for the notification of an incident.
IT · established · [acn-379907] · The plan carries the procedures for preparing and sending the reports the NIS decree requires, and it names the contacts through which an incident is reported. Notification runs to CSIRT Italia.
CZ · established · [holoska-doucek] · It falls to the legal function to state where an incident has to be reported to a public authority, and where personal data have been lost the supervisory authority is to be told without undue delay.

### IR007 · Notification to affected persons {#ir007}
What it is: The telling of the people whose data or whose position the incident affected.
IT · established · [acn-379907] · Procedures are documented for telling the recipients of a service, without unjustified delay, of a significant incident that may bear adversely on the provision of that service, and for telling those exposed to a significant threat what its nature is and what they can do about it. Separate procedures cover informing the public where the agency orders it.

### IR008 · Escalation to crisis management {#ir008}
What it is: The passing of a matter to the body that decides for the organization as a whole.
IT · established · [acn-379907] · How communication runs inside the organization is part of the plan, and the involvement of the administrative and management bodies is named as part of it. Those bodies approve the plan itself.
DE · established · [bsi-grundschutz] · The handling of a security incident is to be settled with emergency management, and where the organization keeps a separate role for ordinary fault handling that role is brought in too. The interfaces to crisis and emergency management are defined and documented, which staff answer for which task is settled, how they are to be communicated with is settled, and the contact people are to be reachable at all times.

### IR009 · Post-incident review {#ir009}
What it is: The examination, after the fact, of what the program saw, when, and what it did with it.
EU · established · [nis2-ir] · A review after the fact is carried out once recovery is done, where appropriate. It identifies the root cause where that can be done and produces documented lessons, and what those lessons are to improve is named: the approach to security, the treatment of risk, and the procedures for handling, detecting, and responding. Whether incidents led to a review at all is itself checked at planned intervals.
IT · established · [acn-379907] · The plan is reviewed and where appropriate updated periodically and in any case at least every two years, and again whenever a significant incident occurs, with the lessons learned from it worked in.
DE · established · [bsi-grundschutz] · An incident should be worked through afterwards to a standard form, examining how quickly it was detected and remedied, whether the reporting routes worked, whether there was enough information to assess it, and whether the detection measures were effective. What is learned is used to write instructions for comparable incidents, made known to the groups they concern, and updated as more is learned. The leadership of the organization is told about the incidents once a year, and at once where something has to be done immediately.
NO · established · [no-nsm] · What worked and what can be improved are both identified. The controls that were compromised are mapped and reviewed and then updated or replaced, and it is assessed whether what is in place covers the organization's risk picture at all. The processes, procedures, reporting formats, and organizational structures are evaluated for how effective they were, regularly and after an incident.

### IR010 · Exercising the response {#ir010}
What it is: The rehearsal of the playbooks against a scenario, with the people who would run them.
EU · established · [nis2-ir] · The incident response procedures are tested at planned intervals.

## CP · Consequence for the person {#cp}
Summary: The action taken against a person following a finding, and the basis on which it may be taken.

### CP001 · Disciplinary action on monitoring evidence {#cp001}
What it is: Action taken against a person on the basis of what the program observed, short of ending the relationship.
AT · established · [at-arbvg-96] · A workplace disciplinary code has no legal effect without the works council's consent, so what may follow from what the program observed is settled with the workforce before any case arises.
EU · established · [nis2-ir] · A disciplinary process for handling violations of the security policies is established, communicated, and maintained, and it takes the legal, statutory, contractual, and business requirements into account. It is reviewed at planned intervals and when a change in the law calls for it. What may be relied on to establish a violation is not addressed.
CZ · established · [holoska-doucek] · The final assessment of the examination is made against the organization's own rules and recommendations, and it is from that assessment that disciplinary proceedings follow, where they follow.

### CP002 · Termination of employment {#cp002}
What it is: The ending of the employment relationship on that basis.

CoE · established · [gramaxo] [lopez-ribalda] · Dismissal on geolocation and dismissal after covert cameras have both been examined under article 8 and survived on their facts, which settles the method and not the outcome.
FI · established · [fi-privacy-working-life] · Recordings may be used to substantiate the grounds for ending an employment relationship, and that use is stated as an exception to the purpose limitation and to the cooperation procedure.

### CP003 · Consistency of outcomes {#cp003}
What it is: The comparison of a proposed outcome against those reached in comparable cases.

### CP004 · Reliance on material obtained in breach {#cp004}
What it is: Reliance in proceedings on material gathered otherwise than as a legal requirement allowed.

EU · established · [nth-haustechnik] · Material obtained in breach is not barred from proceedings by that alone, and a failure to inform the person does not bar it either.
IT · established · [cassazione-24204-2025] · Material taken from personal correspondence could not be relied on, the Strasbourg case law being applied in the national setting.

### CP005 · Referral to law enforcement {#cp005}
What it is: The passing of a case, and the material supporting it, to an authority with powers the organization does not have.
ES · established · [es-ens] · Evidence that may fall to be settled before a court is recorded as such, and the prosecution of an offense is one of the three cases the decree names for it, alongside disciplinary action against internal staff and against an external supplier. What that evidence has to comprise, and in what detail, is settled on specialized legal advice.

### CP006 · Civil recovery and injunctive action {#cp006}
What it is: Proceedings brought by the organization to recover what was taken or to restrain its use.

### CP007 · Communication of the outcome to the person {#cp007}
What it is: The telling of the person what was concluded about them.


## AW · Awareness and training {#aw}
Summary: The instruction of the workforce concerning the program, and the record of it.

### AW001 · Workforce awareness on insider risk {#aw001}
What it is: The instruction of the workforce in what the program is, what it asks of them, and what it protects.

EU · established · [help2protect] · A Union-funded platform carries an awareness module and downloadable templates, addressed mainly to transport, energy, and other critical infrastructure operators.
EU · established · [coess-manual] · The Union-funded manual addresses the structure of a program rather than the conditions attached to one, and has not been revised since 2019.
GB · established · [npsa-digital-learning] · Awareness is delivered as a course rather than a notice, in modules of ten to twenty minutes, with governance and leadership taught before the controls.
EU · established · [nis2] [nis2-ir] · Basic cyber hygiene practices and cybersecurity training are named among the measures an entity in scope has to take, and the implementing rules say what the awareness program holds: it is scheduled over time so that it repeats and reaches new employees, it covers the threats, the measures in place, and where to go for advice, it reaches direct suppliers and service providers as well as employees and the members of the management bodies, and it is tested for effectiveness where appropriate. What is asked to be taught is the security of systems, not insider risk.
IT · established · [acn-379907] · A training plan for the workforce, the administrative and management bodies included, is defined, implemented, kept current, and documented, and those bodies approve it. It sets out what is taught and, where any are provided for, how it is checked that the content was taken in. What it teaches is the security of systems, not insider risk.
ES · established · [es-ens] · The workforce is reminded periodically of the security rules on the proper use of the equipment and of the commonest social engineering techniques, of how to identify an incident and the activities or behaviors that are suspicious and have to be reported so that specialized staff can deal with them, and of the procedure for reporting, whether what is reported turns out to be real or a false alarm.
NO · established · [no-nsm] · Real cases from the handling of incidents are to be used in the training and the raising of awareness of staff, and the results of an evaluation are shared with those they concern.
NL · established · [nl-bio2] · Everyone using the information systems, employees and contractors alike, has demonstrably completed an awareness training within three months of entering service. Management is to press the importance of it at appointment and at an internal transfer, and in work meetings and personnel discussions, and to encourage it being taken again periodically.
BE · established · [be-cyfun] · Insider threat awareness and reporting are to be included in the security training, by name, so that people can recognize and respond to internal risks. What the training covers is set out: how to recognize the behavioral signs, what an insider threat is, how and where to report suspicious activity and why reporting in time matters, and real cases or simulations used to show what an insider event costs. It reaches all staff, at onboarding and in the regular training, with an annual refresher.

### AW002 · Transparency notice on what is observed {#aw002}
What it is: The account of the program's reach given to the persons subject to it.
FI · established · [fi-privacy-working-life] · What the workforce is told after the procedure is the purpose of the monitoring, its introduction, the methods used, and the terms on which electronic mail and the network may be used.
BE · established · [be-cct-81] · What each worker is told at installation is the monitoring policy, the purposes, whether personal data are kept and where and for how long, whether the monitoring is permanent, and what the employer and the supervising staff may do.
NO · established · [no-aml-kontroll] · Before the measure starts, those affected are told its purpose, what it will mean in practice, how it will be carried out, and how long it is expected to last.
IT · established · [garante-itas-2026] · A backup of the mailboxes described in none of the notices given to the staff leaves them unable to know it exists, which is the finding rather than the keeping itself.
NO · established · [no-nsm] · The workforce is informed of what is collected, what it is to be used for, and how the data are to be handled, and that sits alongside establishing which laws apply and deciding how long the data shall and may be stored.
GB · established · [uk-monitoring-regs] · The system controller has to have made all reasonable efforts to inform every person who may use the system that communications transmitted by it may be intercepted. Everyone who may use it, not everyone employed, and reasonable efforts rather than acknowledgement.
GB · established · [ico-monitoring] · Workers must be made aware of how and what personal information is collected. A system could be set up so that they remain aware that monitoring is taking place, through an intranet or signage in the areas it reaches. The privacy information must be kept up to date, and workers must be told when a change is introduced.

### AW003 · Role-specific training {#aw003}
What it is: The additional instruction given to managers, privileged users, and the people who run the program.
EU · established · [nis2-ir] · The employees whose roles need security-relevant skills are identified and trained regularly, and the training program sets the needs of particular roles and positions against criteria. What the training covers is named: secure configuration and operation of the systems, mobile devices included, a briefing on known threats, and how to behave when a security-relevant event occurs. It is given again to staff who move into such a role, and its effectiveness is assessed.
IT · established · [acn-379907] · Training dedicated to the people in specialized roles, system administrators named among them, is part of the same plan, and it covers the secure configuration and operation of the systems, the threats that are known, and what to do when an event bearing on security occurs.
DE · established · [bsi-grundschutz] · Where the protection need is raised, particular people should be given the task of watching the logging data, it should be the greater part of what they do, and they should be given specialized further training and qualification. A group should be named that is responsible for the evaluation of logging data and for nothing else.
ES · established · [es-ens] · The workforce is trained regularly in what their duties require of them, and three subjects are named: the configuration of systems, the detection of and reaction to incidents, and the handling of information on any medium, which is to cover its storage, transfer, copying, distribution, and destruction. The effectiveness of the training given is assessed.
BE · established · [be-cyfun] · Training specific to the role is to be given to the staff who reach sensitive data or systems, on the responsibilities that reaching them carries, and cross-functional training is to be built where two kinds of expertise have to meet.
GB · established · [ico-monitoring] · The people who handle what monitoring produces should be trained to handle it, and they are to be identified as the appropriate people for that rather than reached by default.

### AW004 · Training records {#aw004}
What it is: The record, attached to a named person, of the instruction they received and when.
IT · established · [acn-379907] · An up-to-date register is kept of the employees who received the training, of its contents, and of the checks carried out where checks were provided for. A register of the same kind is required for the training given to specialized roles.
NL · established · [nl-bio2] · The completion of the awareness training within three months of entering service has to be demonstrable, which puts the record of who took it and when inside the requirement.

### AW005 · Simulated exercises on live staff {#aw005}
What it is: The testing of the workforce by means of a staged event.
BE · established · [be-cyfun] · Phishing simulations are to be run regularly to reduce the risk of social engineering, and simulated phishing or social engineering tests are named again among the methods by which an awareness program is evaluated.

### AW006 · Security culture measurement {#aw006}
What it is: The assessment of what the workforce actually believes and does, as distinct from what it has been told.
BE · established · [be-cyfun] · Whether the training reaches everyone it should, and whether it actually moves behavior, awareness, and attitude, is to be assessed. The methods are to be a mix, and surveys measuring the change in awareness, confidence, and behavior are named among them, alongside assessments before and after, simulated tests, and feedback from those who took part and those who taught. What is learned is documented and used on the next round.


