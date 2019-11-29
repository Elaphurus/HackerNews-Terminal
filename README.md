# HackerNews-Terminal

HackerNews (HN) is blocked in China.
However, it's strange for the following two things:

1. HN is for technology information, and not politically sensitive
2. proxy is not effcetive here (don't know why)

Fortunately, a little crawler is enough to get it back.

## Usage

```python
python3 hacker_news [numbers=10]
```

An example and its output:

```bash
./hacker_news.py 5
=> 1. Rooms can be as bright as the outdoors
(score: 215, id: 21660718, time: 2019-11-29 06:57:08)
https://www.benkuhn.net/lux

=> 2. Ask HN: What are you thankful for?
(score: 61, id: 21660118, time: 2019-11-29 04:55:06)
https://news.ycombinator.com/item?id=21660118

=> 3. Siberia: 18,000-year-old frozen 'dog' stumps scientists
(score: 178, id: 21660041, time: 2019-11-29 04:38:43)
https://www.bbc.com/news/world-europe-50586508

=> 4. Drive drunk twice in Quebec, get ignition breathalyzer for life
(score: 15, id: 21661249, time: 2019-11-29 09:18:32)
https://www.cbc.ca/news/canada/montreal/drunk-driving-twice-quebec-breathalyzer-for-life-1.5369145

=> 5. DeepPCB: Pure AI-Powered, Cloud-Native Printed Circuit Board Routing
(score: 30, id: 21660365, time: 2019-11-29 05:41:56)
https://deeppcb.ai/
```
