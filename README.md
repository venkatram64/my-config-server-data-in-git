this repository is for centralized repository for the following microservices:
0. post-config-server(post-config-server.yml) is placed in my-config-server-data-in-git folder along with application.yml
remaining configurations are placed in config folder
1. post-service (post-service.yml)--> post related functionality
2. content-service(content-service.yml( --> will call post -service using webclient
3. service-registry-in-eureka(service-registry-in-eureka.yml)  -> to register post-service, content-service and post-api-gateway-service
4. post-api-gateway-service(post-api-gateway-service.yml) --> this is for api gateway
   so convert int git based centralized configuration with details
