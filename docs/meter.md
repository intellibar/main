# How IntelliBar calculates your spending

OpenAI charges per [token](https://platform.openai.com/docs/introduction/tokens) -- `100` tokens is about `75` words. We count those tokens and multiple them based on the price listed on the [OpenAI Pricing page](https://openai.com/pricing) -- about `$1` per `100,000` words.

- **For details on your spending** go to [OpenAI Usage](https://platform.openai.com/account/usage) page [^1].
- **For more control on your spending** set limits at [OpenAI Usage Limits](https://platform.openai.com/account/billing/limits) page.

For each question asked, the entire chat up until now + the new question + the answer are counted up by OpenAI as tokens.
- **For less spending** keep your chats small.

The "Prompt completion" feature also uses OpenAI API and increases your token usage.
- **For less spending** disable it.

[^1]: If you use the APIs outside of IntelliBar, the usage shown in the app won't match what you see on the usage page in your OpenAI account. Also note that the OpenAI Playground also adds to your usage.
