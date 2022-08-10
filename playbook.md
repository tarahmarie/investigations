# How to Stand Up a Major Cyber Incident Investigations Board


## A guide for independent organizations and state and local governments to develop a sustainable mechanism for investigating and drawing lessons-learned from cyber incidents both in the immediate aftermath of a cyber incident and long-term

Victoria Ontiveros

Tarah Wheeler

Adam Shostack




# Acknowledgements

We would like to thank Rob Knake for initiating this project and guiding it through the early phases during his time as a fellow at the Belfer Center. We would like to thank Bob Lord, Mark Montgomery, and Tatyana Bolt for their thoughtful feedback. Their comments helped clarify our thinking, and their experience with cyber incidents helped us make the guidance offered in this document actionable. Thank you to Lauren Zabierek for her support, encouragement, and feedback throughout the project. Lauren’s perspective and feedback pushed us to answer hard questions throughout the project’s development. We appreciate the insights Andrea Rebora offered on cyber incident response norms and practices. We also wish to thank all of the participants in the workshop Learning from Cyber Incidents, whose comments and discussion also informed this playbook.



**Authors**

**Victoria Ontiveros:** Victoria Ontiveros is a Master in Public Policy candidate at the Harvard Kennedy School of Government where she is focusing on how cybersecurity interacts with foreign policy issues. Her Policy Analysis Exercise at HKS explored how the U.S. can respond to China’s increasing investment in Africa’s telecommunications infrastructure development. 

**Tarah Wheeler:** Tarah Wheeler is CEO of information security consultancy Red Queen Dynamics, and a Cyber Project Fellow at the Belfer Center. She is an International Security Fellow at New America and a US/UK Fulbright Scholar in Cyber Security. She is an Electronic Frontier Foundation advisory board member, as well as a contributor at the Washington Post, the Brookings Institution, and Foreign Policy Magazine. 

**Adam Shostack:** Adam Shostack is a leading expert on threat modeling, and a consultant, entrepreneur, technologist, author and game designer. He's a member of the BlackHat Review Board, and helped create the CVE. Adam also serves as an Affiliate Professor at the Paul G. Allen School of Computer Science and Engineering at the University of Washington.




[TOC]





# Are You in Crisis Mode? Start Here.

**Your organization has experienced a cyber incident, and you have been tasked with forming a group of people to conduct an investigation/review. You’ve come to the right place. Try not to conflate urgent incident response with this investigation board if you can help it. Incident response is very different than thoughtfully setting up an investigation board before you need it, but sometimes that’s not how cybersecurity works, and we understand that.**

**What is a Major Cyber Incident Investigation Board?**

An MCIIB is a group of cybersecurity experts and representatives from academic organizations, government, and the private sector who convene after a cybersecurity incident has occured and lead a review into the incident. 

**How will this document help you?**

This document lays out how to form a Board and how to form a team with technical skill sets needed to conduct an investigation into why the cyber incident occurred, what security systems failed, and what factors contributed to the incident’s severity. **For now, you just need to read the information in the red boxes. Everything you need to know to stand up a Board and conduct an investigation quickly is in there. **The rest of the document goes into details that you don’t need to know right now.

**How does an MCIIB Investigation work?**

There are two components to an MCIIB incident review: the Technical Team’s investigation and the Board’s review. The technical team is a group of professionals with the technical skills to conduct an in depth analysis of how the incident happened. The Board conducts a review of the incident based on the findings derived from the Technical Team’s analysis and will come up with recommendations to prevent a similar incident from happening in the future or decrease its negative impact.

**Opening Board Meeting**

The Board Members meet virtually to receive the details on the cyber incident, select an Investigator in Charge (IIC), and agree on outside companies or organizations to invite to serve as Parties to the investigation. 

**Technical Investigation**

Phase I: Collect data and evidence

Phase II: Perform analysis, develop a timeline and discover open questions

Phase III: Form and test hypotheses

**Closing Board Meeting**

The Board Members meet virtually to discuss and vote on findings of the technical investigation and recommendations to include in the Final Report.

**Distribute the Final Report far and wide.**




# Abbreviations

**MCIIB **Major Cyber Incident Investigations Board

**POS **Point of Sale

**IIC **Investigator In Charge

**CFPB **Consumer Finance Protection Bureau

**CISO **Chief Information Security Officer

**ISAC **Information Sharing and Analysis Centers

**ISAO **Information Sharing and Analysis Organizations

**NTSB **National Transportation Safety Board 


# Introduction

The goal of this document is to provide guidance for any organization that wishes to set up an independent cyber incident review board. The document serves as a blueprint for an independent review board which may be needed by private or public organizations, such as municipalities, counties, hospitals, utilities, or other organizations that anticipate experiencing cyberattacks and wish to maximize their learning from them. We offer considerations and analysis throughout the document to present alternative options and insights. An organization such as a think tank, local or federal government agency, university, or other non-profit organization may also set up a MCIIB. Such a Board would conduct investigations of major cybersecurity incidents and deliver a report outlining the sequence of events, contributing factors, and recommendations for security practices. 

There are three major stages of an investigation: Opening, Technical Investigation, and Board Review.

This document explains how to stand up a board, the tradeoffs which can be made, and the effects of those tradeoffs. We are also aware that investigations are often triggered by crises, and thread guidance for that scenario throughout the document.


## A story from the future

A 2005 breach at a large retailer[^1] can serve as an example of the application of this manual, framing the issues in convening a board, conducting a technical investigation, and issuing a report that helps people understand the attack in future.

The MCIIB of Arkansas[^2] becomes aware that a big-box retail store had recently been the victim of a point-of-sale (POS) and credit card number attack[^3]:

First, the Board convenes for the Opening Board Meeting and agrees to initiate an investigation and review of the incident. At the Opening Meeting the Board will also designate a Board Member to contact the retail company and coordinate the initiation of the investigation. Once the company has either invited the Board to initiate the investigation and agreed to submit evidence, or been compelled to cooperate with the Board’s investigation by a body with the appropriate authority, the Board will select an Investigator in Charge (IIC) who will lead the Technical Investigation and determine whether outside organizations should be invited to serve as Parties to the Investigation. Parties in this case include relevant labor unions, the company’s software vendors, credit card companies, local banks, the local government’s consumer protection department, and the Consumer Financial Protection Bureau[^4] (CFPB). 

 

Second, the IIC will coordinate with the host organization and Parties to form the Technical Team and initiate Phase I of the Technical Investigation, beginning with the collection of evidence and data. Once the Team feels that they have sufficient evidence–such as the malware used in the attack, the cybersecurity systems in place at both local stores and headquarters, how long it took for the data breach to be detected, the vulnerability exploited by the malware– they can move to Phase II and begin to analyze the data and evidence that has been collected thus far. More evidence may need to be collected to support further analysis. When the Team feels that sufficient analysis has been completed, the investigation enters Phase III, where Team Members may propose hypotheses as to contributing factors and the sequence of events that culminated in the incident. Following the example of the NTSB, the team has actively avoided guessing until now, allowing the evidence to tell the story. Throughout the Technical Investigation, a report writer will document the Team’s findings and hypotheses and finalize the Findings Report with approval from the Team Members. The IIC will then send the Findings Report to the Board Members and the Party Representatives. 

 

Third, the Final Board Meeting is scheduled two months after the conclusion of the Technical Investigation. After reviewing the Findings Report in depth, the Party Representatives should submit their Party Recommendation Letters to the Board within a month of receiving the Findings Report. Ahead of the Final Board Meeting, the Board Members familiarize themselves with the content of the Findings Report and the Party Recommendation Letters. At the Final Board Meeting, the IIC will present the Technical Team’s Findings as an overview for the Board and remain for the duration of the meeting to answer any of the Board Members’ questions regarding the Technical Investigation’s procedures or findings. Following the presentation, the Board Members will open discussion as to which findings to include in the Final Report. Each finding is determined by majority vote before the report writer includes it in the Final Report. Once all the findings have been voted on, the discussion shifts to recommendations for the targeted organization and the cybersecurity community. The recommendations are also decided upon through majority vote before they are included in the Final Report. 

 

The report writer will deliver the Final Report to the Board Members for approval no later than two weeks after the Final Board Meeting. Each Board Member will add their signature to the Final Report. Should a Board Member disagree with a finding or recommendation included in the Final Report, they may submit a Letter of Dissent to be appended to the Final Report.

 

Once all Board Members have signed the Final Report or lodged their dissent, the Final Report is sent to all Party Representatives and uploaded to the Board’s website for wide, public dissemination.  



