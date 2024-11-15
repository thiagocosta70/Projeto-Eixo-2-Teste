# Programação de Funcionalidades

## Pré-requisitos

- [Especificação do Projeto](2-Especificação%20do%20Projeto.md)
- [Projeto de Interface](3-Projeto%20de%20Interface.md)
- [Metodologia](4-Metodologia.md)
- [Arquitetura da Solução](5-Arquitetura%20da%20Solução.md)

## Funcionalidades Implementadas

| ID    | Descrição do Requisito                                                                                                          | Artefatos Produzidos | Aluno(a) Responsável |
| ----- | ------------------------------------------------------------------------------------------------------------------------------- | -------------------- | -------------------- |
| RF-01 | A aplicação deve permitir que o usuário cadastre uma conta como cliente ou prestador de serviço.                                | src/ServiçoFacil/Controllers/CadastroController.cs            |     Ytallo Bruno                 |
| RF-02 | A aplicação deve permitir que o usuário faça login na sua conta.                                                                | src/ServiçoFacil/Controllers/LoginController.cs            |     Thiago Emanuel                 |
| RF-03 | A aplicação deve permitir que o cliente busque e visualize prestadores de serviços disponíveis.                                 | src/ServiçoFacil/Controllers/ServiçosController.cs            |    Laura Furtado                  |
| RF-04 | A aplicação deve permitir que o cliente agende serviços com os prestadores selecionados.                                        | src/ServiçoFacil/Controllers/AgendamentosController.cs            |   Laura Furtado                   |
| RF-05 | A aplicação deve permitir que o cliente realize o pagamento dos serviços de forma online.                                       | `A fazer`            |                      |
| RF-06 | A aplicação deve permitir que o cliente visualize o status de um serviço agendado.                                              | src/ServiçoFacil/Controllers/AgendamentoController.cs            |     Gabriel Roeder                 |
| RF-07 | A aplicação deve permitir que o prestador de serviço organize e visualize suas demandas e horários agendados.                   | src/ServiçoFacil/Controllers/MinhaAgendaController.cs            |    Gabriel Roeder                  |
| RF-08 | A aplicação deve permitir que o cliente avalie o serviço e o prestador após a conclusão do trabalho.                            | src/ServiçoFacil/Controllers/AvalicoesController.cs`            |    Gabriel Roeder                  |
| RF-09 | A aplicação deve permitir que o cliente filtre prestadores de serviço por especialidade e localização.                          | `A fazer`            |                      |
| RF-10 | A aplicação deve permitir que o cliente e o prestador de serviço mantenham uma comunicação direta através de um chat integrado. | `A fazer`            |                      |
| RF-11 | A aplicação deve permitir que o prestador de serviço edite seu perfil e detalhes dos serviços oferecidos.                       | src/ServiçoFacil/Controllers/PerfilPrestadorController.cs`            |     Laura Furtado                 |
| RF-12 | A aplicação deve permitir o uso de cupons promocionais e descontos em serviços selecionados.                                    | `A fazer`            |                      |

