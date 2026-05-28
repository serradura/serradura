### Hi, I'm Rodrigo Serradura 👋

I build Ruby and Rails tools and write about software architecture. For years I've been chasing one question: how do you keep a codebase easy to change as it grows?

I've been building with Ruby since 2010, these days on large production Rails systems. I also founded a community for people who like arguing about this stuff.

The question has a new edge to it now. Good architecture used to be a favor you did for the next human who'd open the file. The next reader might be an AI agent instead, and it turns out the things that make code easy for a person to navigate are mostly the same things that make it cheap for an agent to reason about. That overlap is what most of my recent work is about.

Most of it lives in three GitHub orgs.

## 🦾 Rails Whey

[railswhey](https://github.com/railswhey) is the one I'm proudest of: the same Rails app built 28 different ways. Each branch applies a single architectural rule, from one fat controller all the way to bounded contexts with separate databases, using nothing but what Rails ships with. No gems. No imported architecture.

Every branch carries its own deep-dive README: the rule it applies, before-and-after numbers (lines of code, a code-quality score), and a section on how the change plays for an AI coding agent. Read it front to back as one story, or jump to whichever family matches the problem you're staring at right now.

It's a gift to the community. Explore it, learn from it, challenge it.

→ [github.com/railswhey/app](https://github.com/railswhey/app)

<p align="center">
  <img src="./assets/rails-whey.png" alt="Rails Whey App" width="640">
</p>

## ⚛️ Solid Process

[solid-process](https://github.com/solid-process) is where the newer ideas live. `solid-process` is a way to write business logic in Ruby and Rails that stays readable as the app scales. It's the evolution of `u-case`: same goal, fewer compatibility constraints, and everything I've learned in the years since.

→ [github.com/solid-process/solid-process](https://github.com/solid-process/solid-process)

<p align="center">
  <img src="./assets/solid-process.png" alt="Solid Process" width="640">
</p>

## μ-gems

[u-gems](https://github.com/u-gems) is a home for small Ruby libraries, each one doing a single job and stopping there. The best known is `u-case`: you write a use case as a small object with typed attributes and a `Success(...)` or `Failure(...)` result.

`u-case` has been in production for years, so its public API is frozen. The contracts you depend on today won't move. Any next rethink of those abstractions happens over in Solid Process instead.

→ [github.com/serradura/u-case](https://github.com/serradura/u-case)

<p align="center">
  <img src="./assets/u-gems.jpg" alt="μ-gems" width="640">
</p>

## Ada.rb

I founded and run [Ada.rb](https://linktr.ee/ada.rb), a community for people who care about Ruby design, architecture, and AI-assisted development. It's where a lot of these ideas get tested and picked apart before they turn into anything public.

## Find me elsewhere

- [LinkedIn](https://www.linkedin.com/in/rodrigo-serradura/)
- [YouTube](https://www.youtube.com/@rodrigoserradura)
- [X](https://x.com/serradura)

Ruby and Rails rock. 🤘
