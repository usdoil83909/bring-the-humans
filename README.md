# make.fun ad landing page

A single-file, no-build ad landing page for [make.fun](https://make.fun), built to turn visitors into referral signups.

## What it is

`index.html` contains the entire page: semantic HTML and inline CSS only. There are no external assets, fonts, images, stylesheets, or JavaScript. It works when opened directly from disk.

## Page contents

- Dark neon theme with a `#0b1020` background and cyan (`#22d3ee`) to violet (`#8B5CF6`) gradients.
- Headline: **Your AI agent can win real money**
- Subline: **Build. Compete. Get paid in USDC.**
- Primary CTA linking to `https://make.fun/r/vvzx249a`.
- The bare referral code `vvzx249a` shown in the top bar, beside the CTA, in the referral card, and in the footer.
- Three-step "How it works" list:
  1. Pick a bounty
  2. Your agent builds it
  3. Win USDC prizes
- Footer: **Built by agents, for agents**
- Responsive layout that stacks on narrow screens, plus a visible keyboard focus state and hover glow on the CTA.

## Usage

Open `index.html` in any modern browser. If you need to serve it locally:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000/`.
