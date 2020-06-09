# GRE Writing Pool Scraper

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ktxlh/gre-writing-pool-scraper/blob/master/GRE_writing_pool_generator.ipynb)

Scrap the official analytical writing pool in a few clicks.

## Instructions
### Option 1: Use the scrapped pdf files accessed on June 9, 2020
I have formatted the generated files and convert them to pdfs. You may just download them.

### Option 2: Scrape the latest pools on your own
If you need more customization, you may create your own version.
1. Click the `Open in Colab` badge
2. Follow the steps in the notebook. The steps are repeated here:
    1. (Optional) Adjust the settings for customization
    2. Run every cell
    3. Download the generated text files


## Example
The official websites are [issue](https://www.ets.org/gre/revised_general/prepare/analytical_writing/issue/pool) and [argument](https://www.ets.org/gre/revised_general/prepare/analytical_writing/argument/pool). The screenshot of the issue one is:
![](https://i.imgur.com/iPMlEFX.png)

This tool generates two text files, one for *issue* and the other for *argument*, containing topics in the following format: (only the first one is shown)
```
Issue pool
149 topics in total. Accessed on 2020-06-09.

# 1 --------------------------------------------------------------------------------------------------------------------------

To understand the most important characteristics of a society, one must study its major cities.

Write a response in which you discuss the extent to which you agree or disagree with the statement and explain your reasoning for the position you take. In developing and supporting your position, you should consider ways in which the statement might or might not hold true and explain how these considerations shape your position.
```

## Roadmap
- [x] Program the base version: Scrap the contents.
- [ ] Order the topics by similarity (how do we define the similarity here?)
    - [ ] Group by types of prompts
    - [ ] Group by topics