1. Overview of an Independent Cyber Incident Investigations Board 
    1. Definition of a “Major Cyber Incident”

Defining a “major cybersecurity incident” may vary depending on the organization initiating and hosting the Board. 


### Considerations

To determine whether to convene the Board and launch a technical investigation the following factors may be considered:



* Has a similar incident occured before?
* Does a set of standards already exist?
* Would the larger cyber community benefit from an analysis of the incident or is it specific to one or a select few companies?


### Determination

Each independent Board must determine the definition of “major cyber incident” for itself for two reasons. One, the cybersecurity field is constantly evolving; a static definition of “major cyber incident” may be insufficient and ultimately detrimental to the essential work of an independent review board Two, the host organization’s mission and values may influence what an independent review board investigates. Therefore, the definition of a “major cyber incident” should be unique to each Board. 

**CRISIS MODE**

**The triggering incident is a major incident, and the definition will be refined by the board after delivery of their final report.**



    2. Purpose and Role of the Board

**CRISIS MODE**

**The Board will be a group of respected individuals with extensive experience with cybersecurity issues. The Board you create will conduct a review of the facts of the incident and will deliver a report that outlines the facts of the case, their hypotheses, and recommendations for preventing similar incidents from happening or mitigating the impact of such incidents in the future. **

The goal of a Major Cyber Incident Investigations Board must be to conduct an independent analysis of a major cyber incident (including significant near misses), compile a shared history of what occurred, and generate actionable recommendations for cybersecurity actors to execute in order to prevent a similar event from happening in the future. The cybersecurity industry thus far lacks a reputable record of past cyber incidents from which the industry can collectively draw lessons learned[^5]. The Board can serve as an initial step in creating a shared history of cyber incidents and developing recommendations for best practices. 

The creation of an independent board creates an opportunity to bring together respected experts and organizations across the cybersecurity industry to lend their expertise and credibility to much needed analysis of cybersecurity incidents. An independent board is uniquely valuable, because it can develop unbiased analysis of cybersecurity incidents and have a greater degree of flexibility throughout the investigative and review processes. 

The Board differs from the Technical Team in that Board Members need not necessarily have technical expertise. Individuals who do not hold technical expertise but have experience in government regulation or policymaking or who are well-regarded within the cybersecurity community will bring highly valuable experience to the Board. Technical expertise is not needed for Board Members, because the Technical Team will conduct the Technical Investigation and compile their findings and hypotheses in a Findings Report. Thus, Board Members will rely on their experience rather than technical skills to fulfill their duties of analyzing the Findings Report and generating recommendations. 


## Selecting Board Members

**CRISIS MODE**

**Find 4 people who are qualified to serve as Board Members: 1 individual expert, 1 from an academic institution (university, think tank, etc.), 1 from a cybersecurity-related corporation, and 1 from a government agency (it may be you). **



1. **Go to your local or a respected university’s computer science department and ask the chair to serve or suggest someone else in academia. **
2. **For your individual contributor, look for a local chapter of ISSA (the Information Systems Security Association), the Cloud Security Alliance, Infragard, B-Sides (a security conference umbrella), or reach out to the authors of this report online for help in rapidly finding someone to serve.  You can also look to a sectoral resource, such as an information sharing association like an ISAC or ISAO.**
3. **For your government member, if you have not already been assigned to be that person, reach to your state CISO office to request a person.**
4. **For your corporate member, ask ten CISOs of respected companies in your relevant jurisdiction/location/area of impact who do not have a vested interest in the outcome of the investigation. **
5. **Tell them they are all going to serve for not less than 30 days and not more than 90 days.**
6. **Conduct the investigation according to the guidelines below.**
7. **Use what you have learned to stand up a skeleton board that can rapidly be spun up in future.**

There should be a minimum of four people on the board, one from each of the following four areas: individuals, companies, governments, and academic institutions. If the Board needs additional members, people from the four categories of organizations should be added as evenly as possible. In the authors’ experience, more than sixteen people can be unwieldy for an investigation of this nature. The host organization may invite software companies, think tanks, cybersecurity firms, major industry players, and individual cybersecurity experts and consultants to serve as Members of the Board. Having a Board composed of respected members of the cybersecurity community lends the Board credibility and visibility. Inviting a wide range of organizations and individuals incorporates diverse views in the discussion over the findings and recommendations derived from the investigation and extends the reach of the investigation’s conclusions.


### Considerations


### Inevitably, the Board will comprise quasi-competing components: government agencies; private corporations; individuals; organizations. To strike a balance between the various components requires taking into account the unique value added by each type of Board Member. 

Primary questions for consideration: 



1. Does the individual or entity hold unique expertise that is not already represented in other Board Members?
2. Is the Board as a whole representative of the larger cybersecurity community?

In the selection of Board Members, thought should also be given to the resulting Board’s diversity including but not limited to racial, ethnic, and gender diversity. Not only does diversity bring new experiences, perspectives, and ideas but a homogenous Board runs the risk of proposing infeasible recommendations or overlooking ideas by virtue of its limited perspective.

**Individuals: **There are individual experts who hold unique experience and perspectives separate from any organization or corporation they may be affiliated with. It should be noted that these individuals are not limited to former government officials. Researchers, consultants, and other experts who do not hold government experience are also qualified to serve on the Board and would offer perspectives not necessarily represented in former government officials. The benefit to including many individual experts is that individuals representing themselves are not constrained by corporate interests, government policy, or guidelines set by an academic organization. On the other hand, individual experts may wield less influence than corporations, government agencies, and academic organizations, limiting the impact of the final report and recommendations. 

**Corporations: **The private sector is one of the largest stakeholders in cybersecurity issues, owning a majority of critical infrastructure in the country; they have enormous potential to influence markets and set industry standards. Including multiple corporations on the Board could increase buy-in from other corporations and increase the rate of adoption of the Board’s recommendations. However, the cybersecurity community may not trust a majority corporate Board to draw unbiased and effective conclusions and recommendations. 

**Government Agencies: **Federal, state, and local government agencies possess useful insights into the regulatory environments and can offer guidance as to where recommendations should be targeted to be most effective. Government employees can also bring a public-service orientation. The government perspective is especially valuable when operating in a complex regulated environment. 

**Academic Organizations: **Universities, non-profit, and think tank organizations house vast expertise across a variety of issues and have already established credibility in the cyber field. Their involvement not only lends the Board additional expertise but also supports a wide distribution of the Final Report and recommendations. Though academic organizations have access to a wide range of expertise and typically hold influence to support wide distribution of the report findings and recommendations, corporations may discount conclusions derived by academic organizations who do not hold profit interests in cybersecurity measures.


### Determination

Invitations to serve on the Board should be extended to individuals as well as corporations, government agencies, and academic organizations to ensure that the Board consists of diverse perspectives. A Board stacked with any one type of Board Member, for example majority corporations or majority individuals, risks both being perceived as biased and inadvertently exerting bias through the omission of differing perspectives. Therefore, representation should be balanced to ensure that no one industry holds a majority on the Board.



    3. Structure of the Board

**CRISIS MODE**

**Invite 1 individual expert, 1 government representative, 1 representative from a corporation, and 1 member of an academic institution to serve as Board Members, 4 Board Members in total. Once the crisis has ended, you can go through the considerations to determine how many Board Members should be on the Board in the long term.  **

The number of Board Members should be between four and sixteen in order to keep the discussion streamlined and the Board functional as a decision making body. While a larger Board may offer more representation of the cybersecurity community and expand the reach of the Board’s conclusions and recommendations, allowing too many voices in the discussion may drag on discussions and prevent consensus surrounding the investigation’s findings and recommendations. 


### Considerations

A key consideration in determining the size of the board must be maintaining efficiency throughout the review process and incorporating diverse perspectives and developing credibility among the cybersecurity community. A board with too few members sacrifices diversity of opinion and perspective and risks being perceived as serving a particular set of interests, losing credibility as a result. Too many members increases the logistical complexity of convening the board to review a cybersecurity incident and increases the potential for discussions on findings and recommendations being dragged out or diluted beyond useability. The NTSB, for example, has a five-member board. 


### Determination

The exact number of the Board Members should be determined by the host organization. Though the NTSB model operates on a five person board, a larger board would be appropriate in this case to accommodate the various types of actors in the field of cybersecurity and the competing interests and perspectives. Such a board could allow for more than one entity from each of the categories mentioned above, and leaves room for multiple, conflicting voices to be incorporated. The Board can be expanded depending on the needs of the host organization, though the two principles, efficiency and diversity, must be balanced. 



        1. Board Member Term Length

