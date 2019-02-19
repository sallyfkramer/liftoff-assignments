# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
For the last 11 years I worked at the Nelson-Atkins Museum of Art. My team managed the largest department in the museum, the Security/Visitor Services department. One of my job duties was to write the schedule for 45+ job positions for each shift. It was a tedious task that often took several hours. Many aspects of it could be automated so that it could be done faster and more accurately. 
### Features

Feature 1:Create employee profiles. Each profile should contain the employee's name, which shifts the employee works, which positions they are trained to work and a designation for limited duty for injuries.
Feature 2: Rosters for everyone and rosters for each shift. The overall roster should list all current employees. The shift roster should display a table containing all employees that work a given shift. It should also have a list of each training area and the number of employees that have each.
Feature 3: Position list. There needs to be a list of all positions needed when the museum is open. There needs to be a feature for adding/subtracting and editing an existing position. Each position will have a name and what training is required to work it. Additionally, each post needs a ranking so that if a shift is understaffed the program knows which post to leave empty.
Feature 4: Training page. This page should show a week calendar of all of the shifts with the number of positions needed with each training and the number of employees that possess each training. It also should have a feature to add or subtract training types.
Feature 5: Calendar. Each shift should have a link to that day's scheduled. When a schedule is first accessed, the program should prompt a review of the roster to add/subtract names of employees who asked off or are covering shifts. The schedule should be generated randomly by filling the more specialized positions first and then filling in with the more general positions last. It should be possible to override the random assignments and save changes.

### Technologies
This will be accomplished using Java, Spring Boot, SQL and HTML.

### What I'll Have to Learn
The database for the positions, schedules, trainings, and employees is going to be a more involved and complex version of the last project in the Launch Code Java. Figuring out how to create randomly generated schedules and allow for editing will be the hard part. Additionaly, the strech goal would be to set it up to prioritize scheduling each employee for a post that they hadn't worked for their last 2 shifts.
