# testRepo
Test Repository for IDEAS course

A live version is available [here](https://ageller.github.io/testRepo/).

Cool thing for our bash prompt:
* put this in your .bash_profile file:
```export PS1="[\u@\h:\W]\[\e[32m\]\$(git branch 2>/dev/null | grep '^*' | awk '{print \" (\"\$2\")\"}')\[\e[m\] \$ "```
