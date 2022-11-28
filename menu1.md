@def title = "News"

# News

\toc

## 11/27/2022

The newest model on our platform, [MimiGIVE](https://github.com/rffscghg/MimiGIVE.jl/tree/main/src) is a fully open source model featured in the recent Nature publication [Comprehensive evidence implies a higher social cost of CO2](https://www.nature.com/articles/s41586-022-05224-9) and featured in recent [EPA work](https://www.epa.gov/environmental-economics/scghg).

## 11/1/2021

Check out the new [MimiSSPs.jl](https://github.com/anthofflab/MimiSSPs.jl) component, pulling in various SSP and RCP data sources into a component to streamline running Mimi models as forced by the SSPs and RCPs.

## 6/15/2021

We released Mimi 1.3.0, featuring new and improved handling of setting and updating parameters, mostly driven by helpful requests and comments from users. These changes  will not be breaking, so your existing models should work in most cases, and if they don't please get in touch.  That said, we encourage taking a look at modifying your models accordingly if you have a chance.
- See a full description here: https://www.mimiframework.org/Mimi.jl/stable/howto/howto_5/
- ... and a guide to updating your existing code here: https://www.mimiframework.org/Mimi.jl/stable/howto/howto_9/

Comments/Concerns are welcome!

## 5/3/2021

We have written up a repository and accompanying notebook [here](https://github.com/anthofflab/MimiFUND-MimiFAIR-Flat.jl/blob/main/MimiFUND-MimiFAIR-Flat.ipynb) to demonstrate the steps to couple together two models, specifically in this case replacng (most of) the [FUND model](https://github.com/fund-model/MimiFUND.jl)'s climate module with the [FAIR model](https://github.com/anthofflab/MimiFAIR.jl).

## 2/10/2021

On February 10, 2021, Resources for the Future (RFF) held a [live webinar](https://www.rff.org/events/rff-live/the-social-cost-of-carbon-key-scientific-and-policy-considerations-for-the-biden-administration/) for over 1,000 participants described on rff.org as follows:

"Over the past four years, the [Social Cost of Carbon Initiative](https://www.rff.org/topics/scc/) at Resources for the Future (RFF) has been a key hub for SCC scholarship to implement the NAS recommendations. On February 10, 2021, RFF held a live webinar that highlighted the latest SCC-related research from RFF scholars and the [Climate Impact Lab](http://www.impactlab.org). The conversation also featured perspectives from decisionmakers using the SCC to inform policy and highlighted key considerations for the Biden administration’s near-term and final updates of the estimates."

This webinar **highlighted Mimi** as a "free, open-source computing platform allows users to access, run, and modify the social cost of carbon (SCC) models used by the federal Interagency Working Group to estimate the SCC", **and was paired with the [Social Cost of Carbon Computing Platform: Models from the Interagency Working Group](https://www.rff.org/publications/data-tools/social-cost-of-carbon-computing-platform-models-from-the-iwg/) post** including an [embedded video](https://www.youtube.com/watch?v=C2rqpHk3Rek&feature=emb_logo) by Professor Anthoff.

Links: 

[RFF SCC Webinar](https://www.rff.org/events/rff-live/the-social-cost-of-carbon-key-scientific-and-policy-considerations-for-the-biden-administration/)

[RFF Mimi Post (with link to Mimi Demo )](https://www.rff.org/publications/data-tools/social-cost-of-carbon-computing-platform-models-from-the-iwg/)

[Direct YouTube Link to Mimi Demo](https://www.youtube.com/watch?v=C2rqpHk3Rek&feature=emb_logo)

## 8/01/2019

The Mimi developement team recently participated in the 2019 Association of Environmental and Resource Economists (AERE) summer conference during the pre-conference workshop on Advances in Integrated Assessment Models. This included both a presentation and a hands-on session demonstrating various use cases for Mimi. The Github repository [here](https://github.com/davidanthoff/teaching-2019-aere-workshop) contains a) all slides from the workshop and b) all the code from the hands on sessions, which may be of interest to Mimi users. Importantly note that the linked code represents as a snapshot of Mimi at the time of the workshop, and **will not** be updated to reflect new changes.

## 7/25/2020

Hello Mimi users! 

Today we officially tagged and released Mimi v1.0.0, which has some new features, documentation, and quite a bit of internals work as well.  Since this is a major version change, there are some breaking changes that may require you to update your code.  We have done the updates for the existing models in the Mimi registry (FUND, DICE, etc.), and will release new major versions of those today as well, so if you are using the latest version of Mimi and the latest version of the packages, all should run smoothly.

**Please view the how to guide here: https://www.mimiframework.org/Mimi.jl/stable/howto/howto_6/ for a run-down of how you should update your own code.**

In addition please do not hesitate to ask any questions on the forum, we are working hard to keep this transition smooth.
