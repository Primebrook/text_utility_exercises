# Text Utility Exercises

This repo contains exercises to practice using some classic text CLI utilities, currently we have exercises for `awk` and `sed`.

### Usage

In each folder there is a `README.md` file which has the exercises. Each folder also contains an `expected_output/` directory which contains txt files of the expected output for each exercise. If you'd like to test the output of your solution with the expected output you can use the `diff` tool like so:

```terminal
COMMAND | diff - expected_output/1.txt
```

where `COMMAND` is your text utility program.


All solutions should only make use of the text utility in question e.g. all awk exercises should only use the `awk` tool.
