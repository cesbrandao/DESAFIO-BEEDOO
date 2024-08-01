# Desafio Beedoo | Analista de Qualidade de Software Júnior
Repositório referente à resolução do desafio para a vaga de Analista de Qualidade de Software Júnior da empresa Beedoo.

## User Story
Desenvolvimento das histórias de usuário refente ao módulo de **Cursos** da Beedoo.

>As histórias de usuário foram criadas com base nas funcionalidades de `Cadastrar curso`, `Listar cursos` e `Excluir curso`.

>Visando a futura implementação de diferentes perfis de acesso, como `Administrador`, `Instrutor` e `Aluno`, as histórias de usuário foram descritas para o perfil `Administrador`, no qual o usuário tem liberdade total na utilização do sistema. 

### Funcionalidades (*Features*)

#### 1.  Cadastrar curso
**Como** administrador do sistema, **quero** criar um novo curso **para** adicionar novos conteúdos educacionais à plataforma.

Critérios de Aceite:
- Acessível para usuários cadastrados do tipo `Administrador`.
- O usuário deve poder inserir todos os dados referentes ao curso (nome, descrição, instrutor, datas de início e fim, número de vagas, tipo de curso, etc.).
- O usuário deve ser notificado caso algum campo obrigatório não tenha sido preenchido de forma adequada.
- O usuário deve ser notificado após o curso ser cadastrado com sucesso.

---
#### 2.  Listar cursos
**Como** administrador do sistema, **quero** listar todos os cursos cadastrados na plataforma **para** visualizar e gerenciar o conteúdo disponível.

Critérios de Aceite:
- Acessível para usuários cadastrados do tipo `Administrador`.
- O usuário deve poder ver uma lista com todos os cursos e suas informações (nome, tipo, vagas, datas de início e fim, instrutor, etc.).
- O usuário deve poder filtrar e ordenar a lista de cursos por diferentes critérios (instrutor, tipo, datas de início e fim, etc.).
- O usuário deve poder excluir cursos diretamente da lista de cursos. 

---
#### 3.  Excluir cursos
**Como** administrador do sistema, **quero** excluir um curso **para** manter a plataforma livre de conteúdos desatualizados ou irrelevantes.

Critérios de Aceite:
- Acessível para usuários cadastrados do tipo "Administrador".
- O usuário deve poder excluir um curso da lista de cursos disponíveis.
- O usuário deve receber uma mensagem para confirmar a exclusão do curso.
- O usuário deve receber uma mensagem de sucesso após a exclusão do curso.      
- O curso deve ser removido permanentemente da plataforma.

---