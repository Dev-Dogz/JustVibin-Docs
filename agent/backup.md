# Backup



To ensure a proper anti-nuke system, Wick has to **restore what was damaged**. Wick is effective and efficient against nuke attempts, but these attempts result in some loss or creation of discord components (channels, roles, emojis, or webhooks)

Wick takes a snippet of your server at regular intervals of time which is used after a nuke attempt has occurred. The snippet consists of **all of your server components except messages and role assignments** (not to be confused with roles). After a Nuke attempt, Wick will **load the recent image found** while taking some precautionary measures. It will not mess with your server, it will just restore it to a previous safe state. All deletions and creations will be restored, including emojis.

![](broken-reference)

{% hint style="info" %}
In the future, there will be a command available where you can take a backup and another load backups so that it can be available separately from the anti-nuke.
{% endhint %}
