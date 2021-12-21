# Anti Raid

The critical feature that differentiates Wick from **all** other Discord Bots is its **anti-nuke system**. It is a monitoring system with the objective to observe and note any changes (spontaneous or planned) that take place in your server. Some of the key observation markers are:\
\
**1. Channels creation and deletion**\
**2. Bans**\
**3. Emoji creation and deletion**\
\
It covers **everything that can destroy your server!** It is a system made to counter any rogue admins or other key members that may have the power to make changes in the server.

To allow the system to hold its integrity, Wick also notes any attempts to bypass the Anti-Nuke system. It will strip off the power of a rogue admin/bot or member and notify the owners immediately.

### Panic Mode

A complex and efficient system known as **panic mode** allows Wick to fend off rapid mass nukes that may be done through scripts or specialized bots.

As soon as Wick notes a nuke attempt, it **locks down the server** and starts making amendments in the background. Only the owner and Wick will have complete authority in the server.

During a lockdown, Wick will also simultaneously deploy a miniWick that retrieves the server info before the nuke trigger. It takes time to find all the parties responsible that caused the nuke. This miniWick is separate from the Wick bot so it never burdens the Wick's resources. The bot is perfectly isolated from the miniWick so even if there are hundreds of nukes, Wick wouldn't suffer at all.&#x20;

Once the causes are understood and fixed up, **Wick will load the latest snippet of your server saved!** This "loading up" is basically the **Restore System**.&#x20;

![](broken-reference)

### Restore System

Restore System counts on two scenarios.

1.  **If Imaging (Backups) is enabled:** Wick will save a backup/snippet (Image) of your server at regular intervals of time. The backup consists of everything except messages and role assignments. All the emojis are also stored. When a nuke occurs, Wick will load the latest backup corresponding to your server. Anything that does not match the image will be removed and all deletions that took place in that short span of time will be reverted back. It reverts the server back to normal, trying to cause as little damage as possible.


2. **If Imaging (Backups) is disabled:** Wick will try to use its memory and Discord to restore the server back to the original. **It is a finicky process and lacks a lot of information and the server may not be restored properly**.&#x20;
