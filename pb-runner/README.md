# PB-Runner Running Coach

Connect Claude to your running data and use it as your running coach. PB-Runner is a running app for Garmin, Apple Watch, iPhone and Android. Claude reads your runs and recovery, then writes your next session to your watch or phone.

## What you can ask

Ask how a run went and Claude reads your splits and pace. Ask for your personal bests, your goal progress or a race prediction. Ask for a plan for a 5K, 10K, half marathon or marathon and it drafts the sessions, shows them to you and saves them when you say yes. Saved sessions appear in the PB-Runner app's Schedule, play on your Apple Watch, your phone or the PB-Runner Garmin watch app with live cues, and can go straight to your Garmin Connect calendar.

- Help me set up my training plan.
- Analyze the splits of my last run.
- Put an interval session on my watch for Thursday.
- Build me a half marathon plan around four runs a week.

## You stay in control

Claude reads your training when you ask, and it changes your schedule, your profile or your logged runs only after you confirm a draft in the conversation.

## What's inside

- **The PB-Runner connector.** The plugin points Claude at the PB-Runner server at https://mcp.pb-runner.com/mcp, the same server as the PB-Runner Running Coach connector in Claude's directory. If you already connected that, there is nothing more to do. If not, connect it from the plugin's Connectors tab and sign in with the same Apple or Google account you use in the PB-Runner app.
- **A coaching skill.** It tells Claude to check your PB-Runner connection with the PB-Runner tools first, to help you get your runs in if there are none yet, to coach from your real data in your units, and to draft any plan and save it only after you confirm.

## Get the app

The PB-Runner app is free on the [App Store](https://apps.apple.com/app/id6769277536) and [Google Play](https://play.google.com/store/apps/details?id=com.bunker47.pbrunner). Runs from a Garmin linked in the app arrive by themselves, or record with PB-Runner on your Apple Watch, iPhone or Android phone. Connect PB-Runner in Claude with the same Apple or Google account you use in the app.

## Data

The plugin contains no code, scripts or hooks. It holds one skill, which is a set of written instructions, and the address of the PB-Runner server. Your training data goes only between Claude and mcp.pb-runner.com through the connector, for the account you sign in with, and PB-Runner never sends Claude your GPS routes. Nothing is written to your schedule until you say yes in the conversation.

Privacy policy: https://pb-runner.com/privacy

Support: https://pb-runner.com/support or support@pb-runner.com

Setup guide: https://pb-runner.com/guide
