# Cloud Mininet

## Usage 

Before running this run the pox server as

`sudo python pox.py forwarding.l2_multi openflow.discovery --eat-early-packets openflow.spanning_tree --no-flood --hold-down`
 
`sudo python vishnu_s.py`

Input number of switches and hosts when asked

wait for 10 (for each 20 devices you add) seconds before testing pingall for network discovery
