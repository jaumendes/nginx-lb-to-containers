# nginx-lb-to-containers

Running locally

`docker build -t myapp . `

`docker run -p 9000:80 myapp`


`docker build -t myproxy . `

`docker run -p 80:80 myproxy`


`cd nginx-lb-to-containers`
`docker-compose up `
