# Anti Nuke / Anti Raid

Servers are raided on a daily basis. Whether its a rouge admin, server perms not setup properly or someone clicking a phishing link. This critical feature that increases security in any server is our **Anti Nuke/Raid System**. With our monitoring system observing the guilds including multiple actions of:

**Creation and Deletion of Roles or Channels**\
**Mass Bans**\
**Mass Kicks**\
**Emoji Creation and Deletion**\
**Blacklisted Names**













### Backup System

**If Imaging (Backups) is enabled:** Wick will save a backup/snippet (Image) of your server at regular intervals of time. The backup consists of everything except messages and role assignments. All the emojis are also stored. When a nuke occurs, Wick will load the latest backup corresponding to your server. Anything that does not match the image will be removed and all deletions that took place in that short span of time will be reverted back. It reverts the server back to normal, trying to cause as little damage as possible.

1. **If Imaging (Backups) is disabled:** Wick will try to use its memory and Discord to restore the server back to the original. **It is a finicky process and lacks a lot of information and the server may not be restored properly**.





A complex and efficient system known as **panic mode** allows Wick to fend off rapid mass nukes that may be done through scripts or specialized bots.

As soon as Wick notes a nuke attempt, it **locks down the server** and starts making amendments in the background. Only the owner and Wick will have complete authority in the server.

During a lockdown, Wick will also simultaneously deploy a miniWick that retrieves the server info before the nuke trigger. It takes time to find all the parties responsible that caused the nuke. This miniWick is separate from the Wick bot so it never burdens the Wick's resources. The bot is perfectly isolated from the miniWick so even if there are hundreds of nukes, Wick wouldn't suffer at all.

Once the causes are understood and fixed up, **Wick will load the latest snippet of your server saved!** This "loading up" is basically the **Restore System**.\
