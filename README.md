# shared-date-note
Notes can be added to individual calendar days together.

The idea started from the fact that family members want to take care of my grandmother, and it is necessary to enter in advance who will be good and when. A shared table could also be used for this, but it is not very transparent, especially in the phone view. Doodle would also be an option when who will take care of my mom, but with such a large family there would be too many lines and it would not be transparent.

## Web page

### GET /
Load the main page, you can create new shared group for date notes, or you can join a code.

### POST group/create
Create the group id and redirect to the `group/{id}/notes` page.

### GET group/{id}/notes
The page for the shared group with dates with its note.

### POST group/{id}/note/create
Post method for the html forms with the date and note.

## API (later)
### POST api/group/create
### GET api/group/{id}/notes
### POST api/group/{id}/note/create
