### Vehicles
* User needs to provide basic vehicle information. Such as: **Vehicle type**, **Vehicle colour**, **VIN** and **Vehicle owner**. User can add multiple vehicles that he owns.
* Vehicle microservice will also return list of all vehicles owned by user.
* For each vehicle service will return date when Vignette has been purchased and Vignette expiration date. User will have at all time knowledge about Vignettes and expiration dates for different vehicles.

![Vehicle Diagram](https://github.com/fkrenUniversity/E-vinjete/blob/main/diagrams/Vehicle.png?raw=true)
* **Vehicle**
    * Service has to be executed in less than 100ms
    * Service needs to be protected
    * When there are multiple requests for this service, response time should be less than 3000ms
