# 🧩 Padrões de Projeto com Spring Boot

Projeto desenvolvido para o desafio prático de Padrões de Projeto na plataforma **Digital Innovation One (DIO)**.

---

## 🎯 Objetivo

O objetivo deste projeto é demonstrar na prática a aplicação dos Padrões de Projeto mais comuns no ecossistema Spring:
* **Singleton:** Gerenciamento de componentes e injeção de dependências (`@Service`, `@Repository`, `@RestController`).
* **Strategy:** Organização e abstração de regras de negócio de clientes via interfaces (`ClienteService` / `ClienteServiceImpl`).
* **Facade:** Simplificação da integração com a API externa do ViaCEP utilizando OpenFeign (`@FeignClient`).

---

## 🛠️ Tecnologias Utilizadas

* **Java 17**
* **Spring Boot 3**
* **Spring Data JPA**
* **OpenFeign** (Integração com ViaCEP)
* **H2 Database** (Banco em memória)
* **SpringDoc OpenAPI / Swagger** (Documentação da API)

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/jpno/dio-lab-padroes-projeto-spring.git](https://github.com/jpno/dio-lab-padroes-projeto-spring.git)