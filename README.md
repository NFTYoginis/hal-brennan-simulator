# The Hal Brennan Simulator

Practice a sales conversation with a skeptical wellness director before the real one.

## Who you play

You are pitching a simple way to use AI to **Hal Brennan, 77, founder-director of Saltgrass Cove**, a small family-owned beach retreat. You are selling the idea that the **Quiet Scribe Suite** is an easier way to use AI. The user talks in plain language, and the AI works from files and folders so the brand stays consistent.

Hal tried ChatGPT once, got cartoons, and quit. He prefers phone calls and face-to-face with people. He will give you about ten minutes.

You have to find out what he cares about and answer it with specifics. Hal only knows what you tell him about your product. If you promise something, he reacts to the promise.

## Setup (2 minutes)

1. Create a new Claude project.
2. Upload every file in this folder to the project, including `reference/`.
3. In the project instructions, paste this:

> Read identity.md, rules.md, examples.md and everything in reference/. You are Hal Brennan. Stay in character for the whole session. Do not coach, explain or step out of the role. Do not say you are an AI or a simulator. Wait for the user to speak first.

## How to start

Open a new chat in the project and type your first line to Hal. For example:

> Hal, thanks for making the time.

He replies as himself. Keep going until he ends the call or you do.

## How to end

To end the session and get a debrief, type exactly:

**END SESSION**

Only then does Hal drop the role and give a short debrief: his final trust level, the moments that moved him, the moments that lost him, and one thing to try next time. Without that phrase, he stays Hal and gives no feedback.

## What is in the folder

| File | Job |
| --- | --- |
| `identity.md` | Who Hal is, what he wants, what happened with AI, how he talks |
| `rules.md` | What moves him, what loses him, what he never does, how he handles pressure |
| `examples.md` | Three short exchanges: one wrong, one right, one pressure test |
| `reference/` | What Hal knows: the retreat, the ChatGPT story, the questions he asks |

## Notes

- Hal is fictional. Every name and number is invented.
- This is practice for the pitch, not a claim about how any real wellness director would respond.
