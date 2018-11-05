# RHEL 7.x Ansible Hardening 

This repository contains a list of playbooks created by OpenSCAP and based on the following security profiles:

| Profile  | Description  |   
|---|---|
| [Standard Profile](standard.yml)  | Standard security baseline of Red Hat Enterprise Linux 7 system. Regardless of your system's workload all of these checks should pass.  |
| [Certified Cloud Providers](rhccp.yml) | A *draft* SCAP profile for Red Hat Certified Cloud Providers. |
| [CIS Profile](c2s.yml)  | Inspired by the Center for Internet Security (CIS) Red Hat Enterprise Linux 7 Benchmark, v2.1.1 - 01-31-2017  |
| [PCI-DSS Profile](pci_dss.yml)  | A *draft* profile for PCI-DSS v3 |
| [Docker Host](docker_host.yml) | Ensures standard security baseline of Red Hat Enterprise Linux 7 system running the docker daemon. This discussion is currently being held on open-scap-list@redhat.com and scap-security-guide@lists.fedorahosted.org  |
| [RHEV Hypervisor Profile](rhevh.yml) | STIG for Red Hat Virtualization Hypervisor.  |

