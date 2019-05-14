
```
docker build -t test-web-app -f .\TestWebApp\Dockerfile .

docker run -d -p 7000:80 test-web-app
```

http://localhost:7000/api-docs/index.html
