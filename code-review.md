# Code Review
![Code Review](https://raw.githubusercontent.com/TaraShanahan/SQA_Handook_Group9/main/Images/code-review.png)
## Introduction
A code review is the process where a developer’s code is examined by one or more team members before it is merged into the main codebase.
Instead of allowing individuals to work in isolation, code reviews ensure that all changes are checked, discussed, and improved collaboratively.
The purpose of a code review is not only to identify bugs, but also to improve the overall quality, readability, and maintainability of the code.
In a fast-moving startup environment, where speed is important, code reviews act as a safety net to prevent defects from reaching production and to maintain consistent standards across the team.
(https://www.computerworld.com/article/1345733) (https://www.holycode.com/blog/code-review-best-practices-and-techniques)

## Importance of Code Reviews

Code reviews are important because they not only uncover defects early in the development process but also help ensure consistent coding practices across the team. 
A comprehensive article on code review best practices highlights that effective reviews improve quality, refine design, and maintain compliance across a codebase
(https://www.wiz.io/academy/application-security)
By reviewing each other’s work, developers are encouraged to write cleaner and more thoughtful code, and team members become familiar with parts of the product they don’t work on every day. 
This collaborative benefit is one of the strongest cultural in the organisations report from adopting regular code reviews.
(https://builtin.com/software-engineering-perspectives)

![Why Code Review Matters](https://github.com/TaraShanahan/SQA_Handook_Group9/blob/main/Why-code-review-matters.png?raw=true)
 ## Review Process

1. A developer writes code on a feature or bug‑fix branch.
2. A Pull Request (PR) is opened to propose merging changes. The PR should clearly describe what was changed and why.
3. Automated tools (tests, linters, CI checks) run to catch obvious problems early.
4. One or more developers review the code manually. They examine logic, readability, adherence to standards, and test coverage.
5. Feedback is given in the
 PR comments.
6. The original developer addresses the comments and improves the code.
7. Once reviewers are satisfied, the PR is approved and merged into the main branch.

### What Reviewers actually want from a review 
Good reviewers focus on several key aspects of the code:
Correctness: Does the code meet the requirements and avoid bugs?
Readability: Can another developer easily understand what this code does?
Maintainability: Is the logic structured so that it will be easy to change in the future?
Consistency: Does the code follow team conventions and style standards?
Performance and Security: Are there performance bottlenecks or potential vulnerabilities?

### Best Practices for Code Reviews:D0s✅

when it comes to the code review practice it is very important to get things right some points that are a must to focus on:
1. Keep Pull Requests small and focused so reviewers can understand and evaluate them efficiently. Evidence shows that large code diffs reduce review effectiveness.
2. Provide clear context in PR descriptions so reviewers know what to look for this reduces time.
3. Be respectful and constructive in feedback, because code reviews should build team trust, not create tension  between team
members.
4, using frequent coomunication and comments help the process to go quicker and solve any minor problem before it turns into major one.

Well‑organised code review processes and positive team cultures around reviews are the best wau to make the task effective and bring a positive team spirit.

### Common Mistakes to Avoid:Don'ts❌

As we know that code reviews are beneficial, they can be misused and become less effective Some common issues include:
1. Allowing very large Pull Requests, which makes reviews tiring and ineffective make the ewquest bite sized and easy to work with.
2. Treating code reviews as nitpicking over details instead of focusing on meaningful improvements and genuine feedback.
3. Merging code without review, which defeats the purpose of having this quality control step in the first place.
(https://blog.pullnotifier.com/blog/9-actionable-code-review-best-practices-for-2025) (https://www.codeant.ai/blogs/code-review-process-guide)

![dos and don's](https://github.com/TaraShanahan/SQA_Handook_Group9/blob/main/Images/dos%20and%20don's.png?raw=true)

### further read about code reviews:

References for Further Reading
Code Review Best Practices from practitioners: https://builtin.com/software-engineering-perspectives/code-review-best-practices
 
 Running effective code reviews and why they matter: https://www.computerworld.com/article/1345733/running-an-effective-code-review-2.html

 Code review explanation and techniques: https://www.holycode.com/blog/code-review-best-practices-and-techniques/
 
 How to do and improve code reviews: https://engx.space/global/en/blog/how-to-do-code-review

 Best practices including PR size and effective feedback: https://www.codeant.ai/blogs/code-review-process-guide



