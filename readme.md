I put this lil script in my path, and then I can ask for the word count of the last ten commit messages like:

```sh
git wc 10
```

Strong recommend starting with a small range lol. Add sort!

```sh
git wc 100 | sort --parallel 4
```

If the output is looking good, let's get the fans going!

```sh
git wc | sort --parallel 16
```
