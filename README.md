this repository is for centralized repository for the following microservices:

1. post-service (post-service.yml)--> post related functionality
2. content-service(content-service.yml( --> will call post -service using webclient
3. service-registry-in-eureka(service-registry-in-eureka.yml)  -> to register post-service, content-service and post-api-gateway-service
4.post-api-gateway-service(post-api-gateway-service.yml) --> this is for api gateway
   so convert int git based centralized configuration with details
