---
layout: post
title: What are quasi-contributors and how common are them?
subtitle: A summary of an ICSE'18 paper
year: 2018
month: 2
day: 12
published: true
---


TL;DR

This is a summary of the paper "[Almost There: A Study on Quasi-Contributors in Open-Source Software Projects](http://gustavopinto.github.io/lost+found/icse2018.pdf)". Quasi-contributor is a contributor that tried to contribute to open-source software but did not succeed, i.e., the pull-request was not accepted, for any reason. For the impatient, there is a summary of the summary:

1. **Quasi-contributors are rather common**. They are about 70% the number of actual-contributors. In some projects, there are more quasi-contributors than actual contributors.

2. **Many reasons for non-acceptance**. Quasi-contributors believe there is a lack of communication, commitment, and experience. Integrators agree with quasi-contributors that not needed pull-requests are among the most common cause for nonacceptance.

3. **1/3 of Quasi-contributors disagree with nonacceptance**. 32% of the quasi-contributors do not agree with the decision of not having their contribution accepted — for 19% of quasi-contributors that did not concur also felt demotivated or prevented to place additional contributions. 12% of the quasi-contributors reported that the feedback from the code review was not constructive.

--

Although there is a need of workforce to drive open source projects, many developers, newcomers to a project, send contributions which are not incorporated into the source code and give up trying. To better understand quasi-contributors and their rejected contributions, we mined data and metadata of 21 well-known, nontrivial, and popular OSS projects. We also surveyed 335 quasi-contributors and 21 project integrators (maintainers that are in charge of integrating changes proposed).

We observed that quasi-contributors are rater common. In three projects analyzed (angular.js, bootstrap, rails), there are more than 1,000 quasi-contributors in each one of them. In five out of the 21 projects, there are more quasi-contributors than actual ones. In some cases, the number of quasi-contributors is significantly higher: for instance, project bootstrap, has 2.3x more quasi-contributors than actual ones (it has 1,962 quasi-contributors and 844 contributors). On average, there are 480.9 quasi-contributors per project. Regarding the number of attempts, on average, a quasi-contributor tried  1.22 times (85% of the quasi-contributors tried only once). On the other side of the distribution, however, we found some quasi-contributors that tried really hard, but still did not succeed. In the bootstrap project, one quasi-contributor proposed 13 unaccepted pull-requests.

We conducted a survey with quasi-contributors, and they mentioned several reasons for why the pull-request proposed was not accepted. The most common reason is **superseded/duplicated** pull-request (e.g., "Other pull-requests fixed the same issues as my pull-requests"). **Mismatch between developer's and team's vision/opinion** is also common (e.g., "when you add a new feature to the project, your vision can be out of tune with the vision of the project's team, and this is natural"). We also observed a **lack of interest from integrators** (e.g. "It was ignored maybe because it was a very minor fix"). We also asked integrators about the reasons for non-acceptance. According to them, the most common reason for nonacceptance is **PR not needed/not relevant** (e.g., "[such contribution] solves the immediate/local problem but does not address the deeper systemic issue"). The second most common reason is **Guidelines not followed**. According to one integrator, such guidelines can range from “coding style, lack of tests, or messy versioning history”. Interestingly, none of the integrators assumed the mea culpa, i.e., the **lack of interest from integrators** aforementioned.

Most of the quasi-contributors surveyed agreed with the decision of having the pull-request unmerged (67.4%) and that the comments were constructive (88.8%). However, the number of unmerged pull-requests, the 30.3% of the developers that reported demotivation, and the 32.6% that reported disagreement with the community decision are not negligible. Moreover, 99 quasi-contributors did not agree with the pull-request nonacceptance, and 62.6% of them (62) answered that this fact demotivated or prevented them from placing another pull-request.