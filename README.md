# forms.byallen.com

Easy local server:

```bash
docker run --rm -ti --name allen-forms -p '8088:80' -v $(pwd):/usr/share/nginx/html:ro -v $(pwd)/conf.d:/etc/nginx/conf.d:ro nginx:alpine
```
