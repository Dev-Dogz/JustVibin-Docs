# Server Tools

`a!purge <qty> @User` : Purges messages\
**Note**: Only owner can use without specifying user\
\
`a!slowmode <seconds>` : Assigns slow mode time to current channel

### Timed Messages

`a!timedmessage <minutes> #channel <message>` : Sends message on timer \
\
`a!timedmessagelist` : Shows list of timed messages and their IDs \
\
`a!deltimedmessage <id>` : Deletes a timed message

### Lockdown Commands

`a!lockexempt <role>` : Exempts role from lockdown \
\
`a!dellockexempt <role>` : Removes role from lockdown exmpt\
\
`a!chanlockdown` : Locksdown the channel, restricting access \
\
`a!chanunlock` : Unlocks the channel \
\
`a!rolelockdown <role>` : Locksdown a role, restricting perms \
\
`a!roleunlock <role>` : Unlocks a role

### Bot Messages

`a!sendmessage #channel <msg>` : Sends a text message to channel \
\
`a!sendembed #channel> <title> <message> <footer> [image]` : Sends embed to channel

### Whitelist

`a!whitelist <ping/roleping/spam/links/words> <add/del/enable/disable> <role/channel/user>` : Whitelist one of the following for different areas of the server.
