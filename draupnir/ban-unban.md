# Banning and unbanning users


## Banning a user

Sometimes you will have to ban a user from your rooms manually. To do this, you have two options:
* ban the user via your app in one of your rooms directly and then following the prompts in the management room
* ban the user via a command to your bot in the management room

To ban a user via your bot, run the following command in your management room:
```
!draupnir ban <user_ID> <list> <reason>
```
For example, if you want to ban the user `@example:example.org` on your default list for the reason "spam", then the command would look like this:
```
!draupnir ban @example:example.org list spam
```
Alternatively you can also do only `!draupnir ban @example:example.org` and then follow the prompts in the management room.  

## Unbanning a user

Sometimes you will have to unban a user from your rooms because you either accidentally banned them or you decided that they deserve a second chance. To do this, you have two options:
* unban the user via your app in one of your rooms directly and then follow the prompts in the management room
* unban the user via a command to your bot in the management room

To unban a user via your bot, run the following command in your management room:
```
!draupnir unban <user_ID>
```
For example, if you want to unban the user `@example:example.org`, then the command would look like this:
```
!draupnir unban @example:example.org
```
After sending the command, simply follow the prompts in the management room.