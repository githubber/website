---
layout: default
title: DiSo Project
---
Silo free living.

[Social networks are becoming more open, more interconnected, and more
distributed][redmonk]. Many of us in the web creation world are embracing and promoting
web standards &mdash; both client-side and server-side. Microformats, standard
APIs, and open-source software are key building blocks of these technologies.
This model can be described as having three sides: Information, Identity, and
Interaction.

Diso (dee &bull; soh) is an initiative to facilitate the creation of open,
non-proprietary and interoperable building blocks for the decentralized social
web.

Our first target is [WordPress][], bootstrapping on existing work and building out
from there.

### So what does that mean? ###

We're building Wordpress plugins that implement or build on:

 - [microformats][] like [XFN][], [hCard][], [XOXO][] - wp-contactlist, wp-profiles
 - [OpenID][] - wp-contactlist, wp-openid-server
 - [OAuth][]
 - ...and others

[redmonk]: http://redmonk.net/archives/2007/12/05/diso/
[WordPress]: http://wordpress.org/
[microformats]: http://microformats.org/
[XFN]: http://microformats.org/wiki/XFN
[hCard]: http://microformats.org/wiki/hcard
[XOXO]: http://microformats.org/wiki/XOXO
[OpenID]: http://openid.net/
[OAuth]: http://oauth.net/

### Blogroll ###

 - [Chris Messina](http://factoryjoe.com/blog)
 - [Stephen Paul Weber](http://singpolyma.net/)
 - [Steve Ivy](http://www.monkinetic.com/)
 - [Will Norris](http://willnorris.com/)

### Diso - Distributed ###

 - [Diso Code](http://code.google.com/p/diso/)
 - [Diso on Github](http://github.com/diso/)
 - [Diso on Flickr](http://flickr.com/groups/diso/)
 - [Diso on Twitter](http://twitter.com/diso)
 - [Diso Wiki](http://wiki.diso-project.org/)

### Archives ###
<ul>
{% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

