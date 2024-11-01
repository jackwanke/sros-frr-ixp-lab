# IXP Lab with BIRD, FRR as Peers and BIRD, OpenBGPd as Route Servers

A containerlab-based lab designed to offer hands-on experience with IXP technologies and best practices.

Setup linux bridge: sudo ip link add name ixp-net type bridge
Set bridge up: sudo ip link set ixp-net up
Start lab: sudo clab deploy -t ixp.clab.yml

Lab documentation is available at <https://containerlab.dev/lab-examples/peering-lab/>
