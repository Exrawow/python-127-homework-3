# Exercises

Create these files inside your own folder:
`submissions/<your-github-username>/`.

## exercise_1.py — Age category

Ask the user for their age with `input()`, cast it to `int`. Using
`if`/`elif`/`else`, print `"child"` if under 13, `"teen"` if 13-17, and
`"adult"` otherwise.

Example run (input is `15`):
```
How old are you?
15
teen
```

## exercise_2.py — Fix the bug

This code always prints `"Weekend!"`, even on a Monday. Copy it into
`exercise_2.py`, then fix the condition so it only matches Saturday or
Sunday.

```python
day = input("What day is it?\n").strip().lower()

if day == "saturday" or "sunday":   # BUG: fix this condition
    print("Weekend!")
else:
    print("Not the weekend.")
```

Expected output (for an input of `monday`):
```
What day is it?
monday
Not the weekend.
```

## exercise_3.py — Grade calculator

Ask the user for a score with `input()`, cast it to `int`. Using
`if`/`elif`/`else`, print the letter grade: `A` for 90 and above, `B`
for 80-89, `C` for 70-79, otherwise `F`.

Example run (input is `82`):
```
Enter your score:
82
Grade: B
```

## exercise_4.py — Comfortable temperature

Ask the user for a temperature with `input()`, cast it to `float`. Use
a chained comparison (`18 <= temperature <= 25`) to print `True` if
it's comfortable, `False` otherwise.

Example run (input is `22`):
```
Enter the temperature:
22
Comfortable: True
```

## exercise_5.py — Bonus: one-line status

Ask the user for their age with `input()`, cast it to `int`. Using a
one-line conditional expression (ternary), set `status` to `"adult"` if
`age >= 18` else `"minor"`, and print it.

Example run (input is `16`):
```
How old are you?
16
minor
```
