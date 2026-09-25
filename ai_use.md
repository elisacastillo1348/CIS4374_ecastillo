# CIS4374_ecastillo
CIS4374.19148 - Semester Project
# AI Use Disclosure

**Assignment:** Semester Project, Smart Parking Platform
**Student:** Elisa Castillo
**Course:** CIS 4374

## Summary

I used AI tools as a learning and structuring aid for this assignment. I described the project to the tools in my own words and did not upload the assignment PDF to Gemini. I used the tools to understand how a Software Requirements Specification is organized, how to structure the Vision and Scope section, and how to format the document professionally. I wrote all of the document content myself in my own words, and I verified the AI output before using any of it. The instances below document every use.

## Google Gemini

**What it was used for:**
I used Gemini as a coach and thinking partner to understand and plan the document, not to write it. I asked it to explain the standard structure of a Software Requirements Specification and how to organize my full semester document, to recommend how the Vision and Scope section should be structured, and to describe how professional formatting (running headers and footers, table of contents, typography, and figure and table captions) should look. I directed Gemini to guide and review my work rather than produce the content for me.

**Prompts I used:**

Prompt 1 (opening message):

```
You are my project coach and thinking partner for a software engineering project that runs across a full semester. I am a Computer Information Systems student. Your job is to help me understand the material and produce strong work myself, not to do the work for me.

Default behavior I want from you:
1. When I ask about something, explain the concept first and, when it helps, ask me questions that push my own thinking before you give me an answer.
2. Review sections I have already drafted and tell me what is missing, unclear, or weak, then suggest how I could improve them in my own words.
3. Help me brainstorm, structure, and organize, and proofread my writing after I draft it without changing my meaning or voice.
4. Do not write my analysis, requirements, or use cases from scratch for me. If I ask you to just produce a section, remind me to draft it first and bring it to you for feedback.

Here is the project in my own words:

My fictional company is $oftware Corp, a software studio with an unlimited budget and resources. We are building a Smart Parking Platform, a web and mobile system that helps drivers find, reserve, and pay for spaces in parking garages in real time. The platform shows live availability on an interactive map, gives navigation assistance, and gives parking operators tools to manage occupancy, pricing, and reporting.

The business problem: drivers waste time searching for parking, which causes congestion, frustration, and lost productivity, and operators lack good tools to monitor occupancy, set pricing, and improve how their facilities are used.

Core features I need to cover: user registration and authentication, live availability of parking spaces, an interactive map of available locations, reservations, digital payment processing, reservation history and receipts, an administrative dashboard for operators, occupancy reporting and analytics, notifications and alerts for users, and integration with external mapping and navigation services. I am expected to find more requirements through stakeholder analysis and requirements elicitation.

Stakeholders: drivers and vehicle owners, parking facility operators, city transportation departments, system administrators, finance and billing staff, mobile app users, and external payment providers. My internal teams cover mobile, web, backend and API, mapping and location services, payment integration, and quality assurance and testing.

Constraints: an unlimited theoretical budget, a fixed timeline of one semester, dependence on external services and APIs, and compliance with security, privacy, and city ordinances and laws.

The deliverable is one document that I grow every week across the semester until it becomes a full project management plan and software requirements specification (SRS). It needs to include:
1. A research and competitive analysis section that compares existing parking solutions, notes their strengths and weaknesses, and explains how my platform will be different.
2. A vision and scope section that introduces my fictional company, explains how the project was acquired, and gives an overview of what it is about.
3. An SRS with a minimum of 15 use cases that grows toward completion over the semester.
4. Project management content: requirements gathering, stakeholder management, scheduling, budgeting, risk management, and team coordination.
5. Professional formatting with a header, footer, table of contents, and image captions.

To start, please confirm you understand how I want you to work with me, then ask me which section I am focusing on this week and what I already have, so we can work from there.
```

Prompt 2:

```
Help me first with the structure of a SRS and describe to me how should my project should be structured it (the project documentation).
```

