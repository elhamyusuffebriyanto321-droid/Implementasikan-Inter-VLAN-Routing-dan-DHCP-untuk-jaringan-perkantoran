Switch>enable
Switch#configure terminal
Switch(config)#vlan 30
Switch(config-vlan)#name VLAN30
Switch(config-vlan)#vlan 40
Switch(config-vlan)#name VLAN40
Switch(config-vlan)#exit

Switch(config)#interface range f0/2-4
Switch(config-if-range)#switchport mode access
Switch(config-if-range)#switchport access vlan 30
Switch(config-if-range)#interface range f0/5-7
Switch(config-if-range)#switchport mode access
Switch(config-if-range)#switchport access vlan 40
Switch(config-if-range)#exit

Switch(config)#interface f0/1
Switch(config-if)#switchport mode trunk
