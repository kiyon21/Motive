# Motive
Motive is a mobile app that connects people looking to play team sports with people hosting said sporting events. This application allows users to host their events and let people nearby be informed of what sports are being played, the specific participant details about the person, and any additional items required to participate. There were a multitude of features implemented to do this. Some of the initial ones planned were not implemented, as well as new features that were initially unplanned being added to improve the user experience.
## Core Features
### Account Management
- Users are able to create and maintain an account using the firebase authentication API
- Metadata about users and games are stored and associated with users to allow them to maintain the data needed to run the app in a secure manner
### Event Creation (Hosting)
- Users are able to create an event record via a form, and this event shows up on the system map at the selected location, viewable by all users
- Events can be edited after creation, such that the host can make changes as needed
- The host can view the users that have joined their event
### Joining Events
- Users can join events, which they can select via the map view as well as via filters on certain criteria
- Once a user has selected an event and joined it, the host will see that a new user has joined their game

## Additional Features
### Notifications:
- Users are notified when someone joins the game they are hosting
### Time:
- Events are regulated by a time component, such that no two events are scheduled at the same time
### Editing events:
- Allows hosts to change events after they are created
