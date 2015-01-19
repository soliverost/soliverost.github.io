---
title: "Insight Data Engineering Project"
---

Earlier this week I was struggling to choose a project that would be a good fit to learn and practice the art of building full big data pipelines. The thing that resonated with me the most was: *Pick a project that is personal to you*.

For the past couple of years I have been working on serious topics like Cancer Care Engineering and the Coast Guard Visual Analytics Suite (cgSARVA). I really enjoyed working both of those projects and I can say they taught me several things:

* The definition of Big Data varies from person to person, for some is measured in the amount of memory, for others is measured in the amount of records, and the exact numbers that make a dataset a Big Data dataset also depend on the user.
* The traditional Relation Database Model works well in certain scenarios.
* Data is highly valuable in the industry/governement. Therefore a lot of interesting datasets are not publicly available.

So, I was looking for a dataset that can be scaled to fully showcase the benefits of implementing at Big Data pipeline and that has a realtime component to further explore the Lambda Architecture. That narrowed down a lot of the datasets because either: the dataset is not publicly available, the dataset is not large enough to merit being proccessed in a distributed file system, there is no real-time analysis component, or the dataset is not really personal to me

I decided I wanted to work with sports data since both my husband and I love watching live sports. A traditional game of football/basketball/soccer/tennis doesn't warrant the use of DFS to analyze it (unless we talk about getting the recorded movements for each player but sadly that information is not public), therefore I though about recreating a <mark>Fantasy Sports League</mark> introducing real-time analytics and real-time substitutions.

To me, createing a fantasy sports league from scratch meets the requirements: the number of users playing in the overall league can easily be scaled to thousands, if not millions of users to test the robustness of the pipeline. It also has a real-time component when couple with logs that can simulate an actual game being played, and a large amount of users substituing players from the bench. And I can engineer the data in lieu of trying to convince Yahoo to share they fantasy league information data.

Time can be a constraint, but I will be initially simplifying the rules and the model that I will be using. You can follow the development of the project in the future posts of this blog.