# Plano de Testes de Usabilidade

Os testes de usabilidade permitem avaliar a qualidade da interface com o usuário da aplicação interativa.

Um plano de teste de usabilidade deverá conter: o detalhamento dos objetivos (ou cenários) em função dos requisitos levantados/implementados, dos critérios que serão utilizados para a seleção dos participantes, dos procedimentos a serem adotados pelos condutores de teste (por exemplo: os testes serão presenciais ou remotos? o método será observação direta, medição ou avaliação?), dos dados a serem coletados (quantidade de cliques, número de erros, tempo etc.), da ordem de execução das tarefas e das etapas da sessão de teste, recursos demandados, métricas coletadas etc.

Para cada voluntário do teste, é fundamental coletar e apresentar todos os dados/métricas previamente definidos, mas não se esqueça: atendendo à LGPD (Lei Geral de Proteção de Dados), nenhum dado sensível, que permita identificar o voluntário, deverá ser apresentado.

Para analisar de maneira mais ampla a opinião das pessoas que testaram nosso produto, utilizamos o sistema de avaliação heurística que basicamente se baseia em algumas escalas.

| Escala   | Discriminação                                                                   |
| -------- | ------------------------------------------------------------------------------- |
| Nível 1: | Não é nescessariamente um problema de usabilidade.                              |
| Nível 2: | Problemas estéticos que possam ser temporariamente "ignoradas".                 |
| Nível 3: | Problema com grande nescessidade de conserto.                                   |
| Nível 4: | Problema com grande nivel de complexidade, só pode ser lançado após a correção. |

## Casos de Teste

| Caso de teste 01   | CT 01 - Cadastro (Cliente/Prestador)                                                                                                                          |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Analisar se o sistema de cadastro está com o funcionamento esperado.                                                                                          |
| Ações esperadas    | 1- Exito ao entrar na área de cadastro (Cliente ou Prestador).<br> 2-Colocar os dados nescessarios para o cadastro.<br> 3- Salvar as informações cadastradas. |
| Critérios de êxito | A conta de um cliente ou prestador será criada.                                                                                                               |

<br>

| Notas dos avaliadores | Dificuldades encontradas | Sugestão de melhoria   |
| --------------------- | ------------------------ | ---------------------- |
| 1                     | Nenhuma dificuldade      | Está ótimo             |
| 2                     |                          |                        |
| 3                     | Muito Complicado         | Melhorar Intuitividade |

<br>

| Caso de teste 02   | CT 02 - Login (Cliente/Prestador)                                                                                                          |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ |
| Objetivo do teste  | Analisar se o sistema de login está com o funcionamento esperado.                                                                          |
| Ações esperadas    | 1- Exito ao entrar na área de login(Cliente ou Prestador).<br> 2-Colocar os dados que anteriormente cadastrados.<br> 3- Acessar sua conta. |
| Critérios de êxito | Conseguir acessar a conta com sucesso.                                                                                                     |

<br>

| Notas dos avaliadores | Dificuldades encontradas        | Sugestão de melhoria                                  |
| --------------------- | ------------------------------- | ----------------------------------------------------- |
| 1                     | Nenhuma dificuldade             | Está ótimo                                            |
| 2                     |                                 |                                                       |
| 3                     | Dificuldade em inserir os dados | Melhorar a identificação das abas a serem preenchidas |

<br>

| Caso de teste 03   | CT 03 - Solicitação de serviços (Cliente)                                                                                                    |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Analisar se o cliente consegue solicitar serviços em nossa plataforma.                                                                       |
| Ações esperadas    | 1- Acessar a plataforma como cliente.<br> 2- Ir para a área de solicitação.<br> 3- Inserir o serviço.<br> 4- Clicar em "Enviar solicitação". |
| Critérios de êxito | O cliente conseguir solicitar o serviço desejado.                                                                                            |

<br>

| Notas dos avaliadores | Dificuldades encontradas           | Sugestão de melhoria                    |
| --------------------- | ---------------------------------- | --------------------------------------- |
| 1                     | Nenhuma dificuldade                | Está ótimo                              |
| 2                     |                                    |                                         |
| 3                     | Dificuldade em solicitar o serviço | Melhorar a forma de solicitar o serviço |

<br>

| Caso de teste 04   | CT 04 - Encontrar/Aceitar um Serviço (Prestador)                                                                                                                                        |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Analisar se o prestador consegue encontrar/aceitar serviços a serem realizados.                                                                                                         |
| Ações esperadas    | 1- Acessar a plataforma como prestador de serviços.<br> 2- Ir para a área dos serviços solicitados.<br> 3- Encontrar o serviço que deseja realizar.<br> 4- Clicar em "Aceitar Serviço". |
| Critérios de êxito | O Prestador conseguir encontrar e aceitar o serviço desejado.                                                                                                                           |

<br>

| Notas dos avaliadores | Dificuldades encontradas          | Sugestão de melhoria                              |
| --------------------- | --------------------------------- | ------------------------------------------------- |
| 1                     | Nenhuma dificuldade               | Está ótimo                                        |
| 2                     |                                   |                                                   |
| 3                     | Dificuldade em encontrar serviços | Melhorar a forma de encontrar o serviço desejado. |

<br>

| Caso de teste 05   | CT 05 - Pagamento Online                                                                                                    |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Verificar se o cliente consegue realizar o pagamento do serviço de forma segura e sem falhas.                               |
| Ações esperadas    | 1- Acessar a área de pagamento.<br> 2- Escolher o método de pagamento.<br> 3- Inserir dados de pagamento.<br> 4- Confirmar pagamento. |
| Critérios de êxito | O pagamento é processado corretamente, e o cliente recebe a confirmação do pagamento.                                       |

