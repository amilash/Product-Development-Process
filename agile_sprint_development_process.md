# AGILE Sprint Development Process
The development process for Agile/Scrum software to follow.  The following parts of Agile/Scrum are based on best practices and can be implemented by all teams, not jsut software development teams:

## Sprint
A sprint is a time boxed iteration of continuous development effort. Typically a sprint will be 1 or 2 weeks long. Within a sprint you need to have one of each of the following ceremonies:

+ Daily Standup - Daily
+ Sprint Planning - 1x per Sprint
+ Demo - 1x per Sprint
+ Backlog Grooming - 1x per Sprint
+ Sprint Planning - 1x per Sprint
+ Retrospective - >1 per 2 sprints.

## Standup Meetings
Standup Meetings should be held on a daily basis for all teams.  Teams may hold stand-up by delivering status over Slack, e-mail, etc. in lieu of a conference call or in-person meeting at the team's discretion.  To keep the team aligned and unblocked, we will spend ~15min each morning as planned in the team charter, enabling each team member to report out yesterday's results, today's goals, and whether they need any help. If issues warrant further discussion, the scrum master will set the conversation to continue with an appropriate sub-set of team members at the end of the full team standup.
The following format must be used for standup:

A contributing member is any member whose name is assigned in a Jira ticket either in a sprint or in the backlog, or who is responsible for the creation of tickets.  Typically this will include engineers, QA, product owners, DevOps, etc.  Managers in attendance typically don't give status.  Project managers typically don't give status.

Each contributing member gives status in the following form:

+ What they worked on yesterday.  If what they worked on was related to something in Jira (i.e. a Jira Bug or Story, they should refer to the ticket by number and/or description).  It should be noted that contributing members should in most cases be referring to tickets.  Engineers should always be referring to tickets.
+ What they will work on today. If what they worked on was related to something in Jira (i.e. a Jira Bug or Story, they should refer to the ticket by number and/or description).  It should be noted that contributing members should in most cases be referring to tickets.  Engineers should always be referring to tickets.
+ What they are blocked on. If what they worked on was related to something in Jira (i.e. a Jira Bug or Story, they should refer to the ticket by number and/or description).  It should be noted that contributing members should in most cases be referring to tickets.  Engineers should always be referring to tickets. All blocked items should be listed every day regardless of if they are in the sprint or if they have been mentioned in past stand-ups.
Once the status is given there may be up to 2 minutes of discussion and coordination between people attending the standup.  If the discussion continues longer the scrum master (typically the Product Manager/ Scrum Master/ Project Manager) must table the balance of the discussion and coordinate a longer discussion after the stand-up between appropriate parties. This will keep stand ups short and manageable even when yopu have a big team or multiple teams standing up.

## Sprint Backlog Grooming
This is a meeting between Scrum Master, Product Management, Business Owner Optional. The purpose is to priorities work for the coming sprint(s). Backlog grooming is done once per sprint prior to sprint planning. The goal is to assess any new information, asks and user stories and allow for adjustment to the backlog items in the roadmap. This practice allows teams to pivot and adapt quickly to changing external circumstances allowing teams to adapt and consistently deliver the most valuable features and opportunities for users. 

The following deliverables should be created:

Prioritized backlog with Epics, and Stories, and Bugs, that Product has agreed to and map to the project roadmap priorities.
Epics and Stories/ work items are documented with detail including acceptance criteria.
All stories that don't have clear acceptance criteria we should plan to punt to the next sprint, and product should provide this.


## Sprint Planning
During the sprint planning meeting, the engineering team members plan one or more sprints.  Sprint planning must happen once per sprint cycle. During this meeting the team reviews the high priority User Stories in the product backlog, creates a consensus around technical approach, and estimates the stories. The team then commits to the sprint size and the ammount of stories to deliver for a given sprint based on estimated effort and complexity of task. 
The following activities should take place:

+ Planning what Jira tickets will be worked on in future sprints, maybe just the next sprint, maybe a series of sprints.
+ Breaking down work into tickets based on agreed upon approach and subtasks.
+ Estimating work by assigning points to stories.
+ Making a sprint commitment based on past velocity. (Base how many points will your team commits to based on how many points your team was able to deliver last sprint.)

