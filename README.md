# My pcap Storage

### Just a collection
Records the pcaps what's it for...

### Now recording...
- 83_84_85_91_load_balancer.pcap  
	date: 2019/12/2  
	83,84: Local ip address for opensips  
	91: Virtual ip address of 83,84  
	85: Local ip address of asterisk  
	77: Local ip address of caller (Linphone 19900000003)  
	56: Local ip address of call register (asterisk)  

- 20.84.pcap  
	date: 2019/12/3  
	mac_lvs: 00:50:56:90:d7:41
	mac_83(osips): 00:50:56:90:f9:de  
	mac_84(osips): 00:50:56:90:6a:45  
	Notes: stateful->stateless proxy
	tm,rr,dialog,uac has been removed. ?
	load_balancer->dispatcher
	record_route, uac_replace_from/to cannot use...

