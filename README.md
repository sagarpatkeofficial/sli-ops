## Project Title: StackOps
### Objective:
Project to centralize Academic Reporting and tracking of academic Interventions.

### Scope:
#### Monitor Academic Activities
Project will monitor academic activities of Instructors, Teaching Assistants, Students, Student Services, and Academic Data Entry staff.

#### Solve the problem of Time Travel
Tracking student's journey through the learning path is seldom done through aggregated reporting. Aggregated reports typically display the current state, or display the state of whenever it was last updated. However, it does not capture enough information about the journey. For instance, when looking at the final Academic Progress report for a class, we are unable to identify students who had a slow start, but later were able to catch up quickly to analyze interventions taken and opportunities lost. The information of student progress was lost when the aggrated report was updated.

This problem can be solved by shifting the perspective from persistent reports, to persistent Activities, and focusing on capturing all activities performed as part of the process. Not only does this help in keeping track of all operational activities, it also enables us to generate reports that are snapshots in time. For instance, it can allow us to generate the Class Progress report at 1/4, 2/4, 3/4 and final report, for analysis, by writing a reducer function and applying it on an events array. The same function can be used for creating a report at any snapshot in time, without additional code changes.

#### Generate progress-tracking report
Generate a report that enables us to track progress for all classes.

#### Perform academic data entry
Through file-drop method.

#### Injest real-time activities from distributed systems
Such as the Learning Platform, CompTIA, HubSpot, etc.

### Milestones:
#### Major Milestone
- [ ] Upload files to report Enrollments, Schedule, Attendance, Student Progress, Teaching Assistant Interventions, and Support Activities.
- [ ] Report that displays Students' current progress
#### 12-August:
- [ ] Upload files to report
    - [ ] Attendance
    - [ ] Student Progress
    - [ ] Support Activities
- [ ] Report that displays class-wise student progress
