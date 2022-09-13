# Network Address Translation (NAT)
Network Address Translation (NAT) is a process in which one or more local IP address is translated into one or more Global IP address and vice versa in order to provide Internet access to the local hosts. Also, it does the translation of port numbers i.e. masks the port number of the host with another port number, in the packet that will be routed to the destination.

## Network Address Translation (NAT) Types 
* Static NAT – In this, a single unregistered (Private) IP address is mapped with a legally registered (Public) IP address i.e one-to-one mapping between local and global addresses. This is generally used for Web hosting. These are not used in organizations as there are many devices that will need Internet access and to provide Internet access, a public IP address is needed. 

* Dynamic NAT – In this type of NAT, an unregistered IP address is translated into a registered (Public) IP address from a pool of public IP addresses. If the IP address of the pool is not free, then the packet will be dropped as only a fixed number of private IP addresses can be translated to public addresses. 

* Port Address Translation (PAT) – This is also known as NAT overload. In this, many local (private) IP addresses can be translated to a single registered IP address. Port numbers are used to distinguish the traffic i.e., which traffic belongs to which IP address. This is most frequently used as it is cost-effective as thousands of users can be connected to the Internet by using only one real global (public) IP address. 

## Advantages of NAT – 
 
 * NAT conserves legally registered IP addresses. 
 * It provides privacy as the device’s IP address, sending and receiving the traffic, will be hidden.
 * Eliminates address renumbering when a network evolves. 

## Disadvantage of NAT – 
* Translation results in switching path delays. 
* Certain applications will not function while NAT is enabled. 
* Complicates tunneling protocols such as IPsec. 
* Also, the router being a network layer device, should not tamper with port numbers(transport layer) but it has to do so because of NAT. 
