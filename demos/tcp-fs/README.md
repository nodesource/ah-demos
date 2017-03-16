## Multi Connection

- one server that ends each connection immediately and closes itself after the 3rd one
- three clients that open a connection
- server processes data when it closed
- client processes no data
- the async-hook subscription is set up _before_ the server is listening in order to gather the
  listen step and show how we can corelate it with the connections
  
## Data Files

- server network only data saved to `./test/tmp/multi-connection.server.json`
- server all activity data saved to `./test/tmp/multi-connection.server.all.json`

Run via `./run`
