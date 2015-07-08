---
layout: page
---

<div style="width: 100%; display: inline-block;">
<img src="{{ site.baseurl }}/public/ryan-stutsman.jpg" alt="Headshot" width="25%" style="float: left;"/>
<div style="float: left; padding-left: 20px;">
<span style="font-size: 150%;">Ryan Stutsman</span><br>
Assistant Professor<br>
University of Utah<br>
<a href="mailto:stutsman@cs.utah.edu">stutsman@cs.utah.edu</a>
</div>
</div>

<p></p>

[Projects](#projects) -
[Publications](#publications) -
[Talks](#talks) -
[Activities](#activities) -
[Blog](./blog/)

*I am looking for Ph.D. students in the data center, cloud, and large-scale
storage area. If you are an admitted or current University of Utah CS student
feel free to contact me. Otherwise, apply to the [Utah SoC PhD
program](http://www.cs.utah.edu).*

I am an Assistant Professor at the [School of Computing](http://www.cs.utah.edu/)
at the [University of Utah](http://www.utah.edu/).
My interests include Distributed Systems,
Operating Systems, and Databases.  I'm passionate about designing and building
systems that allow large-scale applications to access data more intensively
than has been possible in the past.  My dissertation work,
[Fast Crash Recovery in RAMCloud]
(http://www.stanford.edu/~ouster/cgi-bin/papers/ramcloud-recovery.pdf)
provides durability and availability in a large-scale distributed DRAM-based
storage system with the same price and energy consumption as today's volatile
caches.  Overall, it enables the use of DRAM as fault-tolerant large-scale data
center storage which is 50 to 5000 times faster than other data center storage
systems.

Formerly, I was a Postdoctoral Researcher in the
[databases group](http://research.microsoft.com/en-us/groups/db/) at
[Microsoft Research](http://research.microsoft.com/).
Before that, I earned my Ph.D. at Stanford University working as a part of the
[RAMCloud](https://ramcloud.stanford.edu/) and the
[Secure Computer Systems](http://www.scs.stanford.edu/) lab</a>.
 

# <a name="projects"></a> Projects

## Current

 - [Deuteronomy](http://research.microsoft.com/en-us/groups/db/) - A fully lock-free
   transactional database engine that is performance competitive with modern
   in-memory databases. Deuteronomy maintains clean architectural separation of
   storage, indexing, and transaction components for flexible 
   deployment in embedded, cloud, or data center systems.
 - [RAMCloud](http://ramcloud.stanford.edu/) - A high-performance distributed
   key-value storage system designed with latency goals to enable the next
   generation of data center applications.

## Past

 - [Cinder](http://www.scs.stanford.edu/cinder) - An operating system designed
   for cellular phones and mobile devices with fine-grained energy accounting,
    allocation, subdivision, and delegation.
 - [HiStar](http://www.scs.stanford.edu/histar) - An operating system designed
   around decentralized information flow control.
 - [ROSE](http://www.rosecompiler.org/) - A source-to-source compiler
   infrastructure for transformation and analysis tools for large-scale
   applications.
 - [AutoTest](http://autotest.github.com/) - A release-driven Linux kernel
   regression testing framework.
 - [Lost in Translation](./stego/) - A steganographic system that hides information in
   natural language translations.

# <a name="publications"></a> Publications

## Refereed conference and journal publications

 1. Darko Makreshanski, Justin Levandoski, Ryan Stutsman.
    To Lock, Swap, or Elide: On the Interplay of Hardware Transactional Memory and Lock-Free Indexing.
    To appear VLDB 2015.
 1. Ryan Stutsman, Collin Lee, and John Ousterhout.
    [Experience with Rules-Based Programming for Distributed, Concurrent, Fault-Tolerant Code.]
    (https://www.usenix.org/system/files/conference/atc15/atc15-paper-stutsman.pdf)
    In *Proceedings of the 2015 USENIX Conference on Annual Technical Conference*,
    USENIX ATC'15, pages 17-30, Santa Clara, CA, USA, 2015. USENIX Association.
 1. Justin Levandoski, David Lomet, Sudipta Sengupta, Ryan Stutsman, Rui Wang.
    [High Performance Transactions in Deuteronomy.]
    (http://www.cidrdb.org/cidr2015/Papers/CIDR15_Paper15.pdf)
    *Conference on Innovative Data Systems Research*, CIDR 2015.
 1. Asaf Cidon, Stephen M. Rumble, Ryan Stutsman, Sachin Katti, John
    Ousterhout, and Mendel Rosenblum.
    [Copysets: Reducing the Frequency of Data Loss in Cloud Storage.]
    (http://www.stanford.edu/~cidon/materials/CR.pdf)
    In *Proceedings of the 2013 USENIX Conference on Annual Technical Conference*,
    USENIX ATC'13, pages 37­48, Berkeley, CA, USA, 2013. USENIX Association.
    (**Best Student Paper Award**)
 1. Diego Ongaro, Stephen M. Rumble, Ryan Stutsman, John Ousterhout, and Mendel Rosenblum.
    [Fast Crash Recovery in RAMCloud.]
    (http://www.stanford.edu/~ouster/cgi-bin/papers/ramcloud-recovery.pdf)
    In *Proceedings of the Twenty-Third ACM Symposium on Operating Systems Principles*,
    SOSP '11, pages 29-41, New York, NY, USA, 2011. ACM.
 1. John Ousterhout, Parag Agrawal, David Erickson, Christos Kozyrakis, Jacob Leverich,
    David Mazi&egrave;res, Subhasish Mitra, Aravind Narayanan, Diego Ongaro, Guru Parulkar,
    Mendel Rosenblum, Stephen M. Rumble, Eric Stratmann, and Ryan Stutsman.
    [The Case for RAMCloud.]
    ("http://cacm.acm.org/magazines/2011/7/109885-the-case-for-ramcloud/fulltext)
    *Communications of the ACM*,
    54(7):121-130, July 2011.
 1. Arjun Roy, Stephen M. Rumble, Ryan Stutsman, Philip Levis, David Mazi&egrave;res,
    and Nickolai Zeldovich.
    [Energy Management in Mobile Devices with the Cinder Operating System.]
    (http://www.scs.stanford.edu/~rumble/papers/eurosys2011-roy.pdf)
    In *Proceedings of the Sixth conference on Computer Systems*,
     EuroSys '11, pages 139-152, New York, NY, USA, 2011. ACM.
 1. Ryan Stutsman, Mikhail Atallah, Christian Grothoff, and Krista Grothoff.
    [Lost in Just the Translation.]
    (papers/lijtt.pdf)
    In *Proceedings of the 2006 ACM Symposium on Applied Computing*,
    pages 338-345. ACM, April 2006.

## Refereed workshop publications
 1. Ryan Stutsman and John Ousterhout.
    [Toward Common Patterns for Distributed, Concurrent, Fault-Tolerant Code.]
    (papers/stutsman-dcft-hotos13.pdf)
    In *Proceedings of the 13th USENIX Conference on Hot Topics in Operating Systems*,
    HotOS'13, Berkeley, CA, USA, 2013. USENIX Association.
 1. Stephen M. Rumble, Diego Ongaro, Ryan Stutsman, Mendel Rosenblum, and John K. Ousterhout.
    [It's Time for Low Latency.]
    (http://www.scs.stanford.edu/~rumble/papers/latency_hotos11.pdf)
    In *Proceedings of the 13th USENIX Conference on Hot Topics in Operating Systems*,
    HotOS '11, pages 11-15, Berkeley, CA, USA, 2011. USENIX Association.
 1. Stephen M. Rumble, Ryan Stutsman, Philip Levis, David Mazi&egrave;res, and Nickolai Zeldovich.
    [Apprehending Joule Thieves with Cinder.]
    (papers/mobiheld04-rumble.pdf)
    In *MobiHeld '09: Proceedings of the 1st ACM workshop on Networking,
    systems, and applications for mobile handhelds*, pages 49-54, 2009.
 1.  Jad Naous, Ryan Stutsman, David Mazi&egrave;res, Nick McKeown, and Nickolai Zeldovich.
     [Delegating Network Security with More Information.]
     (papers/wren27-naous.pdf)
     In *Proceedings of the 1st ACM Workshop on Research on Enterprise Networking*,
     WREN '09, pages 19-26, 2009.
 1.  Christian Grothoff, Krista Grothoff, Ludmila Alkhutova, Ryan Stutsman, and Mikhail Atallah.
     [Translation-Based Steganography]
     (papers/lit.pdf)
     In *Proceedings of Information Hiding Workshop*,
     IH 2005, pages 213-233. Springer-Verlag, 2005.

## Unrefereed publications and technical reports
{% comment %}
Note to self: The missing one is the RAMCloud TR. But it is irrelevant given SIGOPS version.
{% endcomment %}
 1.  Arjun Roy, Stephen M. Rumble, Ryan Stutsman, Philip Levis, David Mazi&egrave;res,
     and Nickolai Zeldovich.
     [Energy Management in Mobile Devices with the Cinder Operating System.]
     (http://hci.stanford.edu/cstr/reports/2010-02.pdf)
     Technical Report CSTR-2010-02, Stanford University, June 2010.
 1. Stephen M. Rumble, Ryan Stutsman, Philip Levis, David Mazi&egrave;res, and Nickolai Zeldovich.
    [Apprehending Joule Thieves with Cinder.]
    ("papers/rumble-cinder-ccr.pdf")
    *SIGCOMM Computer Communication Review*, 40(1):106-111, 2010.
 1. John Ousterhout, Parag Agrawal, David Erickson, Christos Kozyrakis, Jacob Leverich,
    David Mazi&egrave;res, Subhasish Mitra, Aravind Narayanan, Guru Parulkar, Mendel Rosenblum,
    Stephen M. Rumble, Eric Stratmann, and Ryan Stutsman.
    [The Case for RAMClouds: Scalable High-Performance Storage Entirely in DRAM.]
    (http://doi.acm.org/10.1145/1713254.1713276)
    *SIGOPS Operating Systems Review*, 43(4):92-105, December 2009.
 1. Christian Grothoff, Krista Grothoff, Ryan Stutsman, Ludmila Alkhutova, and Mikhail J. Atallah.
    [Translation-based Steganography.]
    ("http://iospress.metapress.com/content/j97333w402k26404/")
    *Journal of Computer Security*, 17(3):269-303, 2009.
 1.  Christian Grothoff, Krista Grothoff, Ludmila Alkhutova, Ryan Stutsman, and Mikhail Atallah.
     [Translation-Based Steganography.]
     (https://www.cerias.purdue.edu/assets/pdf/bibtex_archive/2005-39.pdf)
      Technical Report CSD TR 05-009, Purdue University, 2005.

## Dissertation

[Durability and Crash Recovery in Distributed In-Memory Storage Systems.]
(./papers/thesis.pdf)
PhD thesis, Stanford University, Stanford, CA, USA, December 2013.

# <a name="talks"></a> Talks

 1. [Experience with Rules-Based Programming for Distributed, Concurrent, Fault-Tolerant Code.]
    (https://www.usenix.org/system/files/conference/atc15/atc15-paper-stutsman.pdf)
    USENIX ATC'15.
 1. [High Performance Transactions in Deuteronomy.]
    (http://www.cidrdb.org/cidr2015/Papers/CIDR15_Paper15.pdf)
    CIDR 2015.
 1. [Toward Common Patterns for Distributed, Concurrent, Fault-Tolerant Code.]
    (papers/stutsman-dcft-hotos13.pdf)
    HotOS'13.
 1. [Fast Crash Recovery in RAMCloud.]
    (http://www.stanford.edu/~ouster/cgi-bin/papers/ramcloud-recovery.pdf)
    SOSP '11.
 1. [Energy Management in Mobile Devices with the Cinder Operating System.]
    (http://www.scs.stanford.edu/~rumble/papers/eurosys2011-roy.pdf)
    EuroSys '11.
 1. [Lost in Just the Translation.]
    (papers/lijtt.pdf)
    ACM SAC '06.

# <a name="activities"></a> Activities

 - IMDM 2014, 2015 PC member
 - SIGMETRICS 2015 PC member
 - ICDE 2016 PC member
