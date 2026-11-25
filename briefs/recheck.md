# Brief: re-check four fixes in the Loresta phone app

Read AGENT_BRIEF.md first: its tools, rules and final report files all apply.
Sign-in: never try it. Tap **Preview a sample account** (it may be below the first
screen: scroll). Ignore the "create an account" goal and the e-mail rule.

Check exactly these four things, about 40 actions in all. For each, write one line
in report.md: FIXED, NOT FIXED or COULD NOT CHECK, with screenshot numbers and what you saw.

1. Report dialog: Supporters > any supporter > More > Report this person (and the
   same for Block). A dialog opens with a visible Cancel. Android Back closes it,
   and tapping outside the dialog closes it, without filing anything.
2. Your font size is already set (see the device line). On the sign-in screen, is
   "Preview a sample account" reachable by scrolling? On Home, Messages, Supporters,
   Updates and Settings: do the screen titles stay whole words (no "Supporte / rs")?
   In Settings, are all three reply options (Off, Draft, Send safe ones) shown in full?
3. Messages > open a conversation > Write my own > tap the box and type a few words.
   Are the box and the Send reply button both still visible above the keyboard?
   Then press Android Back: do you land on the Messages list?
4. Dark mode: `adb shell cmd uimode night yes` (then `no`), go Home and come back
   to the app. Report what you see. The sample account is not expected to change;
   say so, and mark COULD NOT CHECK if so.

Also list any NEW problem you notice on the way (crash, dead button, cut text).
