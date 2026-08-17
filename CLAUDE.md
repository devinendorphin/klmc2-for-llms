# klmc2-for-llms

**Register: seed.** A name and an intention. Scaffold minimally; do not build a project
around a sentence.

**Stated intention:** "Seeing if LLMs might find this method of animation useful for
purposes of visual communication."

## What this repo needs first

1. **A definition of KLMC2.** The hub `GLOSSARY.md` currently marks it *(needs your
   definition)*. Best inference from the `FLUX_KLMC2_Animation` notebooks in `Klmc2-flux` is
   Kinetic Langevin Monte Carlo (order 2) used as a diffusion sampler — but that is inferred
   from filenames, not from anything committed. Ask rather than assume.
2. **A thesis paragraph.** What would it mean for an LLM to "find this useful"? Generating
   the animations? Reading them? Using them as an output modality?
3. **A decision about `Klmc2-flux`.** That repo holds the two working notebooks and no
   README. These may be one project rather than two — merging is a legitimate outcome.

## The harness

The canonical working agreements, the atlas of all repos, and the shared glossary live in
**`devinendorphin/claude-at-claude`**. Pull it in when you need the full map:

```
add_repo devinendorphin/claude-at-claude
```

This container is ephemeral, so anything that matters gets committed *this turn*. Be a
collaborator rather than a cheerleader, and run a disconfirming test on primed claims.
Endorphin works from a phone and often dictates while walking — expect speech-to-text
artifacts, and mark guessed corrections `[?original→guess]`.
