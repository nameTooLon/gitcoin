# Gitcoin

Welcome to the wonderful world of Gitcoin!

## Overview

The balances are all contained in `LEDGER.txt`. We also have provided you with a sample Gitcoin mining script in `miner` -- you'll probably notice it's too slow to use in practice though. To win, you will probably need to optimise the code otherwise someone else will mine more gitcoins than you
 with their optimised code. 
 
If you make a really clever minig script or mining rig, please submit it to us. There will be between 0 and 10 bonus points handed out for the best mining systems after the completion of wargames.

Read the Wargames page for more information on what this task (worth 50 points) entails, but to summarise, the only commits that can be pushed are ones that:

- Increments an existing ledger entry by 1, or adds a new ledger entry
  with balance: 1; and
- Has a SHA1 lexicographically less than the value in `difficulty.txt`.

If you encounter an `ERROR`, your repo may be out of sync with the server. You should run `git reset --hard origin/master` to get your repo back to the server's state.

In some cases, we may decide to reset the gitcoin instance, at which point you'll have to run `git reset --hard origin/master` to reset your clone's state. We will announce when this is the case.

## Catalog

- `difficulty.txt`: A strict upper bound on valid Gitcoin SHA1 values.

- `miner`: A sample Gitcoin mining script.

- `LEDGER.txt`: The current Gitcoin balances.

- `README.md`: This file.

## This is a copy of the cloned repository set up by Pezz.
