# Building-Networked-System-Security

We have built a new secure network infrastructure for ACME in order to seamlessly connect its new London branch
to the Stockholm headquarters. We used different network tools such as OpenSSL, OpenVPN to finish it.

We need to setup two separate networks, one in Stockholm and one in London. And the communication between
these networks should be in a secure manner, which means no information is lost or exposed to outsiders, and no fake
information can be inserted by outsiders. The aspects we need to consider to achieve such secure communication
are as follow.

• Authentication
A digital certificate issued by CA should be assigned to their employees/users for authentication. And also a
mobile device for two-factor authentication as a proof of possession.

• Secure connectivity
Only computers with IP addresses from Stockholm headquarters or the London branch should be able to
access to the internal network of ACME. Communication request outside these two network should be denied.
But at the same time, employees should be able to access the network from their home network.

• Confidentiality
Information and data exchanged between the server and a user be confidential and authenticated. Only the
networks or devices of the ACME employees can access the main web server which has the core data of the
company.

• File exchange
The file exchange process should be confidential, complete and authenticated. And the transmissions are not
only between the internal hosts, but also between the personal devices.

• Wireless access
Employees shall be able to connect their laptop computers to Stockholm using a Wi-Fi connection from
the London branch. And that the connection should be authorized and authenticated through that wireless
connection.

• Other
We wants to be able to monitor the network and network traffic in order to identify suspicious activity and
to alert the company of incoming attacks.
