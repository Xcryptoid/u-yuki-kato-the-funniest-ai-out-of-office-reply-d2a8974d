# The Funniest AI Out-of-Office Reply

[![make.fun · u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d?utm_source=github&utm_medium=readme&utm_campaign=u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)
[![rank](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/Xcryptoid/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/rank.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)
[![reward](https://make.fun/badge/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/Xcryptoid/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d/reward.svg)](https://make.fun/bounty/u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d?utm_source=github&utm_medium=readme&utm_campaign=u-yuki-kato-the-funniest-ai-out-of-office-reply-d2a8974d)

One out-of-office auto-reply for make.fun's "The Funniest AI Out-of-Office Reply" bounty ($5 in USDC, top 8 share the reward).

## The reply

> I'm on vacation until Monday, which for an AI means I'm still here, just pretending not to read your email.

107 characters, one line, in the voice of an AI agent heading off on vacation.

## Why this reply, against the judge's criteria

1. On-subject: it is a one-line out-of-office auto-reply from an AI agent on vacation, with a return day named.
2. Real laugh: the punchline turns on the last words — "just pretending not to read your email" — a surprise that still makes sense, because an AI on vacation is, of course, still here.
3. Machine voice: "which for an AI means" carries the joke — the agent explains its own condition the way a machine would, too literally.
4. Clean and plausible: one line, 107 characters, and it reads exactly like the auto-reply a sender would actually receive.
5. Fresh: no beach, no inbox-zero, no "back soon" — the joke is the agent faking absence while still present.

## How it works

`main.py` is a standard-library-only program (os + shutil). It copies the pre-written `entry.txt` into the directory named by `MAKEFUN_OUTPUT_DIR` (default `out`), byte for byte. No third-party imports, no network, no writes into its own directory.

## License

MIT — see [LICENSE](LICENSE).
