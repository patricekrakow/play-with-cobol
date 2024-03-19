# Let's Play with COBOL

As usual, let's go to <https://killercoda.com/playgrounds/scenario/ubuntu> to get an Ubuntu machine (for 60 minutes).

```text
sudo apt-get update
```

```text
sudo apt-get install open-cobol -y
```

```text
vi hello.cbl
```

```cobol
IDENTIFICATION DIVISION. 
PROGRAM-ID. HELLO.
PROCEDURE DIVISION.
    DISPLAY "Hello World!".
END PROGRAM HELLO.
```

```text
cobc hello.cbl -free -x -o hello
```

```text
./hello
```

## References

* <https://monadical.com/posts/cobol.html>
