# opensim-NAT
Set of ini files for concealing private port behind NAT.

Opensimulator version : 0.9.1

Replace the three files from your opensim distribution:

* Robust.HG.ini 
* Opensim.ini
* config-include/GridCommon.ini
 
and edit the variable PrivURL to point to your ROBUST server, e.g.

	PrivURL = "http://localhost"

or
	PrivURL = "http://192.168.0.15"You may nos close port 8003 at the gateway.