Prompt 3:

```
Give me your recommendations on how the vision and scope section should be structured based on what I told you about the project.
```

Prompt 4:

```
Be more specific on how the professional headers and all of that should look like.
```

Prompt 5:

```
Could you describe me the correct way to build a WBS and what elements should include?
```

Prompt 6:

```
Now could you describe me the correct way of how a timeline for a project like this should look like? How does the Gantt chart should be implemented in a project like this?
```

Prompt 7:

```
Do you recommend me to use Power Point to build both WBS and Gantt chart?
```

Prompt 8:

```
Could you tell me what is necessary in a backlog?
```

Prompt 9:

```
What is the difference between creating a Scrum Backlog in Jira and in Trello? Which one do you recommend to use?
```

**What I kept and what I changed:**

What I kept as guidance:
- The general idea that an SRS moves from high level context toward specific requirements (introduction, overall description, then specific requirements including use cases and functional and nonfunctional requirements). This informed how I laid out Section 4.
- A checklist of what a Vision and Scope section should contain (company profile, how the project was acquired, the business problem, what is in scope and out of scope, and constraints). This informed the subsections of Section 3.
- Formatting conventions, which informed my cover page, my running header and footer, my table of contents with leader dots limited to heading level three, my figure and table caption format, and the document conventions listed in Section 1.3.
- The idea of a deliverable oriented Work Breakdown Structure organized in hierarchy levels (the overall project, major subsystems, deliverables, and work packages), the rule that the breakdown should cover one hundred percent of the scope, and the guidance that a work package should represent roughly one day to two weeks of work. This informed how I plan the Work Breakdown Structure in the project management section.
- The phase based semester timeline (initiation and scope, requirements, system design and project management plan, implementation and integration, quality assurance, and final delivery) and the essential elements of a Gantt chart (task identifier and name, start and end dates, predecessors, assigned team, and percent complete). This informed how I plan the project schedule and Gantt chart.
- The recommendation to build the Work Breakdown Structure and the Gantt chart in a dedicated tool and insert them as captioned images rather than building them in PowerPoint. This informed my tooling choice for those diagrams.
- The elements of a product backlog: a unique item ID that traces to the WBS and SRS, the user story format, acceptance criteria in the Given, When, Then format, MoSCoW prioritization, and story point estimation, plus the backlog table layout (Story ID, User Class, User Story Statement, Priority, Story Points, WBS reference).
- The comparison of Jira and Trello and the recommendation to use Jira for a project like this, which helped to know how I plan to manage the backlog.

What I changed or wrote myself:
- I did not use Gemini's proposed top level outline as it was. I reorganized the document into my own structure: a dedicated Introduction (Purpose, Intended Audience, Document Conventions), followed by separate top level sections for Research and Competitive Analysis, Vision and Scope, the Software Requirements Specification, Stakeholder Analysis and Management, Project Schedule, Budget, Risk Management, Team Structure and Coordination, Appendices, and References.
- I wrote all of the content in my own words. The competitive analysis of SpotHero, ParkWhiz, and ParkMobile is based on my own research of those products and their reviews, and the sources are listed in the References section. None of that text came from Gemini.
- I wrote my own acquisition story for the project (commissioned by a regional parking operator working with a city transportation department through a request for proposal) instead of using the example scenarios Gemini offered.
- I wrote the fifteen use cases myself as user stories in the format "As a role, I want a goal so that a benefit," and I mapped them to the high level feature list.
- The Work Breakdown Structure, schedule, and Gantt chart that I add to the document are my own work, built in [name the tool you used, for example Excel, Draw.io, Lucidchart, or Mermaid.js], with my own task breakdown, durations, dependencies, and team assignments. I did not copy Gemini's example hierarchy or its sample Gantt table.

**Verification:**
I checked Gemini's structural advice against the assignment instructions and the course slides, confirmed the competitive claims against the sources in the References section, and reviewed all wording. No text was copied from Gemini into the document without being rewritten in my own words.