**CRISIS MODE**

**No need to consider Board Member term length policy now. For now, consider Board Member term length to be the duration of the technical investigation and Board review. Once the Final Report has been submitted, you can reevaluate Board Members and institute a term length.**

A term of two years balances the stagnation caused by long term lengths against inefficiency brought on by frequent turnover. At the end of a Board Member’s two year term, the organization or individual can be reevaluated to determine whether to extend their seat for an additional term. The decision to extend an invitation for an additional term should consider the value added by the Board Member in past investigations and deliberations and whether the Board would benefit more from a new perspective. 


### Considerations

Onboarding new Board Members and integrating them into the review processes takes time and resources. It would, therefore, make sense to keep Board Members on the Board for as long as possible; it would reduce time and resources lost to a new Member’s learning curve. 

It is also true that the cybersecurity field is constantly evolving: cyber vulnerabilities permeate to affect new industries, new threat actors emerge, and new offensive techniques and strategies are developed. To ensure that the Board is always representative of the present state of the cyber field and in tune with the concerns and experiences  of the cybersecurity community, short Board Member terms would be best. A constantly changing Board would mirror the constantly changing cybersecurity environment. These two points are in direct conflict on purpose. The host organization may decide which is more important.


### Determination

The term length is determined in recognition of the constantly changing nature of the cyber field and the value gained from having experienced Members serve on the Board. Term lengths for Board Members are necessary in order to guarantee turnover on the Board and maintain opportunities for new expertise and voices to join the Board without constantly increasing the size of the Board. The changing membership keeps the Board agile and responsive to industry changes, while the two year term preserves a degree of experience in the review process on the Board. 



        2. Conflicts of Interest

**CRISIS MODE**

**When choosing the 4 people to serve as Board Members, ask:**



1. **Does this person, corporation, academic institution, or government agency benefit financially from a particular outcome of the investigation? **
2. **Would their reputation or that of their employer be impacted negatively by a particular outcome of the investigation?**
3. **Would this person, corporation, academic institution, or government agency serving on the Board call into question the impartiality of the Board?**

During a Board Member’s term, cyber incidents may arise that present a conflict of interest for the individual or organization. To preserve honest discussion and preemptively protect the findings from accusations of bias, a system should be established such that any Board Member can raise the issue of a conflict of interest for themselves or for another Board Member at the Opening Meeting. Should new facts emerge during the investigation that call into question the impartiality of a Board Member, the Board may convene an emergency meeting to determine whether a conflict of interest exists and initiate the recusal process if need be. 

If the Board Member for whom the cyber incident may present a conflict of interest does not recuse themselves then the matter can be brought to a majority vote, with all Board Members participating. If the majority of the Board votes in recognition of a conflict of interest, the Board Member should not be involved in the investigation process or deliberations on findings and recommendations. The Board may then proceed one member short for the duration of the investigation. 


### Considerations

Inevitably, in all industries, conflicts of interest arise. An investigator having a vested interest in the outcome of an investigation is immediate cause for concern. In the case of a Major Cyber Incident Investigations Board, a conflict of interest could arise in inaccurate findings and insufficient recommendations. Take for example a Microsoft representative serving on the Board during an investigation into a vulnerability exploited in Microsoft’s operating system. 

There are already models for ensuring the impartiality of decision-making bodies. For example, electing a Board Chair who has the authority to make determinations regarding conflicts of interest. A similar role can be played by an inspector general. Alternatively, a separate ethics board can make the decision for conflicts of interest. 

If all individuals, organizations, agencies, and corporations who could potentially be biased in an investigation were excluded from serving on the Board, there would be no qualified Board Members. Thus, a case-by-case approach rather than a unilateral approach may be needed. 

Furthermore, bringing an outside body up to speed on the facts of the case and potential relationship to the Board Member would take time and potentially delay the investigation and deliberation. 

The U.S. Office of Government Ethics offers useful guidance on different types of conflicts of interest[^6]. The National Council of Nonprofits also has useful resources on navigating conflicts of interest[^7].


### Determination

Preserving the Board’s independence and credibility is of the utmost importance if the reports and recommendations are to have the needed impact. Conflicts of interest are unavoidable given the diversity of the Board and the interconnected nature of the cybersecurity industry. In recognition of that fact, there must be a process in place to facilitate the recusal of a Board Member from the review and investigation of a cybersecurity incident where they may be biased. A formal process removes stigma from a Board Member recusing themselves in acknowledgement of their potential impartiality in that particular case. The voting mechanism through which the Board Members can force the recusal of a Board Member should be in place to implicitly enforce the recusal process and prevent a Board Member from potentially being involved in the review of an incident from which they would derive personal or professional gain or loss. 

The voting process cements the egalitarian nature of the MCIIB; all of the Board Members are allowed to weigh in, and thus, the decision is representative of the Board as a whole. This process also saves time by relying on the Board Members’ expertise and familiarity with the case. 



    4. Board Member Duties

**CRISIS MODE**

**20% of a Board Member’s effort will happen on initiation of the investigation, 10% over the course of the actual technical investigation, and 70% will happen over the week of the review of the Technical Report, Board discussions, and preparing the Final Report for public dissemination. **

_Investigation Initial Stages_

Board Members should ensure that they are available to attend Board Meetings as needed throughout the investigation. At the start of the investigation, Board Members will convene to discuss the cyber incident that is the subject of investigation and agree upon a schedule for Board Meetings once the investigation concludes to discuss and vote on findings and recommendations. 

_During the Investigation_

Board Members will not be directly involved in the day-to-day operations of the Technical Investigation but should be responsive to information requests from the Technical Team. e.g. consultation requests from expert Board Members or software support from a software company representative.  Board Members should use the investigative phase to ensure that their schedules can accommodate an intensive period of Board Meetings at the conclusion of the investigation.

_Review Conclusion Stages_

Once the Technical Team has submitted their report outlining their analysis of the cybersecurity incident, the Board Members will convene for the Closing Board Meeting to discuss and vote on the findings that will be included in the Final Report. The Closing Board Meeting should be scheduled no sooner than two months following the conclusion of the Technical Investigation in order to ensure that Board Members have sufficient time to review and understand the investigation and findings. At the Closing Board Meeting, Board Members will shape the Final Report through their deliberations. Board Members will also propose and vote on recommendations of cybersecurity practices that could be effective in preventing or mitigating a similar incident from happening in the future.


### Considerations

Board Members’ time and expertise is extremely valuable. The goal of delineating Board Member duties is thus to allocate Board Members’ time to where it is most needed and where it will be most effective.

There are two parts to a cyber incident review. The first is the Technical Investigation: analyzing reports, interviews, and other materials; general fact finding.  The second is a higher level analysis of the implications of the facts uncovered during the Technical Investigation and identifying potential recommendations. The question to consider is, therefore, where in the review process should Board Members be involved in order to maximize the impact of their skills and experience. 

Should Board Members be seen as representatives of a company, or serving in a personal capacity? The way in which the Board Members are defined and referenced may increase or decrease their credibility in complex ways. For example, “the representative from MajorTechCo” probably increases technical cachet, at the possible cost of their impartiality being questioned. 


### Determination

Having the Board Members be involved only in the review of the Technical Investigation findings and the development of recommendations focuses Board Members’ skills and experience on implications of what the findings of the Technical Investigation mean, rather than the fact finding portion of the investigation. The Technical Investigation can be outsourced to skilled professionals, instead. 

A secondary benefit to the division of labor between the Technical Investigation and the Review is that Board Members will view the Findings report provided by the Technical Team with fresh eyes; they will not have bias towards findings that they themselves developed. The focus of the Board Members, therefore, is to review the facts and develop a narrative and set of recommendations based on the Technical Investigation. 



2. The Technical Team

**CRISIS MODE**

**Consult with the Board Members you have selected and determine what technical skills are essential for conducting an investigation. First, look into whether those skills are present in your IT department. If not, ask the Board Members if there are people at their home organizations that can join the Technical Investigation. These people will not be needed for the entire review process, only for the Technical Investigation. You will also need a report writer. This can be anyone in your organization who writes reports that shows critical thinking and management of ambiguity. They will be involved in the entirety of the review process. **

**Examples of technical skills that may be required:**



