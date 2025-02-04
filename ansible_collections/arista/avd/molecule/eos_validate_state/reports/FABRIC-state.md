# Validate State Report

**Table of Contents:**

- [Validate State Report](validate-state-report)
  - [Test Results Summary](#test-results-summary)
  - [Failed Test Results Summary](#failed-test-results-summary)
  - [All Test Results](#all-test-results)

## Test Results Summary

### Summary Totals

| Total Tests | Total Tests Passed | Total Tests Failed | Total Tests Skipped |
| ----------- | ------------------ | ------------------ | ------------------- |
| 1710 | 0 | 0 | 0 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Tests Skipped | Categories Failed | Categories Skipped |
| --- | ----------- | ------------ | ------------ | ------------- | ----------------- | ------------------ |
| dc1-leaf1a | 124 | 0 | 0 | 0 | - | - |
| dc1-leaf1b | 117 | 0 | 0 | 0 | - | - |
| dc1-leaf1c | 59 | 0 | 0 | 0 | - | - |
| dc1-leaf2a | 114 | 0 | 0 | 0 | - | - |
| dc1-leaf2c | 58 | 0 | 0 | 0 | - | - |
| dc1-spine1 | 72 | 0 | 0 | 0 | - | - |
| dc1-spine2 | 72 | 0 | 0 | 0 | - | - |
| dc1-wan1 | 51 | 0 | 0 | 0 | - | - |
| dc1-wan2 | 51 | 0 | 0 | 0 | - | - |
| dc2-leaf1a | 128 | 0 | 0 | 0 | - | - |
| dc2-leaf1b | 128 | 0 | 0 | 0 | - | - |
| dc2-leaf1c | 43 | 0 | 0 | 0 | - | - |
| dc2-leaf2a | 133 | 0 | 0 | 0 | - | - |
| dc2-leaf2b | 129 | 0 | 0 | 0 | - | - |
| dc2-leaf2c | 43 | 0 | 0 | 0 | - | - |
| dc2-leaf3a.arista.com | 125 | 0 | 0 | 0 | - | - |
| dc2-leaf3b.arista.com | 125 | 0 | 0 | 0 | - | - |
| dc2-spine1 | 69 | 0 | 0 | 0 | - | - |
| dc2-spine2 | 69 | 0 | 0 | 0 | - | - |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed | Tests Skipped |
| ------------- | ----------- | ------------ | ------------ | ------------- |
| AAA | 133 | 0 | 0 | 0 |
| BFD | 6 | 0 | 0 | 0 |
| BGP | 99 | 0 | 0 | 0 |
| Configuration | 38 | 0 | 0 | 0 |
| Field Notices | 38 | 0 | 0 | 0 |
| Hardware | 209 | 0 | 0 | 0 |
| IGMP | 12 | 0 | 0 | 0 |
| IP Reachability | 46 | 0 | 0 | 0 |
| Interfaces | 286 | 0 | 0 | 0 |
| LLDP Topology | 76 | 0 | 0 | 0 |
| Logging | 48 | 0 | 0 | 0 |
| Loopback0 Reachability | 165 | 0 | 0 | 0 |
| MLAG | 39 | 0 | 0 | 0 |
| Multicast | 12 | 0 | 0 | 0 |
| NTP | 19 | 0 | 0 | 0 |
| OSPF | 4 | 0 | 0 | 0 |
| Profiles | 4 | 0 | 0 | 0 |
| Routing | 6 | 0 | 0 | 0 |
| Routing Table | 180 | 0 | 0 | 0 |
| SNMP | 57 | 0 | 0 | 0 |
| STP | 30 | 0 | 0 | 0 |
| Security | 19 | 0 | 0 | 0 |
| Software | 78 | 0 | 0 | 0 |
| System | 152 | 0 | 0 | 0 |
| VXLAN | 4 | 0 | 0 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Categories | Test Description | Test | Test Result | Messages |
| ------- | ---- | --------------- | ---------------- | ---- | ----------- | -------- |

## All Test Results

| Test ID | Node | Test Categories | Test Description | Test | Test Result | Messages |
| ------- | ---- | --------------- | ---------------- | ---- | ----------- | -------- |
| 1 | dc1-leaf1a | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 2 | dc1-leaf1a | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 3 | dc1-leaf1a | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 4 | dc1-leaf1a | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 5 | dc1-leaf1a | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 6 | dc1-leaf1a | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 7 | dc1-leaf1a | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 8 | dc1-leaf1a | BGP | Verifies the configured routing protocol model. | Routing protocol model: multi-agent | NOT RUN | - |
| 9 | dc1-leaf1a | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.0.1 | NOT RUN | - |
| 10 | dc1-leaf1a | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.0.2 | NOT RUN | - |
| 11 | dc1-leaf1a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.1.97 | NOT RUN | - |
| 12 | dc1-leaf1a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.0 | NOT RUN | - |
| 13 | dc1-leaf1a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.1 | NOT RUN | - |
| 14 | dc1-leaf1a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.2 | NOT RUN | - |
| 15 | dc1-leaf1a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.5 | NOT RUN | - |
| 16 | dc1-leaf1a | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 17 | dc1-leaf1a | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 18 | dc1-leaf1a | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 19 | dc1-leaf1a | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 20 | dc1-leaf1a | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 21 | dc1-leaf1a | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 22 | dc1-leaf1a | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 23 | dc1-leaf1a | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 24 | dc1-leaf1a | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 25 | dc1-leaf1a | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 26 | dc1-leaf1a | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 27 | dc1-leaf1a | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 28 | dc1-leaf1a | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 29 | dc1-leaf1a | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 30 | dc1-leaf1a | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 31 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC1-SPINE1_Ethernet1 = 'up' | NOT RUN | - |
| 32 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC1-SPINE2_Ethernet1 = 'up' | NOT RUN | - |
| 33 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - MLAG_PEER_dc1-leaf1b_Ethernet3 = 'up' | NOT RUN | - |
| 34 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - MLAG_PEER_dc1-leaf1b_Ethernet4 = 'up' | NOT RUN | - |
| 35 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet5 - dc1-leaf1-server1_PCI1 = 'up' | NOT RUN | - |
| 36 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet6 - P2P_LINK_TO_DC1-WAN1_Ethernet1 = 'up' | NOT RUN | - |
| 37 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet7 - P2P_LINK_TO_DC1-WAN2_Ethernet1 = 'up' | NOT RUN | - |
| 38 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet8 - DC1-LEAF1C_Ethernet1 = 'up' | NOT RUN | - |
| 39 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - EVPN_Overlay_Peering = 'up' | NOT RUN | - |
| 40 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback1 - VTEP_VXLAN_Tunnel_Source = 'up' | NOT RUN | - |
| 41 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback10 - VRF10_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 42 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback11 - VRF11_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 43 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel3 - MLAG_PEER_dc1-leaf1b_Po3 = 'up' | NOT RUN | - |
| 44 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel5 - dc1-leaf1-server1_PortChannel dc1-leaf1-server1 = 'up' | NOT RUN | - |
| 45 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel8 - DC1-LEAF1C_Po1 = 'up' | NOT RUN | - |
| 46 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan11 - VRF10_VLAN11 = 'up' | NOT RUN | - |
| 47 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan12 - VRF10_VLAN12 = 'up' | NOT RUN | - |
| 48 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan21 - VRF11_VLAN21 = 'up' | NOT RUN | - |
| 49 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan22 - VRF11_VLAN22 = 'up' | NOT RUN | - |
| 50 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF10 = 'up' | NOT RUN | - |
| 51 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3010 - MLAG_PEER_L3_iBGP: vrf VRF11 = 'up' | NOT RUN | - |
| 52 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4085 - Inband Management = 'up' | NOT RUN | - |
| 53 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4093 - MLAG_PEER_L3_PEERING = 'up' | NOT RUN | - |
| 54 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4094 - MLAG_PEER = 'up' | NOT RUN | - |
| 55 | dc1-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vxlan1 = 'up' | NOT RUN | - |
| 56 | dc1-leaf1a | IP Reachability | ip reachability test p2p links | Source: dc1-leaf1a_Ethernet1 - Destination: dc1-spine1_Ethernet1 | NOT RUN | - |
| 57 | dc1-leaf1a | IP Reachability | ip reachability test p2p links | Source: dc1-leaf1a_Ethernet2 - Destination: dc1-spine2_Ethernet1 | NOT RUN | - |
| 58 | dc1-leaf1a | IP Reachability | ip reachability test p2p links | Source: dc1-leaf1a_Ethernet6 - Destination: dc1-wan1_Ethernet1 | NOT RUN | - |
| 59 | dc1-leaf1a | IP Reachability | ip reachability test p2p links | Source: dc1-leaf1a_Ethernet7 - Destination: dc1-wan2_Ethernet1 | NOT RUN | - |
| 60 | dc1-leaf1a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc1-spine1_Ethernet1 | NOT RUN | - |
| 61 | dc1-leaf1a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc1-spine2_Ethernet1 | NOT RUN | - |
| 62 | dc1-leaf1a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: dc1-leaf1b_Ethernet3 | NOT RUN | - |
| 63 | dc1-leaf1a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: dc1-leaf1b_Ethernet4 | NOT RUN | - |
| 64 | dc1-leaf1a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: dc1-wan1_Ethernet1 | NOT RUN | - |
| 65 | dc1-leaf1a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: dc1-wan2_Ethernet1 | NOT RUN | - |
| 66 | dc1-leaf1a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet8 - remote: dc1-leaf1c_Ethernet1 | NOT RUN | - |
| 67 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.0.1 | NOT RUN | - |
| 68 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.0.2 | NOT RUN | - |
| 69 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.0.3 | NOT RUN | - |
| 70 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.0.4 | NOT RUN | - |
| 71 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.0.5 | NOT RUN | - |
| 72 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.128.11 | NOT RUN | - |
| 73 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.128.12 | NOT RUN | - |
| 74 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.128.13 | NOT RUN | - |
| 75 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.128.14 | NOT RUN | - |
| 76 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.128.15 | NOT RUN | - |
| 77 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.128.16 | NOT RUN | - |
| 78 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.128.17 | NOT RUN | - |
| 79 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.128.18 | NOT RUN | - |
| 80 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.2.1 | NOT RUN | - |
| 81 | dc1-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1a - 10.255.0.3/32 Destination: 10.255.2.2 | NOT RUN | - |
| 82 | dc1-leaf1a | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 83 | dc1-leaf1a | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 84 | dc1-leaf1a | Profiles | - | VerifyUnifiedForwardingTableMode | NOT RUN | - |
| 85 | dc1-leaf1a | Profiles | Verify that the assigned TCAM profile is actually running on the device | VerifyTcamProfile | NOT RUN | - |
| 86 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.0.1 | NOT RUN | - |
| 87 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.0.2 | NOT RUN | - |
| 88 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.0.3 | NOT RUN | - |
| 89 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.0.4 | NOT RUN | - |
| 90 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.0.5 | NOT RUN | - |
| 91 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.11 | NOT RUN | - |
| 92 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.12 | NOT RUN | - |
| 93 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.13 | NOT RUN | - |
| 94 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.14 | NOT RUN | - |
| 95 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.15 | NOT RUN | - |
| 96 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.16 | NOT RUN | - |
| 97 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.17 | NOT RUN | - |
| 98 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.18 | NOT RUN | - |
| 99 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.2.1 | NOT RUN | - |
| 100 | dc1-leaf1a | Routing Table | Remote Lo0 address | 10.255.2.2 | NOT RUN | - |
| 101 | dc1-leaf1a | Routing Table | Remote VTEP address | 10.255.1.3 | NOT RUN | - |
| 102 | dc1-leaf1a | Routing Table | Remote VTEP address | 10.255.1.5 | NOT RUN | - |
| 103 | dc1-leaf1a | Routing Table | Remote VTEP address | 10.255.129.13 | NOT RUN | - |
| 104 | dc1-leaf1a | Routing Table | Remote VTEP address | 10.255.129.15 | NOT RUN | - |
| 105 | dc1-leaf1a | Routing Table | Remote VTEP address | 10.255.129.17 | NOT RUN | - |
| 106 | dc1-leaf1a | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 107 | dc1-leaf1a | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 108 | dc1-leaf1a | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 109 | dc1-leaf1a | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 110 | dc1-leaf1a | Software | Verifies all EOS extensions installed on the device are enabled for boot persistence. | VerifyEOSExtensions | NOT RUN | - |
| 111 | dc1-leaf1a | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 112 | dc1-leaf1a | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 113 | dc1-leaf1a | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 114 | dc1-leaf1a | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 115 | dc1-leaf1a | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 116 | dc1-leaf1a | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 117 | dc1-leaf1a | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 118 | dc1-leaf1a | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 119 | dc1-leaf1a | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 120 | dc1-leaf1a | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 121 | dc1-leaf1a | VXLAN | Verifies the VNI-VLAN bindings of the Vxlan1 interface. | VerifyVxlanVniBinding | NOT RUN | - |
| 122 | dc1-leaf1a | VXLAN | Verifies the VTEP peers of the Vxlan1 interface | VerifyVxlanVtep | NOT RUN | - |
| 123 | dc1-leaf1a | VXLAN | Verifies the Vxlan1 interface status. | VerifyVxlan1Interface | NOT RUN | - |
| 124 | dc1-leaf1a | VXLAN | Verifies there are no VXLAN config-sanity inconsistencies. | VerifyVxlanConfigSanity | NOT RUN | - |
| 125 | dc1-leaf1b | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 126 | dc1-leaf1b | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 127 | dc1-leaf1b | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 128 | dc1-leaf1b | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 129 | dc1-leaf1b | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 130 | dc1-leaf1b | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 131 | dc1-leaf1b | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 132 | dc1-leaf1b | BGP | Verifies the configured routing protocol model. | Routing protocol model: multi-agent | NOT RUN | - |
| 133 | dc1-leaf1b | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.0.1 | NOT RUN | - |
| 134 | dc1-leaf1b | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.0.2 | NOT RUN | - |
| 135 | dc1-leaf1b | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.1.96 | NOT RUN | - |
| 136 | dc1-leaf1b | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.3 | NOT RUN | - |
| 137 | dc1-leaf1b | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.4 | NOT RUN | - |
| 138 | dc1-leaf1b | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.6 | NOT RUN | - |
| 139 | dc1-leaf1b | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.7 | NOT RUN | - |
| 140 | dc1-leaf1b | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 141 | dc1-leaf1b | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 142 | dc1-leaf1b | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 143 | dc1-leaf1b | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 144 | dc1-leaf1b | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 145 | dc1-leaf1b | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 146 | dc1-leaf1b | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 147 | dc1-leaf1b | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 148 | dc1-leaf1b | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 149 | dc1-leaf1b | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 150 | dc1-leaf1b | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 151 | dc1-leaf1b | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 152 | dc1-leaf1b | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 153 | dc1-leaf1b | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 154 | dc1-leaf1b | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 155 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC1-SPINE1_Ethernet2 = 'up' | NOT RUN | - |
| 156 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC1-SPINE2_Ethernet2 = 'up' | NOT RUN | - |
| 157 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - MLAG_PEER_dc1-leaf1a_Ethernet3 = 'up' | NOT RUN | - |
| 158 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - MLAG_PEER_dc1-leaf1a_Ethernet4 = 'up' | NOT RUN | - |
| 159 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet5 - dc1-leaf1-server1_PCI2 = 'up' | NOT RUN | - |
| 160 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet6 - P2P_LINK_TO_DC1-WAN1_Ethernet2 = 'up' | NOT RUN | - |
| 161 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet7 - P2P_LINK_TO_DC1-WAN2_Ethernet2 = 'up' | NOT RUN | - |
| 162 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet8 - DC1-LEAF1C_Ethernet2 = 'up' | NOT RUN | - |
| 163 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - EVPN_Overlay_Peering = 'up' | NOT RUN | - |
| 164 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback1 - VTEP_VXLAN_Tunnel_Source = 'up' | NOT RUN | - |
| 165 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback10 - VRF10_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 166 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback11 - VRF11_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 167 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel3 - MLAG_PEER_dc1-leaf1a_Po3 = 'up' | NOT RUN | - |
| 168 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel5 - dc1-leaf1-server1_PortChannel dc1-leaf1-server1 = 'up' | NOT RUN | - |
| 169 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel8 - DC1-LEAF1C_Po1 = 'up' | NOT RUN | - |
| 170 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan11 - VRF10_VLAN11 = 'up' | NOT RUN | - |
| 171 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan12 - VRF10_VLAN12 = 'up' | NOT RUN | - |
| 172 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan21 - VRF11_VLAN21 = 'up' | NOT RUN | - |
| 173 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan22 - VRF11_VLAN22 = 'up' | NOT RUN | - |
| 174 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF10 = 'up' | NOT RUN | - |
| 175 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3010 - MLAG_PEER_L3_iBGP: vrf VRF11 = 'up' | NOT RUN | - |
| 176 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4085 - Inband Management = 'up' | NOT RUN | - |
| 177 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4093 - MLAG_PEER_L3_PEERING = 'up' | NOT RUN | - |
| 178 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4094 - MLAG_PEER = 'up' | NOT RUN | - |
| 179 | dc1-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vxlan1 = 'up' | NOT RUN | - |
| 180 | dc1-leaf1b | IP Reachability | ip reachability test p2p links | Source: dc1-leaf1b_Ethernet1 - Destination: dc1-spine1_Ethernet2 | NOT RUN | - |
| 181 | dc1-leaf1b | IP Reachability | ip reachability test p2p links | Source: dc1-leaf1b_Ethernet2 - Destination: dc1-spine2_Ethernet2 | NOT RUN | - |
| 182 | dc1-leaf1b | IP Reachability | ip reachability test p2p links | Source: dc1-leaf1b_Ethernet6 - Destination: dc1-wan1_Ethernet2 | NOT RUN | - |
| 183 | dc1-leaf1b | IP Reachability | ip reachability test p2p links | Source: dc1-leaf1b_Ethernet7 - Destination: dc1-wan2_Ethernet2 | NOT RUN | - |
| 184 | dc1-leaf1b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc1-spine1_Ethernet2 | NOT RUN | - |
| 185 | dc1-leaf1b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc1-spine2_Ethernet2 | NOT RUN | - |
| 186 | dc1-leaf1b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: dc1-leaf1a_Ethernet3 | NOT RUN | - |
| 187 | dc1-leaf1b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: dc1-leaf1a_Ethernet4 | NOT RUN | - |
| 188 | dc1-leaf1b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: dc1-wan1_Ethernet2 | NOT RUN | - |
| 189 | dc1-leaf1b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet7 - remote: dc1-wan2_Ethernet2 | NOT RUN | - |
| 190 | dc1-leaf1b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet8 - remote: dc1-leaf1c_Ethernet2 | NOT RUN | - |
| 191 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.0.1 | NOT RUN | - |
| 192 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.0.2 | NOT RUN | - |
| 193 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.0.3 | NOT RUN | - |
| 194 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.0.4 | NOT RUN | - |
| 195 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.0.5 | NOT RUN | - |
| 196 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.128.11 | NOT RUN | - |
| 197 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.128.12 | NOT RUN | - |
| 198 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.128.13 | NOT RUN | - |
| 199 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.128.14 | NOT RUN | - |
| 200 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.128.15 | NOT RUN | - |
| 201 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.128.16 | NOT RUN | - |
| 202 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.128.17 | NOT RUN | - |
| 203 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.128.18 | NOT RUN | - |
| 204 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.2.1 | NOT RUN | - |
| 205 | dc1-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf1b - 10.255.0.4/32 Destination: 10.255.2.2 | NOT RUN | - |
| 206 | dc1-leaf1b | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 207 | dc1-leaf1b | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 208 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.0.1 | NOT RUN | - |
| 209 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.0.2 | NOT RUN | - |
| 210 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.0.3 | NOT RUN | - |
| 211 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.0.4 | NOT RUN | - |
| 212 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.0.5 | NOT RUN | - |
| 213 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.11 | NOT RUN | - |
| 214 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.12 | NOT RUN | - |
| 215 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.13 | NOT RUN | - |
| 216 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.14 | NOT RUN | - |
| 217 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.15 | NOT RUN | - |
| 218 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.16 | NOT RUN | - |
| 219 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.17 | NOT RUN | - |
| 220 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.18 | NOT RUN | - |
| 221 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.2.1 | NOT RUN | - |
| 222 | dc1-leaf1b | Routing Table | Remote Lo0 address | 10.255.2.2 | NOT RUN | - |
| 223 | dc1-leaf1b | Routing Table | Remote VTEP address | 10.255.1.3 | NOT RUN | - |
| 224 | dc1-leaf1b | Routing Table | Remote VTEP address | 10.255.1.5 | NOT RUN | - |
| 225 | dc1-leaf1b | Routing Table | Remote VTEP address | 10.255.129.13 | NOT RUN | - |
| 226 | dc1-leaf1b | Routing Table | Remote VTEP address | 10.255.129.15 | NOT RUN | - |
| 227 | dc1-leaf1b | Routing Table | Remote VTEP address | 10.255.129.17 | NOT RUN | - |
| 228 | dc1-leaf1b | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 229 | dc1-leaf1b | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 230 | dc1-leaf1b | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 231 | dc1-leaf1b | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 232 | dc1-leaf1b | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 233 | dc1-leaf1b | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 234 | dc1-leaf1b | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 235 | dc1-leaf1b | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 236 | dc1-leaf1b | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 237 | dc1-leaf1b | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 238 | dc1-leaf1b | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 239 | dc1-leaf1b | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 240 | dc1-leaf1b | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 241 | dc1-leaf1b | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 242 | dc1-leaf1c | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 243 | dc1-leaf1c | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 244 | dc1-leaf1c | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 245 | dc1-leaf1c | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 246 | dc1-leaf1c | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 247 | dc1-leaf1c | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 248 | dc1-leaf1c | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 249 | dc1-leaf1c | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 250 | dc1-leaf1c | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 251 | dc1-leaf1c | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 252 | dc1-leaf1c | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 253 | dc1-leaf1c | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 254 | dc1-leaf1c | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 255 | dc1-leaf1c | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 256 | dc1-leaf1c | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 257 | dc1-leaf1c | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 258 | dc1-leaf1c | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 259 | dc1-leaf1c | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 260 | dc1-leaf1c | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 261 | dc1-leaf1c | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 262 | dc1-leaf1c | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 263 | dc1-leaf1c | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 264 | dc1-leaf1c | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - DC1-LEAF1A_Ethernet8 = 'up' | NOT RUN | - |
| 265 | dc1-leaf1c | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - DC1-LEAF1B_Ethernet8 = 'up' | NOT RUN | - |
| 266 | dc1-leaf1c | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet5 - dc1-leaf1-server1_iLO = 'up' | NOT RUN | - |
| 267 | dc1-leaf1c | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel1 - DC1_L3_LEAF1_Po8 = 'up' | NOT RUN | - |
| 268 | dc1-leaf1c | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4085 - L2LEAF_INBAND_MGMT = 'up' | NOT RUN | - |
| 269 | dc1-leaf1c | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc1-leaf1a_Ethernet8 | NOT RUN | - |
| 270 | dc1-leaf1c | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc1-leaf1b_Ethernet8 | NOT RUN | - |
| 271 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.0.1 | NOT RUN | - |
| 272 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.0.2 | NOT RUN | - |
| 273 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.0.3 | NOT RUN | - |
| 274 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.0.4 | NOT RUN | - |
| 275 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.0.5 | NOT RUN | - |
| 276 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.128.11 | NOT RUN | - |
| 277 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.128.12 | NOT RUN | - |
| 278 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.128.13 | NOT RUN | - |
| 279 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.128.14 | NOT RUN | - |
| 280 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.128.15 | NOT RUN | - |
| 281 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.128.16 | NOT RUN | - |
| 282 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.128.17 | NOT RUN | - |
| 283 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.128.18 | NOT RUN | - |
| 284 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.2.1 | NOT RUN | - |
| 285 | dc1-leaf1c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf1c - Vlan4085 Destination: 10.255.2.2 | NOT RUN | - |
| 286 | dc1-leaf1c | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 287 | dc1-leaf1c | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 288 | dc1-leaf1c | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 289 | dc1-leaf1c | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 290 | dc1-leaf1c | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 291 | dc1-leaf1c | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 292 | dc1-leaf1c | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 293 | dc1-leaf1c | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 294 | dc1-leaf1c | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 295 | dc1-leaf1c | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 296 | dc1-leaf1c | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 297 | dc1-leaf1c | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 298 | dc1-leaf1c | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 299 | dc1-leaf1c | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 300 | dc1-leaf1c | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 301 | dc1-leaf2a | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 302 | dc1-leaf2a | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 303 | dc1-leaf2a | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 304 | dc1-leaf2a | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 305 | dc1-leaf2a | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 306 | dc1-leaf2a | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 307 | dc1-leaf2a | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 308 | dc1-leaf2a | BGP | Verifies the configured routing protocol model. | Routing protocol model: multi-agent | NOT RUN | - |
| 309 | dc1-leaf2a | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.0.1 | NOT RUN | - |
| 310 | dc1-leaf2a | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.0.2 | NOT RUN | - |
| 311 | dc1-leaf2a | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.15 | NOT RUN | - |
| 312 | dc1-leaf2a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.10 | NOT RUN | - |
| 313 | dc1-leaf2a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.8 | NOT RUN | - |
| 314 | dc1-leaf2a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 192.168.100.1 | NOT RUN | - |
| 315 | dc1-leaf2a | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 316 | dc1-leaf2a | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 317 | dc1-leaf2a | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 318 | dc1-leaf2a | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 319 | dc1-leaf2a | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 320 | dc1-leaf2a | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 321 | dc1-leaf2a | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 322 | dc1-leaf2a | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 323 | dc1-leaf2a | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 324 | dc1-leaf2a | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 325 | dc1-leaf2a | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 326 | dc1-leaf2a | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 327 | dc1-leaf2a | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 328 | dc1-leaf2a | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 329 | dc1-leaf2a | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 330 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC1-SPINE1_Ethernet3 = 'up' | NOT RUN | - |
| 331 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC1-SPINE2_Ethernet3 = 'up' | NOT RUN | - |
| 332 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - MLAG_PEER_dc1-leaf2b_Ethernet3 = 'up' | NOT RUN | - |
| 333 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - MLAG_PEER_dc1-leaf2b_Ethernet4 = 'up' | NOT RUN | - |
| 334 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet5 - dc1-leaf2-server1_PCI1 = 'up' | NOT RUN | - |
| 335 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet6 - P2P_LINK_TO_dc2-leaf2a_Ethernet6 = 'up' | NOT RUN | - |
| 336 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet8 - DC1-LEAF2C_Ethernet1 = 'up' | NOT RUN | - |
| 337 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - EVPN_Overlay_Peering = 'up' | NOT RUN | - |
| 338 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback1 - VTEP_VXLAN_Tunnel_Source = 'up' | NOT RUN | - |
| 339 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback10 - VRF10_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 340 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback11 - VRF11_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 341 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel3 - MLAG_PEER_dc1-leaf2b_Po3 = 'up' | NOT RUN | - |
| 342 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel5 - dc1-leaf2-server1_PortChannel dc1-leaf2-server1 = 'up' | NOT RUN | - |
| 343 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel8 - DC1-LEAF2C_Po1 = 'up' | NOT RUN | - |
| 344 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan11 - VRF10_VLAN11 = 'up' | NOT RUN | - |
| 345 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan12 - VRF10_VLAN12 = 'up' | NOT RUN | - |
| 346 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan21 - VRF11_VLAN21 = 'up' | NOT RUN | - |
| 347 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan22 - VRF11_VLAN22 = 'up' | NOT RUN | - |
| 348 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF10 = 'up' | NOT RUN | - |
| 349 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3010 - MLAG_PEER_L3_iBGP: vrf VRF11 = 'up' | NOT RUN | - |
| 350 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4085 - Inband Management = 'up' | NOT RUN | - |
| 351 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4093 - MLAG_PEER_L3_PEERING = 'up' | NOT RUN | - |
| 352 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4094 - MLAG_PEER = 'up' | NOT RUN | - |
| 353 | dc1-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vxlan1 = 'up' | NOT RUN | - |
| 354 | dc1-leaf2a | IP Reachability | ip reachability test p2p links | Source: dc1-leaf2a_Ethernet1 - Destination: dc1-spine1_Ethernet3 | NOT RUN | - |
| 355 | dc1-leaf2a | IP Reachability | ip reachability test p2p links | Source: dc1-leaf2a_Ethernet2 - Destination: dc1-spine2_Ethernet3 | NOT RUN | - |
| 356 | dc1-leaf2a | IP Reachability | ip reachability test p2p links | Source: dc1-leaf2a_Ethernet6 - Destination: dc2-leaf2a_Ethernet6 | NOT RUN | - |
| 357 | dc1-leaf2a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc1-spine1_Ethernet3 | NOT RUN | - |
| 358 | dc1-leaf2a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc1-spine2_Ethernet3 | NOT RUN | - |
| 359 | dc1-leaf2a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: dc2-leaf2a_Ethernet6 | NOT RUN | - |
| 360 | dc1-leaf2a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet8 - remote: dc1-leaf2c_Ethernet1 | NOT RUN | - |
| 361 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.0.1 | NOT RUN | - |
| 362 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.0.2 | NOT RUN | - |
| 363 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.0.3 | NOT RUN | - |
| 364 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.0.4 | NOT RUN | - |
| 365 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.0.5 | NOT RUN | - |
| 366 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.128.11 | NOT RUN | - |
| 367 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.128.12 | NOT RUN | - |
| 368 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.128.13 | NOT RUN | - |
| 369 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.128.14 | NOT RUN | - |
| 370 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.128.15 | NOT RUN | - |
| 371 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.128.16 | NOT RUN | - |
| 372 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.128.17 | NOT RUN | - |
| 373 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.128.18 | NOT RUN | - |
| 374 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.2.1 | NOT RUN | - |
| 375 | dc1-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc1-leaf2a - 10.255.0.5/32 Destination: 10.255.2.2 | NOT RUN | - |
| 376 | dc1-leaf2a | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 377 | dc1-leaf2a | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 378 | dc1-leaf2a | Profiles | - | VerifyUnifiedForwardingTableMode | NOT RUN | - |
| 379 | dc1-leaf2a | Profiles | Verify that the assigned TCAM profile is actually running on the device | VerifyTcamProfile | NOT RUN | - |
| 380 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.0.1 | NOT RUN | - |
| 381 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.0.2 | NOT RUN | - |
| 382 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.0.3 | NOT RUN | - |
| 383 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.0.4 | NOT RUN | - |
| 384 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.0.5 | NOT RUN | - |
| 385 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.11 | NOT RUN | - |
| 386 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.12 | NOT RUN | - |
| 387 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.13 | NOT RUN | - |
| 388 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.14 | NOT RUN | - |
| 389 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.15 | NOT RUN | - |
| 390 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.16 | NOT RUN | - |
| 391 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.17 | NOT RUN | - |
| 392 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.18 | NOT RUN | - |
| 393 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.2.1 | NOT RUN | - |
| 394 | dc1-leaf2a | Routing Table | Remote Lo0 address | 10.255.2.2 | NOT RUN | - |
| 395 | dc1-leaf2a | Routing Table | Remote VTEP address | 10.255.1.3 | NOT RUN | - |
| 396 | dc1-leaf2a | Routing Table | Remote VTEP address | 10.255.1.5 | NOT RUN | - |
| 397 | dc1-leaf2a | Routing Table | Remote VTEP address | 10.255.129.13 | NOT RUN | - |
| 398 | dc1-leaf2a | Routing Table | Remote VTEP address | 10.255.129.15 | NOT RUN | - |
| 399 | dc1-leaf2a | Routing Table | Remote VTEP address | 10.255.129.17 | NOT RUN | - |
| 400 | dc1-leaf2a | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 401 | dc1-leaf2a | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 402 | dc1-leaf2a | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 403 | dc1-leaf2a | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 404 | dc1-leaf2a | Software | Verifies all EOS extensions installed on the device are enabled for boot persistence. | VerifyEOSExtensions | NOT RUN | - |
| 405 | dc1-leaf2a | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 406 | dc1-leaf2a | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 407 | dc1-leaf2a | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 408 | dc1-leaf2a | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 409 | dc1-leaf2a | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 410 | dc1-leaf2a | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 411 | dc1-leaf2a | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 412 | dc1-leaf2a | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 413 | dc1-leaf2a | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 414 | dc1-leaf2a | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 415 | dc1-leaf2c | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 416 | dc1-leaf2c | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 417 | dc1-leaf2c | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 418 | dc1-leaf2c | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 419 | dc1-leaf2c | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 420 | dc1-leaf2c | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 421 | dc1-leaf2c | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 422 | dc1-leaf2c | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 423 | dc1-leaf2c | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 424 | dc1-leaf2c | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 425 | dc1-leaf2c | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 426 | dc1-leaf2c | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 427 | dc1-leaf2c | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 428 | dc1-leaf2c | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 429 | dc1-leaf2c | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 430 | dc1-leaf2c | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 431 | dc1-leaf2c | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 432 | dc1-leaf2c | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 433 | dc1-leaf2c | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 434 | dc1-leaf2c | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 435 | dc1-leaf2c | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 436 | dc1-leaf2c | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 437 | dc1-leaf2c | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - DC1-LEAF2A_Ethernet8 = 'up' | NOT RUN | - |
| 438 | dc1-leaf2c | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - DC1-LEAF2B_Ethernet8 = 'adminDown' | NOT RUN | - |
| 439 | dc1-leaf2c | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet5 - dc1-leaf2-server1_iLO = 'up' | NOT RUN | - |
| 440 | dc1-leaf2c | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel1 - DC1_L3_LEAF2_Po8 = 'up' | NOT RUN | - |
| 441 | dc1-leaf2c | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4085 - L2LEAF_INBAND_MGMT = 'up' | NOT RUN | - |
| 442 | dc1-leaf2c | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc1-leaf2a_Ethernet8 | NOT RUN | - |
| 443 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.0.1 | NOT RUN | - |
| 444 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.0.2 | NOT RUN | - |
| 445 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.0.3 | NOT RUN | - |
| 446 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.0.4 | NOT RUN | - |
| 447 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.0.5 | NOT RUN | - |
| 448 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.128.11 | NOT RUN | - |
| 449 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.128.12 | NOT RUN | - |
| 450 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.128.13 | NOT RUN | - |
| 451 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.128.14 | NOT RUN | - |
| 452 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.128.15 | NOT RUN | - |
| 453 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.128.16 | NOT RUN | - |
| 454 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.128.17 | NOT RUN | - |
| 455 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.128.18 | NOT RUN | - |
| 456 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.2.1 | NOT RUN | - |
| 457 | dc1-leaf2c | Loopback0 Reachability | Inband Mgmt Reachability | Source: dc1-leaf2c - Vlan4085 Destination: 10.255.2.2 | NOT RUN | - |
| 458 | dc1-leaf2c | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 459 | dc1-leaf2c | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 460 | dc1-leaf2c | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 461 | dc1-leaf2c | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 462 | dc1-leaf2c | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 463 | dc1-leaf2c | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 464 | dc1-leaf2c | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 465 | dc1-leaf2c | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 466 | dc1-leaf2c | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 467 | dc1-leaf2c | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 468 | dc1-leaf2c | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 469 | dc1-leaf2c | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 470 | dc1-leaf2c | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 471 | dc1-leaf2c | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 472 | dc1-leaf2c | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 473 | dc1-spine1 | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 474 | dc1-spine1 | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 475 | dc1-spine1 | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 476 | dc1-spine1 | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 477 | dc1-spine1 | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 478 | dc1-spine1 | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 479 | dc1-spine1 | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 480 | dc1-spine1 | BFD | Verifies the health of all IPv4 BFD peers. | VerifyBFDPeersHealth | NOT RUN | - |
| 481 | dc1-spine1 | BFD | Verifies the IPv4 BFD peer's sessions and remote disc in the specified VRF. | VerifyBFDSpecificPeers | NOT RUN | - |
| 482 | dc1-spine1 | BFD | Verifies the timers of the IPv4 BFD peers in the specified VRF. | VerifyBFDPeersIntervals | NOT RUN | - |
| 483 | dc1-spine1 | BGP | Verifies the count of BGP peers. | VerifyBGPPeerCount | NOT RUN | - |
| 484 | dc1-spine1 | BGP | Verifies the health of BGP peers | VerifyBGPPeersHealth | NOT RUN | - |
| 485 | dc1-spine1 | BGP | Verifies the health of specific BGP peer(s). | VerifyBGPSpecificPeers | NOT RUN | - |
| 486 | dc1-spine1 | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 487 | dc1-spine1 | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 488 | dc1-spine1 | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 489 | dc1-spine1 | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 490 | dc1-spine1 | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 491 | dc1-spine1 | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 492 | dc1-spine1 | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 493 | dc1-spine1 | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 494 | dc1-spine1 | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 495 | dc1-spine1 | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 496 | dc1-spine1 | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 497 | dc1-spine1 | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 498 | dc1-spine1 | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 499 | dc1-spine1 | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 500 | dc1-spine1 | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 501 | dc1-spine1 | Interfaces | Verifies if Proxy ARP is enabled. | VerifyIPProxyARP | NOT RUN | - |
| 502 | dc1-spine1 | Interfaces | Verifies that all interfaces have a usage below 75%. | VerifyInterfaceUtilization | NOT RUN | - |
| 503 | dc1-spine1 | Interfaces | Verifies the global L2 MTU of all L2 interfaces. | VerifyL2MTU | NOT RUN | - |
| 504 | dc1-spine1 | Interfaces | Verifies the global L3 MTU of all L3 interfaces. | VerifyL3MTU | NOT RUN | - |
| 505 | dc1-spine1 | Interfaces | Verifies the number of loopback interfaces and their status. | VerifyLoopbackCount | NOT RUN | - |
| 506 | dc1-spine1 | Interfaces | Verifies the status of all SVIs. | VerifySVI | NOT RUN | - |
| 507 | dc1-spine1 | Interfaces | Verifies the status of the provided interfaces. | VerifyInterfacesStatus | NOT RUN | - |
| 508 | dc1-spine1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC1-LEAF1A_Ethernet1 = 'up' | NOT RUN | - |
| 509 | dc1-spine1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC1-LEAF1B_Ethernet1 = 'up' | NOT RUN | - |
| 510 | dc1-spine1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - P2P_LINK_TO_DC1-LEAF2A_Ethernet1 = 'up' | NOT RUN | - |
| 511 | dc1-spine1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - P2P_LINK_TO_DC1-LEAF2B_Ethernet1 = 'adminDown' | NOT RUN | - |
| 512 | dc1-spine1 | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - EVPN_Overlay_Peering = 'up' | NOT RUN | - |
| 513 | dc1-spine1 | Interfaces | Verifies there are no illegal LACP packets in all port channels. | VerifyIllegalLACP | NOT RUN | - |
| 514 | dc1-spine1 | Interfaces | Verifies there are no inactive ports in all port channels. | VerifyPortChannels | NOT RUN | - |
| 515 | dc1-spine1 | Interfaces | Verifies there are no interface discard counters. | VerifyInterfaceDiscards | NOT RUN | - |
| 516 | dc1-spine1 | Interfaces | Verifies there are no interface error counters. | VerifyInterfaceErrors | NOT RUN | - |
| 517 | dc1-spine1 | Interfaces | Verifies there are no interface storm-control drop counters. | VerifyStormControlDrops | NOT RUN | - |
| 518 | dc1-spine1 | Interfaces | Verifies there are no interfaces in the errdisabled state. | VerifyInterfaceErrDisabled | NOT RUN | - |
| 519 | dc1-spine1 | IP Reachability | ip reachability test p2p links | Source: dc1-spine1_Ethernet1 - Destination: dc1-leaf1a_Ethernet1 | NOT RUN | - |
| 520 | dc1-spine1 | IP Reachability | ip reachability test p2p links | Source: dc1-spine1_Ethernet2 - Destination: dc1-leaf1b_Ethernet1 | NOT RUN | - |
| 521 | dc1-spine1 | IP Reachability | ip reachability test p2p links | Source: dc1-spine1_Ethernet3 - Destination: dc1-leaf2a_Ethernet1 | NOT RUN | - |
| 522 | dc1-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc1-leaf1a_Ethernet1 | NOT RUN | - |
| 523 | dc1-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc1-leaf1b_Ethernet1 | NOT RUN | - |
| 524 | dc1-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: dc1-leaf2a_Ethernet1 | NOT RUN | - |
| 525 | dc1-spine1 | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 526 | dc1-spine1 | OSPF | Verifies all OSPF neighbors are in FULL state. | VerifyOSPFNeighborState | NOT RUN | - |
| 527 | dc1-spine1 | OSPF | Verifies the number of OSPF neighbors in FULL state is the one we expect. | VerifyOSPFNeighborCount | NOT RUN | - |
| 528 | dc1-spine1 | Routing | Verifies that the provided routes are present in the routing table of a specified VRF. | VerifyRoutingTableEntry | NOT RUN | - |
| 529 | dc1-spine1 | Routing | Verifies the configured routing protocol model. | VerifyRoutingProtocolModel | NOT RUN | - |
| 530 | dc1-spine1 | Routing | Verifies the size of the IP routing table (default VRF). Should be between the two provided thresholds. | VerifyRoutingTableSize | NOT RUN | - |
| 531 | dc1-spine1 | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 532 | dc1-spine1 | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 533 | dc1-spine1 | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 534 | dc1-spine1 | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 535 | dc1-spine1 | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 536 | dc1-spine1 | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 537 | dc1-spine1 | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 538 | dc1-spine1 | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 539 | dc1-spine1 | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 540 | dc1-spine1 | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 541 | dc1-spine1 | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 542 | dc1-spine1 | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 543 | dc1-spine1 | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 544 | dc1-spine1 | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 545 | dc1-spine2 | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 546 | dc1-spine2 | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 547 | dc1-spine2 | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 548 | dc1-spine2 | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 549 | dc1-spine2 | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 550 | dc1-spine2 | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 551 | dc1-spine2 | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 552 | dc1-spine2 | BFD | Verifies the health of all IPv4 BFD peers. | VerifyBFDPeersHealth | NOT RUN | - |
| 553 | dc1-spine2 | BFD | Verifies the IPv4 BFD peer's sessions and remote disc in the specified VRF. | VerifyBFDSpecificPeers | NOT RUN | - |
| 554 | dc1-spine2 | BFD | Verifies the timers of the IPv4 BFD peers in the specified VRF. | VerifyBFDPeersIntervals | NOT RUN | - |
| 555 | dc1-spine2 | BGP | Verifies the count of BGP peers. | VerifyBGPPeerCount | NOT RUN | - |
| 556 | dc1-spine2 | BGP | Verifies the health of BGP peers | VerifyBGPPeersHealth | NOT RUN | - |
| 557 | dc1-spine2 | BGP | Verifies the health of specific BGP peer(s). | VerifyBGPSpecificPeers | NOT RUN | - |
| 558 | dc1-spine2 | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 559 | dc1-spine2 | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 560 | dc1-spine2 | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 561 | dc1-spine2 | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 562 | dc1-spine2 | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 563 | dc1-spine2 | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 564 | dc1-spine2 | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 565 | dc1-spine2 | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 566 | dc1-spine2 | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 567 | dc1-spine2 | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 568 | dc1-spine2 | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 569 | dc1-spine2 | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 570 | dc1-spine2 | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 571 | dc1-spine2 | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 572 | dc1-spine2 | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 573 | dc1-spine2 | Interfaces | Verifies if Proxy ARP is enabled. | VerifyIPProxyARP | NOT RUN | - |
| 574 | dc1-spine2 | Interfaces | Verifies that all interfaces have a usage below 75%. | VerifyInterfaceUtilization | NOT RUN | - |
| 575 | dc1-spine2 | Interfaces | Verifies the global L2 MTU of all L2 interfaces. | VerifyL2MTU | NOT RUN | - |
| 576 | dc1-spine2 | Interfaces | Verifies the global L3 MTU of all L3 interfaces. | VerifyL3MTU | NOT RUN | - |
| 577 | dc1-spine2 | Interfaces | Verifies the number of loopback interfaces and their status. | VerifyLoopbackCount | NOT RUN | - |
| 578 | dc1-spine2 | Interfaces | Verifies the status of all SVIs. | VerifySVI | NOT RUN | - |
| 579 | dc1-spine2 | Interfaces | Verifies the status of the provided interfaces. | VerifyInterfacesStatus | NOT RUN | - |
| 580 | dc1-spine2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC1-LEAF1A_Ethernet2 = 'up' | NOT RUN | - |
| 581 | dc1-spine2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC1-LEAF1B_Ethernet2 = 'up' | NOT RUN | - |
| 582 | dc1-spine2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - P2P_LINK_TO_DC1-LEAF2A_Ethernet2 = 'up' | NOT RUN | - |
| 583 | dc1-spine2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - P2P_LINK_TO_DC1-LEAF2B_Ethernet2 = 'adminDown' | NOT RUN | - |
| 584 | dc1-spine2 | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - EVPN_Overlay_Peering = 'up' | NOT RUN | - |
| 585 | dc1-spine2 | Interfaces | Verifies there are no illegal LACP packets in all port channels. | VerifyIllegalLACP | NOT RUN | - |
| 586 | dc1-spine2 | Interfaces | Verifies there are no inactive ports in all port channels. | VerifyPortChannels | NOT RUN | - |
| 587 | dc1-spine2 | Interfaces | Verifies there are no interface discard counters. | VerifyInterfaceDiscards | NOT RUN | - |
| 588 | dc1-spine2 | Interfaces | Verifies there are no interface error counters. | VerifyInterfaceErrors | NOT RUN | - |
| 589 | dc1-spine2 | Interfaces | Verifies there are no interface storm-control drop counters. | VerifyStormControlDrops | NOT RUN | - |
| 590 | dc1-spine2 | Interfaces | Verifies there are no interfaces in the errdisabled state. | VerifyInterfaceErrDisabled | NOT RUN | - |
| 591 | dc1-spine2 | IP Reachability | ip reachability test p2p links | Source: dc1-spine2_Ethernet1 - Destination: dc1-leaf1a_Ethernet2 | NOT RUN | - |
| 592 | dc1-spine2 | IP Reachability | ip reachability test p2p links | Source: dc1-spine2_Ethernet2 - Destination: dc1-leaf1b_Ethernet2 | NOT RUN | - |
| 593 | dc1-spine2 | IP Reachability | ip reachability test p2p links | Source: dc1-spine2_Ethernet3 - Destination: dc1-leaf2a_Ethernet2 | NOT RUN | - |
| 594 | dc1-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc1-leaf1a_Ethernet2 | NOT RUN | - |
| 595 | dc1-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc1-leaf1b_Ethernet2 | NOT RUN | - |
| 596 | dc1-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: dc1-leaf2a_Ethernet2 | NOT RUN | - |
| 597 | dc1-spine2 | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 598 | dc1-spine2 | OSPF | Verifies all OSPF neighbors are in FULL state. | VerifyOSPFNeighborState | NOT RUN | - |
| 599 | dc1-spine2 | OSPF | Verifies the number of OSPF neighbors in FULL state is the one we expect. | VerifyOSPFNeighborCount | NOT RUN | - |
| 600 | dc1-spine2 | Routing | Verifies that the provided routes are present in the routing table of a specified VRF. | VerifyRoutingTableEntry | NOT RUN | - |
| 601 | dc1-spine2 | Routing | Verifies the configured routing protocol model. | VerifyRoutingProtocolModel | NOT RUN | - |
| 602 | dc1-spine2 | Routing | Verifies the size of the IP routing table (default VRF). Should be between the two provided thresholds. | VerifyRoutingTableSize | NOT RUN | - |
| 603 | dc1-spine2 | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 604 | dc1-spine2 | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 605 | dc1-spine2 | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 606 | dc1-spine2 | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 607 | dc1-spine2 | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 608 | dc1-spine2 | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 609 | dc1-spine2 | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 610 | dc1-spine2 | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 611 | dc1-spine2 | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 612 | dc1-spine2 | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 613 | dc1-spine2 | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 614 | dc1-spine2 | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 615 | dc1-spine2 | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 616 | dc1-spine2 | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 617 | dc1-wan1 | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 618 | dc1-wan1 | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 619 | dc1-wan1 | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 620 | dc1-wan1 | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 621 | dc1-wan1 | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 622 | dc1-wan1 | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 623 | dc1-wan1 | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 624 | dc1-wan1 | BGP | Verifies the configured routing protocol model. | Routing protocol model: multi-agent | NOT RUN | - |
| 625 | dc1-wan1 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.0 | NOT RUN | - |
| 626 | dc1-wan1 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.2 | NOT RUN | - |
| 627 | dc1-wan1 | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 628 | dc1-wan1 | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 629 | dc1-wan1 | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 630 | dc1-wan1 | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 631 | dc1-wan1 | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 632 | dc1-wan1 | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 633 | dc1-wan1 | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 634 | dc1-wan1 | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 635 | dc1-wan1 | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 636 | dc1-wan1 | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 637 | dc1-wan1 | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 638 | dc1-wan1 | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 639 | dc1-wan1 | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 640 | dc1-wan1 | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 641 | dc1-wan1 | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 642 | dc1-wan1 | Interfaces | Verifies the status of the provided interfaces. | Interface Dps1 - DPS Interface = 'up' | NOT RUN | - |
| 643 | dc1-wan1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC1-LEAF1A_Ethernet6 = 'up' | NOT RUN | - |
| 644 | dc1-wan1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC1-LEAF1B_Ethernet6 = 'up' | NOT RUN | - |
| 645 | dc1-wan1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - mpls-sp-1_DC1-MPLS-3 = 'up' | NOT RUN | - |
| 646 | dc1-wan1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - isp-1_DC1-INET-3 = 'up' | NOT RUN | - |
| 647 | dc1-wan1 | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - Router_ID = 'up' | NOT RUN | - |
| 648 | dc1-wan1 | Interfaces | Verifies the status of the provided interfaces. | Interface Vxlan1 = 'up' | NOT RUN | - |
| 649 | dc1-wan1 | IP Reachability | ip reachability test p2p links | Source: dc1-wan1_Ethernet1 - Destination: dc1-leaf1a_Ethernet6 | NOT RUN | - |
| 650 | dc1-wan1 | IP Reachability | ip reachability test p2p links | Source: dc1-wan1_Ethernet2 - Destination: dc1-leaf1b_Ethernet6 | NOT RUN | - |
| 651 | dc1-wan1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc1-leaf1a_Ethernet6 | NOT RUN | - |
| 652 | dc1-wan1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc1-leaf1b_Ethernet6 | NOT RUN | - |
| 653 | dc1-wan1 | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 654 | dc1-wan1 | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 655 | dc1-wan1 | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 656 | dc1-wan1 | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 657 | dc1-wan1 | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 658 | dc1-wan1 | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 659 | dc1-wan1 | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 660 | dc1-wan1 | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 661 | dc1-wan1 | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 662 | dc1-wan1 | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 663 | dc1-wan1 | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 664 | dc1-wan1 | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 665 | dc1-wan1 | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 666 | dc1-wan1 | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 667 | dc1-wan1 | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 668 | dc1-wan2 | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 669 | dc1-wan2 | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 670 | dc1-wan2 | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 671 | dc1-wan2 | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 672 | dc1-wan2 | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 673 | dc1-wan2 | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 674 | dc1-wan2 | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 675 | dc1-wan2 | BGP | Verifies the configured routing protocol model. | Routing protocol model: multi-agent | NOT RUN | - |
| 676 | dc1-wan2 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.4 | NOT RUN | - |
| 677 | dc1-wan2 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.6 | NOT RUN | - |
| 678 | dc1-wan2 | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 679 | dc1-wan2 | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 680 | dc1-wan2 | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 681 | dc1-wan2 | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 682 | dc1-wan2 | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 683 | dc1-wan2 | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 684 | dc1-wan2 | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 685 | dc1-wan2 | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 686 | dc1-wan2 | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 687 | dc1-wan2 | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 688 | dc1-wan2 | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 689 | dc1-wan2 | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 690 | dc1-wan2 | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 691 | dc1-wan2 | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 692 | dc1-wan2 | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 693 | dc1-wan2 | Interfaces | Verifies the status of the provided interfaces. | Interface Dps1 - DPS Interface = 'up' | NOT RUN | - |
| 694 | dc1-wan2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC1-LEAF1A_Ethernet7 = 'up' | NOT RUN | - |
| 695 | dc1-wan2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC1-LEAF1B_Ethernet7 = 'up' | NOT RUN | - |
| 696 | dc1-wan2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - mpls-sp-1_DC1-MPLS-4 = 'up' | NOT RUN | - |
| 697 | dc1-wan2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - isp-1_DC1-INET-4 = 'up' | NOT RUN | - |
| 698 | dc1-wan2 | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - Router_ID = 'up' | NOT RUN | - |
| 699 | dc1-wan2 | Interfaces | Verifies the status of the provided interfaces. | Interface Vxlan1 = 'up' | NOT RUN | - |
| 700 | dc1-wan2 | IP Reachability | ip reachability test p2p links | Source: dc1-wan2_Ethernet1 - Destination: dc1-leaf1a_Ethernet7 | NOT RUN | - |
| 701 | dc1-wan2 | IP Reachability | ip reachability test p2p links | Source: dc1-wan2_Ethernet2 - Destination: dc1-leaf1b_Ethernet7 | NOT RUN | - |
| 702 | dc1-wan2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc1-leaf1a_Ethernet7 | NOT RUN | - |
| 703 | dc1-wan2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc1-leaf1b_Ethernet7 | NOT RUN | - |
| 704 | dc1-wan2 | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 705 | dc1-wan2 | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 706 | dc1-wan2 | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 707 | dc1-wan2 | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 708 | dc1-wan2 | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 709 | dc1-wan2 | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 710 | dc1-wan2 | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 711 | dc1-wan2 | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 712 | dc1-wan2 | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 713 | dc1-wan2 | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 714 | dc1-wan2 | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 715 | dc1-wan2 | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 716 | dc1-wan2 | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 717 | dc1-wan2 | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 718 | dc1-wan2 | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 719 | dc2-leaf1a | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 720 | dc2-leaf1a | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 721 | dc2-leaf1a | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 722 | dc2-leaf1a | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 723 | dc2-leaf1a | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 724 | dc2-leaf1a | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 725 | dc2-leaf1a | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 726 | dc2-leaf1a | BGP | Verifies the configured routing protocol model. | Routing protocol model: multi-agent | NOT RUN | - |
| 727 | dc2-leaf1a | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.11 | NOT RUN | - |
| 728 | dc2-leaf1a | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.12 | NOT RUN | - |
| 729 | dc2-leaf1a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.129.117 | NOT RUN | - |
| 730 | dc2-leaf1a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.104 | NOT RUN | - |
| 731 | dc2-leaf1a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.106 | NOT RUN | - |
| 732 | dc2-leaf1a | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 733 | dc2-leaf1a | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 734 | dc2-leaf1a | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 735 | dc2-leaf1a | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 736 | dc2-leaf1a | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 737 | dc2-leaf1a | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 738 | dc2-leaf1a | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 739 | dc2-leaf1a | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 740 | dc2-leaf1a | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 741 | dc2-leaf1a | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 742 | dc2-leaf1a | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 743 | dc2-leaf1a | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 744 | dc2-leaf1a | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 745 | dc2-leaf1a | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 746 | dc2-leaf1a | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 747 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC2-SPINE1_Ethernet1 = 'up' | NOT RUN | - |
| 748 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC2-SPINE2_Ethernet1 = 'up' | NOT RUN | - |
| 749 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - MLAG_PEER_dc2-leaf1b_Ethernet3 = 'up' | NOT RUN | - |
| 750 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - MLAG_PEER_dc2-leaf1b_Ethernet4 = 'up' | NOT RUN | - |
| 751 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet5 - dc2-leaf1-server1_PCI1 = 'up' | NOT RUN | - |
| 752 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet8 - DC2-LEAF1C_Ethernet1 = 'up' | NOT RUN | - |
| 753 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - EVPN_Overlay_Peering = 'up' | NOT RUN | - |
| 754 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback1 - VTEP_VXLAN_Tunnel_Source = 'up' | NOT RUN | - |
| 755 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback10 - VRF10_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 756 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback11 - VRF11_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 757 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel3 - MLAG_PEER_dc2-leaf1b_Po3 = 'up' | NOT RUN | - |
| 758 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel5 - dc2-leaf1-server1_PortChannel dc2-leaf1-server1 = 'up' | NOT RUN | - |
| 759 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel8 - DC2-LEAF1C_Po1 = 'up' | NOT RUN | - |
| 760 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan11 - VRF10_VLAN11 = 'up' | NOT RUN | - |
| 761 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan12 - VRF10_VLAN12 = 'up' | NOT RUN | - |
| 762 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan21 - VRF11_VLAN21 = 'up' | NOT RUN | - |
| 763 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan22 - VRF11_VLAN22 = 'up' | NOT RUN | - |
| 764 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF10 = 'up' | NOT RUN | - |
| 765 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3010 - MLAG_PEER_L3_iBGP: vrf VRF11 = 'up' | NOT RUN | - |
| 766 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4093 - MLAG_PEER_L3_PEERING = 'up' | NOT RUN | - |
| 767 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4094 - MLAG_PEER = 'up' | NOT RUN | - |
| 768 | dc2-leaf1a | Interfaces | Verifies the status of the provided interfaces. | Interface Vxlan1 = 'up' | NOT RUN | - |
| 769 | dc2-leaf1a | IP Reachability | ip reachability test p2p links | Source: dc2-leaf1a_Ethernet1 - Destination: dc2-spine1_Ethernet1 | NOT RUN | - |
| 770 | dc2-leaf1a | IP Reachability | ip reachability test p2p links | Source: dc2-leaf1a_Ethernet2 - Destination: dc2-spine2_Ethernet1 | NOT RUN | - |
| 771 | dc2-leaf1a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc2-spine1_Ethernet1 | NOT RUN | - |
| 772 | dc2-leaf1a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc2-spine2_Ethernet1 | NOT RUN | - |
| 773 | dc2-leaf1a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: dc2-leaf1b_Ethernet3 | NOT RUN | - |
| 774 | dc2-leaf1a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: dc2-leaf1b_Ethernet4 | NOT RUN | - |
| 775 | dc2-leaf1a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet8 - remote: dc2-leaf1c_Ethernet1 | NOT RUN | - |
| 776 | dc2-leaf1a | Logging | This test verifies there are no syslog messages with a severity of ERRORS or higher. | VerifyLoggingWarning | NOT RUN | - |
| 777 | dc2-leaf1a | Logging | Verifies if AAA accounting logs are generated. | VerifyLoggingAccounting | NOT RUN | - |
| 778 | dc2-leaf1a | Logging | Verifies if logging persistent is enabled and logs are saved in flash. | VerifyLoggingPersistent | NOT RUN | - |
| 779 | dc2-leaf1a | Logging | Verifies if logs are generated with the appropriate timestamp. | VerifyLoggingTimestamp | NOT RUN | - |
| 780 | dc2-leaf1a | Logging | Verifies if logs are generated with the device FQDN. | VerifyLoggingHostname | NOT RUN | - |
| 781 | dc2-leaf1a | Logging | Verifies if logs are generated. | VerifyLoggingLogsGeneration | NOT RUN | - |
| 782 | dc2-leaf1a | Logging | Verifies logging hosts (syslog servers) for a specified VRF. | VerifyLoggingHosts | NOT RUN | - |
| 783 | dc2-leaf1a | Logging | Verifies logging source-interface for a specified VRF. | VerifyLoggingSourceInt | NOT RUN | - |
| 784 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.0.1 | NOT RUN | - |
| 785 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.0.2 | NOT RUN | - |
| 786 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.0.3 | NOT RUN | - |
| 787 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.0.4 | NOT RUN | - |
| 788 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.0.5 | NOT RUN | - |
| 789 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.128.11 | NOT RUN | - |
| 790 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.128.12 | NOT RUN | - |
| 791 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.128.13 | NOT RUN | - |
| 792 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.128.14 | NOT RUN | - |
| 793 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.128.15 | NOT RUN | - |
| 794 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.128.16 | NOT RUN | - |
| 795 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.128.17 | NOT RUN | - |
| 796 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.128.18 | NOT RUN | - |
| 797 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.2.1 | NOT RUN | - |
| 798 | dc2-leaf1a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1a - 10.255.128.13/32 Destination: 10.255.2.2 | NOT RUN | - |
| 799 | dc2-leaf1a | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 800 | dc2-leaf1a | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 801 | dc2-leaf1a | MLAG | Verifies the MLAG dual-primary detection parameters. | VerifyMlagDualPrimary | NOT RUN | - |
| 802 | dc2-leaf1a | MLAG | Verifies the MLAG reload-delay parameters. | VerifyMlagReloadDelay | NOT RUN | - |
| 803 | dc2-leaf1a | MLAG | Verifies there are no inactive or active-partial MLAG ports. | VerifyMlagInterfaces | NOT RUN | - |
| 804 | dc2-leaf1a | MLAG | Verifies there are no MLAG config-sanity inconsistencies. | VerifyMlagConfigSanity | NOT RUN | - |
| 805 | dc2-leaf1a | Multicast, IGMP | Verifies the IGMP snooping configuration for some VLANs. | VerifyIGMPSnoopingVlans | NOT RUN | - |
| 806 | dc2-leaf1a | Multicast, IGMP | Verifies the IGMP snooping global configuration. | VerifyIGMPSnoopingGlobal | NOT RUN | - |
| 807 | dc2-leaf1a | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 808 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.0.1 | NOT RUN | - |
| 809 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.0.2 | NOT RUN | - |
| 810 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.0.3 | NOT RUN | - |
| 811 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.0.4 | NOT RUN | - |
| 812 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.0.5 | NOT RUN | - |
| 813 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.11 | NOT RUN | - |
| 814 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.12 | NOT RUN | - |
| 815 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.13 | NOT RUN | - |
| 816 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.14 | NOT RUN | - |
| 817 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.15 | NOT RUN | - |
| 818 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.16 | NOT RUN | - |
| 819 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.17 | NOT RUN | - |
| 820 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.128.18 | NOT RUN | - |
| 821 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.2.1 | NOT RUN | - |
| 822 | dc2-leaf1a | Routing Table | Remote Lo0 address | 10.255.2.2 | NOT RUN | - |
| 823 | dc2-leaf1a | Routing Table | Remote VTEP address | 10.255.1.3 | NOT RUN | - |
| 824 | dc2-leaf1a | Routing Table | Remote VTEP address | 10.255.1.5 | NOT RUN | - |
| 825 | dc2-leaf1a | Routing Table | Remote VTEP address | 10.255.129.13 | NOT RUN | - |
| 826 | dc2-leaf1a | Routing Table | Remote VTEP address | 10.255.129.15 | NOT RUN | - |
| 827 | dc2-leaf1a | Routing Table | Remote VTEP address | 10.255.129.17 | NOT RUN | - |
| 828 | dc2-leaf1a | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 829 | dc2-leaf1a | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 830 | dc2-leaf1a | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 831 | dc2-leaf1a | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 832 | dc2-leaf1a | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 833 | dc2-leaf1a | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 834 | dc2-leaf1a | STP | Verifies that all interfaces are forwarding for a provided list of VLAN(s). | VerifySTPForwardingPorts | NOT RUN | - |
| 835 | dc2-leaf1a | STP | Verifies the configured STP mode for a provided list of VLAN(s). | VerifySTPMode | NOT RUN | - |
| 836 | dc2-leaf1a | STP | Verifies the STP root priority for a provided list of VLAN or MST instance ID(s). | VerifySTPRootPriority | NOT RUN | - |
| 837 | dc2-leaf1a | STP | Verifies there is no errors in STP BPDU packets. | VerifySTPCounters | NOT RUN | - |
| 838 | dc2-leaf1a | STP | Verifies there is no STP blocked ports. | VerifySTPBlockedPorts | NOT RUN | - |
| 839 | dc2-leaf1a | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 840 | dc2-leaf1a | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 841 | dc2-leaf1a | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 842 | dc2-leaf1a | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 843 | dc2-leaf1a | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 844 | dc2-leaf1a | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 845 | dc2-leaf1a | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 846 | dc2-leaf1a | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 847 | dc2-leaf1b | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 848 | dc2-leaf1b | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 849 | dc2-leaf1b | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 850 | dc2-leaf1b | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 851 | dc2-leaf1b | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 852 | dc2-leaf1b | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 853 | dc2-leaf1b | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 854 | dc2-leaf1b | BGP | Verifies the configured routing protocol model. | Routing protocol model: multi-agent | NOT RUN | - |
| 855 | dc2-leaf1b | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.11 | NOT RUN | - |
| 856 | dc2-leaf1b | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.12 | NOT RUN | - |
| 857 | dc2-leaf1b | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.129.116 | NOT RUN | - |
| 858 | dc2-leaf1b | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.108 | NOT RUN | - |
| 859 | dc2-leaf1b | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.110 | NOT RUN | - |
| 860 | dc2-leaf1b | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 861 | dc2-leaf1b | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 862 | dc2-leaf1b | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 863 | dc2-leaf1b | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 864 | dc2-leaf1b | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 865 | dc2-leaf1b | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 866 | dc2-leaf1b | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 867 | dc2-leaf1b | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 868 | dc2-leaf1b | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 869 | dc2-leaf1b | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 870 | dc2-leaf1b | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 871 | dc2-leaf1b | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 872 | dc2-leaf1b | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 873 | dc2-leaf1b | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 874 | dc2-leaf1b | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 875 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC2-SPINE1_Ethernet2 = 'up' | NOT RUN | - |
| 876 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC2-SPINE2_Ethernet2 = 'up' | NOT RUN | - |
| 877 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - MLAG_PEER_dc2-leaf1a_Ethernet3 = 'up' | NOT RUN | - |
| 878 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - MLAG_PEER_dc2-leaf1a_Ethernet4 = 'up' | NOT RUN | - |
| 879 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet5 - dc2-leaf1-server1_PCI2 = 'up' | NOT RUN | - |
| 880 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet8 - DC2-LEAF1C_Ethernet2 = 'up' | NOT RUN | - |
| 881 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - EVPN_Overlay_Peering = 'up' | NOT RUN | - |
| 882 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback1 - VTEP_VXLAN_Tunnel_Source = 'up' | NOT RUN | - |
| 883 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback10 - VRF10_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 884 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback11 - VRF11_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 885 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel3 - MLAG_PEER_dc2-leaf1a_Po3 = 'up' | NOT RUN | - |
| 886 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel5 - dc2-leaf1-server1_PortChannel dc2-leaf1-server1 = 'up' | NOT RUN | - |
| 887 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel8 - DC2-LEAF1C_Po1 = 'up' | NOT RUN | - |
| 888 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan11 - VRF10_VLAN11 = 'up' | NOT RUN | - |
| 889 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan12 - VRF10_VLAN12 = 'up' | NOT RUN | - |
| 890 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan21 - VRF11_VLAN21 = 'up' | NOT RUN | - |
| 891 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan22 - VRF11_VLAN22 = 'up' | NOT RUN | - |
| 892 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF10 = 'up' | NOT RUN | - |
| 893 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3010 - MLAG_PEER_L3_iBGP: vrf VRF11 = 'up' | NOT RUN | - |
| 894 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4093 - MLAG_PEER_L3_PEERING = 'up' | NOT RUN | - |
| 895 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4094 - MLAG_PEER = 'up' | NOT RUN | - |
| 896 | dc2-leaf1b | Interfaces | Verifies the status of the provided interfaces. | Interface Vxlan1 = 'up' | NOT RUN | - |
| 897 | dc2-leaf1b | IP Reachability | ip reachability test p2p links | Source: dc2-leaf1b_Ethernet1 - Destination: dc2-spine1_Ethernet2 | NOT RUN | - |
| 898 | dc2-leaf1b | IP Reachability | ip reachability test p2p links | Source: dc2-leaf1b_Ethernet2 - Destination: dc2-spine2_Ethernet2 | NOT RUN | - |
| 899 | dc2-leaf1b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc2-spine1_Ethernet2 | NOT RUN | - |
| 900 | dc2-leaf1b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc2-spine2_Ethernet2 | NOT RUN | - |
| 901 | dc2-leaf1b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: dc2-leaf1a_Ethernet3 | NOT RUN | - |
| 902 | dc2-leaf1b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: dc2-leaf1a_Ethernet4 | NOT RUN | - |
| 903 | dc2-leaf1b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet8 - remote: dc2-leaf1c_Ethernet2 | NOT RUN | - |
| 904 | dc2-leaf1b | Logging | This test verifies there are no syslog messages with a severity of ERRORS or higher. | VerifyLoggingWarning | NOT RUN | - |
| 905 | dc2-leaf1b | Logging | Verifies if AAA accounting logs are generated. | VerifyLoggingAccounting | NOT RUN | - |
| 906 | dc2-leaf1b | Logging | Verifies if logging persistent is enabled and logs are saved in flash. | VerifyLoggingPersistent | NOT RUN | - |
| 907 | dc2-leaf1b | Logging | Verifies if logs are generated with the appropriate timestamp. | VerifyLoggingTimestamp | NOT RUN | - |
| 908 | dc2-leaf1b | Logging | Verifies if logs are generated with the device FQDN. | VerifyLoggingHostname | NOT RUN | - |
| 909 | dc2-leaf1b | Logging | Verifies if logs are generated. | VerifyLoggingLogsGeneration | NOT RUN | - |
| 910 | dc2-leaf1b | Logging | Verifies logging hosts (syslog servers) for a specified VRF. | VerifyLoggingHosts | NOT RUN | - |
| 911 | dc2-leaf1b | Logging | Verifies logging source-interface for a specified VRF. | VerifyLoggingSourceInt | NOT RUN | - |
| 912 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.0.1 | NOT RUN | - |
| 913 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.0.2 | NOT RUN | - |
| 914 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.0.3 | NOT RUN | - |
| 915 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.0.4 | NOT RUN | - |
| 916 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.0.5 | NOT RUN | - |
| 917 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.128.11 | NOT RUN | - |
| 918 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.128.12 | NOT RUN | - |
| 919 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.128.13 | NOT RUN | - |
| 920 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.128.14 | NOT RUN | - |
| 921 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.128.15 | NOT RUN | - |
| 922 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.128.16 | NOT RUN | - |
| 923 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.128.17 | NOT RUN | - |
| 924 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.128.18 | NOT RUN | - |
| 925 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.2.1 | NOT RUN | - |
| 926 | dc2-leaf1b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf1b - 10.255.128.14/32 Destination: 10.255.2.2 | NOT RUN | - |
| 927 | dc2-leaf1b | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 928 | dc2-leaf1b | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 929 | dc2-leaf1b | MLAG | Verifies the MLAG dual-primary detection parameters. | VerifyMlagDualPrimary | NOT RUN | - |
| 930 | dc2-leaf1b | MLAG | Verifies the MLAG reload-delay parameters. | VerifyMlagReloadDelay | NOT RUN | - |
| 931 | dc2-leaf1b | MLAG | Verifies there are no inactive or active-partial MLAG ports. | VerifyMlagInterfaces | NOT RUN | - |
| 932 | dc2-leaf1b | MLAG | Verifies there are no MLAG config-sanity inconsistencies. | VerifyMlagConfigSanity | NOT RUN | - |
| 933 | dc2-leaf1b | Multicast, IGMP | Verifies the IGMP snooping configuration for some VLANs. | VerifyIGMPSnoopingVlans | NOT RUN | - |
| 934 | dc2-leaf1b | Multicast, IGMP | Verifies the IGMP snooping global configuration. | VerifyIGMPSnoopingGlobal | NOT RUN | - |
| 935 | dc2-leaf1b | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 936 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.0.1 | NOT RUN | - |
| 937 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.0.2 | NOT RUN | - |
| 938 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.0.3 | NOT RUN | - |
| 939 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.0.4 | NOT RUN | - |
| 940 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.0.5 | NOT RUN | - |
| 941 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.11 | NOT RUN | - |
| 942 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.12 | NOT RUN | - |
| 943 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.13 | NOT RUN | - |
| 944 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.14 | NOT RUN | - |
| 945 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.15 | NOT RUN | - |
| 946 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.16 | NOT RUN | - |
| 947 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.17 | NOT RUN | - |
| 948 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.128.18 | NOT RUN | - |
| 949 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.2.1 | NOT RUN | - |
| 950 | dc2-leaf1b | Routing Table | Remote Lo0 address | 10.255.2.2 | NOT RUN | - |
| 951 | dc2-leaf1b | Routing Table | Remote VTEP address | 10.255.1.3 | NOT RUN | - |
| 952 | dc2-leaf1b | Routing Table | Remote VTEP address | 10.255.1.5 | NOT RUN | - |
| 953 | dc2-leaf1b | Routing Table | Remote VTEP address | 10.255.129.13 | NOT RUN | - |
| 954 | dc2-leaf1b | Routing Table | Remote VTEP address | 10.255.129.15 | NOT RUN | - |
| 955 | dc2-leaf1b | Routing Table | Remote VTEP address | 10.255.129.17 | NOT RUN | - |
| 956 | dc2-leaf1b | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 957 | dc2-leaf1b | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 958 | dc2-leaf1b | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 959 | dc2-leaf1b | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 960 | dc2-leaf1b | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 961 | dc2-leaf1b | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 962 | dc2-leaf1b | STP | Verifies that all interfaces are forwarding for a provided list of VLAN(s). | VerifySTPForwardingPorts | NOT RUN | - |
| 963 | dc2-leaf1b | STP | Verifies the configured STP mode for a provided list of VLAN(s). | VerifySTPMode | NOT RUN | - |
| 964 | dc2-leaf1b | STP | Verifies the STP root priority for a provided list of VLAN or MST instance ID(s). | VerifySTPRootPriority | NOT RUN | - |
| 965 | dc2-leaf1b | STP | Verifies there is no errors in STP BPDU packets. | VerifySTPCounters | NOT RUN | - |
| 966 | dc2-leaf1b | STP | Verifies there is no STP blocked ports. | VerifySTPBlockedPorts | NOT RUN | - |
| 967 | dc2-leaf1b | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 968 | dc2-leaf1b | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 969 | dc2-leaf1b | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 970 | dc2-leaf1b | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 971 | dc2-leaf1b | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 972 | dc2-leaf1b | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 973 | dc2-leaf1b | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 974 | dc2-leaf1b | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 975 | dc2-leaf1c | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 976 | dc2-leaf1c | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 977 | dc2-leaf1c | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 978 | dc2-leaf1c | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 979 | dc2-leaf1c | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 980 | dc2-leaf1c | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 981 | dc2-leaf1c | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 982 | dc2-leaf1c | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 983 | dc2-leaf1c | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 984 | dc2-leaf1c | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 985 | dc2-leaf1c | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 986 | dc2-leaf1c | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 987 | dc2-leaf1c | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 988 | dc2-leaf1c | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 989 | dc2-leaf1c | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 990 | dc2-leaf1c | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 991 | dc2-leaf1c | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 992 | dc2-leaf1c | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 993 | dc2-leaf1c | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 994 | dc2-leaf1c | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 995 | dc2-leaf1c | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 996 | dc2-leaf1c | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 997 | dc2-leaf1c | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - DC2-LEAF1A_Ethernet8 = 'up' | NOT RUN | - |
| 998 | dc2-leaf1c | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - DC2-LEAF1B_Ethernet8 = 'up' | NOT RUN | - |
| 999 | dc2-leaf1c | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet5 - dc2-leaf1-server1_iLO = 'up' | NOT RUN | - |
| 1000 | dc2-leaf1c | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel1 - DC2_L3_LEAF1_Po8 = 'up' | NOT RUN | - |
| 1001 | dc2-leaf1c | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc2-leaf1a_Ethernet8 | NOT RUN | - |
| 1002 | dc2-leaf1c | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc2-leaf1b_Ethernet8 | NOT RUN | - |
| 1003 | dc2-leaf1c | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 1004 | dc2-leaf1c | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 1005 | dc2-leaf1c | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 1006 | dc2-leaf1c | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 1007 | dc2-leaf1c | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 1008 | dc2-leaf1c | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 1009 | dc2-leaf1c | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 1010 | dc2-leaf1c | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 1011 | dc2-leaf1c | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 1012 | dc2-leaf1c | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 1013 | dc2-leaf1c | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 1014 | dc2-leaf1c | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 1015 | dc2-leaf1c | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 1016 | dc2-leaf1c | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 1017 | dc2-leaf1c | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 1018 | dc2-leaf2a | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 1019 | dc2-leaf2a | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 1020 | dc2-leaf2a | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 1021 | dc2-leaf2a | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 1022 | dc2-leaf2a | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 1023 | dc2-leaf2a | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 1024 | dc2-leaf2a | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 1025 | dc2-leaf2a | BGP | Verifies the configured routing protocol model. | Routing protocol model: multi-agent | NOT RUN | - |
| 1026 | dc2-leaf2a | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.0.5 | NOT RUN | - |
| 1027 | dc2-leaf2a | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.11 | NOT RUN | - |
| 1028 | dc2-leaf2a | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.12 | NOT RUN | - |
| 1029 | dc2-leaf2a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.129.121 | NOT RUN | - |
| 1030 | dc2-leaf2a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.112 | NOT RUN | - |
| 1031 | dc2-leaf2a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.114 | NOT RUN | - |
| 1032 | dc2-leaf2a | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 192.168.100.0 | NOT RUN | - |
| 1033 | dc2-leaf2a | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 1034 | dc2-leaf2a | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 1035 | dc2-leaf2a | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 1036 | dc2-leaf2a | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 1037 | dc2-leaf2a | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1038 | dc2-leaf2a | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1039 | dc2-leaf2a | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1040 | dc2-leaf2a | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1041 | dc2-leaf2a | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1042 | dc2-leaf2a | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1043 | dc2-leaf2a | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1044 | dc2-leaf2a | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1045 | dc2-leaf2a | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 1046 | dc2-leaf2a | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 1047 | dc2-leaf2a | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 1048 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC2-SPINE1_Ethernet3 = 'up' | NOT RUN | - |
| 1049 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC2-SPINE2_Ethernet3 = 'up' | NOT RUN | - |
| 1050 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - MLAG_PEER_dc2-leaf2b_Ethernet3 = 'up' | NOT RUN | - |
| 1051 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - MLAG_PEER_dc2-leaf2b_Ethernet4 = 'up' | NOT RUN | - |
| 1052 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet5 - dc2-leaf2-server1_PCI1 = 'up' | NOT RUN | - |
| 1053 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet6 - P2P_LINK_TO_dc1-leaf2a_Ethernet6 = 'up' | NOT RUN | - |
| 1054 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet8 - DC2-LEAF2C_Ethernet1 = 'up' | NOT RUN | - |
| 1055 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - EVPN_Overlay_Peering = 'up' | NOT RUN | - |
| 1056 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback1 - VTEP_VXLAN_Tunnel_Source = 'up' | NOT RUN | - |
| 1057 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback10 - VRF10_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 1058 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback11 - VRF11_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 1059 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel3 - MLAG_PEER_dc2-leaf2b_Po3 = 'up' | NOT RUN | - |
| 1060 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel5 - dc2-leaf2-server1_PortChannel dc2-leaf2-server1 = 'up' | NOT RUN | - |
| 1061 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel8 - DC2-LEAF2C_Po1 = 'up' | NOT RUN | - |
| 1062 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan11 - VRF10_VLAN11 = 'up' | NOT RUN | - |
| 1063 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan12 - VRF10_VLAN12 = 'up' | NOT RUN | - |
| 1064 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan21 - VRF11_VLAN21 = 'up' | NOT RUN | - |
| 1065 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan22 - VRF11_VLAN22 = 'up' | NOT RUN | - |
| 1066 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF10 = 'up' | NOT RUN | - |
| 1067 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3010 - MLAG_PEER_L3_iBGP: vrf VRF11 = 'up' | NOT RUN | - |
| 1068 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4093 - MLAG_PEER_L3_PEERING = 'up' | NOT RUN | - |
| 1069 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4094 - MLAG_PEER = 'up' | NOT RUN | - |
| 1070 | dc2-leaf2a | Interfaces | Verifies the status of the provided interfaces. | Interface Vxlan1 = 'up' | NOT RUN | - |
| 1071 | dc2-leaf2a | IP Reachability | ip reachability test p2p links | Source: dc2-leaf2a_Ethernet1 - Destination: dc2-spine1_Ethernet3 | NOT RUN | - |
| 1072 | dc2-leaf2a | IP Reachability | ip reachability test p2p links | Source: dc2-leaf2a_Ethernet2 - Destination: dc2-spine2_Ethernet3 | NOT RUN | - |
| 1073 | dc2-leaf2a | IP Reachability | ip reachability test p2p links | Source: dc2-leaf2a_Ethernet6 - Destination: dc1-leaf2a_Ethernet6 | NOT RUN | - |
| 1074 | dc2-leaf2a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc2-spine1_Ethernet3 | NOT RUN | - |
| 1075 | dc2-leaf2a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc2-spine2_Ethernet3 | NOT RUN | - |
| 1076 | dc2-leaf2a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: dc2-leaf2b_Ethernet3 | NOT RUN | - |
| 1077 | dc2-leaf2a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: dc2-leaf2b_Ethernet4 | NOT RUN | - |
| 1078 | dc2-leaf2a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: dc1-leaf2a_Ethernet6 | NOT RUN | - |
| 1079 | dc2-leaf2a | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet8 - remote: dc2-leaf2c_Ethernet1 | NOT RUN | - |
| 1080 | dc2-leaf2a | Logging | This test verifies there are no syslog messages with a severity of ERRORS or higher. | VerifyLoggingWarning | NOT RUN | - |
| 1081 | dc2-leaf2a | Logging | Verifies if AAA accounting logs are generated. | VerifyLoggingAccounting | NOT RUN | - |
| 1082 | dc2-leaf2a | Logging | Verifies if logging persistent is enabled and logs are saved in flash. | VerifyLoggingPersistent | NOT RUN | - |
| 1083 | dc2-leaf2a | Logging | Verifies if logs are generated with the appropriate timestamp. | VerifyLoggingTimestamp | NOT RUN | - |
| 1084 | dc2-leaf2a | Logging | Verifies if logs are generated with the device FQDN. | VerifyLoggingHostname | NOT RUN | - |
| 1085 | dc2-leaf2a | Logging | Verifies if logs are generated. | VerifyLoggingLogsGeneration | NOT RUN | - |
| 1086 | dc2-leaf2a | Logging | Verifies logging hosts (syslog servers) for a specified VRF. | VerifyLoggingHosts | NOT RUN | - |
| 1087 | dc2-leaf2a | Logging | Verifies logging source-interface for a specified VRF. | VerifyLoggingSourceInt | NOT RUN | - |
| 1088 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.0.1 | NOT RUN | - |
| 1089 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.0.2 | NOT RUN | - |
| 1090 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.0.3 | NOT RUN | - |
| 1091 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.0.4 | NOT RUN | - |
| 1092 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.0.5 | NOT RUN | - |
| 1093 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.128.11 | NOT RUN | - |
| 1094 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.128.12 | NOT RUN | - |
| 1095 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.128.13 | NOT RUN | - |
| 1096 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.128.14 | NOT RUN | - |
| 1097 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.128.15 | NOT RUN | - |
| 1098 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.128.16 | NOT RUN | - |
| 1099 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.128.17 | NOT RUN | - |
| 1100 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.128.18 | NOT RUN | - |
| 1101 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.2.1 | NOT RUN | - |
| 1102 | dc2-leaf2a | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2a - 10.255.128.15/32 Destination: 10.255.2.2 | NOT RUN | - |
| 1103 | dc2-leaf2a | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 1104 | dc2-leaf2a | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 1105 | dc2-leaf2a | MLAG | Verifies the MLAG dual-primary detection parameters. | VerifyMlagDualPrimary | NOT RUN | - |
| 1106 | dc2-leaf2a | MLAG | Verifies the MLAG reload-delay parameters. | VerifyMlagReloadDelay | NOT RUN | - |
| 1107 | dc2-leaf2a | MLAG | Verifies there are no inactive or active-partial MLAG ports. | VerifyMlagInterfaces | NOT RUN | - |
| 1108 | dc2-leaf2a | MLAG | Verifies there are no MLAG config-sanity inconsistencies. | VerifyMlagConfigSanity | NOT RUN | - |
| 1109 | dc2-leaf2a | Multicast, IGMP | Verifies the IGMP snooping configuration for some VLANs. | VerifyIGMPSnoopingVlans | NOT RUN | - |
| 1110 | dc2-leaf2a | Multicast, IGMP | Verifies the IGMP snooping global configuration. | VerifyIGMPSnoopingGlobal | NOT RUN | - |
| 1111 | dc2-leaf2a | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 1112 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.0.1 | NOT RUN | - |
| 1113 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.0.2 | NOT RUN | - |
| 1114 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.0.3 | NOT RUN | - |
| 1115 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.0.4 | NOT RUN | - |
| 1116 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.0.5 | NOT RUN | - |
| 1117 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.11 | NOT RUN | - |
| 1118 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.12 | NOT RUN | - |
| 1119 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.13 | NOT RUN | - |
| 1120 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.14 | NOT RUN | - |
| 1121 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.15 | NOT RUN | - |
| 1122 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.16 | NOT RUN | - |
| 1123 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.17 | NOT RUN | - |
| 1124 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.128.18 | NOT RUN | - |
| 1125 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.2.1 | NOT RUN | - |
| 1126 | dc2-leaf2a | Routing Table | Remote Lo0 address | 10.255.2.2 | NOT RUN | - |
| 1127 | dc2-leaf2a | Routing Table | Remote VTEP address | 10.255.1.3 | NOT RUN | - |
| 1128 | dc2-leaf2a | Routing Table | Remote VTEP address | 10.255.1.5 | NOT RUN | - |
| 1129 | dc2-leaf2a | Routing Table | Remote VTEP address | 10.255.129.13 | NOT RUN | - |
| 1130 | dc2-leaf2a | Routing Table | Remote VTEP address | 10.255.129.15 | NOT RUN | - |
| 1131 | dc2-leaf2a | Routing Table | Remote VTEP address | 10.255.129.17 | NOT RUN | - |
| 1132 | dc2-leaf2a | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 1133 | dc2-leaf2a | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 1134 | dc2-leaf2a | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 1135 | dc2-leaf2a | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 1136 | dc2-leaf2a | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 1137 | dc2-leaf2a | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 1138 | dc2-leaf2a | STP | Verifies that all interfaces are forwarding for a provided list of VLAN(s). | VerifySTPForwardingPorts | NOT RUN | - |
| 1139 | dc2-leaf2a | STP | Verifies the configured STP mode for a provided list of VLAN(s). | VerifySTPMode | NOT RUN | - |
| 1140 | dc2-leaf2a | STP | Verifies the STP root priority for a provided list of VLAN or MST instance ID(s). | VerifySTPRootPriority | NOT RUN | - |
| 1141 | dc2-leaf2a | STP | Verifies there is no errors in STP BPDU packets. | VerifySTPCounters | NOT RUN | - |
| 1142 | dc2-leaf2a | STP | Verifies there is no STP blocked ports. | VerifySTPBlockedPorts | NOT RUN | - |
| 1143 | dc2-leaf2a | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 1144 | dc2-leaf2a | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 1145 | dc2-leaf2a | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 1146 | dc2-leaf2a | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 1147 | dc2-leaf2a | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 1148 | dc2-leaf2a | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 1149 | dc2-leaf2a | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 1150 | dc2-leaf2a | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 1151 | dc2-leaf2b | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 1152 | dc2-leaf2b | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 1153 | dc2-leaf2b | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 1154 | dc2-leaf2b | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 1155 | dc2-leaf2b | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 1156 | dc2-leaf2b | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 1157 | dc2-leaf2b | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 1158 | dc2-leaf2b | BGP | Verifies the configured routing protocol model. | Routing protocol model: multi-agent | NOT RUN | - |
| 1159 | dc2-leaf2b | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.11 | NOT RUN | - |
| 1160 | dc2-leaf2b | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.12 | NOT RUN | - |
| 1161 | dc2-leaf2b | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.129.120 | NOT RUN | - |
| 1162 | dc2-leaf2b | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.116 | NOT RUN | - |
| 1163 | dc2-leaf2b | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.118 | NOT RUN | - |
| 1164 | dc2-leaf2b | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 1165 | dc2-leaf2b | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 1166 | dc2-leaf2b | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 1167 | dc2-leaf2b | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 1168 | dc2-leaf2b | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1169 | dc2-leaf2b | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1170 | dc2-leaf2b | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1171 | dc2-leaf2b | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1172 | dc2-leaf2b | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1173 | dc2-leaf2b | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1174 | dc2-leaf2b | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1175 | dc2-leaf2b | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1176 | dc2-leaf2b | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 1177 | dc2-leaf2b | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 1178 | dc2-leaf2b | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 1179 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC2-SPINE1_Ethernet4 = 'up' | NOT RUN | - |
| 1180 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC2-SPINE2_Ethernet4 = 'up' | NOT RUN | - |
| 1181 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - MLAG_PEER_dc2-leaf2a_Ethernet3 = 'up' | NOT RUN | - |
| 1182 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - MLAG_PEER_dc2-leaf2a_Ethernet4 = 'up' | NOT RUN | - |
| 1183 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet5 - dc2-leaf2-server1_PCI2 = 'up' | NOT RUN | - |
| 1184 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet6 - P2P_LINK_TO_dc1-leaf2b_Ethernet6 = 'up' | NOT RUN | - |
| 1185 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet8 - DC2-LEAF2C_Ethernet2 = 'up' | NOT RUN | - |
| 1186 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - EVPN_Overlay_Peering = 'up' | NOT RUN | - |
| 1187 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback1 - VTEP_VXLAN_Tunnel_Source = 'up' | NOT RUN | - |
| 1188 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback10 - VRF10_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 1189 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback11 - VRF11_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 1190 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel3 - MLAG_PEER_dc2-leaf2a_Po3 = 'up' | NOT RUN | - |
| 1191 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel5 - dc2-leaf2-server1_PortChannel dc2-leaf2-server1 = 'up' | NOT RUN | - |
| 1192 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel8 - DC2-LEAF2C_Po1 = 'up' | NOT RUN | - |
| 1193 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan11 - VRF10_VLAN11 = 'up' | NOT RUN | - |
| 1194 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan12 - VRF10_VLAN12 = 'up' | NOT RUN | - |
| 1195 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan21 - VRF11_VLAN21 = 'up' | NOT RUN | - |
| 1196 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan22 - VRF11_VLAN22 = 'up' | NOT RUN | - |
| 1197 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF10 = 'up' | NOT RUN | - |
| 1198 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3010 - MLAG_PEER_L3_iBGP: vrf VRF11 = 'up' | NOT RUN | - |
| 1199 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4093 - MLAG_PEER_L3_PEERING = 'up' | NOT RUN | - |
| 1200 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4094 - MLAG_PEER = 'up' | NOT RUN | - |
| 1201 | dc2-leaf2b | Interfaces | Verifies the status of the provided interfaces. | Interface Vxlan1 = 'up' | NOT RUN | - |
| 1202 | dc2-leaf2b | IP Reachability | ip reachability test p2p links | Source: dc2-leaf2b_Ethernet1 - Destination: dc2-spine1_Ethernet4 | NOT RUN | - |
| 1203 | dc2-leaf2b | IP Reachability | ip reachability test p2p links | Source: dc2-leaf2b_Ethernet2 - Destination: dc2-spine2_Ethernet4 | NOT RUN | - |
| 1204 | dc2-leaf2b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc2-spine1_Ethernet4 | NOT RUN | - |
| 1205 | dc2-leaf2b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc2-spine2_Ethernet4 | NOT RUN | - |
| 1206 | dc2-leaf2b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: dc2-leaf2a_Ethernet3 | NOT RUN | - |
| 1207 | dc2-leaf2b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: dc2-leaf2a_Ethernet4 | NOT RUN | - |
| 1208 | dc2-leaf2b | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet8 - remote: dc2-leaf2c_Ethernet2 | NOT RUN | - |
| 1209 | dc2-leaf2b | Logging | This test verifies there are no syslog messages with a severity of ERRORS or higher. | VerifyLoggingWarning | NOT RUN | - |
| 1210 | dc2-leaf2b | Logging | Verifies if AAA accounting logs are generated. | VerifyLoggingAccounting | NOT RUN | - |
| 1211 | dc2-leaf2b | Logging | Verifies if logging persistent is enabled and logs are saved in flash. | VerifyLoggingPersistent | NOT RUN | - |
| 1212 | dc2-leaf2b | Logging | Verifies if logs are generated with the appropriate timestamp. | VerifyLoggingTimestamp | NOT RUN | - |
| 1213 | dc2-leaf2b | Logging | Verifies if logs are generated with the device FQDN. | VerifyLoggingHostname | NOT RUN | - |
| 1214 | dc2-leaf2b | Logging | Verifies if logs are generated. | VerifyLoggingLogsGeneration | NOT RUN | - |
| 1215 | dc2-leaf2b | Logging | Verifies logging hosts (syslog servers) for a specified VRF. | VerifyLoggingHosts | NOT RUN | - |
| 1216 | dc2-leaf2b | Logging | Verifies logging source-interface for a specified VRF. | VerifyLoggingSourceInt | NOT RUN | - |
| 1217 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.0.1 | NOT RUN | - |
| 1218 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.0.2 | NOT RUN | - |
| 1219 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.0.3 | NOT RUN | - |
| 1220 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.0.4 | NOT RUN | - |
| 1221 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.0.5 | NOT RUN | - |
| 1222 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.128.11 | NOT RUN | - |
| 1223 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.128.12 | NOT RUN | - |
| 1224 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.128.13 | NOT RUN | - |
| 1225 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.128.14 | NOT RUN | - |
| 1226 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.128.15 | NOT RUN | - |
| 1227 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.128.16 | NOT RUN | - |
| 1228 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.128.17 | NOT RUN | - |
| 1229 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.128.18 | NOT RUN | - |
| 1230 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.2.1 | NOT RUN | - |
| 1231 | dc2-leaf2b | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf2b - 10.255.128.16/32 Destination: 10.255.2.2 | NOT RUN | - |
| 1232 | dc2-leaf2b | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 1233 | dc2-leaf2b | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 1234 | dc2-leaf2b | MLAG | Verifies the MLAG dual-primary detection parameters. | VerifyMlagDualPrimary | NOT RUN | - |
| 1235 | dc2-leaf2b | MLAG | Verifies the MLAG reload-delay parameters. | VerifyMlagReloadDelay | NOT RUN | - |
| 1236 | dc2-leaf2b | MLAG | Verifies there are no inactive or active-partial MLAG ports. | VerifyMlagInterfaces | NOT RUN | - |
| 1237 | dc2-leaf2b | MLAG | Verifies there are no MLAG config-sanity inconsistencies. | VerifyMlagConfigSanity | NOT RUN | - |
| 1238 | dc2-leaf2b | Multicast, IGMP | Verifies the IGMP snooping configuration for some VLANs. | VerifyIGMPSnoopingVlans | NOT RUN | - |
| 1239 | dc2-leaf2b | Multicast, IGMP | Verifies the IGMP snooping global configuration. | VerifyIGMPSnoopingGlobal | NOT RUN | - |
| 1240 | dc2-leaf2b | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 1241 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.0.1 | NOT RUN | - |
| 1242 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.0.2 | NOT RUN | - |
| 1243 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.0.3 | NOT RUN | - |
| 1244 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.0.4 | NOT RUN | - |
| 1245 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.0.5 | NOT RUN | - |
| 1246 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.128.11 | NOT RUN | - |
| 1247 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.128.12 | NOT RUN | - |
| 1248 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.128.13 | NOT RUN | - |
| 1249 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.128.14 | NOT RUN | - |
| 1250 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.128.15 | NOT RUN | - |
| 1251 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.128.16 | NOT RUN | - |
| 1252 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.128.17 | NOT RUN | - |
| 1253 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.128.18 | NOT RUN | - |
| 1254 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.2.1 | NOT RUN | - |
| 1255 | dc2-leaf2b | Routing Table | Remote Lo0 address | 10.255.2.2 | NOT RUN | - |
| 1256 | dc2-leaf2b | Routing Table | Remote VTEP address | 10.255.1.3 | NOT RUN | - |
| 1257 | dc2-leaf2b | Routing Table | Remote VTEP address | 10.255.1.5 | NOT RUN | - |
| 1258 | dc2-leaf2b | Routing Table | Remote VTEP address | 10.255.129.13 | NOT RUN | - |
| 1259 | dc2-leaf2b | Routing Table | Remote VTEP address | 10.255.129.15 | NOT RUN | - |
| 1260 | dc2-leaf2b | Routing Table | Remote VTEP address | 10.255.129.17 | NOT RUN | - |
| 1261 | dc2-leaf2b | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 1262 | dc2-leaf2b | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 1263 | dc2-leaf2b | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 1264 | dc2-leaf2b | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 1265 | dc2-leaf2b | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 1266 | dc2-leaf2b | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 1267 | dc2-leaf2b | STP | Verifies that all interfaces are forwarding for a provided list of VLAN(s). | VerifySTPForwardingPorts | NOT RUN | - |
| 1268 | dc2-leaf2b | STP | Verifies the configured STP mode for a provided list of VLAN(s). | VerifySTPMode | NOT RUN | - |
| 1269 | dc2-leaf2b | STP | Verifies the STP root priority for a provided list of VLAN or MST instance ID(s). | VerifySTPRootPriority | NOT RUN | - |
| 1270 | dc2-leaf2b | STP | Verifies there is no errors in STP BPDU packets. | VerifySTPCounters | NOT RUN | - |
| 1271 | dc2-leaf2b | STP | Verifies there is no STP blocked ports. | VerifySTPBlockedPorts | NOT RUN | - |
| 1272 | dc2-leaf2b | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 1273 | dc2-leaf2b | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 1274 | dc2-leaf2b | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 1275 | dc2-leaf2b | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 1276 | dc2-leaf2b | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 1277 | dc2-leaf2b | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 1278 | dc2-leaf2b | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 1279 | dc2-leaf2b | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 1280 | dc2-leaf2c | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 1281 | dc2-leaf2c | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 1282 | dc2-leaf2c | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 1283 | dc2-leaf2c | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 1284 | dc2-leaf2c | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 1285 | dc2-leaf2c | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 1286 | dc2-leaf2c | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 1287 | dc2-leaf2c | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 1288 | dc2-leaf2c | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 1289 | dc2-leaf2c | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 1290 | dc2-leaf2c | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 1291 | dc2-leaf2c | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1292 | dc2-leaf2c | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1293 | dc2-leaf2c | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1294 | dc2-leaf2c | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1295 | dc2-leaf2c | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1296 | dc2-leaf2c | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1297 | dc2-leaf2c | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1298 | dc2-leaf2c | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1299 | dc2-leaf2c | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 1300 | dc2-leaf2c | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 1301 | dc2-leaf2c | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 1302 | dc2-leaf2c | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - DC2-LEAF2A_Ethernet8 = 'up' | NOT RUN | - |
| 1303 | dc2-leaf2c | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - DC2-LEAF2B_Ethernet8 = 'up' | NOT RUN | - |
| 1304 | dc2-leaf2c | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet5 - dc2-leaf2-server1_iLO = 'up' | NOT RUN | - |
| 1305 | dc2-leaf2c | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel1 - DC2_L3_LEAF2_Po8 = 'up' | NOT RUN | - |
| 1306 | dc2-leaf2c | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc2-leaf2a_Ethernet8 | NOT RUN | - |
| 1307 | dc2-leaf2c | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc2-leaf2b_Ethernet8 | NOT RUN | - |
| 1308 | dc2-leaf2c | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 1309 | dc2-leaf2c | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 1310 | dc2-leaf2c | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 1311 | dc2-leaf2c | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 1312 | dc2-leaf2c | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 1313 | dc2-leaf2c | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 1314 | dc2-leaf2c | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 1315 | dc2-leaf2c | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 1316 | dc2-leaf2c | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 1317 | dc2-leaf2c | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 1318 | dc2-leaf2c | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 1319 | dc2-leaf2c | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 1320 | dc2-leaf2c | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 1321 | dc2-leaf2c | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 1322 | dc2-leaf2c | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 1323 | dc2-leaf3a.arista.com | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 1324 | dc2-leaf3a.arista.com | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 1325 | dc2-leaf3a.arista.com | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 1326 | dc2-leaf3a.arista.com | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 1327 | dc2-leaf3a.arista.com | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 1328 | dc2-leaf3a.arista.com | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 1329 | dc2-leaf3a.arista.com | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 1330 | dc2-leaf3a.arista.com | BGP | Verifies the configured routing protocol model. | Routing protocol model: multi-agent | NOT RUN | - |
| 1331 | dc2-leaf3a.arista.com | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.11 | NOT RUN | - |
| 1332 | dc2-leaf3a.arista.com | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.12 | NOT RUN | - |
| 1333 | dc2-leaf3a.arista.com | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.129.125 | NOT RUN | - |
| 1334 | dc2-leaf3a.arista.com | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.120 | NOT RUN | - |
| 1335 | dc2-leaf3a.arista.com | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.122 | NOT RUN | - |
| 1336 | dc2-leaf3a.arista.com | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 1337 | dc2-leaf3a.arista.com | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 1338 | dc2-leaf3a.arista.com | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 1339 | dc2-leaf3a.arista.com | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 1340 | dc2-leaf3a.arista.com | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1341 | dc2-leaf3a.arista.com | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1342 | dc2-leaf3a.arista.com | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1343 | dc2-leaf3a.arista.com | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1344 | dc2-leaf3a.arista.com | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1345 | dc2-leaf3a.arista.com | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1346 | dc2-leaf3a.arista.com | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1347 | dc2-leaf3a.arista.com | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1348 | dc2-leaf3a.arista.com | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 1349 | dc2-leaf3a.arista.com | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 1350 | dc2-leaf3a.arista.com | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 1351 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC2-SPINE1_Ethernet5 = 'up' | NOT RUN | - |
| 1352 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet11 - dc2-leaf3-fw1_e1 = 'up' | NOT RUN | - |
| 1353 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC2-SPINE2_Ethernet5 = 'up' | NOT RUN | - |
| 1354 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - MLAG_PEER_dc2-leaf3b.arista.com_Ethernet3 = 'up' | NOT RUN | - |
| 1355 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - MLAG_PEER_dc2-leaf3b.arista.com_Ethernet4 = 'up' | NOT RUN | - |
| 1356 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - EVPN_Overlay_Peering = 'up' | NOT RUN | - |
| 1357 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback1 - VTEP_VXLAN_Tunnel_Source = 'up' | NOT RUN | - |
| 1358 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback10 - VRF10_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 1359 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback11 - VRF11_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 1360 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel11 - dc2-leaf3-fw1_PortChannel = 'up' | NOT RUN | - |
| 1361 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel3 - MLAG_PEER_dc2-leaf3b.arista.com_Po3 = 'up' | NOT RUN | - |
| 1362 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan11 - VRF10_VLAN11 = 'up' | NOT RUN | - |
| 1363 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan12 - VRF10_VLAN12 = 'up' | NOT RUN | - |
| 1364 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan21 - VRF11_VLAN21 = 'up' | NOT RUN | - |
| 1365 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan22 - VRF11_VLAN22 = 'up' | NOT RUN | - |
| 1366 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF10 = 'up' | NOT RUN | - |
| 1367 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3010 - MLAG_PEER_L3_iBGP: vrf VRF11 = 'up' | NOT RUN | - |
| 1368 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4093 - MLAG_PEER_L3_PEERING = 'up' | NOT RUN | - |
| 1369 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4094 - MLAG_PEER = 'up' | NOT RUN | - |
| 1370 | dc2-leaf3a.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vxlan1 = 'up' | NOT RUN | - |
| 1371 | dc2-leaf3a.arista.com | IP Reachability | ip reachability test p2p links | Source: dc2-leaf3a.arista.com_Ethernet1 - Destination: dc2-spine1_Ethernet5 | NOT RUN | - |
| 1372 | dc2-leaf3a.arista.com | IP Reachability | ip reachability test p2p links | Source: dc2-leaf3a.arista.com_Ethernet2 - Destination: dc2-spine2_Ethernet5 | NOT RUN | - |
| 1373 | dc2-leaf3a.arista.com | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc2-spine1_Ethernet5 | NOT RUN | - |
| 1374 | dc2-leaf3a.arista.com | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc2-spine2_Ethernet5 | NOT RUN | - |
| 1375 | dc2-leaf3a.arista.com | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: dc2-leaf3b.arista.com_Ethernet3 | NOT RUN | - |
| 1376 | dc2-leaf3a.arista.com | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: dc2-leaf3b.arista.com_Ethernet4 | NOT RUN | - |
| 1377 | dc2-leaf3a.arista.com | Logging | This test verifies there are no syslog messages with a severity of ERRORS or higher. | VerifyLoggingWarning | NOT RUN | - |
| 1378 | dc2-leaf3a.arista.com | Logging | Verifies if AAA accounting logs are generated. | VerifyLoggingAccounting | NOT RUN | - |
| 1379 | dc2-leaf3a.arista.com | Logging | Verifies if logging persistent is enabled and logs are saved in flash. | VerifyLoggingPersistent | NOT RUN | - |
| 1380 | dc2-leaf3a.arista.com | Logging | Verifies if logs are generated with the appropriate timestamp. | VerifyLoggingTimestamp | NOT RUN | - |
| 1381 | dc2-leaf3a.arista.com | Logging | Verifies if logs are generated with the device FQDN. | VerifyLoggingHostname | NOT RUN | - |
| 1382 | dc2-leaf3a.arista.com | Logging | Verifies if logs are generated. | VerifyLoggingLogsGeneration | NOT RUN | - |
| 1383 | dc2-leaf3a.arista.com | Logging | Verifies logging hosts (syslog servers) for a specified VRF. | VerifyLoggingHosts | NOT RUN | - |
| 1384 | dc2-leaf3a.arista.com | Logging | Verifies logging source-interface for a specified VRF. | VerifyLoggingSourceInt | NOT RUN | - |
| 1385 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.0.1 | NOT RUN | - |
| 1386 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.0.2 | NOT RUN | - |
| 1387 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.0.3 | NOT RUN | - |
| 1388 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.0.4 | NOT RUN | - |
| 1389 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.0.5 | NOT RUN | - |
| 1390 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.128.11 | NOT RUN | - |
| 1391 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.128.12 | NOT RUN | - |
| 1392 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.128.13 | NOT RUN | - |
| 1393 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.128.14 | NOT RUN | - |
| 1394 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.128.15 | NOT RUN | - |
| 1395 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.128.16 | NOT RUN | - |
| 1396 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.128.17 | NOT RUN | - |
| 1397 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.128.18 | NOT RUN | - |
| 1398 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.2.1 | NOT RUN | - |
| 1399 | dc2-leaf3a.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3a.arista.com - 10.255.128.17/32 Destination: 10.255.2.2 | NOT RUN | - |
| 1400 | dc2-leaf3a.arista.com | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 1401 | dc2-leaf3a.arista.com | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 1402 | dc2-leaf3a.arista.com | MLAG | Verifies the MLAG dual-primary detection parameters. | VerifyMlagDualPrimary | NOT RUN | - |
| 1403 | dc2-leaf3a.arista.com | MLAG | Verifies the MLAG reload-delay parameters. | VerifyMlagReloadDelay | NOT RUN | - |
| 1404 | dc2-leaf3a.arista.com | MLAG | Verifies there are no inactive or active-partial MLAG ports. | VerifyMlagInterfaces | NOT RUN | - |
| 1405 | dc2-leaf3a.arista.com | MLAG | Verifies there are no MLAG config-sanity inconsistencies. | VerifyMlagConfigSanity | NOT RUN | - |
| 1406 | dc2-leaf3a.arista.com | Multicast, IGMP | Verifies the IGMP snooping configuration for some VLANs. | VerifyIGMPSnoopingVlans | NOT RUN | - |
| 1407 | dc2-leaf3a.arista.com | Multicast, IGMP | Verifies the IGMP snooping global configuration. | VerifyIGMPSnoopingGlobal | NOT RUN | - |
| 1408 | dc2-leaf3a.arista.com | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 1409 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.0.1 | NOT RUN | - |
| 1410 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.0.2 | NOT RUN | - |
| 1411 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.0.3 | NOT RUN | - |
| 1412 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.0.4 | NOT RUN | - |
| 1413 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.0.5 | NOT RUN | - |
| 1414 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.128.11 | NOT RUN | - |
| 1415 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.128.12 | NOT RUN | - |
| 1416 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.128.13 | NOT RUN | - |
| 1417 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.128.14 | NOT RUN | - |
| 1418 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.128.15 | NOT RUN | - |
| 1419 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.128.16 | NOT RUN | - |
| 1420 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.128.17 | NOT RUN | - |
| 1421 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.128.18 | NOT RUN | - |
| 1422 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.2.1 | NOT RUN | - |
| 1423 | dc2-leaf3a.arista.com | Routing Table | Remote Lo0 address | 10.255.2.2 | NOT RUN | - |
| 1424 | dc2-leaf3a.arista.com | Routing Table | Remote VTEP address | 10.255.1.3 | NOT RUN | - |
| 1425 | dc2-leaf3a.arista.com | Routing Table | Remote VTEP address | 10.255.1.5 | NOT RUN | - |
| 1426 | dc2-leaf3a.arista.com | Routing Table | Remote VTEP address | 10.255.129.13 | NOT RUN | - |
| 1427 | dc2-leaf3a.arista.com | Routing Table | Remote VTEP address | 10.255.129.15 | NOT RUN | - |
| 1428 | dc2-leaf3a.arista.com | Routing Table | Remote VTEP address | 10.255.129.17 | NOT RUN | - |
| 1429 | dc2-leaf3a.arista.com | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 1430 | dc2-leaf3a.arista.com | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 1431 | dc2-leaf3a.arista.com | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 1432 | dc2-leaf3a.arista.com | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 1433 | dc2-leaf3a.arista.com | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 1434 | dc2-leaf3a.arista.com | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 1435 | dc2-leaf3a.arista.com | STP | Verifies that all interfaces are forwarding for a provided list of VLAN(s). | VerifySTPForwardingPorts | NOT RUN | - |
| 1436 | dc2-leaf3a.arista.com | STP | Verifies the configured STP mode for a provided list of VLAN(s). | VerifySTPMode | NOT RUN | - |
| 1437 | dc2-leaf3a.arista.com | STP | Verifies the STP root priority for a provided list of VLAN or MST instance ID(s). | VerifySTPRootPriority | NOT RUN | - |
| 1438 | dc2-leaf3a.arista.com | STP | Verifies there is no errors in STP BPDU packets. | VerifySTPCounters | NOT RUN | - |
| 1439 | dc2-leaf3a.arista.com | STP | Verifies there is no STP blocked ports. | VerifySTPBlockedPorts | NOT RUN | - |
| 1440 | dc2-leaf3a.arista.com | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 1441 | dc2-leaf3a.arista.com | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 1442 | dc2-leaf3a.arista.com | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 1443 | dc2-leaf3a.arista.com | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 1444 | dc2-leaf3a.arista.com | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 1445 | dc2-leaf3a.arista.com | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 1446 | dc2-leaf3a.arista.com | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 1447 | dc2-leaf3a.arista.com | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 1448 | dc2-leaf3b.arista.com | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 1449 | dc2-leaf3b.arista.com | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 1450 | dc2-leaf3b.arista.com | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 1451 | dc2-leaf3b.arista.com | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 1452 | dc2-leaf3b.arista.com | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 1453 | dc2-leaf3b.arista.com | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 1454 | dc2-leaf3b.arista.com | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 1455 | dc2-leaf3b.arista.com | BGP | Verifies the configured routing protocol model. | Routing protocol model: multi-agent | NOT RUN | - |
| 1456 | dc2-leaf3b.arista.com | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.11 | NOT RUN | - |
| 1457 | dc2-leaf3b.arista.com | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.12 | NOT RUN | - |
| 1458 | dc2-leaf3b.arista.com | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.129.124 | NOT RUN | - |
| 1459 | dc2-leaf3b.arista.com | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.124 | NOT RUN | - |
| 1460 | dc2-leaf3b.arista.com | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.126 | NOT RUN | - |
| 1461 | dc2-leaf3b.arista.com | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 1462 | dc2-leaf3b.arista.com | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 1463 | dc2-leaf3b.arista.com | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 1464 | dc2-leaf3b.arista.com | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 1465 | dc2-leaf3b.arista.com | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1466 | dc2-leaf3b.arista.com | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1467 | dc2-leaf3b.arista.com | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1468 | dc2-leaf3b.arista.com | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1469 | dc2-leaf3b.arista.com | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1470 | dc2-leaf3b.arista.com | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1471 | dc2-leaf3b.arista.com | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1472 | dc2-leaf3b.arista.com | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1473 | dc2-leaf3b.arista.com | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 1474 | dc2-leaf3b.arista.com | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 1475 | dc2-leaf3b.arista.com | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 1476 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC2-SPINE1_Ethernet6 = 'up' | NOT RUN | - |
| 1477 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet11 - dc2-leaf3-fw1_e1 = 'adminDown' | NOT RUN | - |
| 1478 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC2-SPINE2_Ethernet6 = 'up' | NOT RUN | - |
| 1479 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - MLAG_PEER_dc2-leaf3a.arista.com_Ethernet3 = 'up' | NOT RUN | - |
| 1480 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - MLAG_PEER_dc2-leaf3a.arista.com_Ethernet4 = 'up' | NOT RUN | - |
| 1481 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - EVPN_Overlay_Peering = 'up' | NOT RUN | - |
| 1482 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback1 - VTEP_VXLAN_Tunnel_Source = 'up' | NOT RUN | - |
| 1483 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback10 - VRF10_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 1484 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback11 - VRF11_VTEP_DIAGNOSTICS = 'up' | NOT RUN | - |
| 1485 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel11 - dc2-leaf3-fw1_PortChannel = 'up' | NOT RUN | - |
| 1486 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Port-Channel3 - MLAG_PEER_dc2-leaf3a.arista.com_Po3 = 'up' | NOT RUN | - |
| 1487 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan11 - VRF10_VLAN11 = 'up' | NOT RUN | - |
| 1488 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan12 - VRF10_VLAN12 = 'up' | NOT RUN | - |
| 1489 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan21 - VRF11_VLAN21 = 'up' | NOT RUN | - |
| 1490 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan22 - VRF11_VLAN22 = 'up' | NOT RUN | - |
| 1491 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF10 = 'up' | NOT RUN | - |
| 1492 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan3010 - MLAG_PEER_L3_iBGP: vrf VRF11 = 'up' | NOT RUN | - |
| 1493 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4093 - MLAG_PEER_L3_PEERING = 'up' | NOT RUN | - |
| 1494 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vlan4094 - MLAG_PEER = 'up' | NOT RUN | - |
| 1495 | dc2-leaf3b.arista.com | Interfaces | Verifies the status of the provided interfaces. | Interface Vxlan1 = 'up' | NOT RUN | - |
| 1496 | dc2-leaf3b.arista.com | IP Reachability | ip reachability test p2p links | Source: dc2-leaf3b.arista.com_Ethernet1 - Destination: dc2-spine1_Ethernet6 | NOT RUN | - |
| 1497 | dc2-leaf3b.arista.com | IP Reachability | ip reachability test p2p links | Source: dc2-leaf3b.arista.com_Ethernet2 - Destination: dc2-spine2_Ethernet6 | NOT RUN | - |
| 1498 | dc2-leaf3b.arista.com | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc2-spine1_Ethernet6 | NOT RUN | - |
| 1499 | dc2-leaf3b.arista.com | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc2-spine2_Ethernet6 | NOT RUN | - |
| 1500 | dc2-leaf3b.arista.com | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: dc2-leaf3a.arista.com_Ethernet3 | NOT RUN | - |
| 1501 | dc2-leaf3b.arista.com | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: dc2-leaf3a.arista.com_Ethernet4 | NOT RUN | - |
| 1502 | dc2-leaf3b.arista.com | Logging | This test verifies there are no syslog messages with a severity of ERRORS or higher. | VerifyLoggingWarning | NOT RUN | - |
| 1503 | dc2-leaf3b.arista.com | Logging | Verifies if AAA accounting logs are generated. | VerifyLoggingAccounting | NOT RUN | - |
| 1504 | dc2-leaf3b.arista.com | Logging | Verifies if logging persistent is enabled and logs are saved in flash. | VerifyLoggingPersistent | NOT RUN | - |
| 1505 | dc2-leaf3b.arista.com | Logging | Verifies if logs are generated with the appropriate timestamp. | VerifyLoggingTimestamp | NOT RUN | - |
| 1506 | dc2-leaf3b.arista.com | Logging | Verifies if logs are generated with the device FQDN. | VerifyLoggingHostname | NOT RUN | - |
| 1507 | dc2-leaf3b.arista.com | Logging | Verifies if logs are generated. | VerifyLoggingLogsGeneration | NOT RUN | - |
| 1508 | dc2-leaf3b.arista.com | Logging | Verifies logging hosts (syslog servers) for a specified VRF. | VerifyLoggingHosts | NOT RUN | - |
| 1509 | dc2-leaf3b.arista.com | Logging | Verifies logging source-interface for a specified VRF. | VerifyLoggingSourceInt | NOT RUN | - |
| 1510 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.0.1 | NOT RUN | - |
| 1511 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.0.2 | NOT RUN | - |
| 1512 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.0.3 | NOT RUN | - |
| 1513 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.0.4 | NOT RUN | - |
| 1514 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.0.5 | NOT RUN | - |
| 1515 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.128.11 | NOT RUN | - |
| 1516 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.128.12 | NOT RUN | - |
| 1517 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.128.13 | NOT RUN | - |
| 1518 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.128.14 | NOT RUN | - |
| 1519 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.128.15 | NOT RUN | - |
| 1520 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.128.16 | NOT RUN | - |
| 1521 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.128.17 | NOT RUN | - |
| 1522 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.128.18 | NOT RUN | - |
| 1523 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.2.1 | NOT RUN | - |
| 1524 | dc2-leaf3b.arista.com | Loopback0 Reachability | Loopback0 Reachability | Source: dc2-leaf3b.arista.com - 10.255.128.18/32 Destination: 10.255.2.2 | NOT RUN | - |
| 1525 | dc2-leaf3b.arista.com | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 1526 | dc2-leaf3b.arista.com | MLAG | Verifies the health status of the MLAG configuration. | VerifyMlagStatus | NOT RUN | - |
| 1527 | dc2-leaf3b.arista.com | MLAG | Verifies the MLAG dual-primary detection parameters. | VerifyMlagDualPrimary | NOT RUN | - |
| 1528 | dc2-leaf3b.arista.com | MLAG | Verifies the MLAG reload-delay parameters. | VerifyMlagReloadDelay | NOT RUN | - |
| 1529 | dc2-leaf3b.arista.com | MLAG | Verifies there are no inactive or active-partial MLAG ports. | VerifyMlagInterfaces | NOT RUN | - |
| 1530 | dc2-leaf3b.arista.com | MLAG | Verifies there are no MLAG config-sanity inconsistencies. | VerifyMlagConfigSanity | NOT RUN | - |
| 1531 | dc2-leaf3b.arista.com | Multicast, IGMP | Verifies the IGMP snooping configuration for some VLANs. | VerifyIGMPSnoopingVlans | NOT RUN | - |
| 1532 | dc2-leaf3b.arista.com | Multicast, IGMP | Verifies the IGMP snooping global configuration. | VerifyIGMPSnoopingGlobal | NOT RUN | - |
| 1533 | dc2-leaf3b.arista.com | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 1534 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.0.1 | NOT RUN | - |
| 1535 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.0.2 | NOT RUN | - |
| 1536 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.0.3 | NOT RUN | - |
| 1537 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.0.4 | NOT RUN | - |
| 1538 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.0.5 | NOT RUN | - |
| 1539 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.128.11 | NOT RUN | - |
| 1540 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.128.12 | NOT RUN | - |
| 1541 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.128.13 | NOT RUN | - |
| 1542 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.128.14 | NOT RUN | - |
| 1543 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.128.15 | NOT RUN | - |
| 1544 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.128.16 | NOT RUN | - |
| 1545 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.128.17 | NOT RUN | - |
| 1546 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.128.18 | NOT RUN | - |
| 1547 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.2.1 | NOT RUN | - |
| 1548 | dc2-leaf3b.arista.com | Routing Table | Remote Lo0 address | 10.255.2.2 | NOT RUN | - |
| 1549 | dc2-leaf3b.arista.com | Routing Table | Remote VTEP address | 10.255.1.3 | NOT RUN | - |
| 1550 | dc2-leaf3b.arista.com | Routing Table | Remote VTEP address | 10.255.1.5 | NOT RUN | - |
| 1551 | dc2-leaf3b.arista.com | Routing Table | Remote VTEP address | 10.255.129.13 | NOT RUN | - |
| 1552 | dc2-leaf3b.arista.com | Routing Table | Remote VTEP address | 10.255.129.15 | NOT RUN | - |
| 1553 | dc2-leaf3b.arista.com | Routing Table | Remote VTEP address | 10.255.129.17 | NOT RUN | - |
| 1554 | dc2-leaf3b.arista.com | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 1555 | dc2-leaf3b.arista.com | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 1556 | dc2-leaf3b.arista.com | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 1557 | dc2-leaf3b.arista.com | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 1558 | dc2-leaf3b.arista.com | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 1559 | dc2-leaf3b.arista.com | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 1560 | dc2-leaf3b.arista.com | STP | Verifies that all interfaces are forwarding for a provided list of VLAN(s). | VerifySTPForwardingPorts | NOT RUN | - |
| 1561 | dc2-leaf3b.arista.com | STP | Verifies the configured STP mode for a provided list of VLAN(s). | VerifySTPMode | NOT RUN | - |
| 1562 | dc2-leaf3b.arista.com | STP | Verifies the STP root priority for a provided list of VLAN or MST instance ID(s). | VerifySTPRootPriority | NOT RUN | - |
| 1563 | dc2-leaf3b.arista.com | STP | Verifies there is no errors in STP BPDU packets. | VerifySTPCounters | NOT RUN | - |
| 1564 | dc2-leaf3b.arista.com | STP | Verifies there is no STP blocked ports. | VerifySTPBlockedPorts | NOT RUN | - |
| 1565 | dc2-leaf3b.arista.com | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 1566 | dc2-leaf3b.arista.com | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 1567 | dc2-leaf3b.arista.com | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 1568 | dc2-leaf3b.arista.com | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 1569 | dc2-leaf3b.arista.com | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 1570 | dc2-leaf3b.arista.com | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 1571 | dc2-leaf3b.arista.com | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 1572 | dc2-leaf3b.arista.com | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 1573 | dc2-spine1 | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 1574 | dc2-spine1 | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 1575 | dc2-spine1 | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 1576 | dc2-spine1 | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 1577 | dc2-spine1 | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 1578 | dc2-spine1 | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 1579 | dc2-spine1 | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 1580 | dc2-spine1 | BGP | Verifies the configured routing protocol model. | Routing protocol model: multi-agent | NOT RUN | - |
| 1581 | dc2-spine1 | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.13 | NOT RUN | - |
| 1582 | dc2-spine1 | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.14 | NOT RUN | - |
| 1583 | dc2-spine1 | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.15 | NOT RUN | - |
| 1584 | dc2-spine1 | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.16 | NOT RUN | - |
| 1585 | dc2-spine1 | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.17 | NOT RUN | - |
| 1586 | dc2-spine1 | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.18 | NOT RUN | - |
| 1587 | dc2-spine1 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.105 | NOT RUN | - |
| 1588 | dc2-spine1 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.109 | NOT RUN | - |
| 1589 | dc2-spine1 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.113 | NOT RUN | - |
| 1590 | dc2-spine1 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.117 | NOT RUN | - |
| 1591 | dc2-spine1 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.121 | NOT RUN | - |
| 1592 | dc2-spine1 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.125 | NOT RUN | - |
| 1593 | dc2-spine1 | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 1594 | dc2-spine1 | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 1595 | dc2-spine1 | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 1596 | dc2-spine1 | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 1597 | dc2-spine1 | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1598 | dc2-spine1 | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1599 | dc2-spine1 | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1600 | dc2-spine1 | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1601 | dc2-spine1 | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1602 | dc2-spine1 | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1603 | dc2-spine1 | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1604 | dc2-spine1 | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1605 | dc2-spine1 | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 1606 | dc2-spine1 | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 1607 | dc2-spine1 | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 1608 | dc2-spine1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC2-LEAF1A_Ethernet1 = 'up' | NOT RUN | - |
| 1609 | dc2-spine1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC2-LEAF1B_Ethernet1 = 'up' | NOT RUN | - |
| 1610 | dc2-spine1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - P2P_LINK_TO_DC2-LEAF2A_Ethernet1 = 'up' | NOT RUN | - |
| 1611 | dc2-spine1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - P2P_LINK_TO_DC2-LEAF2B_Ethernet1 = 'up' | NOT RUN | - |
| 1612 | dc2-spine1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet5 - P2P_LINK_TO_DC2-LEAF3A.ARISTA.COM_Ethernet1 = 'up' | NOT RUN | - |
| 1613 | dc2-spine1 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet6 - P2P_LINK_TO_DC2-LEAF3B.ARISTA.COM_Ethernet1 = 'up' | NOT RUN | - |
| 1614 | dc2-spine1 | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - EVPN_Overlay_Peering = 'up' | NOT RUN | - |
| 1615 | dc2-spine1 | IP Reachability | ip reachability test p2p links | Source: dc2-spine1_Ethernet1 - Destination: dc2-leaf1a_Ethernet1 | NOT RUN | - |
| 1616 | dc2-spine1 | IP Reachability | ip reachability test p2p links | Source: dc2-spine1_Ethernet2 - Destination: dc2-leaf1b_Ethernet1 | NOT RUN | - |
| 1617 | dc2-spine1 | IP Reachability | ip reachability test p2p links | Source: dc2-spine1_Ethernet3 - Destination: dc2-leaf2a_Ethernet1 | NOT RUN | - |
| 1618 | dc2-spine1 | IP Reachability | ip reachability test p2p links | Source: dc2-spine1_Ethernet4 - Destination: dc2-leaf2b_Ethernet1 | NOT RUN | - |
| 1619 | dc2-spine1 | IP Reachability | ip reachability test p2p links | Source: dc2-spine1_Ethernet5 - Destination: dc2-leaf3a.arista.com_Ethernet1 | NOT RUN | - |
| 1620 | dc2-spine1 | IP Reachability | ip reachability test p2p links | Source: dc2-spine1_Ethernet6 - Destination: dc2-leaf3b.arista.com_Ethernet1 | NOT RUN | - |
| 1621 | dc2-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc2-leaf1a_Ethernet1 | NOT RUN | - |
| 1622 | dc2-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc2-leaf1b_Ethernet1 | NOT RUN | - |
| 1623 | dc2-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: dc2-leaf2a_Ethernet1 | NOT RUN | - |
| 1624 | dc2-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: dc2-leaf2b_Ethernet1 | NOT RUN | - |
| 1625 | dc2-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: dc2-leaf3a.arista.com_Ethernet1 | NOT RUN | - |
| 1626 | dc2-spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: dc2-leaf3b.arista.com_Ethernet1 | NOT RUN | - |
| 1627 | dc2-spine1 | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 1628 | dc2-spine1 | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 1629 | dc2-spine1 | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 1630 | dc2-spine1 | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 1631 | dc2-spine1 | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 1632 | dc2-spine1 | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 1633 | dc2-spine1 | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 1634 | dc2-spine1 | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 1635 | dc2-spine1 | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 1636 | dc2-spine1 | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 1637 | dc2-spine1 | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 1638 | dc2-spine1 | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 1639 | dc2-spine1 | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 1640 | dc2-spine1 | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 1641 | dc2-spine1 | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
| 1642 | dc2-spine2 | AAA | Verifies if the provided TACACS server group(s) are configured. | VerifyTacacsServerGroups | NOT RUN | - |
| 1643 | dc2-spine2 | AAA | Verifies TACACS servers are configured for a specified VRF. | VerifyTacacsServers | NOT RUN | - |
| 1644 | dc2-spine2 | AAA | Verifies TACACS source-interface for a specified VRF. | VerifyTacacsSourceIntf | NOT RUN | - |
| 1645 | dc2-spine2 | AAA | Verifies the AAA accounting console method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctConsoleMethods | NOT RUN | - |
| 1646 | dc2-spine2 | AAA | Verifies the AAA accounting default method lists for different accounting types (system, exec, commands, dot1x). | VerifyAcctDefaultMethods | NOT RUN | - |
| 1647 | dc2-spine2 | AAA | Verifies the AAA authentication method lists for different authentication types (login, enable, dot1x). | VerifyAuthenMethods | NOT RUN | - |
| 1648 | dc2-spine2 | AAA | Verifies the AAA authorization method lists for different authorization types (commands, exec). | VerifyAuthzMethods | NOT RUN | - |
| 1649 | dc2-spine2 | BGP | Verifies the configured routing protocol model. | Routing protocol model: multi-agent | NOT RUN | - |
| 1650 | dc2-spine2 | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.13 | NOT RUN | - |
| 1651 | dc2-spine2 | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.14 | NOT RUN | - |
| 1652 | dc2-spine2 | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.15 | NOT RUN | - |
| 1653 | dc2-spine2 | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.16 | NOT RUN | - |
| 1654 | dc2-spine2 | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.17 | NOT RUN | - |
| 1655 | dc2-spine2 | BGP | Verifies the health of specific BGP peer(s). | BGP EVPN Peer: 10.255.128.18 | NOT RUN | - |
| 1656 | dc2-spine2 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.107 | NOT RUN | - |
| 1657 | dc2-spine2 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.111 | NOT RUN | - |
| 1658 | dc2-spine2 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.115 | NOT RUN | - |
| 1659 | dc2-spine2 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.119 | NOT RUN | - |
| 1660 | dc2-spine2 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.123 | NOT RUN | - |
| 1661 | dc2-spine2 | BGP | Verifies the health of specific BGP peer(s). | BGP IPv4 Unicast Peer: 10.255.255.127 | NOT RUN | - |
| 1662 | dc2-spine2 | Configuration | Verifies there is no difference between the running-config and the startup-config | VerifyRunningConfigDiffs | NOT RUN | - |
| 1663 | dc2-spine2 | Configuration | Verifies ZeroTouch is disabled | VerifyZeroTouch | NOT RUN | - |
| 1664 | dc2-spine2 | Field Notices, Software | Verifies if the device has exposeure to FN72, and if the issue has been mitigated | VerifyFieldNotice72Resolution | NOT RUN | - |
| 1665 | dc2-spine2 | Field Notices, Software | Verifies the device is using an Aboot version that fix the bug discussed in the field notice 44 (Aboot manages system settings prior to EOS initialization) | VerifyFieldNotice44Resolution | NOT RUN | - |
| 1666 | dc2-spine2 | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1667 | dc2-spine2 | Hardware | Verifies if all transceivers come from approved manufacturers. | VerifyTransceiversManufacturers | NOT RUN | - |
| 1668 | dc2-spine2 | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1669 | dc2-spine2 | Hardware | Verifies the device temperature. | VerifyTemperature | NOT RUN | - |
| 1670 | dc2-spine2 | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1671 | dc2-spine2 | Hardware | Verifies the power supplies status. | VerifyEnvironmentPower | NOT RUN | - |
| 1672 | dc2-spine2 | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1673 | dc2-spine2 | Hardware | Verifies the status of power supply fans and all fan trays. | VerifyEnvironmentCooling | NOT RUN | - |
| 1674 | dc2-spine2 | Hardware | Verifies the system cooling status. | VerifyEnvironmentSystemCooling | NOT RUN | - |
| 1675 | dc2-spine2 | Hardware | Verifies the transceivers temperature. | VerifyTransceiversTemperature | NOT RUN | - |
| 1676 | dc2-spine2 | Hardware | Verifies there are no adverse drops on DCS7280E and DCS7500E | VerifyAdverseDrops | NOT RUN | - |
| 1677 | dc2-spine2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet1 - P2P_LINK_TO_DC2-LEAF1A_Ethernet2 = 'up' | NOT RUN | - |
| 1678 | dc2-spine2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet2 - P2P_LINK_TO_DC2-LEAF1B_Ethernet2 = 'up' | NOT RUN | - |
| 1679 | dc2-spine2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet3 - P2P_LINK_TO_DC2-LEAF2A_Ethernet2 = 'up' | NOT RUN | - |
| 1680 | dc2-spine2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet4 - P2P_LINK_TO_DC2-LEAF2B_Ethernet2 = 'up' | NOT RUN | - |
| 1681 | dc2-spine2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet5 - P2P_LINK_TO_DC2-LEAF3A.ARISTA.COM_Ethernet2 = 'up' | NOT RUN | - |
| 1682 | dc2-spine2 | Interfaces | Verifies the status of the provided interfaces. | Interface Ethernet6 - P2P_LINK_TO_DC2-LEAF3B.ARISTA.COM_Ethernet2 = 'up' | NOT RUN | - |
| 1683 | dc2-spine2 | Interfaces | Verifies the status of the provided interfaces. | Interface Loopback0 - EVPN_Overlay_Peering = 'up' | NOT RUN | - |
| 1684 | dc2-spine2 | IP Reachability | ip reachability test p2p links | Source: dc2-spine2_Ethernet1 - Destination: dc2-leaf1a_Ethernet2 | NOT RUN | - |
| 1685 | dc2-spine2 | IP Reachability | ip reachability test p2p links | Source: dc2-spine2_Ethernet2 - Destination: dc2-leaf1b_Ethernet2 | NOT RUN | - |
| 1686 | dc2-spine2 | IP Reachability | ip reachability test p2p links | Source: dc2-spine2_Ethernet3 - Destination: dc2-leaf2a_Ethernet2 | NOT RUN | - |
| 1687 | dc2-spine2 | IP Reachability | ip reachability test p2p links | Source: dc2-spine2_Ethernet4 - Destination: dc2-leaf2b_Ethernet2 | NOT RUN | - |
| 1688 | dc2-spine2 | IP Reachability | ip reachability test p2p links | Source: dc2-spine2_Ethernet5 - Destination: dc2-leaf3a.arista.com_Ethernet2 | NOT RUN | - |
| 1689 | dc2-spine2 | IP Reachability | ip reachability test p2p links | Source: dc2-spine2_Ethernet6 - Destination: dc2-leaf3b.arista.com_Ethernet2 | NOT RUN | - |
| 1690 | dc2-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: dc2-leaf1a_Ethernet2 | NOT RUN | - |
| 1691 | dc2-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: dc2-leaf1b_Ethernet2 | NOT RUN | - |
| 1692 | dc2-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: dc2-leaf2a_Ethernet2 | NOT RUN | - |
| 1693 | dc2-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: dc2-leaf2b_Ethernet2 | NOT RUN | - |
| 1694 | dc2-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: dc2-leaf3a.arista.com_Ethernet2 | NOT RUN | - |
| 1695 | dc2-spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet6 - remote: dc2-leaf3b.arista.com_Ethernet2 | NOT RUN | - |
| 1696 | dc2-spine2 | NTP | Synchronised with NTP server | NTP | NOT RUN | - |
| 1697 | dc2-spine2 | Security | Verifies if the eAPI has a valid SSL profile. | VerifyAPIHttpsSSL | NOT RUN | - |
| 1698 | dc2-spine2 | SNMP | Verifies if the SNMP agent has IPv4 ACL(s) configured. | VerifySnmpIPv4Acl | NOT RUN | - |
| 1699 | dc2-spine2 | SNMP | Verifies if the SNMP agent has IPv6 ACL(s) configured. | VerifySnmpIPv6Acl | NOT RUN | - |
| 1700 | dc2-spine2 | SNMP | Verifies if the SNMP agent is enabled. | VerifySnmpStatus | NOT RUN | - |
| 1701 | dc2-spine2 | Software | Verifies the device is running one of the allowed EOS version. | VerifyEOSVersion | NOT RUN | - |
| 1702 | dc2-spine2 | Software | Verifies the device is running one of the allowed TerminAttr version. | VerifyTerminAttrVersion | NOT RUN | - |
| 1703 | dc2-spine2 | System | Verifies if NTP is synchronised. | VerifyNTP | NOT RUN | - |
| 1704 | dc2-spine2 | System | Verifies that no partition is utilizing more than 75% of its disk space. | VerifyFileSystemUtilization | NOT RUN | - |
| 1705 | dc2-spine2 | System | Verifies the device uptime. | VerifyUptime | NOT RUN | - |
| 1706 | dc2-spine2 | System | Verifies the last reload cause of the device. | VerifyReloadCause | NOT RUN | - |
| 1707 | dc2-spine2 | System | Verifies there are no agent crash reports. | VerifyAgentLogs | NOT RUN | - |
| 1708 | dc2-spine2 | System | Verifies there are no core dump files. | VerifyCoredump | NOT RUN | - |
| 1709 | dc2-spine2 | System | Verifies whether the CPU utilization is below 75%. | VerifyCPUUtilization | NOT RUN | - |
| 1710 | dc2-spine2 | System | Verifies whether the memory utilization is below 75%. | VerifyMemoryUtilization | NOT RUN | - |
