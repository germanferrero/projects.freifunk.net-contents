---
name: Call A Friend
desc: Push an Android WebRTC app forward to call people without any servers. 
maskdown: freifunk-meshenger-ng.md
collaborating_projects:
  - freifunk
developers_involved: []
difficulty: high
size: full-time
status: open
email: moritzwarning@web.de
initiatives:
  - GSoC2022
issues:
mentors:
  - mwarning
requirements:
  - "Android programming"
  - "WebRTC"
tags:
  - GSoC
  - Android
  - WebRTC
  - Meshenger
---

During [GSOC 2018](https://blog.freifunk.net/2018/08/14/meshenger-p2p-local-network-messenger-final-update/) we developed an App called [Meshenger](https://github.com/meshenger-app/). It can be used to (video/audio) call people over mesh networks, e.g. [Freifunk](https://freifunk.net/), [Libremesh](https://libremesh.org/), typical LANs or overlay networks.

This App was quite a success and is available on [F-Droid](https://f-droid.org/en/packages/d.d.meshenger/).

WebRTC without servers is an underutilized feature in WebRTC. Most call and messenger Apps want to bind people to servers and the Internet for profit and convenience. Meshenger is an important effort to help to take communication off leash of server and the Internet.

Since back then a few features (cryptography, call list, block list, lots of bugfixes) were added. But there was never a release, since calling is broken/fragile in the development branch. The reason is unknown.
Meshenger is for the most part the [WebRTC Android example](https://chromium.googlesource.com/external/webrtc/+/refs/heads/main/examples/androidapp/) with added features. This should give a solid guidline.

The task for this project would be to fix the the current state (possibly up or downgrading WebRTC) to get a new release out of the door. A highly motivated person might event want to switch the project to Kotlin. The mentor(s) will support with understanding the code and inner working of the App throughout the project.

This is an effort to create something that can be used across the globe for many small communities.

Many aspects of this project are up for the discussion. If you are interested, but unsure, then feel free to contact the mentor(s) beforehand. It is welcome and shows initiative (moritzwarning@web.de). :-)

#### Milestones

##### GSoC Peraration/Bonding

* Let's talk about the current state of project.
* Talking about the outline of the project.
* Maybe visit the Battlemesh (depends on covid and date&location).

##### GSOC Start

* Plan steps to create a release.
* Decide on features to add or remove.
* Get to know the code with sessions with mentor(s)

##### GSOC Midterm

* Testing and fixing.

##### GSOC Final

* Make a release and add reap the Karma