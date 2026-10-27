# Privacy Policy — DBuddy

Last updated: 2026-10-22 (version 2.0.5)

DBuddy does not sell personal data, and shows no ads. Most of it works only in your browser. The optional DBling coins and foil rarity sharing use a small server of ours, and only after you press **Connect Discord**.

## Without connecting Discord

Everything stays on your device, apart from the anonymous theme count below:

- Your settings (theme, colours, keyboard shortcuts, muted usernames, alert choices, window positions).
- Your notes, action log, background image, custom CSS, and the finishes you give your cards.

All of this is kept in your browser's extension storage. Settings also sync between your own browsers if you use Chrome sync. You can export, import or erase everything from the Support tab ("Reset all settings"), or by removing the extension.

**Anonymous theme count** (on unless you switch it off): once a day, if you have not connected Discord, DBuddy sends our server only which theme you have on (or "no theme"), and our server only adds 1 to that theme's count for the day (kept 30 days). Our server keeps no id, name, account or address; Cloudflare, which hosts it, keeps standard request logs (such as your IP address) for a few days. Switch "Share anonymous theme counts" off in Settings › Privacy to stop it.

The extension reads public files from DuelingBook's own image server (images.duelingbook.com), the same ones the site loads.

## With "Connect Discord" (optional)

DBling coins, bought finishes and showing your finishes to opponents need an account. Your Discord account is that account. When you connect, our server (Cloudflare Workers and Cloudflare D1, stored in Europe) keeps:

- **Your Discord user id**, and a **hash of your Discord email** (SHA-256, plus a masked hint such as `p•••@gmail.com`). Discord only gives us the email if it is verified. It is used only to match your Buy Me a Coffee membership and tips to your coins. We never keep the email itself, your Discord name, your messages or your password.
- **Your coins**: balance, membership tier, and a history of grants, purchases, tips and top-ups.
- **What you bought**: the finishes and looks per card name, and a copy of the finishes your cards show, so a new browser can get them back.
- **Your DuelingBook name**, linked when you log in, if "Show my rarities to opponents" is on. Opponents who use DBuddy then see the finishes you own. Turn it off in the Rarities tab, and your shared list is deleted.
- **Codes**: your tip code, and the creator code you used or own (creator program).
- **Which DBuddy theme you have on**: only the theme's name (or "no theme"), sent with the coin refresh, and the days of the last 30 on which each theme was on. It shows us which themes people use, so unused ones can be retired. Nothing else about your settings is sent.
- **Joining our Discord** (the "Also join the DBuddy Discord" box at Connect Discord): Discord then also asks to let us add you to a server. That permission is used once, to add you to the DBuddy server, and is never stored. We keep whether you are in our server and whether its one-time 100 coins were paid.
- **Your Discord roles in our server** are read to give your monthly coins (Supporter, Duelist, Legend, Godlike, Coffee, Content Creator).

## Buy Me a Coffee

When someone tips or becomes a member on buymeacoffee.com/sudbina, Buy Me a Coffee sends our server the payment (amount, the message, the supporter's email). We use it only to add coins, or the membership tier and its Discord role, to the account whose tip code is in the message, or whose linked email matches. We keep the payment id and amount with your coin history, and the email only as a hash. A tip that matches nobody waits, as a hash, for up to a year; a membership waits while it runs.

An email is linked to an account only when it is proven: your Discord-verified email when you connect, or a moderator who checked it with you (they see it only masked afterwards).

If you allow it, the "Or tip" link fills your tip code into the Buy Me a Coffee message box for you. That is the only thing DBuddy does on buymeacoffee.com, and only when you click it.

## Who can see what

- **Opponents** who use DBuddy see the finishes you own, under your DuelingBook name, while sharing is on.
- **Our Discord moderators** see coin events in a private staff channel: your Discord user, coins added or spent, tip and membership amounts, and masked emails (`p•••@gmail.com`). They use it to help with missing coins and to stop abuse.

## Deleting your data

- **Disconnect** signs this browser out.
- **Delete account** (Settings tab, under Account) deletes your account from our server: coins, purchases, codes, linked email, names and coin history. The finishes on your cards stay in your browser until you clear them.
- What stays: that your Discord id once used a creator code (so a code cannot be used twice), whether it already got this month's coins, the one-time tip bonus, the one-time Discord join bonus and the pre-2.0 finish claim (so deleting and reconnecting does not hand them out again; no coins, purchases or links), Buy Me a Coffee payments and memberships kept by email hash, Discord roles you were given, and past posts in the staff channel. Email us to remove those too.
- Or email us and we delete it for you.

## Permissions

- **storage**: to remember your settings and notes.
- **unlimitedStorage**: so a large background image fits on your device. Nothing is uploaded.
- **scripting**: to re-attach the extension to DuelingBook tabs that were already open when it was installed or updated, and to fill your tip code on the Buy Me a Coffee page when you click "Or tip".
- **identity** (optional, asked when you press Connect Discord): to log in with Discord.
- **Our points server** (optional host permission, asked with Connect Discord): to read and update your coins.
- **buymeacoffee.com** (optional host permission, asked the first time you click "Or tip"): to fill in your tip code.
- The extension itself runs only on duelingbook.com.

## Contact

Questions or deletion requests: paul.lukic94@gmail.com, or open an issue at https://github.com/paullukic/dueling-book-theme-editor/issues.

Publisher: Sudbina
