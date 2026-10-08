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

**🖼️ Thumbnail maker** (in each planner card) — Press **Generate thumbnail** to draw a YouTube-size thumbnail from the card's title: big outlined words, your channel colors, and emoji stickers that match the title. **🎲 Shuffle** for a new look, change the big/small text, then **💾 Save to card** (a mini preview shows on the card) or **⬇️ Download** the picture. The dashed circle is a spot to add a photo of your face in any photo app.

**📝 Script maker** (in each planner card) — Press **Generate script**. It reads the card's title and description to figure out what kind of video it is (hide and seek, race, build, battle, guessing, try-not-to-laugh, survival, contest...) and writes a script made for that kind: its own hook, rules, rounds, reactions and filming tips. Sentences from your description become the explanation and rules. Tick **⚡ This is a Short** on the card to get a 60-second Short script instead (filmed tall, with 0–3 sec hook, setup, action, payoff, ending). **🎲 New version** for different wording, edit anything, then **💾 Save to card**, **📋 Copy** or **⬇️ Download**.

**👍👎 Voting** (Idea Bank, Shorts & Planner) — Give ideas and episodes a thumbs up or thumbs down (one vote each; tap again to take it back). Score = 👍 minus 👎, and the best scores float to the top. Needs your family code and your name (⚙️ Settings).

**🔔 What's new** — When a sibling adds or moves a card, ticks a checklist, adds an idea, chats or comments, a line shows up in the What's new box at the top (even if the app was closed). Press **Got it ✓** to clear it.

**🎬 Filming** — Tools for filming day:
- **⏱️ Challenge timer** — a giant stopwatch (with 🏁 laps) or countdown (10 sec to 5 min) with beeps at the end. Tap **Full screen** to show it big on camera.
- **🎲 Who goes first?** — type the names, then pick a random order or make 2 teams.
- **🏆 Sibling scoreboard** — add who won each challenge and see the all-time leaderboard (shared with the family).

**📦 Archive** (in the Planner) — Finished a video? On Posted cards the ▶ becomes **📦** — tap it to archive the card so the board stays tidy (or use 📦 Archive in the card's pop-up). **📦 Show archived** brings them back (faded), with an Unarchive button.

**🗓️ Calendar** (in the Planner) — switch between **📋 Board** and **🗓️ Calendar** to see every film day and post day on a month calendar.

**🎥 Shot list** (in each planner card) — the scenes to film, in order. Use the starter shots or add your own, move them with ▲ ▼, and tick them off as you film.

**🤪 Idea Mashup** (on the Spin tab) — Makes a new idea from your bank: a **Double Challenge** (two short games in one video, most wins = champion) or a **twist** that fits that kind of video (like *Floor Is Lava Parkour, but no jumping allowed!*). It never mixes Gaming and Challenge ideas. Send it to the Planner if you like it.

**📱 Home screen app** — In Safari tap Share ⬆️ → **Add to Home Screen** to get the planner as an app with its own icon.

**✏️ Our punishments & twists** — Under the 🎡 wheel, add your own punishments (they become wheel slices; you can turn the starter ones off). Under 🤪 Mashup, add your own twists for Gaming, Challenge, or Both. Shared with the family when you're connected.

**🎉 Fun Extras** — A spinning punishment wheel, a title helper (*Who + What + Hook*), and a random intro-line picker.

**📦 Share & Backup** (in ⚙️ Settings) — Export everything to a file as a backup, or import a file from a sibling.

**👨‍👩‍👧 Family Sync** (in ⚙️ Settings) — Type your secret family code and press Connect. Everyone who uses the same code shares ONE planner, and changes show up on everyone's screen within a few seconds. This part needs the internet; if you're offline, changes wait and sync later. Keep the code secret!

**💬 Card comments** (in the Planner) — Tap 💬 on any card to talk about just that episode. It turns pink with a number when a sibling left a comment you haven't read yet (your own comments don't count). Separate from the main chat!

**💬 Chat** — Once you're connected with your family code, talk about what you're planning! Type your name once, then chat. A pink number on the Chat tab means new messages.

**✉️ Direct messages** (in Chat) — Private messages between two people. The first time, type your name and make up a secret PIN (4–8 numbers). Only you and the person you're messaging can read them — even someone else with the family code can't. Press **🔒 Lock** on a shared device.

**⚙️ Settings**
- **📺 Channel name** — Change the name at the top of the app. If you're connected with your family code, everyone sees the new name.
- **👤 Your name** — Used for chat, comments, votes and jobs.
- **🌙 Dark mode** — Darker colors for nighttime (just on your device).
- **😀 Show emojis** — Flip it off if all the emojis get annoying (just on your device, on by default). Nothing you saved changes; emojis are just hidden.

The stats line at the top shows how many ideas are banked and where your episodes are.

## For the coder 💻
All the code is in `index.html` with comments. The seed ideas are lists near the top of the `<script>`, so you can read or change them. Saved data lives in `localStorage` under the names `tes_ideas_v1` and `tes_episodes_v1`. To start over from scratch, clear this site's data in your browser settings.
