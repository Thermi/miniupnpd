miniupnpd split
==============

What?
====

miniupnpd split is a project to split
the functionality of the upnp parser
and the firewall agent,

Why?
====

Currently, miniupnpd only works in networks
in which WAN and LAN have different are reachable
over different interfaces and where the firewall
seperating WAN and LAN runs on a host in the LAN.
In scenarios, where at least one of this 
requirements is not the case will miniupnpd 
not be able to work correctly.

How?
=====

By spliting the functionality of the upnp
parser and the firewall agent into different
programs is it possible to run them on different
hosts and connecting them over a tcp connection.

This makes it possible to use miniupnpd in any
environment with a functional network.

How can I contribute?
=====================

If you wish to contribute, please fork the project
and make pull requests!
