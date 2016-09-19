![todo](images/todo.png)

- Introduction to GitLabCI
- Simple example
- Real world example

!SUB
Docker containers wrap up a piece of software in a complete filesystem that contains everything it needs to run: code, runtime, system tools, system libraries - anything you can install on a server. This guarantees that it will always run the same, regardless of the environment it is running in.
![docker](images/docker-logo.png)


!SUB
## Docker architecture
![architecture](images/architecture.jpg)

!SUB
### Dockerfile by example

```
FROM ubuntu

RUN apt-get install apache2

COPY index.html /var/www/html

```


!SUB
![gitlab](images/gitlab-logo.png)
- Projects, issues, review, merge on successful build
- Wiki, CI, Docker Registry andGitLab Pages
- In the cloud, on premise community annd enterprise edition


!SUB
## Gitlab builds
![runners](images/definitions.png)

!SUB
## Gitlab runners
![runners](images/runners.png)

!SLIDE
## Demo
![demo1](images/hello-world.jpg)


!SLIDE
## Real world example
![demo2](images/pipeline.png)


!SUB
## Real world example - enviroment
![demo2](images/ci-container.png)

!SUB
## Real world example - demo
![demo2](images/ci-container.png)



!SLIDE
## More real world
![example](images/apps.png)


!SUB
## More real world
![example](images/service.png)


!SLIDE
# Thanks

All sources are available on GitHub
- Slides<br>
  - `open http://codethebuild.github.io/slides/`
  - `git clone https://github.com/codethebuild/slides.git`
  - `docker run -d -p 80:80 npalm/codethebuild:nextbuild`
- CI / CD enviroment
  - `git clone https://github.com/codethebuild/cicd.git`
- Sample sources Java Spring Boot service
  - `git clone https://github.com/codethebuild/service.git`
