:BEP: No Number Attributed
:Title: TLS Protocol Encryption
:Version: $Revision$
:Last-Modified: $Date$
:Author:  Raphael Roumezin <raphael.roumezin @at@ ik.me>
:Status:  Draft
:Type:    Standards Track
:Content-Type: text/x-rst
:Created: 09-Jan-2024
:Post-History: 


Abstract
========

Using TLS for exchanges between peers.

Rationale
=========

The usage of TLS for the bittorrent protocol allows users to use
private torrents and trackers while ensuring safety of exchanged data and
confidentiality.

The TLS security protocol is already being used for many protocols like HTTPS,
and contributes to user and server safety by securing the connections and
preventing attacks such as MITM (Man In The Middle) which can let an external
actor read the connection between two peers and tamper with it.


References
==========



Copyright
=========

This document has been placed in the public domain.



..
  Local Variables:
  mode: indented-text
  indent-tabs-mode: nil
  sentence-end-double-space: t
  fill-column: 70
  coding: utf-8
  End:
