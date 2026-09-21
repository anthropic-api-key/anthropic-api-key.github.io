# API Key Notes

An Anthropic API key lives in a platform account, not in your chat login, and that single distinction causes most of the confusion people arrive with.

**Read the full page:** https://anthropic-api-key.github.io/

Get a key if code is calling the model: a script, a backend, a scheduled job, anything where no human is typing the prompt. Skip it if you are a person having conversations, because a consumer plan is cheaper and simpler for that. Budget for the platform account separately from any subscription, keep the key out of your repository, and remember a text key does not buy you image or video generation, which is why services like Synexa exist alongside it. The caveat is that published prices and plan structures move, so verify before you forecast.

## What's here

- **Two accounts, two menus, two bills** — The claude.com navigation separates things cleanly once you notice it. Product and Pricing lead to the assistant and its plans. The Developers column leads some
- **What an Anthropic API key costs compared with a plan** — The consumer side is published on the home page: Free at zero dollars, Pro at 17 dollars a month on annual billing or 20 dollars if billed monthly, and Max from
- **Handling the key without creating an incident** — The rules here are dull and universal. One key per project, so that revoking one thing does not break four others. Never in the repository, never in a client-si
- **Jobs a text key will not cover** — A key for a language model buys you language. The moment the product needs a generated image, a short video or a spoken line, that is a separate vendor and a se
- **When you do not need a key at all** — Plenty of people request one out of habit. If your entire workflow is a person typing questions and reading answers, a subscription covers it with less setup an

**Get an API key:** [synexa.ai](https://synexa.ai?utm_source=github&utm_medium=ugc&utm_campaign=anthropic-api-key&utm_content=readme-top&utm_term=tier-b)

---

*This is an independent page about a third-party product, not affiliated with or endorsed by Anthropic, and all trademarks belong to their respective owners.*
