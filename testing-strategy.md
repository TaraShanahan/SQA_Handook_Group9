# Testing Strategy
## 1.Introduction
Welcome to the topic of testing strategy ! In software engineering a testing strategy is the overall approach used to verify that systems, features and code changes work as expected before the release. It defines how quality will be checked, what types of testing should be used, and how testing fits into the wider development process. This section outlines the guidlines of a testing strategy, the key practices that support effective testing, and the common mistakes/bad practices that should be avoided.
## 2.Testing Strategy Guidelines and Good Practices
These guidelines and good practices are supported by practical engineering write-ups found online where teams improved their testing strategy after experiencing real delivery and quality problems.
 -   **Keep tests stable and worth trusting**  
    A test suite is only useful if developers believe the failures actually mean something. If tests fail randomly or break too easily people start ignoring them. This came through clearly in Google’s discussion of flaky tests and also fits broader practical guidance from teams that focus on maintainability and consistency.[Read More](https://testing.googleblog.com/2016/05/flaky-tests-at-google-and-how-we.html)
-   **Make tests maintainable as the system grows**  
    Good testing is not just about catching bugs once. Tests also need to stay readable, manageable and easy to update over time. Stack Overflow’s post shows that difficult to test code can hold a team back which makes maintainability part of the testing strategy itself rather than just a coding concern and Gitlabs guidance reinforces that [lower-level](https://gryftec.com/en/low-level-testing/) tests are usually easier to maintain than end-to-end tests, which are more expensive to run and support.[Read More](https://stackoverflow.blog/2022/07/04/how-stack-overflow-is-leveling-up-its-unit-testing-game)
-   **Match the strategy to the architecture**  
    Testing strategy should not be one size fits all. Spotify’s microservices article is useful because it shows that once a system becomes more distributed,service interactions and integration points become a much bigger part of the risk. In that kind of setup, testing needs to reflect how the system actually behaves in practice, not just how individual units behave in isolation.[Read More](https://engineering.atspotify.com/2018/01/testing-of-microservices)
-   **Improve the testing process when it becomes a bottleneck**  
    Slack’s engineering write up is a good example of this. Their focus was not simply “do more testing”, but improve the pipeline so engineers were not wasting time on redundant work. That is a useful reminder that testing strategy is also about how tests run in practice, not just what types of tests exist on paper.[Read More](https://slack.engineering/speedup-e2e-testing/ )
    
## 3. Bad Practices to Avoid
A testing strategy becomes much less effective when testing is inconsistent, overly manual or treated as something to do at the very end. Sources show that weaker testing habits often lead to the same outcome i.e slower feedback, less confidence in releases, and more defects reaching production.

![tests](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS2q1Q4oLdfZDPcClJqR3fzYcgQ481mFCepXQ&s)
 - **Relying too heavily on manual testing**  
  Manual testing still has value, but on its own it is difficult to repeat consistently and becomes harder to manage as systems and releases grow.
-   **Overusing end to end tests**  
    End to end tests are useful for checking key user journeys, but too many can make the test suite slow, fragile and more difficult to troubleshoot.
-   **Testing only happy paths**  
    Focusing only on expected outcomes can leave major gaps in quality. Errors, edge cases and unusual inputs also need to be tested.
-   **Writing flaky or brittle tests**  
    Tests that fail randomly or break after small changes reduce trust in the test suite and create unnecessary work for developers.
-   **Focusing on coverage numbers over test value**  
    High coverage does not automatically mean effective testing. Tests should be meaningful and should check important behaviour, not just inflate metrics.
-   **Leaving testing until the end of development**  
    When testing is delayed until the final stage, issues are often found later, fixes become more rushed, and release confidence is reduced.

These problems appeared or are inferred across the research and show that poor testing strategy is usually not caused by one single issue, but by a combination of weak habits over time.


## 4. What We Learned from the Teams and Sources

Looking across the teams and sources used in this section, a few clear lessons stood out. The main one was that good testing strategy is not about having the most tests, but about having tests that are reliable, maintainable and suited to the systems being built. Many of the teams faced similar problems such as flaky tests, too much manual testing, slow pipelines and over reliance on one test layer.

In summary the key lessons our to keep testing balanced, practical and consistent. We should aim to use the right mix of tests and keep them stable enough to trust and avoid letting testing become rushed or left until the very end!!  Just as importantly testing should support development rather than slow it down. Overall the sources showed that strong testing comes from good habits, maintainable processes and a clear strategy followed by the whole team.Good luck with your testing ! and if you want to read more about all this look at the links below !!!

## 5. Further Reading

-   [Google Testing Blog, Flaky Tests at Google and How We Mitigate Them](https://testing.googleblog.com/2016/05/flaky-tests-at-google-and-how-we.html)
-   [Stack Overflow Blog, How Stack Overflow is leveling up its unit testing game](https://stackoverflow.blog/2022/07/04/how-stack-overflow-is-leveling-up-its-unit-testing-game)
-   [Spotify Engineering, Testing of Microservices_](https://engineering.atspotify.com/2018/01/testing-of-microservices)
-   [Slack Engineering, Optimizing Our E2E Pipeline](https://slack.engineering/speedup-e2e-testing/)

-  [GitLab Docs , testing levels / E2E best practices](https://docs.gitlab.com/development/testing_guide/testing_levels) 

-  [Low Level Testing ](https://gryftec.com/en/low-level-testing/)
