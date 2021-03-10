# Product-Management-Process
Process Docs for Product Development Service Delivery Teams and Consultancies.

## Introduction: 
I've been Leading Agile Product Development for Consultancy Firms and Service Delivery teams for the past 15 years. Though the projects and industries I've delivered for are varied, one thing remains consistent - I keep re-writing the best practices 'run book' for how to approach Product Management and Delivery for Software projects, and training the teammembers. This is me open sourcing the info and making it available (in part so I don thave to write it again at every new company I work for ;) ). 

This work is intended to be for Product Managers, Engineers, Business Development Teams, Product Management consultancies who are trying to figure out how to optimize thier process and approach.

Technology is a tool. Our job as Technologists is to apply those tools well and justly. When we solve the right problems for the right people, we can affect real change using technology as a tool for good. Doing Product Management and Delivery well allows for this.

Feel free to contribute to the repo. I acknowldedge that for different industries slightly different approaches are appropriate. This is inteded to be a base line process and approach for deliverying aligned products/solutions, keeping teams efficeint, customers happy, all in service of making better products with a user centered approach to Product Development. 

Enjoy. 

p.s. Yes, I am available to consult for your organization on process, organizational development, training Product Development Teams and Managers in AGILE, and on specific projects.


## Business Development Phase:
+ Client Account Discovery Meeting - (Biz Dev, Client, Dept Lead ?)
+ Discuss services, and expertise we offer.
+ Assess client needs and engagement possibilities or specific project needs over next 12 months
+ Define what we could do for them
+ Project RFP Call - Project/Product Goals, Deliverables, Milestones, features, requirements - (Biz Dev, PM Lead, Design Lead, Client)
+ Technical Call - Details, environments, technical reqs/limitations, → Estimation. (PM, Tech Lead)
+ SOW Creation - Biz Dev Attempts to gather some of the information in this: Project SOW Proposal Plan Template
    - Project/Product Manager Lead is then responsible for getting input from a Design and Technical Lead and creating a high level estimate and project plan that operates in reality and could be reasonably delivere on with enough room/time to complete and deliver sucessfully.
    - This goes back to Biz Dev resource to put into a contract SOW along with pricing and team size and skills list.
    - SOW draft is sent through Tarun/Operations to get MSA and SOw approved ingternally
    - Sent to client for approval.
    - Confirm project kickoff date.
+ Internal Resourcing Meeting - Ops meeting to discuss how to staff the project, a Product Manager and Team is assigned.
+ Biz Dev hands over to Project PM Lead for Kickoff and Project Initiation and Discovery.
+ Set Up Bi-Weekly, or Monthly Feedback Session/Semi-Regular Checkins - SalesLead or Account Manager with Client
+ Respond as needed and proactively
+ Celebrate Launches and major milestones in person when possible

## Project Initiation Phase
**Sprint 0:** 
Biz Dev + Product
+ Project Kickoff Meeting
    - Client brief Team on project scope 
    - Team Brief Client on Teams project approach, and reporting needs/expectations
    - Set Sprint Cadence, schedule Agile sprint meetings (Grooming, Planning, Retro, Demo)
    - Send agenda to client outlining objectives in advance of call, 
    - Set Up Project Tools
+ Schedule Discovery Meetings for Product Roadmapping with Client 
    - Schedule time with Product Owners to develop/confirm use cases, gain approval on prioritization and stories, create MVP definition.
