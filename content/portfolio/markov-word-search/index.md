+++
title = "Markov Wordsearch Generator"
description = "A simple wordsearch generator trained on the complete works of shakespeare"
date = "2023-09-11T13:24:34-04:00"
jobDate = 2014
work = ["hobby"]
techs = ["C++", "Markov Chains"]
designs = []
thumbnail = ""
projectUrl = "https://github.com/jladan/wordsearch"
# testimonial =""
#   name = ""
#   role = ""
#   image = ""
#   text = ""
+++

<!-- TODO include a sample letter grid -->
<!-- TODO create a nice thumbnail image-->

This was a little experiment to play with Markov chains. The wordsearch is
generated using a 2nd order Markov-chain. That is, the probability of the next
letter is determined by the previous two letters.

The Markov model was trained from the complete works of Shakespeare, and used to
generate a 2D grid of letters, randomly creating a wordsearch, which likely
contains words.

