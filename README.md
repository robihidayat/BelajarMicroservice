# Microservice Learning 

    Microservice, mulai dipopulerkan sejak 2012, James Lewis, Fred George, Adrian. 

    http://2012.33degree.org/talk/show/67 
    http://www.slideshare.net/fredgeorge/micro-service-architecure
    https://www.slideshare.net/adriancockcroft/microservices-workshop-all-topics-deck-2016 


    " an approach to developing a single application as a suite of small services, 
    each running in its own process and communicating with lightweight mechanisms"
    Martin Fowler : https://martinfowler.com/articles/microservices.html 

    
## Plus Minus Microservices

    + Independent Development       
    + Independent Data Management
    + Independent Technology
    + Independent Release
    + Independent Scaling

    - Level of Modularity
    - Interoperability / Versioning
    - Transaction Management
    - Deployment
    - Configuration Management
    - Integration
    - Discovery
    - Tracing Error / Performance

## Microservice Tooling

    ## Continuous Delivery
        + Travis CI
        + Gitlab CI
        + Jenkins
    ## Spring Cloud
        + Config Service
        + Discovery Service
        + Integration
        + Distributed Tracing
    ## Cloud Native App


## Microservice Deployment
    ## PaaS (Heroku, Pivotal)
    ## IaaS (Digital Ocean, Google, Amazon)
        + Easy provisioning
        + Hourly billing
        + Management API
    ## Automated Setup
        + CM Tools (Ansible, Puppet, Chef)
        + Docker : Custom-made, runnable image
    ## Automated Scaling
        + AWS Autoscale
        + Kubernetes

# Cloud Native

    Cloud-native is an approach to building and running applications that fully exploits the advantages of the cloud computing model

## 12 Factor - https://12factor.net/  
    + Single Codebase Multiple Deploy
    + Dependency Management
    + Configuration Management
        Environment Variable
        Vault
    + Backing Services
        Database, MQ, File
    + Build, Release, Run
        Continuous Delivery
    + Stateless / Ephemeral Process
        Instances come and go
    + Port Binding
        Setiap app bisa menangani request
        Embedded HTTP server
    + Concurrency / Scale Out
        Setiap app bisa direplikasi
    + Disposability
        Kebalikan dari scale out
    + Environment Parity
        dev/staging/prod harus mirip
    + Logs
    + Admin Process 
            
            More Factor : http://pivotal.io/beyond-the-twelve-factor-app 



# Spring Cloud

    + Config Server
    + Discovery Service
    + Feign Client
    + API Gateway
    + OAuth
    + Distributed Tracing

## Spring Cloud Family - http://projects.spring.io/spring-cloud/ 

    + Config Server
    + Registry & Discovery Service
    + Service Integration
    + Routing / API Gateway
    + Load Balancing
    + Failover / Circuit Breaker
    + Distributed Tracing
    + Authentication / Authorization

    > https://github.com/endymuhardin/belajar-springcloud 
    > https://github.com/endymuhardin/belajar-springoauth2/ 



source : https://docs.google.com/presentation/d/1s-JbBwd9mipf_xmxrqvmBnDPDTil7ychPKZC4B_wx2Y/edit#slide=id.g20854bfafd_0_79










