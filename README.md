# ReverseProxy
ReverseProxy in golang in docker

## Usage:
```
docker pull hmbsbige/reverseproxy
docker run -d -p 8888:8888 hmbsbige/reverseproxy
docker run -d -p 80:8888 -e "r=http://www.bige0.com" -e "l=0.0.0.0:8888" hmbsbige/reverseproxy
```
