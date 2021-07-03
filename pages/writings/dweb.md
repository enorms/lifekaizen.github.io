---
layout: default
permalink: /writings/dweb
id: writings
---

# Why I think the distributed web is a thing

InterPlanetary File System (IPFS) does a great job of laying out the benefits on their home page and has solved two difficult technical challenges:
Use content-based addressing which makes it easy to scale copies and save (and distinguish) versions. 0
Infra to connect peers which combines: finding and ranking peers, dealing with various routing headaches. 1

Separately, a better distributed data structure came out of computer science resarch into the world; that's CRDT, implementation example: yjs.

Distributed versions of many things will need to be built. Example: replacing Dropbox. 2
It feels a bit like the stories of Bezos at the mathemeticians fund, when they saw the internet was coming and brainstormed what was possible and Amazon was essentially one of those ideas. 3

## How different is it really (say from using a modern CDN)?

Well it's a paradigm shift so in addition to the technical architecture being completely different, there is a philosophical shift about privacy and control and against extreme centralized power; IPFS founder does a good job laying out the emotional case for this 4

Other than that, for end users it should be similar. But for devs and app developers, the simple ability to create private networks and databases, and expand them publicy. Potentially lower costs, better uptime. 5 Simpler is coming anyway with Jamstack and databases that handle for of the maintenance. 8

It seems early. When I searched "IPFS" today to show a friend, the result was way down after some medical terms and local maps - despite searching and clicking on IPFS frequently. 9 Some obvious things have not been completed yet, and many .com domain names have availability. 10 There is some initial infrastructure support. 11 12

I'm working on a content-addressed, distributed oject database with dynamic access control 13 If you're intersted in this or any other "for service in web: service.dweb", reach out and let me know your thoughts!

###### Footnotes:

0 <https://www.wired.com/2016/06/inventors-internet-trying-build-truly-permanent-web/>

1 that's libp2p, which is maturing, as Ethereum is using it, but early as can be seen by the status of <https://libp2p.io/implementations/>

2 <https://medium.com/pinata/why-you-should-stop-sharing-your-creative-work-through-dropbox-7ec38be7da75>

3 paraphrasing, condensing, but vaguely based on <https://www.goodreads.com/book/show/17660462-the-everything-store>

4 Why IPFS [Matters], Founder, 2019 <https://www.youtube.com/watch?v=zE_WSLbqqvo&t=29s>

5 IPFS estimates 60% for video <http://sites.science.oregonstate.edu/~kovchegy/web/papers/p2p-vdn.pdf> via <https://ipfs.io/>

8 'something that makes it possible to author a complex web application and git push deploy it to a scalable “delivery/compute/storage” layer, with minimal lock-in and awesome performance' <https://tom.preston-werner.com/2020/03/04/joining-the-netlify-board.html>

9 DuckDuckGo gives it position 5, or 3 excluding ads. Google seems to have learned my patterns and now gives position 1.

10 "[Access Control List] can never change, which means you can't add/revoke other write permissions" <https://github.com/orbitdb/field-manual/blob/3ddce1c1bf2357f66494060c7397b5495b6c1601/01_Tutorial/06_Identity_Permission.md>; at the time of writing, anyway

11 "Cloudflare’s easy way to access content from IPFS" posted in 2018 with enough experience to think about "Dealing with abuse" <https://blog.cloudflare.com/distributed-web-gateway/>

12 Brave, which I started using as my iOS browser due to better add blocking, added support for "IPFS URI" in Jan 2021, recent <https://brave.com/ipfs-support/>, initial <https://brave.com/brave-integrates-ipfs/>

13 <https://github.com/collabswarm/collabswarm>; name will likely change so if link is broken please let me know!

###### Other References:

- <https://ens.domains/>
- <https://github.com/dappkit/aviondb>
- <https://github.com/amark/gun>
- <https://thegraph.com/>


###### Thanks
To Robert Chu for reading drafts.

_Formatting Note:_ in trying to encourage myself to write more I'm trying to reduce friction so using super basic footnotes and links, hopefully everyone can figure out the meaning and the numbering doesn't misalign, if not let me know.


