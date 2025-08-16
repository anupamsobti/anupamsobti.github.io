---
layout: page
title: lab philosophy
description:
permalink: /lab-philosophy/
nav: false
---

Any organization, big or small, is characterised by its culture. I want to take the time to articulate and explain how to go about certain things in the lab. These are guidelines. So, feel free to break them but I've personally found the ideas useful. Hence, I'm trying to communicate this in a more tangible form.
The geovisionaries lab is an impact lab. While we do some things that are closer to **pure research**, we also actively try to **productize it** so that we can pitch to users. Our research, therefore, is informed by needs of the people whom we serve. We do not shy away from creating that API endpoint from our latest algorithm or implementing it with sagemaker. We also actively create artifacts which can demonstrate the capabilities we develop to the right audience.

## Understanding what we do

### Who are the users?

The lab empowers users who make decisions in two large ecosystems - cities and farms. Due to the highly complex ecosystems in which cities and farms develop with multiple stakeholders like administrators, politicians, the public; decision making often happens through different types of forces, be it political pressures, people pleasing, think tanks, consultants or corruption. Amongst stakeholders here, there seems to be lack of long term accountability and ownership towards problem solving. Therefore, our lab is trying to bring scientific rigor along with software design interventions such that the optimal choices become the obvious choices.

### Operational models

In developing tools and services for various stakeholders, there could often be the need to have a partner who provides long term service for successful integration into the practice, e.g., troubleshoot issues, provide trainings on softwares, include new feature requests, etc.. Therefore, we would prefer paid contracts where the softwares we provide are available as services. This would be through a company, the current placeholder being www.theurbaneye.in . However, we are open to build open source artifacts if the former option is not available or stakeholders aren't open to commercialization of the tools. These are not personal but societal problems and open sourcing them also has the possibility of a snowball effect.

### Co-building

The primary reason for the openness towards use of the tools is because we ourselves have limited understanding of how things work on the ground and what are the nuances that go into the decision making at various levels. Therefore, we need to engage deeply with partners who have seen things on the ground and would be able to inform our solutions. In such a scenario, the partners need to be able to trust that they are not being exploited for commercial benefit only.

## How we do things: Research

### What kind of research do we do?

Our toolbox includes state of the art machine learning and deep learning tools that can provide generalized insights at scale. We also love modeling systems wherever possible. Therefore, we incorporate systemic models to determine system behavior including integration of process-based models wherever processes follow certain rules, e.g., crop growth models or physics of micro-climate.

A major challenge in building scalable machine learning pipelines is the availability of data. Traditional companies collect data at scale by providing users value in other forms, e.g., facebook collects personal information by allowing you to share it easily with your friends, amazon collects product preferences by allowing you to easily purchase stuff. There is a dataset that combines all cities and farms of the world and that happens to be geospatial data. Various types of data that our satellites collect - images, weather data, active thermal sensing, radar, etc. provides a big playground in terms of extracting insights. Before you ask for labels, let me clarify, that one of the major areas of interest in the lab is self-supervised learning on these modalities to learn nuances of the data. As for labels, we hope to provide value to our users in some form and collecting labels through this process, albeit at a smaller scale, e.g., a city. This is where productization comes in. I'll write about this later.

### Providing updates

Updates ideally follow the markov assumption. When you provide research updates, please make them such that no prior context is required to understand the update. Include a slide or two on the overall goals, what we've tried so far, where we fall short and what intuition we are exploring.

### Breaking walls

Specially with research, it often happens that you've been working on something for 5 months and it feels like you're only making incremental progress or are stuck because there are too many competing methods or complexities. This is where the magic happens. Don't stop. Keep pushing here. You now are getting closer to making your dent in research but your mind is processing the additional information and insight that it has gained so far. This is the time to be proactive in designing new experiments and reading new papers that allow you to expand further.

### Taking agency

Let me take small examples of agency that I'd like students to develop:

- Found a new paper with an interesting dataset -> download and start playing with it
- Didn't understand something on a paper or didn't find code the authors claim they've published -> email them
- Found some papers from a research group where you'd like to work -> reach out for an internship

and more.. Essentially, don't wait for someone to validate your ideas unless you're skeptical if you should invest the time. Then, always check.

### Meetings with mentor

