---
layout:     post
title:      Implementation of P2P file sharing system
subtitle:   A BitTorrent-like P2P sharing software
date:       2019-10-27
author:     Jue Yuan
header-img: "img/post-bg-2018.jpg"
tags:
    - P2P
    - File Sharing
    - BitTorrent
---
[ProjectPage](https://github.com/shumoyuan/P2PFile)

Remodeled a P2P file sharing software like BitTorrent to enable users to share files using Java language.

Enabled peers to send a handshake message before transmission.

Improved file sharing efficiency by coding communication protocol, file splitting and combining rules.

Transformed 1GB file among 6 users in 10 seconds, tested by Apache JMeter.

main class: peerProcess
