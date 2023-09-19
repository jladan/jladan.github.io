+++
title = "Markov Wordsearch Generator"
description = "A simple wordsearch generator trained on the complete works of shakespeare"
date = "2014-09-11"
jobDate = 2014
work = ["hobby"]
techs = ["C++", "Markov Chains"]
designs = []
thumbnail = "markov-word-search/sample-grid-filled.png"
projectUrl = "https://github.com/jladan/wordsearch"
# testimonial =""
#   name = ""
#   role = ""
#   image = ""
#   text = ""
+++

This was a little experiment to play with Markov chains. The wordsearch is
generated using a 2nd order Markov-chain. That is, the probability of the next
letter is determined by the previous two letters.

The Markov model was trained from the complete works of Shakespeare, and used to
generate a 2D grid of letters, randomly creating a wordsearch, which likely
contains words. This also makes it difficult, because everything has the
appearance of English words.

Limitations:
- Biased towards common words (like "the", "and", "with", etc.), because these
  weren't filtered out of the training set.
- Biased toward shorter words, because it is only 2nd order.

