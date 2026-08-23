# Alex Tavor

I build virtual power tools - authoring systems, visual editors, no-code
platforms, and the compilers and toolchains underneath them. Fifteen years across Flash, Java,
C#, TypeScript, Python, whichever the tool needed.

Agents got good enough at implementation that the work can finally move up to spec and
architecture. That only holds while the tests can be treated as ground truth, so most of what
is below is about validating tests.

[LinkedIn](https://www.linkedin.com/in/alextavor/) · Utrecht, NL

---

### A method, and the experiment that killed it

**[pdd-experiment-cave](https://github.com/AlexTavor/pdd-experiment-cave)**: a three-arm
experiment comparing a raw agent against a spec-driven method on a large brownfield codebase.
Prompts frozen, commits pinned, blind adjudication by a separate judge. Stopped after run 1,
because the result was stark and a run is expensive.
[Dashboard](https://alextavor.github.io/pdd-experiment-cave/).

**[proof-driven-development](https://github.com/AlexTavor/proof-driven-development)**:
concluded. A method and CLI for changing code you cannot verify by reading, legacy or
AI-generated, without breaking it. The experiment above is why it stopped, and the
[post-mortem](https://github.com/AlexTavor/proof-driven-development/blob/main/POSTMORTEM.md)
says what came out of it.

**[engineering-discipline](https://github.com/AlexTavor/engineering-discipline)**: the rules
that survived, as an installable, stack-independent plugin. Every one exists because something
went wrong on a real project, and each cites the commits it was recovered from.

**[gatechain](https://github.com/AlexTavor/gatechain)**: the companion to
engineering-discipline. Those rules as enforceable gates for TypeScript repositories: eleven
detectors and the chain that runs them at the pre-push hook and in CI. The modules are what
independently survived into two unrelated codebases, and the package is gated by its own chain.

**[chdr](https://github.com/AlexTavor/chdr)**: a LangGraph orchestrator for an autonomous TDD
loop, with a post-mortem on the results.

### Engines and authoring

**[cave-public](https://github.com/AlexTavor/cave-public)**: a browser simulation game on a
custom data-driven engine, with compiler and linker, physics, simulation and narrative
subsystems, an authoring suite, and the art tool I made its visuals with.
[Play it](https://speaks-with-stone.itch.io/cave).

### Local tooling

**[dod](https://github.com/AlexTavor/dod)**: one local supervisor that registers, launches and
frames every other local dashboard in a single admin UI.

**[rapport](https://github.com/AlexTavor/rapport)**: local-only analysis and graphing of
relationships from text chat dumps.

---

**Stack:** TypeScript · React · Node · Python · C# · Java · Unity

Open to lead and senior engineering roles. Reachable on
[LinkedIn](https://www.linkedin.com/in/alextavor/).
