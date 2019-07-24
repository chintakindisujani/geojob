geojob
======

Find local jobs using MongoDB and Backbone.js app

Application Technology Stack
The application was built using the following technology stack :

Java EE 6 : Using JAX-RS and CDI. 
What is JAX-RS?

Restful Web Services. Which provides a Java API for creating web services according to the REST architectural pattern.

What is CDI? 
CDI stands for Context and Dependency Injection. CDI allows Java EE components to be bound to lifecycle contexts, injected, and then interact in a loosely coupled way 
by triggering and observing events.

MongoDB : MongoDB is a NoSQL document oriented datastore.  Jobs data are persisted in MongoDB. It usesgeo spatial capabilities in the application.

HTML 5 : The client side of the application is built using HTML 5. Also uses W3C GeoLocation API to get the users current location.

Google Maps : The application uses Google Maps to render the user and jobs information.

OpenShift : The application is deployed to the OpenShift public PaaS at - http://geojobs-hapandya.rhcloud.com/
