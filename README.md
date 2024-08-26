# Running Vite on nginx with a root path
This site hosts an app at root path `/my-app`

## Docker things
```bash
docker build -t vite-on-nginx .
docker run -p 8080:80 vite-on-nginx
```