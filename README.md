# Tech Jobs

This is an assignment for LaunchCode's LC101 Bootcamp, for which I was a Teaching Assistant for the Summer-Fall Kansas City Cohort. In order to assure that I could properly assist students with this assignment, I completed the assignment myself and I am currently working on adding other features to test my own understanding of the ASP .Net framework and the C# language.

## Tech Stack
- MySQL
- C#
- ASP .Net
- Razor Views

#### Other Tools Used:
- Bootstrap
- EntityFrameworkCore

## Functionality

This web app is designed to allow users to add, view, and search for tech jobs. Job listings include the name of the position, the employer, and the skills required. Employer listings include the employer's name and location. Skills are all attached to a description of the skill.

### The Home/Index View

The *Home* view gives the user three options: they can add a job, list jobs, or search for jobs. There is also a table that is populated with all jobs that exist in the database, as well as their respective employers. The job names in this table serve as links that connect to a *Job Detail* view for the selected job.

### The Add Job Form View

When a user follows the *Add Job* link, they will see a form with a text field for the name, a select menu for the employer, and checkboxes for skills. If a user does not see the employer for the job they would like to add, the can follow the *Add Employer* link to the *Add Employer* view. The same is true for skills. If the employer and skills required are present, the user enters the name and submits.

### The Add Employer and Add Skills Form Views

The forms for adding an employer and adding a skill are relatively straightt-forward, with simple text fieds and submit buttons.

### The Search View

If a user would like to search the database for a job, they can do so from the *Search* view. Here, they can search by employer, skill, or by all. If the user selects 'all' then any keywork matches in the job detail view will return a hit for that job. Otherwise, the search will execute on the employer and skill tables only.

### The List Jobs View

The *List Jobs* view shows two lists: one list of employers and one list of skills, all presented as links. Following these links will show a ttable oof joobs that are attached to that specific skill or employer.
