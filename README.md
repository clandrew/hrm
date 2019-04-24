# Human Resource Machine Solutions
These are my solutions to the programming-themed game Human Resource Machine.

The solutions cover all levels.

Due to the open-endedness of the problem-solving aspects of this game, other people may have found found a solution that also works well, or may work better. All the same, these cover all size and speed optimizations plus some commentary about the approach. Enjoy.

## 1 - Mail Room
This is a tutorial level intended to get you acquainted with some commands.

```
01 🡆inbox

02 outbox🡆

03 🡆inbox

04 outbox🡆

05 🡆inbox

06 outbox🡆
```

## 2 - Busy Mail Room (size)
Another tutorial level where they teach you how to use the JUMP command. Using the JUMP will land you into the size optimization.

```
start:

01 🡆inbox

02 outbox🡆

03 jump start
```


## 2 - Busy Mail Room (speed)
You can use JUMP, but you don't have to. You can exploit the fact that the game will only send you a fixed number of inputs.

```
01 🡆inbox

02 outbox🡆

03 🡆inbox

04 outbox🡆

05 🡆inbox

06 outbox🡆

07 🡆inbox

08 outbox🡆

09 🡆inbox

10 outbox🡆
```
