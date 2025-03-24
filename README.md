# qubetics-join-testnet-script

This repository provides ubuntu 22 script for running a node on qubetics testnet:

System Requirements:

- Operating System: Ubuntu 22.04
- Memory: At least 4GB RAM
- Storage: Minimum 20GB available disk space
- Network: Stable internet connection

Clone this repo using:
git clone '<https://github.com/Qubetics/qubetics-join-testnet>'

Setup the node:
open a terminal window and run the following command :

./qubetics_ubuntu_node.sh

NOTE: The blockchain  is syncing in a background as a service. You can print the logs and check the logs of the node with the following command :

journalctl -u qubeticschain.service -f
