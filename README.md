# About

This container have the items necessary to run the vue-cli.

# Using this container

In your .bash_aliases file include:

```
alias vue='docker run -it --rm -v "$PWD":"$PWD" -w "$PWD"  -p 8080:8080 simonardejr/vue-cli vue'
```
