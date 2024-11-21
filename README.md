
# DSList

A **DSList** é uma aplicação que permite aos usuários pesquisar informações sobre diferentes jogos, visualizar listas categorizadas e classificar os jogos com base em suas opiniões. 

## 🚀 Funcionalidades

- **Pesquisa de Jogos**: Encontre informações detalhadas sobre diversos títulos.
- **Listas de Jogos**: Navegue por categorias específicas.
- **Classificação Personalizada**: Organize os jogos de acordo com sua preferência.

---

## ⚙️ Configurações

### 📋 Requisitos

- **Java 17**
- **Maven**
- **PostgreSQL**

### 📂 Como rodar o projeto

1. Clone o repositório:
   ```bash
   git clone git@github.com:MauricioGoulartOliveira/dsList-backend.git && cd dslist
   
2.Execute a aplicação:
./mvnw spring-boot:run

3.Acesse a API no endereço:
http://localhost:8080

📌 Rotas da API

🎮 Jogos
GET /games: Retorna a lista completa de jogos.
GET /games/{id}: Retorna os detalhes de um jogo específico pelo ID.
📋 Listas de Jogos
GET /lists: Retorna as categorias das listas de jogos.
GET /lists/{id}/games: Retorna os jogos categorizados pelo ID da lista.
🔄 Organização Personalizada
POST /lists/{listId}/replacement: Permite reorganizar os jogos na lista com base na opinião do usuário.

📊 Diagrama de Arquitetura
O diagrama a seguir foi utilizado como base para a construção da API:

Diagrama:
![diagrama](https://github.com/user-attachments/assets/20f53d01-8fdb-4ff8-b284-737d96af353e)


🛠️ Tecnologias Utilizadas
Java 17
Spring Boot
PostgreSQL
Maven
🌟 Contribuições
Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

📄 Licença
Este projeto está sob a licença MIT.

Desenvolvido com 💻 por Maurício Goulart de Oliveira.

