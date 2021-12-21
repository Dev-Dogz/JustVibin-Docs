---
description: 'This page describes the core component of Wick: Quarantine'
---

# Quarantine



Quarantine is a crucial element of Wick. It is a core ingredient to its safety mechanism. Any rogue admins,  unverified users, bots will be added to it. Any account with dangerous permissions is added to it.

Anyone trying to **free** other users from quarantine will themselves be added to it, thus creating a **Domino Effect**.&#x20;

The importance of the Quarantine can be briefed in a few points:&#x20;

* **Nuke Attempts:** Wick will add any user with dangerous permissions/rogue admins to quarantine
* **Verification:** New users joining that have to verify will be quarantined **temporarily** until they pass verification.
* **Bypassing Quarantine:** Any bypass/freeing attempts without proper permissions will result in the user being quarantined.
* **Adding dangerous permissions to the Quarantine/Muted roles:** Adding dangerous permissions to the quarantine/muted roles will result in the user being quarantined.
* **Adding dangerous permissions to ANY role -if enabled-:** Quarantines a user that tries to give the ANY role some dangerous permissions.
* **Adding dangerous permissions to a STATIC role:** Giving dangerous permission to a user's static role that is currently in quarantine will result in that user being added to quarantine as well.
* **Other suspicious trends that we consider unsafe.**

{% hint style="warning" %}
#### With a proper wick setup, a user in Quarantine is not capable of doing ANYTHING. They can't even see channels unless the admins allow them to.
{% endhint %}
