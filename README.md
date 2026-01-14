# Routing-static
router 1 
Router1> enable
Router1# configure terminal
Router1(config)# ip route 192.168.2.0 255.255.255.0 10.10.10.2
Router1(config)# exit

router 2 
Router2> enable
Router2# configure terminal
Router2(config)# ip route 192.168.1.0 255.255.255.0 10.10.10.1
Router2(config)# exit
