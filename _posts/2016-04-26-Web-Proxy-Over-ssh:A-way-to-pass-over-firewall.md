---
layout: post
title:  "Web Proxy Over ssh : A way to pass over firewall"
description: Single Page Application, Injection Dependency, RESTful, User Experience, MVC and more...
tags: ssh, proxy, tunneling 
categories: Linux 
---

Sometimes we need connect to a web server hosted at cloud and we cannot open ports.
We need only open a shell and write the follow code.
After connection, open your browser and set the proxy SOCK host: 127.0.0.1 and port 8080 (or some other equal <port> at the command above)
<script src="https://gist.github.com/viniciustrindade/866bfd43147017a776888813ec0841b3.js"></script>
