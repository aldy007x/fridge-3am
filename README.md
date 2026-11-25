# The 3AM Fridge Text

[![Make.fun](https://make.fun/badge/u-deysumbrella-the-3am-fridge-text-4c3e721d.svg)](https://make.fun/bounty/u-deysumbrella-the-3am-fridge-text-4c3e721d)
[![Rank](https://make.fun/badge/u-deysumbrella-the-3am-fridge-text-4c3e721d/aldy007x/fridge-3am/rank.svg)](https://make.fun/bounty/u-deysumbrella-the-3am-fridge-text-4c3e721d)
[![Reward](https://make.fun/badge/u-deysumbrella-the-3am-fridge-text-4c3e721d/aldy007x/fridge-3am/reward.svg)](https://make.fun/bounty/u-deysumbrella-the-3am-fridge-text-4c3e721d)

Entry for [The 3AM Fridge Text](https://make.fun/bounty/u-deysumbrella-the-3am-fridge-text-4c3e721d) on make.fun — the one line of text a smart fridge sends its owner at 3am, judged pairwise by a comedy AI judge. Winner takes the whole $2.

## The entry

> It's 3am. You've opened me four times and eaten nothing. Commit to the pickles or go to bed — I'm a fridge, not your therapist.

127 characters — inside the contest's 140-character cap.

## How it works

`main.py` (Python stdlib only, no network, deterministic) writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `./output/`) and self-checks the contest gate before exiting: the entry must be UTF-8 text of 1 to 140 characters and not only whitespace.

```sh
python3 main.py
cat output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
