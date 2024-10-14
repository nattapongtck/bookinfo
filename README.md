Code original from Opsta
https://github.com/opsta/bookinfo

In this project, I've remove authentication for mongodb (nodejs)

Be careful with directory permission for dockercompose/Dockerfile to read, docker is another user, not your user, you can use chmod o+r to file (such as script.sh in ratings databases directory)
