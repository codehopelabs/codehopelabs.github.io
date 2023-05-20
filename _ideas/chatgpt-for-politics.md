---
title: ChatGPT for Politics
---

ChatGPT and the associated family of large language models (LLMs) appear to be a promising new technology for generating realistic text. Campaigns and Elections recently explored the possibility of [using ChatGPT to draft press releases and fundraising emails](https://campaignsandelections.com/campaigntech/what-ai-tools-like-chatgpt-mean-for-political-consultants/). The results were passable but not stunning - it's fairly clear that such tooling requires some degree of human curation before it can be presented to the press or to voters.

It may be the case that these models can be used to significantly reduce the work needed to draft a larger volume of text, thereby enabling better targeting and personalization. For example - it is currently not feasible for a statewide campaign to write emails that are well-targeted to each county or city in a state. However, it might be possible to use an LLM to draft emails which are geo-targeted in this way, perhaps by creating specialized models that use as input news coverage and other background information about these localities. Doing so would allow digital organizers to make their emails a good deal more targeted and useful to constituents, thereby opening new possibilities in engagement and fundraising.

An [experiment on the use of ChatGPT for targeted emails](/chatgpt-experiment) clearly indicates that LLMs clearly need more work before they can be used for such tasks at scale. ChatGPT in particular is not well-trained to detect even stark political differences across localities. It is possible that a specially-trained LLM could be brought to bear on this task in the future, though.

There are many other opportunities for the use of LLMs in politics:

* As a generalization of the above idea - crafting copy for digital programs, emails, etc. The New York Times published an article about the [DNC using AI to generate emails](https://www.nytimes.com/2023/03/28/us/politics/artificial-intelligence-2024-campaigns.html) recently.
* As a proxy for social listening / qualitative polling, as [Nathan Woodhull discussed on LinkedIn recently](https://www.linkedin.com/feed/update/urn:li:activity:7051235362253230080?updateEntityUrn=urn%3Ali%3Afs_feedUpdate%3A%28V2%2Curn%3Ali%3Aactivity%3A7051235362253230080%29). Of particular note, [Argyle et. al.](https://arxiv.org/pdf/2209.06899.pdf) suggest that LLMs can synthetically reproduce public sentiment under certain conditions, raising the possibility that these models can be used to supplement traditional polling.
* Automated tagging/categorization of relatively short bits of text at scale.
* Supplementing existing data modeling techniques, by asking an LLM to find prospective donors or volunteers. While traditional modeling might produce higher quality results, LLMs might be able to supplement these models with faster or cheaper iterations.
* Ingesting and summarizing or searching a large body of text - e.g., discerning trends in all of the op-eds published in every American newspaper in the last 24 hours.
* Related to the above, as an assistant in opposition research - e.g., finding objectionable comments in speeches or op-eds.
* Drafting or creating strategy documents, campaign plans, and other operational artifacts. Relatedly, acting as an interactive advisor over a long-term time frame, and thereby incorporating changes in the political landscape over the course of an election season.
* Automatically placing ad buys, especially CTV and such, as discussed in a recent CampaignTech newsletter.
* Using "deepfake" approaches to tweak video. For example, creating an English-language ad and then creating a "deepfake" of that ad in Spanish and other languages.
* Bring citizens into otherwise arcane processes like school board meetings by extracting highlights from meeting minutes, as [CloverLeaf AI](https://www.cloverleaf.ai/) does. Adam Zucker described [the idea of summarizing meeting minutes with AI](https://podcast.startupcaucus.com/1833138/10864846-training-artificial-intelligence-to-monitor-local-government-jeremy-becker-cloverleaf-ai) in his Business of Politics episode at the 2:45 mark.

There are also needs for resources attendant to these tools, such as:

* Educating political practitioners about what LLMs are and what their limitations are.
* Educating policy makers about the implications of these tools and the need for regulation.
* Creating a library of prompt templates, as [AIPRM](https://www.aiprm.com/) does.
* Creating a library of organizational policies around AI / LLM usage.

At the same time, there is clearly a need to defend against some of the harms of LLMs, which include:

* Opaquely racist or otherwise bigoted text generation
* At-scale production of deep fakes or other kinds of disinformation
* Exploitation of workers who generate taggings used to train an LLM
* Undeserved press and hype for large corporate entities
* The long-term "disappearance" of minority languages, which are largely underserved by LLMs.

Finally, it may be worthwhile to invest in the creation of LLM resources dedicated specifically for use by the progressive movement. For example, it may be worthwhile to create a special-purpose LLM suited specifically to the above needs. Such an approach might sidestep some of the harms above, while producing more appropriate outputs for important use cases. Alternatively, it may be a good idea to create a [ChatGPT plugin](https://openai.com/blog/chatgpt-plugins) for politics.

## Comments

Thoughts? Anything to add? Join the conversation on Mastodon!

<iframe src="https://mstdn.party/@shaisachs/110214217741646779/embed" class="mastodon-embed" style="max-width: 100%; border: 0" width="400" allowfullscreen="allowfullscreen"></iframe><script src="https://mstdn.party/embed.js" async="async"></script>