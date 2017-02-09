# Docker - Shopware 5.1

Based on the [php-docker-boilerplate](https://github.com/webdevops/php-docker-boilerplate) we create a pre-built docker image on which you can build your environment.

Image contains:

 - Debian 8
 - PHP5.6 (including ionCube)
 - Nginx (with shopware optimized configuration)
 - Tag for recent shopware versions (5.1 branch only)

Use an image like e.g.:

	1drop/shopware-51:5.1.6

## Future improvements

- Install profiling tools for debug (Profiler, Clockwork)
- Include configuration respecting ENV variables (and document them)
