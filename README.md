# random-inspirational-messages

Printing out random inspirational messages.

### Build
```
docker build -t setkyar/random-inspirational-messages-fe:1.0.5 . --platform linux/amd64
```

### Run and Test

```
docker run -p 8080:8080 setkyar/random-inspirational-messages-fe:1.0.5
http://localhost:8080 # Check from browser
```

### Push

```
docker push setkyar/random-inspirational-messages-fe:1.0.5
```