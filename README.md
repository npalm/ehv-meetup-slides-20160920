# Code the build
The slides deck contains the slides for the talk at Ehv Developers meetup (20-09-2016).

- You can view the slides via GitHub static pages [here](http://npalm.github.io/ehv-meetup-slides-20160920).
- Or just run them in a conainter `docker run -p 80:80 npalm/ehv-meetup-slides:20160920`

## slides
For the slides we use the [RevealJS](https://github.com/hakimel/reveal.js/) framework.
- See index.html for the slide show composition
- See markdown/* for the slide sources.

### Run the slides from sources
- You can also run the slides locally in a container from sources.
```
docker run -d -p 80:80 --name slides \
  -v ${PWD}:/usr/share/nginx/html nginx
```
- Or use docker-compose to avoid some issues with nginx when running docker in a VM using boot2docker
```
docker compuse up -d
```
- Open a browser [slides](http://localhost/)
