- docker build . -t blockchainserver
- docker run -p 65005:65005 -d --network="host" blockchainserver

- docker exec -it <container ID> /bin/bash
