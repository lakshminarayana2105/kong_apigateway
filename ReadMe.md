
For Dynamic Config via Admin API (/config):

post:http://localhost:8001/config
body-->binary--> add kong.yml file

Get:http://localhost:8001/config

For knowing services running:

Get:http://localhost:8001/services/

For users date:

Get:http://localhost:8000/users


For keyclock token:

post:http://localhost:8080/realms/Hexadefence/protocol/openid-connect/token


For creating the network:

command: docker network create kong-net 

For docker to run :

command:docker-compose up --build


