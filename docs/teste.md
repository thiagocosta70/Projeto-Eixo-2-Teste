| Caso de teste 01   | CT 01 - Cadastro (Cliente/Prestador)                                                                                      |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Analisar se o sistema de cadastro está com o funcionamento esperado.                                                     |
| Ações esperadas    | 1- Exito ao entrar na área de cadastro (Cliente ou Prestador).<br> 2-Colocar os dados necessários para o cadastro.<br> 3- Salvar as informações cadastradas. |
| Critérios de êxito | A conta de um cliente ou prestador será criada.                                                                          |

<br>

| Notas dos avaliadores | Dificuldades encontradas | Sugestão de melhoria   |
| --------------------- | ------------------------ | ---------------------- |
| 1                     | Nenhuma dificuldade      | Está ótimo             |
| 2                     |                          |                        |
| 3                     | Muito Complicado         | Melhorar Intuitividade |

<br>

| Caso de teste 02   | CT 02 - Login                                                                                                             |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Analisar se o sistema de login está funcionando conforme esperado.                                                        |
| Ações esperadas    | 1- Entrar na área de login.<br> 2- Inserir as credenciais de acesso válidas.<br> 3- Acessar o sistema com sucesso.         |
| Critérios de êxito | O usuário é autenticado e direcionado para a área inicial de sua conta.                                                  |

<br>

| Notas dos avaliadores | Dificuldades encontradas | Sugestão de melhoria   |
| --------------------- | ------------------------ | ---------------------- |
| 1                     | Processo intuitivo       | Nenhuma melhoria       |
| 2                     | Mensagem de erro pouco clara | Melhorar feedback ao usuário |
| 3                     |                          |                        |

<br>

| Caso de teste 03   | CT 03 - Busca de Prestadores                                                                                              |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Verificar se a busca por prestadores está funcionando corretamente e com os filtros esperados.                           |
| Ações esperadas    | 1- Acessar a área de busca.<br> 2- Aplicar filtros como especialidade e localização.<br> 3- Visualizar os resultados correspondentes. |
| Critérios de êxito | Os resultados exibidos correspondem aos critérios de busca aplicados.                                                   |

<br>

| Notas dos avaliadores | Dificuldades encontradas | Sugestão de melhoria   |
| --------------------- | ------------------------ | ---------------------- |
| 1                     | Lentidão na busca        | Otimizar carregamento  |
| 2                     | Filtros pouco intuitivos | Melhorar design        |
| 3                     |                          |                        |
"""

| Caso de teste 04   | CT 04 - Agendamento de Serviços                                                                                              |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Analisar se o cliente consegue agendar um serviço com o prestador selecionado de forma eficiente e clara.                    |
| Ações esperadas    | 1- Acessar a área de agendamento.<br> 2- Escolher o prestador.<br> 3- Selecionar data e horário.<br> 4- Confirmar o agendamento. |
| Critérios de êxito | O serviço é agendado corretamente, e o cliente recebe confirmação.                                                           |

<br>

| Notas dos avaliadores | Dificuldades encontradas | Sugestão de melhoria   |
| --------------------- | ------------------------ | ---------------------- |
| 1                     | Nenhuma                  | Está ótimo             |
| 2                     | Dificuldade com horários | Melhorar a interface de escolha de horário |
| 3                     |                          |                        |

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

| Caso de teste 12   | CT 12 - Uso de Cupons Promocionais                                                                                          |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| Objetivo do teste  | Verificar se o cliente consegue aplicar cupons promocionais e obter descontos corretamente.                                 |
| Ações esperadas    | 1- Acessar a área de cupons.<br> 2- Inserir o código do cupom.<br> 3- Aplicar o cupom ao serviço.<br> 4- Verificar o desconto. |
| Critérios de êxito | O cupom é aplicado corretamente e o desconto é refletido no valor final do serviço.                                           |

<br>

| Notas dos avaliadores | Dificuldades encontradas | Sugestão de melhoria   |
| --------------------- | ------------------------ | ---------------------- |
| 1                     | Nenhuma                  | Está ótimo             |
| 2                     | Cupons não funcionam corretamente | Melhorar validação de cupons |
| 3                     |                          |                        |

