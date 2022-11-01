# nginx-lb-to-containers

Running locally

`cd app && docker build -t myapp . `

`docker run -p 9000:80 myapp`


`cd app && docker build -t myproxy . `

`docker run -p 80:80 myproxy`


Running Globally 

`docker-compose up `
