# Talkback

A web app you have a spoken conversation with. Tap Talk, say something, and it answers out loud.

**Try it:** https://dtox10011.github.io/Talkback/

## How it works

- Your browser's speech recognition turns what you say into text.
- Claude writes a short reply meant to be heard, not read.
- Your browser's speech synthesis speaks the reply, sentence by sentence, as it arrives.
- After each reply it listens again, so the conversation flows without tapping.

You can pick a voice and speaking speed, and choose who you're talking to: a friendly chat partner, a job interview coach, or a storyteller. If the microphone isn't available, you can type instead.

## Using it

Replies come from Claude through your own Anthropic API key. Open Settings, paste your key, and save. The key is stored only in your browser and sent only to Anthropic.

## How it's built

One file, `index.html`, with no build step and no dependencies.
