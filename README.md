<h1 align="center">Routing Information Protocol</h1>
<p align = "center"> Implementation with Bellman-Ford Algorithm</p>

<p align="center">
  <a href="#-technology">Technology</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-run">How to Run</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">License</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=000000">
</p>
## Introduction
This repository contains the code implementation of the Routing Information Protocol (RIP) using Python. The RIP implementation consists of classes and functions that simulate the exchange of routing information between routers in a network.

### What is Routing Information Protocol (RIP)?
Routing Information Protocol (RIP) is one of the oldest distance-vector routing protocols used in computer networks. It was designed to help routers dynamically exchange routing information within an autonomous system (AS). RIP is classified as a distance-vector protocol because it measures the distance (or cost) to a destination network and makes routing decisions based on this information.

RIP operates by broadcasting its routing table to neighboring routers and receiving updates from them. The protocol employs the Bellman-Ford algorithm to calculate the shortest path to each destination network. RIP uses hop count as the metric to determine the cost of a route, where each hop represents a router traversed.

## ✨ Technology

The Project was develop as using the following techs:
- Python 3.6+

## 💻 Project
The repository includes the following files:

* router.py: This file contains the implementation of the router_base and 
* router classes. The router_base class provides the basic structure and functionality for a router, while the router class inherits from router_base and implements the RIP-specific functions.
* rip_packet.py: This file contains the RIP_entry and RIP_packet classes, which represent the entries in the forwarding table and the packets used for RIP communication.
* port.py: This file contains the port_link and port classes, which define the links associated with each port of a router.
* topology_reader.py: This file contains the topology_to_routers function, which converts a network topology representation into a list of router objects.
## 🚀 How to Run

To run the RIP implementation, follow these steps:

1. Clone the repository to your local machine:
bash.
2. Navigate to the project directory:
3. Open the Python script in your preferred editor.
4. Modify the network topology representation in the main function to define your desired network configuration. Each sublist represents a router and its corresponding ports and links.
5. Run the Python script:
6. Observe the output, which will display the initial state of the routers, followed by the iterative exchange of RIP packets and the updated forwarding tables.
7. Iterate and refine the implementation as needed to ensure the routers correctly exchange routing information and update their forwarding tables.


## 📄 License
The projects is under the MIT license. See the file [LICENSE](LICENSE) fore more details

---
## Author

Made with ♥ by Rafael 👋🏻


[![Linkedin Badge](https://img.shields.io/badge/-Rafael-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/tgmarinho/)](https://www.linkedin.com/in/rafael-mgr/)
[![Gmail Badge](https://img.shields.io/badge/-Gmail-red?style=flat-square&link=mailto:nelsonsantosaraujo@hotmail.com)](mailto:ribeirorafaelmatehus@gmail.com)
