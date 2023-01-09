---
title: "Goodbye, Zig"
---

Here I explain why after 6 years the Zig programming language hasn't caught on and why I believe it doesn't have a bright future. I also explain why, despite of this, Zig shows up on the front page of Hacker News every couple of weeks.

Zig has been marketed as a "better C". Unfortunately, the language didn't address the issues associated with C (memory safety, concurrency). Nor it did introduce new ideas. Arguably the only feature that makes Zig stand out is its 'comptime' feature which languages like D have had for the last 16 years.

However, even though Zig didn't bring anything new to the table, some people might still prefer it because they feel more productive with it. The reason why we haven't seen Zig in companies' codebases and only in people's personal projects is because companies are reluctant to commit to a high-risk pre-alpha language.

And it doesn't look like Zig is going to reach version 1.0 anytime soon - the Zig compiler is still "not stable enough" to parse tabs:

- [https://github.com/ziglang/zig/wiki/FAQ#why-does-zig-force-me-to-use-spaces-instead-of-tabs](https://github.com/ziglang/zig/wiki/FAQ/4003c860ff980a854346976bddbaea55f1b1a789#why-does-zig-force-me-to-use-spaces-instead-of-tabs)

Then why do we keep seeing a pre-alpha language showing up on the Hacker News frontpage every couple of weeks?

Because there is a financial incentive to promote the language - these are the financial reports of the Zig Software Foundation:

<img width="690" alt="Finances" src="https://user-images.githubusercontent.com/116085775/196540578-f2114e5b-0188-4ea1-a869-a2a16ce4659f.png">

But since Zig doesn't have a solid technical foundation, promoting the language is not enough. The Zig team is also aggressive towards competing languages:

<img width="954" alt="Hacker News" src="https://user-images.githubusercontent.com/116085775/198046023-dc76b2e1-337c-4765-ba5f-99558828e08d.png">

and people who point out Zig's shortcomings:

<img width="768" alt="Twitter" src="https://user-images.githubusercontent.com/116085775/196545451-51be0cc0-c8a9-4806-8788-65b010f63ead.png">

Developers would love to see a language replacing the half-a-century old C. Unfortunately, I doubt that will be Zig.

[_Next post_](https://mikefsn.github.io/2022/10/22/how-the-zig-team-pushes-a-narrative.html)
