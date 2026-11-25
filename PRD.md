# Product Requirements Document (PRD)

## Campus Hostel Maintenance Management System

> **Course:** BU-COS 209 Backend Engineering
> **Assigment:** Week 4 PRD
> **Team Branch:** `The-Cipher-Circle`
> **Team Level:** 200 Level

---

## 1. Document Information

| Item | Details |
|---|---|
| Product name | Campus Hostel Maintenance Management System |
| Course | BU-COS 209 Backend Engineering |
| Assignment | Week 4 PRD |
| Team Branch | `The-Cipher-Circle` |
| Team Level | 200 Level |
| Team Members | Wabara Michael, Ukpebor Elliot, Ubani Michael, Onileowo David |
| Date | 23rd November 2026 |
| Version | 1.0 |

## 2. Executive Summary

The Campus Hostel Maintenance Management System is a proposed web-based platform intended to make it easier for students to report maintenance problems in their hostels and follow the progress of those reports. It is also intended to give authorised hostel or maintenance personnel a central place to review, assign, update, and close reported issues.

The team's initial survery was completed by students of the university, and the team has reported that many of the facility-conditions responses selected were either "Fair" or "Good" about hostel conditions. This is an early indication that hostel facilities deserve further developing. The proposed product is a Campus Hostel Maintenance Management System, its purpose is to give students a way to submit maintenance reports, while allowing hostel personnel or people in charge of maintenance to review and update the reports

## 3. Problem Background

Now, Hostel facilities can require manitenance including, overall cleanliness, fixing of toilets, pipes and drainages, doors, lockers, fans, windows etc. When any of these problems occur, students should be able to reach out or try and communicate to the people responsible for the maintenance of the things mentioned above.

The team's survey is intended to learn about how students are faring with the current hostel condition. The team's overall description of the survey was either "Fair" or "Good".

## 4. Problem Statement

Hostel students need a dependable way to report maintenance issues and to check their progress. Our project will investigate whether the existing reporting process makes it difficult for students to record, prioritise, follow up, and resolve the     maintenance requests.

The product will address the problems stated after the teams survey. Our team will establish
- Which maintenance problems occur the most;
- Which halls these problems occur in;
- The current effectiveness of the facilities in the halls;
- How many students currently report these problems.

## 5. Research Objectives

Our research is intended to:
1. Identify the hostel maintenance students experience as unsatisfactory
2. Determine the most frequently reported maintenance problems
3. Identify the most important improvement from the students' point of view
4. Find out whether students can track the progress of their reports
5. Use the findings to determine which features belong in the MVP (Minimum Viable Product)

## 6. Research Evidence

### 6.1 Survey

Our team created a google form titled **Babcock University Hostel Survey**. The response data contain **8 submissions**, timestamped between the 24th and 25th of November. The results below describe only these 8 respondents and should not be treated as representative of every student or hostel resident.

**Level and Hall of Residence**

| Item | Responses | Percentage |
|---|---:|---:|
| 200 Level | 7 | 87.5% |
| 600 Level | 1 | 12.5% |
| Neal Wilson | 4 | 50% |
| Nelson Mandela | 1 | 12.5% |
| Welch | 1 | 12.5% |
| Winslow | 2 | 25% |

**General hostel condition**

| Rating | Responses | Percentage |
|---|---:|---:|
| Fair | 5 | 62.5% |
| Good | 3 | 37.5% |

**Problems experienced**

| Problem | Respondents selecting it | Percentage of respondents |
|---|---:|---:|
| Unstable electricity | 7 | 87.5% |
| Poor internet | 6 | 75% |
| Poor water supply | 4 | 50% |
| Blocked toilets or drainage | 2 | 25% |
| Damaged furniture | 2 | 25% |
| Faulty fans | 1 | 12.5% |
| Others | 2 | 25% |

**Frequency of experiencing the selected problems**

| Frequency | Responses | Percentage |
|---|---:|---:|
| Occasionally | 4 | 50% |
| Daily | 2 | 25% |
| Weekly | 2 | 25% |

**Cleanliness satisfaction score**

| Recorded score | Responses | Percentage |
|---|---:|---:|
| 2 | 3 | 37.5% |
| 4 | 5 | 62.5% |

**Frequency of electrical appliance faults**

| Frequency | Responses | Percentage |
|---|---:|---:|
| Occasionally | 6 | 75% |
| Daily | 1 | 12.5% |
| Weekly | 1 | 12.5% |

