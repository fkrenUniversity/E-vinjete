# E-vinjete
This repository is used for digitalization for slovenian vignettes.

## Structure
Project is divided into 3 simple webservices and web application(UI). For webservices we will be using Python and framework FastAPI. For web application we will be using latest node.js and framework React.js
## Web services




### Vignette
* When user adds vehicle, he will be provided with vignette type for his vehicle, which he can choose from. Vignette types are: **Weekly**, **Monthly** and **Yearly**.
* Prices are dependend on vehicle and vignette type.
* Service will also return list of all vignette types and their prices and their availabillity.
* If user has changed his mind about purchasing vignette he will have some grace time before he can cancel it.

![Vignette Diagram](https://github.com/fkrenUniversity/E-vinjete/blob/main/diagrams/Vignette.png?raw=true)



* **Vignette**
    * Service has to be executed in less than 100ms
    * Service needs to be protected
    * When there are multiple requests for this service, response time should be less than 3000ms  
