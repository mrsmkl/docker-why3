# docker-why3

Instructions from https://gist.github.com/kobigurk/a6efa63ac60c9a412af765b507e4a7e3

```
docker build -t formal . 
docker run -ti --rm -e DISPLAY=$DISPLAY  -v /tmp/.X11-unix:/tmp/.X11-unix -v ~/formal_work:/work formal
```
See also https://github.com/cogumbreiro/why3-dockerfile
