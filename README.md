# ddd-talks
Talks about Domain-Driven Design

## Alberto Brandolini
- [DDD Europe | Event Storming](https://www.youtube.com/watch?v=mLXQIYEwK24) (2019)
  - quickfire overview of Brandolini's Event Storming techniques, summarized in the end as "Merge the people, Split the software" (which, he notes, is the opposite of the way things have often historically been done with silos of humans and shared databases)
  - the value of Domain Events in modelling is explained 
  - another amusing point is that like that true pizza, you can freely add extra "toppings" on top of the basic Event Storming recipe... with the exception of database tables and pineapple!

## Eric Evans
- [SE-Radio - Episode 8: Interview Eric Evans](https://www.se-radio.net/2006/03/episode-8-interview-eric-evans/) (2006) (podcast)
- [DDD: putting the model to work](https://www.infoq.com/presentations/model-to-work-evans/) (2007)
- [DDD: Strategic Design](https://www.infoq.com/presentations/strategic-design-evans/) (2007)
- [Eric Evans on Domain-Driven Design](https://www.iheart.com/podcast/256-net-rocks-31158901/episode/eric-evans-on-domain-driven-design-38577478/) (2007) (podcast)
  - including discussion of working with legacy systems via anticorruption layers
- [What I've learned about DDD since the book](https://www.youtube.com/watch?v=lE6Hxz4yomA&t) (2009)
  - including discussion of Domain Events as a new Building Block, and Big Ball of Mud within Strategic Design
  - [Introduction](https://www.youtube.com/watch?v=YAcu9yKf51U)
- [On DDD and Agile at DDD-NYC SIG](https://www.youtube.com/watch?v=f00jUC64osw) (2010)
  - Recording of a [similar talk given at qcon 2010](https://qconlondon.com/london-2010/qconlondon.com/london-2010/presentation/Folding+Design+into+an+Agile+Process.html)
  - introduces the [Whirlpool process](https://domainlanguage.com/ddd/whirlpool/)
- [Domain Driven Design Strategies for Dealing With Legacy Systems (YOW! 2011)](https://www.youtube.com/watch?v=OTF2Y6TLTG0) (2011)
  - First half is an intro to DDD, and the second part introduces material covered in [this white paper](https://domainlanguage.com/ddd/surrounded-by-legacy-software/) 
- [What's the Best Way to Improve Software Architectures?](https://www.infoq.com/presentations/panel-improve-software-architecture/?itm_source=infoq&itm_campaign=user_page&itm_medium=link) (2014)  
  - A Michael Feathers hosted panel discussion, with Eric Evans, Duncan DeVore, and Leo Gorodinski
- [SE-Radio - Episode 226: Eric Evans on Domain-Driven Design at 10 Years](https://www.se-radio.net/2015/05/se-radio-episode-226-eric-evans-on-domain-driven-design-at-10-years/) (2015) (podcast) 
  - Interview covering the core of DDD (Bounded Contexts, Strategic Design), Bounded Contexts relationship with microservices, developments in DDD such as Domain Events, CQRS and Event Sourcing, the Actor model as it relates to Aggregates, and what NoSQL means for DDD
- [DDD and Microservices: At Last, Some Boundaries!](https://www.infoq.com/presentations/ddd-microservices-2016/) (2016)
  - a key point is in the title; while microservices have overhead, they are a way of establishing hard boundaries between new DDD models and monolithic ones. Simple logical boundaries (e.g. within monoliths) have a track record of failing to be robust over time, leading to the Big Ball of Mud  
- [Explore DDD | Keynote: Tackling Complexity in the Heart of Software](https://www.youtube.com/watch?v=kIKwPNKXaLU) (2017)  
  - Latter part covers advances since 2003, giving an overview of where DDD was at in 2017
- [Explore DDD | Exploring Time](https://www.youtube.com/watch?v=Zm95cYAtAa8) (2017)
  - A talk about exploring models of the generic sub-domain of "Time"
- [Explore DDD | DDD Isn't Done: A Skeptical, Optimistic, Pragmatic Look](https://www.youtube.com/watch?v=R2IAgnpkBck&t=1493s) (2018)
  - A call to arms for a(nother) shake-up of DDD concepts
- [DDD Europe | What is DDD?](https://www.youtube.com/watch?v=pMuiVlnGqjk&t=318s) (2019)
  - Introductory talk, focusing on models and language. An interesting point made was that the reason Evan's focuses on language is that the actual, specific words used when talking about the domain can be valuable leads towards defining a useful model (words that can easily be overlooked due to their natural appearance during the context of the conversation). 
- [Explore DDD | Keynote: Language in Context: And How Do We Go Forward From Here?](https://www.youtube.com/watch?v=kjMZVYdwucs) (2019)
  - A talk that challenges the existing descriptions of Bounded Contexts and encourages the DDD community to shake this area up

## Martin Kleppmann

- [DDD Europe | Event Sourcing and Stream Processing at Scale](https://www.youtube.com/watch?v=avi-TZI9t2I&t) (2016)
  - on similar techniques that emerged out of the DDD and Stream processing communities, relating to "events" and their processing, but with different drivers

## Greg Young
- [CQRS and Event Sourcing - Code on the Beach 2014](https://www.youtube.com/watch?v=JHGkaShoyNs) (2014)
  - First 2/3rds on Event Sourcing, last 1/3rd on CQRS 
- [A Decade of DDD, CQRS, Event Sourcing](https://www.youtube.com/watch?v=LDW0QWie21s) (2016)
  - Covers the Good, the Bad, and the Future; interesting points for me were his mentioning the utility of the actor model in managing processes, and in looking to the future, "N-Temporal" use cases for Event Sourcing, e.g. enabling a representation of what was known "as-of" a point in time, as well as what was known "as-at" a point in time.
