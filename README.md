# Dockerized-OpenApiGenerated
A guide and the resources to generate and run an API from an OpenApi spec yaml file 

NOTE: A lightweight simple bank app was used to reduce build time. 

1. clone repository into directory of choice
2. In DOS CMD run the `docker-compose build` command
3. the build will take around 3 - 4 minutes so go make yourself a coffee, you deserve it.
4. once the build is complete run `docker-compose up` 
5. to test the depolyment of the application in your search engine of choice search `localhost:80` this should direct you to the swagger ui of the mimacom Banking API.

TESTING 
- To test the creation of the API use POSTMAN.
1. Import the postman collection fond in this repository into your desktop version of POSTMAN.
2. run the `Get Accounts` rrequest.
3. teh output should be a JSON object with an array called test within it, this array should contain 2 instances of the string iban. 

