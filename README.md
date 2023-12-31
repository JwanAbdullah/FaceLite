# FaceLite Social Network Application
 
## Overview
FaceLite is a straightforward JavaFX program made to administer a minimal social network. Users of the application can search for, add, and remove user profiles on the network. additionally, switch between the light and dark modes. A person's name, an optional profile picture, their current status, and a list of friends are all included in each profile.
 

## Project Description
A social network functions as a platform where individuals establish connections through user profiles and reciprocal friendships. In the context of FaceLite, a profile represents an individual, and friendships indicate mutual relationships between profiles. When two individuals are friends on FaceLite, it implies a mutual connection, creating a network of shared associations within the platform.
 
## Project Objectives
The primary objectives of the FaceLite project include:
- Creating and managing user profiles.
- Establishing reciprocal friendship relationships between profiles.
- Allowing users to set a profile picture, a current status, and manage their list of friends.
 
## Project Features
1. **Add Profile:** Users can create a new profile with a unique name.
2. **Delete Profile:** Users can remove an existing profile from the social network.
3. **Look-Up Profile:** Users can search for and view details of a specific profile.
4. **Update Status:** Users can change the current status associated with their profile.
5. **Update Profile Picture:** Users can add or change their profile picture.
6. **Add Friend:** Users can add friends to their profile, and the friendship is reciprocal.
7. **Light/Dark Mode:** users can switch between light and dark color schemes.
 
## How to Run
1. Clone the repository to your local machine.
2. Open the project in your Java IDE.
3. Run the `FaceLiteApplication` class to launch the application.
 
## Class Descriptions
 
### `FaceLiteApplication`
- Launches the FaceLite application.
 
### `Controllers`
- Manages UI behavior and connects user interface components with the `DataBase` class.
 
### `DataBase`
- Manages data operations, such as checking profile existence, adding new users, looking up user info, updating specific user details, and deleting users.
 
## Design Overview
The application follows a simple Model-View-Controller (MVC) design. `FaceLiteApplication` serves as the entry point, `Controllers` manages UI behavior, and `DataBase` handles data operations.
 
## Testing
The application's functionality can be manually tested by creating profiles, deleting profiles, looking up profiles, adding friends, updating status, and changing pictures.
 
## Author
Jana Alkahlan (202242700) & Jwan Alghamdi (202246560)
