# dnsmasq
Offsite fork of dnsmasq, for implementing some features I need/use.

Original can be found at [http://www.thekelleys.org.uk/dnsmasq/doc.html](http://www.thekelleys.org.uk/dnsmasq/doc.html). Official git at  *git://thekelleys.org.uk/dnsmasq.git*.

# Status
- our master is at 2.80test2-28-g312945e (*check official git for real HEAD*)

# Addons
- Added **virtual** dhcp-range - this allows to assign static addresses via *dhcp-host* even if the assigned address is not reachable via dhcp interface.
- Added multiple static routes - allow sending of multiple static routes as RFC says
