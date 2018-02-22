# Introduction
This document outlines our (v1.0) processes for work prioritisation, assignment and management.
Kanbans are currently hosted on a livingston-hosted instance of a kanban tool (WeKan). This is being used during development and refinement of the process. The intention over time is for the process to be implemented on the ServiceNow platform and for further convergence on scaled agile processes for programme and solution backlogs ( http://www.scaledagileframework.com/program-and-solution-backlogs/ ) - the following should be read in that context.

# Process Overview
We use the following process to manage delivery of work in the team. 
The process aims to triage work and break it down in stages into chunks which are deliverable within a PI and then within a single sprint. The aim is to maintain a reasonable and steady delivery progress across the wide range of activities currently being undertaken across consultancy, development and hosting.

Work is surfaced on a series of Kanban boards, 
* the service backlog, showing all work currently in train and 
* the current sprint backog, showing work for the current sprint
* future sprint backlogs showing work scheduled for forthcoming sprints in a PI

As sprints are completed, the boards representing them are archived and new ones created.

![Process Kanban](/Process%20Kanban.png)

The service backlog kanban is used as the overall basket of items to be worked on and contains three main columns:
* the master backlog column 
* The PI column - a list of items that can be delivered over a PI,
* A Sprint column - a list of items that should be deliverable within a sprint. 
Items in the three columns are generally analogous to Epics, Features and Stories respectively in size and scale (but may be of any type in the SAFE requirements model http://www.scaledagileframework.com/safe-requirements-model/). Two additional columns are used to list work done and work that has been parked parked (i.e. work that cannot currently be scheduled, for example it is under consideration but awaiting further analysis or formal decision from a third party). 

![Service Backlog](/Service%20Backlog%20img1.png)

# Sources of Demand
Items on the service backlog are from two sources - eHealth SLA work and NSS internal work. Items can be either New demand, BAU or service improvement. 
NSS work may be part of or separate from the digital transforamtion programmge. NSS work done under the DT programme should come in as prioritised by the digital demand stream and is marked as digital demand and added to the service backlog without further analysis (though will still need to be prioritised as part of the backlog refinement process). Non-DT work would go through a scoping phase and be marked as pre-discovery.
eHealth SLA work can come on to the backlog as new business agreed by the steering group or as fulfillment of existing agreed services.

# Service Backlog Refinement - Funneling and analysis
Senior staff meet fortnightly to discuss current and new demand and agree items on the service backlog. Senior staff meet fortnightly to discuss current and new demand and agree items on the service backlog. 
The service backlog refinement process acts as the funnel for the service backlog. New work items are added for acton in forthcoming sprints, the priority of new and existing is re-considered and, if necessary adjusted. This is done by moving pieces of work from the master backlog to the PI and sprint columns. items on the sprint backlog column can be moved onto individual sprints.

##Master Backlog
Generally, work that is on the master backlog in on the Kanban is larger in scale, representing collections of multiple user stories deliverable over one or more program increments. The multiple stories they represent are shown within a service backlog item as one or more checklists. Work on the service backlog is examinned and chunks are 'broken off' from this into items deliverable across PIs and sprints respectively.
(Where work comes from a legitimate source of demand but additional analysis is required, items that are much smaller in scale and potentially deliverable witin a single sprint might be added.)

## PI Backlog
The PI backlog consists ot items broken down from the service backlog into items deliverable over the course of a 12 week programme increment.
We are currently experimenting with the idea of breaking PIs into two-phases of 6 weeks each; PIa and PIb to support greater flexibility in dealing with new demand coming on to the service backlog. (an example would be responding to new security threats).

![Sprint Backlog](/Sprint%20Backlog%20img1.png)

## Sprint Backlog
Items in the PI backlog are assessed and further decomposed into sprintable stories during backlog refinement meetings.
Depending on the priority of items on the PI backlog, this refinement may take place over several sprints. (The principle used is for additional detail and refinement to be done as needed and as close to intended delivery as possible, to avoid losing agility). Sprintable stories are moved on to individual sprints for completion.

![Refinement process](/backlog%20refinement.gif)

# Running Sprints
Items which are distributed into sprints from the service backlog into individal sprints are handled through a normal sprint process. The team meets at the start of a sprint to plan work and conducts a sprint retrospective at the end of each sprint to consider progress. Daily standups are conducted, either in person or through messaging on a #Slack board. The team can pick items off the sprint backlog opportunisically and progress of work is controlled on Sprint boards moving through "On sprint", "Doing", "Done"  (we are considering whether to use on-sprint, doing, testing, released, done in future iterations). 

# Tags
Tags are used to categorise items on the lists.
These are filtered to allow for measureent of effort by category. For example, items may be tagged as new demand, bau and service improvement. 
The following tags are in (V1) use

### Labels

* Security👮
* KM and DocMgmnt 📙
* Infrastructure🏗
* Governance🤴
* Digital development📳
* Sensitive 🤞
* Mnt and Management🚜
* New Service Request
* Service Improvement - CSI 🦄
* Unaccounted for query 💀

# Points
Points are assigned at the sprint level. We have agreed in the team to assign 2 points per day worked so for a team of 8 a sprint is worth 160 points (assumes no holidays). 
 
#  Undone Items
1. Unfinished/UnDone items are put back on the service backlog for reassessment 
2. The backlog refinement reassesses and re-prioritises the backlog. Typically unfinished items end up at the top, but not always. 
3. Items may be resized where work has been done to reflect what will go on the next sprint.
(Unfinished items are not included the velocity calculation of the current sprint.)

# Common Tasks
Certain tasks are seen as common to multiple projects. We are developing a set of standard checklists to reflect the common steps to be carried out. As we develop the approach we will create more "template tasks" to embed good-practice in work delivery.


