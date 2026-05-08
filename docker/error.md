$ docker build -t ziglang/static-base:llvm15-$(uname -m)-1 . --build-arg ZIGVER=0.10.0-dev.4560+828735ac0
ERROR: Cannot connect to the Docker daemon at unix:///Users/ogawakiyoshi/.docker/run/docker.sock. Is the docker daemon running?

$ docker build -t ziglang/static-base:llvm15-$(uname -m)-1 . --build-arg ZIGVER=0.10.0-dev.4560+828735ac0
[+] Building 0.0s (2/2) FINISHED                           docker:desktop-linux
 => [internal] load build definition from Dockerfile                       0.0s
 => => transferring dockerfile: 2B                                         0.0s
 => [internal] load .dockerignore                                          0.0s
 => => transferring context: 2B                                            0.0s
ERROR: failed to solve: failed to read dockerfile: open /var/lib/docker/tmp/buildkit-mount2316917158/Dockerfile: no such file or directory
