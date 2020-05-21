## lit_ai - Literature in the Age of Artificial Intelligence 

# about

This was the final project for the class CLEN 4728 Literature in the Age of Artificial Intelligence with Professor Dennis Tenen.

# proposal
The artifact I have chosen to work with is Quirinus Kuhlmann’s Love-Kiss XLI. “Kuhlmann published his first major collection of poems in 1671 at age twenty - a sequence of fifty sonnets in alexandrines entitled Himmliche Libes-Kusse (Heavenly love-kisses), derived in part from the allegorical erotics of Solomon’s Song of Songs.” The purpose of this artifact was to generate love poems using a method Kuhlmann described in the following manner:

1. Begin a sentence with the given first word.
2. Select one of thirteen words for a given line at random, and use this as the next word in the sentence.
3. Concatenate the first two words from a  b with the last two words of the sentence which are given on therespective line.

```
Example for Steps 1-3 using the first line in Love-Kiss XLI: From Fog and Plagues
'''

4. Construct 11 more sentences following steps a-c with each of the 12 lines in the poem.
5. Attach Kuhlmann’s given final two sentences, one of which contains a combinatorial element.

![proposal](https://github.com/tmatrixhy/lit_ai/blob/master/proposal.pdf)

# results

```
from fire and plagues
come blaze and dread
from fear and fraud
come joy morning rays

the tree at play
love fruit and bread
the work and god
seek praise to say

what should be named
with care to avoid
lest peace be destroyed
where fear the day

all things do change; all things do love; all things are locked in hate
whoever fully thinks this through holds the key to man's estate
'''

```
from frost and plagues
come light and dread
from fear and fraud
come fame morning rays

the tree at play
love fruit and bread
the work and god
seek praise to say

what should be named
with care to avoid
lest friend be destroyed
where woe the day

all things do change; all things do love; all things are locked in hate
holds the key to man's estate whoever fully thinks this through
'''

![results](https://github.com/tmatrixhy/lit_ai/blob/master/final_submission.pdf)

# code

![code](https://github.com/tmatrixhy/lit_ai/blob/master/lit_ai_FINAL.ipynb)