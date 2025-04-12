## service dicovery
https://medium.com/@ksaquib/mastering-spring-boot-service-discovery-and-registration-using-spring-cloud-netflix-eureka-a-1eec70317b32

## API gateway
make it as eureka client to fetch detauils of all running service
<img width="455" alt="image" src="https://github.com/user-attachments/assets/cda02041-2e2c-4dcf-9835-22b136e14edd" />

avoid haqrdcoding of URL and send it in loadbalanced way
<img width="559" alt="image" src="https://github.com/user-attachments/assets/0330fa30-3e71-4f27-91d6-0323bb37058f" />
we can also rewrirtepath
   filters:
            - RewritePath=/v1/management/api/accounts/(?<segment>.*), /v1/accounts/$\{segment}

