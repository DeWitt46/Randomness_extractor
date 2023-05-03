# Randomness_extractor
Implementation of a "truly random" bit-string generator. It uses the randomness extractor from Quantinuum cryptomite package.
We take measurements from a n=2 qubit circuit (easily generalizable) with a simple error model (such that H_min is bounded). 
Otherwise we take measurements using a "certification protocol" based on Bell's inequalities (not so easy generalizable).

Started from the use-case solution proposed by my team, "Average Dodo enjoyers", at the ICTP-Quantinuum Hackathon.
