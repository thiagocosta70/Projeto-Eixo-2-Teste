 # Registro de Testes de Software

| Caso de Teste      | CT-01 - Verificar o cadastro de usuários (Cliente ou Prestador)                                                                                |
|--------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados  |  RF-01: A aplicação deve permitir que o usuário cadastre uma conta como cliente ou prestador de serviço.                                    |
| Objetivo do Teste      | Verificar se o cadastro está sendo feito corretamente.            |
| Passos                 | 1. Navegar para a página de cadastro. 2. Selecionar o tipo de conta (cliente/prestador). 3. Preencher os campos obrigatórios. 4. Submeter o formulário.   |
| Critérios de Êxito     | O usuário deve ser cadastrado com sucesso e uma mensagem de confirmação deve ser exibida.  |
| Resultado Obtido   |   Sucesso. O sistema exibiu a mensagem de confirmação conforme esperado.         | 
| Responsável pela execução do caso de Teste   |   Laura Furtado Amaral   |         

## Registro de Cadastro com Sucesso - Cliente

![Teste 1 Sucesso]
<img src='cadcliente.gif'>

## Registro de Cadastro com Sucesso - Prestador

![Teste 1 Sucesso]
<img src='cadprestador.gif'>




| Caso de Teste      | CT-02: Verificar o login de usuários                                                                                 |
|--------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados  |  RF-02: A aplicação deve permitir que o usuário faça login na sua conta.                                    |
| Objetivo do Teste      | Verificar se o login está sendo feito corretamente.            |
| Passos                 | 1. Acessar a página Entrar. 2. Inserir e-mail e senha corretos. 3. Clicar em "Entrar".   |
| Critérios de Êxito     | O sistema deve permitir o login e redirecionar para o pagina Home.  | 
| Resultado Obtido   |   O usuário foi autenticado e redirecionado corretamente para a página "Home".         |
| Responsável pela execução do caso de Teste   |   Gabriel Roeder   |         


## Login do usuário com sucesso - Cliente

![Teste 2 Sucesso]
<img src='logincliente.gif'>

## Login do usuário com sucesso - Prestador

![Teste 2 Sucesso]
<img src='loginprest.gif'>

## Login do usuário sem sucesso - dados incorretos

![Teste 2 Sem Sucesso]
<img src='loginfailure.gif'>


| Caso de Teste      | CT-03: Busca e Visualização de Prestadores de Serviço                                                                                |
|--------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados  |  RF-03: A aplicação deve permitir que o cliente busque e visualize prestadores de serviços disponíveis.                                    |
| Objetivo do Teste      | Testar a busca por prestadores de serviços e exibição dos resultados.            |
| Passos                 | 1. Acessar a tela de busca de prestadores. 2. Buscar prestador . 3. Submeter e visualizar resultados.   |
| Critérios de Êxito     | O sistema deve exibir prestadores que correspondem aos critérios.  | 
| Resultado Obtido   |   A lista de prestadores foi exibida corretamente com base nos filtros aplicados.         |         
| Responsável pela execução do caso de Teste   |   Thiago Emanuel da Costa   |

## Busca e Visualização de Prestadores de Serviço 

![Teste 3 Sucesso]
<img src='buscaprestador.gif'>


| Caso de Teste      | CT-04: : Agendamento de Serviços                  |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados  | RF-04: A aplicação deve permitir que o cliente agende serviços com os prestadores selecionados.  |
| Objetivo do Teste      | Testar a funcionalidade de agendamento de serviços.                                                               |
| Passos                 | 1. Selecionar um prestador de serviços. 2.Escolher uma data e hora disponíveis. 3. Confirmar o agendamento.                                              |
| Critérios de Êxito     |   O agendamento deve ser registrado e confirmado com sucesso. | 
| Resultado Obtido   |   O agendamento foi concluído e o usuário recebeu a confirmação e os detalhes do serviço agendado.         |         
| Responsável pela execução do caso de Teste   |   Ytallo Bruno Canuto Guedes   |


## Agendamento de Serviços 
![Teste 4 Sucesso]
<img src='agendamento.gif'>



| Caso de Teste      | CT-05: Verificar a realização de pagamentos online                |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados  | RF-05:A aplicação deve permitir que o cliente realize o pagamento dos serviços de forma online.  |
| Objetivo do Teste      | Verificar o processo de pagamento online.                                                               |
| Passos                 | 1. Após agendar um serviço, proceder para a tela de pagamento. 2. Escolher um método de pagamento (cartão de crédito, débito, etc.). 3. Inserir informações de pagamento. 4. Confirmar o pagamento.                           |
| Critérios de Êxito     |   O pagamento deve ser processado com sucesso.  | 
| Resultado Obtido   |   O pagamento foi processado com sucesso e um recibo deve foi gerado.         |         
| Responsável pela execução do caso de Teste   |   Ytallo Bruno   |                                                      |                                      
              
## Realização de pagamentos online

![Teste 5 Sucesso]
<img src='status.gif'>

