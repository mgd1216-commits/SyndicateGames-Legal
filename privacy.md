# Syndicate Games Privacy Policy

Effective Date: November 11, 2026

This policy explains what data the Syndicate Games Discord bot collects, why, where it is kept, how long it is kept, and how to have it deleted. It describes how the bot actually works today.

---------------------------------------------------------------------

1. What We Collect

- Discord identifiers: your user ID and username, the IDs of servers the bot is in, and the channel and role IDs that server admins choose in the bot's settings.
- Game and economy data: virtual coin balances, game results, Syndicate Card collections, leaderboard stats and transaction history. Coins are virtual and have no real-money value.
- Command usage: the command name, the options you type into it, your user ID and username, and the server and channel it was used in. This is also posted to the bot owner's log channel in Discord when command logging is on.
- Alerts: the ID of the last in-bot alert you were shown, so you only see each alert once.
- Agreements: whether you (and each server) accepted our Terms of Service and this Privacy Policy, and when.
- Votes: your user ID, vote totals and streaks, and an audit record of each vote when you vote for the bot on Top.gg.
- Rumble Assistant payouts: the server, channel and message ID of a Rumble Royale winner message, the winner's user ID and the amount paid, to prevent double payouts.
- Premium Shop requests: the custom name, colors and design you enter when you buy a custom item are sent to the bot owner so it can be made.
- Preferences: your vote-reminder setting and any DM preference you set in the past.

We do not collect email addresses, IP addresses, phone numbers or payment information.

---------------------------------------------------------------------

2. Message Content

Some features read the text of messages. This is how each one works:

- Triggers (admin-created auto-responses): in servers whose admins create triggers, the bot checks the text of members' messages for the trigger words those admins set. Staff can also send triggers with the /t slash command, which reads no message text. When a trigger fires:
  - a log entry with up to 1,000 characters of the triggering message is posted to the bot owner's log channel in Discord (when trigger logging is turned on), and to a separate log channel if one is set for that trigger;
  - the trigger name, user, server, channel and matched word are written to our logs. For pattern-based triggers, the matched word is the part of your message that matched.
- Ping Shield (anti-ping protection): uses Discord's mention data to remove messages that ping protected members. When it removes a message, a preview of up to 200 characters is posted to that server's own staff log channel.
- Rumble Assistant: in servers we have approved, it reads only messages sent by the Rumble Royale bot, only in battle channels the server's admins select, to detect battle starts and winners. Up to 200 characters of that bot's message text and embeds are written to our bot's process logs. It never reads members' own messages.
- Admin upload prompts: when an admin is asked to send a file or emoji in the channel, the bot reads that one message; a file link they send is saved to the setting it was meant for.

We do not save message text in our database, and we do not collect message history or private messages. Message content is never used to train AI or machine-learning models and is never sent to any AI service.

---------------------------------------------------------------------

3. Member Data

- When someone joins or leaves a server, the bot uses that event only to post the welcome message or join/leave log that the server's admins set up, in the channel they chose.
- For role-based features (the weekly Money Mob drawing and adding a role's members to the Wheel of Fate), the bot loads the server's member list to see who holds the role.

Member lists and join/leave events are not saved. We do not use presence data.

---------------------------------------------------------------------

4. Why We Use This Data

- To run the bot: games, economy, leaderboards, triggers, welcome messages and logs.
- To protect fairness and safety: anti-cheat, anti-abuse, vote-fraud checks and blocking abusive users.
- To find and fix problems: error logs and diagnostics.

We never sell your data.

---------------------------------------------------------------------

5. Where Data Is Kept and Who Processes It

- Neon: hosts our PostgreSQL database.
- Hetzner: hosts the server the bot runs on (managed with Coolify), including its process logs and log files.
- Discord: log entries posted to Discord channels stay in Discord.
- Top.gg: sends us your user ID when you vote. We do not send them your data.
- fal.ai: generates artwork for games from our own prompts. It receives no user or message data.

The database, server and log files are accessible only to the bot's developer. Log entries posted in Discord channels can be seen by whoever has access to those channels.

---------------------------------------------------------------------

6. How Long We Keep It

- Transaction history: 30 days.
- Command and trigger logs: 14 days in our database; log files are deleted after 7 days.
- Process logs on our server: rotated automatically. At most about 30 MB of the most recent logs are kept (3 files of 10 MB), and older entries are overwritten.
- Vote audit records (used for vote-fraud checks): 90 days. Your vote totals and streaks are part of your game data.
- Log entries posted to Discord channels: until the channel's owner deletes them.
- Profile, game, card, payout and settings data: until you or a server admin asks us to delete it.
- Moderation and anti-fraud records (such as block lists and vote-fraud logs): kept to protect the community, even after a deletion request.

---------------------------------------------------------------------

7. Your Choices

- There is no individual opt-out from message reading. Server admins decide which features run in their server: they can switch off or delete any trigger and remove Rumble Assistant battle channels at any time.
- Owner announcements are shown as in-bot alerts after your next command. We do not DM them.
- Vote reminders can be turned on or off at any time with /votereminder.
- Declining our Terms/Privacy prompt locks bot commands for you.

---------------------------------------------------------------------

8. How to Request Data Deletion

To have all data linked to your Discord ID deleted, contact us:

- Support Server: https://discord.gg/PY6sfJhct6
- Email: Troublethedonsyndicate@gmail.com

We delete your profile, economy, game, card and preference data from our database within 48 hours of your request. Logs expire on the schedule in section 6. Moderation and anti-fraud records may be kept as described above.

---------------------------------------------------------------------

9. Children

Like Discord, Syndicate Games is not meant for anyone under 13, and we do not knowingly collect data from children under 13.

---------------------------------------------------------------------

10. Changes and Contact

We will update this policy when the bot's data practices change and update the effective date above. For privacy questions:

- Email: Troublethedonsyndicate@gmail.com
- Support Server: https://discord.gg/PY6sfJhct6
