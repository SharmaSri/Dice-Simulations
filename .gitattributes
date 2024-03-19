import random

def roll_dice(probability):
    return random.random() < probability

def simulate_dice():
    attempts = [(0.2, 6), (0.1, 4), (0.2, 1), (0.1, 2), (0.3, 5), (0.1, 3)]
    for attempt in attempts:
        probability, result = attempt
        if roll_dice(probability):
            return result
    return None

result = simulate_dice()
if result is not None:
    print("The dice rolled:", result)
else:
    print("No successful roll in three attempts.")
