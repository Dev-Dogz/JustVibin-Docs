# AGENT NOTES





1. Setup; setting roles for mods/admins/owner/master - setting logs channel&#x20;
2. Join Gate; verification (just simple verification, no captcha shit)&#x20;
3. Join Raid; set how many users join per minute to trigger join raid. (remind me to look into if it checks user\_id's- it's supposed to check to see if accounts were made on same day so a real user doesnt get caught up in the raid)&#x20;
4. Anti-Nuke; set triggers on how many times in 1 minute and 1 hour a mod/admin/owner can use a command&#x20;
5. Anti-spam/whitelist; set channels/users/roles to a whitelist that done get punished for ping/spam/roleping&#x20;
6. Backups; saves 10 backups, set autobackup timer, (remind me to test out the backup that should never get deleted unless you manually save a backup over it)
7. Moderation; just do !help and check all the mod commands (spamscam, mute, kick, ban, slowmode, etc)









settings = { # description in bot profile 'description': "I'm secret agent",

```
# first come the longer prefixes, and then the shorter ones
'bot_prefix_list': ('!',),

# token of your bot (tell me if the questions)
'token': 'OTA0NDk4Mzk0MDQ5OTYxOTg0.YX8ZxQ.2TAauCOZGJw3ho1k8MVi4ZWWVRI',

# help commands list of bot
'help': {
    'help': 'Displays a list of available commands',
    'logs <channel>': 'Sets logs channel',
    'alldms <channel>': 'Sets Agent DMs channel',
    'addmaster/amr <user>': 'Adds a new master',
    'addowner/ao <user>': 'Adds a new owner',
    'addadmin/aa <user>': 'Adds a new administrator',
    'addmod/am <user>': 'Adds a new moderator',
    'kick/k <user> "<reason>"': 'Kicks the listed users',
    'ban/b <user>, "<reason>"': 'Bans the listed users',
    'unban/ub <user>': 'Unbans the listed users',
    'giverole/gr <user> <roles>': 'Issues the specified role to the listed users',
    'removerole/rr <user> <roles> ': 'Takes the specified role to the listed users',
    'mute/m <user> <minutes>': 'Remove all roles and add `mute` role (restore all roles after mute time)',
    'unmute/um <user>': 'The opposite of mute',
    'purge <msgs amount> <user>': 'Deletes recent <msgs amount> messages',
    'createchannel/cc <name> <voice or text> <category>': 'Creates channel with specified parameters',
    'delchannel/dc <channel>': 'Deletes specified channel',
    'spamscam/ss <user>': 'Gives the `spam-scam` role to the user',
    'quarantine/q <user>': 'Places the member in quarantine',
    'unquarantine/unq <user>': 'Takes the member from quarantine',
    'slowmode/slm <seconds>': 'Sets slowmode to <seconds>',
    'timedmessage/tmsg <minutes> <channel> <message>': 'Sets timed message',
    'timedmessagelist/ltmsg': 'Sends list of timed messages',
    'deltimedmessage/dtmsg <id>': 'Removes timed message by id',
    'rmaster <role>': 'Sets master role',
    'rowner <role>': 'Sets owner role',
    'radmin <role>': 'Sets admin role',
    'rmoder <role>': 'Sets moderator role',
    'rmain <role>': 'Sets main role',
    'rmute <role>': 'Sets mute role',
    'rspam <role>': 'Sets spam-scam role',
    'rquar <role>': 'Sets quarantine role',
    'runver <role>': 'Sets unverification role',
    'lockexempt/lex <role>': 'Adds role exempt from lockdown',
    'dellockexempt/delex <role>': 'Removes role exempt from lockdown',
    'welcomemessage/wmsg <text>': 'Sets welcome message for new members',
    'makeverify/mkv <channel>': 'Sends verify message',
    'chanlockdown/chl <channel>': 'Locks down specified channel',
    'chanunlock/chul <channel>': 'Unlocks specified channel',
    'rolelockdown/rl <role>': 'Locks down specified role',
    'roleunlock/rul <role>': 'Unlocks specified role',
    'lockdown/l': 'Loks down server',
    'unlock/ul': 'Unlocks server',
    'sendmessage/sm <channel> <message>': 'Sends message to the specified channel',
    'senddm/sdm/warn <user> <message>': 'Sends DM message to the specified user',
    'sendembed/se <channel> "<title>" "<msg>" "<footer>" "<img>"': 'Sends embed message to the specified channel',
    'createbackup/bup': 'Creates a backup of everything',
    'autobackup/abup <minutes>': 'Creates a backup every <minutes>',
    'deletebackup/dbup <id>': 'Deletes backup by id',
    'showbackup/sbup <id>': 'Shows more information about backup by id',
    'restoreall/rall <id>': 'Restores everything',
    'restoremissing/rms <id>': 'Restores missing',
    'restorechannel/rsc <all/channel(s)>': 'Restores specified or all channels',
    'restorerole/rsr <all/role(s)>': 'Restores specified or all roles',
    'restorewebhooks/rswh': 'Restores all webhooks',
    'whitelist/wl <ping or spam or roleping> <add or del or enable or disable> <channel or user or role>': 'Adds or removes a chan/user/role to whitelist',
    'trigger/tr <command> <role> <times per minute> <times per hour>': 'Adds trigger to control admins activities',
    'addblackword/abw <word>': 'Adds forbidden word',
    'delblackword/dbw <word>': 'Removes forbidden word',
    'mutetime/mt <minutes>': 'Sets the auto mute time',
    'joinraid/jr <joins> <minutes>': 'Sets the joinraid trigger',
    'joingate/jt <kick or mute or ban or quar> <days>': 'Sets the joinraid trigger',
    'addblacklink/abl <link>': 'Sets the black link',
    'delblacklink/dbl <link>': 'Removes the black link',
    'leavelist/ll <enable or disable or exempt or unexempt> <role>': 'Rich, pls write the annotation to this',
    'antispam/asp <messages> <seconds>': 'Rich, pls write the annotation to this'
},

# embed sideline color in all messages
'success color': (47, 49, 54),
# embed sideline color in error messages
'error color': (216, 65, 65),

# embed sideline color in warning messages
'warn color': (230, 233, 84),

#bot will ping staff if a member with this name joins (low case)
'warn names': ['trade hub', 'the hub', 'rich', 'noahr', 'support', 'help', 'admin', 'owner', 'moderator', 'hubert', 'peggy'],

# Don't touch it!!!
```

}\
