# Anti Nuke / Anti Raid

Servers are raided on a daily basis. Whether its a rouge admin, server perms not setup properly or someone clicking a phishing link. This critical feature that increases security in any server is our **Anti Nuke/Raid System**. With our monitoring system observing the guilds including multiple actions of:

**Creation and Deletion of Roles or Channels**\
**Mass Bans**\
**Mass Kicks**\
**Emoji Creation and Deletion**\
**Blacklisted Names**

`a!trigger <command> <role> <x within min> <x within hour>` : Set triggers for certain roles.

`a!addblackword` : Adds black words. Anyone that sends one of these words the message will be deleted.\
\
`a!delblackword` | `<word>` Removes word from blacklist\
\
`a!addblacklink link` : Adds black links. Anyone that sends one of these links the message will be deleted.\
\
`a!delblacklink` | `<link>` Removes link from blacklist\
\
`a!addblackname name` : Adds blacklisted names. Anyone that joins with a name from this list it will notify staff.\
\
`a!delblackname` | `<name>` Removes name from blacklist

### Backup System

To ensure a safe server and working anti nuke system Agent will restore the latest back of your server. Agent is very efficient using this to fix raid/nuke attempts.\
\
\
`a!createbackup/bup` : Creates a backup of everything in your server.\
\
`a!autobackup/abup <minutes>` : Creates a automatic backup every \<minutes>\
\
`a!deletebackup/dbup <id>` : Deletes backup using the id\
\
`a!showbackup/sbup <id>` : Shows more information about backup by using the id\
\
`a!restoreall/rall <id>` : Restores everything\
\
`a!restoremissing/rms <id>` : Restores missing\
\
`a!restorechannel/rsc <all/channel(s)>` : Restores specified or all channels\
\
`a!restorerole/rsr <all/role(s)>` : Restores specified or all roles\
\
`a!restorewebhooks/rswh` : Restores all webhooks
