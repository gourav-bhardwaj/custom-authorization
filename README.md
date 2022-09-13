# custom-authorization-server


Authorization Server with OAuth2 Client and Resource server

- In CMD 'docker-compose -f docker-compose.yml up' (Make sure you have docker)
## Run authorization-server 
  - Mac: Open cmd and run './gradlew clean build'
  - Windows: Open cmd and run 'gradle.bat clean build'
  - In CMD now run 'java -jar build/libs/authorization-server-0.0.1-SNAPSHOT.jar'
## Run sp-govtech-api-gateway
  - Mac: Open cmd and run './gradlew clean build'
  - Windows: Open cmd and run 'gradle.bat clean build'
  - In CMD now run 'java -jar build/libs/sp-govtech-api-gateway-0.0.1-SNAPSHOT.jar'
## Run product-resource-server
  - Mac: Open cmd and run './gradlew clean build'
  - Windows: Open cmd and run 'gradle.bat clean build'
  - In CMD now run 'java -jar build/libs/product-resource-server-0.0.1-SNAPSHOT.jar'

## Now on browser hit "http://localhost:8787/product/users/status"
- Login with username: user and password: pass
