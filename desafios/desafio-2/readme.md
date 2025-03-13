# Desafio Bootcamp Decola Tech - Dio & Avanade 2025

## Descrição do Projeto
Este repositório contém o código-fonte e a documentação do projeto desenvolvido durante o Bootcamp Decola Tech, uma parceria entre a Digital Innovation One (DIO) e a Avanade. O objetivo deste desafio é criar uma aplicação robusta e escalável utilizando as principais tecnologias e ferramentas do mercado.

## Principais Tecnologias
- **Java 17**: Utilizaremos a versão LTS mais recente do Java para tirar vantagem das últimas inovações que essa linguagem robusta e amplamente utilizada oferece.
- **Spring Boot 3**: Trabalharemos com a mais nova versão do Spring Boot, que maximiza a produtividade do desenvolvedor por meio de sua poderosa premissa de autoconfiguração.
- **Spring Data JPA**: Exploraremos como essa ferramenta pode simplificar nossa camada de acesso aos dados, facilitando a integração com bancos de dados SQL.
- **OpenAPI (Swagger)**: Vamos criar uma documentação de API eficaz e fácil de entender usando a OpenAPI (Swagger), perfeitamente alinhada com a alta produtividade que o Spring Boot oferece.
- **Railway**: Facilita o deploy e monitoramento de nossas soluções na nuvem, além de oferecer diversos bancos de dados como serviço e pipelines de CI/CD.

---

## Funcionalidades da Aplicação

### 1. **Gestão de Tarefas (Tasks)**
- **Criação de Tarefas**: Permite aos usuários criar novas tarefas com título, descrição, data de criação e status.
- **Atualização de Tarefas**: Possibilita a edição de tarefas existentes, como alterar o título, descrição ou status.
- **Listagem de Tarefas**: Exibe todas as tarefas cadastradas, com opções de filtro por status (pendente, em andamento, concluída).
- **Exclusão de Tarefas**: Remove tarefas que não são mais necessárias.

### 2. **Gestão de Usuários**
- **Cadastro de Usuários**: Permite o registro de novos usuários com informações como nome, e-mail e senha.
- **Autenticação de Usuários**: Oferece um sistema de login seguro para autenticar usuários.
- **Atribuição de Tarefas**: Permite associar tarefas a usuários específicos.

### 3. **Documentação da API com Swagger**
- **Documentação Automática**: Gera automaticamente uma documentação interativa da API utilizando OpenAPI (Swagger).
- **Testes de Endpoints**: Permite testar os endpoints diretamente pela interface do Swagger.

### 4. **Integração com Banco de Dados**
- **Persistência de Dados**: Utiliza Spring Data JPA para persistir dados em um banco de dados SQL (MySQL, PostgreSQL ou H2 para testes).
- **Consultas Personalizadas**: Oferece métodos de consulta personalizados para filtrar e ordenar tarefas e usuários.

### 5. **Deploy na Nuvem com Railway**
- **CI/CD Integrado**: Configuração automática de pipelines de integração e deploy contínuo.
- **Monitoramento**: Facilita o monitoramento da aplicação em tempo real.
- **Escalabilidade**: Permite escalar a aplicação conforme a demanda.

### 6. **Validações e Tratamento de Erros**
- **Validação de Dados**: Valida entradas de usuários para garantir a integridade dos dados.
- **Tratamento de Exceções**: Oferece mensagens de erro claras e personalizadas para facilitar a depuração.

---

## Como Executar o Projeto

### Pré-requisitos
- Java 17 instalado
- Maven instalado
- Docker (opcional, para execução em contêineres)
- Conta no Railway para deploy na nuvem

### Clonando o Repositório
```bash
git clone https://github.com/digitalinnovationone/board.git
cd board