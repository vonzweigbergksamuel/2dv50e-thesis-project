# Summaries of Related Articles

## Table of Contents

- [Summaries of Related Articles](#summaries-of-related-articles)
  - [Table of Contents](#table-of-contents)
  - [Related Articles](#related-articles)
  - [Summaries](#summaries)
    - [Migrating a large JavaScript web UI to TypeScript to improve developer experience](#migrating-a-large-javascript-web-ui-to-typescript-to-improve-developer-experience)
    - [An empirical investigation of the effects of type systems and code completion on API usability using TypeScript and JavaScript in MS visual studio](#an-empirical-investigation-of-the-effects-of-type-systems-and-code-completion-on-api-usability-using-typescript-and-javascript-in-ms-visual-studio)
    - [Generating TypeScript types from OpenAPI specification for improved developer experience](#generating-typescript-types-from-openapi-specification-for-improved-developer-experience)
    - [JavaScript alternative (TypeScript) and its effectiveness in web development](#javascript-alternative-typescript-and-its-effectiveness-in-web-development)
    - [Modern front-end web development :­ how libraries and frameworks transform everything](#modern-front-end-web-development--how-libraries-and-frameworks-transform-everything)
  - [Final Thoughts](#final-thoughts)
  - [We think that these articles are best suited as related work for our bachelor thesis:](#we-think-that-these-articles-are-best-suited-as-related-work-for-our-bachelor-thesis)

## Related Articles

- [Migrating a large JavaScript web UI to TypeScript to improve developer experience](https://lutpub.lut.fi/handle/10024/164790)
- [An empirical investigation of the effects of type systems and code completion on API usability using TypeScript and JavaScript in MS visual studio](https://dl.acm.org/doi/abs/10.1145/2936313.2816720)
- [Generating TypeScript types from OpenAPI specification for improved developer experience](https://lutpub.lut.fi/handle/10024/170636)
- [JavaScript alternative (TypeScript) and its effectiveness in web development](https://www.theseus.fi/handle/10024/795522)
- [Modern front-end web development :­ how libraries and frameworks transform everything](https://www.theseus.fi/handle/10024/342325)
- [To type or not to type?: a systematic comparison of the software quality of JavaScript and typescript applications on GitHub](https://dl.acm.org/doi/abs/10.1145/3524842.3528454)
- [TypeScript: An Open-Source Programming Language with Options for Robust Development and Large-Scale Applications](https://ieeexplore.ieee.org/abstract/document/10743426)
- [Do TypeScript Applications Show Better Software Quality than JavaScript Applications? A Repository Mining Study on GitHub](https://elib.uni-stuttgart.de/server/api/core/bitstreams/f73e742e-ed9c-4a66-8469-fcf54465871c/content)

## Summaries

### Migrating a large JavaScript web UI to TypeScript to improve developer experience

`2022 (Relevant)`

The article is about how to migrate a large JavaScript web UI codebase to TypeScript and how that improves the Developer Experience (DX). One intresting part is how the mood of developer impact code quality and productivity. Another interesting thing is how the migration of the codebase to TypeScript improved more than just DX, it seemed to have made bugs less likely and the code more optimized. The article demonstrates clear advantages of using TypeScript. The code written in Typescript have a consistent code structure, direct documentation in the code from the types themselves, and made it easier to understand and comprehend the code. It also benefits the usage of autocomplete and other tools that are available in a modern IDE.

**Reflections**

What articles can we reference to explain the difference between dynamically- and statically typed languages, and the advantages of statically typed ones?

What constitutes Developer Experience (DX)? What is it, how is it defined? We need to know this to be able to design good testing with junior developers.

More dependencies are required for typescript, mainly just "typescript". How is the tooling equiped for typescript? New tooling like Bun and Deno are Typescript compatible out of the box, Node doesn't have full support yet but they are getting there (can be fixed by adding a dependency like "tsx"). Are packages built for typescript? Not all, but many, and Typescript can still be useful when some aren't. You can infer the types from return values or if that's not possible the "any" or "unkown" types can be used.

It can take a lot of time for types to update in an IDE in a large project. The type-checker takes time. The TypeScript port to Golang will improve this dramatically.

[Color coded article](../pdf/migrating-a-large-javascript-web-ui-to-typescript-to-improve-developer-experience.pdf)

---

### An empirical investigation of the effects of type systems and code completion on API usability using TypeScript and JavaScript in MS visual studio

`2015 (Not relevant)`

The article is about comparing JavaScript with TypeScript for code completion in IDE's (Microsoft Visual Studio). The article describes a comparison between 4 groups that got different tasks in TS or JS and with or without code completions. There was a large difference between TypeScript and JavaScript but only a small effect when it came to code completions. The result didn't show any significant differences between the groups. The authors said that the result should not be overinterpreted. It was a very controlled experiment. They don't describe the result or their conclustion in a good and clear way.

**Reflections**

Old article, from 2015.

Not much of a conclusion that would be useful for our thesis.

---

### Generating TypeScript types from OpenAPI specification for improved developer experience

`2025 (Relevant)`

This article is from the same university as the first article. This article describes how important it is to know the types of an API your working with. The author created a survey which had developers answer different questions about their experience with working with types and API documentation. The result showed that the developers were more satisfied when working with types that got autogenerated from the OpenAPI specification. We can see a big improvement in the developer experience when the types are autogenerated from the OpenAPI specification. However it was only a small group of developers that answered the survey. So we can't really draw any conclusions from this article on the validity of the result. However it is still intresting to see that the developer experience is improved when working with types.

**Reflections**

They had a *AI usage* part under the Declarations heading. This will be very important if we decide to use AI, for example to improve grammar...

Stack Overflow survey on popularity of TypeScript growing. Could be interesting to reference in the *Background* part of the thesis.

[Color coded article](../pdf/generating-typescript-types-from-openapi-specification-for-improved-developer-experience.pdf)

### JavaScript alternative (TypeScript) and its effectiveness in web development

`2023 (Relevant)`

This article is about the benefits of using TypeScript instead of JavaScript in general. It describes the benefits of using Typescript and how it can improve the code quality, maintainability, scalability and early error detection. It also includes a case study of TypeScript which includes different companies and their use of TypeScript. It feels like the case studies/experiments they did are missing something. It feels like they are just describing the benefits of using TypeScript and not showing any actual data or experiments that prove it's benefits. Overall it is a good article that describes the benefits and drawbacks of using Typescript. The article highlights that developers already comfortable with JavaScript may need to put in some extra effort to learn TypeScript, that it adds an extra step to the build process and that it's overall a worthwhile investment for all the above mentioned benefits.

**Reflections**

*Could be good to use if we write about if schools should switch to teaching typescript instead of javascript. Overall it is a good article that describes the benefits and drawbacks of using Typescript.*

Another article describing the benefits of TypeScript.

[Color coded article](../pdf/javascript-alternative-typescript-and-its-effectiveness-in-web-development.pdf)

### Modern front-end web development :­ how libraries and frameworks transform everything

`2020 (Might be relevant)`

This article is about HTML, CSS and JavaScript vs libraries and frameworks.

**Reflections**

*Not quite inline with what we want to write about.*

TypeScript is good for debugging.

TypeScript: "JavaScript that scales"

## Final Thoughts

We think that these articles are best suited as related work for our bachelor thesis:
- 