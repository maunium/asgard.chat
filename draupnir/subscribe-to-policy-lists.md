# Subscribing to policy lists

Policy lists are like a shared blacklist and bots can subscribe to them.
For example: A user starts spamming in room A and as a result gets added to a policy list that your bot subscribes to. Your bot will block that user from your rooms automatically.

Your Draupnir will create a personal policy list for you automatically when it is set up, however, there are more lists out there that you can "watch".

#### To subscribe to more policy lists, you have to write the following command in your management room:
```
!draupnir watch <room alias/ID>
```
#### For example, to subscribe to the **community-moderation-effort (CME)** list, write:  
```
!draupnir watch #community-moderation-effort-bl:neko.dev
```
<br>

## Recommended policy lists:

### Community Moderation Effort (CME):

This list is maintained by the Matrix community itself and contains spammer & scammer accounts.
It is trusted by many; for example the Debian and Ubuntu communities. This list is generally really fast and has an extremely low rate of false positives. Any false positives get removed as soon as managers are made aware of them.
#### The policy room is: [#community-moderation-effort-bl:neko.dev](https://matrix.to/#/#community-moderation-effort-bl:neko.dev)


### Project Huginn and Muninn Active Threats (CAT):

This list is maintained by the matrix community itself and contains ACL's for servers which are actively used in attacks.
This list is really fast and all servers are manually checked before they are added.
#### The policy room is: [#huginn-muninn-active-threats:feline.support](https://matrix.to/#/#huginn-muninn-active-threats:feline.support)

### Matrix.org Code of Conduct (COC):

This list is maintained by the matrix.org foundation.
It is used by the foundation itself and some communities use it too. This list contains bans for all kinds of behaviour that violated the matrix.org code of conduct. This means that this list not only contain spammers but also trolls, rude people and more.
#### The policy room is: [#matrix-org-coc-bl:matrix.org](https://matrix.to/#/#matrix-org-coc-bl:matrix.org)