# CCNA Labs

Hands-on labs I am building while studying for the **Cisco CCNA (200-301)** exam. Every lab is built in Cisco Packet Tracer and documented with the topology, step-by-step configuration, verification output and troubleshooting notes.

**Plan:** 8 weeks, 10 labs per week, plus one project at the end of each week. Week 8 ends with a full enterprise network as the final project.

## Progress

| Week | Topic | Labs | Project | Status |
|------|-------|------|---------|--------|
| 1 | [Network Fundamentals & Addressing](week-01-network-fundamentals-addressing/) | 10 | Small Company Network with VLSM | In progress (2/10 labs) |
| 2 | [Switching & VLANs](week-02-switching-vlans/) | 10 | Multi-Department Campus with Inter-VLAN Routing | Not started |
| 3 | [Layer 2 Redundancy & Security](week-03-layer-2-redundancy-security/) | 10 | Redundant Campus with Secured Access Layer | Not started |
| 4 | [IP Routing](week-04-ip-routing/) | 10 | Multi-Site WAN with OSPF | Not started |
| 5 | [IP Services](week-05-ip-services/) | 10 | Branch Internet Access with DHCP, NAT & HSRP | Not started |
| 6 | [Network Security](week-06-network-security/) | 10 | Secured Enterprise Network with ACLs | Not started |
| 7 | [IPv6 & Automation](week-07-ipv6-automation/) | 10 | Dual-Stack Network with Automated Backups | Not started |
| 8 | [Review, Troubleshooting & Final](week-08-review-troubleshooting-final/) | 10 | **Final Project:** Full Enterprise Network | Not started |

## Repository Structure

```
ccna-labs/
├── README.md
├── week-01-network-fundamentals-addressing/
│   ├── README.md                 # week overview and lab list
│   ├── lab-01-basic-device-configuration/
│   │   ├── README.md             # objective, steps, verification, lessons
│   │   ├── lab.pkt               # Packet Tracer file
│   │   ├── configs/              # sanitized device configs
│   │   └── images/               # topology and verification screenshots
│   ├── ...
│   └── project-small-company-network-with-vlsm/
└── week-02-.../
```

## What Each Lab Contains

- **Objective:** what the lab teaches.
- **Topology and addressing table:** devices, interfaces and IPs.
- **Steps:** the commands used, with a short explanation of each.
- **Verification:** the `show` and `ping` output that proves it works.
- **Troubleshooting:** problems I hit and how I fixed them.
- **Lessons learned:** the key takeaways.

## Tools

- Cisco Packet Tracer
- GNS3 (for selected labs)
- Python and Netmiko (Week 7)
- Ansible (Week 7)
- Git and GitHub

## How to Open a Lab

1. Install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) (free with a Cisco Networking Academy account).
2. Open the `lab.pkt` file inside the lab folder.
3. Follow the lab `README.md` and compare your results with the verification section.

## Notes

- All passwords and secrets are removed from the saved configs.
- Labs are numbered in the recommended order, and later weeks build on earlier ones.
