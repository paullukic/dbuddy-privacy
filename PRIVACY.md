# Privacy Policy — DBuddy

Last updated: 2026-11-04 (purchases of the last hour kept for undo; rarity sell-back)

DBuddy does not sell personal data, and shows no ads. Most of it works only in your browser. The optional DBling coins and foil rarity sharing use a small server of ours, and only after you press **Connect Discord**.

## Without connecting Discord

Everything stays on your device, apart from the anonymous theme count below:

- Your settings (theme, colours, keyboard shortcuts, muted usernames, alert choices, window positions).
- Your notes, action log, background image, custom CSS, and the finishes you give your cards.

All of this is kept in your browser's extension storage. Settings also sync between your own browsers if you use Chrome sync. You can export or import it in the Settings tab, under Backup and reset. "Reset all settings" there puts your settings back to default and clears the cached overframe images and the list of cards they came from. The foil images DBuddy draws for itself stay on your device until the next update redraws them. They hold nothing about you. Removing the extension erases all of it.

**Rarity list updates:** on install, and at most every 2 days after, DBuddy asks our server whether the list of real card rarities changed, and downloads it if so. These requests carry no account or settings, and our server keeps nothing from them. Like any request, they reach our host (Cloudflare) with your IP address, and on Firefox with the random id of your install, neither of which we store.

**Anonymous theme count** (on unless you switch it off): DBuddy shows a one-time note on duelingbook.com first, and sends nothing until that note has been shown. After that, once a day, if you have not connected Discord, DBuddy sends our server only which theme you have on (or "no theme"), and our server only adds 1 to that theme's count for the day (kept 30 days). Our server keeps no id, name, account or address; Cloudflare, which hosts it, keeps standard request logs (such as your IP address) for a few days. Switch "Share anonymous theme counts" off in Settings › Privacy to stop it.

The extension reads public files from DuelingBook's own image server (images.duelingbook.com), the same ones the site loads.

**Overframe images**: if you or a player you watch shows a card as Overframe (UR) or Overframe (ST), DBuddy downloads that card's overframe images from our image server (dbuddy-assets.shadow-lukic31-6cc.workers.dev). Like any web request this shows the server your IP address and which card's images were asked for. No cookie or id is sent, and we keep no logs of these requests. The images are kept in your browser so they are not downloaded again.

## With "Connect Discord" (optional)

DBling coins, bought finishes and showing your finishes to opponents need an account. Your Discord account is that account. When you connect, our server (Cloudflare Workers and Cloudflare D1, stored in Europe) keeps:

- **Your Discord user id**, and a **hash of your Discord email** (SHA-256, plus a masked hint such as `p•••@gmail.com`). Discord only gives us the email if it is verified. It is used only to match your Buy Me a Coffee membership and tips to your coins. We never keep the email itself, your Discord name, your messages or your password.
- **Your coins**: balance, membership tier, whether it is paid yearly, and a history of grants, purchases, undone purchases, rarities sold back, tips and top-ups.
- **What you bought**: the finishes and looks per card name, and a copy of the finishes your cards show, so a new browser can get them back. Your purchases of the last hour (what each bought and cost) are kept for 60 minutes so you can undo one, along with how many undos you used this month and which finishes were free pre-2.0 gifts that cannot be sold back.
- **Your DuelingBook name**, linked when you log in, if "Show my rarities to opponents" is on. Opponents who use DBuddy then see the finishes you own. Turn it off in the Rarities tab, and your shared list is deleted.
- **Codes**: your tip code, and the creator code you used or own (creator program).
- **Which DBuddy theme you have on**: only the theme's name (or "no theme"), sent with the coin refresh, and the days of the last 30 on which each theme was on. It shows us which themes people use, so unused ones can be retired. Nothing else about your settings is sent.
- **Joining our Discord** (the "Also join the DBuddy Discord" box at Connect Discord): Discord then also asks to let us add you to a server. That permission is used once, to add you to the DBuddy server, and is never stored. We keep whether you are in our server and whether its one-time 100 coins were paid.
- **Your Discord roles in our server** are read to give your monthly coins (Supporter, Duelist, Legend, Godlike, Coffee, Content Creator).

## Buy Me a Coffee

