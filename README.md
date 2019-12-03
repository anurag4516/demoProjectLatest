# demoProjectLatest

The application in our example has three distinct parts:

    Database (MySQL server)
    Back end (Java Spring Boot application)
    Front end (Angular app)
    
    We will deploy all of these components on a Kubernetes cluster.
    We will have one replica of database, 
    two replicas of back end and 
    two replicas of front end. 
    
    Front-end instances will communicate with back end through HTTP. 
    Back-end instances will communicate with the database. 
    
    To facilitate this communication, we have to configure Kubernetes accordingly.
    
    The application we are going to deploy has front end implemented with Angular Framework, 
    and back end implemented with Spring Boot Framework.
