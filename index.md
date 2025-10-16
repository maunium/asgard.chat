# Introduction
Asgard offers hosted Matrix moderation bots for room admins who can't host one
themselves or just want a backup for their existing bot.

## Why?
Spam is always a risk in any public rooms. While you can do basic moderation
like banning users directly from your client, it won't scale easily. If you have
multiple rooms, you need to ban spammers from each room separately. Some clients
offer a button to redact all messages when banning, but it's easy to hit rate
limits when doing it with a normal account.

The benefits of moderation bots include:

* Automatically applying policies in multiple rooms.
* Deleting messages from banned users with less risk of hitting rate limits.
* Subscribing to policy lists like CME (Community Moderation Effort), which can
  give your rooms better coverage for getting rid of spammers without needing
  your own 24/7 moderation team.

## How?
We currently offer instances of [Meowlnir] and [Draupnir]. Both bots can follow
policy lists, apply user and server bans across multiple rooms, and redact
messages. Meowlnir is a newer bot that can be faster, while Draupnir has more
features like automatic (optional) protections that ban users for flooding or
sending an image as the first message after join.

[Meowlnir]: https://github.com/maunium/meowlnir
[Draupnir]: https://github.com/the-draupnir-project/Draupnir
[MSC4284]: https://github.com/matrix-org/matrix-spec-proposals/pull/4284

To get started, join the [#general:asgard.chat](https://matrix.to/#/#general:asgard.chat)
Matrix room, specify which bot you want and also include context about what
rooms you're protecting (space/room link, number of rooms, number of users in
rooms). After your request is approved, follow the Asgard docs for the bot you
chose:

* [Getting started with Draupnir](./draupnir/index.md)
* [Getting started with Meowlnir](./meowlnir/index.md)

## Who?
Asgard is maintained by [Tulir], [Sky], [Cat], and [Nex]. The server and domain
are funded by Tulir and Sky.

Meowlnir is primarily developed by Tulir and Draupnir by [Gnuxie]. If you use
Draupnir (or even if you don't and just want to support moderation bot development),
we recommend sponsoring Gnuxie on [GitHub sponsors](https://github.com/sponsors/Gnuxie)
or [Ko-fi](https://ko-fi.com/gnuxie).

[Tulir]: https://github.com/tulir
[Sky]: https://github.com/ll-SKY-ll
[Cat]: https://github.com/FSG-Cat
[Nex]: https://github.com/nexy7574
[Gnuxie]: https://github.com/Gnuxie
