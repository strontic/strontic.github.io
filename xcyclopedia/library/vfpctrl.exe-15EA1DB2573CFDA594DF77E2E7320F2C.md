
# vfpctrl.exe 

* File Path: `C:\WINDOWS\system32\vfpctrl.exe`
* Description: vfpctrl.exe
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `15EA1DB2573CFDA594DF77E2E7320F2C`
SHA1 | `432933BDC00C3C1491A39F037E614D0E569D81DC`
SHA256 | `116E8F379CBC518E257C5862C4E0FEB166FBB9F66311FE2C34F8E9C6EDC58F11`
SHA384 | `731108378085B53BA149CF85FC3F5DF84665588CFB5B9959561F0021A57BE3851C4353FC8CB834A099935491EAFA03A0`
SHA415 | `A647223AD3CD71D76106D573896CE166B980842AA50E44D326707D9D74A26A56C6E1528AAC8FE52DC1E04FA20D5F05CFEBAB6F5AA5B35C983A9A862605B28386`
SSDEEP | `6144:43r73bllgQM/gTvK7zO5M5JP61njuK7D7av9zujDqN05dfQZI:4H3sUK7zOiF2`

## Runtime Data

### Usage (stdout):
```Batchfile


VFP control and diagnostics utility

    /port "[port name]" - specify the target port.

    /switch "[switch name]" - specify the target switch.

    /layer [layer_id] - specify the target layer.

    /group [group_id] - specify the target group.

    /rule [rule_id] - specify the target rule.

    /nat-pool [nat_pool_id] - specify the target NAT pool.

    /nat-range [nat_range_id] - specify the target NAT range.

    /space [space_id] - specify the map space.

    /mapping [mapping_id] - specify the mapping id.

    /queue [queue_id] - specify the QoS queue id.




    /tag [tag_id] - specify the target tag.

    /rulecounter [rulecounter_id] - specify the rule counter id.




    /list-vmswitch-port - list the active ports and NICs on all vmswitches in the system.

    /get-vmswitch-port-counter - get vmswitch counters for the given port.

    /get-binding - get the binding type of VFP currently loaded.

    /get-aperture-state - queries if Hyper-V aperture is supported on the node.

    /get-version - get the version of VFP currently loaded.


  ======================== Port Commands ========================

    /enable-port - enable VFP on the given port.

    /disable-port - disable VFP on the given port.

    /block-port - block traffic on the given enabled port.

    /block-port-on-restore - block traffic on restore on the given enabled port.

    /unblock-port - unblock traffic on the given enabled port.

    /unblock-port-on-restore - unblock traffic on restore on the given enabled port.

    /inject - inject a packet to a port.

    /intercept - test intercept event.

    /injectex - inject a packet with metadata to a port.

    /interceptex - test intercept event with packet metadata.

    /interceptex2 "[queue type]"/- test intercept event with specific queues and packet metadata.        queue type - 1:default; 2:dhcpv6; 3:dhcpv4; 4:arp; 5:ndp

    /get-port-state - get the port state.

    /get-port-counter - get the performance counter of the port.

    /get-tcp-log - get the address log of the port.

    /set-address-info "[ca ipv4] [pa ipv4] [mac] [fake mac] [flags] [ca ipv6] [pa ipv6] " - set the port's address information.
        flags - 16:virtualized; 32:intercept, 64:mac virtualized, 128:process non-ip, 256:process client DHCP, 512:DHCPV6 intercept, 1024:DHCPV4 intercept, 2048:ARP intercept, 4096:NDP intercept, 8192:RDP intercept 

    /get-address-info - get the port's address information.

    /set-guard-config [flags] - set the VFP guard configurations.
        flags:
            1:arp guard; 2:arp limiter; 4:dhcp guard; 8:dhcp limiter
            16:block bcast; 32:block non-ip; 64:arp filter
            128:ipv4 guard; 256:ipv6 guard; 2048: icmpv6 limiter; 4096: NDP guard; 8192:timestamp rx guard
            16384:mac guard 32768: broadcast limiter
        dscp tx flags:
            default: bypass dscp flags
            512: set dscp flags to all zeros
        dscp rx flags:
            default: bypass dscp flags
            1024: set dscp flags to all zeros

    /get-guard-config - get the VFP guard configurations.

    /set-arp-limiter-config "[timespan] [threshold] [penalty]" - set the ARP limiter configurations.

    /get-arp-limiter-config - get the ARP limiter configurations.

    /set-dhcp-limiter-config "[timespan] [threshold] [penalty]" - set the DHCP limiter configurations.

    /get-dhcp-limiter-config - get the DHCP limiter configurations.

    /set-icmpv6-limiter-config "[timespan] [threshold] [penalty]" - set the Icmpv6 limiter configurations.

    /get-icmpv6-limiter-config - get the icmpv6 limiter configurations.

    /set-broadcast-limiter-config "[timespan] [threshold] [penalty]" - set the Broadcast limiter configurations.

    /get-broadcast-limiter-config - get the Broadcast limiter configurations.

    /set-arp-filter "[addr]{0,1024}" - set the allowed list of target IPv4 addresses in arp packets.

    /get-arp-filter - get the allowed list of target IPv4 addresses in arp packets.

    /get-frag-cache-stats - get the fragmentation cache stats of the port.

    /get-port-flow-stats - get the unified flow statistics of the port.

    /get-port-flow-settings - get the unified flow settings of the port.

    /set-port-flow-limit "[in|out] [flow class] [limit]" - set the unified flow limit of a port.
        class [0] - total entry
        class [1] - half open flow
        class [2] - total flow
        class [3] - tcp flow
        class [4] - udp flow
        class [5] - other flow

    /set-port-flow-settings "[Half Ttl] [Pending Timeout] [TIME_WAIT Ttl] [Default Ttl] [Fragment Size] [Max Pending Entries] [Max Pending Packets] [TCP tracking] [Enable Unified Flows] [Support Reordered Fragments] [Enable Offloads] [Force Unified Flows] [Enable Fast UF Locking][Subsume Layer Flows]  [Auto condition Enabled] [Monitoring Ping Enabled] [enable hyper-v aperture] [aperture batch size] [Enable ESP Unified Flows]"
	- set the unified flow settings of the port.

    /clear-port-flow-state - clear the unified flow state of a port as well as all layer flow states.

    /clear-port-unified-flow-state - clear the unified flow state of a port.

    /list-unified-flow - list all the unified flows of a port.

    /sample-unified-flow "[sample size] [reset counters] [flags]"- sample the unified flows of a port.
        flags - 1:Sample Flow Pairs 2:Sample Inbound Only 4:Sample Outbound Only

    /add-local-ipv4-addr "[addr]{0,4}" - add a list of local IPv4 addresses.

    /remove-local-ipv4-addr "[addr]{0,4}" - remove a list of local IPv4 addresses.

    /get-local-ipv4-addr - get the list of local IPv4 addresses.

    /add-local-ipv6-addr "[addr]{0,4}" - add a list of local IPv6 addresses.

    /remove-local-ipv6-addr "[addr]{0,4}" - remove a list of local IPv6 addresses.

    /get-local-ipv6-addr - get the list of local IPv6 addresses.

    /set-next-hop-addr - set the next-hop MAC address.

    /set-port-parser-settings "[enable vxlan] [enable encrypted vxlan] [parse inbound vxlan outside src port range] [src vxlan port base] [src vxlan port range] [src encrypted vxlan port base] [src encrypted vxlan port range] [ignore global settings] [parse rdma] [rdma dest port] " - set the port parser settings.

    /get-port-parser-settings - get the port parser settings.

    /get-next-hop-addr - get the next-hop MAC address.

    /set-trace-filters "[in|out|both] [src_mac] [dst_mac] [TNI] [VlanId] [proto] [src_ip] [src_port] [dst_ip] [dest_port]"- configures trace filters on the given port.

    /remove-trace-filters - removes trace filters configured on the given port.


  ======================== Rule Commands ========================

    /add-layer "[id] [name] [stateful|stateless] [priority] [flags]" - add a new layer.
        flags - 1:default allow; 2:hairpin; 4:clear TNI; 16:enable monitoring ping responder


    /force-add-layer "same as add-layer" - forcibly add a new layer.

    /remove-layer - remove a layer.

    /list-layer - list all the layers.

    /remove-all-layer - remove all the layers of a given port.

    /get-layer-counter - get the performance counter of a layer.

    /get-layer-ttl - get the ttl settings of a layer.

    /get-layer-metadata-value "[key string] " - get the metadata value for a specific key in a layer.

    /list-layer-metadata-keys - list all the metadata keys in a layer.

    /list-layer-metadata-values - list all the metadata keys and values entry of a layer.

    /get-flow-stats - get the flow stats of the layer.

    /list-active-ping - list all the active pings flow Ids.

    /clear-active-ping - clear all the active ping flows.

    /ping-endpoint "[proto] [ipv4|ipv6 flag] [src mac] [dest mac] [src ip] [dest ip] [src port] [dest port] [retrycount] [TNI] [with option] [diagnostic tunnel Id]" set the initiating ping info.
        ipv6 flag- Ipv6:1; Ipv4: 0
        protocol - ICMP:1; TCP:6; UDP:17 
        with option - 0: ping has no option, 1: ping has an option with the magic number stamp
        diagnostic tunnel Id - 0: none, nonzero: tunnel Id (e.g., GRE key)


    /enable ping responder on a layer

    /disable ping responder on a layer

    /set-flow-limit "[in|out] [flow class] [limit]" - set the flow limit.
        class [0] - total entry
        class [1] - half open flow
        class [2] - total flow
        class [3] - tcp flow
        class [4] - udp flow
        class [5] - other flow

    /set-layer-ttl "[half-open ttl] [time_wait ttl]" - set the ttl settings of a layer.

    /set-layer-metadata-value "[key string] [value string]" - set the metadata value for a specific key in a layer.

    /delete-layer-metadata-key "[key string]" - delete the metadata entry of a layer.

    /list-flow - list all the flows of a layer.

    /sample-flow "[sample size] [flags]"- sample the flows of a layer.
        flags - 1:Sample Flow Pairs 2:Sample Inbound Only 4:Sample Outbound Only

    /clear-flow - clear all the flows of a layer.

    /replace-layer-flow-address - replaces addresses in layer flows if it matches the provided address.

    /match-tuple "[proto] [src_ip] [src_prt] [dest_ip] [dest_prt] [in|out] [flag]" - find the flow or rule entry matched by a 5-tuple at a given layer in the specified direction.
        flags - 1:tcp syn 2: monitoring ping flag


    /process-tuples "encap [encap_tuples]{0,2} [inner_tuples] [in|out] [flags]" - simulates packet processing through VFP layers for the given tuples in the specified direction.
        encap_tuples - [encap_type] [[src_mac] [dst_mac]]{0,1} [src_ip] [dest_ip] [tenant_id|gre_key] - max currently supported encaps is 2, ensure encap_tuples supercede the inner_tuples
               encap_type - 1:IP-in-GRE 2:IP-in-IP 3:MAC-in-GRE (NVGRE) 4:VXLAN
        inner_tuples - [[src_mac] [dst_mac] [TNI] [VlanId]]{0,1} [proto] [src_ip] [src_prt] [dest_ip] [dest_prt]
        flags - 1:tcp syn 2: monitoring ping flag


    /add-group "[id] [name] [in|out|inv6|outv6] [priority] [[group_condition]] [[group_match_type]]" - add a new group.
        group_condition: [proto] [src_ip] [src_prt] [dest_ip] [dest_prt]
        group_match_type: [priority_based|priority_based_single_condition_opt|priority_based_multi_condition_opt|priority_based_all_condition_opt|priority_based_auto_condition_opt|lpm] [match_condition_type..*5]
            match_condition_type for priority_based, priority_based_all_condition_opt, priority_based_auto_condition_opt : none
            match_condition_type for priority_based_single_condition_opt, priority_based_multi_condition_opt, lpm :
                VfxConditionDestinationIp|VfxConditionDestinationIpRange|VfxConditionDestIpv4Range|
                VfxConditionSourceIp|VfxConditionSourceIpRange|VfxConditionSrcIpv4Range|
                VfxConditionDestinationIpv6|VfxConditionDestIpv6Range|VfxConditionSourceIpv6|VfxConditionSrcIpv6Range|
            match_condition_type for priority_based_single_condition_opt, priority_based_multi_condition_opt :
                VfxConditionSourcePort|VfxConditionDestinationPort|
                VfxConditionSourcePortRange|VfxConditionDestinationPortRange|
                VfxConditionGreKey|VfxConditionGreKeyRange


    /force-add-group "same as add-group" - forcibly add a new group.

    /remove-group - remove a group.

    /set-group-condition "[proto] [src_ip] [src_prt] [dest_ip] [dest_prt]" - set a group condition.

    /remove-group-condition - remove a group condition.

    /set-group-option "[priority_based|priority_based_single_condition_opt|priority_based_multi_condition_opt|priority_based_all_condition_opt|priority_based_auto_condition_opt|lpm] [match_condition_type..*5]" - set group options.
        match_condition_type for priority_based, priority_based_all_condition_opt, priority_based_auto_condition_opt : none
        match_condition_type for priority_based_single_condition_opt, priority_based_multi_condition_opt, lpm :
            VfxConditionDestinationIp|VfxConditionDestinationIpRange|VfxConditionDestIpv4Range|
            VfxConditionSourceIp|VfxConditionSourceIpRange|VfxConditionSrcIpv4Range|
            VfxConditionDestinationIpv6|VfxConditionDestIpv6Range|VfxConditionSourceIpv6|VfxConditionSrcIpv6Range|
        match_condition_type for priority_based_single_condition_opt, priority_based_multi_condition_opt :
            VfxConditionSourcePort|VfxConditionDestinationPort|
            VfxConditionSourcePortRange|VfxConditionDestinationPortRange|
            VfxConditionGreKey|VfxConditionGreKeyRange


    /list-group - list all the groups of a given layer.

    /remove-all-group - remove all the groups of a given layer.

    /add-rule "[proto] [src_ip] [src_prt] [dest_ip] [dest_prt] [flag] [ttl] [pri] [type] [data]" - add a rule.
        flags - 1:terminating; 2:stateful; 4:non-syn only; 8:track tcp state; 16:syn-only; 32: skip hairpinning; 128:opt-condition; 4096:audit matches; mirror:16384; monitoring ping: 32768
        protos - 6:TCP; 17:UDP; 47:GRE; 4:IP-in-IP; 1:ICMP; 41:IPv6-in-IP; 58:ICMPv6; 252:VXLAN; 251:Encrypted VXLAN (available only to mapdecap rules)
        data:
          allow, block, mapipin, mapipout, mapmacin, mapmacout, pingresponse, caredirect: 
          mapencap: [space] [mss_del]/[rev_mss_del] [src_pa] [key] [flags] [local_cert_thumbprint] [remote_cert_subject_name]
              mapencap flags - 4096:MAC lookup; 8192:CA route; 16384:Use Mapping TNI; 32768:CA route with CA MAC
          routeencap: [mss_del]/[rev_mss_del] [flags] [[space]] [[src_pa1] [dest_pa1] [mac1] [key1] [local_cert_thumbprint1] [remote_cert_subject_name1] ..8*]] 
              routeencap flags - 512:Use Mapping 1024:L3 Discovery (GW behind LB) 2048:L4 Discovery 4 (ILB behind LB) 4096: Fix Inner Mac 8192: Use PA MAC 16384: Decrement TTL 32768: Fix Inner MAC use CA source MAC
              rule flags - 256:vnetfpredirect; 512:source preserved redirect
              encap flags - 1:NVGRE format (MAC-in-GRE); 2:IP-in-GRE (default); 4:IP-in-IP; 8: VXLAN; 16: Encrypted VXLAN (available only to mapencap, routeencap, and lbnat rules)
          mapdecap: [space] [mss_del]/[rev_mss_del] [local_cert_thumbprint] [remote_cert_subject_name] [metadata type]
              mapdecap flags - 256:Preserve Inner MAC; 512:Push VSID; 1024:Push TNI as metadata;
          mapin/mapout: [space] [mss_del]/[rev_mss_del] [[rewrite address]]
          mapnat: [space] [mss_del]/[rev_mss_del] [[rewrite address]]
              nat flags - 256:Source NAT (default is Dest NAT) 
          nat: [ip] [port] [mss_del]/[rev_mss_del]
              nat flags - 256:Source NAT; 512:Dest NAT (default); 1024:IP-only NAT
          dynnat: [nat_id] [mss_del]/[rev_mss_del]
              dynnat flags - 256:Source NAT (default); 512:Dest NAT; 2048:Enable TIME_WAIT Assassination; 4096:Use existing UDP port binding
          decap: [metadata type] [mss_del]/[rev_mss_del]
              decap flags - 256:Preserve Inner MAC; 512:Push VSID; 1024:Push TNI as metadata;
          tunnelednat: [mss_del]/[rev_mss_del] l4nat [baseport] [numports] [src_mac] [dest_mac] [flags] [snatip1..64*]
          tunnelednat: [mss_del]/[rev_mss_del] mappedl4nat [baseport] [numports] [src_mac] [dest_mac] [flags] [snatiprange]
          tunnelednat: [mss_del]/[rev_mss_del] [l3nat|nonat] [src_mac] [dest_mac] [flags] [snatiprange1..64*]
              tunneled nat flags - 1:Block RFC1918; 2:NAT only RFC1918
          qos: [rate in Mbps] [queue depth] [queue burst size] 
          transpose: [mss_del]/[rev_mss_del] [[hairpin_switch] [hairpin_port]] [[Metadata Type]:[Value]] [[TNI] [VlanId]] modify [src_mac] [dst_mac] [src_ip] [dst_ip] [src_port] [dst_port] [ttl_dec] [[partial rewrite type] [input byte start] [input byte end] [rewrite byte position] ..4*]]
          transpose: [mss_del]/[rev_mss_del] [[hairpin_switch] [hairpin_port]] [[Metadata Type]:[Value]] [[TNI] [VlanId]] encap [src_mac] [dst_mac] [src_ip] [dst_ip] [encap_type] [key] [[partial rewrite type] [input byte start] [input byte end] [rewrite byte position] ..4*]]
          transpose: [mss_del]/[rev_mss_del] [[hairpin_switch] [hairpin_port]] [[Metadata Type]:[Value]] [[TNI] [VlanId]] decap
          paroute: [compartment_id] [vlan_id | *] [[cache_limit] [cache_entry_timeout] [ifindex] [flags]]
              paroute flags - 4096:Force cache pruning;
          mark: [DSCP class] 
          lbnat: [[space]] [mss_del]/[rev_mss_del] [flags] [[diprange1] [[port1]] ..64*] 
              lbnat flags - 4096: MAC fixup 8192: Use PA MAC in case of encap 16384: Decrement TTL 32768:  MAC fixup use CA source MAC 65536: Modify destination IP 131072: Modify destination port 262144: Encap 524288: Create flow;


    /add-rule-ex "[id] [name] [proto] [src_ip] [src_prt] [dest_ip] [dest_prt] [flag] [ttl] [pri] [type] [data]" - add a rule with ID and name.

    /add-rule-ex2 "[id] [name] [proto] [src_ip] [src_prt] [dest_ip] [dest_prt] [flag] [ttl] [pri] [ruleflags] [rulecounterid] [type] [data]" - add a rule with extended flags and counters on port.

    /add-mac-rule "[id] [name] [src_mac] [dest_mac] [TNI] [VlanId] [proto] [src_ip] [src_prt] [dest_ip] [dest_prt] [flag] [ttl] [pri] [type] [data]" - add a rule with MAC conditions

    /add-metadata-rule "[id] [name] [metadata type:value] [src_mac] [dest_mac] [TNI] [VlanId] [proto] [src_ip] [src_prt] [dest_ip] [dest_prt] [flag] [ttl] [pri] [type] [data]" - add a rule with MAC conditions

    /add-tag-rule "[id] [name] [src_tag] [dest_tag] [proto] [src_ip] [src_prt] [dest_ip] [dest_prt] [flag] [ttl] [pri] [type] [data]" - add a rule with TAG conditions

    /force-add-rule "same as add-rule-ex" - add a rule and remove exsiting one with same ID.


    /remove-rule - remove a rule.

    /list-rule - list all the rules of a group.

    /remove-all-rule - remove all the rules of a given group.

    /add-rule-set "[rule description file name]" - add rules described in the file

    /replace-rule-set "[rule description file name]" - replace rules described in the file

    /get-rule-counter - get the performance counter of a rule.

    /get-rule-info - get extended information of a rule.


  ======================== NAT Commands ========================

    /get-rule-classifier-info - get the classifier info for a rule.

    /add-nat-pool "[id] [name] [flag]" - add a NAT pool.
        flags - 1:reuse udp port binding

    /list-nat-pool - list all the NAT pools.

    /remove-nat-pool - remove a NAT pool.

    /remove-all-nat-pool - remove all NAT pools.

    /get-nat-pool-counter - get NAT pool performance counters.

    /reset-nat-pool-counter - reset NAT pool performance counters.

    /deposit-nat-range "[ip] [prt_start] [prt_end] [reuse_cnt]" - deposit a NAT range.

    /withdraw-nat-range [idle_timeout] - withdraw an idle NAT range.

    /remove-nat-range "[ip] [port_start] [end_start]" - remove a NAT range.

    /list-nat-range - list the NAT ranges.

    /test-nat-event "[ip] [prt_start] [prt_end] [reuse_cnt]" - test the NAT event.

    /list-nat-port-binding - list all the nat port bindings of a nat pool.

    /test-nat-event-async "[ip] [prt_start] [prt_end] [reuse_cnt]" - test the NAT event.


  ======================== Mapping Commands ========================

    /add-space "[id] [name]" - add a map space.

    /list-space - list all the map spaces.

    /remove-space - remove a mapping space.

    /remove-all-space - remove all mapping spaces.

    /test-mapping-event - test the mapping event.

    /set-space-config "[timeout] [pending timeout] [frag size]" - set the map space configurations.

    /get-space-config - get the map space configurations.

    /get-space-packet-counter - get the map space packet counters.

    /get-space-index-counter [pa|ca] - space index performance counters.

    /add-mapping "[pa] [ca] [pamac] [flag] [[camac] [tni]]" - add a mapping.
        flags - 1:permanent; 2:non unique pa, 4: mac mapping

    /remove-mapping "[pa|ca|camac] [[ip] | [camac tni]]" - remove a mapping.

    /list-mapping - list all the mapping.

    /remove-all-mapping - remove all the mappings of a given space.


  ======================== QOS Commands ========================

    /set-qos-config "[enable HW caps] [enable HW reservations] [enable SW reservations] [flags]" - configure QoS setting for a switch.
        flags - 1:force_defer

    /get-qos-config - retrieve QoS config of a switch.

    /set-qos-line-config "[reservation mode] [default reservation] [link speed percentage] [default queue depth] [default queue burst size]  [default queue under-utilized] [default queue over-utilized] [default queue headroom] [default queue rampup time] [default queue min rate]"- configure QoS setting for transmit reservation.

    /get-qos-line-info - retrieve QoS information for egress reservation.

    /get-qos-reservation-info - get rate calculation events

    /add-queue "[id] [name] [EnforceIntraHostLimit] [tx limit] [tx reservation] [rx limit]  [tx queue depth] [rx queue depth] [tx burst size] [rx burst size]  [under-utilized] [over-utilized] [headroom] [rampup time] [min rate]" - add a user-configured QoS queue.

    /remove-queue [queue_id] - remove a user-configured QoS queue.

    /set-queue-config "[EnforceIntraHostLimit] [tx limit] [tx reservation] [rx limit]  [tx queue depth] [rx queue depth] [tx burst size] [rx burst size]  [under-utilized] [over-utilized] [headroom] [rampup time] [min rate]"  - update a QoS queue.

    /list-queue [queue_id] - shows user-configured QoS queues & their configs.

    /get-queue-info [queue_id] "all" | "stats" | "packet_events" | "resume_events" - shows max queue counters for this QoS queue.

    /set-port-queue "queue_id"- associate a port with a Qos queue.

    /clear-port-queue - disassociate a port from a Qos queue.

    /get-port-queue - list the queues that this port is associated with.

    /set-port-allowed-tni-list "[TNI]{1,64}" - set a list of TNIs which will always be allowed during forwarding on a port.

    /clear-matching-flows "[Post Flow Match] [Protocol] [Source IP] [Source Port] [Destination IP] [Destination Port] [Match TNI] [TNI] [Destination Mac] [Source Mac]" - delete flows matching specified conditions. Specify [0|1] for [Post Flow Match] to determine if match should be determined specifically by the flow type

    /clear-port-allowed-tni-list - clears the list of allowed TNIs for the port.

    /get-port-allowed-tni-list - get the list of allowed TNIs for the port.

    /get-dhcp-log - get the dhcp protocol log of the port.

    /set-dscp-config - "[use mapping] [rx guard] [tx guard]".

    /set-dscp-config

    /add-dscp-mapping - "[dscp class] [tc] [allow]".

    /set-dscp-mapping - "[dscp class] [tc] [allow]".

    /clear-dscp-mapping - clear all dscp class mappings

    /get-port-tx-dscp-counter - get packet and byte counters for each DSCP class on transmit for the port.

    /set-port-dtls-settings "[Larval Lifetime Sec] [Lifetime Min] [Lifetime KBytes] [Recv Keepalive Timeout Sec] [Send Keepalive Interval Sec] [Max Session Count] [Offloads Enabled] [NumClientAlgos] [ClientAlgo1 ClientAlgo2 ...] [NumServerAlgos] [ServerAlgo1 ServerAlgo2 ...]

    /get-port-dtls-settings - get the DTLS settings of the port.

    /list-dtls-sessions - list all the DTLS sessions of a port.

    /list-pa-discovery-route - list all the PA discovery route of a port.

    /enable-port-pcw-counters - enable PCW counters for the given port.

    /disable-port-pcw-counters - disable PCW counters for the given port.

    /enable-qos-queue-pcw-counters - enable PCW counters for the given QoS Queue.

    /disable-qos-queue-pcw-counters - disable PCW counters for the given QoS queue.

    /get-dscp-mapping - list dscp to tc mappings


  ======================== Switch Commands ========================

    /test-serialization "[blockPort]"- verify serialization of VFP objects on a port.

    /save-serialization "filename"- writes serialized config for port to specified file.

    /set-serialization "filename"- applies serialized config from file to port.

    /deregister-event - deregister an event from a mapping space, or a nat pool - if neither is specified, deregister the intercept event.

    /deregister-eventex "[event type] [[queue type]]" - deregister the intercept irp from a specific interception queue type default, dhcpv6, mapping space, or a nat pool queue.        event type - 1:intercept; 2:nat pool; 3:mapping space        queue type - 1:default; 2:dhcpv6; 3:dhcpv4; 4:arp; 5:ndp;

    /get-switch-forwarding-settings - get forwarding settings for a switch.

    /get-switch-info - get information about a switch.

    /set-switch-allowed-tni-list "[TNI]{1,64}" - set a list of TNIs which will always be allowed during forwarding on a switch.

    /clear-switch-allowed-tni-list - clears the list of allowed TNIs for the switch.

    /get-switch-allowed-tni-list - gets the list of allowed TNIs for the switch.

    /set-switch-forwarding-settings "[innerMacFwd] [reducePortMtuForEncap] [innerMacVmq] [forwardAllTrafficToExternalNetwork] [usePacketTNI] [skipTNIValidationForInnerMacForwarding] [dropLoopbackHairpin]" - set forwarding settings for a switch.


  ======================== Global Commands ========================

    /set-protocol-settings "[dest vxlan port] [enable vxlan] [enable nvgre flowid] [enable ICMP errors] [enable encrypted vxlan] [parse inbound vxlan outside src port range] [src vxlan port base] [src vxlan port range] [src encrypted vxlan port base] [src encrypted vxlan port range] [enable rdma] [dest rdma port]" - set the encapsulation protocol settings.

    /get-protocol-settings - get the encapsulation protocol settings.

    /set-saverestore-settings "[block on restore] [disable switch save restore] [suppress switch restore failures]" - set the save/restore settings.

    /get-saverestore-settings - get the save/restore settings.

    /prepare-for-uninstall- Rundown state dependent on connectivity - service about to be uninstalled.

    /persist-host-state - Persist host state through vhdcache

    /get-gft-port-state - get the port's GFT state.

    /set-processor-dpctimeout"[single dpc timeout] [queued dpc timeout] " - supported only on Azure and WIN2K12R2

    /get-processor-dpctimeout - get processor dpctimeout- supported only on Azure and WIN2K12R2

    /enable-trace-filtering - Enable filtering for per-packet traces.

    /disable-trace-filtering - Disable filtering for per-packet traces.

    /get-trace-filtering-state - get the state of per-packet trace filtering.

    /add-tag "[id] [name] [ipv4/ipv6] [ips]" - add a new tag.


    /list-tag - list all the tags of a port.

    /replace-tag "[id] [name] [ipv4/ipv6] [ips]" - replace ips of a tag

    /force-add-tag "[id] [name] [ipv4/ipv6] [ips]" - forcibly add a new tag.

    /remove-tag - remove a tag.

    /remove-all-tag - remove all the tag of a given port.

    /add-rule-counter - add an extended rule counter on the port.

    /remove-rule-counter - remove an extended rule counter on the port.

    /list-port-rule-counter - list all extended rule counters of a port.

    /get-stack-expansion-state - get the state of stack expansion state.

    /set-stack-expansion-state - set the state of stack expansion state.


```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vfpctrl.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.10000 (WinBuild.160101.0800)
* Product Version: 10.0.18362.10000
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


