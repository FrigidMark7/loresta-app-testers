# Brief: Loresta phone app walkthrough

Read AGENT_BRIEF.md first: its tools, rules and final report files all apply.
Only the mission changes. The app is a phone app for creators who answer
their fans' messages and sell from one page.

## Sign-in: never try it
The first screen offers sign-in with Google, Apple or an emailed code. You cannot
finish any of them. Do not try. Tap **Preview a sample account** instead; it opens
the app with made-up data. (Ignore the "create an account" goal and the e-mail
rule of AGENT_BRIEF.md.)

## Mission (about 45 actions, then write the report)
1. Open every tab of the bottom bar in turn: Home, Inbox, Supporters, Updates,
   Settings. Scroll each one to the bottom.
2. Press every button, row and link you can see on each screen, then come back
   with the back button or gesture. Open one conversation and one supporter.
3. Pull down on a list to refresh.
4. Rotate the phone on two screens (`adb shell settings put system user_rotation 1`,
   back with `0`). Check large text, which is already set for you.
5. Leave the app (home button) and come back: it should be where you left it.

## Report these
Crashes or a white screen, buttons that do nothing, text that is cut off or
overlaps, content hidden behind the bottom bar or the notch, wording a creator
who is not technical would not understand, screens that are slow or jump.
Each with screenshot numbers, steps and severity, as in AGENT_BRIEF.md.
