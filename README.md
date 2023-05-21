# MTGBML.js
Multi-Threaded Generation-Based Machine Learning for JavaScript.

Let's do the example where we try to generate the string hi with MTGBML. MTGBML starts with a mother unit, the mother unit's got a completely random string (or in other things, dna) and has a few baby units, the baby units randomly change the string (dna) that they inherit from her (in this case by 1 letter), we calculate all the baby unit's fitnesses (in this example how many letters are correct) and the baby unit with the highest fitness is the new mother unit. If there are more than 1 baby units with the same highest fitness, pick randomly from them to be the new mother unit. Repeat this with the new mother unit. Each baby unit being taught and misunderstand their teaching. In our example, if any baby units have completed the goal, we stop and record their string (or dna) to reuse forever. This can be modified to teach a bird to fly to the other side of the screen with obstacles or any other example such as creating walking stickfigures, or other things that you would do with Machine Learning.
