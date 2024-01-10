# JSONVoorheesDb

## Project Outline
This is a proof of concept project.

The product owner wants to explore the possibility of having a MongoDB and cloud-based solution for accessing information about movies, allowing users to post or read comments on movies and managing a film schedule for cinemas.

A sample database (sample_mflix) is provided which includes details of movies, comments, "theaters" and users.

Two products are required: - A RESTful API which allows full CRUD access to the existing data for these 4 collections - A Web application providing a browser-based interface to the same set of existing collections

Additionally, a new feature is required to allow an administrator to create a schedule for a theatre, adding films to the roster and specifying showing times. No ticketing system is required at this point in the project. The cinema film scheduling feature should also be provided through both interfaces (REST & Web).

### Required Technologies
- The persistence mechanism must be MongoDB
- The database must be hosted on MongoDB Atlas using the "Shared" (free) tier hosted on AWS
- The database must be based on the sample_mflix database, which is provided for use within MongoDB - this tutorial explains how to install the sample
- Spring Boot must be used for the API and Web front ends
- Spring Data MongoDB must be used for accessing the database from both the API and the Web application
- The code repository for the project must be hosted on GitHub

#### Submission
By link to GitHub repo, by 18:00 on Friday.

### Project Presentations
Each group will give a 15 minute presentation on the outcome of the project to the Sparta Academy on Friday at **15:00 A further 15 minutes will be allowed immediately after each group's presentation to cover any questions from the audience.

### Updates
Updated 04/12/23 15:17
Try a local merge 15:25
Updated 04/12/23 15:38
