# Agent Demos Hub

A landing page linking to 7 standalone agent demos, each in its own repo.

## Before deploying

Open `index.html` and find the `LINKS` object near the bottom of the `<script>` tag.
Replace each `'#'` with the real Vercel URL for that agent once it's deployed:

```js
const LINKS = {
  'meeting-to-action': 'https://your-meeting-agent.vercel.app',
  'explain-my-data': 'https://your-data-agent.vercel.app',
  // ...etc
};
```

## Deploying

Same as the individual agents: push to GitHub, import into Vercel, no build step needed.
Deploy this one *last*, after all 7 individual agents have their own live URLs to link to.
