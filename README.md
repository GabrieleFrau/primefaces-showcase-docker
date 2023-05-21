run either commands
```
podman build -f Containerfile.Rocky -t showcase
podman build -f Containerfile.Ubuntu -t showcase
```
then create the container from the built image
```
podman run -p 8080:8080 showcase
```