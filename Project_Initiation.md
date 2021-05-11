Please refer to the Kunai Project Customer Journey. It describes the project flow and the high level subjects and goals of those project phases that you as the Product and Project manager will be driving.

# Project Initiation
This is Phase 1 of Product Management responsibilities. Inputs are needed by Team Area Leads and a handoff and information sharing from Biz Dev is critical.

Goal: Set up the project infrastructure. Align team on knowns. Align on neede unkowns. Plan a sucessful discovery approach.

You have gotten an SOW and an NDA from Biz Dev by now and are working with Operations to resource a team and land on a start date and a date for a Project Kickoff call with the client.

Ideally you have designers and engineers lined up for the official Project Kickoff.

## Kickoff Attendees: Client and their project Team + Consultancy's Product Manager, Business Development, Engineers, Designer.
Client brief Project Team on project scope and needs. 
- Project Team Brief Client on working process and reporting needs/expectations
- Set Sprint Cadence, schedule sprint meetings (Grooming, Planning, Retro, Demo)
- Send agenda to client outlining objectives in advance of call, 
- Milestones and User Stories - Schedule time with Product Owners to confirm use cases, gain approval on prioritization and stories.
- Roadmap and Version plan.
## Goal
Start creating project documentation and framing the project parameters. Get any unknown information you need to build a Roadmap/Prioritized and get Sprint Zero started. Create a relationship with the client and stakeholders. Show off how proactive you are and set expectations around how you will drive the project forward.

## Instructions
### Kickoff: Meet with the client.
1. PM, Arrive to this meeting with a project brief covering all the current knowns and highlighting all of the need to know items from the client. This information you should have from Business Development Team, along with their pitch deck, and create a brief that starts to fill out the information you will eventually need to fill up a Roadmap, Vision and Strategic alignment. This can be in a branded Kunai Template, or in your Confluence Project.
2. Gather this info:
- Team contact information, Client + Kunai
- Project Scope and Executed SOW
  - Project Budget
  - Resource(s)
  - Timeline funded (how many sprints, if any critical drop dead delivery dates) 

When you leave your goal should been to have all high level deliverable information

- Product Vision - If they have it, if not lets articulate the goals and the why
- Why - The reasons for the project 
- The How they will measure this - how will they measure success? Let's agree upon this.

3. Set Expectations:
- Review high level Agile Value Prop and how the project will go → Consultant Team's Customer Journey, "This is how we run projects"
- Inform them of our per sprint ceremonies and agree upon Cadence (1 week or 2 week sprints) and day/time for Grooming and Demo. Set up re-occurring calendar invites with all relevant parties.
  - Daily Standup - Project Team + Client Optional unless client has daily contributors (Dev, QA, Ops)
  - Per Sprint Demo - Project Team Dev/PM + with Client
  - Sprint Backlog Grooming - Project Team PM + With Client
  - Sprint Retrospective - Project Team + Client Optional
