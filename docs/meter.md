# How we calculate your spending

OpenAI charges you per [token](https://platform.openai.com/docs/introduction/tokens) (`100` tokens ~= `75` words). We count those tokens and multiple them by the price stated on the [OpenAI Pricing page](https://openai.com/pricing). `100,000` words cost around `$1`.
- **For details on your spending** go to [OpenAI Usage](https://platform.openai.com/account/billing/limits) page [^1].
- **For more control on your spending** set limits at [OpenAI Usage Limits](https://platform.openai.com/account/billing/limits) page.

For each question asked, the entire chat up until now + the new question + the answer are counted up by OpenAI as tokens.
- **For less spending** keep your chats small.

The "Prompt completion" feature also uses OpenAI API and increases your token usage.
- **For less spending** disable it.

[^1]: If you consume tokens outside of IntelliBar, the usage on OpenAI's page won't match what's shown in the app. For example, the OpenAI Playground consumes tokens.
