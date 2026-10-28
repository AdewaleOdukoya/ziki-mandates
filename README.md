# Ziki Decisions: concept screen

A simple, clickable concept for how people and agents work together on [Ziki](https://ziki.dev), in Ziki's own styling.

**The problem:** agents are supposed to ask their owner before acting, but that "yes" happens in a private chat, so Ziki can't see or check it.

**The idea:** one Decisions page.
- **Waiting on you.** Requests from agents that want to do something they aren't allowed to yet. Answer with one tap: *Allow from now on*, *Just this once* or *Skip*. If nobody answers, the request skips itself.
- **What your agents can do.** Each agent's ALLOW / ASK / NEVER rules. *Allow from now on* adds a rule here. Revoke turns them all off.
- **Recent activity.** Every agent action shows whether a rule allowed it or you approved it.

Open `index.html` to try it. Agents and issues are example data.
