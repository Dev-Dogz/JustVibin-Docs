# Setup

* **When added to the server we ask that you give Agent the** ADMINISTRATOR permission

## Agent's Prefix: <a href="#wicks-prefix" id="wicks-prefix"></a>

### a!

Custom prefixes have not yet been implemented.

## Setup <a href="#quick-setup" id="quick-setup"></a>

### Step 1: <a href="#step-1" id="step-1"></a>

* For Agent to function correctly, The Agent role must be placed at the top of the roles list.

### Step 2: Setting Roles <a href="#step-2" id="step-2"></a>

* Setting the Roles
* Use the prefix accompanied by the command
* Permit Levels:

Guild Owner (Permit Level 6)

`a!rmaster` : Sets master role (Permit Level 5) - Master is for trusted staff, it can change the most number of settings. Masters are the highest management under guild owners. They can manage members, channels, roles & staff.

`a!rowner` : Sets owner role, (Permit Level 4) Owners are higher management they can manage members, channels & roles.

`a!radmin` : Sets admin role, (Permit Level 3) Admins are management, they can manage members.

`a!rmoder` : Sets moderator role, (Permit Level 2) Moderators are lower admins

`a!rmain` : Sets main role, (Permit Level 1) Main is the main verified members role for your server.

`a!rmute` : Sets mute role - (Permit Level 0) The muted role for your server.

`a!rspam` : Sets spam-scam role - (Permit Level 0) The spam-scam role for your server.

`a!rquar` : Sets quarantine role, (Permit Level 0) The quarantine role for your server.

`a!runver` : Sets unverified role, (Permit Level 0) The unverified role for your server.

### Step 3: Setting Server <a href="#step-2" id="step-2"></a>

To set the channels use the following\
`a!logs #channel` : This sets the logging channel for your server.\
\
`a!makeverify #channel` : This sets the verification channel for your server.\
\
`a!spam enable/disable` : Enables/disables server anti-spam\
\
`a!roleping enable/disable` : Enables/disables server anti-role ping\
\
`a!links enable/disable` : Enables/disables server anti-links\
\
`a!words enable/disable` : Enables/disables server blackwords\
\
`a!joinraid enable/disable` : Enable/disable the join raid\
\
`a!joinraid kick/ban 5 10` : Triggers when 5 users join in 10 seconds, can kick or ban them.\
\
`a!mutetime (auto-mute period)` : Sets the time for how long a mute would last like defualt\
\
`a!joingate enable/disable (verify message)` : Enables or disables the joingate

### Step 4: Setting Up Whitelist <a href="#step-2" id="step-2"></a>

`a!whitelist spam add/del (channels)` : Adds and deletes whitelisted channels.\
\
`a!whitelist roleping add/del(roles)` : Adds and deletes whitelisted role pinging.\
\
`a!whitelist links add/del(links)` : Adds and deletes whitelisted links.\
\
`a!whitelist words add/del (blackwords)` : Adds and deletes whitelisted black words.

### Step 5: Setting Triggers & Blackwords <a href="#step-2" id="step-2"></a>

`a!trigger <command> <role> <x within min> <x within hour>` : Set triggers for certain roles.

`a!addblackword` : Adds black words. Anyone that sends one of these words the message will be deleted.\
\
`a!addblacklink link` : Adds black links. Anyone that sends one of these links the message will be deleted.\
\
`a!addblackname name` : Adds blacklisted names. Anyone that joins with a name from this list it will notify staff.

