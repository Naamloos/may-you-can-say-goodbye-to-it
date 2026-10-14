# may-you-can-say-goodbye-to-it
Is my server down yet? - no

Add your Discord screenshots as `assets/1.png` and `assets/2.png`.

Start the page:

```sh
docker compose up -d --build
```

Open http://localhost:8080. Set `PORT` to change the published port.
Point your reverse proxy at this host on that port using HTTP. If your proxy
shares a Docker network with this service, use `web:80` instead.

The page can also be opened directly from `index.html`.
