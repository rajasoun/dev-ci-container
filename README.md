# dev-ci-container

Continuous Integration Container a.k.a ci-shell for vscode dev containers

Run 
```
docker run --rm -it \
    --name ci-shell \
    --hostname ci-shell \
    -v "$(pwd):$(pwd)" \
    -v /var/run/docker.sock:/var/run/docker.sock  \
    -w "$(pwd)"  \
    rajasoun/ci-shell:latest
```
