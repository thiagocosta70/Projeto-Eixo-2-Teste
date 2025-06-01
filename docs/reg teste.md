# 📋 Registro de Testes de Software

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>, <a href="8-Plano de Testes de Software.md"> Plano de Testes de Software</a>

Relatório com as evidências dos testes de software realizados no sistema pela equipe, baseado em um plano de testes pré-definido.

---

## Caso de Teste      | CT-01 - Verificar o cadastro de usuários (Praticante ou Personal Trainer)

| Campo                             | Descrição                                                                                                                                 |
|----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados            | RF-01: A aplicação deve permitir que o usuário cadastre uma conta como praticante de musculação ou personal trainer.                     |
| Objetivo do Teste                | Verificar se o cadastro está sendo feito corretamente.                                                                                    |
| Passos                           | 1. Navegar para a página de cadastro. <br>2. Preencher os campos obrigatórios. <br>3. Selecionar o tipo de conta (praticante/personal) <br>4. Submeter o formulário. |
| Critérios de Êxito               | O usuário deve ser cadastrado com sucesso e uma mensagem de confirmação deve ser exibida.                                                 |
| Resultado Obtido                 | O sistema exibiu a mensagem de confirmação conforme esperado.                                                                             |
| Responsável pela execução        | Carolina Santos Félix                                                                                                                     |

<video controls src="/docs/cadastro.mp4" title="Cadastro"></video>
---

## Caso de Teste      | CT-02 - Verificar o login de usuários

| Campo                             | Descrição                                                                                                     |
|----------------------------------|---------------------------------------------------------------------------------------------------------------|
| Requisitos Associados            | RF-02: A aplicação deve permitir que o usuário faça login na sua conta.                                       |
| Objetivo do Teste                | Verificar se o login é efetuado com e-mail e senha válidos.                                                   |
| Passos                           | 1. Navegar para a tela de login. <br>2. Inserir e-mail e senha válidos. <br>3. Clicar em “Entrar”.             |
| Critérios de Êxito               | O sistema deve autenticar o usuário e redirecionar para a tela inicial.                                       |
| Resultado Obtido                 | O login foi realizado com sucesso e o redirecionamento funcionou conforme esperado.                           |
| Responsável pela execução        | Laura Furtado Amaral                                                                                          |


<video controls src="/docs/login.mp4" title="Login"></video>
---

## Caso de Teste      | CT-03 - Verificar o registro de treinos

| Campo                             | Descrição                                                                                                                           |
|----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados            | RF-03: A aplicação deve permitir que o praticante registre seus treinos, incluindo exercícios, séries, repetições e cargas.        |
| Objetivo do Teste                | Validar se os treinos podem ser registrados com todas as informações necessárias.                                                   |
| Passos                           | 1. Acessar a tela de treino. <br>2. Preencher os campos de exercício, séries, repetições e cargas. <br>3. Salvar o treino.          |
| Critérios de Êxito               | O treino deve ser salvo corretamente e armazenado para visualização futura.                                                         |
| Resultado Obtido                 | Os dados foram armazenados e exibidos no histórico corretamente.                                                                    |
| Responsável pela execução        | Gabriel Roeder                                                                                                                      |

<video controls src="/docs/criar treino.mp4" title="Registro"></video>
---

## Caso de Teste      | CT-04 - Verificar a visualização do histórico de treinos

| Campo                             | Descrição                                                                                                                 |
|----------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados            | RF-04: A aplicação deve permitir que o praticante visualize um histórico detalhado dos seus treinos.                      |
| Objetivo do Teste                | Verificar se o histórico exibe corretamente as informações dos treinos anteriores.                                         |
| Passos                           | 1. Acessar a tela de perfil. <br>2. Verificar se os dados dos treinos estão sendo listados com data, exercícios, etc. |
| Critérios de Êxito               | O histórico deve mostrar todos os treinos realizados com os dados corretos.                                               |
| Resultado Obtido                 | A listagem foi exibida com todos os dados conforme esperado.                                                             |
| Responsável pela execução        | Thiago Emanuel da Costa                                                                                                   |

