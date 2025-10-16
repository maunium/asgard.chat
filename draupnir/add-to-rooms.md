# Adding your bot to rooms

In order for your bot to be able to do anything in your rooms at all, it has to actually be in your rooms.

To tell draupnir to "protect" a room, you have to run the following command:
```
!draupnir rooms add <room alias/ID>
```
For example, if the alias of your room would be `#example:example.org`, then the command would look like this:
```
!draupnir rooms add #example:example.org
```
Alternatively, you can invite the bot to your room and then follow the prompts in the management room.  

### Giving the bot the necessary permissions

Usually, you want your bot to be able to ban people and servers in your room.  
For that, the bot needs permissions to send the following events:
* `ban`
* `m.room.server_acl`

In Element, you can do that by opening the room settings, going to **"Roles & Permissions"** and then making sure that your bot has the role that is configured for **"Ban users"** and **"Change server ACLs"**.

Repeat the steps for every room you want to protect.