- Review goals and approach for Week 1 as Discovery/ Sprint Zero, where we set up the Jira/Confluence, Ci/CD and Git Repositories, And Design team will get briefed and started on any UX questions or R1 of UX.
- Set Sprint 1 Start Date. Your team should be resources by then and the work done should be on the product development.
4. Discuss User Stories
- If client has an initial set of these, review and clarify and agree on them. If not schedule discovery sessions to flush out user nees and user stories (see Discovery)
- Prioritize user stories (this can happen in kickoff or in kickoff part 2.
- Build your prioritized backlog from these in Jira.
5. Roadmap- This can happen in a Kickoff #2 if time does not allow)
- If the client doesn't already have the user stories prioritized, get them to commit to a framework or an initial roadmap that lays out what features will be in the Beta/MVP version. 
- MVP/Beta, V1, V2
6. Request Access from the client for any systems or information that we need now or will need soon. Access Procurement can take a long time at client organizations. Start early so it doesn't block you.
7. Document any blocking decisions and who is responsible for answering these unknowns. Follow up on them. 

### What do I do next?
Start sprint Zero. You can track sprint zero activities on the Jira board for best practices.
If you cant get this all done in one meeting, schedule a follow up kickoff with your designer and Tech Lead to focus specifically on Product Vision/Roadmap questions and Customer Journey information.


## SPRINT ZERO
### PM - [Tools and Project Set Up]
- Set an Internal Project Kickoff and ask the team to initiation Sprint Zero activities, and ask them what they need from you and what you will do. 
- Create Google Team Drives Folder for this Project and file all project documents there: You should have at least these docs: Executed SOW, NDA, User Stories, Roadmap (in confluence). Any Pitch Decks Biz Dev Used to win the project. Any other Project Docs. Publish this to the Internal Kunai Team Only. This is an internal project Drive.
- PM Client Drive Folder Template
- Create a line for your project in the Budget Invoice Tracker.
- Project Access Provisioning and Logging: Make a Version for your project and Fill out the Project Links Document in Team Drives Project Folder and keep this updated throughout the project. Ask your Engineering and Design leads and team to help be responsible for logging new accounts. This way we know where all the client and project IP and accounts live. This is important.
- Set up Jira Project
- Set up Confluence Project
- Set up User groups for client and internal team in confluence - do this correctly for security measures.
- Set up Client Slack/Mattermost or Async Messageing channel and add client users - do this correctly and securely. 
- Enter prioritized initial User Stories into Jira backlog.
- Set up any follow up technical calls with client teams or 3rd parties. I.E. to discuss and finalize security technical or data architecture, etc...
- Create a dated V1 Roadmap in Confluence and a Version plan which represents the first set and current understanding of agreed upon priorities. Your current Jira backlog should represent this same priority. Publish this to the internal teams and the client. Keep this updated throughout the project and publish dated version changes as the project progresses per sprint.
- Kick off Discovery Activities

### Engineering
The engineering teams goal should be to set up tools and infrastructure needed for the project so that on week 2 they can hit the ground running with writing code, once the Product and Design team have articulated user stories to start work on.
- Technical Lead should sync with the Product Manager to inform them of cirital tehcnical neeeds and product specific questions that will need to be answered during technical discovery and define a
- Technical Discovery Plan
- Github repos set up
- Set up Ci/CD process (bitbucket? Cirlce Ci, etc..)
- Get team access to the above

Other things Engineers and Engineering Leads can do in Sprint Zero
- Brush up on [Agile Project Delviery Best Practices](https://github.com/amilash/Product-Management-Process/blob/master/agile_sprint_development_process.md)
- Request access for you and your team to Client repo's and systems
- Think about what you will need to know
- Brush up on your engineering skills for the specific technical stack you think your project might be useing. 
- Install things locally and prepare your workstation
- Get into the mindset of building features that are demoable and have demoable value to your Product Manger/Owener and eventual users. this will help them get and give you validation product acceptance and iterate on product needs and stary ahead of your questions and write great acceptance criteria for and with you on user stories. :) 

### Design
Design teams goal is to sync with the Product Manager and create a collaborative discovery process that will work towards developing user stories the Product  Manager can write and prioritize. These excersizes should include Human Centered Design approaches to creating a user oriented product that is in alignment with business and user goals. Decide who will run the discovery sessions, and what goals and deliverables and outcomes are expected from each based on the project and product particulars. Then the design lead should create and prep templates for the discovery excersizes and share and review them with the Product Manager. The design and UX Research Plan should include/provide the following activities/inputs.
- Discovery and Design Plan
- Problems Solving Workshop
- User Persona(s)
- Customer Journey Mapping
- User Flows
- User Interviews
- Affinity/Empathy Mapping
- Lo Fidelity Wireframes
- Hi fidelity Wireframes + Visual Design


DISCOVERY PHASE...visit here for Product Discovery.
Goal: Identify ...
(WIP)