So you either have a PhD student mentor or a professor mentor or a couple of professors as mentors. Set weekly meetings to start with. However, there will obviously be times when they are unavailable. Feel free to ask for clarification meetings in this phase as well. Highlight if you are blocked or don't understand how to proceed and clarify that as soon as possible. It is the mentee's responsibility to get the mentor's time. It's also ok to be slightly irritating here provided you've done your homework.
Don't set meetings to "show" that you're working. If you're in the group, I trust you to do your work. There will also be times when you want to read papers for a week and don't want to run all those experiments. Make sure not to procrastinate. Keep a stack of activities with you in case you get bored of one activity. Document what you're doing so that you understand how you've been spending your time.

### Writing papers

When you write papers, you not only clarify your experiments and claims but also your thinking. At this point, I feel this should be completely done manually without using any AI tools.

- **Iterate**: Your first draft is a reflection of things on your mind. They may or may not be relevant to the papers. Hence, it's common for final drafts to retain <30% of the initial draft.
- **Provide value**: There should be value in reading your paper. So you ran some experiments and got some numbers but what did you learn? Could you explain with examples? Simplify your takeaways.
- **Step back**: It's easy to get lost in overleaf latex commands and figures and not looking at a bigger picture. Take a printout/pdf and annotate with hand (or stylus). You'll find that you observe flow mistakes in your writing and see missing gaps to understand the bigger picture. Include branches with the leaves.

### Don't lose heart

Research, even though highly techincal, can often be emotional. Papers get rejected (even thrice), code gets thrown away, writing gets criticized, you discover dead-ends after working on something for 6 months. All this is heart shattering. Even applying for positions in research is hard and highly selective. It therefore helps to have a mindset of emotional detachment towards work. "Karm kiye ja phal ki chinta na kar". Good outcomes will follow good work. Even when you feel like you haven't learnt anything tangible, you learn how to deal with uncertainty, you learn how to make sense of abstract thoughts, you learn how to talk to people, etc. It's all part of the process.

## How we do things: Products

### User-centricity

On building products, I love the YCombinator motto, "Make something people want". Remember, it's not something optimal or something beautiful, it's something people, a person, who already probably has a job within the ecosystem, wants to make their job easier or more meaningful. Products don't sell themselves. We often [need to talk to users](https://www.youtube.com/watch?v=z1iF1c8w5Lg&ab_channel=YCombinator) to understand their needs and read between the lines to understand what kind of a product would be feasible and integrable in their workflows.

### Product-Research loop

The product, to start with, doesn't have to be aligned with any research project although it is better if it is. However, in this broad area of cities and farms, it should potentially have a data collection loop. Since we are collecting data from our users when they type things or click things, we should make use of it to make either product or research better. It is useful to think of this once you have an MVP that your user likes.

## How we work

### Flexibility in outcomes

A thriving culture lets people experience growth in the directions that they value. I understand that you may not subscribe to the entire, "let's change our cities and farms" agenda and that's fine. Whether you just want to gain experience in machine learning or gain experience in building solutions that users could use through UI/UX contributions or production pipelines, you can choose a path. Good machine learning attempts will take about an year of effort at least. In production pipelines, we may or may not already have a user that we are building for. In the latter case, the process of finding a user, identifying their needs and building relationships and trust takes time. So, we would either focus on the former or develop basic prototypes that would be useful in reaching out to potential users.

### Flexibility in time

There is of course flexibility in time as to when you want to work. However, it is expected that if you take up a project you spend a minimum of 8 hours a week (for UG) and 8 hour per day (for higher roles). It's fine to have variance here because you would inevitably work closer to 12 hours a day nearing deadlines or commitments to collaborators but please try to maintain a minimum commitment throughout the project.

### Working alone vs in teams

I would mostly suggest to work in teams (2-3 people) unless it hampers your learning objectives. Both complementarity and depth can be achieved in smaller teams with frequent discussions and iterations. Choose your team based on how badly they want to learn something your project would use rather than their existing skill in the area. In teams, remember to form relationships before trying to do transactions. Teach something to your teammates, try to understand what they value and where they are in their journey. That would typically give you more conviction in the team as well and set you up for a great collaboration.

### Working from home?

Work from home with caution. At the workplace, you find random adjacent knowledge in chats with colleagues, you absorb their energy and dedication towards their work and share laughter (ofcourse, on geospatial jokes only). That being said, if you need to take care of something for some time, please inform the people you work with and work from home.