* **Malware analyst**
* **Digital forensics and incident response (DFIR) analyst**
* **Security architect**
* **Red team expert**
* **Human resources expert**
* **Software engineer**
* **Insider threat expert**
* **Operations researcher**
    5. Forming the Technical Team

A general guiding framework for a Technical Team is a malware analyst, a digital forensics and incident response (DFIR) analyst, a security architect, a red team expert, a software engineer, an insider threat expert, operations researcher, software developer, and human resources expert. As needed, the team can be expanded to include additional investigators, lawyers to help the investigative team navigate intellectual property restrictions, attorney-client privilege protected documents, and any other legal gray areas, and technical personnel with relevant expertise. A report writer will join the team at the start of the investigation. Throughout the investigation the report writer will shape the Findings Report, presenting the findings in an impartial manner. All personnel assigned to the investigation should be available for a full-time commitment for the duration of the investigation.

In the MCIIB’s nascent stages it may be difficult to compile a list of qualified individuals for a complete Technical Team. Initially, the host organization may tap into its IT team, Board Members can refer people in their networks, and the Board may rely more heavily on lended personnel from Parties to the Investigation. As the Board reviews more cases and develops a rhythm, it will develop a list of reliable technical experts in various fields that it can consult when it needs to assemble a new Technical Team.


### Considerations

As mentioned previously a tradeoff exists between the Board Members conducting the investigation themselves from start to finish. Board Members could lead both the Technical Investigation and the Review. On the other hand, bringing in a Technical Team allows Board Members to focus solely on the Review and determining recommendations. The distance from the technical analysis also serves to preserve bias from the findings. 


### Determination

The Technical Team steps in to conduct the technical analysis of the evidence, reserving the Board Members for the analysis of the implications of the Findings Report. The skill sets among the Technical Team should be diverse enough that there is at least one professional per area of the investigation to ensure that a thorough analysis is conducted. 



    6. Goals of the Technical Team

**CRISIS MODE**

**The Technical Investigation’s goal is to determine the facts of the incident. At the end of their investigation, the Technical Team will turn over a Findings Report to the Board Members. At that point, the Technical Team is dissolved. **

**The Technical Team is not meant to assign blame to any one person or entity, identify who was behind an “attack”, or develop recommendations. **

Questions the Technical Team may explore:



* When did the incident occur?
* Who discovered the incident?
* What security systems were in place before the incident?
* What software or hardware vulnerability was exploited?
* What cybersecurity policies were in place in the organization?
* How did the threat actor move throughout the system(s)?
* How long did the vulnerability exist?
* What data was exposed?

The purpose of the technical investigation is not to identify a singular cause for the cyber incident or to assign blame to a particular actor, but rather to ascertain and document the conditions under which the cyber incident occurred, decisions made before, during, and after the incident, and various software, systems, personnel, and environmental factors that contributed to the incident. At the conclusion of the Investigation the Technical Team should compile a report documenting their investigative process and outlining the team’s findings. The Findings Report will be the foundation for the Board Members’ discussion of the incident and the basis for their recommendations. 


### Considerations

The question is: how far does the purview of the Technical Team extend? Similar to identifying the boundaries of the Board’s responsibilities, we must consider where the Technical Investigation’s time is most valuable and the benefits of dividing the review process between the Technical Investigation and the Board Members. 


### Determination

The Technical Team holds highly technical professional skills that are most conducive to analyzing evidence provided to the Team and compiling a fact findings report. The fact findings report can then be provided to the Board for their review of the cyber incident. Once the Team hands off the fact findings report, they are no longer involved in the review process; the Board Members are not involved in the fact findings investigation and the Technical Team is not involved in the review and recommendations development. Again, the division of labor helps preserve unbiased analysis from both the Technical Team and the Board Members. 



    7. Technical Team Structure

**CRISIS MODE**

**Go with the bare minimum of skill sets needed to conduct the investigation. **

Should the scope of the incident review necessitate a Technical Team of more than 10 experts, the investigator in charge should divide the Technical Team into groups and designate Team Leaders who will be responsible for collecting the group’s daily factual findings and resolving potential conflict within the groups. 


### Considerations

Increasing the size of the Technical Team adds essential skill sets that will improve the accuracy and quality of the fact findings report, but the increase in size also jeopardizes the agility and dynamism that comes from a small working group. Avoiding adding additional professionals to the team in the name of preserving the small group working environment would result in a less effective fact findings report. Enlarging the Team by adding many professionals might impact the IIC’s ability to monitor the group’s progress and obstacles and could impede communication among Team Members, effectively creating information silos among the team. 


### Determination

Dividing the Technical Team into small groups and adding the role of Group Leader to the Technical Team dynamic balances the need for effective communication amongst Team Members and the IIC and the need to be able to add essential technical skill sets to the team. The role of Group Leader can be assigned to any of the Technical Team Members. The responsibilities include acting as daily point of contact, reporting to the IIC regularly regarding progress and obstacles, and resolving conflicts among their group members. Group leaders ensure there is sufficient communication and leadership for the investigation as a whole. 



    8. Members of the Technical Team
        3. The Investigator in Charge

**CRISIS MODE**

**Name the person with the most experience conducting investigations as Investigator in Charge (IIC). This person will serve as the point of contact for the Technical Team, guide the direction of the investigation, and attend the Final Board Meeting. **

After the Board has convened for a cyber incident, an Investigator in Charge (IIC) should be selected to lead the technical investigation. The IIC should have experience leading a team, conducting independent investigations, and be familiar with the cybersecurity field. 

_Review Initial Stages_

Once the IIC has been briefed on the cybersecurity incident that is to be the subject of the investigation, the IIC will compile a list of necessary technical personnel. At the start of the investigation, the IIC will brief the Technical Team on their respective roles, how the Technical Team functions, the goals of the Technical Team, and security protocols.

_During the Review_

Throughout the investigation, the IIC’s main task will be to direct the review process and resolve interpersonal or structural issues as they arise. The IIC will also keep Board Members and Party Coordinators informed of the status of the review through a brief weekly memo and periodically adjust timeline expectations for the conclusion of the investigation.

_Review Conclusion Stages_

At the conclusion of the investigation, the IIC and report writer will assemble the Technical Team’s findings into a Findings Report and submit it to the Board. The IIC will attend the Board meeting to brief the Board Members on the investigation and findings and answer any questions the Board Members may have throughout their discussions. The IIC cannot, however, partake in the discussions except in response to questions, or vote on the findings or recommendations.


### Considerations

The separation of the technical investigation and the review of the facts of the incident has significant value, but the separation may also impede communication and cohesion between the two. Furthermore, while there is benefit in the horizontal power dynamic for the Team, the lack of a central point of contact between the Technical Team and the Board Members or outside contacts may affect the progress of the investigation. 


### Determination

The IIC, a term borrowed from the NTSB, bridges the gap between the Technical Team and the Board, serving as a point of contact for Board Members, as well as the targeted organization, and any other parties. The IIC also guides the investigation, providing direction to the investigative process and coordinating resources needed by Team Members. During the Board’s meetings, the IIC will be present to offer an overview of the technical investigation and answer any questions about the Team’s process and findings. However, to maintain the separation between the technical investigation and the review, the IIC will not partake in the Board’s deliberation or be involved in the development of recommendations. 



    9. Hierarchy Framework

**CRISIS MODE**

**Other than selecting an IIC, make no other moves to establish a hierarchy among the Technical Team or the Board Members. Using an egalitarian model will help foster collaboration and information sharing. **

Unlike other investigative bodies that follow strict hierarchical structures, the Technical Team will mirror the relative egalitarian, collaborative culture of the cyber industry. The pace, direction, and scope of the investigation is determined by the IIC. Team Members are responsible for thoroughly investigating the incident through the lens of their assigned role, and collaboration is encouraged. Technical Members should attempt to resolve disputes or conflicts among themselves, pulling in other Team Members as needed, and only elevate the issue to the attention of the IIC if no agreement can be reached. 

In the event that the incident necessitates a larger Technical Team and the Technical Team is divided into teams with a chosen Group Leader, the Group Leader will hold no authority over team members but will be in charge of leading meetings and resolving conflict among team members. Should an issue, internal or external, that impedes the progress of the investigation arise, the IIC will elevate the issue to the Board who will make a determination by majority vote.


### Considerations

A hierarchical authority structure would provide direction to the investigation and ensure that the IIC is apprised of all progress, issues, and findings. Hierarchical authority is, perhaps, more traditional for investigations. The egalitarian structure more common in tech spaces loses the clear authority of the hierarchical structure, but gains opportunities for collaboration between peers. These are tradeoffs that must be considered when deciding which approach to pursue. 


