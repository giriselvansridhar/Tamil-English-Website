# Amma English — Story mode

Amma learns English through small real-life stories: a shop, a phone call, an auto, the doctor, a new neighbour, and asking the way.

How each story works:
1. The situation is explained in Tamil.
2. The other person speaks in English, with the Tamil meaning shown.
3. Amma's turn: she sees what to say in Tamil, then the English line, then how to pronounce it in Tamil letters. She listens, says it out loud, and taps "சொன்னேன்". She does this 5 times.
4. At the end she acts out the whole conversation once more.

## Deploy on Vercel (free)
1. Push this folder to GitHub.
2. On vercel.com, go to Add New → Project, import the repo, and press Deploy. No settings are needed.
3. On Amma's phone, open the link in Chrome, then tap ⋮ → Add to Home screen.

## Change things (top of the <script> in index.html)
- `MOM_NAME` / `MOM_NAME_TA`: her name in English and in Tamil.
- `PRACTICE`: how many times she repeats each line (default 5).
- `GAP`: seconds before she can tap again, so she actually speaks (default 1.6).
- `STORIES`: add your own stories. Use `them` for lines the other person says and `you` for Amma's lines. Put the pronunciation in Tamil letters in `say`.

Tamil voice: all Tamil text is read aloud. The app uses the phone's Tamil voice if one is installed (Android: Settings → Text-to-speech → Google → install Tamil); otherwise it uses Google's free online Tamil voice, which needs internet.
