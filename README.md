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
# Community Event Space Booking App Pages and Views

## 1. Index Page for Event Spaces
- Lists all available event spaces.
- Includes details like space name, capacity, location, and a thumbnail image.
- Clickable event spaces navigate to their specific show page.

## 2. Index Page for Bookings
- Displays a list of all existing bookings.
- Shows details such as event name, booked space, date, time, and attendees.
- Each booking links to a detailed show page.

## 3. Form Page for Creating a New Event Space
- A form to add a new event space, typically for administrators or managers.
- Fields include space name, capacity, location, and image upload options.
- New spaces are added to the Index Page for Event Spaces upon submission.

## 4. Show Page for Each Event Space
- Provides detailed information about a specific event space.
- Details include name, capacity, location, images, and a description.
- May show availability and include a booking form.

## 5. Show Page for Each Individual Booking
- Detailed view of a specific booking.
- Displays information like the event name, date and time, space used, and attendees.
- Option for modifying or confirming bookings can be considered.

## 6. Booking Form (on Event Space Show Page)
- A form to book an event space.
- Fields for event name, date and time, number of attendees, and special requirements.
- Bookings are added to the Index Page for Bookings and linked to the event space.

**Note:** Each page should have consistent navigation for ease of use. Responsive design for various devices is recommended for an enhanced user experience.

## Fullstack Sprint Teams

1. Keith 	Camacho
   Davon	Bridgett
   Jalal	Jonaid

2. Michael 	Caldwell
   Dwayne	Jones
   Joseph 	Carter
   Nicole 	Slater
   
4. Anthony 	Huarneck
   Michael 	Kleemoff
   Aisha 	Kleemoff
   
   Alexander	Tsiklidis
5. Shanice	Griffin
   Sung	Yi
   Gen	Lara
   Tonesha	Rose
   
6. Erick 	Tolentino
  Joram 	Mercado
  Elisaul	Bautista

