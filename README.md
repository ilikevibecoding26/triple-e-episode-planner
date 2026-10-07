# 🎬 Triple E Studios — Episode Planner

## How to open it
**Double-click `index.html`.** That's it! It opens in your web browser.

- ❌ No installing anything
- ❌ No internet needed (except for Family Sync)
- 🌐 Or just open the website: https://ilikevibecoding26.github.io/triple-e-episode-planner/
- ✅ Everything you add is saved automatically in your browser, so it's still there next time

> Use the same browser each time (e.g. always Safari or always Chrome) — each browser keeps its own saved stuff.

## Quick tour

**🎲 Spin** — Pick Gaming, Challenge, or "Surprise me!", then press the big button for a random idea.
- 🔄 *Give me another!* rolls again
- 📋 *Send to Planner* makes an episode card
- ✅ *Already did this one* hides it from future spins so ideas stay fresh

**💡 Idea Bank** — See every idea (40+ ready to go!). Add your own with the form, filter by channel, mark ideas done, or 🗑️ delete them. Your own ideas get a ⭐.

**📋 Planner** — Five columns: **Idea → Planned → Filming → Editing → Posted**. Move cards with ◀ ▶, or drag them. Click a title (or ✏️) to add title options, a thumbnail idea, a spoken hook, and a punishment. Tap 🗑️ twice to delete a card.

**📅 Dates, 🙋 jobs & ✅ checklists** (in each planner card) — Pick a *Film on* and *Post on* date, add who's doing what (like "Big Sis: Editing"), and tick off the filming checklist. The **Coming up** box at the top of the Planner shows the next 2 weeks (late stuff turns red), and **Show cards for** filters the board to one person.

**👍👎 Voting** (Idea Bank, Shorts & Planner) — Give ideas and episodes a thumbs up or thumbs down (one vote each; tap again to take it back). Score = 👍 minus 👎, and the best scores float to the top. Needs your family code and your name (⚙️ Settings).

**🎉 Fun Extras** — Punishment picker, a title helper (*Who + What + Hook*), and a random intro-line picker.

**👨‍👩‍👧 Family Sync** (in ⚙️ Settings) — Type your secret family code and press Connect. Everyone who uses the same code shares ONE planner, and changes show up on everyone's screen within a few seconds. This part needs the internet; if you're offline, changes wait and sync later. Keep the code secret!

**💬 Card comments** (in the Planner) — Tap 💬 on any card to talk about just that episode. It turns pink with a number when a sibling left a comment you haven't read yet (your own comments don't count). Separate from the main chat!

**💬 Chat** — Once you're connected with your family code, talk about what you're planning! Type your name once, then chat. A pink number on the Chat tab means new messages.

**⚙️ Settings**
- **📺 Channel name** — Change the name at the top of the app. If you're connected with your family code, everyone sees the new name.
- **👤 Your name** — Used for chat, comments, votes and jobs.
- **🌙 Dark mode** — Darker colors for nighttime (just on your device).
- **😀 Show emojis** — Flip it off if all the emojis get annoying (just on your device, on by default). Nothing you saved changes; emojis are just hidden.

The stats line at the top shows how many ideas are banked and where your episodes are.

## For the coder 💻
All the code is in `index.html` with comments. The seed ideas are lists near the top of the `<script>`, so you can read or change them. Saved data lives in `localStorage` under the names `tes_ideas_v1` and `tes_episodes_v1`. To start over from scratch, clear this site's data in your browser settings.
