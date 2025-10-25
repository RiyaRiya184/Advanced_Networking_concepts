# Advanced Networking Concepts in Cloud Computing
This document explains key networking components used in cloud, virtualization, and Kubernetes environments — including TUN/TAP devices, virtual switches, overlay networks, and kernel-user data flow.
## 1. TUN Interface
TUN (Network TUNnel)

-A TUN interface operates at Layer 3 (Network Layer).
-It simulates a network device and handles IP packets.
-Used for routing traffic between virtual machines, VPNs, or containers.

Example:
OpenVPN and WireGuard use TUN interfaces to tunnel IP packets over an encrypted channel.
