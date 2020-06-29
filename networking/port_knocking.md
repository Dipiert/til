# Port knocking 

It's a method of externally opening ports on a firewall by generating a connection attempt on a set of prespecified closed ports. Once a correct sequence of connection attempts is received, the firewall rules are dynamically modifed to allow the host which sent the connection attempts to connect over specific port(s). A variante called single packet authorization (SPA) exists, where only a single "knock" is neede, consisting of an ecrpyted packet.

The complexity of the knock can be anything from a simple ordered list (e.g. TCP port 1000, TCP port 2000, UDP port 3000) to a complex time-dependen, source-IP-based and other-factor-based encrypted hash.

