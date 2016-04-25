# gitree
`gitree` is a wrapper utility around tree created by Steve Baker et al. It
reads your `.gitignore` and excludes those paths from being listed in the
output of `tree`.

[![asciicast](https://asciinema.org/a/43532.png)](https://asciinema.org/a/43532)

## Installation
If you haven't already, first install [Git](https://git-scm.com/) and [Tree](http://mama.indstate.edu/users/ice/tree/index.html). Versions may be available from your package manager (apt-get, homebrew, etc).

Once the dependencies are taken care of, simply copy or link the `gitree` script file into your PATH.

    # Example: copy the script to /usr/local/bin
    cp gitree /usr/local/bin

