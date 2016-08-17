qos_daemon
==========

This is a small small daemon which may be installed on a home router
(e.g OpenWRT) which will enable QoS for VoIP applications. It monitors
the bandwidth from the VoIP device. If it is high, it will
up-prioritize it. If it returns to normal, it will down-prioritize it.