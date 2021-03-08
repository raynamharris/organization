# CFDE DCC PROJECT WORK PLANS

Note: for access to the links contained in this document please see the [Onboarding page](https://cfde-welcome-to-cfde.readthedocs-hosted.com/en/master/General_Onboarding/). This will enable you to use our GitHub repos, mailing list, calendars, and other internal documents. If you are having trouble accessing something you believe you should have access to, please visit our [Fixes for Common Access Problems ](https://cfde-welcome-to-cfde.readthedocs-hosted.com/en/master/General_Onboarding/FixesToAccessProblems/)page or email the [HelpDesk](mailto:autohelp+int+851+6545985337373134556@CFDE.groups.io).
<span style="text-decoration:underline;">
  
The primary principle motivation for project work plans is **clear communication**</span>. The Common Fund Data Ecosystem (CFDE) is a large project that consists of multiple, interoperable, and parallel projects across many teams and timezones. As we work towards building a resilient data ecosystem, the CFDE-Coordination Center (CFDE-CC) and the NIH recognize that CFDE projects are sufficiently complex that no one set of criteria can encompass all aspects of project management. Rather than a fixed set of criteria, this document lays out project management and reporting approaches that should meet most CFDE-CC, DCC, and NIH needs. Exceptions, additions, and alternatives will be explored as needed.

## _Project Plan Generation And Responsibilities_

Awarded DCCs are expected to manage the details of their deliverables, work plans, internal project management, and any cross-Program collaborations. If your deliverables include creating a workgroup, you are also responsible for managing those groups and meetings, however you are welcome to use CFDE-CC infrastructure for them. Your DCC may use any approach to project management for day-to-day work _within_ your organization, however, deliverables must be entered into the DCC project management repo, integrated with ZenHub, and updated regularly. In cases where your deliverables are associated with activities of other DCCs, you should consider including time for a review period with all relevant teams to sign off on joint project deliverables. Your organization will have been given a specific private Github repository to hold your completed workplan. Specific instructions for interacting with Github and Zenhub are outside the scope of this document, [but are available here](https://github.com/nih-cfde/organization/blob/master/projectmanagement/AddingIssuesToEpics.md).

The CFDE-CC is responsible for maintaining the CFDE-wide integrated master schedule, and will import DCC project level information into this schedule. The CFDE-CC is responsible for any ‘all-hands’ meetings, periodic demonstration days, and the scheduling and management of project management meetings between the CFDE-CC and individual DCCs. The CFDE-CC also manages a wide variety of infrastructure which is openly available for use by funded DCCs for their individual and joint work. This infrastructure includes enterprise level Github and Google spaces, Slack, and mailing lists, as well as several tools for advertising and promoting DCC work or events, and event registration. 

## _CFDE-CC meeting cadence_

*   The CFDE-CC will organize a meeting between the Coordination center and all funded DCC project managers to meet as a single group at least monthly for a ‘scrum of scrums’ style meeting to check in on progress, blockers and risks. 
*   The CFDE-CC and each funded DCC will also meet individually at least monthly to check in on any project management related issues. 

## _CFDE-CC Project Management System_

The CFDE-CC uses a combination of Github and Zenhub for project management, and will assist with integrating your plan with the master CFDE schedule. **The following text will walk the reader through the process of creating a project plan that can be integrated with the master system and will fulfill NIH requirements. **

**Process Overview:**

## Table of Contents
[Deliverable Creation](#Deliverable-Creation)
- [Deliverable Description](#Deliverable-Description)

[Sub-Epic Creation](#Sub-Epic-Creation)

[Workplan Submission and Approval](#Workplan-Submission-and-Approval)

[Deliverable Change requests](#Deliverable-Change-requests)

[Appendix](#Appendix)

[Deliverable Evaluation Modes](#Deliverable-Evaluation-Modes)
  * [Evaluation Mode: Peer-to-peer](#Evaluation-Mode:-Peer-to-peer)
  * [Evaluation Mode: Training / Engagement](#Evaluation-Mode:-Training-/-Engagement)
  * [Evaluation Mode: Project-wide Demo](#Evaluation-Mode:-Project-wide-Demo)
  * [Evaluation Mode: Requests For Comment](#Evaluation-Mode:-Requests-For-Comment)

[Program Goals and Objectives](#Program-Goals-and-Objectives)
  + [Goal 1: Enhance the ability to ask scientific questions across data sets](#Goal-1:-Enhance-the-ability-to-ask-scientific-questions-across-data-sets) 
  + [Goal 2: Enable the uptake, reuse, and addition of NIH data and tools from future, current, and ended programs](#Goal-2:-Enable-the-uptake,-reuse,-and-addition-of-NIH-data-and-tools-from-future,-current,-and-ended-programs)
  + [Goal 3: Support the storage, sharing, and sustainability of CF data sets](#Goal-3:-Support-the-storage,-sharing,-and-sustainability-of-CF-data-sets)
  + [Goal 4: Provide training that maximizes a scientist’s ability to upload data and use CF data and other resources](#Goal-4:-Provide-training-that-maximizes-a-scientist’s-ability-to-upload-data-and-use-cf-data-and-other-resources)

## Deliverable Creation 

### Deliverable Description

The outcomes in your work plan will primarily be deliverables- specific objects or outcomes that show progress and that are formally submitted to the NIH PO. In our project management system, each deliverable is an individual Github issue that has been made into a Zenhub Epic. Epics can be linked to issues from across repositories in the CFDE Github space, and so allow us to easily traverse through complex multi-DCC projects and easily create combined project management tracking systems.

The number of deliverables for a project depends on the length and complexity of the goals, however in an OT award it is best to err on the side of fewer, goal based deliverables, and to stay away from frequent, narrowly specified ones. This is because OT awards typically fund projects that have important goals, but where the specifics of how to implement them are not yet known. However, deliverables must be written up front, and are part of the formal NIH contract. The date, requirements and content of a deliverable can only be changed through negotiation with the NIH PO. Too much detail about uncertain future implementation plans can result in extensive, time-consuming renegotiation of the award if the project needs to change direction.

The text of a deliverable should be brief, but each needs to include the following:

*   **Unique ID**: Deliverables for a project must be given unique identification numbers for ease of reference. 
    *   If a single larger goal will consist of many, phased deliverables, they should all be subsets of the same number (e.g. CFDE Coordination Center goal 5 consists of deliverables 5.1, 5.2, ...)
*   **Title:** A one line summary of the deliverable
*   **Description:** The expected outcome(s) or goal(s). Ideally, this is a use-case to be fulfilled or a description of capacity building
    *   For phased deliverables, include context for how this individual deliverable fits into the larger goal. For stand-alone deliverables, explain how it improves or synergizes with the CFDE
*   **Delivery due date:** The specific day this deliverable will be submitted to NIH. When deciding on dates, be sure to include not only development time, but also the time that you need to test this deliverable and demonstrate it works for the intended audience. We suggest syncing demo-type deliverables with the periodic CFDE demo days.
*   **Internal due date:** The specific day this deliverable will be done internally. For a single DCC deliverable, this might be the date it is made available to your project manager. For joint deliverables, this should be the date that all collaborators have shared their products so cross-testing can happen.
*   **Delivery persistence:** Even if the deliverable is a phased portion of a project, it should be a persistent, minimally viable product on delivery. NIH will expect to be able to re-visit older deliverables even if improved versions are submitted later. If the deliverable would be difficult or impossible to keep persistently, specify why and include a specific date for when the deliverable would become unavailable. In general the NIH expects services to be up indefinitely unless there is a significant cost (time/effort/resources) involved in doing so.
*   **Collaborators** For deliverables that require collaboration with other teams, use labels to denote each other team
*   **Test Case:** Define how you will show this deliverable is complete. What mode of evaluation will be used? Who will do that testing? More details about possible modes of evaluation are available in the appendix. 
*   **Dependencies:** Which (if any) other deliverables must be completed prior to this one. Think: What delays/cancellations in other deliverables could make this take longer than I expect or make it impossible?
*   **Assumptions:** Which (if any) capabilities of other CFDE resources are needed to complete the deliverable. Think: This will only work if the portal supports the X protocol.
*   **Risks:** What (if any) objects, ideas, projects, circumstances outside of the CFDE are currently known as potential problems. This is not meant to be exhaustive, but instead to highlight important ones. Think: This will only be done in December if the RAS group has the X service running by October 1st.
*   **Goal and Objective References:** What NIH Goal Reference(s) and NIH Objective Reference(s) does this deliverable contribute to? [Goal and Objective list](#program-goals-and-objectives)

**Example Deliverable:**

Internal Due Date: &lt;03/23/2021>

NIH Due Date: &lt;03/30/2021>

Milestone: 1.2.2.4

POC: &lt;[@sherry-jenkins](https://github.com/sherry-jenkins)>

*   Short description of deliverable: Establish mechanisms to ensure that metadata for the current and future LINCS datasets can be serialized into the CFDE C2M2. Write the scripts to convert current metadata schemas into frictionless C2M2. Identify asset types which overlap with other CF DCCs. The most reused LINCS data is the data collected via the L1000 assay, a low cost transcriptomics assay. We plan to develop a deep learning model that would make the L1000 data better align with RNA-seq data.
*   Delivery persistence: The LINCS L1000 data will be provided in a format compatible with RNA-seq; Mapped metadata elements that match LINCS metadata element; Scripts to transform LINCS metadata to support ontologies and dictionaries used by other DCCs.
*   Ownership: LINCS DCC
*   Test Case: DCCs with matching metadata will validate the mappings.
*   Dependencies: This deliverable may require other DCCs to map their metadata to LINCS metadata. Decisions about standards that are adopted by the CFDE would need to be decided, although support for multiple standards for the same metadata elements might be an alternative solution.
*   Assumptions: The CFDE-CC portal will be able to ingest the metadata.
*   Risks: The conversion of the L1000 data into RNA-seq-like format may not produce accurate results.
*   Goal and Objective References: 1-3


## Sub-Epic Creation

For each Deliverable, you should create a small (typically 2-5) number of sub-epics that represent the major chunks of work that will be part of that deliverable. Like Deliverables, these should be stored as Epics in ZenHub, and will eventually be where you collect individual issues to track day to day work. (Epics can be nested). We’re defining ‘major chunk’ as something that is, in itself, a multipart high level process, but is smaller than the Deliverable. One way to imagine the sub-epics is as parts of the collaboration that belong to different teams. This framework makes it simple to cross-assign epics and establish cross-group dependencies. These issues should have many of the same parts as a deliverable:

*   **Title:** A one line summary of the work required
*   **Description:** The expected outcome(s) or goal(s). 
*   **Approximate due date:** A non-contractually obligated due date for this portion of the work. This date can change as necessary, but for multi-team projects with dependencies, it’s useful for planning effort
*   **Delivery (if any):** For multi-team projects, specify what product will be sent to the other team and how
*   **Ownership:** For multi-team projects, specify which team is responsible for this Epic 
*   **Test Case (if any):** Define how you will show this Epic is complete. 
*   **Dependencies:** Which (if any) other deliverables/Epics must be completed prior to this one. Think: What delays/cancellations in other projects could make this take longer than I expect or make it impossible?
*   **Assumptions:** Which (if any) capabilities of other CFDE resources are needed to complete the deliverable. Think: This will only work if the portal supports the X protocol.
*   **Risks:** What (if any) objects, ideas, projects, circumstances outside of the CFDE are currently known as potential problems. This is not meant to be exhaustive, but instead to highlight important ones. Think: This will only be done in December if the RAS group has the X service running by October 1st.

## Workplan Submission and Approval

Your award’s work plan will need to be final and approved within the first 30 business days. 

Your work plan consists of: 

*   Fully fleshed out deliverables, as Epics, in your specified github repo
*   High-level decompositions (sub-epics) of each deliverable in your specified github repo, tied to the appropriate epics and accepted by any collaborators
*   An excel version of those finalized issues, as a static record of your starting place

You will need to submit your finished work plan to Lora Kutkat, Chris Kinsinger, and/or Haluk Resat for approval. Note that approval is typically an iterative process, and the NIH will check on progress at 10 and 20 business days.

In addition to looking for the specific information that each deliverable requires, the NIH will also look for things like:

*   Do project timelines align for joint projects/deliverables?
*   Do project goals align for joint projects/deliverables?
*   Do both teams in a joint deliverable agree on who is responsible?
*   Are multiple teams submitting overly similar deliverables that should be combined?
*   Does the scope of a deliverable match the NIH Goal/Objective?
*   Realistic timeframe

## Deliverable Change requests

If you need to change the scope or timing of a deliverable:

*   Post a comment on the github issue for the deliverable that requires a change and include:
    *   What the change is
    *   Why it is needed
    *   What downstream effects this might cause
    *   Note any dependencies
    *   Explicitly tag the NIH PO team @awards
    *   Explicitly tag the main CFDE-CC project managers: @CCadmin
*   Your NIH PO may have follow up questions, which they will post as a comment in that issue, or they may approve the change
*   The CFDE-CC will update the integrated master schedule when/if changes are approved

## Appendix 

### Deliverable Evaluation Modes
For each of your deliverables you will need to describe how to confirm that your deliverable has been completed. In general completed evaluation is expected to result in some form a short report, or a demonstration, and will always be recorded in the CFDE project tracking system upon completion. Several modes of evaluation are available for you to request, and you can use a combination of modes for evaluation. For example in the development of a new analysis tool, you could both peer-to-peer as well as training / engagement to evaluate delivery of that system.  Modes of evaluation are the following: 

### Evaluation Mode: Peer-to-peer 
The CFDE proposals included many plans for joint development across DCCs. These activities are an important driver for collaboration in the CFDE, and will require mutual agreement between sites for expectations and completion of tasks. Your deliverable description will layout most of the expectations and dependencies, and should also describe how the two DCCs will evaluate completion of your deliverables. Peer-to-peer evaluation can be completed by establishing a date for a demonstration, reviewing if the requirements for your deliverables were achieved, and passing on a report of your success to the CFDE-CC project management system.

**Peer-to-peer evaluation, an example**: _two DCCs proposed performing harmonization of data between sites. The relevant groups identify the metadata types that would be used for the harmonization exercise, agree on the scope of activities, create a joint schedule for completion, and provide use-case examples of what users should be able to achieve after the data harmonization is complete. They also schedule a date for completion of this activity. Ideally this would be coordinated with submitting the harmonized data to the CFDE portal. The groups jointly meet for deliverable evaluation to test if the expected outcomes for end-users were achieved. The DCCs would complete a jointly authored report, and submit the report into the CFDE-CC management site._

### Evaluation Mode: Training / Engagement
The CFDE Training Coordination Center (TCC) has an engagement team to on-board new users, facilitate user transitions to cloud-based infrastructure, and minimize strain on tech support. The TCC also provides training, which serves as an opportunity to demonstrate the capabilities of new projects to unfamiliar audiences, and also presents opportunities for early user feedback to support ongoing development of tools and infrastructure. The TCC will serve as a central point of contact for training resources, develop curricula, provide training, and workshop administration. Members of the TCC can also supply qualitative and quantitative evaluation of your deliverables. The TCC can do this in a variety of ways. The TCC has staff with post-doctoral training who can test research-grade software or create tutorial videos of tools you have created.

**Training / engagement evaluation, an example**: _the TCC team will be particularly useful for integration testing of two previously separate systems. Consider a scenario where two DCCs have data that would be useful to combine and use for analysis. For example one site could be hosting expression data, while another site had metabolomic information, and both DCCs had data from common body sites. Both sites proposed performing some harmonization effort to simplify finding data across common anatomical terms, and developed web-based analysis tools that would enable users to the relevant datasets in context of each other. For evaluation, both sites had performed peer-to-peer evaluation of the harmonized data, but have asked the TCC to perform integration testing. The DCCs could provide a README file for the TCC team to follow in order to test the relevant tools. The TCC could then test the analysis tools, generate a jupyter notebook and video documenting use of the tools, and provide feedback to the DCC engineers in cases where bugs prevented their team from completing the testing exercise as well as useful suggestions to improve the documentation, tool or both. _

### Evaluation Mode: Project-wide Demo
The CFDE tech team employs teleconference demos to display functionality implemented in executable form, usually by walking participants through a web-based presentation. In the coming months we will synchronize the activities of the DCCs CFDE projects using "all hands", project-wide demos, during teleconference sessions held roughly 2 times a year. Project wide demos will serve as useful touch points where the activities of multiple teams roll up into a complete set of deliverables. Demos will be used to confirm if requirements associated with relevant deliverables have been met, and to confirm if the demonstrated activities match those described in documented CFDE use cases. As the demos are scheduled well in advance, these sessions serve as common rallying points for demonstrating what the CFDE has achieved. Demos also increase awareness of project components across all of the CFDE consortium and will be useful in promoting integration testing across federated systems. 

**Project wide demo evaluation, an example**: _Generation of a virtual cohort. Prior to the demo, multiple DCCs will have generated asset inventories containing patient metadata, and submitted that information using the C2M2 data model into the CFDE portal. The demo then tests if an end user is able to define a virtual cohort using the CFDE portal to identify a subset of data for an analytic workflow deployed on a system such as Cavatica. Steps for this activity would include:_

*   _Review of the data contents at the portal to confirm submission fidelity;_
*   _Exploration of data collections using persistent identifiers;_
*   _Review of findability of clinical studies using terms submitted by the DCCs;_
*   _Identification of a synthetic cohort of subjects based on phenotypic information;_
*   _Generation of a manifest of the cohort using C2M2 and BDBags;_
*   _Push the manifest to a workspace such as Cavatica;_
*   _Open up a Jupyter notebook and perform a GWAS on the samples_

### Evaluation Mode: Requests For Comment
Requests for Comments (RFCs) will build community consensus for standards, policies, and best practices. We have drafted a process for creating CFDE RFCs [described here](https://docs.google.com/document/d/1ubXIY-SYJmkIWyxrCJgIR-ISWrw9H1_3giwer4Hj67A/edit). In general, RFCs will be used to enable individual DCCs, working groups, or teams to propose the adoption of new standards, and promote adoption of conventions (e.g., interfaces, APIs, data models, management schedules, and policies). **RFCs are not intended to simply broadcast information.** They should be utilized in combination with working groups, DCC-to-DCC collaborations, and consortium-wide presentations to generate broad discussion across as many groups as possible. Authors of RFCs are encouraged to coordinate with the CFDE engagement team to encourage others to participate in RFC generation and approval. 

**RFC evaluation, an example:** _A DCC team develops a unique data model associated with imaging files. The data model has been used by the DCC for displays at their site, the investigators have published on the system in a peer-reviewed journal, and they have received CFDE funding to promote use of the data model by other CFDE consortium members. The team generates a draft RFC which describes the merits of the data model, its scope of use, and provides a comparison of their schema to other competing data models. Those researchers perform a pilot study for how data from another DCC could be stored in the model, and hold working group meetings to generate additional text describing the proof of principle for the RFC. The RFC authors then contact the CFDE engagement team, and suggest specific DCCs that could potentially make use of the data model. The authors supply them with a list of questions to be asked of other sites, the engagement team records responses and generates additional comments to be addressed in the RFC. The authors also engage the C2M2 development group for the data model evaluation, and the RFC is also advertised at face-to-face meetings or other CFDE venues. After rounds of revision the RFC is adopted and the authors consult with the relevant project management teams to identify a potential timeline for incorporation into the CFDE ecosystem. _

## Program Goals and Objectives

The four key goals of the CFDE are detailed below:

### Goal 1: Enhance the ability to ask scientific questions across data sets

        1a. Novel scientific and clinical research is enabled through cross-data set discovery
        1b. A standard Authentication/Authorization (AuthN/AuthZ) strategy is implemented to permit appropriate access to and compute on controlled access data
        1c. (Eval only) CFDE activities are having a positive impact on CF DCCs’ ability to manage and use data

### Goal 2: Enable the uptake, reuse, and addition of NIH data and tools from future, current, and ended programs
        2a. Data and metadata structure, descriptions, and organization are optimized so data can be found and combined across data sets
        2b. Common standards, methods, tools, and processes are provided enabling data managers to load, update, maintain and version, and monitor data sets on the cloud
        2c. Common tools and processes are provided to assess and improve FAIR-ness of data and other digital objects to optimize the query, retrieval, and use
        2d. A central, externally facing, scalable portal is provided, serving as the directory to all CF data sets and tools, FAIR-ness metrics, use cases, and the like
        2e. CF DCCs and their users are engaged in the design of self-governed standards applicable to existing and future CF data programs

### Goal 3: Support the storage, sharing, and sustainability of CF data sets
        3a. CF data sets are stored and managed in cloud environments to increase availability and accessibility of key data sets
        3b. CF Programs use the STRIDES agreements for storage and compute, leveraging
        pre-paid funding from the CF
        3c. NIH retains ownership and oversight of data sets after programs have ended
        3d. Practices and policies that can accommodate new CF programs are adopted

### Goal 4: Provide training that maximizes a scientist’s ability to upload data and use CF data and other resources
        4a. Training material is provided for researchers to access, analyze and understand the CF data sets and tools provided by CF Programs
        4b. Use case scenarios are posted to the Data Ecosystem community
        4c. A Data Ecosystem user guide and site documentation are created and accessible


     
