# Alex Tavor

**I build the tools other devs build with.** Authoring systems, visual editors, no-code
platforms, and the compilers and toolchains underneath them. Fifteen years across Flash, Java,
C#, TypeScript and Python, whichever the tool needed.

Lately the work is shifting dev left. If a developer's job is spec and architecture, then
implementation becomes detail an agent can carry. That only holds while the tests can be
treated as ground truth, so most of what is below is about validating tests.

[alextavor.github.io](https://alextavor.github.io) · [LinkedIn](https://www.linkedin.com/in/alextavor/) · Utrecht, NL

---

### The method, and the experiment that killed it

**[pdd-experiment-cave](https://github.com/AlexTavor/pdd-experiment-cave)**: a three-arm
experiment on a large brownfield codebase, comparing a raw agent, a chunked agent and the full
method. Frozen prompts, pinned commits, a kill-condition declared before the run, blind
adjudication by a separate judge. Run 1 is in. The full method found the same four
high-severity issues as the raw agent at 3.9x the cost, and one static gate returned 0 real
findings out of 36. Both results are committed as they came out.

**[proof-driven-development](https://github.com/AlexTavor/proof-driven-development)**:
concluded. A methodology and CLI for changing code you cannot verify by reading, legacy or
AI-generated, without breaking it. It graded whether a test would actually fail on a bug, using
mutation and boundary analysis; run against a public 226-star SDK it found a module at 94% line
coverage whose tests missed about a third of injected bugs. The experiment above is why it
stopped. What survived is the part that paid for itself: the skills and the deterministic
gates, which now run my current project.

**[engineering-discipline](https://github.com/AlexTavor/engineering-discipline)**: those skills,
extracted as an installable, stack-independent plugin, so the standard travels with a team.

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
