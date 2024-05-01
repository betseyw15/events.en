---
title: Ask the experts - Useful extensions in Tags (Launch) to help super charge the Web SDK
description: Are you thinking about migrating your implementation to the new Adobe Web SDK?  We will run through some of our favorite extensions in the Adobe Tags library that will help as you take your data collection to the next level.
solution: Data Collection, Experience Platform
feature: Tags
kt: 10528
event-start-time: 2022-08-23 09:00-7
event-guests: Rudi Shumpert,Jeff Chasin,Eric Matisoff
exl-id: 5ef987f4-37f5-473f-b9f2-1598b7e655ba
duration: 3833
---
# Ask the experts: Useful extensions in Tags (Launch) to help super charge the Web SDK

Are you thinking about migrating your implementation to the new Adobe Web SDK?  We will run through some of our favorite extensions in the Adobe Tags library that will help as you take your data collection to the next level.

>[!VIDEO](https://video.tv.adobe.com/v/346610/?quality=12&learn=on)

## Questions and comments from the show

### Data Element Assistant extension from Evolytics

<br>&nbsp;
**Question:** From a data security point of view, is Evolytics secure to use, as this is third party extension?

**Answer:** Yes. You can review the extension code if you like, also it does not save any of the date, it merely does a transformation.

<br>&nbsp;

**Question:** Does this capture Adobe ECID as well?

**Answer:** The Adobe ECID is not captured within that extension. This extension is meant for creating additional, anonymous identifiers (amongst other things).

**Answer:** The Adobe ECID can be captured in other ways though. We'll share out that via the ExL notes and Twitter since we cannot share links in the chat here.

<br>&nbsp;

**Question:** The hash functionality does it offer various hashing techniques like SHA-256 and provides public and private keys?

**Answer:** Yep! SHA-256 is the default

<br>&nbsp;

### General questions and comments:

<br>&nbsp;

**Question:** What do we click to download the source files for extensions? Is that in the "3-dot menu"?

**Answer:** Yes! The 3 dots, then Download Source (from the catalog view)

<br>&nbsp;

**Comment:** One of the things I really dig with extensions is the time-saving aspect of them. A lot of them do things you *could* do with some custom code but with an extension you don't need to write that code.

**Reply:** Right on. And it's repeatable without having to recreate the wheel each time.

<br>&nbsp;

**Question:** How will analytics plugins be supported or replaced with Web SDK implementations?

**Answer:** Many analytics plugins are actually unnecessary these days thanks to added flexibility of Workspace and Adobe Tags. However, those that aren't, are actively being migrated for use by the Web SDK.

<br>&nbsp;

**Question:** Any development on Activity map tracking using Web SDK?

**Answer:** I'm happy to report that Activity Map is actively being worked on for support in Web SDK too

<br>&nbsp;

**Question:** Would we be able to have access to Adobe Edge network to manage events before transferring them over to the end destinations? I understand we can also do it in Launch but in the future would it be possible to do it at the server as well?

**Answer:** Yes! This is possible via our Event Forwarding feature, which customers can purchase through any of our Real-Time CDP products (Real-Time CDP Connections, Prime, or Ultimate).

**Answer:** RTCDP Connections (Event Forwarding) provides the ability to have more control before you send it to non-adobe destinations.

**Answer:** Check out some of our other ExL Live videos to learn even more about this (like [this one](exl-live-episode-06-23-22.md)).

<br>&nbsp;

**Comment:** Quick call out for one of my favorite extensions: There is a mapping table extension where you can read a table for a data element that "if this value is this then set it as that."

**Reply:** The flexibility they provide is quite impressive. Also to note, companies can create their own private extensions as well if they choose.

<br>&nbsp;

**Question:** You showed the individual data from CRM like city and weather, so where are we storing the individual response?

**Answer:** Responses are stored in each unique event that triggers a rule within an Event Forwarding property, and is used in that specific event only.

<br>&nbsp;

Continue the discussion on this topic in the [Experience League Community discussion](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-platform/experience-league-live-post-session-discussion-useful-extensions/m-p/542620#M240).
<br>&nbsp;

## Additional Experience League LIVE sessions from this data collection series

* [Ask the experts - The basics of Web SDK](exl-live-episode-05-26-22.md)
* [Ask the experts - RTCDP Connections](exl-live-episode-06-23-22.md)
* [Ask the experts - Datastreams and data prep](exl-live-episode-07-21-22.md)
