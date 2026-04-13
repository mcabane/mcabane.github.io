[Back to Portfolio](./)

Stay on Track Web Application
===============

-   **Class: CSCI 498, 499** 
-   **Grade: In Progress** 
-   **Language(s): Ruby, Javascript, HTML/CSS** 
-   **Source Code Repository:** [features/mastering-markdown](https://guides.github.com/features/mastering-markdown/)  
    (Please [email me](mailto:example@csustudent.net?subject=GitHub%20Access) to request access.)

## Statement of Purpose

When it comes to productivity and task trackers they are usually designed for students and are not suited to keeping track of life related tasks that do not occur frequently. When a person is busy with responsibilities it can be difficult to keep track of appointments, deadlines, maintenance, and other non-regular day-to-day chores.

If important dates are not kept track of, it can leave people rushing to complete important tasks like filing taxes to the last minute. If consistent appointments are not maintained it could result in a decline in health or health conditions going undiscovered and untreated. If maintenance of appliances or vehicles is left neglected; it could result in serious damage. For example, if a dryer vent is left blocked; it could result in a house fire.

A solution to maintaining an organized list of non-frequent and important life-related tasks is the Stay on Track web application. Users will be able to set recurring reminders of appointments, maintenance, deadlines, expiration dates of licenses/tags, and other non-frequent tasks.

## Research & Background
Research begin with researching types of appointments and maintenance that often get forgotten. Completion of User-Interfacing Programming course. Followed by learning more about Ruby on Rails, Fly.io for deployment, and turning illustrations into SVG files.

## Project Language(s)
- Ruby on Rails
- Javascript
- HTML/CSS
 
## Additional Software & Hardware
- Visual Studio Code
- Adobe Illustrator
- Windows Personal Computer

## Project Requirements
**ID Number:** 1  
**Type:** Functional  
**Description:**  
Users are able to create a task with a title, description, date, and recurrence
frequency (monthly, 6 months, year, or custom).  
**Rationale:**  
To create an efficient way for the user to manage recurring tasks and important
deadlines.    
**Fit Criterion:**    
The user is able to fill out the task details by typing into text fields, the
recurrence frequency is selected by dropdown. The task when created will be
added to the list with the correct title, description, date, and frequency.
Recurring dates must be automatically created with the specific interval.  
**Priority:** High  
**Dependencies:** ID 10

---

**ID Number:** 2    
**Type:** Functional    
**Description:**    
Users are able to delete or edit existing tasks to modify details without having
to create a new one.  
**Rationale:**    
Keeps the task management updated to the users needs and prevents cluttering the
dashboard with tasks that are no longer needed.  
**Fit Criterion:**    
When editing the user will save the changes by clicking the save button. If
user is deleting task, a warning message will appear to confirm deletion and
show how many instances of that task will be deleted. Tasks will reflect the
modified edits and have the correct information. Deleted tasks are no longer
displayed.  
**Priority:** High    
**Dependencies:** ID 1

---

**ID Number:** 3    
**Type:** Useability    
**Description:**    
Users can select from default categories or create new categories for tasks and
events.  
**Rationale:**    
Categories will aid with organizing by allowing the user to group tasks and
events by type, such as appliance maintenance, car maintenance, or
documents/licenses management.  
**Fit Criterion:**    
When creating a task the user can choose the category it falls under or add a
category to an existing task. The category is added by the user selecting the
from the dropdown menu.  </br>
**Priority:** High </br>
**Dependencies:** ID 1, ID 2

---

**ID Number:** 4    
**Type:** Functional    
**Description:**    
Allow users to mark tasks with levels of urgency.  
**Rationale:**    
This will help prioritize tasks based on the level of urgency.  
**Fit Criterion:**    
The urgency status will be visually represented by color and text, which the user can select the level from a dropdown.  
**Priority:** Medium    
**Dependencies:** ID 1, ID 2

---

**ID Number:** 5    
**Type:** Functional    
**Description:**    
Allow users to mark whether deadlines are concrete or flexible.  
**Rationale:**    
With deadlines differentiated between flexible and concrete will help with
prioritization. Flexible deadlines could be postponed and concrete deadlines
are given more priority.  
**Fit Criterion:**    
Concrete deadlines will have the task’s date locked with flexible deadlines
still editable. For concrete deadlines they can only be changed if the concrete
status is changed.  
**Priority:** Medium    
**Dependencies:** ID 1, ID 2

---

**ID Number:** 6    
**Type:** Functional    
**Description:**    
Determines the priority of the tasks/events based on level of urgency and
deadline status.  
**Rationale:**    
Helps identify the tasks with the highest importance by taking into account
urgency and deadline constraints.  
**Fit Criterion:**    
Tasks with high urgency and concrete deadlines are assigned the highest priority
with tasks of low urgency and flexible deadlines assigned lower priority.    
**Priority:** High    
**Dependencies:** ID 1, ID 3, ID 4, ID 5

---

**ID Number:** 7    
**Type:** Look and Feel    
**Description:**    
Users can view the tasks on a dashboard where it displays overdue, upcoming, and completed
tasks.  
**Rationale:**    
Being able to see the tasks in one place allows the user to visually see the
tasks that require immediate attention.  
**Fit Criterion:**    
The tasks are displayed correctly based on priority and organized by category. The
tasks will be displayed in a consistent format of the same width sizing. The
display of the tasks will be in columns and rows.    
**Priority:** High    
**Dependencies:** ID 1, ID 3, ID 6

---

**ID Number:** 8    
**Type:** Functional    
**Description:**    
Allow users to mark tasks as complete.  
**Rationale:**    
Once a task is complete it no longer has to be in the list of tasks that need to
be completed and recurring tasks would not need to be deleted.  
**Fit Criterion:**    
The completed tasks are moved to a different section and will have a completed
date added for that instance of recurring tasks.  
**Priority:** Medium    
**Dependencies:** ID 1, ID 2, ID 3

---

**ID Number:** 9    
**Type:** Look and Feel    
**Description:**    
Visual representation of the task progress of categories using counters.
**Rationale:**    
Provides a visual representation of the user’s progress and to summarize if
certain categories are being neglected.  
**Fit Criterion:**    
The counters will display the number of tasks in the sections: overdue, upcoming, and completed. 
**Priority:** Medium    
**Dependencies:** ID 1, ID 2, ID 7

---

**ID Number:** 10    
**Type:** Functional    
**Description:**    
Enable recurring scheduling of tasks.  
**Rationale:**    
Makes it convenient to the user to schedule recurring tasks that have the same
details without having to repeatedly create the same tasks that occur after a
specific time frame.  
**Fit Criterion:**    
Users can set the time interval of the time between the repeating task within
the range of days to year. The user can make the selection by selecting from
dropdown. The user will have a custom option, which will notify where the user
can input a number value for the chosen time unit between recurring tasks.    
**Priority:** Medium    
**Dependencies:** ID 1, ID 2

---

**ID Number:** 11  
**Type:** Convenience  
**Description:**  
In the task dashboard, display a countdown of the days remaining for the tasks
using the deadline and current date.  
**Rationale:**  
Displaying the number of days would help the user gauge the time remaining
rather than looking at a date.  
**Fit Criterion:**  
Displays the correct number of days between the current date and the task
deadline.  
**Priority:** Low  
**Dependencies:** ID 7

---

**ID Number:** 12  
**Type:** Personalization and Internationalization  
**Description:**  
Users will be able to select a color theme. 
**Rationale:**  
Allows for the interface to match the user’s preference.  
**Fit Criterion:**  
The user will be able to change between default and dark mode using the button. The theme should apply with correct colors and maintain readability. 
**Priority:** Low  
**Dependencies:** ID 3, ID 7

## Project Implementation Description & Explanation

![screenshot](images/Landing-Page.png)  
Fig 1. The landing page
The landing page is only shown to users that are not logged in.  

<br />
<br />

![screenshot](images/Sign-Up-Page.png)  
Fig 2. Sign Up Page
To create an account users will be prompted to enter name, email, and password. 

<br />
<br />

![screenshot](images/Sign-Up-Page-Validation.png)  
Fig 3. Feedback when an error occurs during sign up. 
The validation checks for any blank input field, email matches valid regex format, and that password is more than 6 characters.

<br />
<br />

![screenshot](images/Login-Page.png)  
Fig 4. Login Page.
The login page will prompt user for email and password. 

<br />
<br />

![screenshot](images/Dashboard-No-Tasks.png)  
Fig 5. Dashboard with no tasks.
When the account is successfully created the user will see the user dashboard. With no tasks created only the empty sections will be shown. 

<br />
<br />

![screenshot](images/User-Dashboard-Tasks.png)  
Fig 6. Example of Dashboard with tasks
When the user is logged in they will see all tasks they created in the user dashboard. 
The counter will be displayed at top with the sections displayed underneath. 

<br />
<br />

![screenshot](images/Task-Creation-Page.png)  
Fig 7. Task Creation Page

<br />
<br />

## Test Plan

User-Acceptance Test Strategy
The user acceptance testing was performed by having users test specific 
features by following steps. The steps were general to determine if the 
interface is intuitive. The users were observed as they performed the test. 
User surveys were used to receive feedback and gain measurable rating of 
specific qualities, such as ease of use. Feedback was utilized to identify 
usability issues, errors, and areas of improvement. A/B testing was used 
to help determine which layouts are more user-friendly.

User-Acceptance Test Purpose
The purpose of the user acceptance testing was to determine that the web 
application met the project requirements and identify errors that users may 
experience when using the application for real-world use. Following each 
testing cycle, users completed a survey to provide feedback on ease of use, 
visual design, and functional performance. The feedback was used to guide 
improvements and future enhancements.

User-Acceptance Test Objectives 
- Collect baseline feedback on ease of use, visual design, and functional 
performance.
- Refine web application based on user feedback and identified errors.
- Conduct follow-up surveys to gather comparative feedback after refinements and 
measure improvement.
- Perform final evaluation to confirm web application meets requirements and 
satisfies users based on ratings.

## Test Results

## Challenges Overcome

## Future Enhancements

## Defense Slides

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