### Determination

The success of a cyber incident investigation is dependent on collaboration between the professionals that make up the investigative team. Each individual pursuing one path of analysis independent of others increases the possibility that additional contributing factors are missed because the team fails to consider connections between their investigative focuses. Because the egalitarian structure encourages collaboration more than the hierarchical structure, the Technical Team should be formed without designating levels of hierarchy among Team Members, other than the IIC who guides the investigation.



3. Operational Logistics of the Investigation
    10. Board Member Location

**CRISIS MODE**

**Use the encrypted telework software of your choice to facilitate remote work for both the Technical Team and the Board. Board Members and Technical Team Members may be scattered across the country; organizing travel for people to relocate for the duration of the investigation will delay the start of the investigation and present challenges that could easily be avoided through remote work options. Debates for in-person vs. remote can happen later.**


### Considerations

Holding meetings remotely would make arranging Board Meetings easier since Board Members will not have to travel. Furthermore, many are now accustomed to using online tools for virtual meetings, so there should not be significant difficulty in carrying out a virtual meeting. 

In person meetings would allow for comfortable conversation without the inconvenience of frequently muting and unmuting oneself. However, the travel involved would make it more difficult to find a time that works with the schedules of all Board Members, and bearing the cost of travel can be prohibitive.


### Determination

The Opening Board Meeting should be flexible, because it may be held immediately after the Board learns of a cybersecurity incident occurring. Furthermore, the Opening Board Meeting centers around the logistics setting up the Technical Investigation, rather than analytical and philosophical debates over findings and recommendations. Thus, the Opening Board Meetings do not lose too much by being held virtually. Closing Board Meetings, on the other hand, are dependent on engaged and active debates between Board Members. To preserve the spirit of debate, the Closing Board Meetings should be held in person. The scheduling of the Closing Board Meeting should begin once the investigation is officially opened so as to give Board Members time to manage their schedules and arrange travel. 



    11. Technical Team Location

To avoid limiting access to talent by mandating that they relocate to conduct the Technical Investigation in person, the Technical Team should operate remotely. The Team can utilize remote work software to ensure that communication channels between Team Members remain open and that meetings can be held with all Team Members present. 


### Considerations

Working in person can foster teamwork among the professionals in the Technical Team and facilitate collaboration through proximity. A high degree of collaboration is ideal for the investigation where linking different components of the investigation, potentially explored by separate professionals, can yield improved insights. 

Skilled professionals are located across the country and mandating a physical relocation for the duration of the investigation may limit the pool of talent and negatively impact the diversity of the Technical Team. Professionals may exclude themselves from consideration to join the Technical Team due to the relocation forcing them to leave family for an extended period of time or other obligations that require them to remain at home. 


### Determination

Sufficient tools now exist to facilitate comradery and collaboration remotely, to share documents, and to co-work. Throughout the COVID-19 pandemic, most professionals have transitioned to working remotely, at least temporarily. The remote nature of the Technical Investigation should, therefore, not affect the quality of the investigation. 



    12. Compensation

**CRISIS MODE**

**Check your budget to determine the stipend you can give to the Technical Team Members and Board Members for their time on the investigation. You can determine standard stipends later. **

Because Board Members and Technical Team Members are dedicating their time and full attention to the investigation, both should be compensated for their work. In addition, lack of compensation may negatively impact the diversity of the Board and Technical Team as potential candidates weigh the cost of taking time away from their full time jobs to contribute to the investigation. 

Considerations

There are many models for compensation in cases where professionals are involved infrequently, two of which will be discussed here. The host organization could pay the Board Members a stipend when the investigation is opened to offset costs from taking time off of work to dedicate their attention to the investigation and to thank them for their contributions. Alternatively, the host organization could pay Board Members an annual salary for their position as Board Members. For investigation boards operated by governments, there may also be an element of prestige associated with service on the board.

Because the Technical Team varies based on the skills needed for each investigation, Technical Team Members could be given a stipend based on the duration of the Technical Investigation. 

Determination

It is important that both Board Members and Technical Team Members are compensated for providing their time and expertise if the MCIIB is to be sustainable and effective. The model through which the professionals are compensated may be left up to the host organization to select. 



4. Parties to the Investigation
    13. The Party System

**CRISIS MODE**

**The priority right now is to move quickly. If there is a company or organization that would significantly improve the quality of the investigation, invite them to be a Party. **

**This can be the company that developed the software found on exposed systems, unions, etc. Otherwise, proceed without Parties for now. Parties should not benefit financially or otherwise from a particular outcome of the investigation. **

**Parties are corporations or organizations who hold technical skills that would be helpful for the investigation. Parties assign personnel to the Technical Team but do not attend Board Meetings. The Findings Report will be sent to the Parties at the end of the Technical Investigation, and Parties can present their opinions and recommendations to the Board through a Party Recommendation Letter, which will be sent to all Board Members ahead of the Final Board Meeting.**

The IIC will consult with the Board at the Opening Meeting to determine whether technical expertise held by outside organizations such as a private sector software or cybersecurity company, a federal agency, a state agency, cybersecurity expert, or a think tank is needed for the investigation. In the case that specific technical expertise would significantly improve the capabilities of the Technical Team, an organization can be invited to participate in the review as a Party. Lawyers representing victims, insurance companies involved in the incident, and representatives of the victims of any resulting damage from the cyber incident cannot serve as Parties to the Investigation. 

Though the Parties lend technical assistance to the investigation, the Parties are not a part of the Board’s review of the incident. Once the IIC assembles the Technical Team’s findings and submits them to the Board, the Parties are no longer a part of the review process. The Parties may submit a Party Recommendation Letter to the Board that details the Party’s perspective on the findings and its recommendations. The Board will read the Party Recommendation Letters along with the Findings Report in preparation for the Final Board Meeting.


### Considerations

While the professionals that form the Technical Team will no doubt be knowledgeable and qualified to conduct the investigation, there may be some knowledge or skill sets that would significantly aid the investigation which are uniquely held by a certain organization. Some skill sets will be needed only for the duration of one particular investigation, so it would not be helpful to incorporate them into the Technical Investigative Team for any longer than that investigation. For example, if the Team were investigating a cyber incident that occurred at a university, it would be helpful to have the head of IT from another university join the investigation to offer insights into the environment of managing a university’s systems. In such a case, it would be helpful to have a mechanism through which the IIC could incorporate a member of the organization into the Technical Investigative Team for the duration of the investigation.


### Determination

The NTSB uses the Party System to take advantage of the unique expertise held by industry stakeholders such as labor unions, consulting firms that have done work with and continue to be interconnected with the targeted organization, and local government agencies. The Board could utilize a similar model to bring in specific expertise on a case-by-case basis. 



    14. Role of the Party Coordinator

**CRISIS MODE**

**Ensure that you have a point of contact within any company or organization invited to be a Party, this will be the Party Coordinator for that company or organization. **

Each outside organization will designate a Party Coordinator to be the IIC’s main point of contact for the organization. The Party Coordinator may be called upon to support conflict resolution involving their organization’s personnel. The Party Coordinator should have sufficient authority within their organization to preclude the need for significant discussion with superiors when making decisions on behalf of the organization as related to matters concerning the Technical Team. Party Coordinators cannot attend the Team meetings; the IIC will send a bi-weekly summary of the team’s progress to all Party Coordinators. 



    15. Party Coordinator Meeting

**CRISIS MODE**

**Meet with each Party Coordinator individually (rather than working around various people’s schedules to schedule a joint meeting). **

**Let them know:**



1. **Personnel will report to the IIC for the direction of the Technical Investigation.**
2. **Party Coordinators will receive a copy of the Findings Report at the conclusion of the Technical Investigation.**
3. **Parties can express their views on the findings and propose recommendations through the Party Recommendation Letter, which will be forwarded to Board Members ahead of the Final Board Meeting.**
4. **Parties will not participate in the Board’s discussions on findings and recommendations. They will receive a copy of the Final Report once the Board releases it for publication.**

Once the Parties to the Investigation have been confirmed by the Board,  the IIC will hold a meeting for the Party Coordinators. At the Party Coordinator Meeting, the IIC will explain the parties’ roles in the investigation and the role of the Party Coordinator, and discuss assigning technical personnel from Parties to the Technical Team. 

