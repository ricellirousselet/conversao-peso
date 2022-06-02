## Building Conversao-Peso

#### Sobre a Aplicação

### Obtida por meio de fork do projeto do Desenvolvedor Fabricio Veronez
### URL do Projeto no GitHub ==> https://github.com/KubeDev/conversao-peso

- Aplicação usada para converter o peso em "Grama" para "Quilo" e vice-versa através de um frontend simples.
- Porta de execução: 80
- Escrita em C# ASP.NET Core.

## Docker

Caso queira não queira usar o Dockerfile oferecido nesse repositório você pode clonar o projeto e fazer seus próprios ajustes no Dockerfile e gerar sua imagem local.

$ ```git clone https://github.com/ricellirousselet/conversao-peso.git```

$ ```docker build -t <image-name> .```

#### Usando a aplicação "conversao-peso"

## Versão Latest (1)

$ ```docker run -d -p 80:80 --name conversao-peso ricellirousselet/conversao-peso:latest```

## Versão 1

$ ```docker run -d -p 80:80 --name conversao-peso ricellirousselet/conversao-peso:1```

## Acessando container "conversao-peso"

$ ```docker container exec -it conversao-peso /bin/sh```
