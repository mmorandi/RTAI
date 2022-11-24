---
---

# RTAI and the RT-Linux patent


The following statement by Eben Moglen, General Counsel of the [Free Software Foundation](http://www.fsf.org/) clearifies the legal situation of RTAI users with regard to the infamous [RT-Linux Patent](http://www.delphion.com/details?pn=US05995745__).
```
Date:    Sat, 20 Oct 2001 11:27:14 -0400 (EDT)
From:    Eben Moglen 
To:      robert@schwebel.de
Subject: Re: Won't help with what?
Thanks for your note.  As I have said, we have by no means ignored these
issues.  We believe on the basis of our own careful review of facts and law,
and after appropriate consultation, that there is no cause for concern on
either ground.
The new patent license allows the teaching of the patent to be practiced
without any additional obligations in any program released under GPL.  If RTAI
is released under GPL, as it can and should be, it is fully protected against
any infringement claim by the license we negotiated.  Any modified RTLinux
system must be GPL'd, because RTLinux is GPL, and thus any RTL system that is
distributed in a GPL-compliant manner is also covered by the new license.  End
of that aspect of the problem.
The applications problem also does not exist. Patents, because they grant very
long-term and "strong" monopolies, are very precise documents.  A patent's
"scope," or the extent of its power to exclude others from its teachings, is
rigidly limited by its "claims," which are one portion of the document that is
negotiated between the inventor and the issuing Patent Office.  Anything which
is not part of the patent's claims is not covered by the patent, and can be
done by anyone anywhere anytime, without regard to the patent.
Victor Yodaiken's patent has eleven claims.  Each of those claims covers
behavior of (1) a real-time OS kernel, (2) a general purpose OS kernel being
run as the idle-task of the RT OS, and (3) a software emulator of hardware
interrupt control, which allows the RT OS to prioritize and present interrupts
to the general purpose OS only when the RT OS has met real-time interrupt
requirements.  These eleven claims, like all claims in all patents, are written
as broadly as possible, so as to bring as much behavior as possible within the
scope of the patent.  But none of the teachings of the patent, as specified in
its claims, is practiced by any applications program running under any OS
kernel.  No application in a running RTLinux or RTAI system does any of the
things the patent claims. No applications program is therefore potentially
infringing, and no applications program is covered, or needs to be covered, by
the license. If an applications program running in a GNU/Linux system as
modified by RTLinux or RTAI is constructed so that it does not violate
GPL--which is not the same thing as being licensed under GPL or being free
software at all--its distribution terms are utterly irrelevant.
I reviewed this issue carefully, as part of my own legal work negotiating the
settlement, and I have taken additional advice from patent counsel on this and
other aspects of the situation.  We would not have completed our arrangements
if we had not been fully satisfied on this point. But reality and perception
differ.  Perhaps Victor has attempted to create the perception that he has more
power over others' arrangements than he has.  This would not be the first time
in the history of business, politics, war or even marriage that such behavior
occurred. We are seeking one or two clarifications in statements appearing on
FSM Labs' website, which we think might inadvertently contribute to
misunderstanding on these points.  FSF may also choose in future to make some
official statement on these matters.  This message summarizes our view of the
legal situation, and you may redistribute it, verbatim, freely.
Best regards.
--
 Eben Moglen                       voice: 212-854-8382
 Professor of Law                    fax: 212-854-7946       moglen@
 Columbia Law School, 435 West 116th Street, NYC 10027     columbia.edu
 General Counsel, Free Software Foundation
```
