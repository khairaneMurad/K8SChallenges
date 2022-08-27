# challenge 3 imperative commands

## First create the vote namespace
k create ns vote

## create vote-deployment with the given specification 
k create deploy vote-deployment --image kodekloud/examplevotingapp_vote:before -n vote


