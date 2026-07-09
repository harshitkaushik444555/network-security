# What is VPN?
A VPN is a networking technology that establishes an encrypted tunnel over a public network, allowing users to securely transmit data and access private network resources.

# What are the types of VPN?
Types based on deployments:
1. Remote Access VPN: It allows an individual user to securely connect to a private network over the internet, and it is widely used by employees working remotely.
2. Site-to-Site VPN: It securely connects two or more separate networks, such as a head office and branch offices, so internal communication remains protected across locations.
3. Mobile VPN: It is designed for mobile users and keeps the VPN session stable even when the device switches between Wi-Fi and cellular networks.
4. MPLS VPN: It is a provider-managed enterprise WAN solution that offers scalable connectivity and traffic prioritization, but it typically does not provide end-to-end encryption by default.

Types based on protocols (tunnelling technology):
1. PPTP (Point-to-Point Tunneling Protocol):
PPTP is one of the earliest VPN protocols developed by Microsoft. It creates a secure tunnel for transmitting data over the internet and is known for its fast connection speeds and easy configuration. However, it uses outdated encryption methods and has several known security vulnerabilities, making it unsuitable for protecting sensitive information.
2. L2TP/IPsec (Layer 2 Tunneling Protocol with Internet Protocol Security):
L2TP provides the tunneling mechanism, while IPsec provides encryption, authentication, and data integrity. This combination offers stronger security than PPTP and is widely supported by operating systems and networking devices. However, because it encapsulates data twice, it can result in slightly slower performance.
3. OpenVPN: OpenVPN is an open-source VPN protocol that uses SSL/TLS encryption to create secure communication tunnels. It is highly secure, flexible, and compatible with most operating systems. OpenVPN is widely used by commercial VPN services due to its strong encryption, reliability, and ability to bypass many network restrictions.
4. IKEv2/IPsec (Internet Key Exchange Version 2 with IPsec): IKEv2/IPsec is a modern VPN protocol that combines the IKEv2 key exchange protocol with IPsec encryption. It provides excellent security, high-speed performance, and stable connections, especially on mobile devices. It can quickly reconnect when switching between networks, such as from Wi-Fi to mobile data.
IKEv2 = Sets up and manages the secure connection.
IPsec = Encrypts and protects the data sent through that connection.
5. SSTP (Secure Socket Tunneling Protocol): SSTP is a VPN protocol developed by Microsoft that uses SSL/TLS encryption over HTTPS (port 443). Because it uses the same port as secure web traffic, it can pass through most firewalls and proxy servers. It offers strong security but is primarily designed for Windows environments.
6. WireGuard is a modern VPN protocol designed to be lightweight, fast, and easier to secure due to a small codebase.
