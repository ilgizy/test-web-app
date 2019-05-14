
```
docker build -t test-web-app -f .\TestWebApp\Dockerfile .

docker run -d -p 7000:80 test-web-app
```
