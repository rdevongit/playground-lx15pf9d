# Guess Number Game!

With random module we can easily play Guess The Number Game. Here we for using For loop syntax with simple if-else.
Happy Guessing!

```python runnable

from random import randint


number_to_guess = randint(0, 10)
n = int(input('Guess my number! '))
while n != number_to_guess:
    if n < number_to_guess:
        print('Too small!')
    else:
        print('Too big!')
    n = int(input('Try again: '))
print('Congratulation! You found it!')
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Python template](https://tech.io/select-repo/429)
