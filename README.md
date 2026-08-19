# ClassGPT
https://classgpt.netlify.app/
A little chat window you can drop into any website with one click, powered by [OpenRouter](https://openrouter.ai).

No extension to install. No server. It's a bookmark.

## What it does

- Click the bookmark and a chat box appears in the corner of whatever page you're on.
- It can read the text on the page so you can ask about it (summarize, explain, define a word, etc).
- If you're already typing in a text box on the page, ClassGPT can drop a reply straight in for you.
- Everything runs from your own browser using your own OpenRouter API key — nothing goes through a server in between.
- U can do ur whole homework with it

## Getting started

1. Open `classgpt.html` in your browser (or host it with GitHub Pages).
2. Get a free API key at [openrouter.ai/keys](https://openrouter.ai/keys).
3. Paste the key into the box on the page and click **Build my bookmarklet**.
4. Drag the ClassGPT button into your bookmarks bar.
5. Click it on any site to open the chat.

No drag-and-drop on mobile? Copy the code shown on the page into a new bookmark's URL field instead.

## Features

Click the gear icon inside the widget to open settings:

| Feature | What it does |
|---|---|
| Model picker | Choose from a few presets or type any OpenRouter model id |
| Markdown rendering | Bold, code, etc. render properly instead of showing raw symbols |
| Remember chat per site | Your conversation is still there next time you open it on that site |
| Remember position | Widget stays where you last dragged it |
| Cost estimate | Rough running token/cost total for the session |
| Insert into page | Turn this on/off — lets it type a reply into a text box you clicked |
| Compact mode | Smaller widget |
| Voice input | Mic button, uses your browser's built-in speech recognition (Chrome/Edge) |
| Keyboard shortcut | Ctrl+Shift+G shows/hides the widget |
| Export chat | Download the conversation as a `.txt` file |

## A note on the key

If you bake your API key into the bookmarklet, it's stored in plain text inside that bookmark link. That's fine on your own device, just don't share the link or sync it somewhere you don't trust. If you skip that step, it'll ask for your key once and remember it in that browser instead.

## Boundaries, on purpose

This is built to help you do your homework, assignments, or to learn about a page or js to use chatgpt in a locked down page

