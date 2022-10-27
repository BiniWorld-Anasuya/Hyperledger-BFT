## Build Your First Network (BYFN)

The directions for using this are documented in the Hyperledger Fabric
["Build Your First Network"](http://hyperledger-fabric.readthedocs.io/en/latest/build_network.html) tutorial.


download the hyperledger binaries and required docker images 
curl -sSL https://bit.ly/2ysbOFE | bash -s -- 1.4.3 1.4.3 0.4.18 


Run the first-network with RAFT can be done by running the ./byfn.sh up -o etcdraft 


check the orderer containers by logging into docker containers using $ docker logs orderer3.example.com



stop the network $./byfn.sh down

*NOTE:* After navigating to the documentation, choose the documentation version that matches your version of Fabric

