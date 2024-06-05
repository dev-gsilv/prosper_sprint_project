# API REST de Produto | Prosper Tech Sprint

### Objetivos do programa
> Desenvolver habilidades em Java para
ajudar profissionais a ingressarem no mercado de trabalho. Cada 
trilha de aprendizado é individual, exclusiva e personalizada. [Saiba mais.](https://prospertechtalents.com/prosper-sprints/)

### Tecnologias utilizadas
- Java
- Spring Boot
- Postgres
- Docker

### Rodando localmente
1. Clone o repositório
```bash
git clone https://github.com/dev-gsilv/prosper_sprint_project.git
```
2. Navegue até a pasta do repositório local

```bash
cd prosper_sprint_project
```
3. Faça a build do container usando docker-compose

```bash
docker-compose up --build
```
4. Acesse a API em http://localhost:8080

> ⚠️ **Não tem docker-compose instalado?** Veja a documentação oficial [aqui.](https://docs.docker.com/compose/install/)

### Documentação de rotas

#### Criar produto

```http
  POST /api/produtos
```

#### Listar produtos

```http
  GET /api/produtos
```

#### Detalhar produto

```http
  GET /api/produtos/:id
```

#### Atualizar produto

```http
  PUT /api/produtos/:id
```

#### Remover produto

```http
  DELETE /api/produtos/:id
```

