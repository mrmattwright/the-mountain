# the-mountain

When maths meets the real world.

## Setup

This project uses [Rye](https://rye-up.com/) for Python dependency management.

### Install Rye

First, install Rye by following the [installation instructions](https://rye-up.com/guide/installation/).

### Install the packages

```bash
rye sync
```

## Probability

[Probs.ipynb](src/the_mountain/probs.ipynb)

This notebook explores the probability of rolling two dice, adding the numbers together then plotting the results. 

First though - start with paper! All you need is a pen and paper and 2 dice. Draw something up that looks like this:

![Dice](resources/img/how-to-start.png)

Now gets to rolling! 

We had a fun conversation about why certaing numbers kept coming up so we wrote the combinations down. Some numbers have more combinations than others! :) 

![Combinations](resources/img/part2.png)

Then you can run the notebook to simulate rolling the dice 100,000 times. 

If we want to explain why this happens a good source is [Normal Distribution](https://kids.kiddle.co/Normal_distribution)

> Many values follow a normal distribution. This is because of the central limit theorem, which says that if an event is the sum of identical but random events, it will be normally distributed. Some examples include:
> - Height
> - Test scores
> - Measurement errors
> - Light intensity (so-called Gaussian beams, as in laser light)
> - Intelligence is probably normally distributed. There is a problem with accurately defining or measuring it, though.
> - Insurance companies use normal distributions to model certain average cases.

### Extensions

A fun exercise is to see what happens if you use 3 dice (or more)?