**Initial interpretation:** Unstable electricity was the most frequently selected problem (7 of 8 respondents), followed by poor internet (6 of 8) and poor water supply (4 of 8). Five respondents rated the general condition of their hostel as Fair, while three rated it Good. These findings identify facility concerns among this small group. The survey except does not establish how students report faults, how quickly staff respond, or whether a report-tracking system is currently used; those questions require follow-up research.

**Survey source:** Babcock University Hostel Survey (Google Forms)[https://docs.google.com/forms/d/e/1FAIpQLSdw-PT-Yu7HwBwSMmQ-mhTqXlNX7YdZkTcwdRBGe1Xu5WrUSA/viewform?usp=publish-editor]

### 6.2 Evidence Summary

Based on the 8 supplied survey responses:

- Most frequently selected issue: **Unstable electricity** (7 responses; 87.5%).
- Second most frequently selected issue: **Poor internet** (6 respones; 75%).
- Other prominent issue: **Poor water supply** (4 responses; 50%).
- Hall that these problems occur in: **Neal Wilson** (4 responses; 50%)
- General hostel condition: **5 responses (62.5%) selected Fair** and 3 (37.5%) selected Good.
- Most common reported frequency of experiencing the selected problems: **Occasionally** (4 responses; 50%).
- Most common answer for how often electrical appliances get bad: **Occasionally** (6 responses; 75%).
- Main current reporting channels: **Google Forms**

### 6.3 Research Limitations

The analysis is based on only 8 responses, most of which came from 200 Level students (7 of 8). The sample may or may not represent the experience of all hostel residents for all academic levels. A facility-problem selection does not establish how long repairs took, or whether a report-tracking system is missing. Follow-up research will be done.

## 7. Target users and stakeholders

### Primary Users

**Hostel students**
- Notice and report maintenance issues.
- View the status of their own reports.

### Operational users

**Hostel or maintenance personnel**
- View submitted reports.
- Review the information provided.
- Update a report's status.
- Mark a request as resolved when work is complete.

**System administrator**
- Manage authorised staff accounts and basic system settings.
- Maintain access permissions.
- Review system activity where appropriate.

### Other stakeholders

- Hostel management.
- University facilities or maintenance department.
- Student representatives.
- Our team.

## 8. User Needs

| User | Need | Reason |
|---|---|---|
| Student | Submit a maintenance report | To notify the team about a fault |
| Student | View report status | To know whether a request has been received or handled |
| Maintenance staff | See reports in one queue | To review requests in an organised way |
| Maintenance staff | Update report status | To communicate progress |
| Administrator | Manage authorised accounts | To help protect the system and its records |

## 9. Identified Gaps and Opportunities

The following are the identfied gaps and opportunities confirmed by the research conducted by our team

- Reports may be spread across different communication channels.
- Students may have not be able to see the progress of their report
- Staff may need a shared list to organise and prioritise requests.
- Management may benefit from a record of recurring faults.

## 10. Proposed Solution

Our team plans to build a web application that allows students to submit hostel maintenance reports weekly and check their status. An authorised staff dashboard will also allow maintenance and administrative personnel to review reports and record progress.

The proposed system will provide:
- a student-facing report submission page;
- a unique reference number for each accepted report;
- a page showing the signed-in student's own reports;
- a place where pictures can be attached to show the pending issues
- a staff dashboard for viewing and managing reports;
- status updates and notes;
- basic categorisation and prioritisation;
- access control for student, staff, and administrator roles.

## 11. Product Goals

The following are the goals my team and I plan to fufill with the creation of our product;

1. Make maintenance reporting straightforward for hostel residents.
2. Give each submitted report a unique reference.
3. Make report status visible to the student who submitted it.
4. Give authorised personnel a structured way to review and update requests.
5. Keep a basic history of report status changes.
6. Produce a usable prototype that can be tested by residents of the school.

## 12. Non Product Goals

Our version of this product will not be responsible for the following:

- replace the university's official maintenance department or approval process;
- guarantee that physical repairs will be completed by a particular time;
- process payments or maintenance budgets;
- monitor hostel facilities using sensors;
- provide emergency response services;
- expose one student's private reports to other students;
- automatically deciding whether a complaint is genuine or not.

## 13. Minimum Viable Product (MVP)

For our first version, we want to build a system that helps students report problems in their hostels and check what is happening with the reports they submit. We are keeping the first version simple so that we can focus on the main features and make sure they work properly.

Our survey had 8 responses. Unstable electricity was selected by 7 students (87.5%), poor internet by 6 students (75%), and poor water supply by 4 students (50%). These results helped us identify the types of problems the system should allow students to report. The survey did not ask how students currently report these problems, so we still need to confirm that part through follow-up research.

### 13.1 Student side

Students should be able to:
- Create an account and log in.
- Report a problem they are having in their hostel.
- Choose the type of problem, such as electricity, water supply, blocked toilets or drainage, faulty fans, damaged furniture, or another issue.
- Select or enter their hostel and give the location of the problem.
- Explain what happened in a short description.
- Add a picture if the team is able to include image uploads safely.
- Submit the report and receive a report ID.
- See the reports they have submitted.
- Check the latest status of each report.

### 13.2 Staff side

Authorised maintenance or hostel staff should be able to:
- Log in to a staff account.
- See the reports submitted by students.
- Open a report to check its category, hostel/location, description, and date submitted.
- Change the report status when action is taken.
- Add a short update so there is a record of what has happened.
- Mark a report as resolved when the issue has been addressed.

### 13.3 Report status

The first version will use these statuses:

| Status | What it means |
|---|---|
| Submitted | The report has been sent successfully. |
| Under Review | Staff have opened or are checking the report. |
| In Progress | Someone is working on the issue or following it up. |
| Resolved | The issue has been marked as addressed. |
| Needs More Information | Staff need the student to provide more details. |

If a report needs more information, staff should add a reason so the student knows what is missing.

### 13.4 What we are focusing on first

The main things we need to get working are:
1. Student registration and login.
2. Submitting a hostel maintenance report.
3. Generating a unique report ID.
4. Saving the report so it can be viewed later.
5. A staff dashboard where reports can be viewed.
6. Updating the report status.
7. Allowing students to check the status of their own reports.

These are the main MVP features because they cover the basic process from reporting a problem to seeing its progress. Image uploads, notifications, charts, and advanced filtering can be added later if there is enough time.

### 13.5 Features we are not including in the first version

To avoid making the project too big, the first version will not include:
- Online payments.
- Automatic repair scheduling.
- Live Sensors.
- AI fault detection.
- Automatic notifications by SMS or email.
- Complex analytics and reports.
- Direct connection to the university's official systems.

These can be considered for a later version if the basic system is completed successfully.

### 13.6 How we will know the MVP works

We will test the system using sample student and staff accounts. The MVP should be able to pass these basic checks:
- A student can log in and submit a report with the required details.
- The system creates a unique report ID for the submission.
- The report is saved and appears in the student's report list.
- A student cannot view another student's private reports.
- An authorised staff account can view the submitted report and update its status.
- The student can see the new status after the staff update.
- An ordinary student account cannot open the staff dashboard.

### 13.7 Division of tasks between our members

| Team member | Responsibilities |
|---|---|
| Ukpebor Elliot | Works on the report submission feature, including the report form and saving report details. |
| Onileowo David | Works on the database structure and the report data, including unique report IDs and status history. |
| Ubani Michael | Works on authentication and access control for student and staff accounts. |
| Wabara Michael | Coordinates the student report-viewing and staff dashboard features, help connect the parts, and check that the full reporting workflow works. |

## 14. Functional Requirements

| ID | Requirement | Priority |
|---|---|---|
| FR-01 | The system shall allow a student to create an account or sign in using the prototype's approved authentication method. | Must have |
| FR-02 | The system shall allow a signed-in student to submit a maintenance report. | Must have |
| FR-03 | A report shall contain a category, hall of residence and a description. | Must have |
| FR-04 | The system shall generate a unique reference for each successfully submitted report. | Must have |
| FR-05 | A student shall be able to view only their own submitted reports. | Must have |
| FR-06 | A student shall be able to view the current status of each of their reports. | Must have |
| FR-07 | An authorised staff member shall be able to view reports submitted by students. | Must have |
| FR-08 | An authorised staff member shall be able to update a report's status. | Must have |
| FR-09 | The system shall record the date and time of report creation and status updates. | Must have |
| FR-10 | Staff shall be able to add a progress or resolution note. | Should have |
| FR-11 | Students shall be able to attach an image to a report if secure file upload is included in the prototype. | Could have |
| FR-12 | Staff shall be able to filter reports by status and category. | Should have |
| FR-13 | Administrators shall be able to manage staff accounts and roles. | Should have |
| FR-14 | The system shall validate required fields and show understandable error messages. | Must have |

## 15. Non-Functional Requirements

- **Usability:** Forms and status labels should be clear to a student with basic web-app experience.
- **Security:** Passwords must not be stored as plain text. Access to staff functions must require an authorised staff role.
- **Privacy:** Students must not be able to view another student's private report details.
- **Reliability:** The system should provide a clear success or failure message when a report is submitted.
- **Data integrity:** Each report must have an ID and valid time of creation.
- **Performance:** Common pages should load within a reasonable time.
- **Compatibility:** The interface should work on desktops and mobile browsers.
- **Maintainability:** The code should be organised into understandable code and it should be documented sufficiently
- **Accessibility:** Forms should have labels, it should be readable and it should be i full co-operation with the keyboard.

## 16. User Stories and Acceptance Criteria

### Story 1: Submit a report

As a hostel resident, I want to submit a maintenance issue, so that the maintenance personnel can review it.

**Acceptance criteria:**
- Required fields are clearly identified.
- The system rejects a submission when required information is missing.
- A valid submission is saved.
- The student sees a confirmation and unique reference number.

### Story 2: Track my report

As a hostel resident, I want to see the status of my report, so that I can understand its progress.

**Acceptance criteria:**
- The student must be signed in.
- The page displays only reports belonging to that student.
- Each report displays its reference, category, submission date, and current status.
- The student can open a report to view its latest update.

### Story 3: Manage incoming reports

As an authorised maintenance staff member, I want to review submitted reports, so that I can organise follow-up work.

**Acceptance criteria:**
- Only an authorised staff account can access the staff dashboard.
- The dashboard displays report summaries.
- Staff can open a report and view its submitted details.
- Staff can update its status and add a note.
- The system records who made the update and when.

### Story 4: Manage staff access

As a system administrator, I want to manage staff accounts, so that only approved personnel can use staff functions.

**Acceptance criteria:**
- Only an administrator can access account-management functions.
- Staff roles can be assigned or disabled.
- A disabled account cannot access protected staff pages.

## 17. Proposed User Workflow

1. Student signs in.
2. Student opens the "Report an Issue" page.
3. Student selects a maintenance category and enters the hostel details and description.
4. Student optionally attaches a relevant image if uploads are supported.
5. Student submits the form.
6. System validates and saves the report.
7. System displays a unique report reference.
8. Student can view the report in "My Reports"
9. Authorised staff review the report in the staff dashboard.
10. Staff update the status and add a note as work progresses.
11. Student sees the latest status when viewing the report.
12. Staff mark the report resolved and add a resolution note.

## 18. Success Metrics

Our team will use the following measures during prototype testing. These are proposed targets, not measured results.

| Metric | How it will be measured | Prototype target |
|---|---|---|
| Report submission success | Valid test submissions saved successfully | At least 9 out of 10 |
| Report reference generation | Successful submissions with a unique reference | 95% |
| Student status visibility | Test users able to find a report's status | At least 4 out of 5 test users |
| Role protection | Unauthorised test account blocked from staff pages | 95% of access tests |
| Task completion | Test users able to submit a report without assistance | At least 4 out of 5 test users |

## 19. Risks and Mitigations

| Risk | Potential effect | Mitigation |
|---|---|---|
| Survey responses are not representative | Our team may misunderstand the wider student experience | State the sample size and limitations; seek varied participants |
| Research does not confirm the assumed reporting problems | Proposed features may not solve the main problem | Validate the current process before finalising scope |
| Unauthorised access | Private student information may be exposed | Use authentication, role checks, and ownership checks |
| Staff do not use the prototype | Reports may not receive updates | Test the staff workflow and clarify that the prototype requires an authorised user |
| Poor internet access | Users may struggle to access the system | Keep pages light and test on mobile connections |
| Photo uploads introduce security or storage issues | Unsafe files or excessive storage use | Make uploads optional; validate file types and size, or don't allow uploads |
| Project scope becomes too large | Our team may not finish the MVP | Prioritise the Must-have requirements |

## 20. Dependencies and Assumptions

### Dependencies
- A working development environment and source-code repository.
- A database for storing users, reports, and status history.
- An authentication mechanism.
- A hosting or local demonstration environment.
- Permission to conduct any testing involving university staff or official processes.

### Assumptions to validate
- Students have access to a phone or computer capable of using a web application.
- A staff role can be represented in the prototype.
- The selected report categories reflect issues students actually experience.
- The university's actual complaint process and responsible office can be described accurately after research.

