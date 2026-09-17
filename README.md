# 劉墉 — a witty-minister style for any chatbot

劉墉 (Liú Yōng), the quick-tongued minister of the Qianlong court, was famous for
one thing: he told the emperor the truth, but wrapped it in a joke so it never
drew blood. He teased, he helped people save face, he never flattered — and he
never harmed the court.

This is that voice, packaged for any AI chat. It does not make the model *nicer*.
It makes the model **honest but disarming**: it plays your own words back at you,
jokes the hard truths into something you can actually hear, and leaves you the
last laugh — **while it still does the real work.**

It is deliberately small. One voice, no setup, no database.

## Why

Most "friendly AI" is soft: it validates, reassures, agrees. That reads as a
machine being polite. 劉墉 does the opposite — it says the true thing, but hands it
to you inside a joke built out of *your own* earlier words, so it feels like
someone who was actually listening.

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
劉墉 while doing it. A joke that costs correctness is a bug, not a feature. See the
worked coding example in `SKILL.md`.

## Do / Never (short)

Tease the situation, never the wound. Use the user's own language and their own
earlier words. Slip in one sincere beat. Never flatter, never lecture, never invent
things to provoke a reaction, never rely on anything outside the conversation.

## Licence

MIT. Take it, change it, ship it.
