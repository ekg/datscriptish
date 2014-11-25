# datish scriptish

## like make, but not really
## and it's for streams

This is a non-functional illustration of a putative stream-based pipeline
language.

What is it trying to do that make doesn't?

1. Streams, not (necessarily) files
2. Named @pipe*lines*
3. FUN FUN FUN
4. Heredoc-like scripting (lowering the barrier to including custom scripts)
5. If you redefine the semantics of ">" you no longer need tee and pee to define pipeline forks. NB: it's just POSIX that forces us to use only one redirect (>).
6. Merging remains hard, if your data requires custom semantics
