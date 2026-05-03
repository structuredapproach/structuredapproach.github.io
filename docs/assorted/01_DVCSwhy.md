---
title: DVCS-Why?
summary: 
authors:
      - Natural Computer
date: 2026-05-01
---
# DVCS - Why is it worth knowing about?

##Background

A computing machine's essential strength is storing information and carrying-out automated instructions on behalf of humans. We appear to be seeing a progressive shift in the interface between human and machine (HMI), away from presenting information as files and folders, and towards indexing and retrieval-via-meaning. In other words the HMI is becoming more abstracted so the machine adapts to human language instead of the human needing to adapt to the machines's structure. For human consumers of a working system this shift clearly makes the HMI easier to use, but for humans interested in contributing to the workings it can make the system appear more complicated. In short, the abstraction away from files and folders masks an underlying reality : that the automation systems which perform the retrieval-via-meaning are still built using source code that's organised upon files and folders.

[Distributed version control systems](https://en.wikipedia.org/wiki/Distributed_version_control) (DVCS), such as [Git](https://git-scm.com/) [^1], have been a major enabling factor in the development of the abstracted systems supporting a more human centric interface. The essential strength of a DVCS is enabling parallel workflows through fast branching and merging with reliable history tracking but, at a more basic level, part of what makes a DVCS so powerful could be described as simply adding a timeline to files and folder systems.

##Relevance

There is an irony in the two paragraphs above : The shift away from files and folders suggests that some humans tend to have difficulty interfacing with them; but the powerful DVCS technology which at an old low level eases the task of intererfacing with files and folders has been used at a new higher level to hide the interface. Some humans might benefit more from being educated in the improvements at the old low level, rather than being blindly encouraged up onto the new higher level.

The next page attempts to provide a convenient route into such an education assuming no pre-existing knowledge. 

[^1]: other examples include [Mercurial](https://www.mercurial-scm.org/) and [Fossil](https://www.fossil-scm.org/home/doc/trunk/www/index.wiki) 
