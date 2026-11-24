Switch>enable
Switch#configure terminal
Switch(config)#vlan 10
Switch(config-vlan)#name VLAN10
Switch(config-vlan)#vlan 20
Switch(config-vlan)#name VLAN20
Switch(config-vlan)#vlan 30
Switch(config-vlan)#name VLAN30
Switch(config-vlan)#vlan 40
Switch(config-vlan)#name VLAN40
Switch(config-vlan)#exit

Switch(config)#interface range f0/1-3
Switch(config-if-range)#switchport mode access
Switch(config-if-range)#switchport access vlan 10
Switch(config-if-range)#interface range f0/4-6
Switch(config-if-range)#switchport mode access
Switch(config-if-range)#switchport access vlan 20
Switch(config-if-range)#exit

Switch(config)#interface f0/7
Switch(config-if)#switchport mode trunk
Switch(config-if)#interface f0/8
Switch(config-if)#switchport mode trunk
