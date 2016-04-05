# Git image
This is an Ubuntu-based image containing Git. It can be used to clean a directory
or checkout code from version control. Therefore a local directory can be mapped
as ``/opt/git``. Example of git clean:
```sh
docker run --rm -v $(pwd):/opt/git bkpr/git clean
```
