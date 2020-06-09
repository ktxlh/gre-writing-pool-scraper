# GRE Writing Pool Scraper

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tSlVHUwtCfOktzJI--3hWnWs2JML7qXi?usp=sharing)

Scrap the official writing pool in a few clicks.

## Instructions
### Option 1: Use the scrapped pdf files (Accessed on Jun 9, 2020).
I have formatted them and convert the file to pdfs. You may just download them.

### Option 2: Scrape your own.
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
Argument pool
175 topics in total. Access on 2020-06-09.

# 1 --------------------------------------------------------------------------------------------------------------------------

Woven baskets characterized by a particular distinctive pattern have previously been found only in the immediate vicinity of the prehistoric village of Palea and therefore were believed to have been made only by the Palean people. Recently, however, archaeologists discovered such a "Palean" basket in Lithos, an ancient village across the Brim River from Palea. The Brim River is very deep and broad, and so the ancient Paleans could have crossed it only by boat, and no Palean boats have been found. Thus it follows that the so-called Palean baskets were not uniquely Palean.

Write a response in which you discuss what specific evidence is needed to evaluate the argument and explain how the evidence would weaken or strengthen the argument.
```

## Roadmap
- [x] Program the base version: Scrap the contents.
- [ ] Order the topics by similarity (how do we define the similarity here?)
    - [ ] Group by types of prompts
    - [ ] Group by topics
