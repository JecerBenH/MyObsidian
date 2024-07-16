## component diagram :
i want a descriptive component diagram of a lwm2m infrastructure.
this infrastructure is composed of  : 
-lwm2m client ( a device on which sensors are mounted for data collection and control) .
-lwm2m server which is responsible for monitoring lwm2m clients and visualizing their measurements and logging them . the server can control clients by turning them on/off or changing some variables.
-lwm2m bootstrap server : is responsible for finding closest server for clients to connect to.
-coap file server : responsible for delivering firmware updates for clients. 