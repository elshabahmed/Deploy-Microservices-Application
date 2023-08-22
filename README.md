Online Boutique is a cloud-native microservices demo application. Online Boutique consists of a 10-tier microservices application.

The application is a web-based e-commerce app where users can browse items, add them to the cart, and purchase them.

Google uses this application to demonstrate use of technologies like Kubernetes/GKE, Istio, Stackdriver, gRPC and OpenCensus. 

Architecture: Online Boutique is composed of 11 microservices written in different languages that talk to each other over gRPC, There is a diagram shows how microservices are connecting to each other.

The application used more than one programing language, it is used Go, Node.js, c#, Python, Java and Python/Locust.

The project used redis to store data and used as a message broker in memory database.
