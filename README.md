This `manublast` repository is an example "blast" repository for:

1. prompt space specification files, see [specs/](specs/), which can be used with
   [copyblaster/gen_prompt_space.py](https://gitlab.com/castedo/copyblaster/-/blob/main/gen_prompt_space.py)
   to generate 

2. large spaces of prompts, for example, [manu1/](manu1/), which along with

3. test source input files, see TBD ..., can be used with
   [copyblaster/blast_cases.py](https://gitlab.com/castedo/copyblaster/-/blob/main/blast_cases.py)
   to generate lots of

4. outputs files, see TBD, which can be stored to this repository, and then these outputs
   can in turn can be used along with

5. check files, see TBD, for evaluate outputs using
   [copyblaster/score_outputs.py](https://gitlab.com/castedo/copyblaster/-/blob/main/score_outputs.py)
   to generate

6. lots of interesting statistics and metrics comparing entire classes of prompts in the prompt
   space.


Another example of a "blast" repository is
[copyblast](https://gitlab.com/castedo/copyblast) where Castedo stores blast testing
results for new prompts for be recommended for use with [CopyAId](https://copyaid.it).