Prior to attending the meeting, each Party Coordinator should review, sign, and submit a Party Agreement. In signing the form, the Party agrees that for the duration of the review any personnel assigned to the Technical Team will report to the Board, and not to their home organization, that the Party will not communicate Board findings or progress to the press or the public, and that all findings and recommendations must be considered confidential until formally published in the Board’s Final Report. 



5. Materials for Review
    16. Materials from Targeted Organization

**CRISIS MODE**

**The IIC acts as the point of contact and initiates requests to the targeted organization for evidentiary materials. The IIC then makes the materials available to the Technical Team for analysis. If a Technical Team Member would like additional materials, they can request it through the IIC. **

**Materials may include:**



* **Systems hardware**
* **Systems records**
* **Past threat assessments**
* **Email correspondence**
* **Attack assessment report conducted by an outside cybersecurity firm**
* **Employee interviews**

Evidentiary materials will be obtained on a voluntary basis from the targeted organization and any third party cybersecurity firms, law firms, or other support, such as public affairs firms and crisis consultants, hired by the organization in the aftermath of the attack. Materials may include but are not limited to systems hardware, systems records, past threat assessments, email correspondence, attack assessment report conducted by a cybersecurity firm, and employee interviews. 

All requests for materials should be facilitated through the IIC to preserve a central point of contact for the targeted organization. All Technical Team members are able to request additional materials and interviews that may be beneficial to their review of the incident through the IIC. 


### Considerations

The NTSB has the authority to subpoena evidence or testimony relevant to the investigation. Organizations are therefore compelled to cooperate with the NTSB. An independent MCIIB does not have the authority of a federal investigative body like the NTSB and therefore cannot mandate that documents and evidence be handed over to the board. 


### Determination

Instead of relying on authority to require the targeted organization to provide the Board Technical Investigative Team with documents and evidence on which to base their investigation, the MCIIB must rely on voluntary cooperation, unless the MCIIB has been granted the authority to subpoena documents and information by a government authority. Voluntary cooperation has the potential to yield positive results, because the investigation into the contributing factors to the cyber incident benefits both the targeted organization and the larger cybersecurity community. 



6. Investigation Process

**CRISIS MODE**

**Read this section!**

**Phase I: Collect data and evidence**

	The goal during this phase is to prepare a foundation for analysis. The collection of evidence may include but is not limited to compilation of internal and third party reports regarding the incident, review of security systems, software, and hardware, and interviews of personnel involved in the incident or any subsequent internal or third party investigations. 

**Phase II: Perform analysis, develop a timeline and discover open questions**

	At its core the investigation is an iterative process. In the development of a timeline, new questions may arise that necessitate the collection of new data. It is also certain that not all questions derived from the analysis can be answered through the obtained evidence. These questions are important and should be documented in the Findings Report. 

**Phase III: Form and test hypotheses**

	The formation of a hypothesis that identifies the root cause or explains the sequence of events is dangerous to thorough and impartial analysis. Thus, hypothesis development should be reserved for the final phase of the technical investigation, after the initial analysis of the evidence has been completed and chronicled. Both proven and disproved hypotheses and the evidence that supports or negates them should be included in the Findings Report. 



    17. “5 Whys” Analytical Framework

**CRISIS MODE**

**Don’t settle for the easy answer, keep asking why. A vulnerability was exploited because a software wasn’t updated and patched. Why wasn’t the software updated on schedule? The automatic update failed. Why did the automatic update system fail? And so on. **

**This kind of analysis identifies multiple contributing factors rather than placing the blame entirely on one failure. **

The “5 Whys” framework is useful for pushing analysis beyond initial conclusions. For example, rather than conclude that a security breach occurred due to personnel negligence, question why the negligence occurred; why there was not a system in place to prevent one person’s negligence from having outsized impact.


### Considerations

What is the “5 Whys” Analytical Framework?

To push past preliminary conclusions, continuously ask “why.” For example, an organization’s security systems were penetrated. Why was the security system vulnerable? Software they used relied on an open source library that was exploited by a hostile third party. The answer is not simply “avoid using open source libraries in the future.” Why did the software rely on an open source library rather than developing everything themselves? It is faster and more efficient to use an open source library. Why was speed prioritized? Why wasn’t the vulnerability caught before the library was operated in the software? The “5 Whys” framework should encourage rather than require constant questioning of preliminary findings. 

All investigations benefit from asking deeper and deeper questions, working to identify root causes. What kind of guidelines can push an investigative team to push past primary findings without setting constraints on the analysis?


### Determination

The 5 “Whys” analytical framework offers useful guidance for an investigative team. The framework does not prescribe analytical steps that may unnecessarily constrain the investigative and analytical process. Instead, the framework offers a method of analysis that pushes investigators to continue asking why even after determining a supposed “root cause.” A useful example is to consider human error. A security vulnerability may have been exposed by an employee failing to meet security standards, but that finding can be pushed deeper. Why was the failing not caught? Why did the employee make that choice? 



    18. Investigative Targets

**CRISIS MODE**

**Set the goal of the investigation as: identify contributing factors. Aim to understand under what conditions the cybersecurity incident occurred. **



* **Environment: How did the cyber incident occur? What conditions were in place that facilitated the issue?**
* **Response: How was the incident discovered? How quickly were leadership notified? What decisions were made in the immediate aftermath and why? **
* **Discovery: How much time elapsed between the initial incident occurrence and the discovery?**
* **Magnitude: Which systems were affected? What data was compromised?**

**Look for evidence regarding the following:**



* **Computing and organizational systems successes (near misses) and failures**
* **Organization’s security policy and procedures, and their gap with identified policies, practices and standards**
* **Software vulnerabilities and organization’s patch management**
    * **Ease of discovering, prioritizing and applying patches**
    * **Operational demands and complexity of applying updates**
* **Software architecture issues that impact security**
* **Software design issues that made security complex or difficult to implement, evaluate or manage**
* **Software defaults that left systems insecure, especially when products were marketed as “secure.”**
* **Software or systems that do not appear fit for purpose**
* **Defensive solutions and their configuration**
* **Human error **
* **Personnel behavior and security awareness**
* **Hardware weaknesses**
* **Organization’s protocol and policy shortcomings**
* **Places where the decision on whether to fix known vulnerabilities privatized profit and socialized public harms.**

The goal of the investigation is to understand the conditions under which the cybersecurity incident occurred and determine what happened, how and why. The Technical Team should refrain from crafting narratives before all the facts are available, or focusing on identifying one singular cause for the incident at the exclusion of anything else. Rather, the investigation should identify contributing factors for the incident. Similarly, the investigation should refrain from allocating blame entirely to the end user of products and instead explore whether vulnerabilities exist in the product itself and the way in which vendors ease or increase the cognitive load.

In analysis of the methodology of the attack, the Technical Team should seek to understand the following:



* **Environment**: How did the cyber incident occur? What conditions were in place that facilitated the vulnerability?
* **Response**: How was the incident discovered? How quickly were leadership notified? What decisions were made in the immediate aftermath and why? 
* **Discovery**: How much time elapsed between the initial incident occurrence and the discovery?
* **Magnitude**: Which systems were affected? What data was compromised?

The Technical Team should explore the following security areas the following categories as they work to identify the underlying causes of the incident:



* Computing and organizational systems successes (near misses) and failures
* Organization’s security policy and procedures, and their gap with identified policies, practices and standards
* Software vulnerabilities and organization’s patch management
* Defensive solutions and their configuration
* Human error 
* Personnel behavior and security awareness
* Hardware weaknesses
* Organization’s protocol and policy shortcomings


### Considerations

What should the Technical Team be aiming to determine? There is a benefit to identifying a singular goal towards which all Team Members could work. For example, the Team could work to identify the actions the attacker took. The Team could also focus on determining the initial point of entry and progress from there. In pursuit of a singular goal, Team Members can utilize evidence from multiple perspectives. The goal could differ between each investigation and vary across host organizations depending on organization values. Such insights may be valuable for developing a plan of action to address the cause of the cyber incident. 

Alternatively, the Team could initiate the investigation without a specific goal in mind to prove or identify. Though this track supports uncovering findings without bias, it may prove less efficient than the strategy of working towards a singular goal. Pursuing multiple lines of inquiry could result in Team Members spending time on findings that turn out to be minor in the context of the larger narrative. 


### Determination

The separation of the Technical Team and the Board and their respective responsibilities means that the Technical Team is solely focused on fact finding. To continue to preserve the unbiased, fact-oriented nature of the Technical Team, the Team should refrain from identifying a singular hypothesis and exploring its plausibility through analysis, and instead should explore multiple lines of inquiry. The topics and questions above may serve as guidelines and starting points for analysis and should not exclude other lines of inquiry. 



    19. Examination of Personnel Actions

