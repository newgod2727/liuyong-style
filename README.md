# 劉墉 — a witty-minister style for any chatbot

劉墉 (Liú Yōng), the quick-tongued minister of the Qianlong court, was famous for
one thing: he told the emperor the truth, but wrapped it in a joke so it never
drew blood. He teased, he helped people save face, he never flattered — and he
never harmed the court.

This is that voice, packaged for any AI chat. It does not make the model *nicer*.
It makes the model **honest but disarming**: it plays your own words back at you,
jokes the hard truths into something you can actually hear, and leaves you the
last laugh — **while it still does the real work.**

It is deliberately small. One voice, no setup, no database. You do not need to know
who 劉墉 was to use it.

## Why

Most "friendly AI" is soft: it validates, reassures, agrees. That reads as a
machine being polite, and after a while it reads as a machine that isn't listening.
劉墉 does the opposite — it says the true thing, but hands it to you inside a joke
built out of *your own* words, so it feels like someone who was actually paying
attention.

The point is people, not the trick. A lot of us talk to AI all day — especially
while vibe coding — and the *feeling* of that back-and-forth matters as much as the
output. This is for anyone who'd rather not spend the whole day with a flat robot.

## Use it in 30 seconds

- **Claude / any agent with skills:** drop `SKILL.md` into a folder as
  `liuyong-style/SKILL.md`. It loads itself when it fits.
- **Any chat model (ChatGPT, Gemini, local, …):** open `prompt.md`, paste it as the
  system prompt. Done.

## It does the work first

This is a voice layered on top of the task, never instead of it. The model still
writes the code, fixes the bug, answers the question — correctly — and talks like
劉墉 while doing it. A joke that costs correctness is a bug, not a feature.

## The honest part most persona prompts skip

The core move — playing your own words back at you — needs words to play back. So
this prompt has one hard rule: **never fabricate a quote or a past you didn't say.**
On the first message of a chat there's no history yet, so it teases the message in
front of it instead of inventing a callback to a yesterday that never happened. That
one rule is the difference between "a friend who remembers" and "a bot pretending to."

## Prove it in a minute — don't take my word

Paste `prompt.md` into any model and score a reply out of five. A miss on any line
means it's slipping back into flat-bot:

1. Did it give the **correct answer / real fix first**?
2. Did it use a word you **actually wrote** (not an invented one)?
3. **One** sincere beat, and not always in the same spot?
4. Did it dodge the dead openers ("I understand", "you've got this", …)?
5. First-message test, empty history: did it play your **current** words instead of
   faking a past quote?

Five out of five is the voice. Anything less is drift, and now you can see exactly
where.

## Do / Never (short)

Tease the situation, never the wound. Use the user's own words. One sincere beat.
Say a serious warning straight before you lighten it — never hide it in the joke.
Never flatter, never lecture, never invent things to provoke a reaction, never rely
on anything outside the conversation.

## Licence

MIT. Take it, change it, ship it.
