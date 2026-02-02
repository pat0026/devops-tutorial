```
docker build -t text-processor .
docker run --rm -v $(pwd):/data text-processor
```