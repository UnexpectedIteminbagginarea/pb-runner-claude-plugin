# PB-Runner Running Coach

Use Claude as your running coach. PB-Runner is a running app for Garmin, Apple Watch, iPhone or Android. Claude reads your runs and recovery, then writes your next session to your watch or phone.

## What you can ask

Ask how a run went and Claude reads your splits, pace and heart rate. Ask how you are recovering and, on iPhone, it reads your resting heart rate, sleep and heart-rate variability from Apple Health alongside your recent training. Ask for a plan for a 5K, 10K, half marathon or marathon and it drafts the sessions, shows them to you and saves them only after you say yes.

- Send 6 x 800 m at my 5K pace to my Garmin for Thursday.
- How did my last run go?
- Build me a half marathon plan around four runs a week.
- How's my recovery looking this week?

## What's inside

- **The PB-Runner connector.** The plugin points Claude at the PB-Runner server at https://mcp.pb-runner.com/mcp, the same server as the PB-Runner Running Coach connector in Claude's directory. If you already connected that, there is nothing more to do. If not, connect it from the plugin's Connectors tab and sign in with the same Apple or Google account you use in the PB-Runner app.
- **A coaching skill.** It tells Claude to check your PB-Runner connection with the PB-Runner tools first, to help you get your runs in if there are none yet, to coach from your real data in your units, and to draft any plan and save it only after you confirm.

## What you need

The PB-Runner app (free on the App Store and Google Play), with some runs recorded or imported.

## Data

The plugin runs no code on your computer, fetches nothing and stores nothing. It holds one skill, which is a set of written instructions, and the address of the PB-Runner server. Your training data goes only between Claude and mcp.pb-runner.com through the connector, for the account you sign in with, and PB-Runner never sends Claude your GPS routes. Nothing is written to your schedule until you say yes in the conversation.

Privacy policy: https://pb-runner.com/privacy

Support: https://pb-runner.com/support or support@pb-runner.com

Setup guide: https://pb-runner.com/guide

Coaching is training guidance, not medical advice.
