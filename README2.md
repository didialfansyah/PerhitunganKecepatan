DECLAR VARIABLE speed = 20
DECLAR VARIABLE x
DECLAR VARIABLE count = 0

WHILE count < 1
    STORE VARIABLE x WITH INPUT NUMBER
    IF x > 0 AND x <= 4
        count += 1

IF x > 2 AND x < 4
    speed -= 5
ELSE IF x == 4
    speed -= 7
ELSE
    speed -= 2

DISPLAY speed