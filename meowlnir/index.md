# Getting started with Meowlnir

After your request for a Meowlnir bot is approved, you'll receive an invite to
the management room from your moderation bot. The user ID will be of the form
`@meowlnir_<uuid>:asgard.chat`. The room will be unencrypted by default, but
you're free to enable encryption if you want it; the bot should come with
cross-signing full set up.

Once you join the room, you can use the `!help` command to view a full list of
available commands. Refer to the Meowlnir docs for actually subscribing to
policy lists and protecting rooms: <https://docs.mau.fi/meowlnir/bot-config.html>.

The most important command to get started is `!join <id or alias>` followed by
`!rooms protect <id or alias>` to protect a room. You can also use the
`!bot-profile` command to change the name and avatar of your bot.

The bot will be subscribed to the Community Moderation Effort (CME) and Cat's
Active Threats (CAT) lists by default. You're free to unsubscribe from them,
but we strongly encourage keeping them. To modify watched policy lists, you
currently have to edit the `fi.mau.meowlnir.watched_lists` state event by hand.

If you have questions that aren't covered by the docs or the help command, you can:

* Ask in the general Asgard chat [#general:asgard.chat](https://matrix.to/#/#general:asgard.chat)
* Ask in the official Meowlnir room [#meowlnir:maunium.net](https://matrix.to/#/#meowlnir:maunium.net)
