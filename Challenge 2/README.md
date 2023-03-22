
# Challenge #2

**Learning from WBS Diversity**

2025 PDA Vision Theme: 
Automated Work Breakdown Structure

**Summary**

We all know that no two project schedules are the same.

But just how diverse are project schedules?  What do they have in common, and how do they differ?  The answer to this question is important, because if we can determine how schedules are built up and what drives their structure, we can then start to machine-generate them using algorithms.  This vision is part of the Project Data Analytics Task Force’s work on WBS Automation.

To help us move along our roadmap, this challenge adopts a particular angle.  We want to understand WBS diversity, and how we can benefit from that diversity to make our future schedules more accurate and resilient, and improve project outcomes.
We will start with a set of Work Breakdown Structures (WBS), and see what we can learn!

**Pain Points**

- Our project schedules are usually ‘hand written’, and require expert knowledge to generate; we fail to exploit the vast data plume of past ‘as built’ schedules
- We don’t know how similar our schedules are to one another, nor how diverse they may be
- We don’t know if our new WBS is missing vital elements of work, increasing risk
- It takes time to review WBS, which we don’t have when responding rapidly to tender requests

**Personas**

- As a bid manager, I want to quickly – based on historical schedules - provide a recommendation to the client for the packages of work that we will need to consider to complete this building. 
- As a client relationship manager, I would like my team to provide a parametric model that allows the client to switch on and off certain packages and see what impact this would have on the overall plan, to help me provide a proposal that best meets their requirements.


**Context**

Imagine you run a business that prepares and plans schedules for commercial premises.

There are many different flavours of commercial buildings. The buildings in the dataset range from £50M-£250M, but broadly consist of similar elements, split into various categories. These buildings are across the UK, and at different stages of completion. They all rely on having a clearly defined schedule of codes – reference data that provides key information as to how the packages of work are allocated in order to deliver the project.

A new client has just requested a proposal from for new 12 storey commercial premises, containing: 
- Roof terrace
- Spa
- Underground carpark

Project teams create their schedule of the packages of work they want to use to split up project delivery. This is then used across multiple project systems and processes to ensure work is consistently tracked and delivered. 

Using a master list, project teams select the codes most applicable for delivering their project. There are different specialisms based on the nature of individual projects, which is to be expected, however, there are also different approaches taken to delivering what can at a certain level be deemed to be the standard elements of projects. 

**Dataset Description**

The schedule of codes is used by project teams as reference data for the different packages of work on their project. It is used to allocate, track and manage packages across multiple different systems and processes used throughout project delivery.

At the beginning of the project, teams will select the codes that they want to use for their project. The list is controlled to ensure a level of consistency. 

We have 9 schedules of codes to interrogate, as well as a full list of all available codes. Each building is provided separately with data for:
- Tier 1 category code
- Tier 2 category code
- Tier 3 category code
- Description (of that code)
- Category (i.e. related tier one code)

**Output**

A successful output would be an auto-generated WBS that satisfies the use cases.
You should also address any concerns or drawbacks this process has.

**Benefit**

Work Breakdown Structures are the foundation of any successful project. A good one leads to greater efficiency and clarity. A bad one leads to delays and scope creep that begins almost immediately.

By automating the WBS in an effectively way we can allow all projects to get started on the best foot possible, improving delivery efficiency and giving confidence to all project stakeholders.
