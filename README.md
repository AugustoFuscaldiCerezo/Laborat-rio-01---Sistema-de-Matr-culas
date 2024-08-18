# Trabalho de Desenvolcimento de Software 2024/2
Descrição

## Integrantes
* Augusto Fuscaldi Cerezo
* Filipe Faria Melo

## Orientadores
* Cristiano de Macêdo Neto

## Histórias de Usuário

### História de Usuário, Aluno 1: Matricular-se em Disciplinas
**Como** aluno,  
**Quero** me matricular nas disciplinas obrigatórias e opitativas,  
**Para que** eu possa escolher as disciplinas que mais me interessam e avançar no meu curso.

**Critérios de Aceitação:**
- O sistema deve permitir que o aluno se matricule em no máximo 4 disciplinas obrigatórias e 2 optativas.
- O aluno deve receber uma confirmação da matrícula após a submissão.
- O aluno deve poder visualizar uma lista das disciplinas em que está matriculado.
- O sistema deverá aceitar matriculas apenas durante o período de matrícula.

---

### História de Usuário, Aluno 2: Cancelar Matrícula
**Como** aluno,  
**Quero** cancelar matrículas feitas durante o período de matrículas,
**Para que** eu possa modificar minha escolha de disciplinas caso necessário.

**Critérios de Aceitação:**
- O sistema deve permitir que o aluno cancele matrículas em disciplinas até o final do período de matrículas.
- O aluno deve receber uma confirmação do cancelamento após a submissão.
- O sistema deve atualizar a lista de disciplinas em que o aluno está matriculado após o cancelamento.

---

### História de Usuário, Aluno 3: Consultar Disciplinas Disponíveis
**Como** aluno,  
**Quero** consultar quais disciplinas estão disponíveis para matrícula,  
**Para que** eu possa tomar uma decisão informada sobre quais disciplinas me matricular.

**Critérios de Aceitação:**
- O sistema deve fornecer uma lista de disciplinas disponíveis para o semestre corrente.
- A lista deve incluir informações sobre o nome da disciplina, número de créditos e se a disciplina é obrigatória ou optativa.

---

### História de Usuário 4: Receber Notificação de Cobrança
**Como** aluno,  
**Quero** receber uma notificação sobre as cobranças das disciplinas em que estou matriculado.
**Para que** eu possa saber o quanto estou sendo cobrado e realizar o pagamento de forma rápida.

**Critérios de Aceitação:**
- O sistema de matrículas deve enviar uma notificação ao sistema de cobranças após o período de matrículas se encerrar.
- A notificação deve incluir detalhes sobre as disciplinas em que cada aluno está matriculado.

---

### História de Usuário, Professor 1: Consultar Alunos Matriculados
**Como** professor,  
**Quero** consultar a lista de alunos matriculados em minhas disciplinas,  
**Para que** eu possa conhecer os alunos que estarão participando das minhas aulas.

**Critérios de Aceitação:**
- O sistema deve permitir que o professor acesse a lista de alunos matriculados em suas disciplinas.
- A lista deve incluir informações básicas dos alunos, como nome e número de matrícula.

---

### História de Usuário, Secretário 1: Gerar Currículo do Semestre
**Como** secretário,  
**Quero** gerar o currículo para cada semestre,  
**Para que** as disciplinas e cursos estejam organizados e disponíveis para matrícula dos alunos.

**Critérios de Aceitação:**
- O sistema deve permitir que o secretário crie e atualize o currículo do semestre.
- O currículo deve incluir informações sobre todas as disciplinas oferecidas e seus respectivos detalhes.

---

### História de Usuário, Secretário 2: Manter Informações de Disciplinas, Professores e Alunos
**Como** secretário,  
**Quero** manter as informações sobre disciplinas, professores e alunos,  
**Para que** os dados estejam sempre atualizados e corretos para o gerenciamento das matrículas.

**Critérios de Aceitação:**
- O sistema deve permitir que o secretário adicione, edite e exclua informações sobre disciplinas, professores e alunos.
- As alterações devem ser refletidas em tempo real no sistema.

---

### História de Usuário, Secretário 3: Atualizar Status das Disciplinas
**Como** secretário,  
**Quero** atualizar o status das disciplinas (ativa ou cancelada) com base no número de matrículas,  
**Para que** o currículo do semestre reflita corretamente quais disciplinas estarão disponíveis.

**Critérios de Aceitação:**
- O sistema deve verificar o número de matrículas de cada disciplina ao final do período de matrículas.
- Disciplinas com menos de 3 alunos matriculados devem ser automaticamente canceladas.
- Disciplinas com 60 ou mais alunos matriculados devem ter as inscrições encerradas.

---
