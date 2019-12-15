## .Net Web Application Core With Dockerfile

Building and running:

```bash
docker build -t webapp .
docker run -d -p 8080:80 --name myapp webapp
```