When someone tips or becomes a member on buymeacoffee.com/sudbina, Buy Me a Coffee sends our server the payment (amount, the message, the supporter's email). We use it only to add coins, or the membership tier and its Discord role, to the account whose tip code is in the message, or whose linked email matches. We keep the payment id and amount with your coin history, and the email only as a hash. A tip that matches nobody waits, as a hash, for up to a year; a membership waits while it runs.

If a payment cannot be applied automatically, we keep its details (amount, level, status, the masked email and a hash of it, never the email itself, your name or your message) for 90 days so a moderator can sort it out, longer only if our moderators could not be told about it yet.

An email is linked to an account only when it is proven: your Discord-verified email when you connect, or a moderator who checked it with you (they see it only masked afterwards).

If you allow it, the "Or tip" link fills your tip code into the Buy Me a Coffee message box for you. That is the only thing DBuddy does on buymeacoffee.com, and only when you click it.

## Who can see what

- **Opponents** who use DBuddy see the finishes you own, under your DuelingBook name, while sharing is on.
- **Our Discord moderators** see coin events in a private staff channel: your Discord user, coins added or spent, tip and membership amounts, and masked emails (`p•••@gmail.com`). They use it to help with missing coins and to stop abuse.

## Tournament coins (partner Discord servers)

Some partner servers run DuelingBook tournaments with RetroBot, a tournament bot. With the partner's permission, our bot reads the results RetroBot posts in their tournament channels. It only reads; it never posts there. When you place in the paid top places, the coins go to the DBuddy account of your Discord id. We keep:

- **The tournament results we read**: for every match line RetroBot posts, the Discord ids of the players, the names RetroBot shows, the DuelingBook names shown as "(DB: …)" when there are any, who beat whom, and the message ids and times. This covers every player in a watched tournament, also players who do not use DBuddy, because the bracket is rebuilt from all its matches. Only these fields are kept, not the message text.
- **What was paid**: placement, coins, how the player was matched (Discord id, DuelingBook name, or a moderator), and a moderator's review if there was one.

Our moderators see these in the staff channel, as with other coin events. A player who has a DBuddy account and is on our Discord is told about the coins in a private channel only they can see.

## Deleting your data

- **Disconnect** signs this browser out.
- **Delete account** (Settings tab, under Account) deletes your account from our server: coins, purchases, codes, linked email, names and coin history. The finishes on your cards stay in your browser until you clear them.
- What stays: a one-way hash of each Buy Me a Coffee payment made to the account, with no name, email, amount or link to you, so the same payment can never pay twice; that your Discord id once used a creator code (so a code cannot be used twice), whether it already got this month's coins, the one-time tip bonus, the one-time Discord join bonus and the pre-2.0 finish claim (so deleting and reconnecting does not hand them out again; no coins, purchases or links), Buy Me a Coffee payments and memberships kept by email hash, Discord roles you were given (paid tier and Annual roles go when a plan is linked, and reconnecting with the same email gives them back while the plan runs), and past posts in the staff channel, including a creator's id and amounts if they delete with money on record. Email us to remove those too.
- **Tournament records also stay**, with your Discord id, for audit: the results we read (above) and the placements paid. They show which placement was paid to whom, so a placement can never be paid twice, and a moderator can check a payout later. After you delete your account, no tournament message is sent to you: notices skip deleted accounts.
- Or email us and we delete it for you.

## Permissions

- **storage**: to remember your settings and notes.
- **unlimitedStorage**: so a large background image and the foil images DBuddy draws fit on your device. Nothing is uploaded.
- **scripting**: to re-attach the extension to DuelingBook tabs that were already open when it was installed or updated, to load a theme's attack effect or animated scene from the extension's own files when a DuelingBook tab needs it, and to fill your tip code on the Buy Me a Coffee page when you click "Or tip".
- **identity** (optional, asked when you press Connect Discord): to log in with Discord.
- **Our points server** (optional host permission, asked with Connect Discord): to read and update your coins.
- **buymeacoffee.com** (optional host permission, asked the first time you click "Or tip"): to fill in your tip code.
- The extension itself runs only on duelingbook.com.

## Contact

Questions or deletion requests: paul.lukic94@gmail.com, or ask a mod in our Discord: https://discord.gg/XtP5Vj4q3C.

Publisher: Sudbina
