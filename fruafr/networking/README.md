# Ansible Collection - fruafr.networking

 Ansible collection for networking tools - Supports Debian and RedHat families

The roles contained in this collection are the following:
- ansible_ping : Ansible ping wrapper
- fw_rules_cockpit : Firewall rules for cockpit
- fw_rules_dhcp_client : Firewall rules for DHCP client (IPv4 and/or IPv6)
- fw_rules_dhcp_server : Firewall rules for DHCP server (IPv4 and/or IPv6)
- fw_rules_dns_server : Firewall rules for DNS server
- fw_rules_forwarding : UFW forwarding rules (Debian family only)
- fw_rules_lxc_lxd: Firewall rules for LXD (port 8443/tcp)
- fw_rules_maas: Firewall rules for MAAS (Debian family only)
- fw_rules_ntp_server : Firewall rules for NTP server
- fw_rules_postgres_server : Firewall rules for PostgreSQL server
- fw_rules_snmp_agent : Firewall rules for SNMP agent (SNMP client)
- fw_rules_snmp_manager : Firewall rules for SNMP manager (SNMP server/trap)
- fw_rules_ssh: Firewall rules for SSH server
- fw_rules_strict: Strict Firewall rules for ufw (Debian family only)
- fw_rules_syslog: Firewall rules for syslog
- host_ip : Displays the host IP address
- hostname_change : Changes the host name
- localhost_reset : Resets the /etc/localhost file
- packages_fail2ban : Install fail2ban
- packages_firewalld : Installs firewalld (RedHat family only)
- packages_network_admin: Install network admin diagnostics tools (tcdump, wireshark, hping3, traceroute, whois...)
- packages_snmp : Installs snmp
- packages_ufw: Installs ufw (Debian family only)
- ping_host : ping a specific host from the targer server
- ping_host_multi : ping multiple hosts from the targer server
- snmp_config : Configure SNMP (/etc/snmp/snmpd.conf)
- snmp_create_user: Create a SNMPv3 user

License
-------
GNU 3.0 or later


Author Information
------------------
David Heurtevent <david@heurtevent.org>