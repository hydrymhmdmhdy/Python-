import random

boys = ["boy1", "boy2", "boy3", "boy4", "boy5", "boy6", "boy7", "boy8"]
girls = ["girl1", "girl2", "girl3", "girl4", "girl5", "girl6", "girl7", "girl8"]

random.shuffle(boys)
random.shuffle(girls)

paris = []
for i in range(len(boys)):
    paris.append((boys[i], girls[i]))

print("===random paris===")
for b, g in paris:
    print(f"{b} -> {g}")
