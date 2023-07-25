# Calculating Averages

## Advantage and Disadvantage

**Advantage** on a `d20` roll can be approximated as a `+5` on the result

**Disadvantage** on a `d20` roll can be approximated as a `-5` on the result

## Dice Roll Averaging

To quickly calculate the average of a dice roll:

1. Half the `dice-size`and add `0.5`
2. Multiply by the `dice-count`
3. Add the `modifier`

AKA: `average = (((dice-size/2) + 0.5) * dice-count) + modifier`

For example, in the roll `2d8+5`

```
dice-size = 8
dice-count = 2
modifier = 5
```

So the average is calculated with:

1. `(8/2) + 0.5 = 4.5`
2. `4.5 * 2 = 9`
3. `9 + 5 = 14`

The average of `2d8+5` is `14`

In a more complicated example:

```
3d8+4 + 5d6+1
= 13.5+4 + 17.5+1
= 36
```

Note: as with all statistics, this is not a fully representative picture.  Things like Standard Deviation can help build a better understanding of the value of your dice rolls.

The website [Anydice.com](www.anydice.com) can help graph and compare different dice rolls to better understand your rolls.