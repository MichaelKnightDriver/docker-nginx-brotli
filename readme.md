
![grafik](https://user-images.githubusercontent.com/98834074/158889529-686ed343-786d-4483-86b0-54d6607b3cb6.png)


# Docker Command

```diff
+ docker pull ghcr.io/michaelknightdriver/docker-nginx-brotli:latest
+ docker pull michaelknightdriver/docker-nginx-brotli:latest
```

# What is this?
This project is based on Alpine Linux, the official nginx image and an nginx module that provides static and dynamic brotli compression. [Brotli](https://github.com/google/brotli) and the [nginx brotli module ](https://github.com/google/ngx_brotli) are built by Google.

# How to use this image
As this project is based on the official [nginx image](https://hub.docker.com/_/nginx/) look for instructions there. In addition to the standard configuration directives, you'll be able to use the brotli module specific ones, see [here for official documentation](https://github.com/google/ngx_brotli#configuration-directives)

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FMichaelKnightDriver%2Fdocker-nginx-brotli%2F&count_bg=%232496ED&title_bg=%231F72A6&icon=docker.svg&icon_color=%23FFFFFF&title=hits&edge_flat=true)](https://hits.seeyoufarm.com)
