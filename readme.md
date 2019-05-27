# Node.js Web on Docker

## 1. Build Docker Images

```bash=
docker build -t node-web-app .
```

## 2. Docker Run

```bash=
docker run -p 49160:8080 -d --name node-web-app node-web-app
```

## 3. Demo

```bash=
curl 127.0.0.1:49160
```