**CRISIS MODE**

**It’s tempting to attribute security failures to solely human error. The Technical Team and Board Members should explore factors that contributed to the incident in addition to human error, as well as systems failures that contributed to human error.**

While avoiding attributing the incident solely to “human error,” the Technical Team will examine the tasks, goals, and behavior of employees and management prior, during, and after the incident and compare the behavior to the organization’s official security policy and any existing state and federal standards. Information regarding employee behavior and the security environment can be gathered from personnel interviews conducted either by Team Members, or through transcripts of interviews conducted by a third party during their investigation. 


### Considerations

Personnel, their actions within systems, and their  interactions with software, are a key component of any cybersecurity environment and will undoubtedly be a point of investigation for the Technical Team. 

However, as briefly mentioned previously, attributing a vulnerability to “human error” is limiting in terms of the debt of the investigation. The NSTB, for example, investigates the actions of pilots and their interactions with the plane’s technological systems onboard in their analysis of aviation events. Still, the human error component is just one factor in their analysis, and the reports go into detail in the failings of technology in addition to the use of technology by pilots[^8]. 


### Determination

Here, the implementation of the “5 Why’s” Analytical Framework is helpful. Certainly, “human error” should be a component of the Technical Team’s investigation, but the analysis should not stop at the attribution of a vulnerability or failing to the misuse of a system by organization personnel. The Team should also investigate weaknesses of the system in its useability,  the use of the system in the context of personnel’s daily duties, and more. 



    20. Identification of Threat Actor and Origin

**CRISIS MODE**

**Avoid attributing blame for the cybersecurity incident to a specific organization or entity. Doing so diverts time and resources from the identification of contributing factors and invites politicization that will increase pressure on the investigation. The investigation findings will be valuable without identifying the threat actor.**

While the investigation should strive to identify the source of any vulnerabilities discovered and the actor(s) that instigated the cyber incident, the Technical Team will refrain from attributing blame to a singular entity. 


### Considerations

Identification of threat actor and origin is certainly useful information to know, but does the benefit of information justify the time and resources required to pinpoint the threat actor and origin? 

Law enforcement agencies may push for identification of a threat actor for the purpose of holding a party responsible for breaking a law or damages inflicted on the host organization. In this sense, the analysis conducted throughout the technical investigation functions to strengthen grounds for holding a party responsible for the incident. 


### Determination

Identifying a threat actor may inadvertently politicize the investigation or pull in additional stakeholders from outside the cybersecurity community. Extra time and resources would need to be dedicated to verifying the identity if it turned out to be politically sensitive. Furthermore, such sensitive information could inadvertently call the credibility of the rest of the report into question if another stakeholder were to refute the identity of the threat actor and origin. Ultimately, the value of identifying the threat actor and origin does not outweigh the time and resources required.



    21. Systems and Information Security

The National Institute of Standards and Technology (NIST) publishes a useful framework for approaching cybersecurity controls[^9]. The Data Protection section may be particularly useful for a body investigating cyber incidents as data security is critical. The NIST Security and Privacy Controls for Information Systems and Organizations offers up-to-date controls for protecting data[^10]. The Center for Internet Security’s Critical Security Controls also offers useful guidance[^11].



7. Investigation Wrap-Up
    22. Materials

**CRISIS MODE**

**Before closing the Technical Investigation, make copies of all materials, correspondence, and report drafts. All documentation should be archived along with the Findings Report and Final Report. **

Digital copies of all reports, correspondence, and written materials should be archived with the Final Report in a library maintained by the host organization. Evidence, including that which was collected but not used in the investigation, should be cataloged in such a way that supports an outside or later reader in understanding the investigation’s process in coming to its findings. 



    23. Hardware

**CRISIS MODE**

**Return all hardware to the targeted organization at the end of the Board’s Review.**

 At the conclusion of the Closing Board Meeting, once the Final Report has been finalized, all hardware collected from the targeted organization is to be returned to the organization. The return of the hardware must be documented and acknowledged by both the Board and the entity receiving the hardware. All findings gained from the inspection of the hardware should be clearly documented in individual Technical Team members’ final findings submissions.



    24. Party Recommendation Letter

**CRISIS MODE**

**Parties do not take part in the Final Board Meeting where Board Members vote on findings and recommendations. To express their views, Party Coordinators submit a Party Recommendation Letter within 2 weeks of receiving the Findings Report. The Letters are then forwarded to the Board Members to review ahead of the Final Board Meeting. **

**Party Recommendation Letters may include:**



* **Support of or disagreement with particular findings included in the Findings Report**
* **Recommendations for cybersecurity practices to prevent a similar incident from happening in the future or mitigate the impact of a future incident**
* **Points of consideration for the Board Members**

The Parties are not involved in the process of drafting the final report and providing recommendations, though they can submit a Party Recommendation Letter with their recommendations based on the information from the Technical Team’s findings. The Party Recommendation Letters are forwarded to the Board ahead of the Board Meeting. The recommendations included in the Party Recommendation Letters can be incorporated into later drafts of the report.


### Considerations

A Party is not a Board Member, but neither is it a singular technical professional who serves on the Technical Team. Thus, they fall somewhere in between Technical Team and Board Member, and their involvement in the discussion of the implications of the findings and recommendations is unclear. Furthermore, a Party is typically an important stakeholder in the industry, such as a nurse’s union when a hospital receives a ransomware attack or the EPA when a pipeline experiences a cybersecurity incident, so they may want to participate in the development of the Final Report and recommendations, but there may be a question as to their bias. 


### Determination

The NTSB Aviation Manual again offers a useful model. The views of Parties to the investigation can be incorporated into the discussion of the findings and recommendations through a Party Recommendation Letter. In the letter, the Party is free to discuss any of the findings and propose their own recommendations. The letter maintains the separation between the Technical Team and the Board and preserves the impartiality of the Board.



8. Preparation of the Final Report

**CRISIS MODE**

**Once the Technical Investigation has wrapped up and the report writer has drafted the Findings Report, each Team Member will review and sign the report to signify their approval. If a Team Member objects to something in the report, the report can be amended.**

Once the investigation is concluded, the IIC and the report writer will draft a report highlighting the findings, the Findings Report, which will then be read and signed by all Team Members. The report should avoid including attribution of blame or naming a singular system failure as the probable cause for the incident. If a Team Member finds that a significant finding has been excluded from the report, the IIC may amend the Findings Report. With approval from the Team Members, the report becomes the Preliminary Report and is submitted to the Party Coordinators and the Board Members. 

Once the Party Coordinators have responded with their recommendations and suggested amendments in a Party Recommendation Letter, the letters should be forwarded to the Board Members for review ahead of the Board Meeting. 



9. Board Meetings
    25. Opening Board Meeting

**CRISIS MODE**

**At the Board’s first meeting (it can be virtual if Board Members are in different geographic locations):**



1. **Hand/send them a copy of this manual, they can read it after the meeting**
2. **Tell the Board Members about the cybersecurity incident they will be investigating**
3. **Explain that the Board Members will review findings and draw recommendations and the Technical Team will analyze the raw evidence and come up with the findings**
4. **Select an IIC**
5. **Ask Board Members for support recruiting technical professionals to serve on the Technical Team if the Team is not already filled**
6. **Establish a timeline for the investigation**
7. **Schedule the Closing Board Meeting**

At the Opening Board Meeting, the Board Members will designate a Board Member to reach out to the targeted organization of the cybersecurity incident and propose the initiation of an investigation. The Board will also select an investigator to serve as IIC should the organization accept the Board’s proposal to conduct an investigation. Board Members will also discuss and decide on outside organizations to invite to serve as Parties to the investigation. 



    26. Closing Board Meeting

**CRISIS MODE**

**Schedule the Closing Board Meeting within 1 month of finishing the Technical Investigation. The goal of this meeting is for the Board Members to discuss the **

**findings and hypotheses in the Findings Report and come up with recommendations to keep an incident from happening again in the future or mitigating the effects of a similar future incident. The IIC should attend to answer any questions about the investigation or the Findings Report, and the Report Writer should attend to take notes for the Final Report. Findings and recommendations are included in the Final Report through majority vote. Only the Board Members are involved in the discussions and voting on findings and recommendations. The Closing Meeting may evolve into multiple meetings.**



