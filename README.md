# FaceLite Social Network Application
 
## Overview
FaceLite is a simple JavaFX application designed to manage a basic social network. The application allows users to create, delete, and look up user profiles within the network. Each profile includes information such as the person's name, an optional profile image, a current status, and a list of friends.
 
## Project Description
A social network is a platform that connects individuals through user profiles and their friendship relationships. In the context of FaceLite, a profile represents an individual, and friendships are reciprocal relationships between profiles. For example, if Moath is friends with Saqar and Hasan, Saqar and Hasan are also considered friends with Moath.
 
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
No specific testing instructions are provided. The application's functionality can be manually tested by creating profiles, adding friends, updating status, and changing pictures.
 
## Author
[Your Name]
