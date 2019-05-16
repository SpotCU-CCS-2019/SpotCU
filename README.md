# Humans are Main Culprit: Spotting Collusive Users Involved in Blackmarket Following Services

The repository contains the code and partial released dumps of the paper.

All the required functions are present in the repository.

## Requirements

- Python 2.7.x
To install the dependencies used in the code, you can use the __requirements.txt__ file as follows -

```
pip install -r requirements.txt
```

## Running the code
First `cd SpotCU` and then run: 

`bash prepare_and_test.sh`

## Motivation

![Alt text](Image/motivation.png?raw=true "Title")

Fake followers and collusive users, and their footprints: (a) Fake followers only follow blackmarket customers (synchronous); (b) Collusive users follow both blackmarket customers and genuine users (asynchronous); (c) Fake followers cause few noticeable spikes at outdegree distribution, whereas collusive and genuine users show multiple small spikes.

## t-SNE

![Alt text](Image/embedding10.png?raw=true "Title")

User projection in the two-dimensional embedding space. We use t-SNE plot to visualize the space. We randomly sample 200 collusive users and 200 genuine users for visualization.
