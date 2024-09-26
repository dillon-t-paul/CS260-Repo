# **Survey Center**
This application will serve as an opportunity for students and friends to get to know each other and to find those who share similar interests. In larger groups, it can be difficult for everyone to have ample time to share and learn about others and our hope is to fix that. Giving everyone tge opportunity to take time to share as much information as they would like and be introduced to others of similar interests.

## Specification Deliverable
### Elevator Pitch
Have you ever been in a crowded event where you didn't seem to know anyone? That awkward feeling of sitting around and waiting for someone to introduce themselves is one that we would all prefer to avoid. Through our application "Survey Center", our goal is to give everyone a voice. In a short couple of minutes, individuals can be introduced to others who share in interests, hobbies, and more. Connecting with others has never been made easier.
### Design
![Design-File](https://github.com/dillon-t-paul/Startup-2/blob/main/Survey-Design.png)
### Key Features
- Secure connection using https
- Get to know you survey(s)
- Ability to view other peoples entries
- Page pairing you with others who have similar interests
### Use of Technology
- **HTML** - Four total pages. Login Page, Survey Page, Page for students with similar responses, and a page for all responses and their statistics
- **CSS** - Application is styled to match window size, has a complimenting color scheme, and centers focus on group chat and TA tips
- **JavaScript** - Provides a checkbox survey that users can answer and save results. Will compare output with others and pair them with others with similar answers
- **Database** - Stores all users names and their answers paired with their login info. Must be logged in to participate
- **Web Services** - Retrieves users choices and logs their submissions (SaveScores)
- **Websocket Data** - As each user submits their surveys, the data is broadcast to all users
