# Product Development (and Management) Process
How to Process Documentation for Product Development Service Delivery Teams and Consultancies. Written by a Product Managment Lead.

## Introduction: 
I've been Leading Agile Product Development for Consultancy Firms and Service Delivery teams as a Product Management Lead for the past 15 years. Though the projects and industries I've delivered for are varied, one thing remains consistent, I repeatedly write the best practices 'run book' for how to deliver Software Product Development and Product/Project Managemet, and train team members. This is me open sourcing the info to make it available (in part so I don't have to write it again at every new company I work with ;) ). 

This work is intended to be for Product Managers, Engineers, Business Development Teams, Operations Teams, and Product Management Consultancies who are working to optimize thier process and approach and deliver best in class service and products. I acknowldedge that for different industries slightly different approaches are appropriate. This is inteded to be a base line approach for deliverying aligned products/solutions, keeping teams efficeint, customers happy, all in service of making better products with a user centered approach to Product Development. 


Technology is a tool. Our job as Technologists is to apply those tools well and justly. When we solve the right problems for the right people, we can affect real change using technology as a tool for good. Doing Product Management and Delivery well allows for this.

Feel free to contribute to the repo.

Enjoy. 

p.s. Yes, I am available to consult for your organization on process, organizational development, training Product Development Teams and Managers in AGILE, and for specific projects and product delivery.


*This work comes from a combination of processes I wrote as Product Management Lead while working at [Monsoon](https://techcrunch.com/2015/07/08/capital-one-acquires-oakland-based-design-and-development-firm-monsoon/), [Kunai](https://www.kunaico.com/), and now for [Raft](https://goraft.tech/), as well as practices I've learned, developed, and taught over my careers worth of sucessful products and projects. Leadership from each company mentioned here and I discussed open sourcing the info, I just never had time to before now. I'd like to credit [Aaron Cooley](https://github.com/acooley) specifically for his contributions to some of the more technical pieces.*

# Product Approach and Agile Ceremonies 
[Why? An Aligned Approach to Product Development](https://github.com/amilash/Product-Development-Process/blob/master/aligned_approach.md)

[Agile Sprint Development Process](https://github.com/amilash/Product-Management-Process/blob/master/agile_sprint_development_process.md)

[Human Centered Design Exercises](https://github.com/amilash/Product-Development-Process/blob/master/human_centered_design.md)


# Product Development Phases and Steps
[Business Development Phase](#Business-Development-Phase)

[Project Initiation Phase](#Project-Initiation-Phase)

[Product Discovery Phase](#Product-Discovery-Phase)

[Product Delivery Phase](#Product-Delivery-Phase)

[Project Closeout](#Project-Closeout)

## Business Development Phase:

**Goal:** To understand the value that the Consulting/Product Devlopment Team can help with and the context that exsists in, the "Why", to define and approve an SOW and Project Scope and Budget that for a Project Team to thereby develop a Product with.

+ Client Account Discovery Meeting - (Biz Dev, Client, Dept Lead)
+ Discuss services, and expertise Project Team can offer.
+ Assess client needs and engagement possibilities or specific project needs over next 12 months
+ Define what we could do for them
+ Project RFP Call - Project/Product Goals, Deliverables, Milestones, features, requirements - (Biz Dev, PM Lead, Design Lead, Client)
+ Technical Call - Details, environments, technical reqs/limitations, → Estimation. (PM, Tech Lead)
+ SOW Creation - Biz Dev attempts to gather some of the information to fill out a Project SOW Proposal Plan Template. Including the PM and Tech Lead here to provide line items needed and estimates is critial to ensuring that your project contact operates in reality and sets your team up for success in delivery.
    - Project/Product Manager Lead is then responsible for getting input from a Design and Technical Lead and creating a high level estimate and project plan that operates in reality and could be reasonably delivere on with enough room/time to complete and deliver sucessfully.
    - This goes back to Biz Dev resource to put into a contract SOW along with pricing and team size and skills list.
    - SOW draft is sent through Operations to get MSA and SOW approved ingternally
    - Sent to client for approval.
    - Confirm project kickoff date.
+ Internal Resourcing Meeting - Ops meeting to discuss how to staff the project, a Product Manager and Team is assigned.
+ Biz Dev hands over to Project PM Lead for Kickoff and Project Initiation and Discovery.
+ Set Up Bi-Weekly, or Monthly Feedback Session/Semi-Regular Checkins - SalesLead or Account Manager with Client
+ Respond as needed and proactively
+ Celebrate Launches and major milestones in person when possible

## Project Initiation Phase
[Project Initiation Details](https://github.com/amilash/Product-Development-Process/blob/master/Project_Initiation.md)

**Goal:** Set up the project infrastructure. Align team on knowns. Align on neede unkowns. Plan a sucessful discovery approach.

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
    - Set [Team Charter](https://github.com/amilash/Product-Management-Process/blob/master/team_charter.mdv) - Shared team norms and operating procedures such as communication channels and expectations, meeting types and times, and tools and standards to be used are critical for forming high-functioning teams and delivering a successful project.
     - Discuss and agree on a common set of expectations and team norms to begin the project.
     - The [team charter](https://github.com/amilash/Product-Management-Process/blob/master/team_charter) is a living document that should be revisited at the start of each sprint and updated as lessons are learned or situations change.
+ Engineering Sprint Zero
Teams goal is to get repos up, create accounts for the project, get credentials for any client systems, etc..
    - CI/CD pipelines + DevSecOps accounts and tools (circle CI, Jenkins, GitLab, etc..)
    - Testing suites and tools
    - Security tools (snyk, etc..)
    - Access provisioning - request access to necessary accounts from client, create accounts for project as needed (AWS, GCP, cloud hosting, testing suites (Jenkins, cucumber)
    - Set up project repos, (github, gitlabs, etc...)
    - Set up Project Managmenet Tools and Repos (Atlassian - Jira/Confluence, Gitlabs, Github Wiki, Trello, Asana, Notion, etc...)
+ Design 
    - Sync with Product Manager and prepare for Design Research and Disovery by creating an:
    - Discovery and Design Plan

## Product Discovery Phase

**Goal** Goal is to understand/define the project problem and scope, who the users we're solving it for and providng value to are, and what contexts in which we are creating a solution. Current vs aspirational. This is where we start making the product, and ensuring we are solving the right problem for the right users. From there we will come out with User stories and an MVP definition that developers/engineers can start building with.

Product and Design Discovery ([Using Human Centered Design approach](https://github.com/amilash/Product-Development-Process/blob/master/human_centered_design.md))
+ [Problem Statment/Product Vision Definition](https://github.com/amilash/Product-Development-Process/blob/master/human_centered_design.md)
+ Product Metric Asses + Analysis
+ Design Research Plan
+ [User Personas](https://github.com/amilash/Product-Development-Process/blob/master/human_centered_design.md)
+ [Customer Journey, Empathy Mapping](https://github.com/amilash/Product-Development-Process/blob/master/human_centered_design.md#Customer-journey-mapping)
+ [User Flows](https://github.com/amilash/Product-Development-Process/blob/master/human_centered_design.md#user-flows)
+ [User Interviews](https://github.com/amilash/Product-Development-Process/blob/master/human_centered_design.md#user-interviews)
+ [Affinity Mapping](https://github.com/amilash/Product-Development-Process/blob/master/human_centered_design.md#affinity-mapping)
+ [Lo Fidelity Wireframes](https://github.com/amilash/Product-Development-Process/blob/master/human_centered_design.md#wireframing)
+ [Hi Fidelity Wireframes + Design](https://github.com/amilash/Product-Development-Process/blob/master/human_centered_design.md#wireframing)

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

**Goal** To efficiently execute and build a product MVP that can be tested and validated by users and Product Owners iteratively and explicitly during a follow on Pilot to validate if the product is sucessful in solving the problem as defined and helps to solve user needs and provides aligned value to both user and the organization.

[Agile Software Development Release Process](https://github.com/amilash/Product-Management-Process/blob/master/agile_sprint_development_process)

Sprint 1 * X:
+ Product Backlog Grooming
+ Engineering Sprint Planning
+ Daily Standup
+ Sprint Demo + Reporting - Per Sprint
     - Working Code + Tests/Documentation
     - Team Sprint Reporting
     - Resource Leveling/Needs
+ Sprint Retrospective
+ Roadmap Planning
    - Track milestones within and across sprints on your project wiki
    - Keep prioritized backlog tickets tagged to release versions as your iterative version plan
    - Product Roadmap should be accessible or reported to client consistently
    - Update this every sprint via backlog grooming
    - Communicate splicitly major changes

Monthly
+ Client Project Invoicing

Quarterly - Check in with Client + Business Team:
+ PI (Program Increment) or Roadmap Planning
+ SOW Extension/ Resource Leveling

## Project Closeout

**Goal** To hand off the project to thje Client organization (or another vendor) for further developkment and operationalization, or ideally to extend the Product Development to an additional Scope of Work leading to a Pilot, Operationalizing the Product and creating a support team, onboarding customers, and future feature development.

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
     - User Flows
     - Lo-Fi Wirerrames
     - Hi-Fi Wireframes
     - User Interviews/Surveys
     - Product Roadmap Versions
     - MVP definition
    - Technical Documentation
     - Technical Discovery Docs
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
     - Lo-Fi Wirefreames
     - Hi-Fi Wireframes
     - Other UX REsearch outputs, User Interviews, User Flows, etc..
     - PDF export from Invision
     - Invision Project export, or retain access credentials?
     - Zeplin access to client
     - Sketch Design Source Files? (If this design team reserves 4-8 hours to prepare files for delivery)
+ End of Project Retrospective (internal + with client)
    - Internal with Project Team
    - With Client and Project Team
+ End of project client survey
