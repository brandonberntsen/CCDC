# CCDC
    Guide for Bind9 http://www.servermom.org/how-to-install-and-setup-bind9-on-ubuntu-server/
    
    -Auto Hardening Script Options-
    Install and Configure UFW firewall;
    Secure shared memory;
    Disable SSH root login and change SSH default port;
    Protect su by limiting access only to admin group;
    Harden network sysctl settings;
    Disable OpenDNS recursion;
    Prevent IP spoofing;
    Harden PHP;
    Install and configure ModSecurity;
    Protect from DDoS attacks with ModEvasive;
    Install and configure DenyHosts to scan logs and ban suspicious hosts;
    Install and configure PSAD intrusion detection application;
    Check for rootkits using RKHunter;
    Install and configure NMAP to scan open ports;
    Analyze system logs using LogWatch;
    Install and configure SELinux;
    Install and configure Tiger security audit and intrusion tool.
    
    -Commands Ran in order-
    sudo apt-get install gksu wget
    sudo apt-get update
    git clone https://github.com/brandonberntsen/CCDC.git
    cd CCDC/
    chmod +x ubuntu-server-secure.sh
    ./ubuntu-server-secure.sh
