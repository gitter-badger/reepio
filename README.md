reep.io
=======

[![Join the chat at https://gitter.im/TimDurward/reepio](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/TimDurward/reepio?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
A browser based peer-to-peer file transfer platform. See it live here: https://reep.io

What is reep.io?
---
reep.io uses modern WebRTC technology to enable peer-to-peer file transfers between two browser.

Peer-to-Peer file transfers
---
With reep.io (reep = peer spelled backwards, duh) you can transfer files directly to another browser. You can transfer anything you want without storing the data on a server first. You can even stream video files or preview images directly. 

Privacy
---
reep.io's only purpose is to make it easy for you to connect to your buddy by providing you with a link that automatically connects you both. After the initial handshake we are out. The file transfer now only happens between you two without up- and downloading the file to a server.

Security
---
The whole communication is encrypted using Datagram Transport Layer Security (DTLS) using SSL. This reduces the risk of man in the middle attacks.

Used libraries
---
* https://github.com/peers/peerjs/ The webrtc js library used. This made reep.io even possible.
* https://github.com/layerssss/paste.js/
* https://getbootstrap.com/
* http://jquery.com/
* https://angularjs.org/
* https://github.com/luisfarzati/angulartics
* https://github.com/mrdoob/three.js/
* http://www.heise.de/extras/socialshareprivacy/

License
---
reep.io uses the [GPL v2](http://www.gnu.org/licenses/gpl-2.0.html) license
