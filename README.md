# Run Stacks 2.0 Testnet using Docker
Read more at https://testnet.blockstack.org/

## Getting started

1) Install Docker

   https://docs.docker.com/get-docker/
   
2) Clone Repo
   
   ```
   git clone https://github.com/viraja1/stacks-blockchain-docker.git
   ```
   
3) Build Image

   ```
   docker build . -t stacks-blockchain-testnet
   ```
   
4) Run the container in background

   ```
   docker container run -it --name stacks-blockchain-testnet -d stacks-blockchain-testnet
   ```   
   
5) Check logs of the container

   ```
   docker logs -f stacks-blockchain-testnet
   ```
