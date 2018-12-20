![ipfs-header-image](https://user-images.githubusercontent.com/194400/50266662-5f8a3800-041c-11e9-9c67-99292d5366b5.jpg)

# Learn IPFS

Learn how to use IPFS
to store data on the ultimate decentralised/distributed file system!

In this _brief_ tutorial we will cover
_Why_ IPFS is _needed_,
_What_ it is, _Who_ should use it
and _How_ to get started! <br />



> **Note**: if you are already familiar with Internet History and IPFS,
feel free to skim/skip and go straight to the "How?"


# _Why?_

The [**Internet**](https://en.wikipedia.org/wiki/Internet)
was designed to be **_decentralised_ network**
that could survive and continue functioning in the event of a
natural or man-made disaster destroying _part_ of the network.

While the _Network_ is distributed and thus resilient to failure,
the vast majority of _content_ is still served by centralised servers.
The founders/creators of the Interned designed the Network and protocols
for routing requests across the network,
but they did _not_ create a means
of distributing and serving content from multiple nodes.

Over the last 20 years we have seen a "winner takes all"
accumulation of power and control on the Internet


## Concentration of Power, Filtering and Censorship

From the earliest days of the World Wide Web,
content hubs emerged as the default way people found information,
created content and communicated online.
Several of these hubs still exist in some form today
(_including AOL, Yahoo and MSN.com_)
however _many_ others are confined to history
(_e.g: GeoCities, Lycos, Tripod.com & BBS_).

After the
["Dotcom Crash of 2001"](https://en.wikipedia.org/wiki/Dot-com_bubble)
came
the resurgence of the web with "Web 2.0",
a new era of web-based _applications_.

More recently new platforms for creating and sharing content
have emerged in "Web 2.0"





### Wikipedia _Blocked_ in Turkey!



https://en.wikipedia.org/wiki/Block_of_Wikipedia_in_Turkey

# What?

This tutorial will take you through the basics of creating
content and publishing it on IPFS,
but first we need a bit of background knowledge/recap.


## What are Centralised, Decentralised and Distributed Networks ?

In a **centralised** network there is a central node that controls communication between all nodes.
A **decentralised** network is a series of interconnected hubs. If one hub goes down only the nodes connected to that hub will be affected, the rest of the network will still continue to function.
The internet is an example of a decentralised network. It is resilient against failure of several hubs.

![centralised-vs-decentralised-vs-distributed-original](https://user-images.githubusercontent.com/194400/50022918-9ce26600-ffd5-11e8-846a-38618d7ab483.png)

If the central node in a _centralised_ network goes offline, all communication is disrupted.
In a decentralised network, one "hub" can be offline and the rest of the network can still communicate.

![centralised-vs-decentralised-vs-distributed-node-down](https://user-images.githubusercontent.com/194400/50022916-9c49cf80-ffd5-11e8-9931-c59378ae1a11.png)

A ***distributed*** network is the most resilient type or ["topology"](https://en.wikipedia.org/wiki/Network_topology). In a distributed network any single node can completely fail and the remaining nodes will still be able to communicate.



<!--
_Most_ of the time using _centralised_
is not a "_problem_", Wikipedia

However our existing infrastructure
-->


# _Who?_

People on the bleeding edge who can deal with "changing spec",
"breaking changes" or "bugs".


# _How?_


For now, your best "_first lesson_" is [proto.school](https://proto.school)
If you get "stuck" going through the examples,
see: https://github.com/nelsonic/learn-ipfs/issues/5#issuecomment-445864393



<br /><br />
# _Open_/_Unanswered_ Questions




## Q: How do I `DELETE` something from IPFS?

My biggest question regarding placing files on a distributed file system
which I have no _control_ over is _how_ do I `DELETE` a file?

Read:
+ https://www.reddit.com/r/dtube/comments/8zt165/wait_so_illegal_content_can_be_uploaded_and_never/
+ https://news.ycombinator.com/item?id=16481112

### What about "Right to be Forgotten" _Law_?

When IPFS was _first_ doing the rounds on Hacker News
the _slogan_ was "The Permanent Web".

![ipfs-permanent-web](https://user-images.githubusercontent.com/194400/50273371-67ed6d80-0432-11e9-8e35-e0727a6307e2.png)

This has been _de-emphasized_ on the IPFS home page lately,
but is still viewable on early press:

https://motherboard.vice.com/en_us/article/78xgaq/the-interplanetary-file-system-wants-to-create-a-permanent-web

The question is: what if someone posts content onto IPFS
that they later want to ***`DELETE`*** ... ***how*** is that done?

And if it's not _possible_ to delete content _permanently_ (_and reliably_),
is that at odds with the _law_?
https://en.wikipedia.org/wiki/Right_to_be_forgotten


## Q: What _Guarantees_ Permanence/Storage of Files?

At present there is _zero_ guarantee
that files uploaded to the IPFS filesystem/network
will still be there in a few weeks/months time when you need them.
You are relying on the
["benevolence"](https://www.goodreads.com/quotes/68664-it-is-not-from-the-benevolence-of-the-butcher-the)
of the people running IPFS nodes on the network
to host our data.
Which as this forum thread notes is currently _not_ reliable:
https://discuss.ipfs.io/t/error-merkledag-not-found-lost-file/3279


### FileCoin?

The proposed solution to file storage guarantees
is a micro payment system called FileCoin. https://filecoin.io

![filecoin](https://user-images.githubusercontent.com/194400/50270104-6323bc00-0428-11e9-9889-d07b02e7f6f5.png)

At present Protocol Labs has not _started_ (_implementation_) work on FileCoin.
However the team has written plenty of "foundational" code for the protocols
that will be _used_ by File Coin so it's "coming" ...
but for now it's very much
[_Vaporware_](https://en.wikipedia.org/wiki/Vaporware).

If you want to _understand_ how FileCoin is _going_ to work
read the "white paper": https://filecoin.io/filecoin.pdf

> The analysis Filecoin doesn’t want you to read:
https://tokeneconomy.co/the-analysis-filecoin-doesnt-want-you-to-read-e60d5243f17c


Related questions:
+ How do I _know_ that something I have uploaded will not _disappear_?
+ Do I need to maintain an IPFS node for my content?

For _example_ "DTube" _uses_ IPFS
and _appears_ to be a _promising_ distributed alternative to YouTube,
but until the reliability of content storage is solved,
it won't gain "mainstream" adoption.

![dtube-content-disappears](https://user-images.githubusercontent.com/194400/50267204-57cb9300-041e-11e9-85ef-250fe1f1effe.png)


LBRY ("_library_") https://lbry.io is suggested in the comment ...

![libr.io-piracy](https://user-images.githubusercontent.com/194400/50266892-4fbf2380-041d-11e9-8447-74944c9a53b0.png)

Sadly, "LBRY" clearly state on their _home page_
that the software _can_ be used for sharing "Hollywood films" ...
so while it _might_ be a good (_Non-IPFS_) distributed file system,
they are basically _inviting_ a copyright infringement lawsuit!


# Notes, References & Further Reading

+ Internet Wikipedia article is great place to start your journey
of understanding the Internet. The article is comprehensive and well-maintained:
https://en.wikipedia.org/wiki/Internet ... the beauty of reading the
Wikipedia article is that whenever you don't understand a term, you can
click or search for it's definition on the web. If you're reading this
offline, you know _exactly_ why the distributed web is _necessary_!
+ Internet history:
https://en.wikipedia.org/wiki/History_of_the_Internet
+ History of the World Wide Web:
https://en.wikipedia.org/wiki/History_of_the_World_Wide_Web
+ Good Summary of IPFS, IPLD and FileCoin:
https://achainofblocks.com/2018/10/05/ipfs-interplanetary-file-system-simply-explained/
+ Introducing Cloudflare’s IPFS Gateway:
https://blog.cloudflare.com/distributed-web-gateway/
  + Discussion thread: https://news.ycombinator.com/item?id=18005488
+ A Beginner’s Guide to IPFS:
https://hackernoon.com/a-beginners-guide-to-ipfs-20673fedd3f
(_good overview, but not practical_)


# Videos

+ Stanford Seminar - IPFS and the Permanent Web
(Juan Benet co-founder of Protocol Labs):
https://youtu.be/HUVmypx9HGI
+ IPFS - Simply Explained (Savjee): https://youtu.be/5Uj6uR3fp-U
+ IPFS - A revolution in file storage and distribution (DataDash):
https://youtu.be/i5Obv_BTjv0 (_non-technical explanation_)
