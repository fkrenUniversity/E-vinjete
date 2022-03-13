### User 
Because its is government application, we will need user identification.
* For user identification we will use Slovenian **tax number**,**email** or **phone number** and **password**. 
* Service will provide with logs, when user has been logged in and from which computer.

![User Diagram](https://github.com/fkrenUniversity/E-vinjete/blob/main/diagrams/User.png?raw=true)

## Non Functional requirements
* **User**
    * 1 email and tax number per user
    * Conformation mail has to be send in 5 minutes after user has been successfully registered
    * Functionallity needs to be locked after 3 unsuccessfully registration attempts. After that user needs to wait 10 minutes