+ Internal Tech Kickoff:
    - Brief Engineering + Designers on project details and confirm approach.
    - Set Team Charter - Shared team norms and operating procedures such as communication channels and expectations, meeting types and times, and tools and standards to be used are critical for forming high-functioning teams and delivering a successful project.
     - Discuss and agree on a common set of expectations and team norms to begin the project.
     - The [team charter](https://github.com/amilash/Product-Management-Process/blob/master/team_charter) is a living document that should be revisited at the start of each sprint and updated as lessons are learned or situations change.
+ Engineering Sprint Zero
- Teams goal is to get repos up, create accounts for the project, get credentials for any client systems, etc..
    - CI/CD pipelines + DevSecOps accounts and tools (circle CI, Jenkins, GitLab, etc..)
    - Testing suites and tools
    - Security tools (snyk, etc..)
    - Access provisioning - request access to necessary accounts from client, create accounts for project as needed (AWS, GCP, cloud hosting, testing suites (Jenkins, cucumber)
    - Set up project repos, (github, gitlabs, etc...)
    - Set up Project Managmenet Tools and Repos (Atlassian - Jira/Confluence, Gitlabs, Github Wiki, Trello, Asana, Notion, etc...)

## Agile Ceremonies and Project Approach
To foster **continuous learning and improvement**, and to **create more value every day** for the organization and the users it serves, our team operated via frequent, open communication and rapid, multi-level loops of **hypothesis, delivery, measurement, and refinement**. The following describes the Agile ceremonies performed during a sprint.

1. **Prioritization** - The team will identify and work first on issues of biggest risk and potential impact to the delivery/release. We will create, using the minimum level of resources and lowest fidelity medium required, assets designed for maximum, actionable learning.

1. **Agile Ceremonies** - The team will operate on a rigorous and predictable schedule to create an environment of maximum flexibility and ability to respond quickly to feedback.
   - **Daily Standups** - To keep the team aligned and unblocked, we will spend ~15min each morning as planned in the [team charter](https://github.com/cedar-challenge/raft-monorepo/blob/main/docs/team-charter.md), enabling each team member to report out yesterday's results, today's goals, and whether they need any help. If issues warrant further discussion, the scrum master will set the conversation to continue with an appropriate sub-set of team members at the end of the full team standup.
   - **Sprint Planning** - Sprint Planning takes place once per sprint. During this meeting the team reviews the high priority User Stories in the product backlog, creates a consensus around technical approach, and estimates the stories. The team then commits to the sprint size and the ammount of stories to deliver for a given sprint based on estimated effort and complexity of task.
    - **Clear User Stories**
     - To immediately convey intent to implementors, story titles will follow the convention of "As a {_type of user or stakeholder_}, I want {_a clear goal_}, so that {_desired outcome is achieved_}."
     - To ensure consistency and rigor, use an [issue template](https://github.com/amilash/Product-Management-Process/blob/master/Issue_Template) including background and purpose, granular tasks, open questions, resources, detailed acceptance criteria, and definition of done.
    - **Backlog Grooming** - Backlog grooming is done once per sprint prior to sprint planning. The goal is to assess any new information, asks and user stories and allow for adjustment to the backlog items in the roadmap. This practice allows teams to pivot and adapt quickly to changing external circumstances allowing teams to adapt and consistently deliver the most valuable features and opportunities for users.
   - **Sprint Demo** - At the end of the sprint the team will demo the finished work to the Product Owner and receive feedback. This feedback is used to add work to the backlog and identify areas for team improvement.
   - **Retrospectives** - To maximize learning and team transparency in the spirit of continuous improvement, we will hold facilliated 1-hour sessions at the end of each sprint to discuss what went well, what did not go well and what we learned from it, and any general team concerns. This is the room where elephants are to be addressed while they are still small and manageable and promote both transparency and continuous improvement.

## Product Discovery Phase

Product and Design Discovery (using Human Centered Design approach)
+ Problem Statment/Product Vision Definition
+ Product Metric Asses + Analysis
+ Design Research Plan
+ User Personas
+ Customer Journey, Empathy Mapping
+ User Flows
+ User Interviews
+ Affinity Mapping
+ Lo Fidelity Wireframes
+ Hi Fidelity Wireframes + Design

Technical Discovery
+ Assess Platform requirements 
+ Technical Architecture
+ Define Technical Stack
+ Ci/CD pipeline and automated testing infrastructure
+ Data Schema and Entity Maps
+ State Diagram

Product Roadmapping
+ User Stories, Epics 
+ Prioritizing User Stories
+ MVP, Version Planning
+ Project Plan, Milestones
+ Roadmap

## Product Delivery Phase

Agile Software Development Release Process

Sprint 1 * X:
+ Product Backlog Grooming
+ Engineering Sprint Planning
+ Daily Standup
+ Sprint Demo + Reporting - Per Sprint
     - Working Code + Tests/Documentation
     - Team Sprint Reporting
     - Resource Leveling/Needs
+ Sprint Retrospective
Roadmap Planning
    - Track milestones within and across sprints on your project wiki
    - Keep prioritized backlog tickets tagged to release versions as your iterative version plan
    - Product Roadmap should be accessible or reported to client consistently
    - Update this every sprint via backlog grooming
    - Communicate splicitly major changes
Monthly -  Invoicing
Quarterly - Check in with Business Team:
    - Roadmap Planning
    - SOW Extension/ Resource Leveling

## Project Closeout

Owner: PM Project Lead / Biz Dev / Engineering Lead

PM / Engineering Lead

Deliverables:

+ Audit and handoff of Project Accounts - PM
+ Systems migration + or data handoff to client - PM
    - Jira/Confluence exports
    - GitHub repo access
    - AWS hosting accounts? 
    - etc...
+ Documentation
    - Discovery and Product Deliverables
    - Problem Statement/Product Vision
    - User Personas
    - Customer Journey
    - User Stories
    - Product Vision
    - Customer Journey Maps
    - Product Roadmap Versions
    - MVP definition
    - Data Architecture
    - Technical Architecture
    - Other Product Documentation
    - Product or Technical How to Manuals
    - Read Me file for codebase
    - Test cases, or tests in code
    - Confluence Product and technical documentation
    - Jira Exports
    - Security Review + Checklist
    - Design Files Handoff
     - PDF export from Invision
     - Invision Project export, or retain access credentials?
     - Zeplin access to client
     - Sketch Design Source Files? (If this design team reserves 4-8 hours to prepare files for delivery)
+ End of Project Retrospective (internal + with client)
    - Internal with Project Team
    - With Client and Project Team
+ End of project client survey?
