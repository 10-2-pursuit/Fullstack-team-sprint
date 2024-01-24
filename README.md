# Fullstack-team-sprint

Create a Community Event Space Booking App client that interacts with a RESTful API using React.

## Technical Requirements

Create an Event Space Booking application where users can:

- View all event spaces
- Create an event space
- View space bookings

#### Booking Management:

- View all bookings
- Book an event space
- Cancel booking
- Find available spaces (optional extra challenge)

**Notes**:

- Feel free to use 3rd-party libraries or packages for functionality or styling. We recommend using Bootstrap, Material UI, or similar for app styling.

### Database

Create a database with 2 tables: EventSpace and Booking. The tables should have identity columns for the IDs and any necessary columns based on requirements and payloads below.

### API

Create a RESTful API service with the following endpoints that read and write to the database, accepting and returning JSON payloads.

| Method   | Endpoint                     | Description                                                                                                                                | Example JSON Body Payload                                                                                                                                                                                                                                                                                                         |
| -------- | ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `GET`    | `/api/event-spaces`          | List all event spaces                                                                                                                      | n/a                                                                                                                                                                                                                                                                                                                                |
| `POST`   | `/api/event-spaces`          | Create an event space<br><em>All fields are required</em>                                                                                  | { <br>&nbsp;&nbsp;&nbsp;&nbsp;"name": "Art Workshop Space",<br>&nbsp;&nbsp;&nbsp;&nbsp;"capacity": 20,<br>&nbsp;&nbsp;&nbsp;&nbsp;"location": "Downtown"<br>}                                                                                                                                                                      |
| `GET`    | `/api/event-spaces/:id`      | Retrieve an event space by id                                                                                                              | n/a                                                                                                                                                                                                                                                                                                                                |
| `GET`    | `/api/event-spaces/:id/bookings` | Retrieve all **future** bookings of an event space                                                                                          | n/a                                                                                                                                                                                                                                                                                                                                |
| ...      | *(similar to original)*     | *(similar functionality as original, adjusted for event spaces)*                                                                            | *(similar to original, adjusted for event spaces)*                                                                                                                                                                                                                                                                                 |

### Wireframes

Your application should follow the provided [wireframes](/assets/wireframes)

### App Pages/Views

Adapt the pages/views for the Event Space Booking context, similar to the original assignment but with relevant changes to terminology and functionality.

## Submission Guidelines

- Aim to complete the challenge in about 7 hours.
- Submit your solution by **[specified deadline]**.
- Include a README.md with instructions on how to run your project.
- Submit your code compressed in a zip file using the provided submission form.
  - Remember to exclude the `node_modules/` folder before compressing.
- For questions, reach out to [designated contact person or platform].