## Other Meetings
Other meetings such as retrospectives and demos are at the discretion of the contributing members.

## Retrospective:
This is a once per sprint, or every 2 sprints meeting and is optional but helpful. The goal of this meeting to identify what works and what can improve. This meeting can help a team improve estimation and expectation setting, as well as identify actionable items to change in process and work approach, resource needs, and communications. The intent is to maximize learnings and team transparency in the spirit of continuous improvement. This is the place where we adress issues before they impact the project and are still manageable to promote transparecy, and empower the team to manage thier work and to be heard.

Format: Round robin, like scrum. Everyone contributes, engineering, qa, devops, product. There is no finger pointing, its about addressing what's working and what can be better. Keep the good, improve a little every iteration

+ What did we do well as a team?
+ What can we improve on as a team?
+ Actionable steps. I.E. Next sprint add QA estimate to stories so we can track the full lifecycle of completion - or commit to fewer stores since we didn't make our sprint commitment, or - not allow product to add tickets to the sprint, and if we do we have to take one of equal effort out.


## User Stories
Each user story must be represented by a story ticket in Jira.  All engineering work must be represented by either a story or a bug.  No additions or changes to the source may EVER be made UNDER ANY CIRCUMSTANCE WITHOUT A TICKET.  To do this will put a platform in production out of compliance.  Any contributing team member may create a ticket at any time.  All tickets must have a description that includes acceptance criteria.  The acceptance criteria determines exactly what work needs to be done to complete the ticket. If an acceptance criteria is not met and the ticket is marked complete it is considered a bug and a bug should be filed.  All stories must be given story points before the are assigned to a sprint that is going to be made active (i.e. all stories in the current sprint must have story points)

## Story Points and Estimating Work
Standard story points are used to point stories. User stories get estimated in Sprint planning by the Scrum Master/ Product Manager and the Engineering team. The team doing the work should estimate the work.

+ Teams should estimate effort by thinking about the effort with a reference of 1 point equaling 1 hour.
+ Valid Story points are 1,2,3,5,8,20,40,100. This is loosely based on the fibonacci sequence. A Story with 100 Story Points is a SPIKE. It requires detailed design, architecture discussion, and/or technology research.
+ Any story more than 20 points have to be broken down.
+ Any story 8 points or larger needs subtasks. It will be a day or multi-day effort and subtasks let us track progress.
+ Stories added to Sprint have to have Story Point and developer assigned.
+ Any team member can add tickets to the backlog. Tickets are either Stories (Enhancement requests, new feature), bugs, or tasks attached to an existing Story/Bug (implementation details).
+ All Jira items identified as a "Story" should have Acceptance Criteria documented.
+ All Jira items identified as a bug should have "Steps to recreate" and environment details documented.

## Bugs
Bugs do not receive story points.  Bugs can be added at any time to any sprint and be given any priority.

## Task and Issue Management 
### Issue creation 
All issues are required to have the following attributes before they are created 

+ QA assignee, which must be a QA engineer 
+ Points, using Fibonacci sequence (1, 2, 3, 5, 8, 13, 20) 
    - Points are estimated taking effort and complexity into account
    - 2 hours worth of work equal 1 point