1. **IIC answers questions about the findings and investigation**
2. **Board opens discussion on findings**
3. **Board votes on findings**
4. **Board members propose recommendations**
5. **Board opens discussion on recommendations**
6. **Board votes on recommendations**

The Board Meeting should be scheduled within one month of the conclusion of the technical investigation. All Board Members must be available for the duration of the Board Meeting. The IIC and the report writer will also attend.

The IIC will attend the Board Meeting and open the meeting by providing an overview of the Technical Team’s process, progress, and findings. At the conclusion of the IIC’s presentation, Board Members may ask the IIC questions regarding the investigation itself and its findings. The IIC should remain for the duration of the Board Meeting to answer any questions about the findings and should be comfortable explaining technical concepts. However, the IIC will not be involved in the deliberation.

Board Members can request to be shown individual pieces of evidence at the Board Meeting. The IIC should be prepared to present the evidence to the Board Members, explain how the evidence was collected by the Technical Team, and detail the insights gained.

Once the Board Members have understood the review process and findings, they can begin voting on the findings to include in the Board’s final report. After the findings have been finalized, the Board will discuss the addition of recommendations for the cybersecurity community. Board Members can propose interventions they believe could prevent similar attacks in the future and can discuss the recommendations proposed by the Parties in their Recommendation Letters. 

Board Members then vote on the recommendations to include in the Final Report. The report writer will update the report to include all findings and recommendations approved by the Board Members. 

If needed, the Closing Meeting can be extended to a series of meetings over the next few days.


### Considerations

What should be included in the final report? Should all of the findings documented by the Technical Team be included in the final report? How many recommendations should be included?


### Determination

There is no limit to how many findings or recommendations can be included in the Final Report. Ultimately, what is included in the Final Report is entirely determined by the Board Members. If a majority of Board Members agree on including a finding in the report, then it can be included in the final report. The same applies to recommendations.



    27. Letters of Dissent

**CRISIS MODE**

**If a Board Member disagrees with a finding or recommendation included in the Final Report, they can write a Letter of Dissent specifying what they disagree with and why. The Letter will then be appended to the Final Report and included in the distribution of the Final Report. **

In the event that a Board Member feels strongly about a proposed finding or recommendation that was not included in the final report or about a recommendation or finding that was to their belief mistakenly included in the report, the Board Member may write a Letter of Dissent detailing their concerns. All Letters will be appended to the final report.


### Considerations

Because the Board operates on majority vote, there is bound to be dissent among the Board when the final report is determined. It is possible that one or more Board Members will disagree with a finding or recommendation. In which case, disagreeing Board Members may wish to publicly differentiate their opinion from that of the Board. 


### Determination

Because all Board Members are prominent members of the cybersecurity community, publicly stating their differing opinion from the Final Report may be important. Letters of Dissent offer Board Members the opportunity to identify the points on which they disagree and explain their reasons for dissent. Appending the Letter of Dissent to the Final Report includes them in the lessons-learned narrative. 



10. Distribution of the Report

**CRISIS MODE**

**Distribute the Final Report far and wide. First, publish the Final Report to your website. Next, find a permanent home for a future library of archived reports. This could be a separate page on your website or, if you are a government organization, on the public library’s website so that the report is available to everyone. **

Wide distribution of the Final Report will benefit the cybersecurity community at large. A compilation of the facts of what led to the cyber incident and contributed to the ensuing damage will make progress towards creating a collective narrative of the cyber incident. The recommendations included in the Report offer the cybersecurity community the opportunity to jointly draw lessons-learned from the incident. Although there may be some hesitation towards publishing a detailed report of what occurred, including failings of trusted systems and software, for the sake of preserving an image of impregnability or protecting corporate information, the Report should be published because the benefits for the community at large far outweigh the potential negatives for one entity. 

The Final Report should be published to the Board’s website. A library of all of the Board’s past reports should be maintained on the website as well. An accessible archive for the public is an important component in the development of a shared narrative of cybersecurity incidents. The local public library could house the archive of Final Reports and other documents. Storing the documents on the public library’s website would strengthen the message that the investigations and reviews are providing a public good and that the public should have access to the information. 


### Considerations

One body of thought holds that the information contained in a report compiled by the Board would potentially be too sensitive for public release. Such sensitive information may include proprietary information, information regarding the attack method, or software vulnerabilities. Another asserts that there is immense value in disseminating the report and recommendations as widely as possible. The more people read the report and act on it, the safer the cybersecurity community as a whole will be. 


### Determination

The benefits of disseminating the report as widely as possible far outweigh the potential downsides to publishing potentially sensitive information. First, by the time the report will be published, the targeted organization will have updated its systems and security protocol in response to the cyber incident. Second, the entire cyber community, and even all users, stand to benefit from organizations and corporations adapting to the recommendations included in the report. Lastly, everyone benefits from the development of a shared, publicly accessible narrative for cyber incidents, from which all can draw lessons learned. 

Additionally, the Board should reconvene, at least virtually, to discuss new updates as they arise. The Board can discuss and vote on whether the new information necessitates updating the Final Report to include a new finding or recommendation. To ensure that all past cases are monitored for updates, the host organization can monitor updates or designate a Board Member to do so for each case. 


# Conclusion

An MCIIB has immense value for the cybersecurity community as a whole. Currently, there is no investigative board that conducts analysis of major cyber incidents and delivers recommendations to prevent or mitigate damage from a similar incident happening in future. Other industries have such an investigative body. The NTSB investigates all major transportation incidents including near misses in aviation, and its reports are publicly available. As a result, transportation corporations and organizations such as the FAA receive recommendations from the NTSB that make the transportation industry as a whole safer. One such improvement is automatic brake systems for trains. The NTSB repeatedly recommended railroad companies adopt the safety technology and campaigned for legislation on Capitol Hill. In addition, the NTSB’s public library of past investigation reports serves as an archive of transportation incidents and safety regulation progress. A shared narrative of past cybersecurity incidents does not currently exist. A MCIIB can serve a similar function to that of the NTSB for the cybersecurity community.




<!-- Footnotes themselves at the bottom. -->
## Notes

[^1]:
     For example, Kim Zetter, "Big-Box Breach: The Inside Story of Wal-Mart's Hacker Attack," Wired, last modified October 13, 2009, https://www.wired.com/2009/10/walmart-hack/. 

[^2]:
     This is a fictional review board offered as an example of how a board developed using this document would operate. In this example, we imagine the MCIIB of Arkansas was created by the state government of Arkansas. 

[^3]:
     This playbook will probably exist mostly as an online resource intended to be updated over time. Source citations will be footnoted with a full URL to make finding further information easier, but one of the things we’ve noted about cyber investigations is that link rot is part of the problem. As a result, the more academic style of footnoting with full citations will be used instead of inline URLs so that if a link no longer works, the story can at least be researched around.

[^4]:
     The CFPB did not exist in 2005, but it is included for the purposes of this example. 

[^5]:
     Rob Knake, Tarah Wheeler, and Adam Shostack, _Learning from Cyber Incidents: Adapting Aviation Safety Models to Cybersecurity_, November 12, 2021, https://www.belfercenter.org/publication/learning-cyber-incidents-adapting-aviation-safety-models-cybersecurity. 

[^6]:
     "Analyzing Potential Conflicts of Interest," U.S. Office of Government Ethics, https://www.oge.gov/web/OGE.nsf/Resources/Analyzing+Potential+Conflicts+of+Interest. 

[^7]:
     "Conflicts of Interest," National Council of Nonprofits, https://www.councilofnonprofits.org/tools-resources/conflicts-of-interest. 

[^8]:
     The NTSB’s investigation into the Boeing 737 Max incidents in Indonesia and Ethiopia, for example, looked into both the failings of the MCAS software that was used in the 737 Max and the way the pilots interacted with the system and responded to its alerts; National Transportation Safety Board, _Assumptions Used in the Safety Assessment Process and the Effects of Multiple Alerts and Indications on Pilot Performance_, September 19, 2019, https://www.ntsb.gov/investigations/accidentreports/reports/asr1901.pdf. 

[^9]:
     National Institute of Standards and Technology, _Cybersecurity Framework_, April 2018, https://www.nist.gov/cyberframework. 

[^10]:
     National Institute of Standards and Technology, _Security and Privacy Controls for Information Systems and Organizations_,  September 2020, https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final. 

[^11]:
     "The 18 CIS Critical Security Controls," Center for Internet Security, https://www.cisecurity.org/controls/cis-controls-list. 
