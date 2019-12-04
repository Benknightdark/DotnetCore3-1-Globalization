# Usage
- docker build --rm  --no-cache -t webapplication1:latest .
- docker run --rm -it -p 4353:443/tcp -p 8053:80/tcp webapplication1:latest