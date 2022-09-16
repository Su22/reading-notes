# Port mirroring

Port mirroring, also known as SPAN or roving analysis, is a method of monitoring network traffic which forwards a copy of each incoming and/or outgoing packet from one (or several) port(s) (or VLAN) of a switch to another port where the analysis device is connected. Port mirroring can be managed locally or remotely.

## Advantages of port mirroring
* Low cost (this feature is embedded in most switches)
* Can be configured remotely through IP or Console port
* The only way to capture intra-switch traffic
* A good way to capture traffic on several ports at once

## Drawbacks of port mirroring
* Not adequate for fully utilized full-duplex links (packets may be dropped)
* Filters out physical errors
* Impact on the switch’s CPU
* Can alter the timing of the frame (with an impact on response time analysis)
* SPAN has a lesser priority than port to port data transfer

#  Network TAP
A network TAP (Terminal Access Point) is a hardware device which can passively capture traffic on a network. It is commonly used to monitor the traffic between two points in the network. If the network between these two points consists of a physical cable, a network TAP may be the best way to capture traffic.

## Advantages of TAPs
* No risk of dropped packets
* Monitoring of all packets (including hardware errors (MAC & media))
* Provides full visibility, including congestion situations

## Drawbacks of TAPs
* The device may require two listening interfaces on the analysis device
* Costly
* No visibility on intra-switch traffic
* Not appropriate for the observation of a narrow traffic range








