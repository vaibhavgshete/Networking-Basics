# Networking Concepts for DevOps Engineers

## 1. Networking Basics
- **IP Addressing (IPv4 & IPv6)** – Understanding private vs. public IPs, CIDR notation, and subnetting.
- **Subnetting** – Dividing a network into smaller sub-networks.
- **MAC Address** – Unique hardware identifier for network interfaces.
- **DNS (Domain Name System)** – Resolving domain names to IP addresses.
- **Ports & Protocols** – Understanding TCP, UDP, and common ports (e.g., 22 for SSH, 80 for HTTP, 443 for HTTPS).

## 2. Network Communication
- **OSI & TCP/IP Models** – Layers of communication and how data flows.
- **Routing** – How packets travel from source to destination.
- **NAT (Network Address Translation)** – Mapping private to public IPs for internet access.
- **DHCP (Dynamic Host Configuration Protocol)** – Assigning IP addresses dynamically.
- **Firewall & Security Groups** – Controlling inbound/outbound traffic.

## 3. Networking in Linux & Containers
- **Linux Networking Commands** – `ip a`, `ip route`, `netstat`, `ss`, `nslookup`, `dig`, `traceroute`, `tcpdump`, etc.
- **Bridging & Virtual Network Interfaces** – How virtual network adapters work.
- **iptables & nftables** – Configuring firewalls in Linux.
- **Docker Networking** – Bridge, host, overlay, macvlan, and none networks.
- **Kubernetes Networking** – Pod-to-pod communication, CNI plugins (Calico, Flannel), Ingress controllers.

## 4. Cloud Networking
- **VPC (Virtual Private Cloud)** – Isolated cloud networks.
- **Load Balancers** – Distributing traffic across multiple servers.
- **VPN & Peering** – Secure connectivity between networks.
- **CDN (Content Delivery Network)** – Distributing content closer to users.
- **Service Mesh** – Istio, Linkerd for microservices networking.

## 5. DevOps-Specific Networking
- **CI/CD Pipeline Connectivity** – Secure communication between build runners and repositories.
- **Reverse Proxy** – Using Nginx, Apache, or Traefik to route traffic.
- **Networking for Monitoring & Logging** – How tools like Prometheus, Grafana, and ELK stack communicate.
- **Networking Security** – Zero Trust, TLS/SSL, SSH, IAM, OAuth, JWT.

## 6. Troubleshooting & Performance
- **Ping & Latency** – Measuring network response times.
- **Packet Capture & Analysis** – Using Wireshark or `tcpdump`.
- **Network Bottlenecks** – Diagnosing slow connections.
- **DNS Issues** – Identifying misconfigurations or failures.
- **Load Testing** – Using tools like Apache JMeter, Locust.

