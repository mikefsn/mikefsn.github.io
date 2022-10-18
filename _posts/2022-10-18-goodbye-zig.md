---
title: "Goodbye, Zig"
---

Here I explain why after 6 years the Zig programming language hasn't caught on and why I believe it doesn't have a bright future. I also explain why, despite of this, Zig shows up on the front page of Hacker News every couple of weeks.

Zig has been marketed as a "better C". Unfortunately, the language didn't address the issues associated with C (memory safety, concurrency). Nor it did introduce new ideas. Arguably the only feature that makes Zig stand out is its 'comptime' feature which languages like D have had for the last 16 years.

However, even though Zig didn't bring anything new to the table, some people might still prefer it because they feel more productive with it. The reason why we haven't seen Zig in companies' codebases and only in people's personal projects is because companies are reluctant to commit to a high-risk pre-alpha language.

And it doesn't look like Zig is going to reach version 1.0 anytime soon. Basic features like:
- https://github.com/ziglang/zig/issues/910
- https://github.com/ziglang/zig/issues/943

have been 'in development' for the last 5-7 years even though the Zig team has been working full-time on the language since 2018.

Then why do we keep seeing a pre-alpha language showing up on the Hacker News frontpage every couple of weeks?

Because there is a financial incentive to promote the language - the Zig Software Foundation is making hundreds of thousands of dollars / year in donations:

<img width="690" alt="Finances" src="https://user-images.githubusercontent.com/116085775/196540578-f2114e5b-0188-4ea1-a869-a2a16ce4659f.png">

But since Zig doesn't have a solid technical foundation, promoting the language is not enough. The Zig team is also attacking competing languages:

<img width="947" alt="Hacker news" src="https://user-images.githubusercontent.com/116085775/196540629-71176776-de8a-41db-9dfb-ea3fc8dff8ff.png">

and people who point out Zig's shortcomings:

<img width="768" alt="Twitter" src="https://user-images.githubusercontent.com/116085775/196540694-ff2a0abc-61c7-48d1-936e-5e8259a89134.png">

Developers would love to see a language replacing the half-a-century old C. Unfortunately, I doubt that will be Zig.
