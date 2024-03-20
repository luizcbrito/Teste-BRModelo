# Teste-BRModelo

---

**Projeto: Sistema de Gerenciamento de Biblioteca**

---

### Requisitos Mínimos:

Para atender aos requisitos mínimos do projeto, foram definidas as seguintes entidades:

- **Livro:** Representa as obras disponíveis na biblioteca.
- **Autor:** Responsável pela criação das obras.
- **Usuário:** Indivíduos que utilizam os serviços da biblioteca.
- **Empréstimo:** Registro de empréstimo de livros aos usuários.

É importante notar que a entidade **Usuário** possui uma especialização-generalização, com disjunção entre Aluno e Professor. Os atributos comuns a ambos, como Idade, Nome, Endereço, Turma e Data de Ingresso, são mantidos na entidade Usuário, enquanto os atributos específicos de Aluno e Professor são atribuídos às suas respectivas entidades.

### Entidades Adicionais:

Além dos requisitos mínimos, foram incluídas as seguintes entidades para melhorar a funcionalidade e usabilidade do sistema:

- **Avaliação:** Permite que os usuários deixem avaliações sobre os livros, facilitando a criação de funcionalidades de recomendação baseadas nas preferências dos usuários.
- **Funcionário:** Representa os colaboradores da biblioteca, com informações como nome, cargo e número de identificação.
- **Evento:** Para armazenar informações sobre eventos realizados na biblioteca, como sessões de leitura e palestras.
- **Editora:** Armazena informações sobre as editoras, como nome, localização e e-mail, permitindo distinguir a entidade responsável pela publicação do livro da entidade responsável pela autoria.
- **Categoria:** Define as categorias ou gêneros de livros, como ficção, não ficção, romance e mistério.

Este documento apresenta uma visão geral das entidades definidas no projeto "Sistema de Gerenciamento de Biblioteca" desenvolvido por [Luiz Claudio Brito Diniz da Silva].
