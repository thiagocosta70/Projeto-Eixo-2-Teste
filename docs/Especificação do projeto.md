# Especificações do Projeto

A partir da participação dos usuários descritos abaixo, através de entrevista, conseguimos definir os problemas e os pontos mais relevantes a serem tratados no projeto. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.

## Personas

As personas levantadas durante o processo de entendimento do problema são apresentadas nas Figuras seguintes.
<table>
     <tbody>
        <tr>
            <td colspan=1 rowspan=2><img src='img/Monalisa.png'  width="160" height="200"></td>
            <td colspan=2 rowspan=1><b>João</b></td>
        </tr>
       <tr>
            <td><b>idade: 42</b><br> <b>Ocupação</b>:<br> Proprietário de escritório de contabilidade</td>
            <td><b>Aplicativos</b>:<br>  * Instagram<br> * TikTok<br> * YouTube<br> * Pinterest<br></td>
        </tr>
        <tr>
            <td><b>Objetivos</b>:<br> Encontrar prestadores de serviços qualificados para limpeza de sua empresa<br></td>
           <td><b>Desafios</b>: <br> Falta de referências confiáveis<br> </td>
        </tr>
    </tbody>
</table>
<br>
<table>
     <tbody>
        <tr>
            <td colspan=1 rowspan=2 style="margin: auto;"><img src='img/Jasuscristo.png' width="160px" height="200px" ></td>
            <td colspan=2 rowspan=1><b>Maria</b></td>
        </tr>
       <tr>
            <td><b>idade: 32</b><br> <b>Ocupação</b>:<br> Dona de casa</td>
            <td><b>Aplicativos</b>:<br>  * Facebook<br> * LinkedIn<br> * TikTok<br> * Tinder<br></td>
        </tr>
        <tr>
            <td><b>Objetivos</b>:<br> Encontrar prestadores de serviços para realizar tarefas como, jardinagem e pequenas reformas<br></td>
             <td><b>Desafios</b>: <br> Dificuldade em comparar preços e disponibilidades de horário<br>
 </td>
        </tr>
    </tbody>
</table>
<br>
<table>
     <tbody>
        <tr>
            <td colspan=1 rowspan=2 style="margin: auto;"><img src='img/Jasuscristo.png' width="160px" height="200px" ></td>
            <td colspan=2 rowspan=1><b>Carlos</b></td>
        </tr>
       <tr>
            <td><b>idade: 29</b><br> <b>Ocupação</b>:<br> Pintor</td>
            <td><b>Aplicativos</b>:<br>  * Facebook<br> * LinkedIn<br> * TikTok<br> * Tinder<br></td>
        </tr>
        <tr>
            <td><b>Objetivos</b>:<br> Anunciar serviços, definir preços e horários que se ajustem a sua agenda<br></td>
             <td><b>Desafios</b>: <br> Atingir clientes potenciais e administrar uma agenda variável<br>
 </td>
        </tr>
    </tbody>
</table>

Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

A partir da compreensão do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários.

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|João | buscar prestadores para limpeza da empresa | agendar conforme disponibilidade |
|Maria | pesquisar e filtrar prestadores de serviço com base em localização, preço e avaliações | encontrar alguém confiável. |
|Carlos | Anunciar serviços técnicos, definir preços e horários | atender a demanda de acordo com minha agenda e maximizar minhas oportunidades de trabalho |
## Requisitos

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades de interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.

### Requisitos Funcionais
A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues.

|ID    | Descrição do Requisito | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O site permite cadastrar o usuário. | ALTA | 
|RF-002| O site deve oferecer ao usuário a página de Login para ser efetuado o acesso ao site.   | ALTA |
|RF-003| O site deve permitir busca por tipo de serviço | ALTO  |
|RF-004| O site deve oferecer painel de controle para usuários pessoas físicas e jurídicas visualizarem histórico de serviços e agendamentos futuros.   | MÉDIA |
|RF-005| O site deve oferecer painel de controle para os prestadores gerenciarem serviços, preços e horários.  | MÈDIA |
|RF-006| O site deve permitir aos usuários avaliarem os prestadores e deixar comentários | ALTA |

### Requisitos não Funcionais
A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.

|ID     | Descrição do Requisito |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deve ser publicado em um ambiente acessível publicamente na Internet | ALTA | 
|RNF-002| O site deverá ser responsivo, permitindo a visualização em um celular de forma adequada | ALTA | 
|RNF-003| O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge) | ALTA | 
|RNF-004| O sistema de identificação do usuário deve permitir recuperar senha em caso de esquecimento, mudar senha quando necessário e identificar quando o usuário está logado. | ALTA |
|RNF-004| O sistema deverá ter uma proteção de dados pessoais e informações de pagamento. | MÈDIA | 


## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 08/12/2024. |
|RE-02| O aplicativo deve utilizar as tecnologias básicas da Web no Frontend e Backend.      |
|RE-03| A equipe não pode subcontratar o desenvolvimento do trabalho.     |