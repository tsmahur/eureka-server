# eureka-server
  This ms is to setup eureka server and [user-ms2](https://github.com/tsmahur/user-ms2), ms [address-ms2](https://github.com/tsmahur/address-ms1) are registered with erueka by addign eureka client config in respective ms. This is a part of [ms-eureka-gateway-hysrtix-cloud-config](https://github.com/tsmahur/ms-eureka-gateway-hysrtix-cloud-config) Project.
  In case of large no of MS it is difficult to maintain the ports information. So, need to create eureka-server service registry and all ms will be connected to this.
##
### Dependency
    erueka server

### application.yml
    port, eureka client config(to register-with-eureka:false-> not to self register)

### main application class
    @EnableEurekaServer

### EndPoints
    http://localhost:8761/ (default port 8761)
