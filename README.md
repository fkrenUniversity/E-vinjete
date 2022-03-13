# E-vinjete
This repository is used for digitalization for slovenian vignettes.

## Structure
Project is divided into 3 simple webservices and web application(UI). For webservices we will be using Python and framework FastAPI. For web application we will be using latest node.js and framework React.js
## Web services


### Vehicles
* User needs to provide basic vehicle information. Such as: **Vehicle type**, **Vehicle colour**, **VIN** and **Vehicle owner**. User can add multiple vehicles that he owns.
* Vehicle microservice will also return list of all vehicles owned by user.
* For each vehicle service will return date when Vignette has been purchased and Vignette expiration date. User will have at all time knowledge about Vignettes and expiration dates for different vehicles.

![Vehicle Diagram](https://github.com/fkrenUniversity/E-vinjete/blob/main/diagrams/Vehicle.png?raw=true)

### Vignette
* When user adds vehicle, he will be provided with vignette type for his vehicle, which he can choose from. Vignette types are: **Weekly**, **Monthly** and **Yearly**.
* Prices are dependend on vehicle and vignette type.
* Service will also return list of all vignette types and their prices and their availabillity.
* If user has changed his mind about purchasing vignette he will have some grace time before he can cancel it.

![Vignette Diagram](https://github.com/fkrenUniversity/E-vinjete/blob/main/diagrams/Vignette.png?raw=true)

## Non Functional requirements
* **User**
    * 1 email and tax number per user
    * Conformation mail has to be send in 5 minutes after user has been successfully registered
    * Functionallity needs to be locked after 3 unsuccessfully registration attempts. After that user needs to wait 10 minutes
* **Vehicle**
    * Service has to be executed in less than 100ms
    * Service needs to be protected
    * When there are multiple requests for this service, response time should be less than 3000ms
* **Vignette**
    * Service has to be executed in less than 100ms
    * Service needs to be protected
    * When there are multiple requests for this service, response time should be less than 3000ms  
