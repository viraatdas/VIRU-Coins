# VIRU Coins

A non-decentralized cryptocurrency that uses computational power for useful things

## Use case

1. Generate value

## What do we want

1. come up with an equivalent problem as solving hash problems
   1. potentially crowdsourcing untrained ML models and using this to award VIRUs
      1. Need to explore how to assign value based on complexity of the model (ex. memory footprint)
2. way to verify that the coin is authentic
   1. this would allow people to buy it
3. general way of buying/selling coins

## How to mine VIRUs

Not completely fleshed out

You train machine learning models and you get awarded VIRUs

## Simple Postgres db - for verification purpose

1. author
2. timestamp

## Exchanging VIRUs

## Rules for wanting to train ML models

Payment structure of some sort

- Do you charge them VIRUs
- Have a few initial untrained models and then whoever trains them successfully based on the criteria, gets VIRUs awarded

## Some problems

How do you get ML models to train?

For example, if you charge 1 VIRU to get the model but training the model gets 2 VIRU back, how do you prevent inflation?

- Use something like [Moss](https://theory.stanford.edu/~aiken/moss/) to make sure that there every model is sufficiently different