+ Acceptance Criteria 
You may use an [issue template](https://github.com/amilash/Product-Management-Process/blob/master/Issue_Template) to make this easier in github and or create custom fields in your issue tracker (jira, trello, etc.)

### Bug creation
All bugs are required to have the following attributes before they are created 

+ Steps to reproduce
+ Relevant screenshots, error messages, stack traces, urls, etc
+ Verification comments when the defect is moved to a done state along with relevant screenshots, other verification artifacts
+ QA assignee, which must be a QA engineer

### Tracking issue tickets for a particular release 
+ During sprint planning, when a ticket is pulled into a particular sprint, it's target fix version field should be updated (scrum master)
+ If said ticket is punted from the release, it's target fix version should be updated (scrum master)
+ When a ticket is moved from 'In Testing' to 'Done' state, it's fixed version should be updated to the version it will be released in (qa)

### QA Approval Process 
+ After engineering has finished their PR review for a ticket and their change is built and deployed to the QA environment,  they are to move their story to the QA check state ('In Testing')
+ QA tests the ticket; updates the fix version and moves the ticket to a done state upon successful verification; or re-opens the ticket if it fails verification
+ Tickets that cannot be tested will be marked done by the developer assigned to it and collaborate with qa to get the Fix version updated 

### Automated Testing Standards
+ Unit tests that mock out dependencies should be written for all code with a minimum of 75% code coverage. These should be run pre-push and pre-commit to git.
+ Integration tests are smaller in scope like unit tests, but actually do hit the dependencies like databases and filesystems should be written and run daily
+ Functional tests that ensure the functionality performs as expected for the end user should be set up with a tool like Selenium and executed weekly

### Versions
All stories in a sprint must have one release version associated with them.  This version must be carefully tracked such that when the story or bug is completed the version that it is tagged with is the version in which it will be released.  This is mandatory for compliance and must be done very carefully.  The following rules will ensure this:

+ Version numbers should be used in the planning phases of Product Discovery to tag stories as MVP, V.01, V1, V2 etc..
+ When an engineer submits a PR the version of the associated ticket must match the version of the branch to which the PR will be merged.
+ If the branch is develop, the version must match the next release branch that will be taken off of develop.
+ If the branch is a release branch, the version must match the version of the release branch
+ If the branch is a hotfix branch, the version must match the version of the hotfix branch
+ Once a product goes to production, all completed Jira stories/tickets should be tagged with the release version number accordingly to the code version number(s).

### Version control
<Name> Projects will be hosted on the <TBD> repository and will follow [git-flow](https://danielkummer.github.io/git-flow-cheatsheet/) using the default git-flow branch names and paths.  All development work must be done on a 'feature/{Jira-Ticket-number}' branch and must be merged with a pull request made from GitLab without exception.

## Release Process
Carefully following the release process is critical for continued compliance and must be strictly followed for any and all changes to production. Please review and check off all item in the below Change Management Release Check list to validate appropriate steps.

### DevOps/Engineering Release Requirements 
+ For web apps that are continuously delivered, use [GitHub Flow procedure](https://guides.github.com/introduction/flow/).
+ For all others
    - Release branch is cut from the development branch 1 week before the target release date.  Release branch should be named "release/{0.0.0.0}", replacing 0.0.0.0 with the release version number where the first number tracks major changes, the second number tracks minor changes, the third number tracks patches or bug fixes and the fourth number tracks changes less significant than a patch
    - From the time the release branch is cut, check-ins should be gated to ensure no unwanted changes are checked in
    - Every change thereafter in the release branch must be reviewed on a case by case basis and only gets checked into the release branch with qa, prod, and dev consensus
    - Whenever a release is ready to be pushed from development to QA it should be a build off the release branch following standard [GitFlow procedure](https://nvie.com/posts/a-successful-git-branching-model/) using [this set of extensions](https://danielkummer.github.io/git-flow-cheatsheet/)
    - Once a release is made, master should be tagged with the release version number
    - Hotfixes are cut from the master branch following the naming convention "hotfix/{0.0.0.0}", setting the version number to the current version and incrementing the third number (a patch) or fourth number (less significant than a patch)

### Version Controlled Source
The process for creating releases where source controlled changes are made must follow [git-flow](https://danielkummer.github.io/git-flow-cheatsheet/) for compliance.  git-flow is prescriptive for this process and the tool must be used for all steps with the exception of merging feature branches, which should be merged using a PR on GitLab. If you don't understand this RTFM.  It's in pictures and just about every language on the planet.  Violators will be forced to fix their mistakes, by-hand, on their own time, and explain to InfoSec why compliance rules were broken.  Any version numbering scheme may be used BUT, the version currently in production MUST always have a part of the version number that contains the git commit SHA that matches a git commit associated with the master branch.

### Release Documentation
Every release must have a release page in confluence that contains or links to the documentation detailed in the following sections.  If any section has been omitted or incorrectly completed and a change to production is made the product service is considered out of compliance.  If this happens InfoSec must be notified of the break in compliance and changes must be made immediately to bring the product back into compliance.

#### Scan Findings
Findings from the following tools which are used to scan the platform:

+ <SonarQube>
+ Unit test coverage reports unless reported as part of <SonarQube>
+ Snyk reports at the time the release was made
+ If the product has a web based interface a scan should be made using <Zed Attack Proxy> or a similar tool and the findings should be included.

#### Automated Test Findings
Every release must include the following findings from the automated testing associated with the release:

+ <Selenium> Test Results
+ Current Load Test Results from Blazemeter
+ Any Ignored or otherwise failing unit tests

#### Manual Test Findings
Every release must include clear documentation of exactly what manual tests were performed and what the finding were for each test.  If needed it should be possible for a person with knowledge of the platform to reproduce the testing process.

#### Security Review
Every release must include a security review conducted by the team.  This review must detail:

+ The security architecture of the product or service being released
+ The standard security practices used for any and all platforms, languages, tools, and processes associated with the product or service being released and how the product being released follows or deviates from these practices
+ Any know security findings or concerns associated with the release and the severity of these findings.  DREAD levels are recommended for this.

#### Release Notes
The release notes must include any instructions to DevOps, Operations, or QA needed to test, install or otherwise deploy the software or service to production.  The release notes must also include a link to a confluence page or links to all Jira tickets associated with the release.

#### Sign-offs
Once the release documentation is complete each group within the team must sign off on the release.  It is recommended that the most senior member from each of these teams sign off.  For some projects additional sign-offs may be required and should be added to the documentation here.  The following sign-offs are mandatory for all projects:

+ Lead Product Owner
+ Lead QA person
+ Lead Engineer
+ Lead DevOps and/or Operations
+ IT?
+ InfoSec?
The sign-offs must happen after the release has been fully documented and is ready to be released for production, but before the actual production release is made.

### Version Number
Before release the version number of the release must be documented in the release notes. The version currently in production MUST always have a part of the version number that contains the git commit SHA that matches a git commit associated with the master branch.

### Release and Change Management Checklist
Cut release branch. Use standard GitFlow procedure to deploy this branch. All changes to this branch will be gated.

#### Code Scans
+ Run and pass all unit tests with at least 75% code coverage, preferably 90%
+ Run static code analysis with ESLint and SonarCube
+ Run dynamic code scans with NetSparker

#### Security
+ Run package scans with [Snyk.io](https://snyk.io/)
+ Complete security review checklist for this release and link to it from the release notes
+ Make any necessary changes to the Basic Security Review, if applicable

#### Testing

+ Get sign-off that QA/QC process has been completed and verified for all tickets within the release as per our project process [link to document]
+ Get sign-off from product owner that User Acceptance Testing (UAT) has been completed and verified

#### Release Notes

+ Create Release Notes in Confluence listing all changes included in this release. Include Jira tickets, configuration changes, documentation changes and anything else that has changed.
+ Document production version release date and time

#### Release Approvals

+ Set up Go / No-Go meeting with all parties - client, engineering lead, operations lead, product manager, product owner, and client InfoSec and compliance party as needed. In this meeting, go over the Confluence Release Notes. Each party should add a comment to the Confluence Release Notes stating “I approve” if they approve of the push to production.

#### Deployment and Validation

+ Once ALL approvals have been documented, schedule a deployment window.
+ At start of deployment window, notify all parties that deployment process is starting.
+ Deploy changes
+ Verify deployment
+ Notify parties that release is complete


### Hotfixes
Hotfix code will be cut to a hotfix version branch from the release branch. Pre-release process is same as above production release. However, risk is minimal due to version package size being smaller. (All steps apply, just faster).

+ Go through all checklist items above for hotfix. Document it as a hotfix version.

### Non-Code Configuration
+ Cut branch, if applicable.
+ Run code scans, if applicable
+ **Complete Security checklist**
+ Perform testing, if applicable
+ **Complete Release Notes** 
+ Complete Release Approvals
+ Complete Deployment and Validation
