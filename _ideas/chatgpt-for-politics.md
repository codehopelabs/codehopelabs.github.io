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
* Drafting or creating strategy documents, campaign plans, and other operational artifacts.
* Automatically placing ad buys, especially CTV and such, as discussed in a recent CampaignTech newsletter.

At the same time, there is clearly a need to defend against some of the harms of LLMs, which include:

* Opaquely racist or otherwise bigoted text generation
* At-scale production of deep fakes or other kinds of disinformation
* Exploitation of workers who generate taggings used to train an LLM
* Undeserved press and hype for large corporate entities