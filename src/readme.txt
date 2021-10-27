
Instruções:

01. executar o cd até chegar no diretório src

02. criar o arquivo Dockerfile
    abra o arquivo e verifique a explicação nos comentários

03. criar o arquivo .dockerignore

04. Executar o comando abaixo para criar a imagem no docker

    $ docker build -t zul9an9/conversao-temperatura:v1 .

05. Executar o comando abaixo para criar o container no docker

    $ docker run -d -p 8080:8080 --name conversao-temperatura zul9an9/conversao-temperatura:v1 

06. Acessar o aplicativo no browser 

    localhost:8080 
