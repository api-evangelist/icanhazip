---
title: "Getting podman quadlets talking to each other"
url: "https://major.io/p/quadlet-networking/"
date: "2025-09-25"
author: "major@mhtx.net (Major Hayden)"
feed_url: "https://major.io/feed/"
---
Quadlets are a handy way to manage containers using systemd unit files. Containers running via quadlets have access to the external network by default, but they don’t automatically communicate with each other like they do in a docker-compose setup. Adding networking only requires a few extra steps.
