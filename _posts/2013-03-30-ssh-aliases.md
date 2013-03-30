---
layout: post
category : lessons
tagline: ""
tags : [ssh, config]
---
{% include JB/setup %}

Creating aliases in ```~/.ssh/config``` will allow you to set the default username for a host.  i.e.

    Host example
    HostName example.net
    User buck

And then instead of doing ```ssh buck@example.net``` you can just do ```ssh example```.  Can also be used with ```scp``` etc.
