#  Sistema de Cadastro de Funcionários (CRUD em Java)

Um sistema de gerenciamento de funcionários desenvolvido no console utilizando Java. O projeto foi construído para praticar conceitos fundamentais da **Programação Orientada a Objetos (POO)** e manipulação de coleções de dados.

---

##  Funcionalidades

- [x] **Cadastrar Funcionário:** Adiciona nome, idade e cargo de novos colaboradores.
- [x] **Listar Funcionários:** Exibe todos os cadastros ativos na memória.
- [x] **Remover Funcionário:** Apaga um cadastro com validação de índice para evitar erros de digitação.
- [x] **Menu Interativo:** Navegação contínua no console via laço `while`.

---

##  Tecnologias Utilizadas

- **Linguagem:** Java (JDK 17+)
- **IDE:** Eclipse IDE
- **Estrutura de Dados:** `ArrayList`
- **Entrada de Dados:** `Scanner`

---

##  Estrutura do Projeto

```text
src/
 ├── trabalho.pessoa/
 │    └── Pessoa.java        # Modelo da Entidade (Nome, Idade, Cargo)
 └── trabalho.cadastro/
      └── Cadastro.java      # Classe Principal com lógica do CRUD e Menu
