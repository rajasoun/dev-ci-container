# dev-ci-container

Continuous Integration Container a.k.a ci-shell for vscode dev containers

Run 
```
docker run --rm -it --name ci-shell --hostname ci-shell -v "$(pwd):$(pwd)" -w "$(pwd)"  -v /var/run/docker.sock:/var/run/docker.sock  rajasoun/ci-shell
```
