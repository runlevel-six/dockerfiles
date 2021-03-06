## fx

[fx][1] in a docker container. This is useful if you do not want to depend on having installed dependencies like fx to your CI node or if you are unable to install dependencies. It can also be used on your local machine.

### Usage

```
curl -s 'https://api.github.com/repos/jdkelley/dockerfiles/commits?per_page=1' | docker run --rm -i jdkelley/fx
```

### Deployed

This is deployed on [Docker Hub][2] and [GitHub Package Registry][3].


### NOTE

With this configuration, you don't get the useful functionality where you can click and expand the json. 

[//]: # "LINKS"

[1]: https://github.com/antonmedv/fx      "fx Source Code (GitHub)"
[2]: https://hub.docker.com/r/jdkelley/fx "jdkelley/fx"
[3]: https://github.com/jdkelley/dockerfiles/packages/39807 "Deployed on GitHub Package Registry"