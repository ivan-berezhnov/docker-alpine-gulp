Alpine Linux docker image with Gulp set up with "gulp" as entrypoint.

```bash
$ docker run --rm -it -v $(pwd):/data jimlei/alpine-gulp -v
```

#### Alias
Add to `~/.bashrc`
```bash
alias gulp='docker run --rm -it -v $(pwd):/data jimlei/alpine-gulp'
```

Load the changes
```bash
$ source ~/.bashrc
```

Usage
```bash
$ gulp -v
```
