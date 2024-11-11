<a href="https://aws.amazon.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/aws-colored-dark.svg" width="36" height="36" alt="Amazon Web Services" />  <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/docker-colored.svg" width="36" height="36" alt="Docker" /></a>
# Projeto Fake Shop
## Objetivo
O objetivo do projeto é ser um pequeno e-commerce para ser usado como prova de conceito para o processo de deploy de uma aplicação em ambiente Kubernetes com pipeline CI/CD e monitoramento.

## Ideia do Projeto
Para o desenvolvimento do projeto, foi seguido as seguintes premissas:
- Containers para facilitar o deploy no Kubernetes
- O deploy da aplicação vai ser feito em um cluster no EKS da AWS
- Todo o processo de criação de release da aplicação e deploy no Kubernetes deve ser feito de forma automática
- A aplicação e o cluster devem ser monitorados 

## Tecnologias relacionadas
Vieram do Fork

- Python
- Flask
Feito depois do Fork

- Docker
- Kubernetes
- AWS
- Prometheus
- Grafana

## Configuração da Aplicação

A configuração da aplicação é feita usando variáveis de ambiente na aplicação e no banco de dados.

### Variáveis de Ambiente do PortgreSQL

As variáveis de ambiente do Postgre são detalhadas no Docker Hub:

https://hub.docker.com/_/postgres

### Variável de Ambiente da aplicação

DB_HOST => Host do banco de dados PostgreSQL.

DB_USER => Nome do usuário do banco de dados PostgreSQL.

DB_PASSWORD => Senha do usuário do banco de dados PostgreSQL.

DB_NAME => Nome do banco de dados PostgreSQL.

DB_PORT => Porta de conexão com o banco de dados PostgreSQL.
