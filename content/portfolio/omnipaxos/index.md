---
title: OmniPaxos
description: This is the description of our sample project
date: "2021-09-02T19:47:09+02:00"
jobDate: 2021
work: [consensus, rust]
techs: [rust]
designs: []
thumbnail: omnipaxos/sample.png
projectUrl: https://github.com/haraldng/omnipaxos
#testimonial:
  #name: John Doe
  #role: CEO @Example
  #image: sample-project/john.jpg
  #text: Prow scuttle parrel provost Sail ho shrouds spirits boom mizzenmast yardarm. Pinnace holystone mizzenmast quarter crow's nest nipperkin
---

OmniPaxos is a Rust library that implements our Omni-Paxos protocol which allows for building abstractions such as a distributed log or replicated state machine. Contrary to other protcols such as Raft or Zab, Omni-Paxos is resilient to partial network partitions and allows for efficient parallel reconfiguration through its decoupled design.

An OmniPaxos replica is implemented as a Rust ```struct```. This should allow for convenient usage with any desired network implementation or on top of an actor framework such as [Kompact](https://github.com/kompics/kompact).
