Dice Rolling System with Probability Calculator
Overview

This Python program simulates rolling any number of dice with any number of sides, displays the outcomes, and calculates the exact probability of that specific outcome occurring.
Features

    Flexible dice configuration: Roll any number of dice with any number of sides

    Detailed results display:

        Individual die outcomes

        Total sum of all dice

    Probability calculation:

        Exact probability of the specific outcome

        "1 in X" probability format

    Accurate mathematics:

        Handles both single and multiple dice cases

        Accounts for all possible orderings (multinomial coefficient)

How It Works
Core Functions

    roll_dice(num_dice, num_sides)

        Generates random rolls for the specified dice configuration

        Returns a list of integers representing each die's result

    calculate_probability(outcomes, num_sides)

        Computes the exact probability of the specific outcome sequence

        Uses combinatorial mathematics to account for all possible orderings

        Handles duplicate values correctly

    factorial(n)

        Helper function for probability calculations

        Computes n! recursively
