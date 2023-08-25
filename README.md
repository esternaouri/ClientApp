Talent Network app
-------------------------------------------------------------------------------------------------------
 TalentNetwork is a web application. It is a social network for finding employees and suppliers
Each user could add information about himself and receive information about other users

Basic data, project data and FAQ can be added

You can manage your own profile and perform CRUD operations
In order to enter the general list of data, basic details must be entered.

If you use as an administrator - you can manage the users and reset their passwords

- FOR TESTING - USERNAME 1, PASWORD 1111
- FOR ADMING - USERNAME 11, PASWORD 1111

the backend application can be find here : https://github.com/esternaouri/TalentNetwork

demo video : https://clipchamp.com/watch/ZuTIbMmywa2

------------------------------------------------------------------------------------------------------------------------------------------------------------------

Installation
To run the application:

* Clone this repository to your local machine.
* Open a terminal in the project directory.
* Run npm install to install the project's dependencies:

 cd to src and than:
* npm install 
* npm install axios 
-----------------------------------------------------------------------------------------------------------
Usage

Ensure that the API is running. The API  documentation and code can be found in - 
the backend application  : https://github.com/esternaouri/TalentNetwork

To use the application, you will need to have a web browser on desktop or an Android or iOS device or an emulator.
-----------------------------------------------------------------------------------------------------------------------------------
**feature: 
**
* User Registration: - User must register himself by filling some personal details for testing can take random six ditits number has users Id.

* User Login: After registration user will enter ID number and password for logging in order to get access to the system, access token saved untill user logs out.

* Logout: if logged in, a click on logout will remove the token from storage & log out the user.

* Home Page: in this page you got all workers details  and proffesion posts. whene you click on one of the post you can get more details about it.

*  Search in worker by proffession or location : User can search/sort workers posts.

* manage user Page: in this page you has a user can manage your own post  by adding first deatails like adress, proffesion and edit/add /delete projects and FAQ'S.

* Massages: you can send watssup by clicking on whtssup icon for a worker that interest you.

* if you are admin:  you can mange users by password reset, delette or edit users.

* for testing admin: user Id - 11 , password - 1111.
* about - page that axplain the application purpose.
* 404 page not found in case thers not page .
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Code Features:
The app folder is divided into 3 main folders:

Core: modules, services, guards, interceptors.
Data: models, DTO's, enums.
Front: components, pipes, styles.
JWT Authentication, token is saved in storage.

Usage of BootStrap components & css.

JWT interceptor for cloning HTTP requests & adding the token.

Refresh token on startup/refresh.

Generic reusable components.

original custom made carrusel & stars components.

Reactive forms with custom regex validators.

Authorization: 2 user roles - [IsAdmin/ ! IsAdmin].
