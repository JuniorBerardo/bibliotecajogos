# 📚 Biblioteca de Jogos Pessoais

Projeto Full Stack desenvolvido como atividade prática, utilizando Spring Boot para o backend e Thymeleaf para o frontend. A aplicação permite gerenciar uma biblioteca de jogos pessoais, com funcionalidades de CRUD para jogos e categorias.

## ✨ Funcionalidades

- Cadastro, Leitura, Atualização e Deleção (CRUD) de Jogos.
- CRUD de Categorias.
- Tema Dark/Light com botão de alternância.
- Rodapé fixo com informações do desenvolvedor.

## 🛠️ Tecnologias Utilizadas

- **Backend:** Java 21, Spring Boot 3.3.x, Spring Web, Spring Data JPA
- **Frontend:** Thymeleaf, HTML5, CSS3, JavaScript
- **Banco de Dados:** H2 (para desenvolvimento local), PostgreSQL (para deploy)
- **Build:** Maven

---

## 🚀 Como Executar Localmente

**Requisitos:**
- JDK 21 ou superior
- Maven 3.9+

1. **Clone o repositório:**
   ```bash
 git clone https://github.com/JuniorBerardo/bibliotecajogos.git
cd bibliotecajogos
   cd bibliotecajogos-pessoais
   ```

2. **Execute a aplicação com o Maven Wrapper:**
   ```bash
   ./mvnw spring-boot:run
   ```

3. **Acesse no seu navegador:**
   [http://localhost:8080](http://localhost:8080)

---

## ☁️ Deploy (Render + Neon)

- **Link da Aplicação no Render:** `https://bibliotecajogos-SeuNomeSobrenome.onrender.com`
- **Banco de dados:** O deploy foi configurado para usar um banco de dados PostgreSQL hospedado no Neon. As variáveis de ambiente no Render (`SPRING_DATASOURCE_URL`, `SPRING_DATASOURCE_USERNAME`, `SPRING_DATASOURCE_PASSWORD`) foram configuradas para conectar à instância do Neon.

---

## 👨‍💻 Desenvolvedor

- **Nome:** [Junior Ivair Berardo]
- **GitHub:** [https://github.com/JuniorBerardo/]
