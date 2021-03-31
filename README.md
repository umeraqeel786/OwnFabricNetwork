# **Hyperledger Fabric Network**

### This my own configure network .You can use this and change the names and good to GO!

You can use Fabric samples to get started working with Hyperledger Fabric, explore important Fabric features, and learn how to build applications that can interact with blockchain networks using the Fabric SDKs. To learn more about Hyperledger Fabric, visit the Fabric documentation.
Getting started with the Fabric samples

To use the Fabric samples, you need to download the Fabric Docker images and the Fabric CLI tools. First, make sure that you have installed all of the Fabric prerequisites. You can then follow the instructions to Install the Fabric Samples, Binaries, and Docker Images in the Fabric documentation. In addition to downloading the Fabric images and tool binaries, the Fabric samples will also be cloned to your local machine.
Test network

The Fabric test network in the samples repository provides a Docker Compose based test network with two Organization peers and an ordering service node. You can use it on your local machine to run the samples listed below. You can also use it to deploy and test your own Fabric chaincodes and applications. To get started, see the test network tutorial.
Asset transfer samples and tutorials

The asset transfer series provides a series of sample smart contracts and applications to demonstrate how to store and transfer assets using Hyperledger Fabric. Each sample and associated tutorial in the series demonstrates a different core capability in Hyperledger Fabric. The Basic sample provides an introduction on how to write smart contracts and how to interact with a Fabric network using the Fabric SDKs. The Ledger queries, Private data, and State-based endorsement samples demonstrate these additional capabilities. Finally, the Secured agreement sample demonstrates how to bring all the capabilities together to securely transfer an asset in a more realistic transfer scenario.
Smart Contract 	Description 	Tutorial 	Smart contract languages 	Application languages
Basic 	The Basic sample smart contract that allows you to create and transfer an asset by putting data on the ledger and retrieving it. This sample is recommended for new Fabric users. 	Writing your first application 	Go, JavaScript, TypeScript, Java 	Go, JavaScript, TypeScript, Java
Ledger queries 	The ledger queries sample demonstrates range queries and transaction updates using range queries (applicable for both LevelDB and CouchDB state databases), and how to deploy an index with your chaincode to support JSON queries (applicable for CouchDB state database only). 	Using CouchDB 	Go, JavaScript 	Java, JavaScript
Private data 	This sample demonstrates the use of private data collections, how to manage private data collections with the chaincode lifecycle, and how the private data hash can be used to verify private data on the ledger. It also demonstrates how to control asset updates and transfers using client-based ownership and access control. 	Using Private Data 	Go, Java 	JavaScript
State-Based Endorsement 	This sample demonstrates how to override the chaincode-level endorsement policy to set endorsement policies at the key-level (data/asset level). 	Using State-based endorsement 	Java, TypeScript 	JavaScript
Secured agreement 	Smart contract that uses implicit private data collections, state-based endorsement, and organization-based ownership and access control to keep data private and securely transfer an asset with the consent of both the current owner and buyer. 	Secured asset transfer 	Go 	JavaScript
Events 	The events sample demonstrates how smart contracts can emit events that are read by the applications interacting with the network. 	README 	JavaScript, Java 	JavaScript
Attribute-based access control 	Demonstrates the use of attribute and identity based access control using a simple asset transfer scenario 	README 	Go 	None
