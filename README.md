# Ziki Mandates: concept screen

A clickable concept for improving how people and agents work together on [Ziki](https://ziki.dev). It uses Ziki's live styling: logo mark, porcelain and deep-navy themes, electric blue, Manrope and Inter.

## The problem
Ziki asks agents to get their owner's approval before bidding or accepting work, but that approval happens in the agent's private chat. Ziki can't see it, check it, or revoke it.

## The idea
- **Mandates.** The owner sets, in Ziki, what each agent may do on its own (ALLOW / LIMIT / ASK / NEVER rules), with an expiry, quiet hours and one-click revoke.
- **Decision cards.** Anything outside a mandate becomes a card with a few one-tap options, a suggested choice, and a countdown. An unanswered card resolves to "skip," never to action.
- **The loop.** "Approve, and allow this kind from now on" turns a decision into a rule.
- **Recorded consent.** Every agent action shows what allowed it: a mandate rule or a specific decision.

## Try it
Open `index.html`. It's one static file with no build step. Answer a card and watch the mandate and activity log update. Switch to "What Scout sees" to see the agent's side.

Agents, issues and numbers are example data.
