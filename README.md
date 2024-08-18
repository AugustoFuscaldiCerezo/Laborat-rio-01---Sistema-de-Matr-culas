# Nome do projeto
Trabalho de Desenvolcimento de Software 2024/2

## Integrantes
* Augusto Fuscaldi Cerezo
* Filipe Faria Melo

## Orientadores
* Cristiano de Macêdo Neto



# Descrição do Sistema de Matrículas da Universidade

## Histórias de Usuário

### História de Usuário 1: Matricular-se em Disciplinas
**Como** aluno,  
**Quero** me matricular em até 4 disciplinas obrigatórias e em mais 2 disciplinas optativas durante o período de matrículas,  
**Para que** eu possa escolher as disciplinas que mais me interessam e avançar no meu curso.

**Critérios de Aceitação:**
- O sistema deve permitir que o aluno se matricule em no máximo 4 disciplinas obrigatórias e 2 optativas.
- O aluno deve receber uma confirmação da matrícula após a submissão.
- O aluno deve poder visualizar uma lista das disciplinas em que está matriculado.

---

### História de Usuário 2: Cancelar Matrícula
**Como** aluno,  
**Quero** cancelar matrículas feitas anteriormente durante o período de matrículas,  
**Para que** eu possa modificar minha escolha de disciplinas caso necessário.

**Critérios de Aceitação:**
- O sistema deve permitir que o aluno cancele matrículas em disciplinas até o final do período de matrículas.
- O aluno deve receber uma confirmação do cancelamento após a submissão.
- O sistema deve atualizar a lista de disciplinas em que o aluno está matriculado após o cancelamento.

---

### História de Usuário 3: Consultar Disciplinas Disponíveis
**Como** aluno,  
**Quero** consultar quais disciplinas estão disponíveis para matrícula,  
**Para que** eu possa tomar uma decisão informada sobre quais disciplinas me matricular.

**Critérios de Aceitação:**
- O sistema deve fornecer uma lista de disciplinas disponíveis para o semestre corrente.
- A lista deve incluir informações sobre o nome da disciplina, número de créditos e se a disciplina é obrigatória ou optativa.

---

### História de Usuário 4: Receber Notificação de Cobrança
**Como** sistema de matrículas,  
**Quero** notificar o sistema de cobranças sobre as disciplinas em que os alunos estão matriculados,  
**Para que** os alunos possam ser cobrados pelas disciplinas do semestre.

**Critérios de Aceitação:**
- O sistema deve enviar uma notificação ao sistema de cobranças após o período de matrículas se encerrar.
- A notificação deve incluir detalhes sobre as disciplinas em que cada aluno está matriculado.

---

### História de Usuário 5: Consultar Alunos Matriculados
**Como** professor,  
**Quero** consultar a lista de alunos matriculados em minhas disciplinas,  
**Para que** eu possa conhecer os alunos que estarão participando das minhas aulas.

**Critérios de Aceitação:**
- O sistema deve permitir que o professor acesse a lista de alunos matriculados em suas disciplinas.
- A lista deve incluir informações básicas dos alunos, como nome e número de matrícula.

---

### História de Usuário 6: Gerar Currículo do Semestre
**Como** secretário,  
**Quero** gerar o currículo para cada semestre,  
**Para que** as disciplinas e cursos estejam organizados e disponíveis para matrícula dos alunos.

**Critérios de Aceitação:**
- O sistema deve permitir que o secretário crie e atualize o currículo do semestre.
- O currículo deve incluir informações sobre todas as disciplinas oferecidas e seus respectivos detalhes.

---

### História de Usuário 7: Manter Informações de Disciplinas, Professores e Alunos
**Como** secretário,  
**Quero** manter as informações sobre disciplinas, professores e alunos,  
**Para que** os dados estejam sempre atualizados e corretos para o gerenciamento das matrículas.

**Critérios de Aceitação:**
- O sistema deve permitir que o secretário adicione, edite e exclua informações sobre disciplinas, professores e alunos.
- As alterações devem ser refletidas em tempo real no sistema.

---

### História de Usuário 8: Atualizar Status das Disciplinas
**Como** secretário,  
**Quero** atualizar o status das disciplinas (ativa ou cancelada) com base no número de matrículas,  
**Para que** o currículo do semestre reflita corretamente quais disciplinas estarão disponíveis.

**Critérios de Aceitação:**
- O sistema deve verificar o número de matrículas de cada disciplina ao final do período de matrículas.
- Disciplinas com menos de 3 alunos matriculados devem ser automaticamente canceladas.
- Disciplinas com 60 ou mais alunos matriculados devem ter as inscrições encerradas.

---