<br>

| Notas dos avaliadores | Dificuldades encontradas | Sugestão de melhoria   |
| --------------------- | ------------------------ | ---------------------- |
| 1                     | Nenhuma                  | Está ótimo             |
| 2                     | Erros de processamento   | Melhorar resposta do sistema |
| 3                     |                          |                        |

<br>

| Caso de teste 06   | CT 06 - Status do Serviço                                                                                                   |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Analisar se o cliente consegue verificar o status do serviço agendado de forma clara.                                       |
| Ações esperadas    | 1- Acessar a área de serviços.<br> 2- Visualizar o status do serviço agendado.                                              |
| Critérios de êxito | O status do serviço é mostrado corretamente, refletindo a situação atual do serviço.                                         |

<br>

| Notas dos avaliadores | Dificuldades encontradas | Sugestão de melhoria   |
| --------------------- | ------------------------ | ---------------------- |
| 1                     | Nenhuma                  | Está ótimo             |
| 2                     | Atraso na atualização    | Melhorar tempo de atualização do status |
| 3                     |                          |                        |

<br>

| Caso de teste 07   | CT 07 - Visualização de Demandas do Prestador                                                                               |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Verificar se o prestador consegue visualizar e organizar suas demandas de forma eficiente.                                   |
| Ações esperadas    | 1- Acessar a área de demandas.<br> 2- Visualizar as solicitações de serviços e horários disponíveis.<br> 3- Organizar a agenda. |
| Critérios de êxito | O prestador consegue visualizar e organizar suas demandas e horários de forma intuitiva.                                     |

<br>

| Notas dos avaliadores | Dificuldades encontradas | Sugestão de melhoria   |
| --------------------- | ------------------------ | ---------------------- |
| 1                     | Nenhuma                  | Está ótimo             |
| 2                     | Difícil organizar horários | Melhorar a interface de agendamento |
| 3                     |                          |                        |

<br>

| Caso de teste 08   | CT 08 - Avaliação do Serviço e Prestador                                                                                      |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Verificar se o cliente consegue avaliar o serviço e prestador após a conclusão do trabalho.                                    |
| Ações esperadas    | 1- Acessar a área de avaliações.<br> 2- Selecionar o prestador.<br> 3- Avaliar o serviço prestado.<br> 4- Enviar a avaliação.   |
| Critérios de êxito | A avaliação é registrada com sucesso e visível no perfil do prestador.                                                       |

<br>

| Notas dos avaliadores | Dificuldades encontradas | Sugestão de melhoria   |
| --------------------- | ------------------------ | ---------------------- |
| 1                     | Nenhuma                  | Está ótimo             |
| 2                     | Difícil encontrar a área de avaliação | Melhorar navegação para avaliações |
| 3                     |                          |                        |

<br>

| Caso de teste 09   | CT 09 - Filtro de Prestadores por Especialidade e Localização                                                                |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Verificar se o cliente consegue aplicar filtros para encontrar prestadores de serviço de acordo com a especialidade e localização. |
| Ações esperadas    | 1- Acessar a área de busca.<br> 2- Aplicar filtros de especialidade e localização.<br> 3- Visualizar a lista de prestadores.   |
| Critérios de êxito | Os prestadores exibidos correspondem corretamente aos filtros aplicados.                                                    |

<br>

| Notas dos avaliadores | Dificuldades encontradas | Sugestão de melhoria   |
| --------------------- | ------------------------ | ---------------------- |
| 1                     | Nenhuma                  | Está ótimo             |
| 2                     | Falta de especialidades   | Ampliar opções de filtro |
| 3                     |                          |                        |

<br>

| Caso de teste 10   | CT 10 - Comunicação via Chat                                                                                                 |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Verificar se a comunicação entre cliente e prestador através do chat integrado está funcionando corretamente.               |
| Ações esperadas    | 1- Acessar a área de chat.<br> 2- Iniciar a conversa com o prestador.<br> 3- Trocar mensagens.<br> 4- Enviar e receber mensagens. |
| Critérios de êxito | O cliente e o prestador podem se comunicar de forma eficiente e as mensagens são enviadas/recebidas corretamente.           |

<br>

| Notas dos avaliadores | Dificuldades encontradas | Sugestão de melhoria   |
| --------------------- | ------------------------ | ---------------------- |
| 1                     | Nenhuma                  | Está ótimo             |
| 2                     | Não aparece notificação de nova mensagem | Melhorar notificação de novas mensagens |
| 3                     |                          |                        |

<br>

| Caso de teste 11   | CT 11 - Edição de Perfil do Prestador                                                                                         |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Verificar se o prestador consegue editar seu perfil e os detalhes dos serviços oferecidos de forma clara e sem falhas.       |
| Ações esperadas    | 1- Acessar a área de perfil.<br> 2- Editar informações do perfil.<br> 3- Salvar alterações.                                   |
| Critérios de êxito | As alterações no perfil são salvas corretamente e refletidas na visualização do cliente.                                      |

<br>

| Notas dos avaliadores | Dificuldades encontradas | Sugestão de melhoria   |
| --------------------- | ------------------------ | ---------------------- |
| 1                     | Nenhuma                  | Está ótimo             |
| 2                     | Processo confuso         | Melhorar fluxo de edição |
| 3                     |                          |                        |

<br>



## Quais aspectos serão analisados após a conclusão do teste:

1. Entender se o usuário consegue navegar tranquilamente na plataforma.
2. Analisar os feedbacks das pessoas que testaram.
3. Entendimento das dificuldades encontradas.
4. Analisar o tempo gasto em nossa plataforma.