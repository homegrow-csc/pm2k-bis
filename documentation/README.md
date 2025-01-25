# how to read the documentation

* dashed lines means "provides". A host can provide a service like MQTT for example.
* full lines means "data is flowing". A host can f.e. poll data from InfluxDB and push data to MariaDB. 
* the reverse proxy is not required. it can be used if one wish to accept submissions from a wider range of clients.
* there is no requirement to spread out the services as has been done here. You can probably run it all on the same host.
* it is a simplified mixed physical / logical map, the symbols might be incorrect.

 
