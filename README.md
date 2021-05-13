# Dashboard Vendas
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/lisber42/projeto-sds3/blob/main/LICENSE)

## Sobre o Projecto

https://lisber-dsvendas.netlify.app/

Dashboard de vendas é uma aplicação web desenvolvida durante a 3ª edição da **Semana DevSuperior**, evento organizado pela [DevSuperior](https://devsuperior.com.br/  site da devSupeior)

Esta aplicação consiste em exibir um dashboard  com graficos e analisis de vendas, a partir de dados fornecidos por um back end construído com Spring Boot.


## Layout Tela inicial Web
![Web](https://github.com/lisber42/assets/blob/main/tela%20de%20acesso.PNG)


## Layout Dashboard 
![Web](https://github.com/lisber42/assets/blob/main/graficos.PNG)



## Modelo Conceitual
![DB](https://github.com/lisber42/assets/blob/main/sds3-mc.png)


## Padrão camadas utilizado
![](https://github.com/lisber42/assets/blob/main/camadas.png) 

## Tecnologias utilizadas
### Front End

- HTML / CSS / JS / TypeScript
- ReactJS
- Apex Charts

### Back End

- Java
- Spring Boot
- JPA / Hibernate
- Maven

### Implantação em produção

- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
- Pré-requisitos: Java 11

```bash
##clonar repositório
git clone https://github.com/lisber42/projeto-sds3.git

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
- Pré-requisitos: npm / yarn

```bash
# clonar repositório 
git clone https://github.com/lisber42/projeto-sds3.git

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Lisber Victores Pompa  
www.linkedin.com/in/lisbervictores
