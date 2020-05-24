a simple stateless microservice in Nodejs, with major functionalities - Authentication,Image Thumbnail Generation

#Authentication (Public Endpoint) – A defined route(LOGIN) containing an arbitrary username/password pair for mock authentication (will accept any username/password) and will return JSON Web Token (will get saved in the local storage of chrome) which can be used to validate future requests.

The JWT obtained in the LOGIN must be attached to each request.



#Image Thumbnail generation (Protected Endpoint) – Will contain a public image URL and return the resulting thumbnail.(Not completed)
