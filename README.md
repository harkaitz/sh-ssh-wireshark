SSH and Wireshark
=================

Capture packets in servers using ssh/tcpdump and local wireshark.

## Help

ssh-h-wireshark

    Usage: ssh-h-wireshark [-f FILTER] USER@HOST INTF
    
    Connect to a remote Linux/OpenBSD machine "USER@HOST" and execute the
    "tcpdump" command in "INTF" interface.
    
    The SSH packets are discarded. Of course the user USER needs capturing
    permissions.
    
    You can specify filtering options (-f) to wireshark with "-f".
    
    Example: $ ssh-h-wireshark -f 'ip.src != 192.168.1.0/24' root@m1 bse0

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
