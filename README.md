# OKD

TASK	HOSTNAME	IP ADDRESS	MEMORY	vCPU	STORAGE
Manager Node
(DNS, HAProxy)
CentOS-Stream-8	apps	192.168.205.16	4GB	4	50GB
Bootstrap Node
Fedora CoreOS	okd4-bootstrap	192.168.205.29	16GB	4	50GB
Control Node 1
Fedora CoreOS	okd4-control-plane-1	192.168.205.30	16GB	4	50GB
Control Node 2
Fedora CoreOS	okd4-control-plane-2	192.168.205.31	16GB	4	50GB
Control Node 3
Fedora CoreOS	okd4-control-plane-3	192.168.205.32	16GB	4	50GB
Compute Node 1
Fedora CoreOS	okd4-compute-1	192.168.205.33	16GB	4	50GB

HOSTNAME		TASK		IP ADDRESS		RAM		vCPU		STORAGE
apps			Bastion		192.168.200.10	4096	2			50GB