### Data Link

* A segment on the data link layer is where all nodes can send traffic using hardware addresses (i.e. MAC addresses). A layer 2 segment might include multiple physical segments, this is known as a logical topology.
* Very few networks have hosts directly connected. Most use a central node, i.e. a switch or wireless access point. These provide forwarding function.
* Addresses of interfaces within the same segment are called local addresses or hardware addresses


* Data link layer organize the stream of bits from the physical layer into structured units called frames.
* Each frame contains a network layer packet this contains the control information in the form of header fields. The headers contain the source and destination hardware addresses plus a basic error check to ensure the packet is valid.


#### Example devices that operate at Layer 2
* NICs (Network adapters or network interface card)
* Bridge - A bridge joins physical network segments while minimizing the performace of having more nodes on the same network. They have multiple ports, these function as a network interface.
* Switch - Advanced type of bridge with many ports. Creates links between a large number of nodes but much more efficiently
* Wireless access point (AP) - Allows nodes with wireless network cards to communicate and creates a bridge between wireless networks and wired ones.