| Caso de Teste      | CT-06: Visualização do Status de Serviço Agendado                 |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados  | RF-06: A aplicação deve permitir que o cliente visualize o status de um serviço agendado.  |
| Objetivo do Teste      | Testar a funcionalidade de visualização de status de serviço.                                                               |
| Passos                 | 1. Após o agendamento, acessar o painel de status de serviços. 2. Verificar o status do serviço (pendente, em andamento, concluído).                           |
| Critérios de Êxito     |   O status do serviço deve ser atualizado corretamente conforme a progressão.  | 
| Resultado Obtido   |   O painel foi exibido corretamente e mostrou o status dos serviços agendados.         |         
| Responsável pela execução do caso de Teste   |   Sidney Gabriel Abreu Magalhães   |                                                      |                                      
              
## Visualização do Status de Serviço Agendado 

![Teste 6 Sucesso]
<img src='status.gif'>

| Caso de Teste      | CT-07: Organização e Visualização de Demandas pelo Prestador                 |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados  | RF-07: A aplicação deve permitir que o prestador de serviço organize e visualize suas demandas e horários agendados.  |
| Objetivo do Teste      | Verificar se o prestador consegue visualizar e organizar seus horários e demandas.                                                               |
| Passos                 | 1. O prestador acessa o painel de agendamentos. 2. Visualiza a lista de serviços agendados. 3. Reorganiza ou edita horários conforme necessário.                           |
| Critérios de Êxito     |   O prestador deve conseguir visualizar todos os agendamentos.  | 
| Resultado Obtido   |   O painel de agendamentos exibiu corretamente todos os serviços e alterações e reorganizações foram salvas com sucesso.         |         
| Responsável pela execução do caso de Teste   |   Laura Furtado   |                                                      |                                      
              
## Organização e Visualização de Demandas pelo Prestador 

![Teste 7 Sucesso]
<img src='status.gif'>

| Caso de Teste      | CT-08: Avaliação de Serviços e Prestadores                 |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados  | RF-08: A aplicação deve permitir que o cliente avalie o serviço e o prestador após a conclusão do trabalho.  |
| Objetivo do Teste      | Verificar se o cliente consegue avaliar o serviço prestado após sua conclusão.                                                               |
| Passos                 | 1. Após a conclusão de um serviço, acessar a funcionalidade de avaliação. 2. Inserir uma avaliação (nota e comentário). 3. Submeter a avaliação.                           |
| Critérios de Êxito     |  A avaliação deve ser salva e exibida corretamente.  | 
| Resultado Obtido   |   As avaliações (nota e comentário) foram salvas corretamente e exibidas no perfil do prestador.         |         
| Responsável pela execução do caso de Teste   |   Gabriel Roeder   |                                                      |                                      
              
## Avaliação de Serviços e Prestadores

![Teste 8 Sucesso]
<img src='status.gif'>

| Caso de Teste      | CT-09: Filtragem de Prestadores de Serviço                 |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados  | RF-09: A aplicação deve permitir que o cliente filtre prestadores de serviço por especialidade e localização.  |
| Objetivo do Teste      | Testar a funcionalidade de filtragem por especialidade e localização.                                                               |
| Passos                 | 1. Acessar a funcionalidade de busca com filtros. 2. Inserir parâmetros de filtro (especialidade, localização).3. Submeter a busca.                           |
| Critérios de Êxito     |  O sistema deve retornar prestadores que correspondem aos critérios definidos.  | 
| Resultado Obtido   |   Os prestadores retornados atenderam aos critérios definidos (especialidade e localização).         |         
| Responsável pela execução do caso de Teste   |   Thiago Emanuel   |                                                      |                                      
              
## Filtragem de Prestadores de Serviço 

![Teste 9 Sucesso]
<img src='status.gif'>

| Caso de Teste      | CT-10: Comunicação via Chat                 |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados  | RF-10: A aplicação deve permitir que o cliente e o prestador de serviço mantenham uma comunicação direta através de um chat integrado.  |
| Objetivo do Teste      | Testar a comunicação entre cliente e prestador via chat integrado.                                                               |
| Passos                 | 1. O cliente acessa a funcionalidade de chat. 2. Inicia uma conversa com o prestador. 3. Envia e recebe mensagens.                           |
| Critérios de Êxito     |  As mensagens devem ser entregues em tempo real.  | 
| Resultado Obtido   |   As mensagens foram entregues em tempo real em todas as interações.        |         
| Responsável pela execução do caso de Teste   |   Ytallo Bruno   |                                                      |                                      
              
## Comunicação via Chat 

![Teste 10 Sucesso]
<img src='status.gif'>

| Caso de Teste      | CT-11: Edição de Perfil do Prestador                 |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Requisitos Associados  | RF-11: A aplicação deve permitir que o prestador de serviço edite seu perfil e detalhes dos serviços oferecidos.  |
| Objetivo do Teste      | Verificar se o prestador consegue editar seu perfil e serviços.                                                               |
| Passos                 | 1. O prestador acessa a área de edição de perfil. 2. Modifica dados pessoais e detalhes dos serviços oferecidos. 3. Salva as alterações.                           |
| Critérios de Êxito     | O perfil do prestador deve ser atualizado corretamente.  | 
| Resultado Obtido   |   As alterações realizadas pelo prestador foram salvas corretamente.         |         
| Responsável pela execução do caso de Teste   |   Thiago Emanuel   |                                                      |                                      
              
## Edição de Perfil do Prestador 

![Teste 11 Sucesso]
<img src='status.gif'>


