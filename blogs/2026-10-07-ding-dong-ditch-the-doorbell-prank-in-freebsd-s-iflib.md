---
title: "Ding-Dong Ditch: The Doorbell Prank in FreeBSD's iflib"
url: "https://www.netgate.com/blog/ding-dong-ditch-the-doorbell-prank-in-freebsds-iflib"
date: "2026-10-07"
author: "Christian McDonald"
feed_url: "https://www.netgate.com/blog/rss.xml"
---
Since 2017, FreeBSD ® 's iflib(4) has been playing ding-dong ditch on network interfaces. When the transmit queue was nearly empty, iflib pressed the interface's doorbell three times for every packet, and two of those announced nothing new. The interface still had to answer each one, and answering is slow.