<video controls src="/docs/historico.mp4" title="Histórico"></video>
---

## Caso de Teste      | CT-05 - Verificar exibição de gráficos e estatísticas

| Campo                             | Descrição                                                                                                                  |
|----------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados            | RF-05: A aplicação deve exibir gráficos e estatísticas sobre a evolução do usuário.                                       |
| Objetivo do Teste                | Verificar se os gráficos de evolução (tempo, volume e repetições) estão sendo exibidos corretamente por período.          |
| Passos                           | 1. Acessar a tela de estatísticas. <br>2. Selecionar o período desejado. <br>3. Verificar os gráficos gerados.             |
| Critérios de Êxito               | Os gráficos devem ser renderizados corretamente e refletir os dados reais do usuário conforme o período escolhido.        |
| Resultado Obtido                 | Os gráficos foram exibidos corretamente, com dados coerentes e navegação funcional entre períodos.                        |
| Responsável pela execução        | Thiago Emanul da Costa                                                                                                     |

<video controls src="/docs/estatisticas.mp4" title="Estatísticas"></video>

---

## Caso de Teste      | CT-06 - Verificar criação e reutilização de rotinas de treino

| Campo                             | Descrição                                                                                                               |
|----------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados            | RF-06: A aplicação deve permitir que o praticante crie e reutilize rotinas de treino personalizadas.                   |
| Objetivo do Teste                | Verificar se é possível criar rotinas personalizadas e reutilizá-las posteriormente.                                   |
| Passos                           | 1. Criar uma nova rotina de treino. <br>2. Salvar a rotina. <br>3. Aplicar a rotina a um novo treino.                  |
| Critérios de Êxito               | A rotina deve ser salva corretamente e aparecer como opção ao registrar novos treinos.                                 |
| Resultado Obtido                 | A rotina foi salva e reutilizada com sucesso.                                                                           |
| Responsável pela execução        | Ytallo Bruno Canuto Guedes                                                                                              |

<video controls src="/docs/realizar treino e salvar.mp4" title="Rotinas"></video>
---

## Caso de Teste      | CT-11 - Verificar edição de perfil do usuário

| Campo                             | Descrição                                                                                                           |
|----------------------------------|---------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados            | RF-11: A aplicação deve permitir que o usuário edite seu perfil e suas preferências de treino.                                  |
| Objetivo do Teste                | Verificar se é possível editar nome, peso, altura, foto e demais dados pessoais.                                         |
| Passos                           | 1. Acessar a tela de perfil. <br>2. Clicar no “Ícone de engrenagem”. <br>3. Alterar os dados desejados. <br>4. Salvar.   |
| Critérios de Êxito               | Os dados alterados devem ser atualizados corretamente e refletidos na tela de perfil com mensagem de confirmação. |
| Resultado Obtido                 | As edições foram realizadas com sucesso e os dados atualizados foram exibidos corretamente.                        |
| Responsável pela execução        | Carolina Santos Félix                                                                                              |

<video controls src="/docs/editar perfil.mp4" title="Perfil"></video>
---

## Caso de Teste      | CT-12 - Verificar exportação e compartilhamento de treinos

| Campo                             | Descrição                                                                                                                    |
|----------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados            | RF-12: A aplicação deve permitir a exportação e compartilhamento dos treinos do usuário.                                           |
| Objetivo do Teste                | Verificar se é possível exportar e compartilhar os treinos .                         |
| Passos                           | 1. Acessar um treino salvo. <br>2. Selecionar a opção “Exportar/Compartilhar”. <br>|
| Critérios de Êxito               | O arquivo deve ser gerado corretamente .                                           |
| Resultado Obtido                 | O Id foi gerado e compartilhado sem erros pelos canais disponíveis.                                                         |
| Responsável pela execução        | Carolina Santos Félix                                                                          

<video controls src="/docs/exportar.mp4" title="Exportação"></video>