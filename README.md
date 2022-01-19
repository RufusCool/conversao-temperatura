# conversao-temperatura

Fork do projeto do Fabricio Veronez - Iniciativa Kubernetes, aula 1

# Comandos utilizados

- git clone https://github.com/RufusCool/conversao-temperatura.git
- docker build . -t rampss/conversao-temperatura:1.0
- docker image ls -a | grep conversao
- docker container ls -a
- npm install
- node server.js  / Teste local para subir a aplicação antes de inpacotar no container!
- docker container run -d -p 8080:8080 rampss/conversao-temperatura:1.0
- git status
- git add -A
- git commit -m 'New File Dockerfile'
- git push
- git status

# Ambiente utilizado

SO Ubuntu 20.04
