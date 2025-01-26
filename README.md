
### Para baixar a imagem já contruida no gitlab, e inicila em um conteiner do docker:
* 1 - docker pull registry.gitlab.com/israel_glixinski/docker_java_example_api:main
* 2 - docker run -d -p 8080:8080 registry.gitlab.com/israel_glixinski/docker_java_example_api:main
* 3 - http://localhost:8080/api/hello

### Endipoints uteis na API
* Swagger - http://localhost:8080/swagger-ui.html