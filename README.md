# jenkins-compose
Docker Compose for Jenkins Based Microservices Deployment

## Environment Variables 
### `DOCKER_TLS_VERIFY`
`0` or `1` indicating if TLS (Transport Layer Security) should be used. Note that if TLS is unfamiliar to you, think about https. (Default is `0` because who uses TLS in development).

### `DOCKER_CERT_PATH`
The path to the TLS certificate. 

### `DOCKER_HOST`
The name of the dind image. 