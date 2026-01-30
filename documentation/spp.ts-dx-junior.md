# Student Project Proposal (SPP)

## Tabel of Contents

- [Tabel of Contents](#tabel-of-contents)
- [Supervisor](#supervisor)
- [Students](#students)
- [Preliminary Thesis Title](#preliminary-thesis-title)
- [Elevator Pitch](#elevator-pitch)
- [Milestones](#milestones)
- [Risks](#risks)
- [Background](#background)
- [Related Work](#related-work)
- [Knowledge Gap](#knowledge-gap)
- [Knowledge Contribution](#knowledge-contribution)
- [Evaluation](#evaluation)
- [References](#references)

# Supervisor

- Mats?

## Students

- Samuel von Zweigbergk (sv222rr)
- Ludwig Wittenberg (lw223cq)

## Preliminary Thesis Title

Understanding the Impact of TypeScript on Developer Experience Among Junior Web Developers

*How does TypeScript affect the developer experience of junior web developers compared to JavaScript?*

## Elevator Pitch

TypeScript is widely believed to improve developer experience by better software quality and better understanding of the codebase, however its impact on junior developers is unclear. This thesis investigates whether and how TypeScript changes junior developers, developer experience compared to JavaScript, focusing on concrete aspects like debugging, confidence, refactoring, and common mistakes. We will collect evidence through semi-structured (including code tests) interviews with junior and senior developers and analyze recurring themes to produce practical guidance on when TypeScript improves (or harms) developer experience for juniors.

## Milestones

1. Define the research question
2. Review the related work
3. Design the methodology
4. Recruit participants
5. Analyze the data
6. Finalize the thesis

## Risks

- Limited access to junior developers
- Interview questions might be unclear or difficult to understand
- Limited validity of the results due to the small sample size

## Background and Motivation

Developer experience (DX) is fundamental in the day to day enjoyment of developers. DX is a measurement of the effectiveness of software development. Productivity, impact and satisfaction are the main parts of DX. Productivity is the effectiveness of a developer who can do their best work. How fast a developer can move from idea to production is part of the impact. But also how easy and effective the developer can make code changes in the codebase. Satisfaction describes how positive or negative the work environment, workflow and tools are. [1]

DX is an important factor for the success of teams and projects. A positive DX can influence developer confidence and can improve their satisfaction. With a positive DX, developers can build applications with the best available tools. [1]

JavaScript's (JS) "superset" TypeScript (TS) adds optional typing to the language. The use of TS adds benefits like static typing and interfaces, which means that the developer can create a more robust codebase and catch errors at compile time instead of runtime. Types also improve the documentation, understandability and readability of the codebase. [2] On top of that, TS also improves the maintainability and scalability by making the codebase more modular and easier to understand. Meanwhile, TS has some downsides, increased compile time and a higher learning curve compared to JS. [3] Despite this, TS is one of the most popular languages for web development. [4] 

By adding static typing to the codebase, errors can be caught as early as in the integrated developer environment (IDE). This improves productivity, which enables the developer to create their best work. [2] When using types and interfaces, we can improve the modularity and at the same time increase the robustness of our codebase, which improves the ease of implementing changes in the codebase. By adding some rules and checks to our codebase, it can drastically improve the developer satisfaction in our project. It creates a good work environment, with code that is easy to maintain, but also improves the modularity and scalability of the code. [3]

DX can be very important for junior developers, especially in their early stages of their career. They often have limited experience and knowledge about programming. DX includes productivity, impact and satisfaction. Despite dynamic languages like JS may be easier to learn and understand for junior developers, they can present challenges to maintain and understand for them. In this context, TS may be relevant for them since it provides some structure, rules and type safety that can help them to create more maintainable code.


## Related Work

Previous studies performed a mining study on GitHub to compare the software quality of TS and JS projects. Both articles found evidence in half of their key figures to support that TS applications exhibit higher software quality. TS applications were more bug prone and took longer to fix. [6], [7]

They measured and compared different key figures to support their research. Code smell, cognitive complexity, bug fix commits, bug resolution time per language and how often the “any” type was used in TS. These studies don't focus on the DX, but they are good to understand the difference in software quality between TS and JS. [6], [7] Our research will focus on how TS affects the DX of junior developers compared to JS.

Another previous study focused on the DX when migrating a JS project to TS. [8] The study found that the DX improved when migrating to TS. They also found that the code got a consistent code structure and better understandability. [8] After the migration, the code got better documentation, it also improved the usage of autocomplete and other tools that are available in the IDE. [8] 

However, this result may lack some validity since it only contains one project and one developer view. We also don't know if the developer was a junior or senior. [8] Instead of focusing on the migration, we will focus on the DX of junior developers when they are using TS instead of JS.

All these studies were performed in the last five years and contribute to a good understanding of the difference in software quality between TS and JS. [6], [7], [8] However, they don't focus on the DX of junior developers. Our research will focus on how TS affects the DX of junior developers compared to JS.



## Knowledge Gap

The previous studies have studied the software quality of applications when comparing TS and JS as the main language. Some studies also focus on how DX is affected by using TS compared to JS, especially when migrating a JS project to TS. Despite this, there is a lack of research on how junior developers experience TS compared to JS in terms of developer experience. This represents a knowledge gap in computer science and is related to the DX of junior developers.

## Knowledge Contribution

By conducting semi-structured interviews on junior and senior developers, we can contribute to knowledge about how TS affects junior developers productivity, impact and satisfaction. We will get a deeper understanding of how TS is used in the field of software engineering and how senior developers use TS and how that affects their DX. 

## Evaluation

We intend to gather data through semi-structured interviews on junior and senior developers. We will also be hosting a workshop with junior developers. The workshop will include tasks in both TS and JS, with different difficulty levels and goals. All participants will be given the exact same tasks to complete, which will be used to draw conclusions about the productivity, impact and satisfaction of junior developers when working with a TS codebase compared to JS codebase. The data will be analyzed using thematic analysis to identify recurring themes and patterns.

We will conduct the workshop and interviews with junior developers that have a limited experience with programming. Mostly year 2 or 3 students. The senior developers will be chosen from the company Flowbic in Kalmar. They have more than eight years of experience in the field of software development. This is to get another perspective on how TS affects the DX of senior developers.

Due to limited access to junior developers, we will only be able to conduct the workshop and interviews with a small sample size. This may limit the validity of the results.

Ethical considerations include informed consent, voluntary participation, anonymization of all participants, and the right to withdraw from the study at any time without consequences.



## References

[1] G. Davis, “Developer experience: What is it and why should you care?”, GitHub Blog. [Online]. Available: https://github.blog/enterprise-software/collaboration/developer-experience-what-is-it-and-why-should-you-care/. [Accessed: 29-Jan-2026].

[2] Microsoft, "What is TypeScript?", TypeScript webpage. [Online]. Available: https://www.typescriptlang.org/. [Accessed: 29-Jan-2026].

[3] Paul Bratslavsky, "Top 6 Benefits of Implementing TypeScript", Stapi blog. [Online]. Available: https://strapi.io/blog/benefits-of-typescript. [Accessed: 29-Jan-2026].

[4] Stack Overflow, "Most Popular Programming Languages 2025", Stack Overflow Developer Survey 2025. [Online]. Available: https://survey.stackoverflow.co/2025/technology. [Accessed: 29-Jan-2026].

[5] Andriy Obrizan, "The Difference Between Senior, Middle and Junior Developers", LeanyLabs. [Online]. Available: https://leanylabs.com/blog/senior-vs-middle-vs-junior-developers/. [Accessed: 29-Jan-2026].

[6] Justus Bogner and Manuel Merkel, "To Type or Not to Type? A Systematic Comparison of the SoftwareQuality of JavaScript and TypeScript Applications on GitHub", dl.acm.org. [Online]. Available: https://dl.acm.org/doi/epdf/10.1145/3524842.3528454. [Accessed: 29-Jan-2026].

[7] Manuel Merkel, "Do TypeScript Applications Show Better Software Quality thanJavaScript Applications? A Repository Mining Study on GitHub", elib.uni-stuttgart.de. [Online]. Available: https://elib.uni-stuttgart.de/server/api/core/bitstreams/f73e742e-ed9c-4a66-8469-fcf54465871c/content. [Accessed: 29-Jan-2026].

[8] Maija Heiskanen, "MIGRATING A LARGE JAVASCRIPT WEB UI TO TYPESCRIPT TO IMPROVE
DEVELOPER EXPERIENCE", lut.fi. [Online]. Available: https://lutpub.lut.fi/bitstream/handle/10024/164790/masters_thesis_maija_heiskanen.pdf?sequence=1&isAllowed=y.